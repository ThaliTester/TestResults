#### Test 92192157a7da9b2_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 18:25:16.955  3986  4243 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-03 18:25:17.042  3986  4243 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-03 18:25:17.422  5579  5579 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 18:25:17.428  5579  5579 D AndroidRuntime: CheckJNI is OFF
11-03 18:25:17.455  5579  5579 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 18:25:17.501  5579  5579 I Radio-JNI: register_android_hardware_Radio DONE
11-03 18:25:17.515  5579  5579 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 18:25:17.528   930  3606 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 18:25:17.547  5579  5579 D AndroidRuntime: Shutting down VM
11-03 18:25:17.554  3968  3985 W SearchService: Abort, client detached.
11-03 18:25:17.568  3968  3968 I HotwordDetector: Closing mic
11-03 18:25:17.568  3968  4235 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@587afbf
11-03 18:25:17.569  3968  4244 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 18:25:17.587   930   940 I ActivityManager: Start proc 5588:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 18:25:17.642   513  4246 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 18:25:17.643   513  4246 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 18:25:17.649   513  4246 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 18:25:17.649   513  4246 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 18:25:17.650   513  3004 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 18:25:17.652  3968  4241 I MicroRecognitionRnrImpl: Detection finished
11-03 18:25:17.652  3968  4237 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 18:25:17.694  5588  5588 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 18:25:17.720  5588  5588 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 18:25:17.791  5588  5588 I LibraryLoader: Time to load native libraries: 66 ms (timestamps 9451-9517)
,11-03 18:25:17.791  5588  5588 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 18:25:17.831  5588  5588 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dc38e}
,11-03 18:25:17.832  5588  5588 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 18:25:17.832  5588  5588 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 18:25:17.839  5588  5588 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 18:25:17.841  5588  5588 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 18:25:17.884  5588  5588 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 18:25:17.897  5588  5588 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 18:25:17.897  5588  5588 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 18:25:17.898  5588  5588 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 18:25:17.898  5588  5588 I Adreno  : Build Date                       : 12/06/15
11-03 18:25:17.898  5588  5588 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 18:25:17.898  5588  5588 I Adreno  : Local Branch                     : mybranch17112971
11-03 18:25:17.898  5588  5588 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 18:25:17.898  5588  5588 I Adreno  : Remote Branch                    : NONE
11-03 18:25:17.898  5588  5588 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 18:25:17.960   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e0dca91:true
,11-03 18:25:17.997  3856  3856 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[17575]" dev="sockfs" ino=17575 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:17.997  3856  3856 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[17575]" dev="sockfs" ino=17575 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.014  5588  5588 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 18:25:18.024  5588  5588 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 18:25:18.054   397   397 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32234]" dev="sockfs" ino=32234 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.054   397   397 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32234]" dev="sockfs" ino=32234 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 18:25:18.057  5588  5625 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 18:25:18.057   941   941 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[20246]" dev="sockfs" ino=20246 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.057   941   941 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[20246]" dev="sockfs" ino=20246 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.063  5588  5612 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 18:25:18.090  5588  5625 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 18:25:18.174  3836  3836 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33794]" dev="sockfs" ino=33794 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.174  3836  3836 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33794]" dev="sockfs" ino=33794 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.177   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +616ms
,11-03 18:25:18.174  3625  3625 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33793]" dev="sockfs" ino=33793 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.174  3625  3625 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33793]" dev="sockfs" ino=33793 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:18.180  3653  3653 I Keyboard.Facilitator: onFinishInput()
,11-03 18:25:18.220  5588  5588 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5588
,11-03 18:25:18.318  5588  5588 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 18:25:18.488  5588  5627 D jxcore_app_log: JniHelper::setJavaVM(0xf53bc000), pthread_self() = -562824912
,11-03 18:25:18.492  5588  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 18:25:18.492  5588  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 18:25:18.492  5588  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 18:25:18.492  5588  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 18:25:18.492  5588  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 18:25:18.492  5588  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6a77bd added. We now have 1 listener(s)
,11-03 18:25:18.495  5588  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 18:25:18.495  5588  5627 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:25:18.496  5588  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:25:18.496  5588  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-03 18:25:18.498  5588  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f829c80 added. We now have 1 listener(s)
11-03 18:25:18.498  5588  5627 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:25:18.503   930  2963 D WifiService: New client listening to asynchronous messages
,11-03 18:25:18.503  5588  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 18:25:18.503  5588  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-03 18:25:18.504  5588  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-03 18:25:18.504  5588  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 18:25:18.504  5588  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-03 18:25:18.504  5588  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-03 18:25:18.504  5588  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-03 18:25:18.505  5588  5627 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 18:25:18.657  5588  5588 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 18:25:19.000  5588  5597 I art     : Background sticky concurrent mark sweep GC freed 75617(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.472ms total 274.167ms
,11-03 18:25:20.375  5588  5597 I art     : Background partial concurrent mark sweep GC freed 54549(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 2.299ms total 285.277ms
,11-03 18:25:21.086  3589  3589 I ConfigService: onDestroy
,11-03 18:25:21.690  5588  5636 W jxcore-log: Initializing JXcore engine
11-03 18:25:21.690  5588  5636 W jxcore-log: JXcore engine is ready
,11-03 18:25:21.740  5636  5636 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11592 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 18:25:21.740  5636  5636 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14465]" dev="sockfs" ino=14465 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 18:25:21.740  5636  5636 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-03 18:25:21.740  5636  5636 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32202]" dev="sockfs" ino=32202 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 18:25:21.761  5588  5636 W jxcore-log: Starting JXcore engine
,11-03 18:25:21.824  5588  5636 W jxcore-log: Platform android
11-03 18:25:21.824  5588  5636 W jxcore-log: 
,11-03 18:25:21.824  5588  5636 W jxcore-log: Process ARCH arm
11-03 18:25:21.824  5588  5636 W jxcore-log: 
,11-03 18:25:22.000  5588  5636 I jxcore-log: JXcore Cordova bridge is ready!
11-03 18:25:22.000  5588  5636 I jxcore-log: 
11-03 18:25:22.000  5588  5636 W jxcore-log: JXcore engine is started
,11-03 18:25:22.012  5588  5627 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-03 18:25:22.018  5588  5588 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 18:25:22.573   930  3705 I ActivityManager: Killing 5233:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 18:25:27.825   930  2963 D WifiService: New client listening to asynchronous messages
,11-03 18:25:27.828  3968  5637 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 18:25:30.681  4894  4927 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 18:25:30.683  4894  4894 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 18:25:31.779  5588  5636 I jxcore-log: 2016-11-03 17:25:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 18:25:31.779  5588  5636 I jxcore-log: 
,11-03 18:25:31.781  5588  5636 I jxcore-log: 2016-11-03 17:25:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 18:25:31.781  5588  5636 I jxcore-log: 
,11-03 18:25:31.785  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 18:25:31.785  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 18:25:31.786  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 18:25:31.787  5588  5636 I jxcore-log: 2016-11-03 17:25:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 18:25:31.787  5588  5636 I jxcore-log: 
,11-03 18:25:31.789  5588  5636 I jxcore-log: 2016-11-03 17:25:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 18:25:31.789  5588  5636 I jxcore-log: 
,11-03 18:25:32.040  5588  5636 I jxcore-log: 2016-11-03 17:25:32 - DEBUG UnitTest_app: 'Running unit tests'
11-03 18:25:32.040  5588  5636 I jxcore-log: 
,11-03 18:25:32.041  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:25:32.041  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba522e added. We now have 2 listener(s)
11-03 18:25:32.042  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:25:32.042  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:25:32.042  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 18:25:32.042  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:25:32.042  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf331cf added. We now have 2 listener(s)
11-03 18:25:32.042  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:25:32.043  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 18:25:32.044  5588  5636 D executeNativeTests: Running unit tests
,11-03 18:25:32.078  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 18:25:32.078  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c added. We now have 3 listener(s)
11-03 18:25:32.079  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:25:32.079  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:25:32.079  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 18:25:32.079  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 18:25:32.079  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 added. We now have 3 listener(s)
,11-03 18:25:32.079  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:25:32.080  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 18:25:32.081  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 18:25:32.081  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 18:25:32.081  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 18:25:32.082  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 18:25:32.082  5588  5636 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 18:25:32.082  5588  5636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 18:25:32.082  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 18:25:32.082  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 18:25:32.082  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 18:25:32.082  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 18:25:32.083  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:32.083  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:32.083  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 18:25:32.083  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:32.083  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:25:32.083  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:25:32.084  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c removed from the list
11-03 18:25:32.084  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:25:32.084  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 removed from the list
11-03 18:25:32.084  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:32.084  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.085  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.085  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.085  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:32.085  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:32.085  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:32.085  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:32.085  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:32.086  5588  5636 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 18:25:32.086  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:32.086  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:32.086  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:32.086  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:32.086  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:32.086  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:32.086  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:32.086  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:32.086  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:32.086  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:32.087  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.087  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.087  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.087  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:32.087  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:32.087  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:32.087  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:32.089  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 18:25:32.090  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-03 18:25:32.090  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:32.090  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:32.090  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:32.091  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:32.091  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:25:32.091  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:32.091  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:32.091  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:32.091  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:32.091  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:32.091  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.091  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.091  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.091  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:32.091  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:32.091  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:32.091  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:32.092  5588  5636 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 18:25:32.093  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:25:32.093  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 18:25:32.101  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 18:25:32.101  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 18:25:32.101  5588  5636 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 18:25:32.102  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:25:32.102  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 18:25:32.102  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 18:25:32.102  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:25:32.102  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 18:25:32.106  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 18:25:32.107  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 18:25:32.107  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 18:25:32.107  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:25:32.112  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:25:32.113  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.113  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 18:25:32.114  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 18:25:32.114  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 18:25:32.114  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 18:25:32.115  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-03 18:25:32.116  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-03 18:25:32.116  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.116  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 18:25:32.116  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 18:25:32.116  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 18:25:32.117  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 18:25:32.117  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.118  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:32.119  4674  4886 D BtGatt.GattService: registerClient() - UUID=4223d61e-8e5c-4a11-a3ff-143fea994aaa
11-03 18:25:32.120  4674  4734 D BtGatt.GattService: onClientRegistered() - UUID=4223d61e-8e5c-4a11-a3ff-143fea994aaa, clientIf=5
11-03 18:25:32.121  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 18:25:32.122  4674  4687 D BtGatt.GattService: start scan with filters
11-03 18:25:32.128  4674  4737 D BtGatt.ScanManager: handling starting scan
11-03 18:25:32.129  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 18:25:32.129  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.129  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 18:25:32.129  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.129  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 18:25:32.129  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 18:25:32.129  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.130  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 18:25:32.130  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 18:25:32.130  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.130  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 18:25:32.130  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.130  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.130  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 18:25:32.130  4674  4737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:25:32.130  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.131  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.131  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:32.131  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.131  5588  5636 I io.jxcore.node.ConnectionHelper: start: OK
11-03 18:25:32.135  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.136  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:25:32.136  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.136  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.136  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:25:32.137  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:25:32.139  4674  4734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 18:25:32.139  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:32.140  4674  4737 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 18:25:32.147  4674  4734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 18:25:32.147  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:32.147  4674  4737 D BtGatt.ScanManager: Starting BLE batch scan
11-03 18:25:32.148  4674  4737 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 18:25:32.160  4674  4734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 18:25:32.161  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:32.168  4674  4734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 18:25:32.169  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:32.639  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-03 18:25:32.640  5588  5588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 18:25:32.640  5588  5588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 18:25:32.855   930  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 18:25:35.909   930  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 18:25:37.139  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:37.139  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:37.139  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 18:25:37.139  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:25:37.139  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 18:25:37.139  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:25:37.139  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 18:25:37.140  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:25:37.140  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 18:25:37.140  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 18:25:37.140  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.140  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.141  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:37.141  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 18:25:37.141  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.142  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:37.142  4674  4886 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 18:25:37.142  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 18:25:37.143  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:37.144  4674  4686 D BtGatt.GattService: stopScan() - queue size =1
,11-03 18:25:37.144  4674  4737 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 18:25:37.145  4674  4886 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 18:25:37.145  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 18:25:37.145  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.145  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 18:25:37.145  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:37.145  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:37.146  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 18:25:37.147  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 18:25:37.147  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:25:37.148  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.149  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.149  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:25:37.149  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.149  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:37.149  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:37.149  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:25:37.149  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:25:37.149  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:37.149  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:25:37.150  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:37.150  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:37.150  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:37.150  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:37.150  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:25:37.150  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 18:25:37.150  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 18:25:37.150  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.152  4674  4674 D BtGatt.ScanManager: awakened up at time 108879
11-03 18:25:37.155   930  3836 I ActivityManager: Killing 5249:com.android.settings/1000 (adj 15): empty #17
,11-03 18:25:37.151  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 18:25:37.156  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 18:25:37.157  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.157  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.157  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 18:25:37.157  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.160  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 18:25:37.161  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.161  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.161  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:25:37.161  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 18:25:37.203  4674  4734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-03 18:25:37.203  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:37.203  4674  4734 D BtGatt.GattService: current time is 108930720511
,11-03 18:25:37.204  4674  4734 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 18:25:37.206  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 18:25:37.207  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 18:25:37.207  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 18:25:37.207  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 18:25:37.219  4674  4734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 18:25:37.219  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:37.219  4674  4737 D BtGatt.ScanManager: stopping BLe Batch
,11-03 18:25:37.229  4674  4734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 18:25:37.229  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:37.229  4674  4737 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:25:37.239  4674  4734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 18:25:37.240  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:37.665  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 18:25:41.651   594   594 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 18:25:41.652   594   594 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 18:25:42.192  5588  5636 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 18:25:42.200  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:25:42.201  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 18:25:42.214  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 18:25:42.219  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 18:25:42.220  5588  5636 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 18:25:42.220  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 18:25:42.220  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-03 18:25:42.220  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 18:25:42.221  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:25:42.221  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 18:25:42.225  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:25:42.227  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 18:25:42.228  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 18:25:42.228  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 18:25:42.231  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:25:42.235  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.235  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 18:25:42.236  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 18:25:42.237  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 18:25:42.237  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 18:25:42.241  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.241  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 18:25:42.242  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 18:25:42.242  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 18:25:42.242  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 18:25:42.242  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.243  5588  5636 D BluetoothAdapter: STATE_ON
,11-03 18:25:42.247  4674  4886 D BtGatt.GattService: registerClient() - UUID=09cfa5ff-a326-4546-9893-f2a1b172d406
11-03 18:25:42.248  4674  4734 D BtGatt.GattService: onClientRegistered() - UUID=09cfa5ff-a326-4546-9893-f2a1b172d406, clientIf=5
11-03 18:25:42.248  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 18:25:42.248  4674  4687 D BtGatt.GattService: start scan with filters
11-03 18:25:42.253  4674  4737 D BtGatt.ScanManager: handling starting scan
11-03 18:25:42.253  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 18:25:42.253  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.253  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 18:25:42.253  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.253  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 18:25:42.254  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 18:25:42.254  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.254  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 18:25:42.254  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 18:25:42.254  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.254  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-03 18:25:42.254  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 18:25:42.255  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 18:25:42.255  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.259  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.259  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:25:42.259  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.259  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.259  5588  5636 I io.jxcore.node.ConnectionHelper: start: OK
11-03 18:25:42.260  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.262  4674  4734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 18:25:42.262  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.263  4674  4737 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 18:25:42.265  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:42.266  5588  5636 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 18:25:42.266  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-03 18:25:42.266  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.266  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 18:25:42.266  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:25:42.266  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.266  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 18:25:42.266  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.266  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:42.266  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 18:25:42.266  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:25:42.266  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 18:25:42.267  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:25:42.267  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 18:25:42.268  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 18:25:42.268  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.269  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.269  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.269  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 18:25:42.269  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.270  5588  5636 D BluetoothAdapter: STATE_ON
,11-03 18:25:42.270  4674  4686 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 18:25:42.270  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 18:25:42.271  4674  4734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 18:25:42.271  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.271  4674  4737 D BtGatt.ScanManager: Starting BLE batch scan
11-03 18:25:42.271  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:42.272  4674  4737 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 18:25:42.272  4674  4687 D BtGatt.GattService: stopScan() - queue size =1
11-03 18:25:42.273  4674  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 18:25:42.274  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 18:25:42.274  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.274  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 18:25:42.274  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.274  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.274  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.275  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.275  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 18:25:42.275  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.275  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.275  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.275  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 18:25:42.275  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 18:25:42.276  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:25:42.276  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.277  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.278  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:25:42.278  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.278  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.278  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:42.278  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:42.278  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:25:42.278  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:42.278  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:25:42.278  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:42.278  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-03 18:25:42.278  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
,11-03 18:25:42.278  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.278  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:42.278  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:42.278  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 18:25:42.278  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:42.278  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 18:25:42.279  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 18:25:42.279  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.279  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.279  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 18:25:42.279  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.281  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 18:25:42.281  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.281  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.281  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.281  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:25:42.281  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.283  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.284  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.284  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.284  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:42.284  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:42.284  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:42.284  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:42.285  5588  5636 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 18:25:42.287  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:25:42.287  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 18:25:42.287  4674  4734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 18:25:42.287  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 18:25:42.294  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 18:25:42.294  4674  4734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 18:25:42.294  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:42.296  4674  4737 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:25:42.298  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 18:25:42.298  5588  5636 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 18:25:42.299  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:25:42.299  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 18:25:42.299  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 18:25:42.299  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:25:42.299  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 18:25:42.302  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:25:42.302  4674  4734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 18:25:42.303  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.305  4674  4734 E BtGatt.ContextMap: Context not found for ID 5
,11-03 18:25:42.306  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:25:42.306  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 18:25:42.306  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 18:25:42.306  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 18:25:42.310  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.310  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 18:25:42.311  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 18:25:42.311  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 18:25:42.311  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 18:25:42.311  4674  4734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 18:25:42.311  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.311  4674  4737 D BtGatt.ScanManager: stopping BLe Batch
,11-03 18:25:42.316  4674  4734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 18:25:42.316  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.316  4674  4737 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:25:42.317  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.317  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 18:25:42.317  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 18:25:42.317  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 18:25:42.317  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 18:25:42.317  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.318  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:42.321  4674  4686 D BtGatt.GattService: registerClient() - UUID=1126af12-8a93-46b7-aa65-d8767e150dd9
11-03 18:25:42.321  4674  4734 D BtGatt.GattService: onClientRegistered() - UUID=1126af12-8a93-46b7-aa65-d8767e150dd9, clientIf=5
11-03 18:25:42.321  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 18:25:42.322  4674  4886 D BtGatt.GattService: start scan with filters
11-03 18:25:42.322  4674  4734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 18:25:42.322  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:42.324  4674  4737 D BtGatt.ScanManager: handling starting scan
,11-03 18:25:42.325  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 18:25:42.325  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.325  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 18:25:42.326  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.326  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 18:25:42.326  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 18:25:42.326  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.326  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 18:25:42.326  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 18:25:42.326  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.326  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.326  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 18:25:42.328  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 18:25:42.328  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.330  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.330  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:25:42.331  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:42.331  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:42.331  4674  4734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 18:25:42.331  5588  5636 I io.jxcore.node.ConnectionHelper: start: OK
11-03 18:25:42.331  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.331  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 18:25:42.331  4674  4737 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 18:25:42.334  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.334  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 18:25:42.334  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.334  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:25:42.334  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 18:25:42.338  4674  4734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 18:25:42.338  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:42.338  4674  4737 D BtGatt.ScanManager: Starting BLE batch scan
11-03 18:25:42.338  4674  4737 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 18:25:42.347  4674  4734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 18:25:42.347  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:42.353  4674  4734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 18:25:42.353  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:42.838  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-03 18:25:42.838  5588  5588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 18:25:42.838  5588  5588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 18:25:43.951   930  5361 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:25:46.655   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:47.335  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:47.335  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:47.336  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 18:25:47.336  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 18:25:47.336  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 18:25:47.336  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:47.337  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 18:25:47.337  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:25:47.337  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 18:25:47.337  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 18:25:47.337  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.338  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.338  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.338  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 18:25:47.338  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.342  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:47.344  4674  4687 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 18:25:47.344  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 18:25:47.346  4674  4737 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 18:25:47.346  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:25:47.349  4674  4886 D BtGatt.GattService: stopScan() - queue size =1
11-03 18:25:47.351  4674  4687 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 18:25:47.352  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 18:25:47.352  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.352  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 18:25:47.353  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.353  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.354  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.354  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.354  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 18:25:47.354  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.355  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.356  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.356  4674  4674 D BtGatt.ScanManager: awakened up at time 119083
11-03 18:25:47.356  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 18:25:47.356  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 18:25:47.359  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:25:47.360  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:47.364  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.364  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:25:47.364  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.365  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:47.365  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:47.365  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:47.366  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 18:25:47.367  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.367  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 18:25:47.367  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-03 18:25:47.367  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.367  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.368  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 18:25:47.368  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.369  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.369  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.370  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.370  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:25:47.370  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 18:25:47.380  4674  4734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-03 18:25:47.380  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:47.380  4674  4734 D BtGatt.GattService: current time is 119107241191
,11-03 18:25:47.380  4674  4734 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 18:25:47.380  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 18:25:47.381  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 18:25:47.381  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 18:25:47.381  4674  4734 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 18:25:47.381  4674  4734 E BtGatt.ContextMap: Context not found for ID 5
,11-03 18:25:47.388  4674  4734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 18:25:47.388  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:47.388  4674  4737 D BtGatt.ScanManager: stopping BLe Batch
,11-03 18:25:47.395  4674  4734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 18:25:47.395  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:25:47.395  4674  4737 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:25:47.402  4674  4734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 18:25:47.402  4674  4734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:25:47.658   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:47.872  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 18:25:47.872  5588  5588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 18:25:47.873  5588  5588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 18:25:48.661   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:49.550   930  2956 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 18:25:49.663   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:50.667   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:51.670   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 18:25:52.369  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:52.370  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.370  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.370  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.371  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:25:52.371  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 18:25:52.371  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.371  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.371  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.372  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.372  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:25:52.372  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 18:25:52.380  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.383  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.384  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.384  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.384  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.384  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.384  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.384  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:52.386  5588  5636 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-03 18:25:52.389  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.389  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.389  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.389  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.390  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.390  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
,11-03 18:25:52.390  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.390  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.390  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.391  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.394  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.395  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.395  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.395  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.396  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.396  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.396  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:52.398  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 18:25:52.399  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:52.399  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.399  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.399  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 18:25:52.401  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.401  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.401  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.402  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.402  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:25:52.402  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.407  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.407  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.408  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.408  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.408  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.408  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.408  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:52.410  5588  5636 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 18:25:52.410  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:52.411  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.411  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.411  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.411  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.411  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.411  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:25:52.412  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.412  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.412  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.415  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.416  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.416  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.416  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 18:25:52.416  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.416  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:25:52.416  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:52.418  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 18:25:52.418  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.418  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.418  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 18:25:52.418  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.419  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.419  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.419  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.419  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.419  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.419  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.422  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.422  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.422  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.422  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.422  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.423  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.423  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.424  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 18:25:52.424  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 18:25:52.424  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 18:25:52.425  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-03 18:25:52.425  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 18:25:52.425  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 18:25:52.425  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 18:25:52.425  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 18:25:52.425  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 18:25:52.425  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.425  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.425  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 18:25:52.426  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.426  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.426  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.426  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.426  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.426  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.427  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.429  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.429  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.429  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.429  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.429  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.429  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.430  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.431  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 18:25:52.431  5588  5636 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 18:25:52.431  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-03 18:25:52.435  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 18:25:52.435  5588  5636 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-03 18:25:52.435  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 18:25:52.435  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 18:25:52.435  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-03 18:25:52.436  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 18:25:52.437  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 18:25:52.438  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-03 18:25:52.438  5588  5636 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 18:25:52.438  5588  5636 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-03 18:25:52.438  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 18:25:52.438  5588  5636 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 18:25:52.438  5588  5636 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-03 18:25:52.439  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 18:25:52.439  5588  5636 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 18:25:52.439  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-03 18:25:52.445  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-03 18:25:52.446  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,11-03 18:25:52.446  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-03 18:25:52.447  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-03 18:25:52.447  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-03 18:25:52.447  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-03 18:25:52.447  5588  5636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 18:25:52.448  5588  5636 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-03 18:25:52.448  5588  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-03 18:25:52.448  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-03 18:25:52.448  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-03 18:25:52.448  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-03 18:25:52.449  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.449  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.449  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.449  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.449  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.450  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-03 18:25:52.451  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.451  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.451  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.451  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.452  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.453  5588  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-03 18:25:52.453  5588  5649 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-03 18:25:52.453  5588  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-03 18:25:52.453  5588  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-03 18:25:52.454  5588  5649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:25:52.454  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.454  5588  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-03 18:25:52.454  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.454  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.454  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.454  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 18:25:52.454  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.454  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.455  5588  5636 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-03 18:25:52.454  4886  4886 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33868]" dev="sockfs" ino=33868 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 18:25:52.456  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.456  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.456  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.456  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.456  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.457  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.457  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.457  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:52.457  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.457  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.457  5588  5649 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-03 18:25:52.457  5588  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-03 18:25:52.457  5588  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,11-03 18:25:52.460  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.460  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.454  4886  4886 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33868]" dev="sockfs" ino=33868 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 18:25:52.460  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.460  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.460  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.461  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.461  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.461  5588  5636 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-03 18:25:52.462  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.462  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.462  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.462  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.462  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.462  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.462  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.462  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:52.462  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.463  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.465  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.465  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.465  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.465  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 18:25:52.465  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.465  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.465  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.466  5588  5636 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 18:25:52.466  5588  5636 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 18:25:52.467  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 18:25:52.467  5588  5636 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-03 18:25:52.467  5588  5636 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 18:25:52.467  5588  5636 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 18:25:52.467  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 18:25:52.467  5588  5636 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 18:25:52.467  5588  5636 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 18:25:52.467  5588  5636 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-03 18:25:52.467  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 18:25:52.467  5588  5636 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 18:25:52.467  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:52.467  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:52.467  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:52.467  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.468  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.468  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.468  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.468  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.468  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:52.468  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.470  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:52.470  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.470  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:52.470  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:52.470  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:52.470  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.470  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.471  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:52.471  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:52.471  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:52.471  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:52.471  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:52.471  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:25:56.674   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:57.241   930  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 18:25:57.474  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.475  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.475  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 18:25:57.475  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:57.476  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:57.476  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:57.476  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:57.477  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:57.477  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:57.477  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:57.477  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:57.477  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.477  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.478  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:25:57.478  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.482  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.483  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.483  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.483  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 18:25:57.483  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:57.483  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:25:57.484  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.487  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 18:25:57.488  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 18:25:57.488  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 18:25:57.494  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-03 18:25:57.495  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 18:25:57.496  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 18:25:57.496  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 18:25:57.496  5588  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 18:25:57.496  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-03 18:25:57.496  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 18:25:57.496  5588  5588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 18:25:57.497  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:57.497  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 18:25:57.497  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 18:25:57.497  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 18:25:57.497  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 18:25:57.498  5588  5651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:25:57.498  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 18:25:57.498  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 18:25:57.498  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
,11-03 18:25:57.498  5588  5588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 18:25:57.498  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.498  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:25:57.498  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 18:25:57.498  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 18:25:57.499  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.501  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.501  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:25:57.501  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.501  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.501  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.501  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:57.501  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:57.502  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:57.502  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:25:57.502  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:57.502  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:25:57.502  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:57.502  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 18:25:57.502  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:57.502  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.502  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.502  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:57.502  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.497  4886  4886 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31515]" dev="sockfs" ino=31515 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 18:25:57.497  4886  4886 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31515]" dev="sockfs" ino=31515 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 18:25:57.503  5588  5651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 18:25:57.503  5588  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 18:25:57.503  5588  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 18:25:57.504  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.504  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.504  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.504  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:57.504  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:57.504  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.504  5588  5588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 18:25:57.504  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.504  5588  5588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:25:57.506  5588  5636 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-03 18:25:57.506  5588  5636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-03 18:25:57.506  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 18:25:57.507  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 18:25:57.507  5588  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 18:25:57.507  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 18:25:57.507  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:57.507  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:57.507  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:57.507  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:25:57.507  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:57.507  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.507  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.508  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:57.508  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.511  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.512  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.512  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.512  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:57.512  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:57.512  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.512  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:57.521  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:57.521  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:25:57.521  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 18:25:57.521  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:57.521  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:57.521  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:57.521  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.521  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.522  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:57.522  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.524  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.524  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.524  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.524  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:57.524  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:57.524  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.524  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.525  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:25:57.525  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 18:25:57.525  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:25:57.525  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:25:57.525  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:25:57.525  5588  5636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b116f8c not in the list
11-03 18:25:57.525  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.525  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
11-03 18:25:57.525  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:25:57.526  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.527  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:25:57.528  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.528  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:25:57.528  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:25:57.528  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:25:57.528  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:25:57.528  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b156d5 not in the list
,11-03 18:25:57.530  5588  5636 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-03 18:25:57.530  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 18:25:57.530  5588  5636 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 18:25:57.530  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-03 18:25:57.530  5588  5636 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-03 18:25:57.530  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 18:25:57.532  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 18:25:57.532  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-03 18:25:57.532  5588  5636 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-03 18:25:57.532  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 18:25:57.533  5588  5636 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-03 18:25:57.533  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 18:25:57.533  5588  5636 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-03 18:25:57.533  5588  5636 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 18:25:57.533  5588  5636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-03 18:25:57.533  5588  5636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-03 18:25:57.534  5588  5636 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 18:25:57.534  5588  5636 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 18:25:57.534  5588  5636 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-03 18:25:57.534  5588  5636 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-03 18:25:57.535  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:25:57.535  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a7069a added. We now have 3 listener(s)
11-03 18:25:57.535  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:25:57.537  5588  5636 D BluetoothAdapter: enable(): BT is already enabled..!
11-03 18:25:57.538   930   940 D WifiService: setWifiEnabled: true pid=5588, uid=10077
11-03 18:25:57.538   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 18:25:57.587  4674  4879 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-03 18:25:57.587  4674  4884 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-03 18:25:57.676   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:58.004  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 18:25:58.678   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:25:59.681   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:00.294   930  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 18:26:00.685   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:01.688   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 18:26:02.549  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 18:26:02.549  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13cebcb added. We now have 4 listener(s)
,11-03 18:26:02.550  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:02.566  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:26:02.567  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13cebcb removed from the list
11-03 18:26:02.567  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:02.568  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:02.569  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca6fa8 added. We now have 4 listener(s)
11-03 18:26:02.569  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:02.572  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:26:02.572  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca6fa8 removed from the list
11-03 18:26:02.572  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:02.574  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:02.574  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@826eac1 added. We now have 4 listener(s)
,11-03 18:26:02.574  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:02.578   930  3595 D WifiService: setWifiEnabled: false pid=5588, uid=10077
11-03 18:26:02.579   930  3595 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 18:26:02.582   930  2956 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 18:26:02.583   930  2956 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 18:26:02.583   930  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 18:26:02.583   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 18:26:02.591  4674  4730 D BluetoothAdapterState: Current state: ON, message: 23
11-03 18:26:02.591  4674  4730 D BluetoothAdapterProperties: Setting state to 13
,11-03 18:26:02.591  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:26:02.591  4674  4730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 18:26:02.591  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 18:26:02.592  4674  4730 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 18:26:02.596  4674  4730 I BluetoothAdapterState: Entering PendingCommandState
11-03 18:26:02.599  4674  4674 D BluetoothMapService: onReceive
11-03 18:26:02.600  4674  4674 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 18:26:02.600  4674  4674 D BluetoothMapService: STATE_TURNING_OFF
11-03 18:26:02.600  4674  4674 D BluetoothMapService: MAP Service closeService in
11-03 18:26:02.600  4674  4674 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 18:26:02.600  4674  4674 D ObexServerSockets0: shutdown(block = true)
11-03 18:26:02.601  4674  4674 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 18:26:02.601  4674  4674 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 18:26:02.601  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 18:26:02.602  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 18:26:02.602  4674  4907 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-03 18:26:02.602  4674  4884 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 18:26:02.602  4674  4908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 18:26:02.603  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:02.604  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 18:26:02.604  5588  5636 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 18:26:02.606  4674  4674 I BtOppRfcommListener: stopping Accept Thread
,11-03 18:26:02.608  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:02.608  4674  5293 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 18:26:02.608  4674  5293 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 18:26:02.610   930  5362 D DhcpClient: Clearing IP address
11-03 18:26:02.610   508   923 D CommandListener: Clearing all IP addresses on wlan0
11-03 18:26:02.611  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:02.618  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:02.620   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:02.623   930  5363 D DhcpClient: Receive thread stopped
,11-03 18:26:02.629   930   943 I ActivityManager: Start proc 5655:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-03 18:26:02.629  3589  5414 V NativeCrypto: Read error: ssl=0x7f957f7a80: I/O error during system call, Connection timed out
,11-03 18:26:02.630  4674  4734 D BluetoothAdapterProperties: Scan Mode:20
11-03 18:26:02.631  3589  5414 V NativeCrypto: SSL shutdown failed: ssl=0x7f957f7a80: I/O error during system call, Broken pipe
11-03 18:26:02.631  4674  4730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 18:26:02.633   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 18:26:02.633   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-03 18:26:02.633  4674  4674 D HeadsetService: Received stop request...Stopping profile...
11-03 18:26:02.634  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 18:26:02.634  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 18:26:02.635  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:02.635  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 18:26:02.637   592   592 E Parcel  : Reading a NULL string not supported here.
11-03 18:26:02.638   930  2966 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 18:26:02.638  3137  3148 D BluetoothHeadset: Proxy object disconnected
,11-03 18:26:02.638   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:02.638  3782  3983 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:02.640   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:02.640   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:02.640  3733  3882 W QCNEJ   : |CORE| network lost: 100
11-03 18:26:02.640   930   930 D RttService: SCAN_AVAILABLE : 1
11-03 18:26:02.640   930  3076 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 18:26:02.640  3733  3882 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 18:26:02.641  4674  4674 D A2dpService: Received stop request...Stopping profile...
11-03 18:26:02.641  4674  4889 D A2dpStateMachine: Exit Disconnected: -1
11-03 18:26:02.643   930   930 D BluetoothA2dp: Proxy object disconnected
,11-03 18:26:02.643  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.644  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.644  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:02.644  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:02.645  4674  4674 D HidService: Received stop request...Stopping profile...
11-03 18:26:02.645  4674  4674 D HidService: Stopping Bluetooth HidService
,11-03 18:26:02.650  4674  4674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 18:26:02.650  4674  4674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 18:26:02.650  4674  4734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 18:26:02.650  4674  4879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:02.650  4674  4879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:02.650  4674  4879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 18:26:02.650  4674  4734 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-03 18:26:02.650  4674  4674 D HealthService: Received stop request...Stopping profile...
11-03 18:26:02.653  4674  4674 D PanService: Received stop request...Stopping profile...
11-03 18:26:02.654  4674  4674 D BluetoothMapService: Received stop request...Stopping profile...
11-03 18:26:02.655  4674  4674 D BluetoothMapService: stop()
11-03 18:26:02.656  4674  4674 D BluetoothMapAppObserver: deinitObservers()
11-03 18:26:02.656  4674  4674 D BluetoothMapAppObserver: removeReceiver()
11-03 18:26:02.657  4674  4674 D SapService: Received stop request...Stopping profile...
11-03 18:26:02.657  4674  4674 V SapService: stop()
11-03 18:26:02.658  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.658  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.659  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 18:26:02.659  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:02.661  3137  3137 D HeadsetProfile: Bluetooth service disconnected
11-03 18:26:02.661   930  2956 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 18:26:02.663  3137  3137 D BluetoothA2dp: Proxy object disconnected
11-03 18:26:02.663  3137  3137 D BluetoothInputDevice: Proxy object disconnected
11-03 18:26:02.663  3137  3137 D HidProfile: Bluetooth service disconnected
11-03 18:26:02.663  3137  3137 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 18:26:02.663  3137  3137 D PanProfile: Bluetooth service disconnected
11-03 18:26:02.663  3137  3137 D BluetoothMap: Proxy object disconnected
11-03 18:26:02.663  3137  3137 D MapProfile: Bluetooth service disconnected
,11-03 18:26:02.665   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 18:26:02.667  5655  5655 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-03 18:26:02.667  4674  4734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 18:26:02.667  4674  4879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:02.667  4674  4879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:02.667  4674  4879 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 18:26:02.667  4674  4879 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-03 18:26:02.667  4674  4879 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 18:26:02.667  4674  4879 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 18:26:02.667  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.667  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.667  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:02.667  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:02.668  4674  4674 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 18:26:02.668  4674  4674 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 18:26:02.668  4674  4734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 18:26:02.668  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.668  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.668  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:02.668  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:02.668  4674  4674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 18:26:02.668  4674  4734 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 18:26:02.669  4674  4674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 18:26:02.669  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.669  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.669  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:02.669  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:02.670  4674  4674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-03 18:26:02.670  4674  4674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 18:26:02.670   930  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 18:26:02.671  4674  4674 D BluetoothMapService: MAP Service closeService in
11-03 18:26:02.671  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.671  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.671  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:02.671  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:02.672  4674  4674 D BluetoothMapService: cleanup()
11-03 18:26:02.672  4674  4674 D BluetoothMapService: MAP Service closeService in
11-03 18:26:02.672  4674  4674 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:02.672  4674  4674 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:02.672  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:02.672  4674  4674 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:02.672  4674  4730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 18:26:02.672  4674  4730 D BluetoothAdapterProperties: Setting state to 15
11-03 18:26:02.672  4674  4730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 18:26:02.673  4674  4730 I BluetoothAdapterState: Entering BleOnState
11-03 18:26:02.673   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 18:26:02.673  3137  4010 D BluetoothMap: onBluetoothStateChange: up=false
,11-03 18:26:02.674  3782  3806 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:02.674   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:02.674   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 18:26:02.675  3137  3962 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 18:26:02.675  3137  3149 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:02.676  3137  3148 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 18:26:02.677   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:02.677  3137  4010 D BluetoothPan: onBluetoothStateChange on: false
11-03 18:26:02.678  3137  3962 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 18:26:02.679  4674  4730 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 18:26:02.679  4674  4730 D BluetoothAdapterProperties: Setting state to 16
11-03 18:26:02.679  4674  4730 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 18:26:02.680  4674  4730 D BluetoothAdapterProperties: onBleDisable
11-03 18:26:02.680  4674  4730 I BluetoothAdapterState: Entering PendingCommandState
11-03 18:26:02.680  4674  4731 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 18:26:02.681  4674  4734 D BluetoothAdapterProperties: Scan Mode:20
11-03 18:26:02.682  5655  5655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 18:26:02.683  4674  4879 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 18:26:02.683  4674  4879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:02.683  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:02.683  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 18:26:02.686  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:02.688  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 18:26:02.690   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 18:26:02.691   508   923 D CommandListener: Clearing all IP addresses on wlan0
11-03 18:26:02.691   508   923 D TetherController: Setting IP forward enable = 0
11-03 18:26:02.692   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5f888a8:true
11-03 18:26:02.692   930  2966 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-03 18:26:02.692   930  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 18:26:02.696   930  2956 D DhcpClient: doQuit
11-03 18:26:02.696   930  2956 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 18:26:02.697   930  5362 D DhcpClient: onQuitting
11-03 18:26:02.697  3456  3456 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-03 18:26:02.698   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-03 18:26:02.699  5265  5265 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8b5615a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-03 18:26:02.700  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:02.700  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 18:26:02.701  3968  3968 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-03 18:26:02.701  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:02.701  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 18:26:02.703  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:02.723  3456  3456 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 18:26:02.725  5655  5655 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 18:26:02.726  3456  3456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 18:26:02.729  5655  5655 D BluetoothMap: Create BluetoothMap proxy object
,11-03 18:26:02.735  5655  5655 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 18:26:02.744  5655  5655 D DockEventReceiver: finishStartingService: stopping service
,11-03 18:26:02.747  5655  5655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 18:26:02.751   508   923 E Netd    : netlink response contains error (No such file or directory)
,11-03 18:26:02.752   508   923 D TetherController: Setting IP forward enable = 0
11-03 18:26:02.752   930  2966 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-03 18:26:02.752  5655  5655 D DockEventReceiver: finishStartingService: stopping service
,11-03 18:26:02.753  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 18:26:02.754   930  3836 I ActivityManager: Killing 5389:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-03 18:26:02.761  3456  3456 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 18:26:02.770  3456  3456 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 18:26:02.783  3986  3986 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 18:26:02.790  3986  3986 D SystemUpdateService: onCreate
,11-03 18:26:02.793  3986  3986 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 18:26:02.802  3986  3986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 18:26:02.807  3986  5690 I SystemUpdateService: active receiver: enabled
,11-03 18:26:02.808  3986  4252 I iu.UploadsManager: num queued entries: 0
,11-03 18:26:02.808  3986  4252 I iu.UploadsManager: num updated entries: 0
,11-03 18:26:02.809  3986  4252 I iu.SyncManager: NEXT; no task
,11-03 18:26:02.811  3986  3986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 18:26:02.812  3986  3986 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 18:26:02.816  3986  5690 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 18:26:02.818  3986  5690 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 18:26:02.818  3986  5690 I SystemUpdateService: now status is 0 (complete)
11-03 18:26:02.818  3986  5690 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 18:26:02.819  3986  5690 I SystemUpdateService: file has been verified
11-03 18:26:02.819  3986  5690 I SystemUpdateService: OTA package size = 21989297
,11-03 18:26:02.824   930  4060 I ActivityManager: Start proc 5692:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-03 18:26:02.829  3986  5690 I SystemUpdateService: showing system update notification
,11-03 18:26:02.840   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 18:26:02.844  3986  3986 D SystemUpdateService: onDestroy
,11-03 18:26:02.858  5692  5692 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-03 18:26:02.861  5692  5692 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 18:26:02.868  5692  5692 D SprintDMHelper: simOperator: 
11-03 18:26:02.868  5692  5692 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 18:26:02.873   930  2956 D wifi    : In wifi stop Hal
,11-03 18:26:02.874   930  2956 D wifi    : halHandle = 0x7f7f232080, mVM = 0x7f9b8cd140, mCls = 0x100a02
11-03 18:26:02.874   930  3455 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 18:26:02.874   930  3455 D WifiHAL : Got a signal to exit!!!
11-03 18:26:02.874   930  3455 I WifiHAL : Exit wifi_event_loop
11-03 18:26:02.874   930  2956 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 18:26:02.874   930  2956 E WifiHAL : Event processing terminated
11-03 18:26:02.875  3711  4201 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 18:26:02.875   930  2956 D wifi    : In wifi cleaned up handler
11-03 18:26:02.875   930  2956 I WifiHAL : Internal cleanup completed
11-03 18:26:02.877  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:02.880  4550  4550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 18:26:02.896   930  3455 D wifi    : set interface wlan0 flags (DOWN)
11-03 18:26:02.896   930  2956 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 18:26:02.898   930  3595 I ActivityManager: Start proc 5705:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 18:26:02.900   930  3705 I ActivityManager: Killing 5265:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-03 18:26:02.931  4674  4734 I bt_hci  : shut_down
,11-03 18:26:02.934  4674  4738 D bt_hwcfg: hw_epilog_process
11-03 18:26:02.935  4674  4738 I bt_vendor: low_power_mode_cb
,11-03 18:26:02.937  4674  4738 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 18:26:02.938  4674  4738 I bt_vendor: epilog_cb
11-03 18:26:02.938  4674  4738 I bt_hci  : epilog_finished_callback
11-03 18:26:02.940  4674  4734 I bt_hci_h4: hal_close
11-03 18:26:02.940  4674  4734 I bt_userial_vendor: device fd = 54 close
,11-03 18:26:02.944  5705  5705 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 18:26:02.952   930  3595 I ActivityManager: Killing 3889:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 18:26:03.050  4674  4731 D bt_stack_manager: event_shut_down_stack finished.
,11-03 18:26:03.050  4674  4730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-03 18:26:03.052  4674  4730 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 18:26:03.052  4674  4674 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 18:26:03.053  4674  4674 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 18:26:03.053  4674  4674 D BtGatt.GattService: stop()
11-03 18:26:03.053  4674  4674 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 18:26:03.055  4674  4674 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:03.055  4674  4674 V BluetoothAdapterState: isTurningOn()=false
,11-03 18:26:03.055  4674  4674 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:03.055  4674  4674 V BluetoothAdapterState: isBleTurningOff()=true
,11-03 18:26:03.056  4674  4730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 18:26:03.056  4674  4730 D BluetoothAdapterProperties: Setting state to 10
11-03 18:26:03.056  4674  4730 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 18:26:03.057  4674  4730 I BluetoothAdapterState: Entering OffState
,11-03 18:26:03.058   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 18:26:03.065  4674  4674 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-03 18:26:03.065  4674  4674 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 18:26:03.065  4674  4674 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-03 18:26:03.066  4674  4731 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 18:26:03.069  4674  4674 I art     : System.exit called, status: 0
11-03 18:26:03.070  4674  4674 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 18:26:03.098   930  3202 I ActivityManager: Process com.android.bluetooth (pid 4674) has died
,11-03 18:26:03.100   930   947 D Tethering: InitialState.processMessage what=4
,11-03 18:26:03.104   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 18:26:07.609   930   941 D WifiService: setWifiEnabled: true pid=5588, uid=10077
,11-03 18:26:07.609   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 18:26:07.618   508   923 D SoftapController: Softap fwReload - Ok
,11-03 18:26:07.624   508   923 D CommandListener: Setting iface cfg
11-03 18:26:07.624   508   923 D CommandListener: Trying to bring down wlan0
,11-03 18:26:07.626   508   923 D CommandListener: Clearing all IP addresses on wlan0
11-03 18:26:07.631   930  2956 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 18:26:08.387   930  2956 D wifi    : set interface wlan0 flags (UP)
,11-03 18:26:08.388   930  2956 I WifiHAL : Initializing wifi
,11-03 18:26:08.388   930  2956 I WifiHAL : Creating socket
,11-03 18:26:08.394   930  2956 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 18:26:08.394   930  2956 D wifi    : Did set static halHandle = 0x7f7f232080
11-03 18:26:08.394   930  2956 D wifi    : halHandle = 0x7f7f232080, mVM = 0x7f9b8cd140, mCls = 0x1019ca
,11-03 18:26:08.396   930  2956 D wifi    : array field set
11-03 18:26:08.396   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 18:26:08.399   930  2956 I WifiNative-HAL: interface[0] = wlan0
,11-03 18:26:08.401   930  5721 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547593855104
,11-03 18:26:08.401   930  5721 D wifi    : waitForHalEvents called, vm = 0x7f9b8cd140, obj = 0x1019ca, env = 0x7f82e7c480
,11-03 18:26:08.465  5722  5722 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 18:26:08.504   930  2956 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 18:26:08.509  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:08.536  5722  5722 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 18:26:08.621  5722  5722 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 18:26:08.621  5722  5722 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 18:26:08.650   930  2956 D WifiConfigStore: Loading config and enabling all networks 
,11-03 18:26:08.651  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:08.651  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 18:26:08.651  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:08.652  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 18:26:08.681   930  2956 D WifiConfigStore: loaded 0 passpoint configs
,11-03 18:26:08.682   930  2956 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 18:26:08.683   930  2956 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 18:26:08.684   930  2956 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 18:26:08.684   930  2956 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 18:26:08.685   930  2956 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 18:26:08.686   930  2956 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 18:26:08.687   930  2956 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 18:26:08.687   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 18:26:08.687   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 18:26:08.687   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 18:26:08.687   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 18:26:08.687   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 18:26:08.689   930  2956 D WifiNative-HAL: Setting external_sim to 1
,11-03 18:26:08.690   930  2956 D wifi    : setting dfs flag to true, 0x7f8124fb40
11-03 18:26:08.690  4550  4550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 18:26:08.690   930  2956 D WifiStateMachine: Setting OUI to DA-A1-19
,11-03 18:26:08.690   930  2956 D wifi    : setting scan oui 0x7f8124fb40
11-03 18:26:08.690   930  2956 D WifiHAL : Sending mac address OUI
,11-03 18:26:08.694   930  2956 E native  : do suspend false
,11-03 18:26:08.722   930  2956 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 18:26:08.722   508   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-03 18:26:08.722   930   930 D RttService: SCAN_AVAILABLE : 3
,11-03 18:26:08.723   930  3076 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-03 18:26:08.724   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:08.730   930  2955 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-03 18:26:08.730   930  2955 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 18:26:08.744   930  2955 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 18:26:08.751   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=140478 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
11-03 18:26:08.752   930  2955 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 18:26:09.554   930  2956 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-03 18:26:11.693   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:11.837  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 18:26:11.851  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 18:26:11.858  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 18:26:11.888   930  2956 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 18:26:11.890   930  2956 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 18:26:11.890   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 18:26:11.906   930  2956 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 18:26:11.946   930  2956 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 18:26:11.952  5722  5722 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 18:26:12.444  5722  5722 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 18:26:12.521  5722  5722 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 18:26:12.523  5722  5722 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 18:26:12.542   930  2956 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 18:26:12.542   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 18:26:12.542   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 18:26:12.567   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 18:26:12.580   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:12.585   930  2956 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 18:26:12.594   930  5728 D DhcpClient: Receive thread started
,11-03 18:26:12.597   930  2956 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 18:26:12.597   930  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 18:26:12.597   930  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-03 18:26:12.615   930   940 D WifiService: setWifiEnabled: false pid=5588, uid=10077
,11-03 18:26:12.615   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 18:26:12.692   930  2956 E native  : do suspend false
,11-03 18:26:12.694   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:12.711   930  5727 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 18:26:12.712   930  2956 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{2}, ntable=[]
,11-03 18:26:12.713   930  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 18:26:12.715   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 18:26:12.727   930  5728 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172697, domain null
,11-03 18:26:12.728   930  5727 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172697 seconds
,11-03 18:26:12.729   930  5727 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 18:26:12.739   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 18:26:12.746   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,11-03 18:26:12.746   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,11-03 18:26:12.755   930   930 D RttService: SCAN_AVAILABLE : 1
11-03 18:26:12.756   930  3076 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 18:26:12.758   930  5728 D DhcpClient: Receive thread stopped
11-03 18:26:12.759   930  2956 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 18:26:12.759   930  2966 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-03 18:26:12.759   930  2966 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-03 18:26:12.762   930  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 18:26:12.764   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 18:26:12.766   930  2956 D DhcpClient: doQuit
11-03 18:26:12.766   930  2956 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 18:26:12.766   930  5727 D DhcpClient: onQuitting
11-03 18:26:12.767  5722  5722 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-03 18:26:12.771  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:12.771  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 18:26:12.771  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 18:26:12.771  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 18:26:12.775  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 18:26:12.782  5722  5722 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 18:26:12.835  5722  5722 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 18:26:12.838  5722  5722 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 18:26:12.844   930  2956 D wifi    : In wifi stop Hal
11-03 18:26:12.844  4550  4550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 18:26:12.845   930  2956 D wifi    : halHandle = 0x7f7f232080, mVM = 0x7f9b8cd140, mCls = 0x1019ca
,11-03 18:26:12.845   930  5721 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 18:26:12.845   930  5721 D WifiHAL : Got a signal to exit!!!
11-03 18:26:12.845   930  5721 I WifiHAL : Exit wifi_event_loop
11-03 18:26:12.845   930  2956 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 18:26:12.845   930  2956 E WifiHAL : Event processing terminated
11-03 18:26:12.846   930  2956 D wifi    : In wifi cleaned up handler
,11-03 18:26:12.846   930  2956 I WifiHAL : Internal cleanup completed
11-03 18:26:12.848  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:12.848  3711  4201 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 18:26:12.865   930  5721 D wifi    : set interface wlan0 flags (DOWN)
11-03 18:26:12.866   930  2956 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 18:26:13.074   930   947 D Tethering: InitialState.processMessage what=4
11-03 18:26:13.081   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 18:26:13.697   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:14.702   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:15.706   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:16.710   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 18:26:17.660   930   947 I ActivityManager: Start proc 5730:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 18:26:17.745  5730  5730 D AdapterServiceConfig: Adding HeadsetService
,11-03 18:26:17.746  5730  5730 D AdapterServiceConfig: Adding A2dpService
11-03 18:26:17.746  5730  5730 D AdapterServiceConfig: Adding HidService
11-03 18:26:17.746  5730  5730 D AdapterServiceConfig: Adding HealthService
11-03 18:26:17.746  5730  5730 D AdapterServiceConfig: Adding PanService
,11-03 18:26:17.746  5730  5730 D AdapterServiceConfig: Adding GattService
11-03 18:26:17.746  5730  5730 D AdapterServiceConfig: Adding BluetoothMapService
11-03 18:26:17.747  5730  5730 D AdapterServiceConfig: Adding SapService
,11-03 18:26:17.756   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@538e5ac:true
,11-03 18:26:17.757  5730  5730 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 18:26:17.760  5730  5730 I bt_bluedroid: init
,11-03 18:26:17.761  5730  5742 I BluetoothAdapterState: Entering OffState
,11-03 18:26:17.764  5730  5743 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 18:26:17.764  5730  5743 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 18:26:17.764  5730  5743 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 18:26:17.764  5730  5743 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 18:26:17.766  5730  5730 I bt_bluedroid: get_profile_interface socket
,11-03 18:26:17.768  5730  5746 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 18:26:17.768  5730  5730 I bt_bluedroid: get_profile_interface sdp
11-03 18:26:17.770  5730  5746 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 18:26:17.773  5730  5741 I bt_bluedroid: config_hci_snoop_log
11-03 18:26:17.774   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 18:26:17.778  5730  5742 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 18:26:17.778  5730  5742 D BluetoothAdapterProperties: Setting state to 14
11-03 18:26:17.779  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 18:26:17.780  5730  5742 D BluetoothBondStateMachine: make
,11-03 18:26:17.782  5730  5747 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 18:26:17.785  5730  5742 I BluetoothAdapterState: Entering PendingCommandState
,11-03 18:26:17.786  5730  5730 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 18:26:17.788  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:26:17.789  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 18:26:17.789  5730  5730 D BtGatt.GattService: Received start request. Starting profile...
11-03 18:26:17.790  5730  5730 D BtGatt.GattService: start()
11-03 18:26:17.790  5730  5730 I bt_bluedroid: get_profile_interface gatt
11-03 18:26:17.791  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:17.791  5730  5730 D BtGatt.AdvertiseManager: advertise manager created
,11-03 18:26:17.796  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-03 18:26:17.796  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:17.796  5730  5730 V BluetoothAdapterState: isBleTurningOn()=true
11-03 18:26:17.796  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:17.797  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 18:26:17.798  5730  5742 I bt_bluedroid: bt_bluedroid
11-03 18:26:17.798  5730  5743 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-03 18:26:17.798  5730  5743 I bt_hci  : start_up
,11-03 18:26:17.804  5730  5743 I bt_vendor: alloc value 0xf407f871
,11-03 18:26:17.804  5730  5743 I bt_vendor: init
11-03 18:26:17.804  5730  5743 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 18:26:17.804  5730  5743 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 18:26:17.914  5730  5743 D bt_hci  : start_up starting async portion
11-03 18:26:17.915  5730  5750 I bt_hci  : event_finish_startup
,11-03 18:26:17.915  5730  5750 I bt_hci_h4: hal_open
11-03 18:26:17.915  5730  5750 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 18:26:17.918  5730  5750 I bt_userial_vendor: device fd = 54 open
,11-03 18:26:17.914  5751  5751 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 18:26:17.938  5730  5750 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 18:26:17.942  5730  5750 D bt_hwcfg: Chipset BCM4358A3
,11-03 18:26:17.942  5730  5750 D bt_hwcfg: Target name = [BCM4358A3]
11-03 18:26:17.943  5730  5750 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 18:26:18.180  3653  3855 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 18:26:18.181  3653  3855 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 18:26:18.230  3589  3589 I ConfigService: onCreate
,11-03 18:26:18.644  5730  5750 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 18:26:18.645  5730  5750 D bt_hwcfg: Settlement delay -- 100 ms
11-03 18:26:18.645  5730  5750 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 18:26:18.781  5730  5750 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-03 18:26:18.782  5730  5750 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 18:26:18.783  5730  5750 I bt_hwcfg: vendor lib fwcfg completed
11-03 18:26:18.784  5730  5750 I bt_vendor: firmware callback
,11-03 18:26:18.784  5730  5750 I bt_hci  : firmware_config_callback
,11-03 18:26:18.796  5730  5754 I bt_btu  : btu_task pending for preload complete event
,11-03 18:26:18.796  5730  5754 I bt_btu_task: Bluetooth chip preload is complete
11-03 18:26:18.796  5730  5754 I bt_btu  : btu_task received preload complete event
,11-03 18:26:18.802  5730  5754 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_BTM
,11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 18:26:18.803  5730  5754 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 18:26:18.804  5730  5754 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 18:26:18.898  5730  5754 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ffd549
,11-03 18:26:18.898  5730  5754 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ffd549 
,11-03 18:26:18.909  5730  5746 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 18:26:18.911  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 18:26:18.911  5730  5746 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 18:26:18.915  5730  5746 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 18:26:18.918  5730  5746 D BluetoothAdapterProperties: Scan Mode:20
11-03 18:26:18.918  5730  5746 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 18:26:18.918  5730  5746 D bt_hci  : do_postload posting postload work item
11-03 18:26:18.918  5730  5750 I bt_hci  : event_postload
11-03 18:26:18.919  5730  5750 I bt_vendor: sco_config_cb
11-03 18:26:18.919  5730  5750 I bt_hci  : sco_config_callback postload finished.
11-03 18:26:18.921  5730  5746 D bt_bte_conf: Device ID record 1 : primary
11-03 18:26:18.921  5730  5746 D bt_bte_conf:   vendorId            = 000f
11-03 18:26:18.921  5730  5746 D bt_bte_conf:   vendorIdSource      = 0001
,11-03 18:26:18.921  5730  5746 D bt_bte_conf:   product             = 1200
,11-03 18:26:18.921  5730  5746 D bt_bte_conf:   version             = 1436
11-03 18:26:18.921  5730  5746 D bt_bte_conf:   clientExecutableURL = 
11-03 18:26:18.921  5730  5746 D bt_bte_conf:   serviceDescription  = 
,11-03 18:26:18.922  5730  5746 D bt_bte_conf:   documentationURL    = 
11-03 18:26:18.922  5730  5746 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 18:26:18.922  5730  5743 D bt_stack_manager: event_start_up_stack finished
11-03 18:26:18.924  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 18:26:18.924  5730  5742 D BluetoothAdapterProperties: Setting state to 15
11-03 18:26:18.924  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 18:26:18.927  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:18.928  5730  5742 I BluetoothAdapterState: Entering BleOnState
,11-03 18:26:18.931  5730  5742 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-03 18:26:18.931  5730  5742 D BluetoothAdapterProperties: Setting state to 11
11-03 18:26:18.932  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-03 18:26:18.933  5730  5750 I bt_vendor: low_power_mode_cb
,11-03 18:26:18.942  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:18.943  5730  5730 D HeadsetService: Received start request. Starting profile...
11-03 18:26:18.947  5730  5730 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-03 18:26:18.948  5730  5730 D HeadsetStateMachine: make
,11-03 18:26:18.953  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:18.960  5730  5742 I BluetoothAdapterState: Entering PendingCommandState
,11-03 18:26:18.961  5730  5730 D HeadsetStateMachine: max_hf_connections = 1
11-03 18:26:18.962  5730  5730 I bt_bluedroid: get_profile_interface handsfree
11-03 18:26:18.962  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 18:26:18.962  5730  5746 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 18:26:18.965  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:26:18.966  5730  5730 D A2dpService: Received start request. Starting profile...
,11-03 18:26:18.967  5730  5730 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-03 18:26:18.967  5730  5730 I bt_bluedroid: get_profile_interface avrcp
,11-03 18:26:18.976  5730  5730 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 18:26:18.977  5730  5730 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 18:26:18.977  5730  5730 D A2dpStateMachine: make
,11-03 18:26:18.978  5730  5730 I bt_bluedroid: get_profile_interface a2dp
,11-03 18:26:18.979  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 18:26:18.981  5730  5762 D A2dpStateMachine: Enter Disconnected: -2
,11-03 18:26:18.981  5730  5730 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 18:26:18.982  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:18.984  5655  5655 D BluetoothInputDevice: Proxy object connected
,11-03 18:26:18.984  5730  5730 D HidService: Received start request. Starting profile...
11-03 18:26:18.984  5730  5730 I bt_bluedroid: get_profile_interface hidhost
11-03 18:26:18.984  5655  5655 D HidProfile: Bluetooth service connected
11-03 18:26:18.984  5730  5730 D HidService: setHidService(): set to: null
11-03 18:26:18.985  5730  5746 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fde56d
11-03 18:26:18.985  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 18:26:18.985  5730  5730 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-03 18:26:18.986  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:18.987  5730  5730 D HealthService: Received start request. Starting profile...
,11-03 18:26:18.989  5730  5730 I bt_bluedroid: get_profile_interface health
,11-03 18:26:18.990  5730  5730 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 18:26:18.990  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:18.992  5655  5655 D BluetoothPan: BluetoothPAN Proxy object connected
,11-03 18:26:18.992  5655  5655 D PanProfile: Bluetooth service connected
11-03 18:26:18.993  5730  5730 D PanService: Received start request. Starting profile...
11-03 18:26:18.993  5730  5730 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 18:26:18.993  5730  5730 I bt_bluedroid: get_profile_interface pan
11-03 18:26:18.994  5730  5746 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 18:26:18.997  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:26:18.997  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 18:26:18.998  5655  5655 D BluetoothMap: Proxy object connected
11-03 18:26:18.998  5730  5730 D BluetoothMapService: Received start request. Starting profile...
11-03 18:26:18.998  5730  5730 D BluetoothMapService: start()
11-03 18:26:18.999  5655  5655 D MapProfile: Bluetooth service connected
11-03 18:26:18.999  5655  5655 D BluetoothMap: getConnectedDevices()
11-03 18:26:19.000  5655  5655 D BluetoothMap: Bluetooth is Not enabled
11-03 18:26:19.001  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 18:26:19.003  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-03 18:26:19.003  5730  5730 D BluetoothMapAppObserver: createReceiver()
11-03 18:26:19.005  5730  5730 D BluetoothMapAppObserver: initObservers()
11-03 18:26:19.005  5730  5730 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 18:26:19.013  5730  5730 V SapService: SapBinder()
,11-03 18:26:19.014  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:19.015  5730  5730 D SapService: Received start request. Starting profile...
11-03 18:26:19.015  5730  5730 V SapService: start()
,11-03 18:26:19.016  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.017  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:19.017  5730  5760 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.018  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.019  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:19.019  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:19.019  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.019  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.019  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:19.020  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:19.020  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:19.020  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:19.020  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:19.021  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 18:26:19.021  5730  5742 D BluetoothAdapterProperties: ScanMode =  20
11-03 18:26:19.021  5730  5742 D BluetoothAdapterProperties: State =  11
,11-03 18:26:19.022  5730  5746 D BluetoothAdapterProperties: Scan Mode:21
,11-03 18:26:19.022  5730  5746 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 18:26:19.022  5730  5742 D BluetoothAdapterProperties: Setting state to 12
11-03 18:26:19.022  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 18:26:19.022  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 18:26:19.023   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:19.023  5730  5742 I BluetoothAdapterState: Entering OnState
11-03 18:26:19.023  3137  3149 D BluetoothMap: onBluetoothStateChange: up=true
11-03 18:26:19.024  3137  3137 D BluetoothMap: Proxy object connected
11-03 18:26:19.024  3137  3137 D MapProfile: Bluetooth service connected
11-03 18:26:19.024  3137  3137 D BluetoothMap: getConnectedDevices()
11-03 18:26:19.025  3782  3983 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:19.025   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:19.026  5655  5664 D BluetoothPan: onBluetoothStateChange on: true
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:19.027  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 18:26:19.028   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 18:26:19.028  5655  5666 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 18:26:19.029   930   930 D BluetoothA2dp: Proxy object connected
11-03 18:26:19.029  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 18:26:19.030  3137  4010 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 18:26:19.031  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 18:26:19.031  3137  3148 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:19.031  3137  3137 D BluetoothA2dp: Proxy object connected
11-03 18:26:19.031  5730  5730 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 18:26:19.032  5655  5664 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 18:26:19.032  3137  3962 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 18:26:19.033  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:26:19.034   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:19.034  3137  3137 D BluetoothInputDevice: Proxy object connected
11-03 18:26:19.034  3137  3137 D HidProfile: Bluetooth service connected
11-03 18:26:19.034  5655  5666 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 18:26:19.035  3137  4010 D BluetoothPan: onBluetoothStateChange on: true
11-03 18:26:19.035  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:26:19.036  3137  3962 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 18:26:19.036  3137  3137 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 18:26:19.036  3137  3137 D PanProfile: Bluetooth service connected
11-03 18:26:19.038  5730  5730 D ObexServerSockets: Succeed to create listening sockets 
11-03 18:26:19.038  5730  5730 D ObexServerSockets0: startAccept()
,11-03 18:26:19.038  5730  5730 D ObexServerSockets0: prepareForNewConnect()
,11-03 18:26:19.039  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 18:26:19.040   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-03 18:26:19.041  5655  5655 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 18:26:19.042  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:19.042  5730  5730 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 18:26:19.042  5730  5730 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 18:26:19.043  5730  5730 D BluetoothMapService: onReceive
11-03 18:26:19.043  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 18:26:19.043  5730  5730 D BluetoothMapService: STATE_ON
11-03 18:26:19.043  5730  5768 D ObexServerSockets0: Accepting socket connection...
11-03 18:26:19.044  5730  5770 D ObexServerSockets0: Accepting socket connection...
11-03 18:26:19.046  5655  5655 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-03 18:26:19.046  5730  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:26:19.049  5730  5771 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 18:26:19.049  5730  5771 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 18:26:19.053  5655  5655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 18:26:19.055  5655  5655 D BluetoothA2dp: Proxy object connected
,11-03 18:26:19.061  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 18:26:19.067  5655  5655 D DockEventReceiver: finishStartingService: stopping service
,11-03 18:26:19.070  3137  3137 D BluetoothPbap: Proxy object connected
11-03 18:26:19.070  3137  3137 D PbapServerProfile: Bluetooth service connected
,11-03 18:26:19.071  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 18:26:19.071  5730  5730 D ObexServerSockets0: prepareForNewConnect()
,11-03 18:26:19.074  5655  5655 D BluetoothPbap: Proxy object connected
11-03 18:26:19.074  5655  5655 D PbapServerProfile: Bluetooth service connected
,11-03 18:26:19.079  5730  5775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 18:26:19.092  5730  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 18:26:19.093  5730  5779 I BtOppRfcommListener: Accept thread started.
,11-03 18:26:19.124  3137  3148 D BluetoothHeadset: Proxy object connected
,11-03 18:26:19.124  3137  3137 D HeadsetProfile: Bluetooth service connected
11-03 18:26:19.125   930   930 D BluetoothHeadset: Proxy object connected
11-03 18:26:19.125  3782  3803 D BluetoothHeadset: Proxy object connected
11-03 18:26:19.125   930   930 D BluetoothHeadset: Proxy object connected
11-03 18:26:19.125   930   930 D BluetoothHeadset: Proxy object connected
11-03 18:26:19.126  3782  3806 D BluetoothHeadset: Proxy object connected
11-03 18:26:19.127   930   947 D BluetoothHeadset: Proxy object connected
,11-03 18:26:19.132  3137  4010 D BluetoothHeadset: Proxy object connected
11-03 18:26:19.132  3137  3137 D HeadsetProfile: Bluetooth service connected
,11-03 18:26:19.135   930   947 D BluetoothHeadset: Proxy object connected
,11-03 18:26:19.148  5655  5664 D BluetoothHeadset: Proxy object connected
,11-03 18:26:19.149  5655  5655 D HeadsetProfile: Bluetooth service connected
,11-03 18:26:20.610   930   950 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-03 18:26:20.623  3653  3653 I Keyboard.Facilitator: onFinishInput()
,11-03 18:26:20.617   940   940 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33793]" dev="sockfs" ino=33793 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 18:26:20.620   940   940 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33793]" dev="sockfs" ino=33793 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:26:20.629   930   950 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 18:26:20.629   930   950 I Adreno  : Build Date                       : 12/06/15
11-03 18:26:20.629   930   950 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 18:26:20.629   930   950 I Adreno  : Local Branch                     : mybranch17112971
11-03 18:26:20.629   930   950 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 18:26:20.629   930   950 I Adreno  : Remote Branch                    : NONE
11-03 18:26:20.629   930   950 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 18:26:20.674   382   753 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
,11-03 18:26:21.430  5588  5588 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 18:26:21.430  5588  5588 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-03 18:26:21.461   930   950 I sensors : batch
,11-03 18:26:21.462   930   950 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-03 18:26:21.466   930   950 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-03 18:26:21.465  5588  5588 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b8e4254 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f2ade54, 16908290=android.view.AbsSavedState$1@f2ade54}, android:focusedViewId=100}]}]
11-03 18:26:21.468  5588  5588 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,11-03 18:26:21.468   930   950 I sensors : activate
11-03 18:26:21.468   930  2783 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-03 18:26:21.468  5588  5588 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 18:26:21.468  5588  5588 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-03 18:26:21.469   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f963c3c00
11-03 18:26:21.469   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-03 18:26:21.469   930   948 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-03 18:26:21.479   930  2783 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-03 18:26:21.791   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-03 18:26:21.792   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
11-03 18:26:21.793   930  3093 D SurfaceControl: Excessive delay in setPowerMode(): 324ms
,11-03 18:26:21.809   930   950 I DreamManagerService: Entering dreamland.
11-03 18:26:21.810   930   950 I PowerManagerService: Dozing...
,11-03 18:26:21.811   930   945 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-03 18:26:21.830  3157  3157 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31610]" dev="sockfs" ino=31610 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:26:21.830  3157  3157 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31610]" dev="sockfs" ino=31610 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 18:26:21.836   930  3625 I sensors : batch
11-03 18:26:21.837   930  3625 I sensors : activate
,11-03 18:26:21.839   930  2783 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-03 18:26:21.841   930  2783 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-03 18:26:21.846   513  3007 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-03 18:26:21.873  3782  4761 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-03 18:26:21.874  3782  4761 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 18:26:21.874  3782  4761 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 18:26:21.874   526  1414 D         : oem-qmi: Connection accepted
11-03 18:26:21.874   526  1414 D         : oem-qmi: Waiting to accept connection
,11-03 18:26:21.876   930   930 I sensors : activate
,11-03 18:26:21.877   513  3006 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-03 18:26:21.879   930  2783 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-03 18:26:21.881  3782  4761 D         : oem_qmi_lib:output 0
11-03 18:26:21.882  3782  4761 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 18:26:21.906  3782  4761 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-03 18:26:21.906  3782  4761 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 18:26:21.906  3782  4761 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 18:26:21.906   526  1414 D         : oem-qmi: Connection accepted
11-03 18:26:21.906   526  1414 D         : oem-qmi: Waiting to accept connection
,11-03 18:26:21.912  3782  4761 D         : oem_qmi_lib:output 0
,11-03 18:26:21.912  3782  4761 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 18:26:22.637  5730  5742 D BluetoothAdapterState: Current state: ON, message: 23
11-03 18:26:22.638  5730  5742 D BluetoothAdapterProperties: Setting state to 13
11-03 18:26:22.638  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 18:26:22.640  5730  5742 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 18:26:22.641  5730  5742 I BluetoothAdapterState: Entering PendingCommandState
11-03 18:26:22.645  5730  5730 D BluetoothMapService: onReceive
,11-03 18:26:22.645  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-03 18:26:22.645  5730  5730 D BluetoothMapService: STATE_TURNING_OFF
,11-03 18:26:22.646  5730  5730 D BluetoothMapService: MAP Service closeService in
,11-03 18:26:22.646  5730  5730 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 18:26:22.646  5730  5730 D ObexServerSockets0: shutdown(block = true)
11-03 18:26:22.648  5730  5768 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 18:26:22.649  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 18:26:22.652  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:22.652  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 18:26:22.653  5730  5770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 18:26:22.653  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 18:26:22.654  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 18:26:22.654  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 18:26:22.654  5730  5756 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 18:26:22.656  5730  5730 I BtOppRfcommListener: stopping Accept Thread
11-03 18:26:22.657  5730  5779 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 18:26:22.656  5730  5746 D BluetoothAdapterProperties: Scan Mode:20
11-03 18:26:22.657  5730  5779 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 18:26:22.658  5655  5655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 18:26:22.658  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 18:26:22.663  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:22.665  5730  5730 D HeadsetService: Received stop request...Stopping profile...
11-03 18:26:22.669  3137  3149 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:22.669   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:22.670  3782  3806 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:22.671   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:22.671  3137  3137 D HeadsetProfile: Bluetooth service disconnected
11-03 18:26:22.671  5655  5666 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:22.672   930   930 D BluetoothHeadset: Proxy object disconnected
11-03 18:26:22.673  5730  5730 D A2dpService: Received stop request...Stopping profile...
11-03 18:26:22.675  5655  5655 D DockEventReceiver: finishStartingService: stopping service
11-03 18:26:22.675  5730  5762 D A2dpStateMachine: Exit Disconnected: -1
,11-03 18:26:22.676  5655  5655 D HeadsetProfile: Bluetooth service disconnected
,11-03 18:26:22.680   930   930 D BluetoothA2dp: Proxy object disconnected
11-03 18:26:22.681  5655  5655 D BluetoothA2dp: Proxy object disconnected
,11-03 18:26:22.684  5730  5730 D HidService: Received stop request...Stopping profile...
,11-03 18:26:22.684  5730  5730 D HidService: Stopping Bluetooth HidService
11-03 18:26:22.686  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.686  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:22.686  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:22.686  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:22.687  5730  5730 D HealthService: Received stop request...Stopping profile...
11-03 18:26:22.690  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 18:26:22.690  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-03 18:26:22.690  5730  5754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:22.690  5730  5754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:22.691  5730  5754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:22.691  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 18:26:22.691  5730  5746 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 18:26:22.691  5730  5730 D PanService: Received stop request...Stopping profile...
11-03 18:26:22.692  3137  3137 D BluetoothA2dp: Proxy object disconnected
11-03 18:26:22.692  3137  3137 D BluetoothInputDevice: Proxy object disconnected
11-03 18:26:22.693  3137  3137 D HidProfile: Bluetooth service disconnected
11-03 18:26:22.693  3137  3137 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 18:26:22.693  3137  3137 D PanProfile: Bluetooth service disconnected
11-03 18:26:22.696  5730  5730 D BluetoothMapService: Received stop request...Stopping profile...
11-03 18:26:22.696  5730  5730 D BluetoothMapService: stop()
11-03 18:26:22.696  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 18:26:22.697  5730  5730 D BluetoothMapAppObserver: deinitObservers()
11-03 18:26:22.697  5730  5730 D BluetoothMapAppObserver: removeReceiver()
11-03 18:26:22.697  5655  5655 D BluetoothInputDevice: Proxy object disconnected
11-03 18:26:22.697  5655  5655 D HidProfile: Bluetooth service disconnected
11-03 18:26:22.698  5655  5655 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 18:26:22.698  5655  5655 D PanProfile: Bluetooth service disconnected
11-03 18:26:22.700  5655  5655 D BluetoothMap: Proxy object disconnected
11-03 18:26:22.700  5655  5655 D MapProfile: Bluetooth service disconnected
11-03 18:26:22.700  5730  5730 D SapService: Received stop request...Stopping profile...
11-03 18:26:22.701  5730  5730 V SapService: stop()
,11-03 18:26:22.701  3137  3137 D BluetoothMap: Proxy object disconnected
11-03 18:26:22.701  3137  3137 D MapProfile: Bluetooth service disconnected
11-03 18:26:22.702  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.703  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:22.703  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:22.703  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:22.704  5730  5754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:22.705  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.705  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:22.705  5730  5754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 18:26:22.705  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:22.705  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:22.705  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 18:26:22.705  5730  5754 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 18:26:22.705  5730  5754 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 18:26:22.705  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 18:26:22.705  5730  5754 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 18:26:22.705  5730  5754 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 18:26:22.705  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 18:26:22.706  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.706  5730  5746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 18:26:22.706  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:22.706  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:22.706  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:22.706  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 18:26:22.706  5730  5746 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 18:26:22.707  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 18:26:22.707  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.707  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:22.707  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 18:26:22.707  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:22.708  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 18:26:22.708  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-03 18:26:22.710  3137  3137 D BluetoothPbap: Proxy object disconnected
11-03 18:26:22.710  3137  3137 D PbapServerProfile: Bluetooth service disconnected
11-03 18:26:22.711  5655  5655 D BluetoothPbap: Proxy object disconnected
11-03 18:26:22.711  5655  5655 D PbapServerProfile: Bluetooth service disconnected
,11-03 18:26:22.711  5730  5730 D BluetoothMapService: MAP Service closeService in
11-03 18:26:22.711  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.711  5730  5730 V BluetoothAdapterState: isTurningOn()=false
,11-03 18:26:22.711  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 18:26:22.711  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:22.711  5730  5730 D BluetoothMapService: cleanup()
11-03 18:26:22.711  5730  5730 D BluetoothMapService: MAP Service closeService in
11-03 18:26:22.712  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-03 18:26:22.712  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:22.712  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:22.712  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:22.712  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 18:26:22.712  5730  5742 D BluetoothAdapterProperties: Setting state to 15
11-03 18:26:22.713  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 18:26:22.714  5730  5742 I BluetoothAdapterState: Entering BleOnState
11-03 18:26:22.714   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:22.715  3137  3962 D BluetoothMap: onBluetoothStateChange: up=false
11-03 18:26:22.715  3782  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:22.716   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:22.716  5655  5664 D BluetoothPan: onBluetoothStateChange on: false
11-03 18:26:22.718   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 18:26:22.719  5655  5666 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 18:26:22.720  3137  3149 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 18:26:22.720  5655  5664 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:22.721  3137  3148 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:22.721  5655  5666 D BluetoothMap: onBluetoothStateChange: up=false
11-03 18:26:22.722  3137  4010 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 18:26:22.722  5655  5664 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 18:26:22.723   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 18:26:22.723  5655  5666 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 18:26:22.724  3137  3962 D BluetoothPan: onBluetoothStateChange on: false
,11-03 18:26:22.725  3137  3149 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 18:26:22.725  5730  5742 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 18:26:22.725  5730  5742 D BluetoothAdapterProperties: Setting state to 16
,11-03 18:26:22.725  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 18:26:22.727  5730  5742 D BluetoothAdapterProperties: onBleDisable
,11-03 18:26:22.728  5730  5742 I BluetoothAdapterState: Entering PendingCommandState
,11-03 18:26:22.728  5730  5743 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-03 18:26:22.729  5730  5746 D BluetoothAdapterProperties: Scan Mode:20
11-03 18:26:22.730  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:22.730  5655  5655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 18:26:22.731  5730  5754 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 18:26:22.731  5730  5754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 18:26:22.734  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:22.736  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 18:26:22.737  5655  5655 D DockEventReceiver: finishStartingService: stopping service
,11-03 18:26:22.950  5730  5746 I bt_hci  : shut_down
,11-03 18:26:22.957  5730  5750 D bt_hwcfg: hw_epilog_process
11-03 18:26:22.958  5730  5750 I bt_vendor: low_power_mode_cb
,11-03 18:26:22.963  5730  5750 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 18:26:22.963  5730  5750 I bt_vendor: epilog_cb
11-03 18:26:22.964  5730  5750 I bt_hci  : epilog_finished_callback
,11-03 18:26:22.971  5730  5746 I bt_hci_h4: hal_close
,11-03 18:26:22.973  5730  5746 I bt_userial_vendor: device fd = 54 close
,11-03 18:26:23.095  5730  5743 D bt_stack_manager: event_shut_down_stack finished.
,11-03 18:26:23.096  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 18:26:23.101  5730  5742 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 18:26:23.102  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 18:26:23.104  5730  5730 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 18:26:23.104  5730  5730 D BtGatt.GattService: stop()
11-03 18:26:23.104  5730  5730 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 18:26:23.108  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:23.109  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:23.109  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:23.109  5730  5730 V BluetoothAdapterState: isBleTurningOff()=true
11-03 18:26:23.110  5730  5742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-03 18:26:23.110  5730  5742 D BluetoothAdapterProperties: Setting state to 10
11-03 18:26:23.110  5730  5742 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 18:26:23.111  5730  5742 I BluetoothAdapterState: Entering OffState
,11-03 18:26:23.114   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 18:26:23.128  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 18:26:23.129  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 18:26:23.129  5730  5730 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 18:26:23.132  5730  5743 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 18:26:23.142  5730  5730 I art     : System.exit called, status: 0
,11-03 18:26:23.142  5730  5730 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 18:26:23.168   930  3705 I ActivityManager: Process com.android.bluetooth (pid 5730) has died
,11-03 18:26:23.275  3589  3589 I ConfigService: onDestroy
,11-03 18:26:25.556  3711  4465 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 18:26:27.636  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:26:27.636  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 18:26:27.643  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:26:27.644  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@826eac1 removed from the list
11-03 18:26:27.644  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:26:27.647  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:27.647  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df671fd added. We now have 4 listener(s)
,11-03 18:26:27.647  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:27.650  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:27.650  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df671fd removed from the list
11-03 18:26:27.650  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:27.652  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:27.652  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f57cef2 added. We now have 4 listener(s)
11-03 18:26:27.653  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:31.711   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:32.667  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 18:26:32.705   930   947 I ActivityManager: Start proc 5794:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 18:26:32.712   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:32.796  5794  5794 D AdapterServiceConfig: Adding HeadsetService
,11-03 18:26:32.796  5794  5794 D AdapterServiceConfig: Adding A2dpService
11-03 18:26:32.797  5794  5794 D AdapterServiceConfig: Adding HidService
11-03 18:26:32.797  5794  5794 D AdapterServiceConfig: Adding HealthService
11-03 18:26:32.797  5794  5794 D AdapterServiceConfig: Adding PanService
11-03 18:26:32.797  5794  5794 D AdapterServiceConfig: Adding GattService
11-03 18:26:32.797  5794  5794 D AdapterServiceConfig: Adding BluetoothMapService
11-03 18:26:32.797  5794  5794 D AdapterServiceConfig: Adding SapService
,11-03 18:26:32.809   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b5eba0f:true
,11-03 18:26:32.809  5794  5794 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 18:26:32.812  5794  5794 I bt_bluedroid: init
,11-03 18:26:32.814  5794  5806 I BluetoothAdapterState: Entering OffState
,11-03 18:26:32.817  5794  5807 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 18:26:32.817  5794  5807 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 18:26:32.817  5794  5807 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 18:26:32.817  5794  5807 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 18:26:32.818  5794  5794 I bt_bluedroid: get_profile_interface socket
,11-03 18:26:32.820  5794  5810 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 18:26:32.821  5794  5794 I bt_bluedroid: get_profile_interface sdp
,11-03 18:26:32.823  5794  5810 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 18:26:32.826  5794  5805 I bt_bluedroid: config_hci_snoop_log
11-03 18:26:32.828   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 18:26:32.832  5794  5806 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 18:26:32.832  5794  5806 D BluetoothAdapterProperties: Setting state to 14
11-03 18:26:32.832  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 18:26:32.834  5794  5806 D BluetoothBondStateMachine: make
,11-03 18:26:32.837  5794  5811 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 18:26:32.840  5794  5806 I BluetoothAdapterState: Entering PendingCommandState
,11-03 18:26:32.841  5794  5794 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 18:26:32.844  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:32.844  5794  5794 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 18:26:32.845  5794  5794 D BtGatt.GattService: Received start request. Starting profile...
11-03 18:26:32.845  5794  5794 D BtGatt.GattService: start()
11-03 18:26:32.845  5794  5794 I bt_bluedroid: get_profile_interface gatt
,11-03 18:26:32.847  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:26:32.847  5794  5794 D BtGatt.AdvertiseManager: advertise manager created
,11-03 18:26:32.854  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:32.854  5794  5794 V BluetoothAdapterState: isTurningOn()=false
11-03 18:26:32.854  5794  5794 V BluetoothAdapterState: isBleTurningOn()=true
11-03 18:26:32.854  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:32.854  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 18:26:32.856  5794  5806 I bt_bluedroid: bt_bluedroid
11-03 18:26:32.856  5794  5807 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 18:26:32.856  5794  5807 I bt_hci  : start_up
,11-03 18:26:32.863  5794  5807 I bt_vendor: alloc value 0xf407f871
11-03 18:26:32.864  5794  5807 I bt_vendor: init
11-03 18:26:32.864  5794  5807 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 18:26:32.864  5794  5807 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 18:26:32.977  5794  5807 D bt_hci  : start_up starting async portion
,11-03 18:26:32.977  5794  5814 I bt_hci  : event_finish_startup
11-03 18:26:32.978  5794  5814 I bt_hci_h4: hal_open
11-03 18:26:32.978  5794  5814 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 18:26:32.977  5815  5815 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 18:26:32.982  5794  5814 I bt_userial_vendor: device fd = 54 open
,11-03 18:26:33.002  5794  5814 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 18:26:33.006  5794  5814 D bt_hwcfg: Chipset BCM4358A3
,11-03 18:26:33.006  5794  5814 D bt_hwcfg: Target name = [BCM4358A3]
11-03 18:26:33.006  5794  5814 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 18:26:33.714   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:33.831  5794  5814 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 18:26:33.832  5794  5814 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 18:26:33.832  5794  5814 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 18:26:33.971  5794  5814 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-03 18:26:33.971  5794  5814 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-03 18:26:33.973  5794  5814 I bt_hwcfg: vendor lib fwcfg completed
11-03 18:26:33.973  5794  5814 I bt_vendor: firmware callback
11-03 18:26:33.973  5794  5814 I bt_hci  : firmware_config_callback
,11-03 18:26:33.985  5794  5817 I bt_btu  : btu_task pending for preload complete event
,11-03 18:26:33.985  5794  5817 I bt_btu_task: Bluetooth chip preload is complete
11-03 18:26:33.985  5794  5817 I bt_btu  : btu_task received preload complete event
,11-03 18:26:33.992  5794  5817 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 18:26:33.993  5794  5817 I         : BTE_InitTraceLevels -- TRC_BTM
,11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 18:26:33.994  5794  5817 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 18:26:34.099  5794  5817 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ffd549
,11-03 18:26:34.099  5794  5817 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ffd549 
,11-03 18:26:34.125  5794  5810 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 18:26:34.127  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 18:26:34.128  5794  5810 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 18:26:34.131  5794  5810 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 18:26:34.135  5794  5810 D BluetoothAdapterProperties: Scan Mode:20
,11-03 18:26:34.135  5794  5810 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 18:26:34.135  5794  5810 D bt_hci  : do_postload posting postload work item
,11-03 18:26:34.135  5794  5814 I bt_hci  : event_postload
11-03 18:26:34.135  5794  5814 I bt_vendor: sco_config_cb
11-03 18:26:34.135  5794  5814 I bt_hci  : sco_config_callback postload finished.
11-03 18:26:34.138  5794  5810 D bt_bte_conf: Device ID record 1 : primary
,11-03 18:26:34.138  5794  5810 D bt_bte_conf:   vendorId            = 000f
11-03 18:26:34.138  5794  5810 D bt_bte_conf:   vendorIdSource      = 0001
11-03 18:26:34.138  5794  5810 D bt_bte_conf:   product             = 1200
11-03 18:26:34.138  5794  5810 D bt_bte_conf:   version             = 1436
11-03 18:26:34.138  5794  5810 D bt_bte_conf:   clientExecutableURL = 
11-03 18:26:34.138  5794  5810 D bt_bte_conf:   serviceDescription  = 
11-03 18:26:34.138  5794  5810 D bt_bte_conf:   documentationURL    = 
11-03 18:26:34.139  5794  5810 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 18:26:34.139  5794  5807 D bt_stack_manager: event_start_up_stack finished
11-03 18:26:34.140  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 18:26:34.140  5794  5806 D BluetoothAdapterProperties: Setting state to 15
,11-03 18:26:34.140  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 18:26:34.141  5794  5806 I BluetoothAdapterState: Entering BleOnState
,11-03 18:26:34.143  5794  5814 I bt_vendor: low_power_mode_cb
11-03 18:26:34.146  5794  5806 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 18:26:34.146  5794  5806 D BluetoothAdapterProperties: Setting state to 11
11-03 18:26:34.146  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 18:26:34.152  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:34.153  5794  5794 D HeadsetService: Received start request. Starting profile...
,11-03 18:26:34.158  5794  5794 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 18:26:34.158  5794  5794 D HeadsetStateMachine: make
,11-03 18:26:34.170  5794  5806 I BluetoothAdapterState: Entering PendingCommandState
,11-03 18:26:34.171  5794  5794 D HeadsetStateMachine: max_hf_connections = 1
11-03 18:26:34.172  5794  5794 I bt_bluedroid: get_profile_interface handsfree
11-03 18:26:34.172  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 18:26:34.172  5794  5810 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-03 18:26:34.175  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:34.176  5794  5794 D A2dpService: Received start request. Starting profile...
11-03 18:26:34.177  5794  5794 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 18:26:34.177  5794  5794 I bt_bluedroid: get_profile_interface avrcp
,11-03 18:26:34.184  5794  5794 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-03 18:26:34.184  5794  5794 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 18:26:34.184  5794  5794 D A2dpStateMachine: make
,11-03 18:26:34.186  5794  5794 I bt_bluedroid: get_profile_interface a2dp
11-03 18:26:34.186  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 18:26:34.188  5794  5825 D A2dpStateMachine: Enter Disconnected: -2
,11-03 18:26:34.188  5794  5794 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 18:26:34.189  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:34.190  5794  5794 D HidService: Received start request. Starting profile...
11-03 18:26:34.190  5794  5794 I bt_bluedroid: get_profile_interface hidhost
11-03 18:26:34.190  5794  5794 D HidService: setHidService(): set to: null
11-03 18:26:34.190  5794  5810 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fde56d
11-03 18:26:34.190  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 18:26:34.191  5794  5794 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 18:26:34.191  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:26:34.192  5794  5794 D HealthService: Received start request. Starting profile...
,11-03 18:26:34.194  5794  5794 I bt_bluedroid: get_profile_interface health
11-03 18:26:34.196  5794  5794 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 18:26:34.196  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:34.197  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 18:26:34.197  5794  5794 D PanService: Received start request. Starting profile...
,11-03 18:26:34.198  5794  5794 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 18:26:34.198  5794  5794 I bt_bluedroid: get_profile_interface pan
11-03 18:26:34.198  5794  5810 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 18:26:34.203  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:34.203  5794  5794 D BluetoothMapService: Received start request. Starting profile...
11-03 18:26:34.203  5794  5794 D BluetoothMapService: start()
11-03 18:26:34.206  5794  5794 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 18:26:34.207  5794  5794 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 18:26:34.207  5794  5794 D BluetoothMapAppObserver: createReceiver()
11-03 18:26:34.209  5794  5794 D BluetoothMapAppObserver: initObservers()
11-03 18:26:34.209  5794  5794 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 18:26:34.216  5794  5794 V SapService: SapBinder()
11-03 18:26:34.216  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
,11-03 18:26:34.217  5794  5794 D SapService: Received start request. Starting profile...
11-03 18:26:34.217  5794  5794 V SapService: start()
,11-03 18:26:34.218  5794  5794 V BluetoothAdapterState: isTurningOff()=false
,11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:34.219  5794  5823 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 18:26:34.219  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:34.220  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.221  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:34.221  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:34.221  5794  5794 V BluetoothAdapterState: isTurningOn()=true
,11-03 18:26:34.221  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.221  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:34.222  5794  5794 V BluetoothAdapterState: isTurningOff()=false
11-03 18:26:34.222  5794  5794 V BluetoothAdapterState: isTurningOn()=true
11-03 18:26:34.222  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
11-03 18:26:34.222  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 18:26:34.223  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-03 18:26:34.223  5794  5806 D BluetoothAdapterProperties: ScanMode =  20
,11-03 18:26:34.223  5794  5806 D BluetoothAdapterProperties: State =  11
11-03 18:26:34.223  5794  5806 D BluetoothAdapterProperties: Setting state to 12
11-03 18:26:34.223  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 18:26:34.223   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:34.224  3137  3149 D BluetoothMap: onBluetoothStateChange: up=true
11-03 18:26:34.224  5794  5810 D BluetoothAdapterProperties: Scan Mode:21
11-03 18:26:34.225  5794  5810 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 18:26:34.225  5794  5806 I BluetoothAdapterState: Entering OnState
11-03 18:26:34.226  3782  3803 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:34.226   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:34.227  3137  3137 D BluetoothMap: Proxy object connected
11-03 18:26:34.227  3137  3137 D MapProfile: Bluetooth service connected
11-03 18:26:34.227  3137  3137 D BluetoothMap: getConnectedDevices()
,11-03 18:26:34.227  5655  5666 D BluetoothPan: onBluetoothStateChange on: true
11-03 18:26:34.229   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 18:26:34.230  5655  5664 D BluetoothPbap: onBluetoothStateChange: up=true
,11-03 18:26:34.231   930   930 D BluetoothA2dp: Proxy object connected
11-03 18:26:34.232  3137  3148 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 18:26:34.233  5655  5655 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 18:26:34.233  5655  5655 D PanProfile: Bluetooth service connected
11-03 18:26:34.234  3137  3137 D BluetoothA2dp: Proxy object connected
11-03 18:26:34.235  5794  5794 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 18:26:34.236  5794  5794 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 18:26:34.236  5655  5666 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:34.237  3137  3149 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:34.237  5655  5664 D BluetoothMap: onBluetoothStateChange: up=true
11-03 18:26:34.237  5794  5794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:26:34.240  3137  3962 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 18:26:34.241  5794  5794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 18:26:34.241  5655  5655 D BluetoothMap: Proxy object connected
11-03 18:26:34.241  5655  5655 D MapProfile: Bluetooth service connected
,11-03 18:26:34.241  5655  5655 D BluetoothMap: getConnectedDevices()
11-03 18:26:34.242  5794  5794 D ObexServerSockets: Succeed to create listening sockets 
11-03 18:26:34.242  5655  5666 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 18:26:34.242  5794  5794 D ObexServerSockets0: startAccept()
11-03 18:26:34.242  5794  5794 D ObexServerSockets0: prepareForNewConnect()
11-03 18:26:34.244  5794  5794 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-03 18:26:34.244   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 18:26:34.245  5794  5794 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 18:26:34.245  5655  5664 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 18:26:34.245  5794  5832 D ObexServerSockets0: Accepting socket connection...
11-03 18:26:34.245  5794  5831 D ObexServerSockets0: Accepting socket connection...
11-03 18:26:34.246  3137  3137 D BluetoothInputDevice: Proxy object connected
11-03 18:26:34.246  3137  3137 D HidProfile: Bluetooth service connected
11-03 18:26:34.247  3137  4010 D BluetoothPan: onBluetoothStateChange on: true
11-03 18:26:34.249  5655  5655 D BluetoothA2dp: Proxy object connected
11-03 18:26:34.249  3137  3137 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 18:26:34.249  3137  3137 D PanProfile: Bluetooth service connected
,11-03 18:26:34.249  3137  3962 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 18:26:34.252   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 18:26:34.254  5794  5794 D BluetoothMapService: onReceive
11-03 18:26:34.254  5794  5794 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 18:26:34.254  5794  5794 D BluetoothMapService: STATE_ON
11-03 18:26:34.255  5655  5655 D BluetoothInputDevice: Proxy object connected
11-03 18:26:34.255  5655  5655 D HidProfile: Bluetooth service connected
11-03 18:26:34.257  5794  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 18:26:34.259  5794  5834 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 18:26:34.259  5794  5834 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 18:26:34.260  5655  5655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 18:26:34.267  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 18:26:34.270  5655  5655 D DockEventReceiver: finishStartingService: stopping service
,11-03 18:26:34.278  5655  5655 D BluetoothPbap: Proxy object connected
,11-03 18:26:34.278  5655  5655 D PbapServerProfile: Bluetooth service connected
,11-03 18:26:34.282  5794  5794 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 18:26:34.282  5794  5794 D ObexServerSockets0: prepareForNewConnect()
,11-03 18:26:34.285  5794  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 18:26:34.286  3137  3137 D BluetoothPbap: Proxy object connected
11-03 18:26:34.286  3137  3137 D PbapServerProfile: Bluetooth service connected
,11-03 18:26:34.302  5794  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 18:26:34.303  5794  5842 I BtOppRfcommListener: Accept thread started.
,11-03 18:26:34.327  3137  3962 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.327   930   930 D BluetoothHeadset: Proxy object connected
,11-03 18:26:34.327  3137  3137 D HeadsetProfile: Bluetooth service connected
11-03 18:26:34.327  3782  3806 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.327   930   930 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.328  5655  5666 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.328   930   930 D BluetoothHeadset: Proxy object connected
,11-03 18:26:34.329  3782  3983 D BluetoothHeadset: Proxy object connected
,11-03 18:26:34.329   930   947 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.330  5655  5655 D HeadsetProfile: Bluetooth service connected
,11-03 18:26:34.337  5655  5830 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.338  3137  3148 D BluetoothHeadset: Proxy object connected
11-03 18:26:34.338  5655  5655 D HeadsetProfile: Bluetooth service connected
11-03 18:26:34.338  3137  3137 D HeadsetProfile: Bluetooth service connected
,11-03 18:26:34.344   930   947 D BluetoothHeadset: Proxy object connected
,11-03 18:26:34.718   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:35.722   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:36.725   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:37.689  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 18:26:37.698  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 18:26:37.699  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:37.699  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f57cef2 removed from the list
11-03 18:26:37.699  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 18:26:37.704  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 18:26:37.704  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9d0943 added. We now have 4 listener(s)
,11-03 18:26:37.704  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:37.712   930  4060 D WifiService: setWifiEnabled: false pid=5588, uid=10077
,11-03 18:26:37.712   930  4060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 18:26:42.725  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 18:26:42.726   930  3202 D WifiService: setWifiEnabled: true pid=5588, uid=10077
,11-03 18:26:42.727   930  3202 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 18:26:42.741   508   923 D SoftapController: Softap fwReload - Ok
,11-03 18:26:42.746   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:42.747   508   923 D CommandListener: Trying to bring down wlan0
11-03 18:26:42.748   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-03 18:26:42.754   930  2956 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 18:26:43.562   930  2956 D wifi    : set interface wlan0 flags (UP)
11-03 18:26:43.564   930  2956 I WifiHAL : Initializing wifi
11-03 18:26:43.564   930  2956 I WifiHAL : Creating socket
,11-03 18:26:43.571   930  2956 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 18:26:43.572   930  2956 D wifi    : Did set static halHandle = 0x7f7f232080
11-03 18:26:43.572   930  2956 D wifi    : halHandle = 0x7f7f232080, mVM = 0x7f9b8cd140, mCls = 0x10148a
11-03 18:26:43.572   930  2956 D wifi    : array field set
,11-03 18:26:43.572   930  2956 I WifiNative-HAL: interface[0] = wlan0
11-03 18:26:43.575   930  5848 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547593855104
,11-03 18:26:43.575   930  5848 D wifi    : waitForHalEvents called, vm = 0x7f9b8cd140, obj = 0x10148a, env = 0x7f82e7e400
11-03 18:26:43.577   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 18:26:43.648  5849  5849 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 18:26:43.680   930  2956 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 18:26:43.721  5849  5849 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 18:26:43.770  5849  5849 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 18:26:43.770  5849  5849 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 18:26:43.823   930  2956 D WifiConfigStore: Loading config and enabling all networks 
,11-03 18:26:43.850   930  2956 D WifiConfigStore: loaded 0 passpoint configs
11-03 18:26:43.852   930  2956 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-03 18:26:43.852   930  2956 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 18:26:43.853   930  2956 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 18:26:43.854   930  2956 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 18:26:43.855   930  2956 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-03 18:26:43.856   930  2956 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 18:26:43.857   930  2956 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 18:26:43.857   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 18:26:43.857   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 18:26:43.857   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-03 18:26:43.857   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 18:26:43.857   930  2956 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 18:26:43.881  4550  4550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 18:26:43.882   930  2956 D WifiNative-HAL: Setting external_sim to 1
,11-03 18:26:43.883   930  2956 D wifi    : setting dfs flag to true, 0x7f805e6800
,11-03 18:26:43.884   930  2956 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 18:26:43.885   930  2956 D wifi    : setting scan oui 0x7f805e6800
11-03 18:26:43.885   930  2956 D WifiHAL : Sending mac address OUI
,11-03 18:26:43.892   930  2956 E native  : do suspend true
,11-03 18:26:43.912   930  2956 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 18:26:43.912   930   930 D RttService: SCAN_AVAILABLE : 3
11-03 18:26:43.912   508   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-03 18:26:43.913   930  3076 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 18:26:43.915   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:43.941   930  2955 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
11-03 18:26:43.942   930  2955 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 18:26:43.961   930  2955 D WifiNative-HAL: p2pGetDeviceAddress
11-03 18:26:43.962   930  2955 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 18:26:43.969   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=175696 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-03 18:26:46.909  5849  5849 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 18:26:46.917  5849  5849 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 18:26:46.923  5849  5849 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 18:26:46.931  5849  5849 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 18:26:46.990   930  2956 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 18:26:46.993   930  2956 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-03 18:26:46.993   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 18:26:47.014   930  2956 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 18:26:47.059   930  2956 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 18:26:47.422  5849  5849 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 18:26:47.464  5849  5849 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 18:26:47.466  5849  5849 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 18:26:47.481   930  2956 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 18:26:47.481   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 18:26:47.482   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 18:26:47.504   930  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 18:26:47.521   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:47.529   930  2956 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 18:26:47.535   930  2956 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 18:26:47.547   930  5854 D DhcpClient: Receive thread started
,11-03 18:26:47.647   930  2956 E native  : do suspend false
,11-03 18:26:47.674   930  5853 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 18:26:47.714   930  5854 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-03 18:26:47.715   930  5853 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
11-03 18:26:47.717   930  5853 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 18:26:47.731   930  5854 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 18:26:47.732   930  5853 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 18:26:47.736   508   923 D CommandListener: Setting iface cfg
,11-03 18:26:47.742   930  2956 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 18:26:47.746   930  2956 E native  : do suspend true
11-03 18:26:47.747   930  5853 D DhcpClient: Scheduling renewal in 86399s
,11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 18:26:47.753  5588  5636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 18:26:47.757  5588  5636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 18:26:47.757  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:26:47.757  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9d0943 removed from the list
11-03 18:26:47.757  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:47.763  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-03 18:26:47.764  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-03 18:26:47.766   930  2956 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-03 18:26:47.767  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b8e4254 Bundle[{}]
11-03 18:26:47.767   930  2956 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 18:26:47.768  5588  5636 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 18:26:47.768  5588  5636 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 18:26:47.769   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-03 18:26:47.769  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 18:26:47.770  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 18:26:47.771   930  2966 D ConnectivityService: Adding iface wlan0 to network 102
,11-03 18:26:47.771   930  2956 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-03 18:26:47.771  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-03 18:26:47.772  5588  5636 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 18:26:47.781  5588  5636 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-03 18:26:47.782  5588  5636 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 18:26:47.782  5588  5636 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-03 18:26:47.784  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 18:26:47.785  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a818bc0 added. We now have 3 listener(s)
11-03 18:26:47.786  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:26:47.786  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.786  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.786  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 18:26:47.787  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d30f9 added. We now have 4 listener(s)
11-03 18:26:47.787  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:47.787  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 18:26:47.790  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 18:26:47.790  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fe83e added. We now have 4 listener(s)
11-03 18:26:47.792  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:26:47.792  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.792  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.792  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 18:26:47.792  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcf69f added. We now have 5 listener(s)
11-03 18:26:47.792  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.792  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:26:47.792  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.792  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:26:47.792  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.792  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.792  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.793  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a818bc0 removed from the list
11-03 18:26:47.793  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:26:47.793  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d30f9 removed from the list
11-03 18:26:47.793  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:47.793  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.794  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.794  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.794  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.794  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 18:26:47.795  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.795  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.795  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d30f9 not in the list
11-03 18:26:47.795  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.796  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.796  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.796  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.796  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.797  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.797  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.797  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcf69f removed from the list
11-03 18:26:47.797  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.797  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.797  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.797  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fe83e removed from the list
11-03 18:26:47.797  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 18:26:47.798  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3a3ec added. We now have 3 listener(s)
11-03 18:26:47.799  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:26:47.799  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.799  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.799  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.800  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196e3b5 added. We now have 4 listener(s)
11-03 18:26:47.800  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.801  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 18:26:47.802  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:26:47.802  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99e4a4a added. We now have 4 listener(s)
,11-03 18:26:47.804  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 18:26:47.804  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.804  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.804  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.804  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2445dbb added. We now have 5 listener(s)
11-03 18:26:47.804  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.804  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:26:47.805  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 18:26:47.805  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 18:26:47.805  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:26:47.805  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 18:26:47.806  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 18:26:47.810  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 18:26:47.810  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 18:26:47.810  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 18:26:47.813  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.813  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 18:26:47.814  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 18:26:47.814  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 18:26:47.814  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 18:26:47.818  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.818  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 18:26:47.818  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 18:26:47.818  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 18:26:47.818  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 18:26:47.818  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.819  5588  5636 D BluetoothAdapter: STATE_ON
,11-03 18:26:47.822   930  2966 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-03 18:26:47.822  5794  5805 D BtGatt.GattService: registerClient() - UUID=ae173143-a5e9-4337-9739-8a8929e8d085
11-03 18:26:47.822   930  2966 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-03 18:26:47.823  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=ae173143-a5e9-4337-9739-8a8929e8d085, clientIf=5
11-03 18:26:47.824   930  2966 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-03 18:26:47.824  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 18:26:47.824  5794  5822 D BtGatt.GattService: start scan with filters
,11-03 18:26:47.825   930  2966 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-03 18:26:47.827   930  2966 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 18:26:47.832   930  2966 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 18:26:47.832  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 18:26:47.833  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.833  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 18:26:47.833  5794  5813 D BtGatt.ScanManager: handling starting scan
11-03 18:26:47.833  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.833  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 18:26:47.833  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-03 18:26:47.833  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.833  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 18:26:47.833  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 18:26:47.833  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.833  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.834  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 18:26:47.834  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 18:26:47.834  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.835  5794  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bbf3ec1
11-03 18:26:47.836   930  2966 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-03 18:26:47.836  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.836  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:26:47.836   930  2966 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-03 18:26:47.837  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.837   930  2966 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-03 18:26:47.837  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.837   930  2966 D ConnectivityService:    accepting network in place of null
11-03 18:26:47.837  5588  5636 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-03 18:26:47.837   930  2956 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 18:26:47.837  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.837   930  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 18:26:47.837  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 18:26:47.837  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.837  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.837  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.837  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 18:26:47.837  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.837   930  2966 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 18:26:47.842  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.842  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.842  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.842  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.842  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 18:26:47.843  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:26:47.843  5794  5810 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 18:26:47.843  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.843  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 18:26:47.843  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 18:26:47.843  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.843  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.844  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.844  5794  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 18:26:47.844  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 18:26:47.844  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.846  5588  5636 D BluetoothAdapter: STATE_ON
,11-03 18:26:47.847  5794  5822 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 18:26:47.847  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 18:26:47.848  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:26:47.848  5794  5805 D BtGatt.GattService: stopScan() - queue size =1
11-03 18:26:47.849  5794  5833 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.849  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.849  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.849  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.850  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.850  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 18:26:47.850  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 18:26:47.850  5794  5813 D BtGatt.ScanManager: Starting BLE batch scan
11-03 18:26:47.850  5794  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 18:26:47.850  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 18:26:47.851  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.852  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.852  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:26:47.852  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.852  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.852  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:26:47.852  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:26:47.852  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 18:26:47.852  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.852  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 18:26:47.852  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 18:26:47.852  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.852  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.852  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 18:26:47.853  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.854  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:26:47.854  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.854  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:26:47.854  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.854  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.854  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.854  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3a3ec removed from the list
11-03 18:26:47.854  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.854  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196e3b5 removed from the list
11-03 18:26:47.854  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:47.855  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.855  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.855  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.855  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.855  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-0,3 18:26:47.855  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:26:47.855  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.855  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.855  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.855  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.855  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.856  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.856  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196e3b5 not in the list
11-03 18:26:47.856  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.856  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.856  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.857  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.857  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.857  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.857  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.857  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2445dbb removed from the list
11-03 18:26:47.857  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.857  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.857  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.857  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99e4a4a removed from the list
11-03 18:26:47.857  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:26:47.858  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dec8484 added. We now have 3 listener(s)
11-03 18:26:47.859  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 18:26:47.859  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.859  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.859  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.859  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd46d added. We now have 4 listener(s)
11-03 18:26:47.859  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.860  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 18:26:47.860  5794  5810 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 18:26:47.860  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.861  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:26:47.861  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51dd8a2 added. We now have 4 listener(s)
11-03 18:26:47.862  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:26:47.862  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.862  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.862  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.862  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@502c933 added. We now have 5 listener(s)
11-03 18:26:47.863  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.863  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:26:47.864  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:26:47.864  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 18:26:47.864  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 18:26:47.864  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 18:26:47.864  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 18:26:47.865  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 18:26:47.867   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 18:26:47.868  5794  ,5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 18:26:47.868  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.869  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 18:26:47.869  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 18:26:47.869  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 18:26:47.869  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 18:26:47.872  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.872  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 18:26:47.873  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 18:26:47.873  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 18:26:47.873  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 18:26:47.875  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 18:26:47.875  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.876  5794  5810 E BtGatt.ContextMap: Context not found for ID 5
,11-03 18:26:47.878  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.878  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 18:26:47.878  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 18:26:47.878  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 18:26:47.878  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 18:26:47.879  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.880  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:26:47.882  5794  5822 D BtGatt.GattService: registerClient() - UUID=e90f919a-b992-4be3-b0e1-dc2c06e9b919
,11-03 18:26:47.883  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=e90f919a-b992-4be3-b0e1-dc2c06e9b919, clientIf=5
11-03 18:26:47.883  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 18:26:47.883  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.883  5588  5629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 18:26:47.883  5794  5813 D BtGatt.ScanManager: stopping BLe Batch
,11-03 18:26:47.884  5794  5804 D BtGatt.GattService: start scan with filters
,11-03 18:26:47.886  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 18:26:47.887  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.887  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 18:26:47.887  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.887  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 18:26:47.887  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 18:26:47.887  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.887  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 18:26:47.887  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 18:26:47.887  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.887  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.887  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 18:26:47.888  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 18:26:47.888  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.890  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 18:26:47.890  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.890  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:26:47.890  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.890  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 18:26:47.890  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.890  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.890  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.890  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:26:47.890  5588  5636 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 18:26:47.891  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:26:47.891  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.891  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:26:47.891  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.891  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.891  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.891  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.891  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 18:26:47.891  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dec8484 removed from the list
11-03 18:26:47.891  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.891  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd46d removed from the list
11-03 18:26:47.891  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:47.891  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.891  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.891  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-03 18:26:47.891  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 18:26:47.891  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.891  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.891  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.892  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.893  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.893  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.893  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.893  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.894  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.894  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.894  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.894  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd46d not in the list
11-03 18:26:47.894  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.894  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.895  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.895  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 18:26:47.895  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.896  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 18:26:47.896  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:26:47.898  5794  5813 D BtGatt.ScanManager: handling starting scan
11-03 18:26:47.898  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:26:47.898   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 18:26:47.898  5794  5805 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 18:26:47.898  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-03 18:26:47.899  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:26:47.900  5794  5833 D BtGatt.GattService: stopScan() - queue size =1
11-03 18:26:47.900  5794  5804 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 18:26:47.901  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 18:26:47.901  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.901  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 18:26:47.901  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.901  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.902  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 18:26:47.902  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 18:26:47.903  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 18:26:47.904  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.905   930  2966 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-03 18:26:47.905   930  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 18:26:47.905  3733  3882 W QCNEJ   : |CORE| network available: 102
,11-03 18:26:47.905  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.906  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:26:47.906  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.906  5794  5810 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 18:26:47.906  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.906  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.906  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.906  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 18:26:47.906  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.906  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@502c933 removed from the list
11-03 18:26:47.906  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.906  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.906  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.906  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:26:47.906  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51dd8a2 removed from the list
11-03 18:26:47.906  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 18:26:47.906  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 18:26:47.906  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.906  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 18:26:47.906  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 18:26:47.907  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.907  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.907  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 18:26:47.907  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 18:26:47.907  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:26:47.907  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fde01c added. We now have 3 listener(s)
11-03 18:26:47.907   930   947 D Tethering: MasterInitialState.processMessage what=3
11-03 18:26:47.908  5794  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 18:26:47.908  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 18:26:47.908  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.908  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.908  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.908  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5092425 added. We now have 4 listener(s)
11-03 18:26:47.908  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.906   930  2966 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-03 18:26:47.910  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 18:26:47.910  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.910  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.910  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.910  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:26:47.910  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 18:26:47.911  3733  3882 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 18:26:47.911  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:26:47.912  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785d9fa added. We now have 4 listener(s)
11-03 18:26:47.913  3733  3882 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 18:26:47.913  3733  3882 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-03 18:26:47.913  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:26:47.914  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.914  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.914  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 18:26:47.914  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc42bab added. We now have 5 listener(s)
11-03 18:26:47.914  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 18:26:47.914  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:26:47.914  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 18:26:47.914  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.914  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 18:26:47.915  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 18:26:47.915  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 18:26:47.915  5794  5813 D BtGatt.ScanManager: Starting BLE batch scan
11-03 18:26:47.915  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 18:26:47.915  5794  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 18:26:47.916  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 18:26:47.925  5794  5810 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 18:26:47.925  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 18:26:47.925  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.925  5588  5636 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 18:26:47.925  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 18:26:47.929  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.929  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 18:26:47.929  3968  3968 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-03 18:26:47.929  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 18:26:47.930  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 18:26:47.930  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 18:26:47.930  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 18:26:47.930  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:26:47.932  3986  3986 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 18:26:47.934  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.934  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 18:26:47.934  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 18:26:47.934  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 18:26:47.935  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 18:26:47.935  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 18:26:47.935  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.936  5588  5636 D BluetoothAdapter: STATE_ON
,11-03 18:26:47.937  3986  3986 D SystemUpdateService: onCreate
,11-03 18:26:47.939  5794  5804 D BtGatt.GattService: registerClient() - UUID=de6d8f78-7194-406f-bea5-65ff4c1eedda
11-03 18:26:47.940  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=de6d8f78-7194-406f-bea5-65ff4c1eedda, clientIf=5
11-03 18:26:47.940  5588  5629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 18:26:47.941  5794  5822 D BtGatt.GattService: start scan with filters
11-03 18:26:47.941  3986  3986 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 18:26:47.941  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 18:26:47.941  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:26:47.943  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 18:26:47.944  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.944  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 18:26:47.944  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.944  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.944  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 18:26:47.944  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 18:26:47.944  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.944  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 18:26:47.944  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 18:26:47.944  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.944  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.944  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 18:26:47.945  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 18:26:47.945  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.947  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.947  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:26:47.947  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.947  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.948  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 18:26:47.950  3986  5863 I SystemUpdateService: active receiver: enabled
11-03 18:26:47.951  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.951  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.951  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 18:26:47.951  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.951  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 18:26:47.953  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:26:47.953  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.953  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:26:47.953  3986  3986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-03 18:26:47.953  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.953  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.954  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 18:26:47.954  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.954  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.954  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 18:26:47.954  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.954  5794  5813 D BtGatt.ScanManager: stopping BLe Batch
11-03 18:26:47.954  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fde01c removed from the list
11-03 18:26:47.954  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.954  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5092425 removed from the list
11-03 18:26:47.954  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:47.954  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 18:26:47.954  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.954  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.954  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-03 18:26:47.954  5588  5636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 18:26:47.954  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 18:26:47.954  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.955  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.955  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.956  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.956  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 18:26:47.956  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.956  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5092425 not in the list
11-03 18:26:47.956  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.956  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 18:26:47.956  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.957  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:26:47.957  5794  5833 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 18:26:47.957  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 18:26:47.960  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 18:26:47.960  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.960  3986  4252 I iu.UploadsManager: num queued entries: 0
11-03 18:26:47.960  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 18:26:47.961  3986  4252 I iu.UploadsManager: num updated entries: 0
11-03 18:26:47.962  3986  4252 I iu.SyncManager: NEXT; no task
11-03 18:26:47.962  5588  5636 D BluetoothAdapter: STATE_ON
11-03 18:26:47.962  5794  5822 D BtGatt.GattService: stopScan() - queue size =0
11-03 18:26:47.963  5794  5804 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 18:26:47.963  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 18:26:47.963  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.963  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 18:26:47.963  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.964  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 18:26:47.964  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 18:26:47.964  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 18:26:47.965  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.965  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 18:26:47.965  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.966  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-03 18:26:47.966  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 18:26:47.966  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.966  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.967  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 18:26:47.967  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.967  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.967  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc42bab removed from the list
11-03 18:26:47.967  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.967  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:26:47.967  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.967  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.967  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 18:26:47.967  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785d9fa removed from the list
11-03 18:26:47.967  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 18:26:47.967  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.967  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 18:26:47.967  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 18:26:47.967  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.967  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.967  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 18:26:47.967  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.967  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 18:26:47.967  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13c16b4 added. We now have 3 listener(s)
11-03 18:26:47.968  5794  5813 D BtGatt.ScanManager: handling starting scan
11-03 18:26:47.968  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 18:26:47.969  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.969  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.969  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.969  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.969  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 18:26:47.969  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.969  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 18:26:47.969  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b8b2dd added. We now have 4 listener(s)
11-03 18:26:47.969  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 18:26:47.969  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.969  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 18:26:47.973  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 18:26:47.974  5794  5810 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 18:26:47.974  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:26:47.974  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111ae52 added. We now have 4 listener(s)
11-03 18:26:47.974  5794  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 18:26:47.975  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 18:26:47.975  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 18:26:47.975  5588  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 18:26:47.975  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 18:26:47.975  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d106523 added. We now have 5 listener(s)
11-03 18:26:47.975  5588  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 18:26:47.976  5588  5636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 18:26:47.976  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.976  5588  5636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 18:26:47.976  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.976  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.976  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.976  3986  3986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 18:26:47.976  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13c16b4 removed from the list
11-03 18:26:47.976  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.976  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b8b2dd removed from the list
11-03 18:26:47.976  5588  5636 D io.jxcore.node.ConnectivityMonitor: stop
11-03 18:26:47.976  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.977  3986  3986 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 18:26:47.978  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.978  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.978  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.978  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.978  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.978  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 18:26:47.978  5588  5636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b8b2dd not in the list
11-03 18:26:47.979  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.980  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.980  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.980  5588  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-03 18:26:47.980  5692  5692 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-03 18:26:47.980  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 18:26:47.980  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 18:26:47.980  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:47.980  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 18:26:47.980  5588  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 18:26:47.981  5794  5813 D BtGatt.ScanManager: Starting BLE batch scan
11-03 18:26:47.981  5794  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 18:26:47.981  5588  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d106523 removed from the list
11-03 18:26:47.981  5588  5636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 18:26:47.981  5588  5636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 18:26:47.981  5588  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 18:26:47.981  5588  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111ae52 removed from the list
11-03 18:26:47.982  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 18:26:47.982  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 18:26:47.982  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 18:26:47.982  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:26:47.982  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-03 18:26:47.982  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 18:26:47.985  5692  5692 D SprintDMHelper: simOperator: 
11-03 18:26:47.985  5692  5692 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 18:26:47.989  3986  5863 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 18:26:47.995  5794  5810 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 18:26:47.995  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:26:48.002  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 18:26:48.002  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 18:26:48.004  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:26:48.007  3986  5863 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-03 18:26:48.007  3986  5863 I SystemUpdateService: now status is 0 (complete)
11-03 18:26:48.007  3986  5863 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-03 18:26:48.007  3986  5863 I SystemUpdateService: file has been verified
11-03 18:26:48.007  3986  5863 I SystemUpdateService: OTA package size = 21989297
,11-03 18:26:48.011  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 18:26:48.011  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:48.011  5794  5810 E BtGatt.ContextMap: Context not found for ID 5
,11-03 18:26:48.018  3986  5863 I SystemUpdateService: showing system update notification
11-03 18:26:48.019  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 18:26:48.019  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:48.019  5794  5813 D BtGatt.ScanManager: stopping BLe Batch
,11-03 18:26:48.024  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 18:26:48.024  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:48.024  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 18:26:48.028   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 18:26:48.030   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179756, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-03 18:26:48.030  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 18:26:48.030  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 18:26:48.031  3986  3986 D SystemUpdateService: onDestroy
,11-03 18:26:48.203   930  5851 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 18:26:48.268   930  5851 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 17:26:48 GMT], X-Android-Received-Millis=[1478194008267], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478194008239]}
,11-03 18:26:48.269   930  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 18:26:48.270   930  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-03 18:26:48.270   930  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 18:26:48.272   930  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 18:26:48.357  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 18:26:48.411  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 18:26:48.471  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 18:26:48.907   930  2966 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 18:26:50.174  5588  5871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 18:26:50.174  5588  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 18:26:50.985  5588  5871 W !!      : call onHalfStreamCopied
,11-03 18:26:50.985  5588  5871 I testCopyDataAndClose: closing input stream
,11-03 18:26:51.165  3589  5873 I VacuumService: Vacuum at: now=1478194011165 tag=VacuumService
,11-03 18:26:51.213  3589  5876 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 18:26:51.251  3589  5874 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-03 18:26:51.254  3589  5874 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 18:26:51.277  3589  5874 W Uploader:  no longer exists, so no auth token.
,11-03 18:26:51.283  3589  5876 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 18:26:51.540  3589  5878 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 18:26:51.666  3589  5876 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 18:26:51.726  3589  5874 W Uploader:  no longer exists, so no auth token.
,11-03 18:26:51.736  3589  5878 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 18:26:51.759  5588  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 18:26:51.820  3589  5876 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 18:26:51.919  3589  5878 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 18:26:55.651  3986  5883 I EventLogService: Aggregate from 1478192215559 (log), 1478192215559 (data)
,11-03 18:26:55.844   930  2966 D ConnectivityService: handlePromptUnvalidated 102
,11-03 18:26:56.040  5588  5885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:26:56.040  5588  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 18:26:56.729   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:57.734   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:58.041  5588  5636 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-03 18:26:58.041  5588  5636 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 18:26:58.041  5588  5636 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-03 18:26:58.064  5588  5885 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-03 18:26:58.065  5588  5885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:26:58.065  5588  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-03 18:26:58.200  5588  5886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 18:26:58.200  5588  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 18:26:58.735   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:59.737   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 18:26:59.806  5588  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 18:27:00.738   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:01.739   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 18:27:04.019  5588  5887 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:27:04.019  5588  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-03 18:27:04.020  5588  5887 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 18:27:04.021  5588  5887 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:27:04.021  5588  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-03 18:27:04.023  5588  5636 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-03 18:27:04.025  5588  5888 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:27:04.025  5588  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 18:27:04.026  5588  5888 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-03 18:27:04.026  5588  5888 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:27:04.026  5588  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 18:27:04.027  5588  5888 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 18:27:04.027  5588  5888 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 18:27:04.027  5588  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 18:27:04.032  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-03 18:27:04.032  5588  5636 I jxcore-log: 
,11-03 18:27:04.032  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-03 18:27:04.032  5588  5636 I jxcore-log: 
11-03 18:27:04.032  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-03 18:27:04.032  5588  5636 I jxcore-log: 
11-03 18:27:04.032  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-03 18:27:04.032  5588  5636 I jxcore-log: 
11-03 18:27:04.033  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'Total duration:  91952'
11-03 18:27:04.033  5588  5636 I jxcore-log: 
,11-03 18:27:04.035  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-03 18:27:04.035  5588  5636 I jxcore-log: 
,11-03 18:27:04.038  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 18:27:04.038  5588  5636 I jxcore-log: 
,11-03 18:27:04.039  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 18:27:04.039  5588  5636 I jxcore-log: 
11-03 18:27:04.040  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 18:27:04.040  5588  5636 I jxcore-log: 
11-03 18:27:04.040  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 18:27:04.040  5588  5636 I jxcore-log: 
11-03 18:27:04.041  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.041  5588  5636 I jxcore-log: 
,11-03 18:27:04.041  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 18:27:04.041  5588  5636 I jxcore-log: 
,11-03 18:27:04.041  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.041  5588  5636 I jxcore-log: 
11-03 18:27:04.041  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 18:27:04.041  5588  5636 I jxcore-log: 
11-03 18:27:04.042  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 18:27:04.042  5588  5636 I jxcore-log: 
11-03 18:27:04.042  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 18:27:04.042  5588  5636 I jxcore-log: 
,11-03 18:27:04.042  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 18:27:04.042  5588  5636 I jxcore-log: 
11-03 18:27:04.042  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.042  5588  5636 I jxcore-log: 
11-03 18:27:04.043  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 18:27:04.043  5588  5636 I jxcore-log: 
,11-03 18:27:04.043  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.043  5588  5636 I jxcore-log: 
11-03 18:27:04.043  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 18:27:04.043  5588  5636 I jxcore-log: 
11-03 18:27:04.043  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.043  5588  5636 I jxcore-log: 
11-03 18:27:04.043  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 18:27:04.043  5588  5636 I jxcore-log: 
,11-03 18:27:04.044  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 18:27:04.044  5588  5636 I jxcore-log: 
,11-03 18:27:04.044  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 18:27:04.044  5588  5636 I jxcore-log: 
11-03 18:27:04.044  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 18:27:04.044  5588  5636 I jxcore-log: 
11-03 18:27:04.045  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 18:27:04.045  5588  5636 I jxcore-log: 
11-03 18:27:04.045  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 18:27:04.045  5588  5636 I jxcore-log: 
11-03 18:27:04.045  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 18:27:04.045  5588  5636 I jxcore-log: 
,11-03 18:27:04.046  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 18:27:04.046  5588  5636 I jxcore-log: 
11-03 18:27:04.047  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 18:27:04.047  5588  5636 I jxcore-log: 
,11-03 18:27:04.047  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 18:27:04.047  5588  5636 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-03 18:27:04.047  5588  5636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 18:27:04.047  5588  5636 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-03 18:27:04.048  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 18:27:04.048  5588  5636 I jxcore-log: 
11-03 18:27:04.048  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.048  5588  5636 I jxcore-log: 
11-03 18:27:04.048  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 18:27:04.048  5588  5636 I jxcore-log: 
11-03 18:27:04.048  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.048  5588  5636 I jxcore-log: 
11-03 18:27:04.048  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 18:27:04.048  5588  5636 I jxcore-log: 
11-03 18:27:04.049  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 18:27:04.049  5588  5636 I jxcore-log: 
,11-03 18:27:04.054  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 18:27:04.054  5588  5636 I jxcore-log: 
11-03 18:27:04.054  5588  5636 I jxcore-log: 2016-11-03 17:27:04 - WARN testUtils: 'myNameCallback not set!'
11-03 18:27:04.054  5588  5636 I jxcore-log: 
11-03 18:27:04.056  5588  5588 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-03 18:27:06.114  5588  5636 I jxcore-log: 2016-11-03 17:27:06 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-03 18:27:06.114  5588  5636 I jxcore-log: 
,11-03 18:27:06.116  5588  5636 I jxcore-log: 2016-11-03 17:27:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 18:27:06.116  5588  5636 I jxcore-log: 
,11-03 18:27:06.465  5588  5636 I jxcore-log: 2016-11-03 17:27:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 18:27:06.465  5588  5636 I jxcore-log: 
,11-03 18:27:06.478  5588  5636 I jxcore-log: 2016-11-03 17:27:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 18:27:06.478  5588  5636 I jxcore-log: 
,11-03 18:27:07.609  5588  5636 I jxcore-log: 2016-11-03 17:27:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 18:27:07.609  5588  5636 I jxcore-log: 
,11-03 18:27:07.724   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=199451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:27:07.802  5588  5636 I jxcore-log: 2016-11-03 17:27:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 18:27:07.802  5588  5636 I jxcore-log: 
,11-03 18:27:07.808  5588  5636 I jxcore-log: 2016-11-03 17:27:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 18:27:07.808  5588  5636 I jxcore-log: 
,11-03 18:27:07.813  5588  5636 I jxcore-log: 2016-11-03 17:27:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 18:27:07.813  5588  5636 I jxcore-log: 
,11-03 18:27:08.305  5588  5636 I jxcore-log: 2016-11-03 17:27:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 18:27:08.305  5588  5636 I jxcore-log: 
,11-03 18:27:08.352  5588  5636 I jxcore-log: 2016-11-03 17:27:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 18:27:08.352  5588  5636 I jxcore-log: 
,11-03 18:27:08.366  5588  5636 I jxcore-log: 2016-11-03 17:27:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 18:27:08.366  5588  5636 I jxcore-log: 
,11-03 18:27:08.370  5588  5636 I jxcore-log: 2016-11-03 17:27:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 18:27:08.370  5588  5636 I jxcore-log: 
,11-03 18:27:08.669  5588  5636 I jxcore-log: 2016-11-03 17:27:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 18:27:08.669  5588  5636 I jxcore-log: 
,11-03 18:27:08.802  5588  5636 I jxcore-log: 2016-11-03 17:27:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 18:27:08.802  5588  5636 I jxcore-log: 
,11-03 18:27:09.169  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 18:27:09.169  5588  5636 I jxcore-log: 
,11-03 18:27:09.178  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 18:27:09.178  5588  5636 I jxcore-log: 
,11-03 18:27:09.182  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 18:27:09.182  5588  5636 I jxcore-log: 
,11-03 18:27:09.187  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 18:27:09.187  5588  5636 I jxcore-log: 
,11-03 18:27:09.193  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 18:27:09.193  5588  5636 I jxcore-log: 
,11-03 18:27:09.221  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 18:27:09.221  5588  5636 I jxcore-log: 
,11-03 18:27:09.256  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 18:27:09.256  5588  5636 I jxcore-log: 
,11-03 18:27:09.262  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 18:27:09.262  5588  5636 I jxcore-log: 
,11-03 18:27:09.267  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 18:27:09.267  5588  5636 I jxcore-log: 
,11-03 18:27:09.281  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 18:27:09.281  5588  5636 I jxcore-log: 
,11-03 18:27:09.285  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 18:27:09.285  5588  5636 I jxcore-log: 
,11-03 18:27:09.290  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 18:27:09.290  5588  5636 I jxcore-log: 
,11-03 18:27:09.295  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 18:27:09.295  5588  5636 I jxcore-log: 
,11-03 18:27:09.307  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 18:27:09.307  5588  5636 I jxcore-log: 
,11-03 18:27:09.312  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 18:27:09.312  5588  5636 I jxcore-log: 
,11-03 18:27:09.333  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 18:27:09.333  5588  5636 I jxcore-log: 
,11-03 18:27:09.342  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 18:27:09.342  5588  5636 I jxcore-log: 
,11-03 18:27:09.364  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 18:27:09.364  5588  5636 I jxcore-log: 
,11-03 18:27:09.373  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 18:27:09.373  5588  5636 I jxcore-log: 
,11-03 18:27:09.385  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 18:27:09.385  5588  5636 I jxcore-log: 
,11-03 18:27:09.395  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 18:27:09.395  5588  5636 I jxcore-log: 
,11-03 18:27:09.400  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 18:27:09.400  5588  5636 I jxcore-log: 
,11-03 18:27:09.420  5588  5636 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 18:27:09.421  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 18:27:09.421  5588  5636 I jxcore-log: 
,11-03 18:27:09.683  5588  5636 I jxcore-log: 2016-11-03 17:27:09 - DEBUG CoordinatedClient: 'connected to the test server'
11-03 18:27:09.683  5588  5636 I jxcore-log: 
,11-03 18:27:14.498   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=206224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:27:20.625  3653  3855 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 18:27:20.625  3653  3855 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 18:27:20.659  3589  3589 I ConfigService: onCreate
,11-03 18:27:25.339   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217065, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:27:25.695  3589  3589 I ConfigService: onDestroy
,11-03 18:27:26.740   594   594 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 18:27:26.740   594   594 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 18:27:36.741   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:37.743   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:38.744   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:39.671   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:27:39.746   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:40.747   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:41.748   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 18:27:46.751   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:47.752   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:48.754   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:49.755   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:50.404   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=242130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:27:50.756   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:27:51.757   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 18:28:01.758   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:02.760   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:03.761   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:04.698   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=256424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:28:04.762   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:05.764   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:06.764   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 18:28:15.417   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:28:21.766   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:22.767   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:23.768   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:24.769   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:25.770   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:26.771   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 18:28:29.737   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=281464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:28:45.524   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:28:46.772   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:47.774   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:48.775   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:49.776   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:50.777   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:28:51.778   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 18:28:54.764   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 18:29:10.511   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=322237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:29:16.778   594   594 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 18:29:16.779   594   594 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 18:29:19.792   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=331518, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 18:29:31.780   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:32.782   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:33.783   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:34.785   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:35.524   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:29:35.787   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:36.489   930  3606 I ActivityManager: Start proc 5900:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-03 18:29:36.534  5900  5900 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-03 18:29:36.609  5900  5912 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-03 18:29:36.696  5900  5912 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-03 18:29:36.738  5900  5912 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-03 18:29:36.762  5900  5900 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-03 18:29:36.768  5925  5925 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads1841368462.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1841368462.dex
,11-03 18:29:36.787   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 18:29:36.799  5925  5925 I dex2oat : dex2oat took 32.032ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1257KB free=1046KB
,11-03 18:29:36.894  5900  5900 W InstanceID/Rpc: Found 10012
,11-03 18:29:36.949   930  3606 I ActivityManager: Killing 5464:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-03 18:29:41.789   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:42.790   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:43.792   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:44.793   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:44.804   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=356530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:29:45.794   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:46.795   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 18:29:55.524   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:29:56.796   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:57.798   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:58.799   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:29:59.801   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:00.802   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:01.803   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 18:30:09.844   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:30:16.804   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:17.806   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:18.807   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:19.809   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:20.592   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392318, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:30:20.810   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:21.811   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 18:30:34.871   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=406597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 18:30:41.813   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:42.814   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:43.816   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:44.817   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:45.604   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=417330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:30:45.818   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 18:30:46.819   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 18:30:53.418   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=425144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 18:31:10.628   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=442354, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 18:31:11.820   594   594 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-03 18:31:11.821   594   594 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 18:31:16.462  5588  5636 I jxcore-log: 2016-11-03 17:31:16 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-03 18:31:16.462  5588  5636 I jxcore-log: 
,11-03 18:31:16.632  5588  5636 I jxcore-log: 2016-11-03 17:31:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:16.632  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:16.632  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:16.632  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:16.632  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:16.632  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:16.632  5588  5636 I jxcore-log: 
,11-03 18:31:16.638  5588  5636 I jxcore-log: 2016-11-03 17:31:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:16.638  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:16.638  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:16.638  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:16.638  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:16.638  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:16.638  5588  5636 I jxcore-log: 
,11-03 18:31:17.105  5588  5636 I jxcore-log: 2016-11-03 17:31:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:17.105  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:17.105  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:17.105  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:17.105  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:17.105  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:17.105  5588  5636 I jxcore-log: 
,11-03 18:31:17.109  5588  5636 I jxcore-log: 2016-11-03 17:31:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:17.109  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:17.109  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:17.109  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:17.109  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:17.109  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:17.109  5588  5636 I jxcore-log: 
,11-03 18:31:18.145  5588  5636 I jxcore-log: 2016-11-03 17:31:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:18.145  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:18.145  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:18.145  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:18.145  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:18.145  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:18.145  5588  5636 I jxcore-log: 
,11-03 18:31:18.150  5588  5636 I jxcore-log: 2016-11-03 17:31:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:18.150  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:18.150  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:18.150  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:18.150  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:18.150  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:18.150  5588  5636 I jxcore-log: 
,11-03 18:31:19.184  5588  5636 I jxcore-log: 2016-11-03 17:31:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:19.184  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:19.184  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:19.184  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:19.184  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:19.184  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:19.184  5588  5636 I jxcore-log: 
,11-03 18:31:19.188  5588  5636 I jxcore-log: 2016-11-03 17:31:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:19.188  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:19.188  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:19.188  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:19.188  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:19.188  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:19.188  5588  5636 I jxcore-log: 
,11-03 18:31:20.231  5588  5636 I jxcore-log: 2016-11-03 17:31:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:20.231  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:20.231  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:20.231  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:20.231  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:20.231  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:20.231  5588  5636 I jxcore-log: 
,11-03 18:31:20.234  5588  5636 I jxcore-log: 2016-11-03 17:31:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:20.234  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:20.234  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:20.234  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:20.234  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:20.234  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:20.234  5588  5636 I jxcore-log: 
,11-03 18:31:21.272  5588  5636 I jxcore-log: 2016-11-03 17:31:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:21.272  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:21.272  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:21.272  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:21.272  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:21.272  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:21.272  5588  5636 I jxcore-log: 
,11-03 18:31:21.277  5588  5636 I jxcore-log: 2016-11-03 17:31:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:21.277  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:21.277  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:21.277  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:21.277  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:21.277  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:21.277  5588  5636 I jxcore-log: 
,11-03 18:31:21.432   930  5852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=453158, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 18:31:22.316  5588  5636 I jxcore-log: 2016-11-03 17:31:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:22.316  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:22.316  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:22.316  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:22.316  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:22.316  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:22.316  5588  5636 I jxcore-log: 
,11-03 18:31:22.320  5588  5636 I jxcore-log: 2016-11-03 17:31:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:22.320  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:22.320  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:22.320  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:22.320  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:22.320  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:22.320  5588  5636 I jxcore-log: 
,11-03 18:31:23.359  5588  5636 I jxcore-log: 2016-11-03 17:31:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:23.359  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:23.359  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:23.359  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:23.359  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:23.359  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:23.359  5588  5636 I jxcore-log: 
,11-03 18:31:23.364  5588  5636 I jxcore-log: 2016-11-03 17:31:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:23.364  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:23.364  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:23.364  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:23.364  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:23.364  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:23.364  5588  5636 I jxcore-log: 
,11-03 18:31:24.405  5588  5636 I jxcore-log: 2016-11-03 17:31:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:24.405  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:24.405  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:24.405  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:24.405  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:24.405  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:24.405  5588  5636 I jxcore-log: 
,11-03 18:31:24.412  5588  5636 I jxcore-log: 2016-11-03 17:31:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:24.412  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:24.412  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:24.412  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:24.412  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:24.412  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:24.412  5588  5636 I jxcore-log: 
,11-03 18:31:25.489  5588  5636 I jxcore-log: 2016-11-03 17:31:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:25.489  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:25.489  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:25.489  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:25.489  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:25.489  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:25.489  5588  5636 I jxcore-log: 
,11-03 18:31:25.495  5588  5636 I jxcore-log: 2016-11-03 17:31:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:25.495  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:25.495  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:25.495  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:25.495  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:25.495  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:25.495  5588  5636 I jxcore-log: 
,11-03 18:31:26.539  5588  5636 I jxcore-log: 2016-11-03 17:31:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:26.539  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:26.539  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:26.539  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:26.539  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:26.539  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:26.539  5588  5636 I jxcore-log: 
,11-03 18:31:26.546  5588  5636 I jxcore-log: 2016-11-03 17:31:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:26.546  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:26.546  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:26.546  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:26.546  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:26.546  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:26.546  5588  5636 I jxcore-log: 
,11-03 18:31:27.590  5588  5636 I jxcore-log: 2016-11-03 17:31:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:27.590  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:27.590  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:27.590  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:27.590  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:27.590  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:27.590  5588  5636 I jxcore-log: 
,11-03 18:31:27.595  5588  5636 I jxcore-log: 2016-11-03 17:31:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:27.595  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:27.595  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:27.595  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:27.595  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:27.595  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:27.595  5588  5636 I jxcore-log: 
,11-03 18:31:28.626  5588  5636 I jxcore-log: 2016-11-03 17:31:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:28.626  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:28.626  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:28.626  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:28.626  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:28.626  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:28.626  5588  5636 I jxcore-log: 
,11-03 18:31:28.631  5588  5636 I jxcore-log: 2016-11-03 17:31:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:28.631  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:28.631  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:28.631  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:28.631  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:28.631  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:28.631  5588  5636 I jxcore-log: 
,11-03 18:31:29.664  5588  5636 I jxcore-log: 2016-11-03 17:31:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:29.664  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:29.664  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:29.664  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:29.664  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:29.664  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:29.664  5588  5636 I jxcore-log: 
,11-03 18:31:29.669  5588  5636 I jxcore-log: 2016-11-03 17:31:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:29.669  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:29.669  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:29.669  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:29.669  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:29.669  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:29.669  5588  5636 I jxcore-log: 
,11-03 18:31:30.701  5588  5636 I jxcore-log: 2016-11-03 17:31:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 18:31:30.701  5588  5636 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 18:31:30.701  5588  5636 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 18:31:30.701  5588  5636 I jxcore-log: emit@events.js:82:1
11-03 18:31:30.701  5588  5636 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 18:31:30.701  5588  5636 I jxcore-log: emit@events.js:82:1'
11-03 18:31:30.701  5588  5636 I jxcore-log: 
,11-03 18:31:30.712  5588  5636 E jxcore  : Error!: error is undefined
11-03 18:31:30.712  5588  5636 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 18:31:30.717  5588  5636 I jxcore-log: 2016-11-03 17:31:30 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 18:31:30.717  5588  5636 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-03 18:31:30.717  5588  5636 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 18:31:30.717  5588  5636 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 18:31:30.717  5588  5636 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 18:31:30.717  5588  5636 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 18:31:30.717  5588  5636 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 18:31:30.717  5588  5636 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 18:31:30.719  5588  5636 I jxcore-log: 2016-11-03 17:31:30 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 18:31:30.719  5588  5636 I jxcore-log: 
11-03 18:31:30.722  5588  5636 E jxcore-log: TypeError: 
11-03 18:31:30.722  5588  5636 E jxcore-log: error is undefined
11-03 18:31:30.722  5588  5636 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-03 18:31:30.722  5588  5636 E jxcore-log: 
,11-03 18:31:30.790   930  2947 W InputDispatcher: channel 'a6eb53d com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-03 18:31:30.792   930  2947 E InputDispatcher: channel 'a6eb53d com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-03 18:31:30.797   930   940 D GraphicsStats: Buffer count: 2
,11-03 18:31:30.798   930  3606 I WindowState: WIN DEATH: Window{a6eb53d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-03 18:31:30.798   930  3606 W InputDispatcher: Attempted to unregister already unregistered input channel 'a6eb53d com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-03 18:31:30.799   930  2963 D WifiService: Client connection lost with reason: 4
,11-03 18:31:30.806   528   528 I Zygote  : Process 5588 exited cleanly (139)
11-03 18:31:30.809   930  3157 I ActivityManager: Process com.test.thalitest (pid 5588) has died
,11-03 18:31:30.830   930  3157 I ActivityManager: Start proc 5984:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-03 18:31:30.888  5984  5984 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-03 18:31:30.903  5984  5984 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 18:31:30.908  5984  5984 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2633-2634)
,11-03 18:31:30.908  5984  5984 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 18:31:30.917  5984  5984 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a072789}
,11-03 18:31:30.917  5984  5984 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 18:31:30.917  5984  5984 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 18:31:30.920  5984  5984 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 18:31:30.921  5984  5984 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 18:31:30.930  5984  5984 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 18:31:30.937  5984  5984 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 18:31:30.938  5984  5984 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 18:31:30.938  5984  5984 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 18:31:30.938  5984  5984 I Adreno  : Build Date                       : 12/06/15
11-03 18:31:30.938  5984  5984 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 18:31:30.938  5984  5984 I Adreno  : Local Branch                     : mybranch17112971
11-03 18:31:30.938  5984  5984 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 18:31:30.938  5984  5984 I Adreno  : Remote Branch                    : NONE
11-03 18:31:30.938  5984  5984 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 18:31:30.972   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@886176b:true
,11-03 18:31:30.990   397   397 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[16905]" dev="sockfs" ino=16905 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 18:31:30.990   397   397 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[16905]" dev="sockfs" ino=16905 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.004  5984  5984 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 18:31:31.012  5984  5984 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 18:31:31.044  3856  3856 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35815]" dev="sockfs" ino=35815 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.046  5984  6020 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-03 18:31:31.044  3856  3856 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35815]" dev="sockfs" ino=35815 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.044  3202  3202 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[20341]" dev="sockfs" ino=20341 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 18:31:31.044  3202  3202 W Binder_4: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[20341]" dev="sockfs" ino=20341 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.051  5984  6007 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 18:31:31.086  5984  6020 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 18:31:31.094  3202  3202 W Binder_4: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[35818]" dev="sockfs" ino=35818 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.094  3202  3202 W Binder_4: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[35818]" dev="sockfs" ino=35818 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 18:31:31.098   930  3202 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5588 uid 10077
,11-03 18:31:31.100  3836  3836 W Binder_9: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[35817]" dev="sockfs" ino=35817 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.100  3836  3836 W Binder_9: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[35817]" dev="sockfs" ino=35817 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 18:31:31.104  3653  3653 I Keyboard.Facilitator: onFinishInput()
,11-03 18:31:31.121   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +270ms (total +307ms)
,11-03 18:31:31.123  5984  5984 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5984
,11-03 18:31:31.177  5984  5984 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 18:31:31.242  5982  5982 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 18:31:31.259  5982  5982 D AndroidRuntime: CheckJNI is OFF
,11-03 18:31:31.283  5982  5982 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 18:31:31.307  5982  5982 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 18:31:31.321  5982  5982 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 18:31:31.326   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-03 18:31:31.326   930   943 I ActivityManager: Killing 5984:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-03 18:31:31.366   930  3202 D GraphicsStats: Buffer count: 2
,11-03 18:31:31.366   930  3705 I WindowState: WIN DEATH: Window{6cc8b0d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-03 18:31:31.427   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-03 18:31:31.428   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-03 18:31:31.429   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-03 18:31:31.429   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-03 18:31:31.429   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 18:31:31.429   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-03 18:31:31.429   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 18:31:31.429   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-03 18:31:31.429   930   943 I ActivityManager:   Force finishing activity ActivityRecord{12985a5 u0 com.test.thalitest/.MainActivity t68}
11-03 18:31:31.431   930   953 I art     : Starting a blocking GC Explicit
,11-03 18:31:31.438   930  3202 W ActivityManager: Spurious death for ProcessRecord{1a0f0d3 0:com.test.thalitest/u0a77}, curProc for 5984: null
,11-03 18:31:31.516   930   953 I art     : Explicit concurrent mark sweep GC freed 19625(1414KB) AllocSpace objects, 11(220KB) LOS objects, 33% free, 29MB/43MB, paused 1.610ms total 84.442ms
,11-03 18:31:31.538   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 18:31:31.543  5982  5982 I art     : System.exit called, status: 0
,11-03 18:31:31.543  5982  5982 I AndroidRuntime: VM exiting with result code 0.
,11-03 18:31:31.558   930   953 I ActivityManager: Start proc 6034:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-03 18:31:31.559   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 18:31:31.564   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-03 18:31:31.568  5794  5794 D BluetoothMapAppObserver: onReceive
11-03 18:31:31.569  5794  5794 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-03 18:31:31.580   930  2948 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 18:31:31.584  3711  4119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-03 18:31:31.584  3653  3653 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-03 18:31:31.604  3407  6047 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 18:31:31.605  3653  6046 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 18:31:31.633  3782  3782 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-03 18:31:31.636  3653  6046 I Decoder : createOrResetDecoder
,11-03 18:31:31.640    27    27 W kworker/2:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 18:31:31.647  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-03 18:31:31.647  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-03 18:31:31.648   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 18:31:31.647    27    27 W kworker/2:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 18:31:31.660    27    27 W kworker/2:1: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 18:31:31.671   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-03 18:31:31.672   930   942 E PackageManager: Failed to write settings, restoring backup
11-03 18:31:31.672   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-03 18:31:31.672   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-03 18:31:31.672   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-03 18:31:31.672   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-03 18:31:31.672   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-03 18:31:31.672   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 18:31:31.672   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-03 18:31:31.672   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 18:31:31.675   930   943 E DropBoxManagerService: Can't write: system_server_wtf
11-03 18:31:31.675   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-03 18:31:31.675   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 18:31:31.675   930   943 E DropBoxManagerService: 	... 13 more
,11-03 18:31:31.697  3407  3430 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj098F59980) - 
,--------- beginning of crash
11-03 18:31:31.724  3407  3430 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-03 18:31:31.724  3407  3430 E AndroidRuntime: Process: android.process.acore, PID: 3407
11-03 18:31:31.724  3407  3430 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 18:31:31.724  3407  3430 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 18:31:31.728   930  6054 E DropBoxManagerService: Can't write: system_app_crash
11-03 18:31:31.728   930  6054 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 18:31:31.728   930  6054 E DropBoxManagerService: 	... 5 more
,11-03 18:31:31.734  3407  6047 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-03 18:31:31.735  3407  6047 I Process : Sending signal. PID: 3407 SIG: 9
,11-03 18:31:31.748   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
