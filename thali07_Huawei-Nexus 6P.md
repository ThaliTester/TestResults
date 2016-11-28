#### Test 951040644e42f59_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
,11-28 17:18:28.318  3958  4198 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-28 17:18:28.396  3958  4198 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
--------- beginning of system
11-28 17:18:28.412   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-28 17:18:28.722  5548  5548 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 17:18:28.728  5548  5548 D AndroidRuntime: CheckJNI is OFF
11-28 17:18:28.757  5548  5548 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-28 17:18:28.793  5548  5548 I Radio-JNI: register_android_hardware_Radio DONE
11-28 17:18:28.810  5548  5548 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-28 17:18:28.815   926  5445 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-28 17:18:28.834  5548  5548 D AndroidRuntime: Shutting down VM
11-28 17:18:28.841  3944  4225 W SearchService: Abort, client detached.
11-28 17:18:28.848  3944  3944 I HotwordDetector: Closing mic
11-28 17:18:28.848  3944  4172 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8851330
11-28 17:18:28.848  3944  4192 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-28 17:18:28.864   926  3141 I ActivityManager: Start proc 5558:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-28 17:18:28.919   513  4194 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-28 17:18:28.921   513  4194 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-28 17:18:28.925   513  4194 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-28 17:18:28.925   513  4194 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-28 17:18:28.926   513  2997 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 17:18:28.927  3944  4174 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-28 17:18:28.928  3944  4190 I MicroRecognitionRnrImpl: Detection finished
11-28 17:18:28.959  5558  5558 I CordovaLog: Changing log level to DEBUG(3)
11-28 17:18:28.959  5558  5558 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-28 17:18:28.959  5558  5558 D CordovaActivity: CordovaActivity.onCreate()
11-28 17:18:28.963  5558  5558 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-28 17:18:28.985  5558  5558 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-28 17:18:29.039  5558  5558 I LibraryLoader: Time to load native libraries: 51 ms (timestamps 4304-4355)
11-28 17:18:29.039  5558  5558 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 17:18:29.065  5558  5558 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28e657e}
,11-28 17:18:29.065  5558  5558 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-28 17:18:29.065  5558  5558 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-28 17:18:29.069  5558  5558 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-28 17:18:29.070  5558  5558 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-28 17:18:29.125  5558  5558 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-28 17:18:29.135  5558  5558 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-28 17:18:29.135  5558  5558 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 17:18:29.135  5558  5558 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 17:18:29.135  5558  5558 I Adreno  : Build Date                       : 12/06/15
11-28 17:18:29.135  5558  5558 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 17:18:29.135  5558  5558 I Adreno  : Local Branch                     : mybranch17112971
11-28 17:18:29.135  5558  5558 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 17:18:29.135  5558  5558 I Adreno  : Remote Branch                    : NONE
11-28 17:18:29.135  5558  5558 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 17:18:29.168   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9fbc66a:true
,11-28 17:18:29.188   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[21348]" dev="sockfs" ino=21348 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.188   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[21348]" dev="sockfs" ino=21348 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.201  5558  5558 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-28 17:18:29.209  5558  5558 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-28 17:18:29.212  5558  5558 D PluginManager: init()
,11-28 17:18:29.215  5558  5558 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-28 17:18:29.229  5558  5558 D CordovaActivity: Started the activity.
,11-28 17:18:29.229  5558  5558 D CordovaActivity: Resumed the activity.
,11-28 17:18:29.233  5558  5595 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-28 17:18:29.228  2974  2974 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31299]" dev="sockfs" ino=31299 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:29.228  2974  2974 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31299]" dev="sockfs" ino=31299 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.231   937   937 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[21359]" dev="sockfs" ino=21359 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.231   937   937 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[21359]" dev="sockfs" ino=21359 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:29.237  5558  5582 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-28 17:18:29.261  5558  5595 I OpenGLRenderer: Initialized EGL, version 1.4
,11-28 17:18:29.331  3140  3140 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32332]" dev="sockfs" ino=32332 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.331  3140  3140 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32332]" dev="sockfs" ino=32332 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:29.334   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +487ms
,11-28 17:18:29.334  3141  3141 W Binder_4: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32331]" dev="sockfs" ino=32331 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.334  3141  3141 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32331]" dev="sockfs" ino=32331 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:29.344  3675  3675 I Keyboard.Facilitator: onFinishInput()
,11-28 17:18:29.353  5558  5558 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-28 17:18:29.383  5558  5558 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5558
,11-28 17:18:29.522  5558  5558 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-28 17:18:29.623  5558  5597 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -564135632
,11-28 17:18:29.627  5558  5597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-28 17:18:29.627  5558  5597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-28 17:18:29.627  5558  5597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-28 17:18:29.627  5558  5597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-28 17:18:29.627  5558  5597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-28 17:18:29.627  5558  5597 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b288c6d added. We now have 1 listener(s)
,11-28 17:18:29.629  5558  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-28 17:18:29.630  5558  5597 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:18:29.630  5558  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 17:18:29.630  5558  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-28 17:18:29.633  5558  5597 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3087cf0 added. We now have 1 listener(s)
,11-28 17:18:29.633  5558  5597 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 17:18:29.641   926  2968 D WifiService: New client listening to asynchronous messages
11-28 17:18:29.641  5558  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 17:18:29.641  5558  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-28 17:18:29.641  5558  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-28 17:18:29.642  5558  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-28 17:18:29.642  5558  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-28 17:18:29.642  5558  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-28 17:18:29.642  5558  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-28 17:18:29.643  5558  5597 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 17:18:29.714  5558  5558 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-28 17:18:29.716  5558  5558 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-28 17:18:29.716  5558  5558 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-28 17:18:29.953  5558  5567 I art     : Background sticky concurrent mark sweep GC freed 87421(8MB) AllocSpace objects, 16(1476KB) LOS objects, 20% free, 26MB/32MB, paused 1.579ms total 102.171ms
,11-28 17:18:30.097  5558  5605 W jxcore-log: Initializing JXcore engine
,11-28 17:18:30.097  5558  5605 W jxcore-log: JXcore engine is ready
,11-28 17:18:30.118  5605  5605 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12730 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-28 17:18:30.118  5605  5605 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[13378]" dev="sockfs" ino=13378 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-28 17:18:30.118  5605  5605 W Thread-58: type=1400 audit(0.0:113): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-28 17:18:30.118  5605  5605 W Thread-58: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31277]" dev="sockfs" ino=31277 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-28 17:18:30.130  5558  5605 W jxcore-log: Starting JXcore engine
,11-28 17:18:30.183  5558  5605 W jxcore-log: Platform android
11-28 17:18:30.183  5558  5605 W jxcore-log: 
,11-28 17:18:30.183  5558  5605 W jxcore-log: Process ARCH arm
11-28 17:18:30.183  5558  5605 W jxcore-log: 
,11-28 17:18:30.331  5558  5605 I jxcore-log: JXcore Cordova bridge is ready!
11-28 17:18:30.331  5558  5605 I jxcore-log: 
,11-28 17:18:30.331  5558  5605 W jxcore-log: JXcore engine is started
,11-28 17:18:30.336  5558  5597 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-28 17:18:30.340  5558  5558 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-28 17:18:30.340  5558  5558 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-28 17:18:31.439   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:18:31.824   926  3440 I ActivityManager: Killing 5034:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-28 17:18:32.401  3573  3573 I ConfigService: onDestroy
,11-28 17:18:33.856   926  5445 I ActivityManager: Killing 5164:org.codeaurora.ims/1001 (adj 15): empty #17
,11-28 17:18:40.139  5558  5605 I jxcore-log: 2016-11-28 16:18:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-28 17:18:40.139  5558  5605 I jxcore-log: 
,11-28 17:18:40.141  5558  5605 I jxcore-log: 2016-11-28 16:18:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-28 17:18:40.141  5558  5605 I jxcore-log: 
,11-28 17:18:40.146  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:18:40.146  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 17:18:40.147  5558  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:18:40.150  5558  5605 I jxcore-log: 2016-11-28 16:18:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-28 17:18:40.150  5558  5605 I jxcore-log: 
11-28 17:18:40.151  5558  5605 I jxcore-log: 2016-11-28 16:18:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-28 17:18:40.151  5558  5605 I jxcore-log: 
,11-28 17:18:40.405  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 17:18:40.405  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95fc225 added. We now have 2 listener(s)
11-28 17:18:40.406  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:18:40.406  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:18:40.406  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:18:40.406  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 17:18:40.406  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88b1ffa added. We now have 2 listener(s)
11-28 17:18:40.406  5558  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 17:18:40.407  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 17:18:40.408  5558  5605 D ExecuteNativeTests: Running unit tests
,11-28 17:18:40.409  5558  5605 D BluetoothAdapter: enable(): BT is already enabled..!
11-28 17:18:40.409   926  5445 D WifiService: setWifiEnabled: true pid=5558, uid=10077
11-28 17:18:40.409   926  5445 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:18:42.067  3944  5609 W CronetSyncConnectionRcs: Upload content type not set.
,11-28 17:18:42.144  4723  4755 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-28 17:18:42.145  4723  4723 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-28 17:18:44.420   926  2967 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 17:18:46.960   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:18:47.961   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:18:48.963   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:18:49.964   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:18:50.415  5558  5605 I com.test.thalitest.ThaliTestRunner: Running UT
,11-28 17:18:50.480  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 17:18:50.480  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bcf27c added. We now have 3 listener(s)
11-28 17:18:50.480  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:18:50.481  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:18:50.481  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:18:50.481  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 17:18:50.481  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d3705 added. We now have 3 listener(s)
11-28 17:18:50.481  5558  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 17:18:50.482  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 17:18:50.486  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-28 17:18:50.486  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-28 17:18:50.486  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 17:18:50.486  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:50.486  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:50.487  5558  5605 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-28 17:18:50.487  5558  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 17:18:50.487  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 17:18:50.487  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:50.487  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:50.487  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:50.489  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-28 17:18:50.489  5558  5605 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-28 17:18:50.491  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-28 17:18:50.493  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-28 17:18:50.493  5558  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:18:50.495  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:50.495  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:18:50.506  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 17:18:50.506  5558  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:18:50.507  5558  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-28 17:18:50.507  5558  5605 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-28 17:18:50.507  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-28 17:18:50.507  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.507  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.507  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.507  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 17:18:50.507  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:18:50.507  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:18:50.507  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 17:18:50.509  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:18:50.509  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:18:50.510  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:18:50.510  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:18:50.510  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 17:18:50.510  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 17:18:50.510  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:50.510  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 17:18:50.510  5558  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:18:50.511  5558  5558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:18:50.513  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:18:50.513  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:18:50.514  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 17:18:50.513  5558  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:50.515  5558  5558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 17:18:50.515  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:18:50.516  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.516  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:18:50.517  5558  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:18:50.511  4271  4271 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32371]" dev="sockfs" ino=32371 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:18:50.517  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:18:50.517  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:18:50.517  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-28 17:18:50.518  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.518  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.518  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-28 17:18:50.518  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:18:50.518  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:18:50.511  4271  4271 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32371]" dev="sockfs" ino=32371 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:50.519  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-28 17:18:50.519  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:50.519  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 17:18:50.519  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.519  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:18:50.519  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:50.519  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.519  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.519  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.520  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:18:50.523  4260  4448 D BtGatt.GattService: registerClient() - UUID=11998925-4c82-4fd4-9380-469da3a8a041
,11-28 17:18:50.523  4260  4307 D BtGatt.GattService: onClientRegistered() - UUID=11998925-4c82-4fd4-9380-469da3a8a041, clientIf=5
11-28 17:18:50.524  5558  5569 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:18:50.528  4260  4309 D BtGatt.AdvertiseManager: message : 0
,11-28 17:18:50.531  4260  4309 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:18:50.549  4260  4307 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:18:50.556  4260  4307 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:18:50.558  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.558  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.558  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:18:50.559  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:18:50.559  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.560  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:50.560  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.560  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:50.560  5558  5605 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:18:50.560  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 17:18:50.561  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 17:18:50.561  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:50.561  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:18:50.561  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.561  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.562  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:50.562  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.562  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:18:50.562  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:18:50.562  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.562  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.562  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.563  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.563  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 17:18:50.566  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.566  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:18:50.566  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.566  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:50.567  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:18:50.966   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:18:51.063  5558  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 17:18:51.064  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 17:18:51.065  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 17:18:51.066  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 17:18:51.067  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 17:18:51.067  5558  5605 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 17:18:51.068  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 17:18:51.068  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-28 17:18:51.068  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:18:51.068  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:18:51.068  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:18:51.068  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-28 17:18:51.069  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 17:18:51.069  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:18:51.069  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:18:51.069  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 17:18:51.069  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 17:18:51.069  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.069  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:18:51.069  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:18:51.070  5558  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-28 17:18:51.070  5558  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:18:51.070  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.070  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.070  5558  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:18:51.070  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.071  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.072  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:18:51.072  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:18:51.073  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:18:51.073  5558  5605 D BluetoothLeScanner: could not find callback wrapper
11-28 17:18:51.074  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 17:18:51.074  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.074  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.074  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.074  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:18:51.074  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.075  4260  4309 D BtGatt.AdvertiseManager: message : 1
,11-28 17:18:51.077  4260  4309 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:18:51.090  4260  4307 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:18:51.090  4260  4307 D BtGatt.GattService: Client app is not null!
11-28 17:18:51.091  4260  4271 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.093  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:18:51.094  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:18:51.094  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:18:51.095  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.096  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.096  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 17:18:51.096  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.096  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.096  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 17:18:51.096  5558  5558 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 17:18:51.098  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-28 17:18:51.098  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:51.098  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:51.098  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:18:51.098  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:18:51.098  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 17:18:51.099  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.099  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:18:51.099  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:18:51.099  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.099  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.099  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.099  5558  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:18:51.099  5558  5605 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 17:18:51.099  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:18:51.099  5558  5605 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-28 17:18:51.100  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.100  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-28 17:18:51.100  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 17:18:51.100  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.100  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.100  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.100  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:18:51.100  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:18:51.100  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:18:51.100  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:51.108  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:18:51.108  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:18:51.108  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:18:51.108  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:18:51.108  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:18:51.109  5558  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:18:51.104  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.109  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.109  5558  5616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:51.109  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.110  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:18:51.110  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 17:18:51.110  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:51.110  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:18:51.113  5558  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:18:51.108  4274  4274 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31323]" dev="sockfs" ino=31323 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:51.108  4274  4274 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31323]" dev="sockfs" ino=31323 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:51.115  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:18:51.115  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:18:51.115  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:18:51.120  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.120  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:18:51.121  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:18:51.121  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:18:51.121  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-28 17:18:51.124  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.124  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.124  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:18:51.124  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:18:51.125  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:18:51.125  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-28 17:18:51.125  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.125  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.125  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.125  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:18:51.125  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.125  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.125  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.126  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.127  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:18:51.131  4260  4274 D BtGatt.GattService: registerClient() - UUID=8b125cfc-ff90-4176-b36c-ba6c0b5da5e7
11-28 17:18:51.131  4260  4307 D BtGatt.GattService: onClientRegistered() - UUID=8b125cfc-ff90-4176-b36c-ba6c0b5da5e7, clientIf=5
11-28 17:18:51.131  5558  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:18:51.133  4260  4309 D BtGatt.AdvertiseManager: message : 0
11-28 17:18:51.135  4260  4309 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:18:51.148  4260  4307 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-28 17:18:51.155  4260  4307 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-28 17:18:51.156  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.157  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:18:51.159  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:18:51.159  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.160  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.161  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.161  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.161  5558  5605 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:18:51.161  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:18:51.161  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.161  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:51.161  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.162  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.162  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.163  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.163  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.163  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.167  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.167  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:18:51.167  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.167  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.167  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:18:51.665  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-28 17:18:51.666  5558  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-28 17:18:51.666  5558  5605 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 17:18:51.666  5558  5605 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 17:18:51.666  5558  5605 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-28 17:18:51.666  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-28 17:18:51.667  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.667  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.667  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.668  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 17:18:51.669  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.669  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-28 17:18:51.670  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.670  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.672  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.680  4260  4309 D BtGatt.AdvertiseManager: message : 1
11-28 17:18:51.681  4260  4309 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:18:51.692  4260  4307 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:18:51.693  4260  4307 D BtGatt.GattService: Client app is not null!
11-28 17:18:51.694  4260  4271 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:18:51.695  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:18:51.695  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.695  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:18:51.695  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.696  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.696  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.696  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:18:51.696  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.696  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.696  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.696  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:18:51.696  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:18:51.697  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:18:51.697  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-28 17:18:51.698  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 17:18:51.698  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.698  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.698  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:18:51.698  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 17:18:51.698  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.699  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.699  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.700  5558  5605 D BluetoothAdapter: STATE_ON
,11-28 17:18:51.706  4260  4448 D BtGatt.GattService: registerClient() - UUID=6413cfa3-44e1-4313-b31e-c0da57d81806
,11-28 17:18:51.706  4260  4307 D BtGatt.GattService: onClientRegistered() - UUID=6413cfa3-44e1-4313-b31e-c0da57d81806, clientIf=5
11-28 17:18:51.706  5558  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 17:18:51.708  4260  4309 D BtGatt.AdvertiseManager: message : 0
,11-28 17:18:51.711  4260  4309 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:18:51.724  4260  4307 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:18:51.730  4260  4307 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:18:51.731  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.731  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.731  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:18:51.731  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.731  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.731  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.731  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.731  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.732  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.732  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 17:18:51.732  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.732  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 17:18:51.732  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 17:18:51.732  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 17:18:51.732  5558  5605 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-28 17:18:51.733  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-28 17:18:51.733  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.734  5558  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 17:18:51.734  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 17:18:51.734  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 17:18:51.734  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:18:51.734  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-28 17:18:51.734  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:18:51.734  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 17:18:51.734  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:18:51.734  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:18:51.734  5558  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:18:51.734  5558  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:18:51.734  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 17:18:51.735  5558  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:18:51.735  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:18:51.735  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.735  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.737  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:18:51.737  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:18:51.738  5558  5605 D BluetoothAdapter: STATE_ON
,11-28 17:18:51.738  5558  5605 D BluetoothLeScanner: could not find callback wrapper
11-28 17:18:51.738  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:18:51.738  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.738  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.738  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.738  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:18:51.738  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.739  4260  4309 D BtGatt.AdvertiseManager: message : 1
11-28 17:18:51.740  4260  4309 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:18:51.748  4260  4307 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:18:51.748  4260  4307 D BtGatt.GattService: Client app is not null!
,11-28 17:18:51.749  4260  4271 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:18:51.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 17:18:51.750  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:18:51.750  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.752  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.752  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:18:51.752  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:51.752  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.752  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 17:18:51.752  5558  5558 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 17:18:51.752  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:18:51.752  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:18:51.752  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:51.752  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:51.753  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.753  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:18:51.753  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.753  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.755  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.755  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.755  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.756  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-28 17:18:51.757  5558  5605 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-28 17:18:51.758  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-28 17:18:51.758  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 17:18:51.759  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-28 17:18:51.759  5558  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-28 17:18:51.760  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-28 17:18:51.760  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-28 17:18:51.761  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-28 17:18:51.761  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 17:18:51.761  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:51.761  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:51.761  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:51.761  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 17:18:51.761  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:51.761  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:51.761  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:51.761  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 17:18:51.762  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:51.762  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:51.762  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:18:51.762  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-28 17:18:51.762  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:18:51.763  5558  5605 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 17:18:51.763  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-28 17:18:51.766  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:18:51.766  5558  5605 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 17:18:51.766  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 17:18:51.767  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 17:18:51.768  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 17:18:51.768  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 17:18:51.768  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 17:18:51.768  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-28 17:18:51.768  5558  5605 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 17:18:51.768  5558  5605 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-28 17:18:51.768  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:18:51.768  5558  5605 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 17:18:51.768  5558  5605 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-28 17:18:51.768  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:18:51.768  5558  5605 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 17:18:51.768  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-28 17:18:51.774  4448  4448 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30568]" dev="sockfs" ino=30568 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:51.773  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-28 17:18:51.774  4448  4448 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[30568]" dev="sockfs" ino=30568 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:51.773  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-28 17:18:51.773  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-28 17:18:51.774  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-28 17:18:51.774  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-28 17:18:51.774  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-28 17:18:51.774  5558  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:18:51.774  5558  5605 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-28 17:18:51.774  5558  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 130)
11-28 17:18:51.774  5558  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-28 17:18:51.775  5558  5620 D org.thaliproject.p2p.btconnectorlib.internal.bl,uetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-28 17:18:51.775  5558  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-28 17:18:51.776  5558  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-28 17:18:51.776  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-28 17:18:51.776  5558  5620 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-28 17:18:51.776  5558  5605 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-28 17:18:51.776  5558  5620 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:51.777  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-28 17:18:51.777  5558  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-28 17:18:51.778  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-28 17:18:51.778  5558  5605 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-28 17:18:51.778  5558  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-28 17:18:51.778  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 17:18:51.778  5558  5605 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-28 17:18:51.778  5558  5605 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 17:18:51.778  5558  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-28 17:18:51.778  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 17:18:51.778  5558  5605 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-28 17:18:51.778  5558  5605 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 17:18:51.778  5558  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 17:18:51.778  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 17:18:51.778  5558  5605 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-28 17:18:51.779  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-28 17:18:51.779  5558  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:18:51.779  5558  5605 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 17:18:51.779  5558  5605 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-28 17:18:51.780  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-28 17:18:51.780  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.780  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.780  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.780  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:18:51.780  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:18:51.780  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:18:51.780  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:51.782  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:18:51.782  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:18:51.782  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:18:51.782  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:18:51.782  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:18:51.782  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 17:18:51.782  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:18:51.782  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:51.782  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:18:51.782  5558  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:18:51.784  5558  5621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:51.786  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:18:51.786  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:18:51.786  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:18:51.784  4271  4271 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[32866]" dev="sockfs" ino=32866 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:51.784  4271  4271 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32866]" dev="sockfs" ino=32866 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:51.788  5558  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:18:51.791  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.791  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:18:51.791  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:18:51.791  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:18:51.791  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-28 17:18:51.793  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.793  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.793  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:18:51.793  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:18:51.793  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:18:51.794  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-28 17:18:51.794  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.794  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.794  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.794  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:18:51.794  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:18:51.794  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.794  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.794  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.795  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:18:51.798  4260  4448 D BtGatt.GattService: registerClient() - UUID=2a368666-3be5-43fa-a4f9-59dc1ebf0470
11-28 17:18:51.798  4260  4307 D BtGatt.GattService: onClientRegistered() - UUID=2a368666-3be5-43fa-a4f9-59dc1ebf0470, clientIf=5
11-28 17:18:51.798  5558  5568 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:18:51.799  4260  4309 D BtGatt.AdvertiseManager: message : 0
11-28 17:18:51.801  4260  4309 D BtGatt.AdvertiseManager: starting multi advertising
11-28 17:18:51.810  4260  4307 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-28 17:18:51.816  4260  4307 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-28 17:18:51.816  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.817  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:18:51.818  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:18:51.819  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.820  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.820  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.820  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:51.820  5558  5605 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:18:51.820  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.821  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.823  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.823  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:18:51.824  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.824  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:51.824  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:18:51.966   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 17:18:52.321  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 17:18:52.321  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-28 17:18:52.322  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:18:52.322  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:18:52.322  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-28 17:18:52.322  5558  5621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:18:52.322  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:18:52.323  5558  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-28 17:18:52.323  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:18:52.323  5558  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 17:18:52.323  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 17:18:52.323  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-28 17:18:52.323  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-28 17:18:52.323  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 17:18:52.324  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 17:18:52.325  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:18:52.326  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bcf27c removed from the list
11-28 17:18:52.327  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 17:18:52.327  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:18:52.328  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:52.328  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:18:52.329  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:18:52.329  5558  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 130
,11-28 17:18:52.329  5558  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-28 17:18:52.329  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.330  5558  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 130)
11-28 17:18:52.330  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:52.330  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.330  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.330  5558  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 130)
11-28 17:18:52.330  4260  4443 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
,11-28 17:18:52.331  5558  5620 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-28 17:18:52.331  5558  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-28 17:18:52.331  5558  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 130)
11-28 17:18:52.332  5558  5605 D BluetoothAdapter: STATE_ON
,11-28 17:18:52.332  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:18:52.334  5558  5605 D BluetoothAdapter: STATE_ON
,11-28 17:18:52.334  5558  5605 D BluetoothLeScanner: could not find callback wrapper
11-28 17:18:52.334  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:18:52.334  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.334  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.335  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.335  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:18:52.335  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.337  4260  4309 D BtGatt.AdvertiseManager: message : 1
,11-28 17:18:52.339  4260  4309 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:18:52.348  4260  4307 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:18:52.348  4260  4307 D BtGatt.GattService: Client app is not null!
,11-28 17:18:52.349  4260  4271 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.350  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:18:52.350  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:18:52.351  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:18:52.351  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:52.353  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.353  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:18:52.353  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.353  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:52.353  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d3705 removed from the list
11-28 17:18:52.353  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:52.353  5558  5605 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:18:52.353  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 17:18:52.353  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:52.353  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 17:18:52.354  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.354  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:18:52.354  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:18:52.354  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.354  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.354  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-28 17:18:52.354  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:18:52.355  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.355  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.356  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.356  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:18:52.357  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 17:18:52.856  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 17:18:55.649   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:18:56.906  4260  4414 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-28 17:18:56.907  4260  4414 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-28 17:18:57.358  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-28 17:18:57.360  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:18:57.361  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:18:57.361  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 17:18:57.370  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 17:18:57.371  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 17:18:57.371  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:18:57.372  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:18:57.372  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:18:57.372  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 17:18:57.372  5558  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:18:57.372  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 17:18:57.374  5558  5623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:57.375  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-28 17:18:57.376  5558  5605 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-28 17:18:57.376  5558  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 17:18:57.376  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 17:18:57.377  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:57.371  4448  4448 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31337]" dev="sockfs" ino=31337 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:57.374  4448  4448 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31337]" dev="sockfs" ino=31337 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:18:57.377  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:18:57.378  5558  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 17:18:57.380  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName,
,11-28 17:18:57.390  5558  5605 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-28 17:18:57.390  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 17:18:57.391  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:18:57.391  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:18:57.391  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:18:57.391  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 17:18:57.391  5558  5623 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:18:57.391  5558  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:18:57.392  5558  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:18:57.392  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:18:57.392  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:18:57.392  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-28 17:18:57.394  5558  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bcf27c not in the list
11-28 17:18:57.394  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 17:18:57.394  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 17:18:57.394  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:18:57.395  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:57.395  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:18:57.395  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:18:57.394  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:18:57.395  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:57.397  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:18:57.398  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:18:57.398  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:57.398  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:18:57.398  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:57.398  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:18:57.398  5558  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d3705 not in the list
11-28 17:18:57.398  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 17:18:57.398  5558  5605 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:18:57.400  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-28 17:18:57.401  5558  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-28 17:18:57.401  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-28 17:18:57.401  5558  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-28 17:18:57.401  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 17:18:57.402  5558  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-28 17:18:57.402  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 17:18:57.402  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-28 17:18:57.403  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-28 17:18:57.405  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-28 17:18:57.405  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-28 17:18:57.405  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-28 17:18:57.406  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-28 17:18:57.407  5558  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-28 17:18:57.407  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 17:18:57.407  5558  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-28 17:18:57.407  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 17:18:57.407  5558  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-28 17:18:57.407  5558  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-28 17:18:57.409  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-28 17:18:57.409  5558  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-28 17:18:57.409  5558  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-28 17:18:57.410  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-28 17:18:57.411  5558  5605 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-28 17:18:57.411  5558  5605 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-28 17:18:57.411  5558  5605 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-28 17:18:57.411  5558  5605 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-28 17:18:57.413  5558  5605 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-28 17:18:57.414  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 17:18:57.414  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d0b7b added. We now have 3 listener(s)
,11-28 17:18:57.415  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:18:57.416  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:18:57.416  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:18:57.416  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 17:18:57.416  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22f8d98 added. We now have 3 listener(s)
11-28 17:18:57.416  5558  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 17:18:57.417  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 17:18:57.420  5558  5605 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 17:18:57.420   926   937 D WifiService: setWifiEnabled: true pid=5558, uid=10077
,11-28 17:18:57.420   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 17:18:57.422  5558  5605 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-28 17:18:57.424  5558  5605 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-28 17:18:57.426  5558  5605 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-28 17:18:57.426  5558  5605 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-28 17:18:57.432  4260  4303 D BluetoothAdapterState: Current state: ON, message: 23
11-28 17:18:57.432  4260  4303 D BluetoothAdapterProperties: Setting state to 13
11-28 17:18:57.432  4260  4303 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:18:57.433  5558  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 17:18:57.433  4260  4303 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 17:18:57.433  4260  4303 I BluetoothAdapterState: Entering PendingCommandState
11-28 17:18:57.433  5558  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 17:18:57.433  5558  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:18:57.435  4260  4307 D BluetoothAdapterProperties: Scan Mode:20
11-28 17:18:57.435  4260  4303 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-28 17:18:57.437  4260  4260 D HeadsetService: Received stop request...Stopping profile...
,11-28 17:18:57.440  3107  3998 D BluetoothHeadset: Proxy object disconnected
11-28 17:18:57.440  3107  3107 D HeadsetProfile: Bluetooth service disconnected
11-28 17:18:57.441  4260  4260 D A2dpService: Received stop request...Stopping profile...
11-28 17:18:57.441  4260  4452 D A2dpStateMachine: Exit Disconnected: -1
11-28 17:18:57.441  3774  3988 D BluetoothHeadset: Proxy object disconnected
,11-28 17:18:57.441   926   926 D BluetoothHeadset: Proxy object disconnected
11-28 17:18:57.442   926   926 D BluetoothHeadset: Proxy object disconnected
11-28 17:18:57.442  5231  5241 D BluetoothHeadset: Proxy object disconnected
11-28 17:18:57.442   926   926 D BluetoothHeadset: Proxy object disconnected
11-28 17:18:57.442   926   926 D BluetoothA2dp: Proxy object disconnected
11-28 17:18:57.443  5231  5231 D HeadsetProfile: Bluetooth service disconnected
11-28 17:18:57.443  5231  5231 D BluetoothA2dp: Proxy object disconnected
,11-28 17:18:57.444  4260  4260 V BluetoothAdapterState: isTurningOff()=true
,11-28 17:18:57.444  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.444  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.444  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:57.444  3107  3107 D BluetoothA2dp: Proxy object disconnected
11-28 17:18:57.445  4260  4260 D HidService: Received stop request...Stopping profile...
11-28 17:18:57.445  4260  4260 D HidService: Stopping Bluetooth HidService
,11-28 17:18:57.446  3107  3107 D BluetoothInputDevice: Proxy object disconnected
11-28 17:18:57.446  3107  3107 D HidProfile: Bluetooth service disconnected
11-28 17:18:57.446  5231  5231 D BluetoothInputDevice: Proxy object disconnected
11-28 17:18:57.446  5231  5231 D HidProfile: Bluetooth service disconnected
11-28 17:18:57.448  4260  4260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 17:18:57.448  4260  4260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 17:18:57.448  4260  4307 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 17:18:57.449  4260  4260 D HealthService: Received stop request...Stopping profile...
11-28 17:18:57.449  4260  4414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 17:18:57.449  4260  4414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:18:57.449  4260  4414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:18:57.449  4260  4307 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-28 17:18:57.450  4260  4260 V BluetoothAdapterState: isTurningOff()=true
11-28 17:18:57.450  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,11-28 17:18:57.450  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.450  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:57.450  4260  4260 D PanService: Received stop request...Stopping profile...
11-28 17:18:57.451  3107  3107 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-28 17:18:57.451  3107  3107 D PanProfile: Bluetooth service disconnected
11-28 17:18:57.452  5231  5231 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 17:18:57.452  5231  5231 D PanProfile: Bluetooth service disconnected
11-28 17:18:57.453  4260  4260 D BluetoothMapService: Received stop request...Stopping profile...
11-28 17:18:57.453  4260  4260 D BluetoothMapService: stop()
11-28 17:18:57.454  4260  4260 D BluetoothMapAppObserver: deinitObservers()
11-28 17:18:57.454  4260  4260 D BluetoothMapAppObserver: removeReceiver()
11-28 17:18:57.454  4260  4307 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 17:18:57.454  4260  4414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:18:57.454  4260  4414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:18:57.454  4260  4414 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-28 17:18:57.454  4260  4414 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 17:18:57.454  4260  4414 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-28 17:18:57.454  4260  4414 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 17:18:57.455  5231  5231 D BluetoothMap: Proxy object disconnected
11-28 17:18:57.455  3107  3107 D BluetoothMap: Proxy object disconnected
11-28 17:18:57.455  5231  5231 D MapProfile: Bluetooth service disconnected
11-28 17:18:57.455  3107  3107 D MapProfile: Bluetooth service disconnected
11-28 17:18:57.456  4260  4260 V BluetoothAdapterState: isTurningOff()=true
11-28 17:18:57.456  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.456  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.456  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:57.456  4260  4260 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-28 17:18:57.457  4260  4260 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 17:18:57.457  4260  4307 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 17:18:57.457  4260  4260 D SapService: Received stop request...Stopping profile...
11-28 17:18:57.457  4260  4260 V SapService: stop()
11-28 17:18:57.459  4260  4260 V BluetoothAdapterState: isTurningOff()=true
11-28 17:18:57.459  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.459  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.459  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:57.459  4260  4260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-28 17:18:57.459  4260  4307 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-28 17:18:57.460  4260  4260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-28 17:18:57.460  4260  4260 V BluetoothAdapterState: isTurningOff()=true
11-28 17:18:57.460  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.461  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.461  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:18:57.461  4260  4260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 17:18:57.461  4260  4260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 17:18:57.462  4260  4260 D BluetoothMapService: MAP Service closeService in
11-28 17:18:57.462  4260  4260 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 17:18:57.462  4260  4260 D ObexServerSockets0: shutdown(block = true)
11-28 17:18:57.463  4260  4260 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 17:18:57.463  4260  4461 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-28 17:18:57.463  4260  4443 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 17:18:57.463  4260  4462 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-28 17:18:57.463  4260  4260 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 17:18:57.464  4260  4260 V BluetoothAdapterState: isTurningOff()=true
11-28 17:18:57.464  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.464  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.464  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:18:57.464  4260  4260 D BluetoothMapService: cleanup()
11-28 17:18:57.464  4260  4260 D BluetoothMapService: MAP Service closeService in
11-28 17:18:57.465  4260  4260 V BluetoothAdapterState: isTurningOff()=true
,11-28 17:18:57.465  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.465  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.465  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:57.465  4260  4303 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 17:18:57.466  4260  4303 D BluetoothAdapterProperties: Setting state to 15
11-28 17:18:57.466  4260  4303 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 17:18:57.466  4260  4303 I BluetoothAdapterState: Entering BleOnState
,11-28 17:18:57.484  3107  3120 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-28 17:18:57.485   926   939 I ActivityManager: Killing 4511:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-28 17:18:57.485  4260  4260 I BtOppRfcommListener: stopping Accept Thread
11-28 17:18:57.485  4260  5253 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 17:18:57.486  4260  5253 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-28 17:18:57.502  3107  4000 D BluetoothPan: onBluetoothStateChange on: false
,11-28 17:18:57.507  5231  5242 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 17:18:57.508  3107  3131 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:18:57.508  5231  5241 D BluetoothMap: onBluetoothStateChange: up=false
11-28 17:18:57.508  3774  4139 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:18:57.509  3107  3998 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 17:18:57.509  3107  3120 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 17:18:57.510   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:18:57.510   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:18:57.510  5231  5242 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:18:57.510  5231  5241 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-28 17:18:57.511  3107  4000 D BluetoothMap: onBluetoothStateChange: up=false
,11-28 17:18:57.512   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:18:57.512  5231  5242 D BluetoothPan: onBluetoothStateChange on: false
11-28 17:18:57.512   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 17:18:57.513  5231  5241 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 17:18:57.514  4260  4303 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 17:18:57.514  4260  4303 D BluetoothAdapterProperties: Setting state to 16
11-28 17:18:57.514  4260  4303 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 17:18:57.515  4260  4303 D BluetoothAdapterProperties: onBleDisable
11-28 17:18:57.515  4260  4303 I BluetoothAdapterState: Entering PendingCommandState
11-28 17:18:57.515  4260  4304 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 17:18:57.516  5231  5231 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 17:18:57.517  4260  4414 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-28 17:18:57.517  4260  4414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 17:18:57.521  4260  4307 D BluetoothAdapterProperties: Scan Mode:20
11-28 17:18:57.524  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 17:18:57.529  5231  5231 D DockEventReceiver: finishStartingService: stopping service
,11-28 17:18:57.539  5231  5231 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 17:18:57.547  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:18:57.548  5231  5231 D DockEventReceiver: finishStartingService: stopping service
,11-28 17:18:57.550   926   936 I ActivityManager: Killing 5179:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-28 17:18:57.729  4260  4307 I bt_hci  : shut_down
,11-28 17:18:57.736  4260  4312 I bt_vendor: low_power_mode_cb
,11-28 17:18:57.738  4260  4312 D bt_hwcfg: hw_epilog_process
,11-28 17:18:57.742  4260  4312 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-28 17:18:57.742  4260  4312 I bt_vendor: epilog_cb
11-28 17:18:57.742  4260  4312 I bt_hci  : epilog_finished_callback
,11-28 17:18:57.745  4260  4307 I bt_hci_h4: hal_close
,11-28 17:18:57.746  4260  4307 I bt_userial_vendor: device fd = 54 close
,11-28 17:18:57.860  4260  4304 D bt_stack_manager: event_shut_down_stack finished.
,11-28 17:18:57.861  4260  4303 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-28 17:18:57.865  4260  4260 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 17:18:57.865  4260  4303 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-28 17:18:57.867  4260  4260 D BtGatt.GattService: Received stop request...Stopping profile...
11-28 17:18:57.867  4260  4260 D BtGatt.GattService: stop()
11-28 17:18:57.867  4260  4260 D BtGatt.AdvertiseManager: advertise clients cleared
,11-28 17:18:57.869  4260  4260 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:57.869  4260  4260 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:57.869  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:57.869  4260  4260 V BluetoothAdapterState: isBleTurningOff()=true
11-28 17:18:57.870  4260  4303 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-28 17:18:57.870  4260  4303 D BluetoothAdapterProperties: Setting state to 10
11-28 17:18:57.870  4260  4303 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 17:18:57.871  4260  4303 I BluetoothAdapterState: Entering OffState
,11-28 17:18:57.872   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-28 17:18:57.881  4260  4260 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-28 17:18:57.881  4260  4260 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-28 17:18:57.881  4260  4260 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-28 17:18:57.882  4260  4304 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-28 17:18:57.887  4260  4260 I art     : System.exit called, status: 0
11-28 17:18:57.887  4260  4260 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 17:18:57.899  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 17:18:57.912   926  5445 I ActivityManager: Process com.android.bluetooth (pid 4260) has died
,11-28 17:18:57.933  5558  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:18:57.933  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 17:18:57.934  5558  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 17:18:57.934  5558  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:18:57.937  5558  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:18:57.948   926   943 I ActivityManager: Start proc 5630:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 17:18:58.007  5630  5630 D AdapterServiceConfig: Adding HeadsetService
,11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding A2dpService
11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding HidService
,11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding HealthService
11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding PanService
11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding GattService
,11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding BluetoothMapService
11-28 17:18:58.008  5630  5630 D AdapterServiceConfig: Adding SapService
,11-28 17:18:58.019   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13656a3:true
,11-28 17:18:58.020  5630  5630 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 17:18:58.023  5630  5630 I bt_bluedroid: init
,11-28 17:18:58.023  5630  5642 I BluetoothAdapterState: Entering OffState
,11-28 17:18:58.026  5630  5643 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-28 17:18:58.026  5630  5643 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 17:18:58.026  5630  5643 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 17:18:58.026  5630  5643 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-28 17:18:58.027  5630  5630 I bt_bluedroid: get_profile_interface socket
,11-28 17:18:58.029  5630  5646 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-28 17:18:58.030  5630  5630 I bt_bluedroid: get_profile_interface sdp
11-28 17:18:58.030  5630  5646 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 17:18:58.034  5630  5641 I bt_bluedroid: config_hci_snoop_log
,11-28 17:18:58.035   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-28 17:18:58.039  5630  5642 D BluetoothAdapterState: Current state: OFF, message: 0
11-28 17:18:58.039  5630  5642 D BluetoothAdapterProperties: Setting state to 14
11-28 17:18:58.040  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-28 17:18:58.041  5630  5642 D BluetoothBondStateMachine: make
,11-28 17:18:58.042  5630  5647 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 17:18:58.045  5630  5642 I BluetoothAdapterState: Entering PendingCommandState
,11-28 17:18:58.046  5630  5630 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 17:18:58.048  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 17:18:58.049  5630  5630 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 17:18:58.049  5630  5630 D BtGatt.GattService: Received start request. Starting profile...
11-28 17:18:58.050  5630  5630 D BtGatt.GattService: start()
11-28 17:18:58.050  5630  5630 I bt_bluedroid: get_profile_interface gatt
,11-28 17:18:58.051  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:18:58.051  5630  5630 D BtGatt.AdvertiseManager: advertise manager created
,11-28 17:18:58.056  5630  5630 V BluetoothAdapterState: isTurningOff()=false
,11-28 17:18:58.056  5630  5630 V BluetoothAdapterState: isTurningOn()=false
11-28 17:18:58.056  5630  5630 V BluetoothAdapterState: isBleTurningOn()=true
11-28 17:18:58.056  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:58.056  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-28 17:18:58.057  5630  5642 I bt_bluedroid: bt_bluedroid
11-28 17:18:58.058  5630  5643 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-28 17:18:58.058  5630  5643 I bt_hci  : start_up
,11-28 17:18:58.063  5630  5643 I bt_vendor: alloc value 0xf3e7f871
11-28 17:18:58.063  5630  5643 I bt_vendor: init
11-28 17:18:58.064  5630  5643 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 17:18:58.064  5630  5643 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 17:18:58.174  5630  5643 D bt_hci  : start_up starting async portion
,11-28 17:18:58.175  5630  5650 I bt_hci  : event_finish_startup
11-28 17:18:58.176  5630  5650 I bt_hci_h4: hal_open
,11-28 17:18:58.176  5630  5650 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 17:18:58.174  5651  5651 W irq/448-msm_hs_: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:18:58.180  5630  5650 I bt_userial_vendor: device fd = 54 open
,11-28 17:18:58.196  5630  5650 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 17:18:58.200  5630  5650 D bt_hwcfg: Chipset BCM4358A3
,11-28 17:18:58.200  5630  5650 D bt_hwcfg: Target name = [BCM4358A3]
11-28 17:18:58.200  5630  5650 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 17:18:58.448  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-28 17:18:58.689   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:18:58.719  5630  5650 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 17:18:58.719  5630  5650 D bt_hwcfg: Settlement delay -- 100 ms
11-28 17:18:58.719  5630  5650 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 17:18:58.844  5630  5650 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-28 17:18:58.845  5630  5650 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-28 17:18:58.846  5630  5650 I bt_hwcfg: vendor lib fwcfg completed
,11-28 17:18:58.846  5630  5650 I bt_vendor: firmware callback
11-28 17:18:58.846  5630  5650 I bt_hci  : firmware_config_callback
,11-28 17:18:58.856  5630  5653 I bt_btu  : btu_task pending for preload complete event
,11-28 17:18:58.856  5630  5653 I bt_btu_task: Bluetooth chip preload is complete
,11-28 17:18:58.856  5630  5653 I bt_btu  : btu_task received preload complete event
,11-28 17:18:58.863  5630  5653 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 17:18:58.863  5630  5653 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 17:18:58.863  5630  5653 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 17:18:58.863  5630  5653 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 17:18:58.864  5630  5653 I         : BTE_InitTraceLevels -- TRC_AVRC
11-28 17:18:58.864  5630  5653 I         : BTE_InitTraceLevels -- TRC_A2D
,11-28 17:18:58.864  5630  5653 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 17:18:58.864  5630  5653 I         : BTE_InitTraceLevels -- TRC_BTM
11-28 17:18:58.864  5630  5653 I         : BTE_InitTraceLevels -- TRC_GAP
11-28 17:18:58.864  5630  5653 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 17:18:58.865  5630  5653 I         : BTE_InitTraceLevels -- TRC_SDP
11-28 17:18:58.865  5630  5653 I         : BTE_InitTraceLevels -- TRC_GATT
,11-28 17:18:58.865  5630  5653 I         : BTE_InitTraceLevels -- TRC_SMP
,11-28 17:18:58.865  5630  5653 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-28 17:18:58.865  5630  5653 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 17:18:58.955  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-28 17:18:58.960  5630  5653 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3dfd549
,11-28 17:18:58.961  5630  5653 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3dfd549 
,11-28 17:18:58.997  5630  5646 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 17:18:58.999  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 17:18:58.999  5630  5646 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 17:18:59.000  5630  5646 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 17:18:59.002  5630  5646 D BluetoothAdapterProperties: Scan Mode:20
11-28 17:18:59.002  5630  5646 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 17:18:59.002  5630  5646 D bt_hci  : do_postload posting postload work item
11-28 17:18:59.003  5630  5650 I bt_hci  : event_postload
11-28 17:18:59.003  5630  5650 I bt_vendor: sco_config_cb
11-28 17:18:59.003  5630  5650 I bt_hci  : sco_config_callback postload finished.
,11-28 17:18:59.004  5630  5646 D bt_bte_conf: Device ID record 1 : primary
11-28 17:18:59.004  5630  5646 D bt_bte_conf:   vendorId            = 000f
11-28 17:18:59.004  5630  5646 D bt_bte_conf:   vendorIdSource      = 0001
11-28 17:18:59.004  5630  5646 D bt_bte_conf:   product             = 1200
,11-28 17:18:59.004  5630  5646 D bt_bte_conf:   version             = 1436
11-28 17:18:59.004  5630  5646 D bt_bte_conf:   clientExecutableURL = 
11-28 17:18:59.005  5630  5646 D bt_bte_conf:   serviceDescription  = 
11-28 17:18:59.005  5630  5646 D bt_bte_conf:   documentationURL    = 
11-28 17:18:59.005  5630  5646 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 17:18:59.005  5630  5643 D bt_stack_manager: event_start_up_stack finished
11-28 17:18:59.006  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 17:18:59.006  5630  5642 D BluetoothAdapterProperties: Setting state to 15
11-28 17:18:59.006  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-28 17:18:59.007  5630  5642 I BluetoothAdapterState: Entering BleOnState
,11-28 17:18:59.011  5630  5650 I bt_vendor: low_power_mode_cb
,11-28 17:18:59.011  5630  5642 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-28 17:18:59.012  5630  5642 D BluetoothAdapterProperties: Setting state to 11
11-28 17:18:59.012  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-28 17:18:59.019  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:18:59.020  5630  5630 D HeadsetService: Received start request. Starting profile...
11-28 17:18:59.024  5630  5630 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 17:18:59.025  5630  5630 D HeadsetStateMachine: make
,11-28 17:18:59.036  5630  5630 D HeadsetStateMachine: max_hf_connections = 1
11-28 17:18:59.037  5630  5630 I bt_bluedroid: get_profile_interface handsfree
,11-28 17:18:59.037  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-28 17:18:59.037  5630  5646 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-28 17:18:59.039  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 17:18:59.041  5630  5642 I BluetoothAdapterState: Entering PendingCommandState
,11-28 17:18:59.042  5630  5630 D A2dpService: Received start request. Starting profile...
11-28 17:18:59.042  5630  5630 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-28 17:18:59.043  5630  5630 I bt_bluedroid: get_profile_interface avrcp
,11-28 17:18:59.049  5630  5630 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 17:18:59.049  5630  5630 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 17:18:59.050  5630  5630 D A2dpStateMachine: make
,11-28 17:18:59.051  5630  5630 I bt_bluedroid: get_profile_interface a2dp
,11-28 17:18:59.052  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-28 17:18:59.053  5630  5661 D A2dpStateMachine: Enter Disconnected: -2
,11-28 17:18:59.054  5630  5630 I BluetoothHidServiceJni: classInitNative: succeeds
11-28 17:18:59.055  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:18:59.056  5630  5630 D HidService: Received start request. Starting profile...
11-28 17:18:59.056  5630  5630 I bt_bluedroid: get_profile_interface hidhost
11-28 17:18:59.056  5630  5630 D HidService: setHidService(): set to: null
11-28 17:18:59.056  5630  5646 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dde56d
11-28 17:18:59.056  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-28 17:18:59.060  5630  5630 I BluetoothHealthServiceJni: classInitNative: succeeds
11-28 17:18:59.061  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:18:59.061  5630  5630 D HealthService: Received start request. Starting profile...
11-28 17:18:59.062  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:18:59.063  5630  5630 I bt_bluedroid: get_profile_interface health
11-28 17:18:59.064  5630  5630 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-28 17:18:59.065  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 17:18:59.066  5630  5630 D PanService: Received start request. Starting profile...
11-28 17:18:59.066  5630  5630 D BluetoothPanServiceJni: initializeNative(L110): pan
11-28 17:18:59.066  5630  5630 I bt_bluedroid: get_profile_interface pan
11-28 17:18:59.067  5630  5646 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-28 17:18:59.067  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.068  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.068  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.068  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:18:59.068  5630  5659 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 17:18:59.069  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:18:59.070  5630  5630 D BluetoothMapService: Received start request. Starting profile...
11-28 17:18:59.070  5630  5630 D BluetoothMapService: start()
11-28 17:18:59.073  5630  5630 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-28 17:18:59.074  5630  5630 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-28 17:18:59.074  5630  5630 D BluetoothMapAppObserver: createReceiver()
11-28 17:18:59.075  5630  5630 D BluetoothMapAppObserver: initObservers()
11-28 17:18:59.075  5630  5630 D BluetoothMapAppObserver: getEnabledAccountItems()
11-28 17:18:59.082  5630  5630 V SapService: SapBinder()
11-28 17:18:59.083  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:18:59.083  5630  5630 D SapService: Received start request. Starting profile...
11-28 17:18:59.083  5630  5630 V SapService: start()
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.085  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.086  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.086  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:59.086  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.086  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.086  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.086  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:59.087  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.087  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.087  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.087  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:59.088  5630  5630 V BluetoothAdapterState: isTurningOff()=false
11-28 17:18:59.088  5630  5630 V BluetoothAdapterState: isTurningOn()=true
11-28 17:18:59.088  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:18:59.088  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:18:59.088  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 17:18:59.088  5630  5642 D BluetoothAdapterProperties: ScanMode =  20
11-28 17:18:59.088  5630  5642 D BluetoothAdapterProperties: State =  11
11-28 17:18:59.089  5630  5642 D BluetoothAdapterProperties: Setting state to 12
11-28 17:18:59.089  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-28 17:18:59.089  3107  3120 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 17:18:59.091  5630  5642 I BluetoothAdapterState: Entering OnState
11-28 17:18:59.093  5630  5646 D BluetoothAdapterProperties: Scan Mode:21
11-28 17:18:59.093  3107  3107 D BluetoothInputDevice: Proxy object connected
11-28 17:18:59.093  5630  5646 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 17:18:59.093  3107  3107 D HidProfile: Bluetooth service connected
11-28 17:18:59.093  3107  3131 D BluetoothPan: onBluetoothStateChange on: true
11-28 17:18:59.095  5231  5242 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 17:18:59.095  3107  3107 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 17:18:59.096  3107  3107 D PanProfile: Bluetooth service connected
11-28 17:18:59.096  3107  3998 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:18:59.097  5231  5241 D BluetoothMap: onBluetoothStateChange: up=true
11-28 17:18:59.098  3774  3787 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:18:59.099  3107  3120 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 17:18:59.100  3107  3131 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 17:18:59.100  3107  3107 D BluetoothA2dp: Proxy object connected
11-28 17:18:59.100  5231  5231 D BluetoothA2dp: Proxy object connected
11-28 17:18:59.102  5630  5630 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 17:18:59.102  5630  5630 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-28 17:18:59.102  5231  5231 D BluetoothMap: Proxy object connected
11-28 17:18:59.102  5231  5231 D MapProfile: Bluetooth service connected
11-28 17:18:59.102  5231  5231 D BluetoothMap: getConnectedDevices()
11-28 17:18:59.103   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:18:59.103   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:18:59.103  5231  5241 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:18:59.103  5630  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:59.104  5231  5242 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 17:18:59.105  5630  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:59.106  3107  3998 D BluetoothMap: onBluetoothStateChange: up=true
11-28 17:18:59.107  5231  5231 D BluetoothInputDevice: Proxy object connected
11-28 17:18:59.107  5231  5231 D HidProfile: Bluetooth service connected
11-28 17:18:59.107  5630  5630 D ObexServerSockets: Succeed to create listening sockets 
11-28 17:18:59.107  5630  5630 D ObexServerSockets0: startAccept()
11-28 17:18:59.107  5630  5630 D ObexServerSockets0: prepareForNewConnect()
11-28 17:18:59.108  3107  3107 D BluetoothMap: Proxy object connected
11-28 17:18:59.108   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:18:59.108  3107  3107 D MapProfile: Bluetooth service connected
11-28 17:18:59.108  3107  3107 D BluetoothMap: getConnectedDevices()
11-28 17:18:59.108  5231  5241 D BluetoothPan: onBluetoothStateChange on: true
11-28 17:18:59.110  5630  5630 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-28 17:18:59.110  5630  5667 D ObexServerSockets0: Accepting socket connection...
11-28 17:18:59.110  5630  5630 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 17:18:59.111  5630  5668 D ObexServerSockets0: Accepting socket connection...
11-28 17:18:59.111   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 17:18:59.112   926   926 D BluetoothA2dp: Proxy object connected
11-28 17:18:59.112  5231  5666 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 17:18:59.112  5231  5231 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 17:18:59.112  5231  5231 D PanProfile: Bluetooth service connected
,11-28 17:18:59.116   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-28 17:18:59.117  5630  5630 D BluetoothMapService: onReceive
11-28 17:18:59.117  5630  5630 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-28 17:18:59.117  5630  5630 D BluetoothMapService: STATE_ON
11-28 17:18:59.119  5630  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:18:59.120  5630  5669 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-28 17:18:59.120  5630  5669 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-28 17:18:59.123  5231  5231 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 17:18:59.128  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:18:59.134  5231  5231 D DockEventReceiver: finishStartingService: stopping service
,11-28 17:18:59.136  5231  5231 D BluetoothPbap: Proxy object connected
11-28 17:18:59.136  5231  5231 D PbapServerProfile: Bluetooth service connected
,11-28 17:18:59.140  5630  5630 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 17:18:59.140  5630  5630 D ObexServerSockets0: prepareForNewConnect()
11-28 17:18:59.143  5630  5674 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:18:59.149  3107  3107 D BluetoothPbap: Proxy object connected
11-28 17:18:59.149  3107  3107 D PbapServerProfile: Bluetooth service connected
,11-28 17:18:59.157  5630  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:18:59.158  5630  5678 I BtOppRfcommListener: Accept thread started.
,11-28 17:18:59.199  3107  4000 D BluetoothHeadset: Proxy object connected
,11-28 17:18:59.199  3107  3107 D HeadsetProfile: Bluetooth service connected
11-28 17:18:59.199  3774  3786 D BluetoothHeadset: Proxy object connected
11-28 17:18:59.199  3774  3786 D BluetoothHeadset: Proxy object connected
11-28 17:18:59.199   926   926 D BluetoothHeadset: Proxy object connected
11-28 17:18:59.199   926   926 D BluetoothHeadset: Proxy object connected
,11-28 17:18:59.200  5231  5242 D BluetoothHeadset: Proxy object connected
,11-28 17:18:59.200   926   926 D BluetoothHeadset: Proxy object connected
11-28 17:18:59.200  5231  5231 D HeadsetProfile: Bluetooth service connected
,11-28 17:18:59.204   926   943 D BluetoothHeadset: Proxy object connected
11-28 17:18:59.204   926   943 D BluetoothHeadset: Proxy object connected
,11-28 17:18:59.204  5231  5241 D BluetoothHeadset: Proxy object connected
,11-28 17:18:59.205  5231  5231 D HeadsetProfile: Bluetooth service connected
,11-28 17:18:59.209   926   943 D BluetoothHeadset: Proxy object connected
,11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:18:59.466  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 17:18:59.471  5558  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:18:59.474  5558  5605 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-28 17:18:59.476   926  5445 D WifiService: setWifiEnabled: false pid=5558, uid=10077
,11-28 17:18:59.477   926  5445 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 17:18:59.481   926  2967 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-28 17:18:59.481   926  2967 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 17:18:59.482   926  2967 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 17:18:59.482   926  2967 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 17:18:59.482  5558  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:18:59.498   926  5339 D DhcpClient: Clearing IP address
,11-28 17:18:59.498   508   919 D CommandListener: Clearing all IP addresses on wlan0
,11-28 17:18:59.506   508   919 D CommandListener: Setting iface cfg
,11-28 17:18:59.510  3573  5391 V NativeCrypto: Read error: ssl=0x7f7d102000: I/O error during system call, Connection timed out
,11-28 17:18:59.512  3573  5391 V NativeCrypto: SSL shutdown failed: ssl=0x7f7d102000: I/O error during system call, Broken pipe
,11-28 17:18:59.515   926  3790 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-28 17:18:59.515   926  5337 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-28 17:18:59.518   926  5337 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-28 17:18:59.519   926  2969 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-28 17:18:59.519   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-28 17:18:59.522   926  2969 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-28 17:18:59.522   926  5340 D DhcpClient: Receive thread stopped
,11-28 17:18:59.525   926   926 D RttService: SCAN_AVAILABLE : 1
,11-28 17:18:59.525   926  2969 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-28 17:18:59.525   926  2969 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-28 17:18:59.525   926  3074 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-28 17:18:59.528   534   534 E Parcel  : Reading a NULL string not supported here.
11-28 17:18:59.532   926  2969 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-28 17:18:59.535  3732  3879 W QCNEJ   : |CORE| network lost: 100
11-28 17:18:59.535  3732  3879 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-28 17:18:59.547   926  2967 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-28 17:18:59.548   926  2967 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 17:18:59.557   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 17:18:59.578   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-28 17:18:59.579   508   919 D CommandListener: Clearing all IP addresses on wlan0
11-28 17:18:59.579   926  2969 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-28 17:18:59.579   508   919 D TetherController: Setting IP forward enable = 0
11-28 17:18:59.579   926  2969 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 17:18:59.581   926   943 D Tethering: MasterInitialState.processMessage what=3
11-28 17:18:59.583   926  2967 D DhcpClient: doQuit
,11-28 17:18:59.583   926  2967 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-28 17:18:59.584   926  5339 D DhcpClient: onQuitting
11-28 17:18:59.584  3468  3468 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 17:18:59.587  3944  3944 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-28 17:18:59.592  3958  3958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 17:18:59.594  4883  4909 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 17:18:59.594  4883  4909 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 17:18:59.594  4883  4909 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 17:18:59.594  4883  4909 E SarControlService: no key has been found,reset the power
11-28 17:18:59.594  4883  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 17:18:59.594  4883  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 17:18:59.594  4883  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-28 17:18:59.595  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 17:18:59.595  4922  4922 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 17:18:59.596  4883  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 17:18:59.596  4883  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 17:18:59.596  4883  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 17:18:59.597  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 17:18:59.597  4922  4922 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 17:18:59.600  4922  4936 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000ea03000000000000ffffffff]
11-28 17:18:59.600  4922  4936 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:18:59.600  4922  4936 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-28 17:18:59.601  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:18:59.601  4883  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 17:18:59.602  3958  3958 D SystemUpdateService: onCreate
,11-28 17:18:59.606  3958  3958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 17:18:59.607  4922  4936 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000eb03000000000000ffffffff]
11-28 17:18:59.608  4922  4936 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:18:59.608  4922  4936 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-28 17:18:59.608  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:18:59.608  4883  4894 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 17:18:59.608  3468  3468 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-28 17:18:59.612  3958  5696 I SystemUpdateService: active receiver: enabled
,11-28 17:18:59.613  3468  3468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-28 17:18:59.615   508   912 W SocketClient: write error (Broken pipe)
11-28 17:18:59.616   508   912 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-28 17:18:59.616   508   912 W SocketListener: Error sending broadcast (Broken pipe)
,11-28 17:18:59.617  3958  3958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-28 17:18:59.622  3958  5363 I iu.UploadsManager: num queued entries: 0
,11-28 17:18:59.623  3958  5363 I iu.UploadsManager: num updated entries: 0
11-28 17:18:59.623  3958  5363 I iu.SyncManager: NEXT; no task
11-28 17:18:59.624  3958  5696 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-28 17:18:59.625  3958  3958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 17:18:59.627  3958  3958 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 17:18:59.629  5366  5366 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 17:18:59.633  5366  5366 D SprintDMHelper: simOperator: 
11-28 17:18:59.633  5366  5366 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 17:18:59.638   508   919 E Netd    : netlink response contains error (No such file or directory)
,11-28 17:18:59.639   508   919 D TetherController: Setting IP forward enable = 0
11-28 17:18:59.640  3958  5696 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-28 17:18:59.640   926  2969 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 17:18:59.640  3958  5696 I SystemUpdateService: now status is 0 (complete)
11-28 17:18:59.641  3958  5696 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 17:18:59.641  3958  5696 I SystemUpdateService: file has been verified
11-28 17:18:59.642  3958  5696 I SystemUpdateService: OTA package size = 21989297
,11-28 17:18:59.645  4432  5700 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 17:18:59.647  3468  3468 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 17:18:59.653  3958  5696 I SystemUpdateService: showing system update notification
,11-28 17:18:59.658   926  3140 I ActivityManager: Start proc 5703:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-28 17:18:59.663  3468  3468 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 17:18:59.669   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-28 17:18:59.671  3958  3958 D SystemUpdateService: onDestroy
,11-28 17:18:59.693  5703  5703 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-28 17:18:59.700   926  3140 I ActivityManager: Killing 5424:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-28 17:18:59.767   926  2967 D wifi    : In wifi stop Hal
11-28 17:18:59.767   926  2967 D wifi    : halHandle = 0x7f7ceee200, mVM = 0x7f9854d140, mCls = 0x100a12
11-28 17:18:59.767   926  3467 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 17:18:59.767   926  3467 D WifiHAL : Got a signal to exit!!!
,11-28 17:18:59.767   926  3467 I WifiHAL : Exit wifi_event_loop
11-28 17:18:59.768   926  2967 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 17:18:59.768   926  2967 E WifiHAL : Event processing terminated
11-28 17:18:59.768   926  2967 D wifi    : In wifi cleaned up handler
11-28 17:18:59.768   926  2967 I WifiHAL : Internal cleanup completed
,11-28 17:18:59.767  4432  4432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 17:18:59.771  4098  4227 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 17:18:59.795   926  3467 D wifi    : set interface wlan0 flags (DOWN)
,11-28 17:18:59.795   926  2967 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 17:18:59.986  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 17:18:59.991  5558  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 17:18:59.995   926  5445 D WifiService: setWifiEnabled: true pid=5558, uid=10077
,11-28 17:18:59.995   926  5445 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:18:59.997  5558  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:19:00.003   926   943 D Tethering: InitialState.processMessage what=4
11-28 17:19:00.003   508   919 D SoftapController: Softap fwReload - Ok
,11-28 17:19:00.006   508   919 D CommandListener: Setting iface cfg
,11-28 17:19:00.007   508   919 D CommandListener: Trying to bring down wlan0
11-28 17:19:00.008   508   919 D CommandListener: Clearing all IP addresses on wlan0
11-28 17:19:00.008   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 17:19:00.011   926  2967 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 17:19:00.503   926   937 D WifiService: setWifiEnabled: true pid=5558, uid=10077
,11-28 17:19:00.507   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:19:00.621   926  2967 D wifi    : set interface wlan0 flags (UP)
11-28 17:19:00.621   926  2967 I WifiHAL : Initializing wifi
11-28 17:19:00.622   926  2967 I WifiHAL : Creating socket
11-28 17:19:00.628   926  2967 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-28 17:19:00.628   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 17:19:00.628   926  2967 D wifi    : Did set static halHandle = 0x7f7ceee200
11-28 17:19:00.628   926  2967 D wifi    : halHandle = 0x7f7ceee200, mVM = 0x7f9854d140, mCls = 0x2015a6
11-28 17:19:00.629   926  2967 D wifi    : array field set
,11-28 17:19:00.629   926  2967 I WifiNative-HAL: interface[0] = wlan0
11-28 17:19:00.631   926  5719 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547556876800
11-28 17:19:00.631   926  5719 D wifi    : waitForHalEvents called, vm = 0x7f9854d140, obj = 0x2015a6, env = 0x7f7d75ab00
,11-28 17:19:00.697  5720  5720 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 17:19:00.733   926  2967 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 17:19:00.768  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 17:19:00.789  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 17:19:00.789  5720  5720 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 17:19:00.802   926  2967 D WifiConfigStore: Loading config and enabling all networks 
,11-28 17:19:00.823   926  2967 D WifiConfigStore: loaded 0 passpoint configs
,11-28 17:19:00.824   926  2967 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-28 17:19:00.824   926  2967 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-28 17:19:00.825   926  2967 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-28 17:19:00.825   926  2967 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-28 17:19:00.825   926  2967 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-28 17:19:00.826   926  2967 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-28 17:19:00.826   926  2967 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-28 17:19:00.826   926  2967 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-28 17:19:00.826   926  2967 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-28 17:19:00.826   926  2967 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-28 17:19:00.826   926  2967 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-28 17:19:00.826   926  2967 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-28 17:19:00.828   926  2967 D WifiNative-HAL: Setting external_sim to 1
,11-28 17:19:00.829   926  2967 D wifi    : setting dfs flag to true, 0x7f802117a0
11-28 17:19:00.829  4432  4432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 17:19:00.829   926  2967 D WifiStateMachine: Setting OUI to DA-A1-19
11-28 17:19:00.829   926  2967 D wifi    : setting scan oui 0x7f802117a0
11-28 17:19:00.829   926  2967 D WifiHAL : Sending mac address OUI
,11-28 17:19:00.832   926  2967 E native  : do suspend false
,11-28 17:19:00.838   926  2967 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 17:19:00.838   926   926 D RttService: SCAN_AVAILABLE : 3
11-28 17:19:00.839   926  3074 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 17:19:00.842   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 17:19:00.843   508   919 D CommandListener: Setting iface cfg
,11-28 17:19:00.849   926  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-28 17:19:00.849   926  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 17:19:00.856   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=96172 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-28 17:19:00.861   926  2956 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 17:19:00.861   926  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 17:19:01.016  5558  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 17:19:01.021  5558  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 17:19:01.024  5558  5605 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 17:19:01.025   926  3788 D WifiService: setWifiEnabled: true pid=5558, uid=10077
,11-28 17:19:01.025   926  3788 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 17:19:01.026  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 17:19:01.026  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:19:01.026  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-28 17:19:01.026  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d0b7b removed from the list
11-28 17:19:01.027  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 17:19:01.027  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22f8d98 removed from the list
,11-28 17:19:01.027  5558  5605 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 17:19:01.030  5558  5605 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-28 17:19:01.033  5558  5605 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-28 17:19:01.036  5558  5605 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-28 17:19:01.038  5558  5605 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-28 17:19:01.041  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-28 17:19:01.042  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-28 17:19:01.043  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-28 17:19:01.043  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-28 17:19:01.044  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-28 17:19:01.049  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-28 17:19:01.049  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@41b0bc4 Bundle[{}]
11-28 17:19:01.050  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-28 17:19:01.050  5558  5605 I io.jxcore.node.LifeCycleMonitor: start: OK
11-28 17:19:01.050  5558  5605 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-28 17:19:01.051  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-28 17:19:01.051  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-28 17:19:01.052  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-28 17:19:01.052  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-28 17:19:01.052  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-28 17:19:01.053  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-28 17:19:01.053  5558  5605 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-28 17:19:01.054  5558  5605 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-28 17:19:01.055  5558  5605 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-28 17:19:01.056  5558  5605 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-28 17:19:01.057  5558  5605 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-28 17:19:01.058  5558  5605 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-28 17:19:01.058  5558  5605 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-28 17:19:01.059  5558  5605 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-28 17:19:01.061  5558  5605 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-28 17:19:01.062  5558  5605 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-28 17:19:02.066  5558  5605 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-28 17:19:02.068  5558  5605 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-28 17:19:02.072  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-28 17:19:02.074  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-28 17:19:02.076  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-28 17:19:02.076  5558  5605 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
11-28 17:19:02.078  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-28 17:19:02.078  5558  5605 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-28 17:19:02.078  5558  5605 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 174)
11-28 17:19:02.079  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-28 17:19:02.080  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-28 17:19:02.082  5558  5605 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-28 17:19:02.083  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 17:19:02.083  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eba99d6 added. We now have 3 listener(s)
,11-28 17:19:02.085  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:19:02.085  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:19:02.085  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:19:02.086  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 17:19:02.086  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6e457 added. We now have 3 listener(s)
,11-28 17:19:02.086  5558  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 17:19:02.087  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 17:19:02.093  5558  5605 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-28 17:19:02.094  5558  5605 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-28 17:19:02.094  5558  5605 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-28 17:19:02.094  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-28 17:19:02.094  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:02.095  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.095  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.095  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:19:02.095  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:19:02.095  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:19:02.095  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:19:02.095  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 17:19:02.100  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 17:19:02.101  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:19:02.102  5558  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:19:02.102  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:19:02.102  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-28 17:19:02.102  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 17:19:02.103  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:19:02.102  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 17:19:02.103  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:19:02.103  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:19:02.103  5558  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:19:02.104  5655  5655 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31460]" dev="sockfs" ino=31460 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:19:02.108  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:19:02.104  5655  5655 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31460]" dev="sockfs" ino=31460 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:19:02.108  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:19:02.108  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:19:02.109  5558  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 17:19:02.113  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:02.113  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:19:02.114  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:19:02.114  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:19:02.114  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-28 17:19:02.116  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.116  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.116  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-28 17:19:02.116  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:19:02.116  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:19:02.116  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-28 17:19:02.117  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:19:02.117  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:19:02.117  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.117  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-28 17:19:02.117  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:19:02.117  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.117  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.117  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:02.118  5558  5605 D BluetoothAdapter: STATE_ON
,11-28 17:19:02.122  5630  5641 D BtGatt.GattService: registerClient() - UUID=eddf7094-512d-4608-9a38-dfbc67b10635
,11-28 17:19:02.123  5630  5646 D BtGatt.GattService: onClientRegistered() - UUID=eddf7094-512d-4608-9a38-dfbc67b10635, clientIf=5
,11-28 17:19:02.124  5558  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 17:19:02.126  5630  5648 D BtGatt.AdvertiseManager: message : 0
,11-28 17:19:02.129  5630  5648 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:19:02.139  5630  5646 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:19:02.145  5630  5646 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:19:02.146  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.146  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.146  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 17:19:02.148  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:19:02.148  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:02.150  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:02.150  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.150  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:02.150  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:19:02.150  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.150  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:19:02.150  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:19:02.150  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.151  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 17:19:02.154  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 17:19:02.154  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:19:02.154  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.154  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:02.154  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:19:02.655  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-28 17:19:02.656  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 17:19:02.656  5558  5558 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 17:19:03.962  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 17:19:03.966  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 17:19:04.020   926  2967 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-28 17:19:04.021   926  2967 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-28 17:19:04.021   926  2967 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 17:19:04.034   926  2967 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 17:19:04.067   926  2967 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 17:19:04.074  5720  5720 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 17:19:04.497  5720  5720 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 17:19:04.534  5720  5720 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 17:19:04.535  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 17:19:04.547   926  2967 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 17:19:04.548   926  2967 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 17:19:04.548   926  2969 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 17:19:04.565   926  2967 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 17:19:04.578   508   919 D CommandListener: Setting iface cfg
,11-28 17:19:04.584   926  2967 D WifiStateMachine: Start Dhcp Watchdog 2
,11-28 17:19:04.593   926  5731 D DhcpClient: Receive thread started
,11-28 17:19:04.594   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:04.594   926  2967 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 17:19:04.594   926  2969 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-28 17:19:04.675   926  2967 E native  : do suspend false
,11-28 17:19:04.687   926  5730 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 17:19:04.710   926  5731 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172739, domain null
,11-28 17:19:04.710   926  5730 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172739 seconds
,11-28 17:19:04.712   926  5730 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-28 17:19:04.730   926  5731 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 17:19:04.731   926  5730 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 17:19:04.732   508   919 D CommandListener: Setting iface cfg
,11-28 17:19:04.735   926  2967 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 17:19:04.738   926  5730 D DhcpClient: Scheduling renewal in 86399s
,11-28 17:19:04.743   926  2967 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-28 17:19:04.744   926  2967 D WifiConfigStore: No blacklist allowed without epno enabled
,11-28 17:19:04.744   926  2969 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-28 17:19:04.746   926  2969 D ConnectivityService: Adding iface wlan0 to network 101
11-28 17:19:04.749   926  2967 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-28 17:19:04.779   926  2969 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-28 17:19:04.779   926  2969 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-28 17:19:04.780   926  2969 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-28 17:19:04.782   926  2969 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-28 17:19:04.783   926  2969 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-28 17:19:04.790   926  2969 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:04.794   926  2969 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-28 17:19:04.794   926  2969 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-28 17:19:04.794   926  2969 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-28 17:19:04.794   926  2967 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-28 17:19:04.794   926  2969 D ConnectivityService:    accepting network in place of null
11-28 17:19:04.794   926  2967 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 17:19:04.795   926  2969 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 17:19:04.803   926  5729 D NetlinkSocketObserver: NeighborEvent{elapsedMs=100119, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 17:19:04.817   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 17:19:04.837   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 17:19:04.840   926  2969 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-28 17:19:04.840   926  2969 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 17:19:04.840  3732  3879 W QCNEJ   : |CORE| network available: 101
11-28 17:19:04.841   926  2969 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-28 17:19:04.843   926   943 D Tethering: MasterInitialState.processMessage what=3
11-28 17:19:04.844  3732  3879 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 17:19:04.845  3732  3879 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 17:19:04.846  3732  3879 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-28 17:19:04.851  4883  4909 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 17:19:04.851  4883  4909 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 17:19:04.851  4883  4909 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-28 17:19:04.851  4883  4909 E SarControlService: no key has been found,reset the power
11-28 17:19:04.851  4883  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 17:19:04.852  4883  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 17:19:04.852  4883  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 17:19:04.852  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-28 17:19:04.852  4922  4922 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 17:19:04.853  4883  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 17:19:04.853  4883  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 17:19:04.853  4883  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 17:19:04.854  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 17:19:04.854  4922  4922 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-28 17:19:04.856  3944  3944 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-28 17:19:04.858  4922  4936 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000ec03000000000000ffffffff]
11-28 17:19:04.858  4922  4936 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:19:04.858  4922  4936 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-28 17:19:04.860  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:19:04.860  4883  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 17:19:04.861  3958  3958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 17:19:04.862  4922  4936 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000ed03000000000000ffffffff]
11-28 17:19:04.862  4922  4936 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:19:04.862  4922  4936 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-28 17:19:04.865  3958  3958 D SystemUpdateService: onCreate
11-28 17:19:04.866  4922  4922 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:19:04.866  4883  4894 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 17:19:04.867   926  5728 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-28 17:19:04.870  3958  3958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 17:19:04.880  3958  3958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-28 17:19:04.884  3958  5363 I iu.UploadsManager: num queued entries: 0
,11-28 17:19:04.885  3958  5363 I iu.UploadsManager: num updated entries: 0
,11-28 17:19:04.885  3958  5363 I iu.SyncManager: NEXT; no task
,11-28 17:19:04.889  3958  5741 I SystemUpdateService: active receiver: enabled
,11-28 17:19:04.891  3958  3958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 17:19:04.892  3958  3958 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 17:19:04.894  5366  5366 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 17:19:04.897  5366  5366 D SprintDMHelper: simOperator: 
11-28 17:19:04.898  5366  5366 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 17:19:04.915   926  5728 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 16:19:04 GMT], X-Android-Received-Millis=[1480349944915], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480349944892]}
,11-28 17:19:04.916   926  2969 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-28 17:19:04.916   926  2969 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-28 17:19:04.916   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-28 17:19:04.917   926  2969 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 17:19:04.921  3958  5741 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 17:19:04.936  3958  5741 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-28 17:19:04.936  3958  5741 I SystemUpdateService: now status is 0 (complete)
11-28 17:19:04.936  3958  5741 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 17:19:04.936  3958  5741 I SystemUpdateService: file has been verified
11-28 17:19:04.937  3958  5741 I SystemUpdateService: OTA package size = 21989297
,11-28 17:19:04.942  3958  5741 I SystemUpdateService: showing system update notification
,11-28 17:19:04.949   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 17:19:04.952  3958  3958 D SystemUpdateService: onDestroy
,11-28 17:19:05.004  4432  5746 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-28 17:19:05.652  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-28 17:19:05.653  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 17:19:05.653  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:19:05.653  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:19:05.653  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:19:05.654  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:19:05.654  5558  5724 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-28 17:19:05.654  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:19:05.654  5558  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:19:05.654  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:19:05.654  5558  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:19:05.655  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 17:19:05.655  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:19:05.655  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:19:05.655  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.655  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-28 17:19:05.655  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:19:05.656  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.656  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.656  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.656  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.660  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:05.660  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-28 17:19:05.662  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:05.662  5558  5605 D BluetoothLeScanner: could not find callback wrapper
11-28 17:19:05.662  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:19:05.663  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.663  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.663  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.663  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:19:05.663  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.665  5630  5648 D BtGatt.AdvertiseManager: message : 1
11-28 17:19:05.666  5630  5648 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:19:05.680  5630  5646 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 17:19:05.680  5630  5646 D BtGatt.GattService: Client app is not null!
11-28 17:19:05.682  5630  5641 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:19:05.683  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:19:05.683  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.683  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:19:05.683  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.684  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.684  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.684  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 17:19:05.684  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:19:05.685  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 17:19:05.686  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.689  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.689  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:19:05.690  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.690  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.690  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 17:19:05.690  5558  5558 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 17:19:05.691  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:19:05.691  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:19:05.691  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:19:05.691  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:19:05.692  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:19:05.692  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 17:19:05.692  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:19:05.693  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-28 17:19:05.693  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.693  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.693  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.693  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:19:05.693  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-28 17:19:05.694  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.696  5558  5605 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-28 17:19:05.696  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 17:19:05.696  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:19:05.696  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.696  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.697  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:19:05.697  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-28 17:19:05.697  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 17:19:05.697  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:19:05.698  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 17:19:05.700  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 17:19:05.704  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 17:19:05.704  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:19:05.704  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 17:19:05.708  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.708  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:19:05.709  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 17:19:05.709  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:19:05.709  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-28 17:19:05.713  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-28 17:19:05.719  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-28 17:19:05.722  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.722  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-28 17:19:05.723  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 17:19:05.723  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 17:19:05.726  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 17:19:05.726  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.727  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:05.733  5630  5670 D BtGatt.GattService: registerClient() - UUID=8b19aa0b-a7dd-4c3b-b25b-0ee5788a73cf
,11-28 17:19:05.734  5630  5646 D BtGatt.GattService: onClientRegistered() - UUID=8b19aa0b-a7dd-4c3b-b25b-0ee5788a73cf, clientIf=5
,11-28 17:19:05.734  5558  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 17:19:05.735  5630  5640 D BtGatt.GattService: start scan with filters
,11-28 17:19:05.739  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 17:19:05.739  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.739  5630  5649 D BtGatt.ScanManager: handling starting scan
11-28 17:19:05.739  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-28 17:19:05.740  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.740  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:19:05.740  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 17:19:05.740  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.741  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 17:19:05.741  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:19:05.741  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.741  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.741  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.741  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-28 17:19:05.742  5630  5649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 17:19:05.742  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:19:05.742  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.745  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:05.745  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 17:19:05.745  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.745  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:05.746  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 17:19:05.749  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 17:19:05.749  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.749  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:05.749  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-28 17:19:05.750  5630  5646 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 17:19:05.751  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:05.751  5630  5649 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 17:19:05.759  5630  5646 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-28 17:19:05.759  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:19:05.759  5630  5649 D BtGatt.ScanManager: Starting BLE batch scan
11-28 17:19:05.760  5630  5649 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 17:19:05.769  5630  5646 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 17:19:05.769  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:05.774  5630  5646 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 17:19:05.775  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:05.841   926  2969 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-28 17:19:06.250  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-28 17:19:06.251  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:19:06.251  5558  5558 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 17:19:07.613   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:08.748  5558  5605 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-28 17:19:08.748  5558  5605 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-28 17:19:08.748  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-28 17:19:08.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:08.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.749  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 17:19:08.750  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.750  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-28 17:19:08.750  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.750  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.751  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:19:08.751  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:19:08.751  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.751  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.751  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.754  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:08.755  5630  5640 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 17:19:08.756  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:19:08.757  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:08.759  5630  5670 D BtGatt.GattService: stopScan() - queue size =1
,11-28 17:19:08.760  5630  5649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 17:19:08.761  5630  5640 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 17:19:08.761  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:19:08.762  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.762  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 17:19:08.762  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:08.762  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:19:08.762  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.763  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:08.763  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 17:19:08.763  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-28 17:19:08.763  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 17:19:08.763  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 17:19:08.763  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.765  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:08.768  5630  5640 D BtGatt.GattService: registerClient() - UUID=37865d16-dd5a-4722-a094-28ff1adb090e
11-28 17:19:08.768  5630  5646 D BtGatt.GattService: onClientRegistered() - UUID=37865d16-dd5a-4722-a094-28ff1adb090e, clientIf=5
,11-28 17:19:08.769  5558  5568 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 17:19:08.769  5630  5641 D BtGatt.GattService: start scan with filters
11-28 17:19:08.772  5630  5630 D BtGatt.ScanManager: awakened up at time 104088
11-28 17:19:08.772  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 17:19:08.773  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.773  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 17:19:08.773  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.773  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.773  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:19:08.773  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 17:19:08.773  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.773  5558  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:19:08.773  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 17:19:08.773  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:19:08.773  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 17:19:08.773  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:19:08.773  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.773  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.774  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:19:08.775  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 17:19:08.776  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:19:08.776  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:19:08.776  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:19:08.776  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:19:08.776  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-28 17:19:08.777  5558  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:19:08.777  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:19:08.777  5558  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-28 17:19:08.778  5558  5754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:19:08.778  5640  5640 W Binder_1: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[21409]" dev="sockfs" ino=21409 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:19:08.778  5640  5640 W Binder_1: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[21409]" dev="sockfs" ino=21409 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:19:08.780  5630  5646 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-28 17:19:08.780  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:08.781  5630  5646 D BtGatt.GattService: current time is 104096895249
11-28 17:19:08.781  5630  5646 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -85, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -89, 1, 12, 55, 1, 107, 1, -128, -92, 34, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 17:19:08.782  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 17:19:08.783  5558  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:19:08.783  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
11-28 17:19:08.784  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-28 17:19:08.785  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-28 17:19:08.787  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.787  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.787  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.787  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:19:08.787  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:19:08.787  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:19:08.787  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-28 17:19:08.787  5558  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:19:08.788  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:19:08.788  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.788  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:19:08.788  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 17:19:08.788  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.788  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.788  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.789  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:08.790  5630  5646 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 17:19:08.790  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:19:08.790  5630  5649 D BtGatt.ScanManager: stopping BLe Batch
,11-28 17:19:08.791  5630  5655 D BtGatt.GattService: registerClient() - UUID=265b7b4c-bc0d-4587-87d6-b169faa09b1e
11-28 17:19:08.791  5630  5646 D BtGatt.GattService: onClientRegistered() - UUID=265b7b4c-bc0d-4587-87d6-b169faa09b1e, clientIf=6
11-28 17:19:08.792  5558  5569 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-28 17:19:08.793  5630  5648 D BtGatt.AdvertiseManager: message : 0
,11-28 17:19:08.795  5630  5648 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:19:08.796  5630  5646 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 17:19:08.796  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:19:08.796  5630  5649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 17:19:08.801  5630  5646 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 17:19:08.801  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:08.803  5630  5649 D BtGatt.ScanManager: handling starting scan
,11-28 17:19:08.810  5630  5646 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-28 17:19:08.815  5630  5646 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-28 17:19:08.815  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:19:08.815  5630  5649 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 17:19:08.820  5630  5646 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-28 17:19:08.820  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-28 17:19:08.821  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-28 17:19:08.821  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:19:08.822  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:19:08.823  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.825  5630  5646 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 17:19:08.825  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:08.825  5630  5649 D BtGatt.ScanManager: Starting BLE batch scan
11-28 17:19:08.825  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.825  5630  5649 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 17:19:08.825  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.825  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:08.826  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-28 17:19:08.826  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 17:19:08.826  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-28 17:19:08.826  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:19:08.826  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.826  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.826  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:19:08.826  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.827  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-28 17:19:08.827  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 17:19:08.827  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.827  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.827  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.827  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.827  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 17:19:08.830  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.830  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-28 17:19:08.831  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:08.831  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 17:19:08.831  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-28 17:19:08.835  5630  5646 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 17:19:08.835  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:08.839  5630  5646 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 17:19:08.839  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:08.840  5630  5649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 17:19:08.845  5630  5646 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 17:19:08.845  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:08.846  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-28 17:19:09.332  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-28 17:19:09.332  5558  5558 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 17:19:09.332  5558  5558 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 17:19:10.644   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:11.829  5558  5605 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-28 17:19:11.829  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 17:19:11.829  5558  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:19:11.829  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:19:11.830  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:19:11.830  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 17:19:11.830  5558  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:19:11.830  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 17:19:11.830  5558  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-28 17:19:11.830  5558  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:19:11.830  5558  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 17:19:11.831  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 17:19:11.831  5558  5558 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:19:11.831  5558  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eba99d6 removed from the list
,11-28 17:19:11.831  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 17:19:11.831  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:19:11.831  5558  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:19:11.831  5558  5558 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:19:11.832  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.832  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:19:11.832  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:19:11.832  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:11.832  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.832  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.833  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 17:19:11.833  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.835  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:11.835  5630  5640 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 17:19:11.836  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:19:11.837  5558  5605 D BluetoothAdapter: STATE_ON
11-28 17:19:11.838  5630  5649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 17:19:11.840  5630  5641 D BtGatt.GattService: stopScan() - queue size =1
11-28 17:19:11.842  5630  5655 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:19:11.843  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:19:11.843  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.843  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 17:19:11.844  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.844  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.844  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.844  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:19:11.844  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.845  5630  5648 D BtGatt.AdvertiseManager: message : 1
11-28 17:19:11.846  5630  5648 D BtGatt.AdvertiseManager: stop advertise for client 6
11-28 17:19:11.847  5630  5630 D BtGatt.ScanManager: awakened up at time 107163
,11-28 17:19:11.864  5630  5646 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-28 17:19:11.864  5630  5646 D BtGatt.GattService: Client app is not null!
,11-28 17:19:11.865  5630  5641 D BtGatt.GattService: unregisterClient() - clientIf=6
11-28 17:19:11.865  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 17:19:11.866  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:11.866  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:19:11.866  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.866  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:11.866  5558  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:11.866  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:19:11.866  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:19:11.867  5558  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 17:19:11.869  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:11.871  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-28 17:19:11.871  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:19:11.871  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.871  5558  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-28 17:19:11.872  5558  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6e457 removed from the list
,11-28 17:19:11.872  5558  5605 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:19:11.872  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:19:11.872  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:19:11.872  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 17:19:11.872  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.872  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:19:11.872  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-28 17:19:11.872  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.873  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-28 17:19:11.873  5558  5558 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:19:11.874  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 17:19:11.874  5558  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.874  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 17:19:11.874  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.874  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 17:19:11.874  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:19:11.874  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-28 17:19:11.874  5558  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 17:19:11.875  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-28 17:19:11.875  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.876  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:19:11.876  5558  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: T,hread[main,5,main], id: 1
11-28 17:19:11.877  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-28 17:19:11.878  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-28 17:19:11.879  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-28 17:19:11.880  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-28 17:19:11.881  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-28 17:19:11.882  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-28 17:19:11.883  5558  5605 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-28 17:19:11.894  5630  5646 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-28 17:19:11.894  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:11.894  5630  5646 D BtGatt.GattService: current time is 107210360073
11-28 17:19:11.895  5630  5646 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -89, 1, 12, 55, 1, 107, 1, -128, -93, 31, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -84, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 17:19:11.895  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 17:19:11.895  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 17:19:11.895  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
,11-28 17:19:11.895  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 17:19:11.896  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 17:19:11.896  5630  5646 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-28 17:19:11.903  5630  5646 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 17:19:11.903  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:19:11.903  5630  5649 D BtGatt.ScanManager: stopping BLe Batch
,11-28 17:19:11.910  5630  5646 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 17:19:11.910  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:19:11.910  5630  5649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 17:19:11.916  5630  5646 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 17:19:11.916  5630  5646 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:19:12.375  5558  5558 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 17:19:12.795   926  2969 D ConnectivityService: handlePromptUnvalidated 101
,11-28 17:19:13.664   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:13.887  5558  5605 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-28 17:19:14.034  5558  5756 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 17:19:14.034  5558  5756 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:14.848  5558  5756 W !!      : call onHalfStreamCopied
,11-28 17:19:14.848  5558  5756 I testCopyDataAndClose: closing input stream
,11-28 17:19:15.088   926  2967 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 8 -> obsolete
,11-28 17:19:15.623  5558  5756 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 17:19:15.623  5558  5756 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:15.623  5558  5756 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 17:19:15.623  5558  5756 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 17:19:15.623  5558  5756 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 17:19:15.624  5558  5756 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 17:19:15.624  5558  5756 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 17:19:15.624  5558  5756 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-28 17:19:15.624  5558  5756 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 17:19:15.624  5558  5756 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 17:19:15.624  5558  5756 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 17:19:15.857   926  2967 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-28 17:19:16.967   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 17:19:16.967   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 17:19:19.708   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:19.960  5558  5605 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-28 17:19:20.044  5558  5757 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 17:19:20.044  5558  5757 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:21.682  5558  5757 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 17:19:21.682  5558  5757 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 17:19:21.683  5558  5757 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 17:19:21.968   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:19:22.745   926  2969 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:19:22.969   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:19:23.971   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:19:24.973   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:19:25.864  5558  5605 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-28 17:19:25.866  5558  5759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:19:25.866  5558  5759 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:25.868  5558  5759 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:19:25.868  5558  5759 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:25.868  5558  5759 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 17:19:25.868  5558  5759 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:19:25.868  5558  5759 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 17:19:25.868  5558  5759 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 17:19:25.869  5558  5759 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 17:19:25.869  5558  5759 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-28 17:19:25.869  5558  5759 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 17:19:25.870  5558  5759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:19:25.870  5558  5759 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-28 17:19:25.871  5558  5605 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-28 17:19:25.871  5558  5605 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-28 17:19:25.872  5558  5605 I StreamCopyingThreadTest: Starting test: testRunWithException
11-28 17:19:25.874  5558  5760 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:19:25.874  5558  5760 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 17:19:25.875  5558  5760 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
11-28 17:19:25.875  5558  5760 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:19:25.875  5558  5760 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-28 17:19:25.875  5558  5760 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-28 17:19:25.876  5558  5760 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:19:25.876  5558  5760 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 17:19:25.880  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG UnitTest_app: 'Running unit tests'
11-28 17:19:25.880  5558  5605 I jxcore-log: 
11-28 17:19:25.880  5558  5605 I jxcore-log: *Native tests were executed*
11-28 17:19:25.880  5558  5605 I jxcore-log: 
11-28 17:19:25.880  5558  5605 I jxcore-log: Total number of executed tests:  81
11-28 17:19:25.880  5558  5605 I jxcore-log: 
,11-28 17:19:25.881  5558  5605 I jxcore-log: Number of passed tests:  79
11-28 17:19:25.881  5558  5605 I jxcore-log: 
11-28 17:19:25.881  5558  5605 I jxcore-log: Number of failed tests:  0
11-28 17:19:25.881  5558  5605 I jxcore-log: 
11-28 17:19:25.881  5558  5605 I jxcore-log: Number of ignored tests:  2
11-28 17:19:25.881  5558  5605 I jxcore-log: 
11-28 17:19:25.881  5558  5605 I jxcore-log: Total duration:  35399
11-28 17:19:25.881  5558  5605 I jxcore-log: 
11-28 17:19:25.883  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-28 17:19:25.883  5558  5605 I jxcore-log: 
,11-28 17:19:25.886  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:19:25.886  5558  5605 I jxcore-log: 
11-28 17:19:25.886  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.886  5558  5605 I jxcore-log: 
11-28 17:19:25.887  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:19:25.887  5558  5605 I jxcore-log: 
11-28 17:19:25.887  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.887  5558  5605 I jxcore-log: 
11-28 17:19:25.888  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:19:25.888  5558  5605 I jxcore-log: 
11-28 17:19:25.889  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:19:25.889  5558  5605 I jxcore-log: 
11-28 17:19:25.889  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.889  5558  5605 I jxcore-log: 
11-28 17:19:25.890  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:19:25.890  5558  5605 I jxcore-log: 
,11-28 17:19:25.890  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:19:25.890  5558  5605 I jxcore-log: 
11-28 17:19:25.890  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.890  5558  5605 I jxcore-log: 
,11-28 17:19:25.890  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:19:25.890  5558  5605 I jxcore-log: 
11-28 17:19:25.890  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:19:25.890  5558  5605 I jxcore-log: 
,11-28 17:19:25.891  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.891  5558  5605 I jxcore-log: 
11-28 17:19:25.891  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 17:19:25.891  5558  5605 I jxcore-log: 
11-28 17:19:25.891  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.891  5558  5605 I jxcore-log: 
11-28 17:19:25.891  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:19:25.891  5558  5605 I jxcore-log: 
11-28 17:19:25.892  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.892  5558  5605 I jxcore-log: 
11-28 17:19:25.892  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 17:19:25.892  5558  5605 I jxcore-log: 
11-28 17:19:25.892  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.892  5558  5605 I jxcore-log: 
11-28 17:19:25.892  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:19:25.892  5558  5605 I jxcore-log: 
11-28 17:19:25.892  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.892  5558  5605 I jxcore-log: 
,11-28 17:19:25.893  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:19:25.893  5558  5605 I jxcore-log: 
11-28 17:19:25.893  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.893  5558  5605 I jxcore-log: 
11-28 17:19:25.893  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 17:19:25.893  5558  5605 I jxcore-log: 
11-28 17:19:25.893  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.893  5558  5605 I jxcore-log: 
11-28 17:19:25.894  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-28 17:19:25.894  5558  5605 I jxcore-log: 
11-28 17:19:25.894  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:19:25.894  5558  5605 I jxcore-log: 
,11-28 17:19:25.894  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:19:25.894  5558  5605 I jxcore-log: 
11-28 17:19:25.894  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:19:25.894  5558  5605 I jxcore-log: 
11-28 17:19:25.895  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.895  5558  5605 I jxcore-log: 
11-28 17:19:25.896  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 17:19:25.896  5558  5605 I jxcore-log: 
11-28 17:19:25.896  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:19:25.896  5558  5605 I jxcore-log: 
,11-28 17:19:25.896  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.896  5558  5605 I jxcore-log: 
11-28 17:19:25.897  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-28 17:19:25.897  5558  5605 I jxcore-log: 
11-28 17:19:25.897  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:19:25.897  5558  5605 I jxcore-log: 
11-28 17:19:25.897  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.897  5558  5605 I jxcore-log: 
11-28 17:19:25.897  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 17:19:25.897  5558  5605 I jxcore-log: 
11-28 17:19:25.897  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:19:25.897  5558  5605 I jxcore-log: 
,11-28 17:19:25.899  5558  5558 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-28 17:19:25.899  5558  5558 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-28 17:19:25.902  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-28 17:19:25.902  5558  5605 I jxcore-log: 
11-28 17:19:25.903  5558  5605 I jxcore-log: 2016-11-28 16:19:25 - WARN testUtils: 'myNameCallback not set!'
11-28 17:19:25.903  5558  5605 I jxcore-log: 
,11-28 17:19:25.974   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:19:26.975   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 17:19:28.027  5558  5605 I jxcore-log: 2016-11-28 16:19:28 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-28 17:19:28.027  5558  5605 I jxcore-log: 
,11-28 17:19:28.029  5558  5605 I jxcore-log: 2016-11-28 16:19:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-28 17:19:28.029  5558  5605 I jxcore-log: 
,11-28 17:19:28.380  5558  5605 I jxcore-log: 2016-11-28 16:19:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-28 17:19:28.380  5558  5605 I jxcore-log: 
,11-28 17:19:28.393  5558  5605 I jxcore-log: 2016-11-28 16:19:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-28 17:19:28.393  5558  5605 I jxcore-log: 
,11-28 17:19:28.644  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 17:19:29.346  3675  3845 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-28 17:19:29.346  3675  3845 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-28 17:19:29.375  3573  3573 I ConfigService: onCreate
,11-28 17:19:29.498  5558  5605 I jxcore-log: 2016-11-28 16:19:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-28 17:19:29.498  5558  5605 I jxcore-log: 
,11-28 17:19:29.667  5558  5605 I jxcore-log: 2016-11-28 16:19:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-28 17:19:29.667  5558  5605 I jxcore-log: 
,11-28 17:19:29.673  5558  5605 I jxcore-log: 2016-11-28 16:19:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-28 17:19:29.673  5558  5605 I jxcore-log: 
,11-28 17:19:29.685  5558  5605 I jxcore-log: 2016-11-28 16:19:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-28 17:19:29.685  5558  5605 I jxcore-log: 
,11-28 17:19:30.183  5558  5605 I jxcore-log: 2016-11-28 16:19:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-28 17:19:30.183  5558  5605 I jxcore-log: 
,11-28 17:19:30.229  5558  5605 I jxcore-log: 2016-11-28 16:19:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-28 17:19:30.229  5558  5605 I jxcore-log: 
,11-28 17:19:30.243  5558  5605 I jxcore-log: 2016-11-28 16:19:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-28 17:19:30.243  5558  5605 I jxcore-log: 
,11-28 17:19:30.247  5558  5605 I jxcore-log: 2016-11-28 16:19:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-28 17:19:30.247  5558  5605 I jxcore-log: 
,11-28 17:19:30.529  5558  5605 I jxcore-log: 2016-11-28 16:19:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-28 17:19:30.529  5558  5605 I jxcore-log: 
,11-28 17:19:30.660  5558  5605 I jxcore-log: 2016-11-28 16:19:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-28 17:19:30.660  5558  5605 I jxcore-log: 
,11-28 17:19:31.039  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-28 17:19:31.039  5558  5605 I jxcore-log: 
,11-28 17:19:31.045  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-28 17:19:31.045  5558  5605 I jxcore-log: 
,11-28 17:19:31.050  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-28 17:19:31.050  5558  5605 I jxcore-log: 
,11-28 17:19:31.053  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-28 17:19:31.053  5558  5605 I jxcore-log: 
,11-28 17:19:31.059  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-28 17:19:31.059  5558  5605 I jxcore-log: 
,11-28 17:19:31.097  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-28 17:19:31.097  5558  5605 I jxcore-log: 
,11-28 17:19:31.103  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-28 17:19:31.103  5558  5605 I jxcore-log: 
,11-28 17:19:31.133  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-28 17:19:31.133  5558  5605 I jxcore-log: 
,11-28 17:19:31.172  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-28 17:19:31.172  5558  5605 I jxcore-log: 
,11-28 17:19:31.179  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-28 17:19:31.179  5558  5605 I jxcore-log: 
,11-28 17:19:31.186  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-28 17:19:31.186  5558  5605 I jxcore-log: 
,11-28 17:19:31.201  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-28 17:19:31.201  5558  5605 I jxcore-log: 
,11-28 17:19:31.216  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-28 17:19:31.216  5558  5605 I jxcore-log: 
,11-28 17:19:31.222  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-28 17:19:31.222  5558  5605 I jxcore-log: 
,11-28 17:19:31.228  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-28 17:19:31.228  5558  5605 I jxcore-log: 
,11-28 17:19:31.241  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-28 17:19:31.241  5558  5605 I jxcore-log: 
,11-28 17:19:31.259  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-28 17:19:31.259  5558  5605 I jxcore-log: 
,11-28 17:19:31.273  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-28 17:19:31.273  5558  5605 I jxcore-log: 
,11-28 17:19:31.284  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-28 17:19:31.284  5558  5605 I jxcore-log: 
,11-28 17:19:31.297  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-28 17:19:31.297  5558  5605 I jxcore-log: 
,11-28 17:19:31.307  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-28 17:19:31.307  5558  5605 I jxcore-log: 
,11-28 17:19:31.321  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-28 17:19:31.321  5558  5605 I jxcore-log: 
,11-28 17:19:31.330  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-28 17:19:31.330  5558  5605 I jxcore-log: 
,11-28 17:19:31.337  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-28 17:19:31.337  5558  5605 I jxcore-log: 
,11-28 17:19:31.358  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-28 17:19:31.358  5558  5605 I jxcore-log: 
,11-28 17:19:31.365  5558  5605 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-28 17:19:31.366  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO testUtils: 'BLE multiple advertisement supported'
11-28 17:19:31.366  5558  5605 I jxcore-log: 
,11-28 17:19:31.404  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-28 17:19:31.404  5558  5605 I jxcore-log: 
,11-28 17:19:31.446  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 17:19:31.446  5558  5605 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 17:19:31.446  5558  5605 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 17:19:31.446  5558  5605 I jxcore-log: emit@events.js:82:1
11-28 17:19:31.446  5558  5605 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 17:19:31.446  5558  5605 I jxcore-log: emit@events.js:82:1''
11-28 17:19:31.446  5558  5605 I jxcore-log: 
,11-28 17:19:31.446  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - DEBUG CoordinatedClient: 'test client failed'
11-28 17:19:31.446  5558  5605 I jxcore-log: 
,11-28 17:19:31.449  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 17:19:31.449  5558  5605 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 17:19:31.449  5558  5605 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 17:19:31.449  5558  5605 I jxcore-log: emit@events.js:82:1
11-28 17:19:31.449  5558  5605 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 17:19:31.449  5558  5605 I jxcore-log: emit@events.js:82:1''
11-28 17:19:31.449  5558  5605 I jxcore-log: 
,11-28 17:19:31.450  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-28 17:19:31.450  5558  5605 I jxcore-log: 
11-28 17:19:31.450  5558  5605 I jxcore-log: 2016-11-28 16:19:31 - ERROR runTests: 'websocket error
11-28 17:19:31.450  5558  5605 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 17:19:31.450  5558  5605 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 17:19:31.450  5558  5605 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 17:19:31.450  5558  5605 I jxcore-log: emit@events.js:82:1
11-28 17:19:31.450  5558  5605 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 17:19:31.450  5558  5605 I jxcore-log: emit@events.js:82:1'
11-28 17:19:31.450  5558  5605 I jxcore-log: 
,11-28 17:19:31.975  5762  5762 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 17:19:31.976   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:19:31.981  5762  5762 D AndroidRuntime: CheckJNI is OFF
,11-28 17:19:32.008  5762  5762 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-28 17:19:32.036  5762  5762 I Radio-JNI: register_android_hardware_Radio DONE
,11-28 17:19:32.052  5762  5762 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-28 17:19:32.061   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-28 17:19:32.061   926   939 I ActivityManager: Killing 5558:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-28 17:19:32.163   926  3141 D GraphicsStats: Buffer count: 2
,11-28 17:19:32.163   926  3790 I WindowState: WIN DEATH: Window{6ca9e1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-28 17:19:32.164   926  2968 D WifiService: Client connection lost with reason: 4
,11-28 17:19:32.181   926   939 W ActivityManager: Force removing ActivityRecord{b3602f3 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-28 17:19:32.209   926   950 I art     : Starting a blocking GC Explicit
,11-28 17:19:32.214   926   937 W ActivityManager: Spurious death for ProcessRecord{fd8b502 0:com.test.thalitest/u0a77}, curProc for 5558: null
,11-28 17:19:32.244   926  3141 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5558 uid 10077
,11-28 17:19:32.245  3675  3675 I Keyboard.Facilitator: onFinishInput()
,11-28 17:19:32.241  3141  3141 W Binder_4: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[29734]" dev="sockfs" ino=29734 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 17:19:32.241  3141  3141 W Binder_4: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[29734]" dev="sockfs" ino=29734 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:19:32.302   926   950 I art     : Explicit concurrent mark sweep GC freed 72256(4MB) AllocSpace objects, 15(512KB) LOS objects, 33% free, 29MB/43MB, paused 1.665ms total 92.443ms
,11-28 17:19:32.310  3944  5774 I MicroRecognitionRnrImpl: Starting detection.
,11-28 17:19:32.311  3944  5775 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ecfcd8c
,11-28 17:19:32.313   513  5777 I AudioFlinger: AudioFlinger's thread 0xf1dc0000 ready to run
,11-28 17:19:32.321   513  2997 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 17:19:32.322   926   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-28 17:19:32.324  3944  5775 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ecfcd8c
,11-28 17:19:32.325  5762  5762 I art     : System.exit called, status: 0
11-28 17:19:32.325  5762  5762 I AndroidRuntime: VM exiting with result code 0.
,11-28 17:19:32.333   513  5777 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-28 17:19:32.333   513  5777 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-28 17:19:32.333   513  5777 I ACDB-LOADER: ACDB AFE returned = -19
11-28 17:19:32.333   513  5777 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-28 17:19:32.333   513  5777 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-28 17:19:32.333   513  5777 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-28 17:19:32.340   513  5777 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-28 17:19:32.341   926   950 I ActivityManager: Start proc 5779:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-28 17:19:32.341   926   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-28 17:19:32.351  3675  3675 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-28 17:19:32.352  5630  5630 D BluetoothMapAppObserver: onReceive
,11-28 17:19:32.353  5630  5630 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-28 17:19:32.357  4098  4171 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-28 17:19:32.367  3675  5792 I Keyboard.Facilitator.DecoderInitializer: run()
11-28 17:19:32.370   926  2907 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-28 17:19:32.381  3675  5792 I Decoder : createOrResetDecoder
,11-28 17:19:32.384  3424  5793 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-28 17:19:32.418  3774  3774 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-28 17:19:32.424  3944  3944 I HotwordWorkerImpl: onReady
,11-28 17:19:32.421    28    28 W kworker/2:1: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:19:32.429   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-28 17:19:32.424    28    28 W kworker/2:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:19:32.438   926   938 E PackageManager: Failed to write settings, restoring backup
11-28 17:19:32.438   926   938 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-28 17:19:32.438   926   938 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-28 17:19:32.438   926   938 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-28 17:19:32.438   926   938 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-28 17:19:32.438   926   938 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
11-28 17:19:32.438   926   938 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
11-28 17:19:32.438   926   938 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
11-28 17:19:32.438   926   938 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
11-28 17:19:32.438   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
11-28 17:19:32.438   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-28 17:19:32.438   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-28 17:19:32.438   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 17:19:32.438   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:19:32.438   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 17:19:32.438   926   938 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-28 17:19:32.438   926   938 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-28 17:19:32.438   926   938 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-28 17:19:32.438   926   938 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-28 17:19:32.438   926   938 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-28 17:19:32.438   926   938 E PackageManager: 	... 12 more
,11-28 17:19:32.438  3573  3573 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-28 17:19:32.439  3573  3573 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-28 17:19:32.440  3573  3573 E AndroidRuntime: FATAL EXCEPTION: main
11-28 17:19:32.440  3573  3573 E AndroidRuntime: Process: com.google.process.gapps, PID: 3573
11-28 17:19:32.440  3573  3573 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-28 17:19:32.440  3573  3573 E AndroidRuntime: 	... 8 more
,11-28 17:19:32.441    28    28 W kworker/2:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:19:32.447  3675  5792 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-28 17:19:32.451   926  3796 I ActivityManager: Start proc 5799:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-28 17:19:32.452  3789  3909 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-28 17:19:32.452  3789  3909 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3789
11-28 17:19:32.452  3789  3909 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:19:32.452  3789  3909 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 17:19:32.457   926  5807 E DropBoxManagerService: Can't write: system_app_crash
11-28 17:19:32.457   926  5807 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:19:32.457   926  5807 E DropBoxManagerService: 	... 5 more
,11-28 17:19:32.457   926  5809 E DropBoxManagerService: Can't write: system_app_crash
11-28 17:19:32.457   926  5809 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:19:32.457   926  5809 E DropBoxManagerService: 	... 5 more
11-28 17:19:32.459   926   936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-28 17:19:32.469  3944  3980 W SearchService: Abort, client detached.
,11-28 17:19:32.472  3944  3944 I HotwordDetector: Closing mic
,11-28 17:19:32.472  3944  4172 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ecfcd8c
11-28 17:19:32.472  3944  5775 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-28 17:19:32.492  3424  5793 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-28 17:19:32.493  3424  5793 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-28 17:19:32.493  3424  5793 E AndroidRuntime: Process: android.process.acore, PID: 3424
11-28 17:19:32.493  3424  5793 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:19:32.493  3424  5793 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 17:19:32.518   926  5813 E DropBoxManagerService: Can't write: system_app_crash
11-28 17:19:32.518   926  5813 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:19:32.518   926  5813 E DropBoxManagerService: 	... 5 more
,11-28 17:19:32.527   926  2930 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 17:19:32.527   926  2930 I Adreno  : Build Date                       : 12/06/15
11-28 17:19:32.527   926  2930 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 17:19:32.527   926  2930 I Adreno  : Local Branch                     : mybranch17112971
11-28 17:19:32.527   926  2930 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 17:19:32.527   926  2930 I Adreno  : Remote Branch                    : NONE
11-28 17:19:32.527   926  2930 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 17:19:32.536   513  5777 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-28 17:19:32.537   513  5777 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-28 17:19:32.541   513  5777 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-28 17:19:32.541   513  5777 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-28 17:19:32.541   513  2997 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 17:19:32.544  3944  4174 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-28 17:19:32.544  3944  5774 I MicroRecognitionRnrImpl: Detection finished
,11-28 17:19:32.841   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
