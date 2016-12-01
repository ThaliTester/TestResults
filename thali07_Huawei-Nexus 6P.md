#### Test 96008345ac97228_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
12-01 13:08:19.249   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:08:19.727  5567  5567 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-01 13:08:19.732  5567  5567 D AndroidRuntime: CheckJNI is OFF
12-01 13:08:19.757  5567  5567 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-01 13:08:19.790  5567  5567 I Radio-JNI: register_android_hardware_Radio DONE
12-01 13:08:19.805  5567  5567 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
12-01 13:08:19.815   929   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
12-01 13:08:19.833  5567  5567 D AndroidRuntime: Shutting down VM
12-01 13:08:19.838  3923  3934 W SearchService: Abort, client detached.
12-01 13:08:19.845  3923  3923 I HotwordDetector: Closing mic
12-01 13:08:19.846  3923  4131 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@38baa6
12-01 13:08:19.847  3923  4150 E AudioRecord-JNI: Error -4 during AudioRecord native read
12-01 13:08:19.874   929  3544 I ActivityManager: Start proc 5576:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
12-01 13:08:19.922   513  4155 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
12-01 13:08:19.924   513  4155 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
12-01 13:08:19.927   513  4155 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
12-01 13:08:19.927   513  4155 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
12-01 13:08:19.928   513  2944 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
12-01 13:08:19.930  3923  4134 I MicroRecognitionRnrImpl: Stopping hotword detection.
12-01 13:08:19.932  3923  4142 I MicroRecognitionRnrImpl: Detection finished
12-01 13:08:19.975  5576  5576 I CordovaLog: Changing log level to DEBUG(3)
12-01 13:08:19.975  5576  5576 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
12-01 13:08:19.975  5576  5576 D CordovaActivity: CordovaActivity.onCreate()
12-01 13:08:19.979  5576  5576 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
12-01 13:08:19.987   929  5347 D DhcpClient: Received packet: 64:cc:2e:73:42:51 NAK, reason (none)
12-01 13:08:19.999  5576  5576 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
12-01 13:08:20.020  5576  5576 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 8033-8051)
12-01 13:08:20.020  5576  5576 I LibraryLoader: Expected native library version number "",actual native library version number ""
12-01 13:08:20.046  5576  5576 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c499cf6}
12-01 13:08:20.047  5576  5576 I LibraryLoader: Expected native library version number "",actual native library version number ""
12-01 13:08:20.047  5576  5576 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
12-01 13:08:20.050  5576  5576 I BrowserStartupController: Initializing chromium process, singleProcess=true
12-01 13:08:20.051  5576  5576 E SysUtils: ApplicationContext is null in ApplicationStatus
,12-01 13:08:20.090  5576  5576 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,12-01 13:08:20.098  5576  5576 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,12-01 13:08:20.098  5576  5576 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-01 13:08:20.098  5576  5576 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
12-01 13:08:20.098  5576  5576 I Adreno  : Build Date                       : 12/06/15
12-01 13:08:20.098  5576  5576 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
12-01 13:08:20.098  5576  5576 I Adreno  : Local Branch                     : mybranch17112971
12-01 13:08:20.098  5576  5576 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
12-01 13:08:20.098  5576  5576 I Adreno  : Remote Branch                    : NONE
12-01 13:08:20.098  5576  5576 I Adreno  : Reconstruct Branch               : NOTHING
,12-01 13:08:20.144   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dde90d:true
,12-01 13:08:20.174  3783  3783 W Binder_5: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21372]" dev="sockfs" ino=21372 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:20.174  3783  3783 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21372]" dev="sockfs" ino=21372 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:20.188  5576  5576 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,12-01 13:08:20.197  5576  5576 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,12-01 13:08:20.200  5576  5576 D PluginManager: init()
,12-01 13:08:20.203  5576  5576 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,12-01 13:08:20.219  5576  5576 D CordovaActivity: Started the activity.
12-01 13:08:20.219  5576  5576 D CordovaActivity: Resumed the activity.
,12-01 13:08:20.220   405   405 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31628]" dev="sockfs" ino=31628 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:20.220   405   405 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31628]" dev="sockfs" ino=31628 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:20.223  5576  5613 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,12-01 13:08:20.224  3103  3103 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14006]" dev="sockfs" ino=14006 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:20.224  3103  3103 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14006]" dev="sockfs" ino=14006 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:20.228  5576  5600 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,12-01 13:08:20.250   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,12-01 13:08:20.257  5576  5613 I OpenGLRenderer: Initialized EGL, version 1.4
,12-01 13:08:20.330  3363  3363 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32228]" dev="sockfs" ino=32228 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:20.334  3363  3363 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32228]" dev="sockfs" ino=32228 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:20.334  3784  3784 W Binder_9: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32227]" dev="sockfs" ino=32227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:20.335   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +489ms
12-01 13:08:20.338  3612  3612 I Keyboard.Facilitator: onFinishInput()
12-01 13:08:20.334  3784  3784 W Binder_9: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32227]" dev="sockfs" ino=32227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:20.355  5576  5576 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,12-01 13:08:20.374  5576  5576 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5576
,12-01 13:08:20.469  5576  5576 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,12-01 13:08:20.684   929   939 I ActivityManager: Killing 5233:com.android.settings/1000 (adj 15): empty #17
,12-01 13:08:20.694  5576  5615 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -563082960
,12-01 13:08:20.699  5576  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
12-01 13:08:20.699  5576  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
12-01 13:08:20.699  5576  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
12-01 13:08:20.699  5576  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
12-01 13:08:20.699  5576  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,12-01 13:08:20.699  5576  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9859f45 added. We now have 1 listener(s)
,12-01 13:08:20.702  5576  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,12-01 13:08:20.702  5576  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,12-01 13:08:20.703  5576  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,12-01 13:08:20.703  5576  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,12-01 13:08:20.705  5576  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8256fa8 added. We now have 1 listener(s)
12-01 13:08:20.705   929   939 I ActivityManager: Killing 5215:org.codeaurora.ims/1001 (adj 15): empty #18
12-01 13:08:20.705  5576  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 13:08:20.713   929  2897 D WifiService: New client listening to asynchronous messages
,12-01 13:08:20.716  5576  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 13:08:20.716  5576  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,12-01 13:08:20.716  5576  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
12-01 13:08:20.716  5576  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
12-01 13:08:20.716  5576  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
12-01 13:08:20.716  5576  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
12-01 13:08:20.717  5576  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
12-01 13:08:20.718  5576  5615 I io.jxcore.node.LifeCycleMonitor: start: OK
,12-01 13:08:20.833  5576  5576 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,12-01 13:08:20.838  5576  5576 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,12-01 13:08:20.840  5576  5576 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,12-01 13:08:21.172  5576  5585 I art     : Background sticky concurrent mark sweep GC freed 73057(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 1.564ms total 268.873ms
,12-01 13:08:22.549  5576  5585 I art     : Background partial concurrent mark sweep GC freed 57134(6MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 1.491ms total 277.531ms
,12-01 13:08:22.792  5576  5624 W jxcore-log: Initializing JXcore engine
12-01 13:08:22.792  5576  5624 W jxcore-log: JXcore engine is ready
,12-01 13:08:22.814  5624  5624 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12179 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,12-01 13:08:22.814  5624  5624 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14459]" dev="sockfs" ino=14459 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
12-01 13:08:22.814  5624  5624 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
12-01 13:08:22.814  5624  5624 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31600]" dev="sockfs" ino=31600 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,12-01 13:08:22.824  5576  5624 W jxcore-log: Starting JXcore engine
,12-01 13:08:22.874  5576  5624 W jxcore-log: Platform android
12-01 13:08:22.874  5576  5624 W jxcore-log: 
,12-01 13:08:22.874  5576  5624 W jxcore-log: Process ARCH arm
12-01 13:08:22.874  5576  5624 W jxcore-log: 
,12-01 13:08:23.000   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:23.061  5576  5624 I jxcore-log: JXcore Cordova bridge is ready!
12-01 13:08:23.061  5576  5624 I jxcore-log: 
,12-01 13:08:23.061  5576  5624 W jxcore-log: JXcore engine is started
,12-01 13:08:23.070  5576  5615 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,12-01 13:08:23.074  5576  5576 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,12-01 13:08:23.074  5576  5576 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,12-01 13:08:29.935  3923  5625 W CronetSyncConnectionRcs: Upload content type not set.
,12-01 13:08:32.068   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:32.834  5576  5624 I jxcore-log: 2016-12-01 12:08:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
12-01 13:08:32.834  5576  5624 I jxcore-log: 
,12-01 13:08:32.836  5576  5624 I jxcore-log: 2016-12-01 12:08:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
12-01 13:08:32.836  5576  5624 I jxcore-log: 
,12-01 13:08:32.845  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 13:08:32.846  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 13:08:32.852  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 13:08:32.856  5576  5624 I jxcore-log: 2016-12-01 12:08:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
12-01 13:08:32.856  5576  5624 I jxcore-log: 
12-01 13:08:32.857  5576  5624 I jxcore-log: 2016-12-01 12:08:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
12-01 13:08:32.857  5576  5624 I jxcore-log: 
,12-01 13:08:32.889   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:08:33.102  5576  5624 I jxcore-log: 2016-12-01 12:08:33 - DEBUG UnitTest_app: 'Running unit tests'
12-01 13:08:33.102  5576  5624 I jxcore-log: 
12-01 13:08:33.102  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 13:08:33.102  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@161c3ed added. We now have 2 listener(s)
12-01 13:08:33.103  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:08:33.103  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:08:33.103  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:08:33.103  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:08:33.103  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a0d222 added. We now have 2 listener(s)
,12-01 13:08:33.103  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:08:33.104  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 13:08:33.106  5576  5624 D executeNativeTests: Running unit tests
,12-01 13:08:33.141  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 13:08:33.141  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 added. We now have 3 listener(s)
12-01 13:08:33.142  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,12-01 13:08:33.142  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:08:33.142  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:08:33.142  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 13:08:33.142  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 added. We now have 3 listener(s)
,12-01 13:08:33.142  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:08:33.142  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 13:08:33.144  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,12-01 13:08:33.144  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,12-01 13:08:33.144  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,12-01 13:08:33.144  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,12-01 13:08:33.145  5576  5624 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
12-01 13:08:33.145  5576  5624 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
12-01 13:08:33.145  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 13:08:33.145  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 13:08:33.145  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 13:08:33.145  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 13:08:33.145  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:33.146  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:33.146  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:33.146  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:33.146  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:33.146  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:08:33.146  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 removed from the list
12-01 13:08:33.146  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:33.146  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 removed from the list
12-01 13:08:33.146  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:33.146  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.146  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:33.147  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.147  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.147  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.147  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:33.147  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:33.147  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:33.147  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:33.148  5576  5624 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,12-01 13:08:33.148  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:33.149  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:33.149  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:33.149  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:33.149  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:33.149  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:33.149  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:33.149  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:33.149  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:08:33.149  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.149  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.149  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.149  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.149  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.150  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:33.150  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:33.150  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:33.150  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
12-01 13:08:33.152  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
12-01 13:08:33.153  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:33.153  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:33.153  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:33.153  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:33.153  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:33.153  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:33.153  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:33.153  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:33.153  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:33.154  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.154  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.154  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current ,thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.154  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.154  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.154  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:33.154  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:33.154  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:33.154  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:33.155  5576  5624 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
12-01 13:08:33.156  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:08:33.156  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 13:08:33.159  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 13:08:33.159  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 13:08:33.160  5576  5624 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 13:08:33.160  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 13:08:33.160  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 13:08:33.160  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 13:08:33.160  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:08:33.160  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 13:08:33.162  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 13:08:33.162  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 13:08:33.162  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 13:08:33.163  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:08:33.165  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:08:33.166  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.166  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,12-01 13:08:33.167  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 13:08:33.167  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 13:08:33.167  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 13:08:33.168  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
12-01 13:08:33.169  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,12-01 13:08:33.169  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.169  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 13:08:33.169  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 13:08:33.170  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 13:08:33.170  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 13:08:33.170  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.170  5576  5624 D BluetoothAdapter: STATE_ON
,12-01 13:08:33.173  4611  4815 D BtGatt.GattService: registerClient() - UUID=c1c11ee3-6046-436c-83a6-7cc2b9d7e29e
,12-01 13:08:33.173  4611  4676 D BtGatt.GattService: onClientRegistered() - UUID=c1c11ee3-6046-436c-83a6-7cc2b9d7e29e, clientIf=5
,12-01 13:08:33.174  5576  5587 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 13:08:33.175  4611  4835 D BtGatt.GattService: start scan with filters
,12-01 13:08:33.179  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,12-01 13:08:33.179  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.179  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,12-01 13:08:33.180  4611  4679 D BtGatt.ScanManager: handling starting scan
12-01 13:08:33.180  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:33.180  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 13:08:33.180  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 13:08:33.180  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.180  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 13:08:33.180  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 13:08:33.180  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 13:08:33.180  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.180  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.180  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.181  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.181  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.181  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.181  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.181  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:33.181  4611  4679 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:08:33.182  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.182  5576  5624 I io.jxcore.node.ConnectionHelper: start: OK
,12-01 13:08:33.184  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.184  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:08:33.185  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.185  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:33.185  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 13:08:33.189  4611  4676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 13:08:33.190  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:33.190  4611  4679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 13:08:33.195  4611  4676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 13:08:33.195  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:33.196  4611  4679 D BtGatt.ScanManager: Starting BLE batch scan
,12-01 13:08:33.196  4611  4679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 13:08:33.204  4611  4676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,12-01 13:08:33.204  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:33.209  4611  4676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 13:08:33.209  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:33.686  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,12-01 13:08:33.687  5576  5576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:08:33.687  5576  5576 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 13:08:35.100   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:38.186  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:38.187  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:38.187  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 13:08:38.187  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:08:38.187  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 13:08:38.187  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 13:08:38.187  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 13:08:38.187  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 13:08:38.188  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.188  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,12-01 13:08:38.188  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 13:08:38.189  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.189  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.189  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:38.189  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 13:08:38.189  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.190  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:38.191  4611  4815 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,12-01 13:08:38.191  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 13:08:38.192  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:38.193  4611  4679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 13:08:38.193  4611  4627 D BtGatt.GattService: stopScan() - queue size =1
12-01 13:08:38.194  4611  4625 D BtGatt.GattService: unregisterClient() - clientIf=5
,12-01 13:08:38.194  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 13:08:38.194  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.194  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 13:08:38.195  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.195  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.195  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.195  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.196  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 13:08:38.196  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.196  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:38.196  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.196  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 13:08:38.196  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 13:08:38.197  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:08:38.197  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.199  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.199  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:38.199  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.199  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:38.199  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:38.199  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:08:38.199  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:08:38.199  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,12-01 13:08:38.199  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:38.199  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:38.200  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:38.200  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:38.200  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:38.200  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:38.200  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:08:38.200  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 13:08:38.200  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:08:38.200  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 13:08:38.200  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 13:08:38.201  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,12-01 13:08:38.201  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 13:08:38.201  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:08:38.201  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:38.202  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 13:08:38.202  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,12-01 13:08:38.204  4611  4611 D BtGatt.ScanManager: awakened up at time 186235
12-01 13:08:38.206  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:08:38.207  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:38.207  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,12-01 13:08:38.230  4611  4676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,12-01 13:08:38.230  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:38.231  4611  4676 D BtGatt.GattService: current time is 186262467618
12-01 13:08:38.231  4611  4676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -88, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -88, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -87, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,12-01 13:08:38.233  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,12-01 13:08:38.234  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
12-01 13:08:38.235  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
12-01 13:08:38.235  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
12-01 13:08:38.236  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
12-01 13:08:38.236  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 13:08:38.245  4611  4676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 13:08:38.245  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:38.246  4611  4679 D BtGatt.ScanManager: stopping BLe Batch
,12-01 13:08:38.259  4611  4676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,12-01 13:08:38.259  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:38.261  4611  4679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:08:38.268  4611  4676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:08:38.268  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:38.344  3527  5629 I VacuumService: Vacuum at: now=1480594118344 tag=VacuumService
,12-01 13:08:38.370  3527  5632 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,12-01 13:08:38.405  3527  5630 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-01 13:08:38.408  3527  5630 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-01 13:08:38.430  3527  5630 W Uploader:  no longer exists, so no auth token.
,12-01 13:08:38.436  3527  5632 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 13:08:38.703  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 13:08:38.784  3527  5634 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 13:08:38.981  3527  5630 W Uploader:  no longer exists, so no auth token.
,12-01 13:08:38.991  3527  5632 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 13:08:39.069  3527  5634 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 13:08:39.160  3527  5632 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 13:08:39.253  3527  5634 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 13:08:40.251   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:08:41.252   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:08:42.254   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:08:43.227  5576  5624 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,12-01 13:08:43.232  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 13:08:43.236  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 13:08:43.251  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 13:08:43.255   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:08:43.256  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 13:08:43.257  5576  5624 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 13:08:43.257  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:08:43.258  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 13:08:43.258  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 13:08:43.258  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 13:08:43.258  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 13:08:43.264  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:08:43.266  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 13:08:43.267  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 13:08:43.267  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,12-01 13:08:43.272  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:08:43.273  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.273  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,12-01 13:08:43.275  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,12-01 13:08:43.275  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 13:08:43.275  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 13:08:43.279  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.279  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,12-01 13:08:43.279  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 13:08:43.279  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 13:08:43.279  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 13:08:43.280  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.280  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:43.283  4611  4815 D BtGatt.GattService: registerClient() - UUID=0365c079-a5d3-4668-91d0-235a5f2f7e1f
12-01 13:08:43.283  4611  4676 D BtGatt.GattService: onClientRegistered() - UUID=0365c079-a5d3-4668-91d0-235a5f2f7e1f, clientIf=5
,12-01 13:08:43.284  5576  5586 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 13:08:43.284  4611  4627 D BtGatt.GattService: start scan with filters
,12-01 13:08:43.289  4611  4679 D BtGatt.ScanManager: handling starting scan
,12-01 13:08:43.290  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 13:08:43.290  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:43.291  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 13:08:43.291  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.291  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 13:08:43.291  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 13:08:43.291  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,12-01 13:08:43.291  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 13:08:43.291  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 13:08:43.291  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,12-01 13:08:43.292  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.292  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.292  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.293  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 13:08:43.293  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.297  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.297  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:08:43.297  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.297  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.297  5576  5624 I io.jxcore.node.ConnectionHelper: start: OK
12-01 13:08:43.297  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.297  4611  4676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 13:08:43.298  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.298  4611  4679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 13:08:43.304  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:43.304  5576  5624 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,12-01 13:08:43.304  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:43.304  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 13:08:43.304  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:08:43.304  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 13:08:43.304  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:43.304  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.304  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 13:08:43.304  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,12-01 13:08:43.305  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.305  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 13:08:43.305  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.305  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 13:08:43.305  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 13:08:43.305  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.305  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.305  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:43.305  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:08:43.306  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 13:08:43.306  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:43.307  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:43.307  4611  4676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 13:08:43.307  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.308  4611  4679 D BtGatt.ScanManager: Starting BLE batch scan
12-01 13:08:43.308  4611  4679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 13:08:43.308  4611  4627 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 13:08:43.308  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,12-01 13:08:43.309  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:43.309  4611  4625 D BtGatt.GattService: stopScan() - queue size =1
12-01 13:08:43.310  4611  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.311  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.312  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.312  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 13:08:43.312  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 13:08:43.312  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:08:43.312  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.313  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.313  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:43.314  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.314  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.314  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:43.314  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:08:43.314  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:08:43.314  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:43.314  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:43.314  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:43.314  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:43.314  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:43.314  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:43.314  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,12-01 13:08:43.314  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:43.314  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.314  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:08:43.314  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 13:08:43.314  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 13:08:43.314  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.314  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.315  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.315  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:43.315  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.315  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.316  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.316  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.316  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.316  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.317  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.318  4611  4676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,12-01 13:08:43.318  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.318  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.319  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.319  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.319  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:43.319  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:43.319  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:43.319  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:43.320  5576  5624 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
12-01 13:08:43.322  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 13:08:43.322  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 13:08:43.326  4611  4676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 13:08:43.326  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 13:08:43.328  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 13:08:43.328  4611  4679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:08:43.330  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 13:08:43.331  5576  5624 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 13:08:43.331  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:08:43.331  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 13:08:43.331  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 13:08:43.331  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:08:43.331  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 13:08:43.334  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 13:08:43.334  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 13:08:43.334  4611  4676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:08:43.334  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,12-01 13:08:43.334  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.334  4611  4676 E BtGatt.ContextMap: Context not found for ID 5
12-01 13:08:43.334  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:08:43.339  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:08:43.339  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.339  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,12-01 13:08:43.341  4611  4676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 13:08:43.341  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.341  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 13:08:43.341  4611  4679 D BtGatt.ScanManager: stopping BLe Batch
12-01 13:08:43.341  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 13:08:43.341  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 13:08:43.344  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:43.345  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 13:08:43.345  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 13:08:43.345  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 13:08:43.345  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 13:08:43.345  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.345  5576  5624 D BluetoothAdapter: STATE_ON
,12-01 13:08:43.346  4611  4676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 13:08:43.346  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.347  4611  4679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:08:43.349  4611  4815 D BtGatt.GattService: registerClient() - UUID=e221bf5f-bcac-49b1-953e-10d80324b871
12-01 13:08:43.349  4611  4676 D BtGatt.GattService: onClientRegistered() - UUID=e221bf5f-bcac-49b1-953e-10d80324b871, clientIf=5
,12-01 13:08:43.349  5576  5587 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 13:08:43.350  4611  4835 D BtGatt.GattService: start scan with filters
12-01 13:08:43.351  4611  4676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:08:43.351  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.352  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 13:08:43.352  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.352  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 13:08:43.352  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.353  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 13:08:43.353  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 13:08:43.353  4611  4679 D BtGatt.ScanManager: handling starting scan
12-01 13:08:43.353  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.353  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 13:08:43.353  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 13:08:43.353  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.353  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.353  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.353  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.354  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 13:08:43.354  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.356  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.356  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:08:43.356  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.356  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:43.356  5576  5624 I io.jxcore.node.ConnectionHelper: start: OK
12-01 13:08:43.356  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.358  4611  4676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 13:08:43.358  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.359  4611  4679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 13:08:43.359  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.359  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.359  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:43.359  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 13:08:43.364  4611  4676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 13:08:43.364  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:43.364  4611  4679 D BtGatt.ScanManager: Starting BLE batch scan
12-01 13:08:43.364  4611  4679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 13:08:43.373  4611  4676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,12-01 13:08:43.373  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:43.378  4611  4676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 13:08:43.378  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:43.861  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,12-01 13:08:43.861  5576  5576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:08:43.861  5576  5576 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 13:08:44.179   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:44.185   929  2898 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 59
,12-01 13:08:44.256   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:08:45.256   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 13:08:47.207   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:47.213   929  2898 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,12-01 13:08:48.357  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:48.357  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:48.357  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 13:08:48.358  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:08:48.358  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 13:08:48.358  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:48.358  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 13:08:48.358  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 13:08:48.359  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.359  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,12-01 13:08:48.359  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,12-01 13:08:48.359  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.359  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:48.360  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.360  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 13:08:48.360  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.362  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:48.363  4611  4835 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 13:08:48.364  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 13:08:48.366  4611  4679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:08:48.366  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:08:48.368  4611  4627 D BtGatt.GattService: stopScan() - queue size =1
12-01 13:08:48.371  4611  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 13:08:48.372  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,12-01 13:08:48.372  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.373  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 13:08:48.373  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.373  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.374  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.374  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.374  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 13:08:48.374  4611  4611 D BtGatt.ScanManager: awakened up at time 196405
12-01 13:08:48.374  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.375  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.375  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:48.375  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 13:08:48.375  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 13:08:48.379  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:08:48.379  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:48.383  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:48.383  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,12-01 13:08:48.383  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.383  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:48.383  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:48.383  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:48.383  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,12-01 13:08:48.383  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.384  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 13:08:48.384  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 13:08:48.384  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.384  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,12-01 13:08:48.384  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.384  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:48.384  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.384  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.386  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.386  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:08:48.386  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,12-01 13:08:48.395  4611  4676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
12-01 13:08:48.395  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:48.395  4611  4676 D BtGatt.GattService: current time is 196427305703
12-01 13:08:48.396  4611  4676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -90, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -88, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
12-01 13:08:48.396  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
12-01 13:08:48.396  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 13:08:48.397  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
12-01 13:08:48.397  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
12-01 13:08:48.397  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,12-01 13:08:48.397  4611  4676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,12-01 13:08:48.403  4611  4676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 13:08:48.403  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:48.404  4611  4679 D BtGatt.ScanManager: stopping BLe Batch
,12-01 13:08:48.409  4611  4676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 13:08:48.409  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:08:48.410  4611  4679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:08:48.416  4611  4676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:08:48.416  4611  4676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:08:48.886  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 13:08:48.886  5576  5576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:48.886  5576  5576 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 13:08:50.240   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:52.892   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:08:53.258   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:08:53.384  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:53.385  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 13:08:53.385  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 13:08:53.385  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 13:08:53.385  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,12-01 13:08:53.385  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:08:53.385  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.386  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
,12-01 13:08:53.386  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.386  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.386  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.386  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:08:53.389  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.389  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.391  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.391  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.392  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.392  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 13:08:53.392  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.392  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.392  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.393  5576  5624 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,12-01 13:08:53.395  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.395  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 13:08:53.395  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.395  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.396  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.396  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.396  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:08:53.396  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.396  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.396  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.396  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.399  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.399  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.400  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.400  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.400  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.400  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:08:53.400  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.402  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
12-01 13:08:53.403  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.403  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 13:08:53.403  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.403  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.403  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.403  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
,12-01 13:08:53.404  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.404  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.404  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.404  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.404  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.406  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.407  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.407  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.407  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.407  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.407  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.407  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.408  5576  5624 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
12-01 13:08:53.409  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:53.409  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:53.409  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.409  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.409  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.409  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.409  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.409  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.410  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:08:53.410  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.410  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.412  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.413  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.413  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.413  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.413  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.413  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.413  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.414  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
12-01 13:08:53.414  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:53.414  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:53.415  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.415  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.415  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.415  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.415  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:08:53.415  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.415  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.415  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.416  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.418  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.418  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.419  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.419  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 13:08:53.419  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.419  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.419  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.420  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 13:08:53.420  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 13:08:53.420  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 13:08:53.420  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 13:08:53.420  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 13:08:53.420  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 13:08:53.421  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 13:08:53.421  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 13:08:53.421  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 13:08:53.421  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.421  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 13:08:53.421  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.421  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.421  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.422  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.422  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.422  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.422  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.422  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.422  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.424  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.424  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.424  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.424  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.424  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.424  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:08:53.424  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
,12-01 13:08:53.425  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 13:08:53.426  5576  5624 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
12-01 13:08:53.426  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
12-01 13:08:53.430  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 13:08:53.430  5576  5624 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
12-01 13:08:53.431  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
12-01 13:08:53.432  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,12-01 13:08:53.433  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
12-01 13:08:53.433  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,12-01 13:08:53.433  5576  5624 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,12-01 13:08:53.434  5576  5624 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,12-01 13:08:53.434  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 13:08:53.434  5576  5624 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 13:08:53.434  5576  5624 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
12-01 13:08:53.434  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,12-01 13:08:53.434  5576  5624 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 13:08:53.434  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
12-01 13:08:53.438  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
12-01 13:08:53.439  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
12-01 13:08:53.440  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,12-01 13:08:53.440  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
12-01 13:08:53.440  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
12-01 13:08:53.441  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
12-01 13:08:53.441  5576  5624 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 13:08:53.441  5576  5624 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,12-01 13:08:53.441  5576  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
12-01 13:08:53.441  5576  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
12-01 13:08:53.441  5576  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
12-01 13:08:53.441  5576  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
12-01 13:08:53.442  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.442  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:53.442  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 13:08:53.442  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.443  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.443  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
12-01 13:08:53.444  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.444  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.444  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.444  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.444  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.444  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.445  5576  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
12-01 13:08:53.445  5576  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
12-01 13:08:53.445  5576  5639 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
12-01 13:08:53.446  5576  5639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:08:53.444  4835  4835 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33112]" dev="sockfs" ino=33112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:53.444  4835  4835 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33112]" dev="sockfs" ino=33112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:53.448  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.449  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.449  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.449  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.449  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.449  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.449  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.450  5576  5624 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
12-01 13:08:53.451  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.451  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:53.451  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.451  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.451  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.451  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.452  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.452  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
,12-01 13:08:53.452  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.453  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.453  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.455  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.455  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.455  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.455  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.455  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.455  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.455  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.456  5576  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
12-01 13:08:53.456  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.457  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:53.457  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 13:08:53.457  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.457  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.457  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.457  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.457  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.457  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.457  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.457  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.459  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.459  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.459  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.459  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.459  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.459  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.459  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.460  5576  5624 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
12-01 13:08:53.460  5576  5624 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
12-01 13:08:53.460  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 13:08:53.460  5576  5624 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
12-01 13:08:53.460  5576  5624 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
12-01 13:08:53.460  5576  5624 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
12-01 13:08:53.460  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
12-01 13:08:53.460  5576  5624 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
12-01 13:08:53.461  5576  5624 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
12-01 13:08:53.461  5576  5624 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,12-01 13:08:53.461  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
12-01 13:08:53.461  5576  5624 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
12-01 13:08:53.461  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:53.461  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:53.461  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:53.461  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:53.461  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.461  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.461  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.461  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.461  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:53.461  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:53.462  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.463  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.463  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.463  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:53.463  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:53.463  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:53.463  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.463  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.464  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 13:08:53.464  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:53.464  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:53.464  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:53.464  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:53.464  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:08:58.465  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:08:58.465  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.466  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.466  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:58.466  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:58.466  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:08:58.466  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:58.467  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:58.467  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.467  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 13:08:58.467  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:58.467  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.467  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.468  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:08:58.468  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.468  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:58.473  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.473  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.474  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.474  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 13:08:58.474  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:58.474  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.474  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
,12-01 13:08:58.478  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,12-01 13:08:58.479  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:08:58.480  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 13:08:58.484  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,12-01 13:08:58.487  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,12-01 13:08:58.487  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
12-01 13:08:58.487  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
12-01 13:08:58.488  5576  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
12-01 13:08:58.488  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,12-01 13:08:58.488  5576  5576 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
12-01 13:08:58.488  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,12-01 13:08:58.489  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.489  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
12-01 13:08:58.490  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
12-01 13:08:58.490  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
12-01 13:08:58.490  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 13:08:58.490  4627  4627 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33114]" dev="sockfs" ino=33114 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,12-01 13:08:58.491  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,12-01 13:08:58.491  5576  5641 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:08:58.491  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
12-01 13:08:58.491  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:58.491  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.491  5576  5576 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
12-01 13:08:58.491  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,12-01 13:08:58.491  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.491  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 13:08:58.492  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 13:08:58.492  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.493  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.494  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:58.494  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.490  4627  4627 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33114]" dev="sockfs" ino=33114 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 13:08:58.494  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.494  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.494  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:58.494  5576  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
12-01 13:08:58.494  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:58.494  5576  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
12-01 13:08:58.494  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:58.494  5576  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
12-01 13:08:58.494  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:08:58.494  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:58.495  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:08:58.495  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.495  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
12-01 13:08:58.495  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
,12-01 13:08:58.495  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.495  5576  5576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,12-01 13:08:58.495  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
,12-01 13:08:58.495  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:58.495  5576  5576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 13:08:58.495  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.496  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.497  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.498  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.498  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.498  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 13:08:58.498  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:58.498  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.498  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.500  5576  5624 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
12-01 13:08:58.500  5576  5624 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
12-01 13:08:58.500  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 13:08:58.501  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 13:08:58.501  5576  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,12-01 13:08:58.501  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:58.501  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:58.501  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:58.501  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.501  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:58.502  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
,12-01 13:08:58.502  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.502  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.502  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:58.502  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.502  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.504  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:58.505  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.505  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.505  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:58.505  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:58.505  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.505  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
,12-01 13:08:58.512  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:58.512  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:58.512  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:58.512  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.512  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 13:08:58.513  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:58.513  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.513  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.513  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:58.513  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.513  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:58.515  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.515  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.515  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.515  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:58.515  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:58.516  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:08:58.516  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.518  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:08:58.518  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:08:58.518  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:08:58.518  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:08:58.518  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:08:58.519  5576  5624 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5f80a3 not in the list
12-01 13:08:58.519  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.519  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
12-01 13:08:58.519  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:08:58.519  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.519  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.521  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.522  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:08:58.522  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:08:58.522  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:08:58.522  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:08:58.522  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:08:58.522  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed9fa0 not in the list
,12-01 13:08:58.523  5576  5624 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
12-01 13:08:58.524  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 13:08:58.524  5576  5624 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
12-01 13:08:58.524  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,12-01 13:08:58.524  5576  5624 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
12-01 13:08:58.524  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,12-01 13:08:58.527  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,12-01 13:08:58.527  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
12-01 13:08:58.528  5576  5624 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
12-01 13:08:58.528  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
12-01 13:08:58.528  5576  5624 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
12-01 13:08:58.528  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
12-01 13:08:58.528  5576  5624 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
12-01 13:08:58.528  5576  5624 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,12-01 13:08:58.529  5576  5624 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
12-01 13:08:58.529  5576  5624 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
12-01 13:08:58.530  5576  5624 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
12-01 13:08:58.530  5576  5624 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
12-01 13:08:58.530  5576  5624 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
12-01 13:08:58.530  5576  5624 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
12-01 13:08:58.531  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 13:08:58.531  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66c58c9 added. We now have 3 listener(s)
12-01 13:08:58.531  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 13:08:58.533  5576  5624 D BluetoothAdapter: enable(): BT is already enabled..!
,12-01 13:08:58.533   929  3721 D WifiService: setWifiEnabled: true pid=5576, uid=10077
12-01 13:08:58.534   929  3721 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 13:08:58.575  4611  4800 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,12-01 13:08:58.576  4611  4813 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
12-01 13:08:58.576  5576  5639 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
12-01 13:08:58.576  5576  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
12-01 13:08:58.576  5576  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,12-01 13:08:58.995  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 13:08:59.302   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:09:02.329   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 13:09:03.539  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:03.539  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a53bce added. We now have 4 listener(s)
,12-01 13:09:03.539  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 13:09:03.551  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:09:03.552  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a53bce removed from the list
,12-01 13:09:03.552  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:09:03.554  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 13:09:03.554  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e76aef added. We now have 4 listener(s)
,12-01 13:09:03.554  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 13:09:03.559  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:09:03.559  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e76aef removed from the list
,12-01 13:09:03.559  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:09:03.561  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:03.561  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf789fc added. We now have 4 listener(s)
,12-01 13:09:03.561  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:03.564   929   940 D WifiService: setWifiEnabled: false pid=5576, uid=10077
,12-01 13:09:03.564   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 13:09:03.571   929  2896 D WifiStateMachine: WifiStateMachine: Leaving Connected state
12-01 13:09:03.571   929  2896 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
12-01 13:09:03.571   929  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,12-01 13:09:03.572   929  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 13:09:03.576  4611  4671 D BluetoothAdapterState: Current state: ON, message: 23
,12-01 13:09:03.576  4611  4671 D BluetoothAdapterProperties: Setting state to 13
12-01 13:09:03.576  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,12-01 13:09:03.577  4611  4671 D BluetoothAdapterProperties: onBluetoothDisable()
,12-01 13:09:03.578  4611  4671 I BluetoothAdapterState: Entering PendingCommandState
12-01 13:09:03.580  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:09:03.580  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 13:09:03.582  4611  4611 D BluetoothMapService: onReceive
12-01 13:09:03.582  4611  4611 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,12-01 13:09:03.583  4611  4611 D BluetoothMapService: STATE_TURNING_OFF
12-01 13:09:03.583  4611  4611 D BluetoothMapService: MAP Service closeService in
12-01 13:09:03.583  4611  4611 D BluetoothMapMasInstance0: MAP Service shutdown
12-01 13:09:03.583  4611  4611 D ObexServerSockets0: shutdown(block = true)
12-01 13:09:03.584  4611  4611 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 13:09:03.584  4611  4611 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 13:09:03.584  4611  4813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
12-01 13:09:03.584  4611  4838 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
12-01 13:09:03.587  4611  4837 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
12-01 13:09:03.589  4611  4611 I BtOppRfcommListener: stopping Accept Thread
12-01 13:09:03.590  4611  5274 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,12-01 13:09:03.590  4611  5274 I BtOppRfcommListener: BluetoothSocket listen thread finished
,12-01 13:09:03.593   929  5346 D DhcpClient: Clearing IP address
,12-01 13:09:03.593   508   926 D CommandListener: Clearing all IP addresses on wlan0
,12-01 13:09:03.600   508   926 D CommandListener: Setting iface cfg
,12-01 13:09:03.602   929   942 I ActivityManager: Start proc 5646:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
12-01 13:09:03.603  4611  4676 D BluetoothAdapterProperties: Scan Mode:20
12-01 13:09:03.603  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,12-01 13:09:03.607  3527  5403 V NativeCrypto: Read error: ssl=0x7f8ab89a80: I/O error during system call, Connection timed out
,12-01 13:09:03.607   929  5347 D DhcpClient: Receive thread stopped
,12-01 13:09:03.609  3527  5403 V NativeCrypto: SSL shutdown failed: ssl=0x7f8ab89a80: I/O error during system call, Broken pipe
12-01 13:09:03.611   929  3784 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
12-01 13:09:03.611  4611  4611 D HeadsetService: Received stop request...Stopping profile...
12-01 13:09:03.612   929  5342 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
12-01 13:09:03.614  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 13:09:03.614  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 13:09:03.614  3060  3074 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:03.615   929   929 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:03.615   929   929 D BluetoothHeadset: Proxy object disconnected
,12-01 13:09:03.615  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.615  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 13:09:03.615   929  5342 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
12-01 13:09:03.615  5576  5624 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 13:09:03.615  3705  3747 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:03.615  3060  3060 D HeadsetProfile: Bluetooth service disconnected
12-01 13:09:03.616   929  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
12-01 13:09:03.616   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
12-01 13:09:03.616   929   929 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:03.617   929  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,12-01 13:09:03.617  4611  4611 D A2dpService: Received stop request...Stopping profile...
,12-01 13:09:03.618  4611  4830 D A2dpStateMachine: Exit Disconnected: -1
12-01 13:09:03.620  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:09:03.620   929  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
12-01 13:09:03.621   929  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,12-01 13:09:03.622  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:03.622  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 13:09:03.623   590   590 E Parcel  : Reading a NULL string not supported here.
,12-01 13:09:03.623  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.623  5576  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 13:09:03.623   929   929 D RttService: SCAN_AVAILABLE : 1
12-01 13:09:03.624   929  3006 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
12-01 13:09:03.626   929   929 D BluetoothA2dp: Proxy object disconnected
12-01 13:09:03.628  3060  3060 D BluetoothA2dp: Proxy object disconnected
12-01 13:09:03.628  4611  4611 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:03.628   929  2898 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
12-01 13:09:03.628  4611  4611 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:03.628  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.628  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:03.629  4611  4611 D HidService: Received stop request...Stopping profile...
12-01 13:09:03.629  4611  4611 D HidService: Stopping Bluetooth HidService
,12-01 13:09:03.629  3677  3812 W QCNEJ   : |CORE| network lost: 100
12-01 13:09:03.630  3677  3812 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
12-01 13:09:03.631  4611  4611 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,12-01 13:09:03.631  4611  4611 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
12-01 13:09:03.631  4611  4676 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
12-01 13:09:03.631  4611  4800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:03.632  4611  4800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:03.632  4611  4800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:03.632  4611  4676 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
12-01 13:09:03.632  4611  4611 D HealthService: Received stop request...Stopping profile...
,12-01 13:09:03.635  4611  4611 D PanService: Received stop request...Stopping profile...
,12-01 13:09:03.636  4611  4611 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:03.636  4611  4611 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:03.636  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.636  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:03.637  4611  4800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:03.639  4611  4611 D BluetoothMapService: Received stop request...Stopping profile...
,12-01 13:09:03.639  4611  4611 D BluetoothMapService: stop()
12-01 13:09:03.639  4611  4800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:03.639  4611  4800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 13:09:03.639  4611  4800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 13:09:03.639  4611  4800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,12-01 13:09:03.639  4611  4800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 13:09:03.637  4611  4676 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
12-01 13:09:03.639  4611  4611 D BluetoothMapAppObserver: deinitObservers()
12-01 13:09:03.640  4611  4611 D BluetoothMapAppObserver: removeReceiver()
12-01 13:09:03.641  4611  4611 D SapService: Received stop request...Stopping profile...
12-01 13:09:03.641  4611  4611 V SapService: stop()
,12-01 13:09:03.642  4611  4611 V BluetoothAdapterState: isTurningOff()=true
,12-01 13:09:03.642  4611  4611 V BluetoothAdapterState: isTurningOn()=false
,12-01 13:09:03.642  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.642  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:03.642  4611  4611 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
12-01 13:09:03.642  4611  4611 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:03.643  4611  4611 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
12-01 13:09:03.643  4611  4611 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isTurningOn()=false
,12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.643  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:03.643  4611  4611 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
12-01 13:09:03.644  4611  4611 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
12-01 13:09:03.645  4611  4611 D BluetoothMapService: MAP Service closeService in
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:03.645  4611  4611 D BluetoothMapService: cleanup()
12-01 13:09:03.645  4611  4611 D BluetoothMapService: MAP Service closeService in
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:03.645  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:03.646  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
12-01 13:09:03.646  4611  4671 D BluetoothAdapterProperties: Setting state to 15
12-01 13:09:03.646  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
12-01 13:09:03.646   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:03.647  4611  4671 I BluetoothAdapterState: Entering BleOnState
12-01 13:09:03.647  3060  3902 D BluetoothMap: onBluetoothStateChange: up=false
12-01 13:09:03.647  3060  3935 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 13:09:03.647   929  2896 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
12-01 13:09:03.648  3060  3074 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:03.648   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:03.648  3060  3076 D BluetoothPan: onBluetoothStateChange on: false
12-01 13:09:03.649  3060  3902 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 13:09:03.649  4611  4676 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 13:09:03.649  4611  4676 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
12-01 13:09:03.650  3705  3750 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:03.650   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 13:09:03.650   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:03.650  3060  3935 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 13:09:03.652  4611  4671 D BluetoothAdapterState: Current state: BLE ON, message: 20
12-01 13:09:03.654  4611  4671 D BluetoothAdapterProperties: Setting state to 16
,12-01 13:09:03.654  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
12-01 13:09:03.654  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:03.654  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 13:09:03.654  4611  4671 D BluetoothAdapterProperties: onBleDisable
12-01 13:09:03.654  4611  4671 I BluetoothAdapterState: Entering PendingCommandState
12-01 13:09:03.654  4611  4673 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
12-01 13:09:03.656  4611  4676 D BluetoothAdapterProperties: Scan Mode:20
12-01 13:09:03.657  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:09:03.657  4611  4800 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
12-01 13:09:03.657  4611  4800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,12-01 13:09:03.666   929  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,12-01 13:09:03.673   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 13:09:03.683  5646  5646 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,12-01 13:09:03.691   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 13:09:03.691   508   926 D CommandListener: Clearing all IP addresses on wlan0
12-01 13:09:03.692   508   926 D TetherController: Setting IP forward enable = 0
12-01 13:09:03.693   929  2898 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
12-01 13:09:03.693   929  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
12-01 13:09:03.695   929   946 D Tethering: MasterInitialState.processMessage what=3
,12-01 13:09:03.697  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:03.698  5248  5248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9379142 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
12-01 13:09:03.700  3923  3923 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,12-01 13:09:03.703  5018  5040 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,12-01 13:09:03.703  5018  5040 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 13:09:03.703  5018  5040 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
12-01 13:09:03.703  5018  5040 E SarControlService: no key has been found,reset the power
12-01 13:09:03.703  5018  5053 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 13:09:03.704  5018  5053 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 13:09:03.704  5018  5053 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 13:09:03.704  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 13:09:03.705  5043  5043 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 13:09:03.707  5018  5053 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 13:09:03.707  5018  5053 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 13:09:03.707  5018  5053 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 13:09:03.709  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 13:09:03.709  5043  5043 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 13:09:03.711  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ea03000000000000ffffffff]
12-01 13:09:03.711  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 13:09:03.711  5043  5057 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
12-01 13:09:03.712  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 13:09:03.712  5018  5028 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,12-01 13:09:03.713  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 13:09:03.716  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000eb03000000000000ffffffff]
12-01 13:09:03.716  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 13:09:03.716  5043  5057 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
12-01 13:09:03.717  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 13:09:03.717  5018  5029 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 13:09:03.720   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d4c294:true
12-01 13:09:03.721  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 13:09:03.736   508   926 E Netd    : netlink response contains error (No such file or directory)
,12-01 13:09:03.737   508   926 D TetherController: Setting IP forward enable = 0
12-01 13:09:03.738   929  2898 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
12-01 13:09:03.738   929  2896 D DhcpClient: doQuit
12-01 13:09:03.738   929  2896 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
12-01 13:09:03.739   929  5346 D DhcpClient: onQuitting
,12-01 13:09:03.739  5646  5646 D LocalBluetoothProfileManager: Adding local MAP profile
12-01 13:09:03.739  3397  3397 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
12-01 13:09:03.741  5646  5646 D BluetoothMap: Create BluetoothMap proxy object
12-01 13:09:03.746  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:03.746  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 13:09:03.747  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:03.747  5576  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 13:09:03.760  5646  5646 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
12-01 13:09:03.763  3397  3397 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
12-01 13:09:03.765  5646  5646 D DockEventReceiver: finishStartingService: stopping service
12-01 13:09:03.768  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 13:09:03.769  3397  3397 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
12-01 13:09:03.775  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 13:09:03.776  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,12-01 13:09:03.780   929  3544 I ActivityManager: Killing 5373:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,12-01 13:09:03.798  3397  3397 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,12-01 13:09:03.808  3397  3397 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,12-01 13:09:03.810  3790  3790 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,12-01 13:09:03.817  3790  3790 D SystemUpdateService: onCreate
,12-01 13:09:03.820  3790  3790 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,12-01 13:09:03.824  3790  5682 I SystemUpdateService: active receiver: enabled
,12-01 13:09:03.828  3790  3790 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,12-01 13:09:03.833  3790  5369 I iu.UploadsManager: num queued entries: 0
,12-01 13:09:03.833  3790  5369 I iu.UploadsManager: num updated entries: 0
12-01 13:09:03.833  3790  5369 I iu.SyncManager: NEXT; no task
,12-01 13:09:03.837  3790  3790 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
12-01 13:09:03.838  3790  3790 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
12-01 13:09:03.839  3790  5682 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,12-01 13:09:03.841  3790  5682 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,12-01 13:09:03.841  3790  5682 I SystemUpdateService: now status is 0 (complete)
12-01 13:09:03.841  3790  5682 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 13:09:03.842  3790  5682 I SystemUpdateService: file has been verified
12-01 13:09:03.842  3790  5682 I SystemUpdateService: OTA package size = 21989297
,12-01 13:09:03.848  3790  5682 I SystemUpdateService: showing system update notification
,12-01 13:09:03.849   929  3721 I ActivityManager: Start proc 5684:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,12-01 13:09:03.862   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,12-01 13:09:03.863  4611  4676 I bt_hci  : shut_down
,12-01 13:09:03.864  3790  3790 D SystemUpdateService: onDestroy
,12-01 13:09:03.869  4611  4680 I bt_vendor: low_power_mode_cb
,12-01 13:09:03.871  4611  4680 D bt_hwcfg: hw_epilog_process
,12-01 13:09:03.874  4611  4680 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,12-01 13:09:03.874  4611  4680 I bt_vendor: epilog_cb
12-01 13:09:03.874  4611  4680 I bt_hci  : epilog_finished_callback
12-01 13:09:03.876  4611  4676 I bt_hci_h4: hal_close
12-01 13:09:03.876  4611  4676 I bt_userial_vendor: device fd = 54 close
,12-01 13:09:03.883  5684  5684 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,12-01 13:09:03.886  5684  5684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 13:09:03.893  5684  5684 D SprintDMHelper: simOperator: 
12-01 13:09:03.893  5684  5684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 13:09:03.903  4970  5696 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,12-01 13:09:03.917   929  3721 I ActivityManager: Start proc 5697:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,12-01 13:09:03.919   929  2896 D wifi    : In wifi stop Hal
12-01 13:09:03.919  4970  4970 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 13:09:03.919   929  2896 D wifi    : halHandle = 0x7f78382f00, mVM = 0x7f94a0d140, mCls = 0x100a02
,12-01 13:09:03.919   929  3396 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
12-01 13:09:03.919   929  3396 D WifiHAL : Got a signal to exit!!!
,12-01 13:09:03.919   929  3396 I WifiHAL : Exit wifi_event_loop
12-01 13:09:03.920   929  2896 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
12-01 13:09:03.920   929  2896 E WifiHAL : Event processing terminated
12-01 13:09:03.920   929  2896 D wifi    : In wifi cleaned up handler
12-01 13:09:03.920   929  2896 I WifiHAL : Internal cleanup completed
,12-01 13:09:03.920   929  3721 I ActivityManager: Killing 5248:com.google.android.music:main/u0a59 (adj 15): empty #17
12-01 13:09:03.921  4018  4168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 13:09:03.921  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:03.940   929  3396 D wifi    : set interface wlan0 flags (DOWN)
,12-01 13:09:03.942   929  2896 D WifiNative-HAL: HAL event thread stopped successfully
,12-01 13:09:03.964  5697  5697 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,12-01 13:09:03.971   929  3620 I ActivityManager: Killing 3814:com.android.providers.calendar/u0a1 (adj 15): empty #17
,12-01 13:09:03.993  4611  4673 D bt_stack_manager: event_shut_down_stack finished.
,12-01 13:09:03.993  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,12-01 13:09:03.994  4611  4671 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,12-01 13:09:03.994  4611  4611 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 13:09:03.995  4611  4611 D BtGatt.GattService: Received stop request...Stopping profile...
12-01 13:09:03.995  4611  4611 D BtGatt.GattService: stop()
12-01 13:09:03.995  4611  4611 D BtGatt.AdvertiseManager: advertise clients cleared
,12-01 13:09:04.001  4611  4611 V BluetoothAdapterState: isTurningOff()=false
,12-01 13:09:04.001  4611  4611 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:04.001  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:04.002  4611  4611 V BluetoothAdapterState: isBleTurningOff()=true
12-01 13:09:04.002  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
12-01 13:09:04.002  4611  4671 D BluetoothAdapterProperties: Setting state to 10
12-01 13:09:04.002  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
12-01 13:09:04.002  4611  4671 I BluetoothAdapterState: Entering OffState
,12-01 13:09:04.003   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,12-01 13:09:04.010  4611  4611 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,12-01 13:09:04.010  4611  4611 W BluetoothSdpJni: Cleaning up Bluetooth Health object
12-01 13:09:04.010  4611  4611 I BluetoothServiceJni: cleanupNative: return from cleanup
12-01 13:09:04.011  4611  4673 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,12-01 13:09:04.015  4611  4611 I art     : System.exit called, status: 0
,12-01 13:09:04.015  4611  4611 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,12-01 13:09:04.036   929  3103 I ActivityManager: Process com.android.bluetooth (pid 4611) has died
,12-01 13:09:04.146   929   946 D Tethering: InitialState.processMessage what=4
,12-01 13:09:04.150   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,12-01 13:09:08.617   929  3721 D WifiService: setWifiEnabled: true pid=5576, uid=10077
,12-01 13:09:08.618   929  3721 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 13:09:08.627   508   926 D SoftapController: Softap fwReload - Ok
,12-01 13:09:08.632   508   926 D CommandListener: Setting iface cfg
,12-01 13:09:08.632   508   926 D CommandListener: Trying to bring down wlan0
,12-01 13:09:08.634   508   926 D CommandListener: Clearing all IP addresses on wlan0
,12-01 13:09:08.638   929  2896 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 13:09:09.220   929  2896 D wifi    : set interface wlan0 flags (UP)
,12-01 13:09:09.221   929  2896 I WifiHAL : Initializing wifi
12-01 13:09:09.221   929  2896 I WifiHAL : Creating socket
12-01 13:09:09.225   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,12-01 13:09:09.233   929  2896 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,12-01 13:09:09.233   929  2896 D wifi    : Did set static halHandle = 0x7f78382f00
12-01 13:09:09.233   929  2896 D wifi    : halHandle = 0x7f78382f00, mVM = 0x7f94a0d140, mCls = 0x1946
12-01 13:09:09.233   929  2896 D wifi    : array field set
,12-01 13:09:09.234   929  2896 I WifiNative-HAL: interface[0] = wlan0
12-01 13:09:09.237   929  5715 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547477794560
,12-01 13:09:09.237   929  5715 D wifi    : waitForHalEvents called, vm = 0x7f94a0d140, obj = 0x1946, env = 0x7f75fe38c0
,12-01 13:09:09.328  5716  5716 I wpa_supplicant: Successfully initialized wpa_supplicant
,12-01 13:09:09.345   929  2896 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,12-01 13:09:09.352  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:09.410  5716  5716 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 13:09:09.420  5716  5716 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 13:09:09.420  5716  5716 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,12-01 13:09:09.433   929  2896 D WifiConfigStore: Loading config and enabling all networks 
,12-01 13:09:09.437  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:09.437  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 13:09:09.437  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:09.437  5576  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 13:09:09.448   929  2896 D WifiConfigStore: loaded 0 passpoint configs
,12-01 13:09:09.449   929  2896 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
12-01 13:09:09.450   929  2896 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
12-01 13:09:09.450   929  2896 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,12-01 13:09:09.450   929  2896 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
12-01 13:09:09.450   929  2896 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
12-01 13:09:09.451   929  2896 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
12-01 13:09:09.451   929  2896 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
12-01 13:09:09.451   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
12-01 13:09:09.451   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
12-01 13:09:09.451   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,12-01 13:09:09.451   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
12-01 13:09:09.451   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,12-01 13:09:09.453   929  2896 D WifiNative-HAL: Setting external_sim to 1
12-01 13:09:09.453   929  2896 D wifi    : setting dfs flag to true, 0x7f7b52bf40
12-01 13:09:09.453   929  2896 D WifiStateMachine: Setting OUI to DA-A1-19
,12-01 13:09:09.453  4970  4970 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 13:09:09.454   929  2896 D wifi    : setting scan oui 0x7f7b52bf40
12-01 13:09:09.454   929  2896 D WifiHAL : Sending mac address OUI
,12-01 13:09:09.456   929  2896 E native  : do suspend false
,12-01 13:09:09.462   929  2896 D wifi    : android_net_wifi_setLinkLayerStats: 1
12-01 13:09:09.462   929   929 D RttService: SCAN_AVAILABLE : 3
,12-01 13:09:09.463   929  3006 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,12-01 13:09:09.465   508   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,12-01 13:09:09.467   508   926 D CommandListener: Setting iface cfg
,12-01 13:09:09.472   929  2895 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,12-01 13:09:09.472   929  2895 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,12-01 13:09:09.476   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=217507 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,12-01 13:09:09.477   929  2895 D WifiNative-HAL: p2pGetDeviceAddress
12-01 13:09:09.477   929  2895 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,12-01 13:09:10.257   592   592 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
12-01 13:09:10.257   592   592 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 13:09:12.607  5716  5716 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 13:09:12.612  5716  5716 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 13:09:12.617  5716  5716 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 13:09:12.659   929  2896 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,12-01 13:09:12.660   929  2896 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,12-01 13:09:12.660   929  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 13:09:12.671   929  2896 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,12-01 13:09:12.711   929  2896 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,12-01 13:09:12.717  5716  5716 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,12-01 13:09:13.145  5716  5716 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,12-01 13:09:13.625   929  3787 D WifiService: setWifiEnabled: false pid=5576, uid=10077
,12-01 13:09:13.625   929  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
12-01 13:09:13.632   929   929 D RttService: SCAN_AVAILABLE : 1
12-01 13:09:13.633   929  3006 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,12-01 13:09:13.649   929  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 13:09:13.649   508   926 D CommandListener: Clearing all IP addresses on wlan0
,12-01 13:09:13.654   929  2896 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 13:09:13.655  5716  5716 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
12-01 13:09:13.664  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:13.664  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 13:09:13.664  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:13.665  5576  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 13:09:13.672  5716  5716 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,12-01 13:09:13.678  5716  5716 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,12-01 13:09:13.679  5716  5716 I wpa_supplicant: wlan0: WPA: 4-Way Handshake failed - pre-shared key may be incorrect
12-01 13:09:13.680  5716  5716 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10 reason=WRONG_KEY
12-01 13:09:13.681   929  2896 E WifiStateMachine: Error! unhandled message{ when=0 what=147469 obj=id=0 ssid="NG700" auth_failures=1 duration=10 reason=WRONG_KEY target=com.android.internal.util.StateMachine$SmHandler }
,12-01 13:09:13.696  5716  5716 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,12-01 13:09:13.707  5716  5716 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,12-01 13:09:13.811   929  2896 D wifi    : In wifi stop Hal
,12-01 13:09:13.811   929  2896 D wifi    : halHandle = 0x7f78382f00, mVM = 0x7f94a0d140, mCls = 0x1946
12-01 13:09:13.811   929  5715 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
12-01 13:09:13.811   929  5715 D WifiHAL : Got a signal to exit!!!
,12-01 13:09:13.812   929  5715 I WifiHAL : Exit wifi_event_loop
12-01 13:09:13.815   929  2896 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
12-01 13:09:13.815   929  2896 E WifiHAL : Event processing terminated
,12-01 13:09:13.816   929  2896 D wifi    : In wifi cleaned up handler
,12-01 13:09:13.816   929  2896 I WifiHAL : Internal cleanup completed
12-01 13:09:13.819  4018  4168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 13:09:13.819  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:13.820  4970  4970 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 13:09:13.852   929  5715 D wifi    : set interface wlan0 flags (DOWN)
,12-01 13:09:13.853   929  2896 D WifiNative-HAL: HAL event thread stopped successfully
,12-01 13:09:14.059   929   946 D Tethering: InitialState.processMessage what=4
,12-01 13:09:14.065   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,12-01 13:09:18.669   929   946 I ActivityManager: Start proc 5720:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,12-01 13:09:18.774  5720  5720 D AdapterServiceConfig: Adding HeadsetService
,12-01 13:09:18.775  5720  5720 D AdapterServiceConfig: Adding A2dpService
,12-01 13:09:18.775  5720  5720 D AdapterServiceConfig: Adding HidService
12-01 13:09:18.775  5720  5720 D AdapterServiceConfig: Adding HealthService
,12-01 13:09:18.775  5720  5720 D AdapterServiceConfig: Adding PanService
12-01 13:09:18.775  5720  5720 D AdapterServiceConfig: Adding GattService
,12-01 13:09:18.776  5720  5720 D AdapterServiceConfig: Adding BluetoothMapService
12-01 13:09:18.776  5720  5720 D AdapterServiceConfig: Adding SapService
,12-01 13:09:18.790   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d76663:true
12-01 13:09:18.790  5720  5720 D BluetoothAdapterState: make() - Creating AdapterState
,12-01 13:09:18.793  5720  5720 I bt_bluedroid: init
,12-01 13:09:18.793  5720  5732 I BluetoothAdapterState: Entering OffState
,12-01 13:09:18.795  5720  5733 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,12-01 13:09:18.795  5720  5733 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
12-01 13:09:18.796  5720  5733 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
12-01 13:09:18.796  5720  5733 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
12-01 13:09:18.796  5720  5720 I bt_bluedroid: get_profile_interface socket
,12-01 13:09:18.798  5720  5736 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,12-01 13:09:18.798  5720  5720 I bt_bluedroid: get_profile_interface sdp
12-01 13:09:18.800  5720  5736 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 13:09:18.803  5720  5731 I bt_bluedroid: config_hci_snoop_log
,12-01 13:09:18.804   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,12-01 13:09:18.809  5720  5732 D BluetoothAdapterState: Current state: OFF, message: 0
12-01 13:09:18.809  5720  5732 D BluetoothAdapterProperties: Setting state to 14
12-01 13:09:18.809  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
12-01 13:09:18.811  5720  5732 D BluetoothBondStateMachine: make
,12-01 13:09:18.813  5720  5737 I BluetoothBondStateMachine: StableState(): Entering Off State
,12-01 13:09:18.817  5720  5732 I BluetoothAdapterState: Entering PendingCommandState
,12-01 13:09:18.818  5720  5720 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,12-01 13:09:18.820  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:18.821  5720  5720 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 13:09:18.821  5720  5720 D BtGatt.GattService: Received start request. Starting profile...
12-01 13:09:18.821  5720  5720 D BtGatt.GattService: start()
12-01 13:09:18.821  5720  5720 I bt_bluedroid: get_profile_interface gatt
,12-01 13:09:18.822  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:18.823  5720  5720 D BtGatt.AdvertiseManager: advertise manager created
,12-01 13:09:18.828  5720  5720 V BluetoothAdapterState: isTurningOff()=false
,12-01 13:09:18.828  5720  5720 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:18.828  5720  5720 V BluetoothAdapterState: isBleTurningOn()=true
12-01 13:09:18.828  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:18.828  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,12-01 13:09:18.830  5720  5732 I bt_bluedroid: bt_bluedroid
12-01 13:09:18.830  5720  5733 D bt_stack_manager: event_start_up_stack is bringing up the stack.
12-01 13:09:18.830  5720  5733 I bt_hci  : start_up
,12-01 13:09:18.836  5720  5733 I bt_vendor: alloc value 0xf4233871
12-01 13:09:18.836  5720  5733 I bt_vendor: init
12-01 13:09:18.836  5720  5733 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
12-01 13:09:18.836  5720  5733 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,12-01 13:09:18.949  5720  5733 D bt_hci  : start_up starting async portion
,12-01 13:09:18.950  5720  5740 I bt_hci  : event_finish_startup
12-01 13:09:18.950  5720  5740 I bt_hci_h4: hal_open
12-01 13:09:18.950  5720  5740 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,12-01 13:09:18.950  5741  5741 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 13:09:18.954  5720  5740 I bt_userial_vendor: device fd = 54 open
,12-01 13:09:18.970  5720  5740 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 13:09:18.974  5720  5740 D bt_hwcfg: Chipset BCM4358A3
,12-01 13:09:18.974  5720  5740 D bt_hwcfg: Target name = [BCM4358A3]
12-01 13:09:18.975  5720  5740 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,12-01 13:09:19.471  5720  5740 I bt_hwcfg: bt vendor lib: set UART baud 115200
12-01 13:09:19.472  5720  5740 D bt_hwcfg: Settlement delay -- 100 ms
12-01 13:09:19.472  5720  5740 I bt_hwcfg: Setting fw settlement delay to 100 
,12-01 13:09:19.605  5720  5740 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 13:09:19.606  5720  5740 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,12-01 13:09:19.607  5720  5740 I bt_hwcfg: vendor lib fwcfg completed
,12-01 13:09:19.607  5720  5740 I bt_vendor: firmware callback
,12-01 13:09:19.608  5720  5740 I bt_hci  : firmware_config_callback
,12-01 13:09:19.616  5720  5743 I bt_btu  : btu_task pending for preload complete event
12-01 13:09:19.616  5720  5743 I bt_btu_task: Bluetooth chip preload is complete
,12-01 13:09:19.616  5720  5743 I bt_btu  : btu_task received preload complete event
,12-01 13:09:19.623  5720  5743 I         : BTE_InitTraceLevels -- TRC_HCI
12-01 13:09:19.623  5720  5743 I         : BTE_InitTraceLevels -- TRC_L2CAP
,12-01 13:09:19.623  5720  5743 I         : BTE_InitTraceLevels -- TRC_RFCOMM
12-01 13:09:19.623  5720  5743 I         : BTE_InitTraceLevels -- TRC_AVDT
,12-01 13:09:19.623  5720  5743 I         : BTE_InitTraceLevels -- TRC_AVRC
12-01 13:09:19.623  5720  5743 I         : BTE_InitTraceLevels -- TRC_A2D
,12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_BNEP
12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_BTM
,12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_GAP
12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_PAN
,12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_SDP
12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_GATT
12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_SMP
12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_BTAPP
,12-01 13:09:19.624  5720  5743 I         : BTE_InitTraceLevels -- TRC_BTIF
,12-01 13:09:19.719  5720  5743 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41b1549
,12-01 13:09:19.719  5720  5743 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41b1549 
,12-01 13:09:19.756  5720  5736 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,12-01 13:09:19.759  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,12-01 13:09:19.759  5720  5736 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,12-01 13:09:19.762  5720  5736 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 13:09:19.765  5720  5736 D BluetoothAdapterProperties: Scan Mode:20
,12-01 13:09:19.765  5720  5736 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 13:09:19.765  5720  5736 D bt_hci  : do_postload posting postload work item
12-01 13:09:19.766  5720  5740 I bt_hci  : event_postload
12-01 13:09:19.766  5720  5740 I bt_vendor: sco_config_cb
12-01 13:09:19.766  5720  5740 I bt_hci  : sco_config_callback postload finished.
,12-01 13:09:19.769  5720  5736 D bt_bte_conf: Device ID record 1 : primary
,12-01 13:09:19.769  5720  5736 D bt_bte_conf:   vendorId            = 000f
12-01 13:09:19.769  5720  5736 D bt_bte_conf:   vendorIdSource      = 0001
12-01 13:09:19.769  5720  5736 D bt_bte_conf:   product             = 1200
12-01 13:09:19.769  5720  5736 D bt_bte_conf:   version             = 1436
12-01 13:09:19.769  5720  5736 D bt_bte_conf:   clientExecutableURL = 
12-01 13:09:19.769  5720  5736 D bt_bte_conf:   serviceDescription  = 
,12-01 13:09:19.769  5720  5736 D bt_bte_conf:   documentationURL    = 
12-01 13:09:19.770  5720  5736 D bt_bte_conf: bte_load_did_conf no section named DID2.
12-01 13:09:19.770  5720  5733 D bt_stack_manager: event_start_up_stack finished
12-01 13:09:19.770  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:09:19.771  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
12-01 13:09:19.771  5720  5732 D BluetoothAdapterProperties: Setting state to 15
12-01 13:09:19.771  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
12-01 13:09:19.772  5720  5732 I BluetoothAdapterState: Entering BleOnState
,12-01 13:09:19.773  5720  5740 I bt_vendor: low_power_mode_cb
12-01 13:09:19.777  5720  5732 D BluetoothAdapterState: Current state: BLE ON, message: 1
,12-01 13:09:19.777  5720  5732 D BluetoothAdapterProperties: Setting state to 11
12-01 13:09:19.777  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,12-01 13:09:19.781  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:19.782  5720  5720 D HeadsetService: Received start request. Starting profile...
,12-01 13:09:19.784  5720  5720 I BluetoothHeadsetServiceJni: classInitNative: succeeds
12-01 13:09:19.785  5720  5720 D HeadsetStateMachine: make
,12-01 13:09:19.792  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:19.797  5720  5732 I BluetoothAdapterState: Entering PendingCommandState
,12-01 13:09:19.798  5720  5720 D HeadsetStateMachine: max_hf_connections = 1
12-01 13:09:19.798  5720  5720 I bt_bluedroid: get_profile_interface handsfree
,12-01 13:09:19.798  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
12-01 13:09:19.798  5720  5736 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
12-01 13:09:19.801  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:19.803  5720  5720 D A2dpService: Received start request. Starting profile...
12-01 13:09:19.803  5720  5720 I BluetoothAvrcpServiceJni: classInitNative: succeeds
12-01 13:09:19.804  5720  5720 I bt_bluedroid: get_profile_interface avrcp
,12-01 13:09:19.809  5720  5720 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
12-01 13:09:19.810  5720  5720 I BluetoothA2dpServiceJni: classInitNative: succeeds
12-01 13:09:19.810  5720  5720 D A2dpStateMachine: make
,12-01 13:09:19.811  5720  5720 I bt_bluedroid: get_profile_interface a2dp
,12-01 13:09:19.813  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,12-01 13:09:19.814  5720  5750 D A2dpStateMachine: Enter Disconnected: -2
,12-01 13:09:19.815  5720  5720 I BluetoothHidServiceJni: classInitNative: succeeds
,12-01 13:09:19.816  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:19.817  5720  5720 D HidService: Received start request. Starting profile...
,12-01 13:09:19.817  5720  5720 I bt_bluedroid: get_profile_interface hidhost
12-01 13:09:19.818  5720  5736 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf419256d
12-01 13:09:19.818  5720  5720 D HidService: setHidService(): set to: null
12-01 13:09:19.818  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
12-01 13:09:19.818  5720  5720 I BluetoothHealthServiceJni: classInitNative: succeeds
12-01 13:09:19.819  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:19.819  5720  5720 D HealthService: Received start request. Starting profile...
,12-01 13:09:19.821  5720  5720 I bt_bluedroid: get_profile_interface health
12-01 13:09:19.821  5720  5720 I BluetoothPanServiceJni: classInitNative(L105): succeeds
12-01 13:09:19.822  5646  5646 D BluetoothInputDevice: Proxy object connected
12-01 13:09:19.822  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:19.823  5646  5646 D HidProfile: Bluetooth service connected
12-01 13:09:19.824  5720  5720 D PanService: Received start request. Starting profile...
12-01 13:09:19.824  5720  5720 D BluetoothPanServiceJni: initializeNative(L110): pan
12-01 13:09:19.824  5720  5720 I bt_bluedroid: get_profile_interface pan
12-01 13:09:19.824  5646  5646 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 13:09:19.825  5646  5646 D PanProfile: Bluetooth service connected
12-01 13:09:19.825  5720  5736 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
12-01 13:09:19.828  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:19.834  5646  5646 D BluetoothMap: Proxy object connected
,12-01 13:09:19.835  5720  5720 D BluetoothMapService: Received start request. Starting profile...
12-01 13:09:19.835  5720  5720 D BluetoothMapService: start()
12-01 13:09:19.838  5720  5720 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,12-01 13:09:19.838  5646  5646 D MapProfile: Bluetooth service connected
12-01 13:09:19.838  5646  5646 D BluetoothMap: getConnectedDevices()
12-01 13:09:19.839  5720  5720 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
12-01 13:09:19.839  5646  5646 D BluetoothMap: Bluetooth is Not enabled
,12-01 13:09:19.839  5720  5720 D BluetoothMapAppObserver: createReceiver()
,12-01 13:09:19.841  5720  5720 D BluetoothMapAppObserver: initObservers()
12-01 13:09:19.841  5720  5720 D BluetoothMapAppObserver: getEnabledAccountItems()
,12-01 13:09:19.849  5720  5720 V SapService: SapBinder()
12-01 13:09:19.849  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:19.850  5720  5720 D SapService: Received start request. Starting profile...
12-01 13:09:19.850  5720  5720 V SapService: start()
,12-01 13:09:19.851  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOff()=false
,12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:19.857  5720  5747 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:19.857  5720  5720 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:19.858  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:19.858  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:19.858  5720  5720 V BluetoothAdapterState: isTurningOff()=false
,12-01 13:09:19.858  5720  5720 V BluetoothAdapterState: isTurningOn()=true
,12-01 13:09:19.858  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:19.858  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:19.860  5720  5720 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:19.860  5720  5720 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:19.860  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:19.860  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:19.860  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
12-01 13:09:19.860  5720  5732 D BluetoothAdapterProperties: ScanMode =  20
12-01 13:09:19.860  5720  5732 D BluetoothAdapterProperties: State =  11
,12-01 13:09:19.861  5720  5732 D BluetoothAdapterProperties: Setting state to 12
,12-01 13:09:19.861  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
12-01 13:09:19.861   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:19.861  3060  3076 D BluetoothMap: onBluetoothStateChange: up=true
12-01 13:09:19.864  5720  5732 I BluetoothAdapterState: Entering OnState
12-01 13:09:19.864  3060  3060 D BluetoothMap: Proxy object connected
12-01 13:09:19.864  3060  3060 D MapProfile: Bluetooth service connected
12-01 13:09:19.864  3060  3060 D BluetoothMap: getConnectedDevices()
12-01 13:09:19.864  5720  5736 D BluetoothAdapterProperties: Scan Mode:21
12-01 13:09:19.865  5720  5736 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 13:09:19.865  3060  3902 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 13:09:19.865  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
12-01 13:09:19.867  3060  3935 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:19.867  5720  5720 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 13:09:19.867  5720  5720 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
12-01 13:09:19.868  5646  5661 D BluetoothPbap: onBluetoothStateChange: up=true
,12-01 13:09:19.869  5720  5720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:09:19.870   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:19.870  3060  3074 D BluetoothPan: onBluetoothStateChange on: true
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:19.871  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 13:09:19.872  3060  3060 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 13:09:19.872  3060  3902 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 13:09:19.872  3060  3060 D PanProfile: Bluetooth service connected
12-01 13:09:19.872  5720  5720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:09:19.873  5576  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 13:09:19.873  3705  4060 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:19.873  5720  5720 D ObexServerSockets: Succeed to create listening sockets 
12-01 13:09:19.874  5720  5720 D ObexServerSockets0: startAccept()
,12-01 13:09:19.874  5720  5720 D ObexServerSockets0: prepareForNewConnect()
12-01 13:09:19.874  5646  5658 D BluetoothPan: onBluetoothStateChange on: true
12-01 13:09:19.874   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 13:09:19.875   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:19.875  3060  3935 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 13:09:19.876  5720  5720 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
12-01 13:09:19.876  5720  5720 D BluetoothSdpJni: SDP Create record success - handle: 0
12-01 13:09:19.876  5720  5756 D ObexServerSockets0: Accepting socket connection...
12-01 13:09:19.877  3060  3060 D BluetoothInputDevice: Proxy object connected
12-01 13:09:19.877  3060  3060 D HidProfile: Bluetooth service connected
,12-01 13:09:19.877  5646  5661 D BluetoothInputDevice: onBluetoothStateChange: up=true
,12-01 13:09:19.877   929   929 D BluetoothA2dp: Proxy object connected
12-01 13:09:19.878  5646  5658 D BluetoothMap: onBluetoothStateChange: up=true
12-01 13:09:19.878  5720  5757 D ObexServerSockets0: Accepting socket connection...
12-01 13:09:19.880  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,12-01 13:09:19.882  5720  5720 D BluetoothMapService: onReceive
12-01 13:09:19.882  5720  5720 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 13:09:19.882  3060  3060 D BluetoothA2dp: Proxy object connected
,12-01 13:09:19.882  5720  5720 D BluetoothMapService: STATE_ON
,12-01 13:09:19.884  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:09:19.884   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,12-01 13:09:19.885  5646  5646 D LocalBluetoothProfileManager: Adding local A2DP profile
,12-01 13:09:19.888  5720  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 13:09:19.889  5720  5759 D BluetoothSdpJni: sdpCreateSapsRecordNative:
12-01 13:09:19.889  5720  5759 D BluetoothSdpJni: SDP Create record success - handle: 1
,12-01 13:09:19.890  5646  5646 D LocalBluetoothProfileManager: Adding local HEADSET profile
,12-01 13:09:19.896  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 13:09:19.898  5646  5646 D BluetoothA2dp: Proxy object connected
,12-01 13:09:19.904  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 13:09:19.906  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,12-01 13:09:19.910  3060  3060 D BluetoothPbap: Proxy object connected
,12-01 13:09:19.910  3060  3060 D PbapServerProfile: Bluetooth service connected
12-01 13:09:19.910  5646  5646 D BluetoothPbap: Proxy object connected
12-01 13:09:19.910  5720  5720 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 13:09:19.910  5720  5720 D ObexServerSockets0: prepareForNewConnect()
,12-01 13:09:19.910  5646  5646 D PbapServerProfile: Bluetooth service connected
,12-01 13:09:19.917  5720  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 13:09:19.934  5720  5768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 13:09:19.935  5720  5768 I BtOppRfcommListener: Accept thread started.
,12-01 13:09:19.964  3060  3935 D BluetoothHeadset: Proxy object connected
,12-01 13:09:19.964   929   929 D BluetoothHeadset: Proxy object connected
12-01 13:09:19.965   929   929 D BluetoothHeadset: Proxy object connected
12-01 13:09:19.965  3060  3060 D HeadsetProfile: Bluetooth service connected
12-01 13:09:19.965  3705  3750 D BluetoothHeadset: Proxy object connected
12-01 13:09:19.965   929   929 D BluetoothHeadset: Proxy object connected
,12-01 13:09:19.968  3060  3076 D BluetoothHeadset: Proxy object connected
12-01 13:09:19.968  3060  3060 D HeadsetProfile: Bluetooth service connected
,12-01 13:09:19.971   929   946 D BluetoothHeadset: Proxy object connected
,12-01 13:09:19.974  3705  3942 D BluetoothHeadset: Proxy object connected
,12-01 13:09:19.975   929   946 D BluetoothHeadset: Proxy object connected
,12-01 13:09:19.993  5646  5658 D BluetoothHeadset: Proxy object connected
,12-01 13:09:19.994  5646  5646 D HeadsetProfile: Bluetooth service connected
,12-01 13:09:20.259   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:20.339  3612  3779 I Keyboard.Facilitator.LanguageModelFlusher: run()
,12-01 13:09:20.339  3612  3779 I Keyboard.Facilitator: flushDynamicLanguageModels()
,12-01 13:09:20.371  3527  3527 I ConfigService: onCreate
,12-01 13:09:21.260   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:22.261   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:23.262   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:23.562  3790  5771 I EventLogService: Aggregate from 1480592363442 (log), 1480592363442 (data)
,12-01 13:09:23.635  5720  5732 D BluetoothAdapterState: Current state: ON, message: 23
,12-01 13:09:23.635  5720  5732 D BluetoothAdapterProperties: Setting state to 13
,12-01 13:09:23.635  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
12-01 13:09:23.636  5720  5732 D BluetoothAdapterProperties: onBluetoothDisable()
,12-01 13:09:23.637  5720  5732 I BluetoothAdapterState: Entering PendingCommandState
,12-01 13:09:23.638  5720  5720 D BluetoothMapService: onReceive
12-01 13:09:23.638  5720  5720 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 13:09:23.639  5720  5720 D BluetoothMapService: STATE_TURNING_OFF
12-01 13:09:23.639  5720  5720 D BluetoothMapService: MAP Service closeService in
12-01 13:09:23.639  5720  5720 D BluetoothMapMasInstance0: MAP Service shutdown
12-01 13:09:23.639  5720  5720 D ObexServerSockets0: shutdown(block = true)
12-01 13:09:23.639  5720  5720 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 13:09:23.640  5720  5720 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 13:09:23.640  5720  5736 D BluetoothAdapterProperties: Scan Mode:20
,12-01 13:09:23.640  5720  5745 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
12-01 13:09:23.640  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,12-01 13:09:23.641  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 13:09:23.641  5720  5756 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
12-01 13:09:23.642  5720  5757 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
12-01 13:09:23.643  5720  5720 I BtOppRfcommListener: stopping Accept Thread
12-01 13:09:23.644  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:23.644  5576  5576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 13:09:23.644  5720  5768 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,12-01 13:09:23.646  5576  5576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 13:09:23.646  5576  5576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 13:09:23.648  5720  5768 I BtOppRfcommListener: BluetoothSocket listen thread finished
12-01 13:09:23.649  5646  5646 D DockEventReceiver: finishStartingService: stopping service
12-01 13:09:23.650  5720  5720 D HeadsetService: Received stop request...Stopping profile...
12-01 13:09:23.651  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:09:23.652  3060  3902 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:23.652   929   929 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:23.652   929   929 D BluetoothHeadset: Proxy object disconnected
,12-01 13:09:23.653  3705  3747 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:23.653   929   929 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:23.653  5720  5720 D A2dpService: Received stop request...Stopping profile...
12-01 13:09:23.653  5646  5658 D BluetoothHeadset: Proxy object disconnected
12-01 13:09:23.654  5720  5750 D A2dpStateMachine: Exit Disconnected: -1
12-01 13:09:23.654  5646  5646 D HeadsetProfile: Bluetooth service disconnected
,12-01 13:09:23.658   929   929 D BluetoothA2dp: Proxy object disconnected
,12-01 13:09:23.659  5646  5646 D BluetoothA2dp: Proxy object disconnected
,12-01 13:09:23.660  5720  5720 D HidService: Received stop request...Stopping profile...
12-01 13:09:23.660  5720  5720 D HidService: Stopping Bluetooth HidService
,12-01 13:09:23.662  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 13:09:23.667  3060  3060 D HeadsetProfile: Bluetooth service disconnected
12-01 13:09:23.667  5646  5646 D BluetoothInputDevice: Proxy object disconnected
,12-01 13:09:23.667  5646  5646 D HidProfile: Bluetooth service disconnected
12-01 13:09:23.667  5720  5720 D HealthService: Received stop request...Stopping profile...
12-01 13:09:23.667  3060  3060 D BluetoothA2dp: Proxy object disconnected
12-01 13:09:23.667  3060  3060 D BluetoothInputDevice: Proxy object disconnected
12-01 13:09:23.667  3060  3060 D HidProfile: Bluetooth service disconnected
12-01 13:09:23.669  5720  5720 D PanService: Received stop request...Stopping profile...
12-01 13:09:23.670  3060  3060 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 13:09:23.670  3060  3060 D PanProfile: Bluetooth service disconnected
12-01 13:09:23.670  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.670  5720  5720 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:23.670  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:23.671  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:23.671  5646  5646 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 13:09:23.671  5646  5646 D PanProfile: Bluetooth service disconnected
,12-01 13:09:23.672  5720  5720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
12-01 13:09:23.672  5720  5720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
12-01 13:09:23.672  5720  5743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:23.672  5720  5743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:23.672  5720  5743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:23.672  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
12-01 13:09:23.672  5720  5736 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
12-01 13:09:23.672  5720  5720 D BluetoothMapService: Received stop request...Stopping profile...
12-01 13:09:23.673  5720  5720 D BluetoothMapService: stop()
12-01 13:09:23.673  5720  5720 D BluetoothMapAppObserver: deinitObservers()
12-01 13:09:23.673  5720  5720 D BluetoothMapAppObserver: removeReceiver()
12-01 13:09:23.674  3060  3060 D BluetoothMap: Proxy object disconnected
12-01 13:09:23.674  3060  3060 D MapProfile: Bluetooth service disconnected
,12-01 13:09:23.675  5720  5720 D SapService: Received stop request...Stopping profile...
12-01 13:09:23.675  5720  5720 V SapService: stop()
,12-01 13:09:23.675  5646  5646 D BluetoothMap: Proxy object disconnected
12-01 13:09:23.676  5646  5646 D MapProfile: Bluetooth service disconnected
,12-01 13:09:23.677  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.677  5720  5720 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:23.677  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 13:09:23.677  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:23.678  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,12-01 13:09:23.678  5720  5743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,12-01 13:09:23.678  5720  5743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:23.678  5720  5743 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 13:09:23.678  5720  5743 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 13:09:23.678  5720  5743 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 13:09:23.678  5720  5743 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 13:09:23.679  3060  3060 D BluetoothPbap: Proxy object disconnected
12-01 13:09:23.679  3060  3060 D PbapServerProfile: Bluetooth service disconnected
12-01 13:09:23.679  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.679  5720  5720 V BluetoothAdapterState: isTurningOn()=false
,12-01 13:09:23.679  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:23.679  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:23.679  5646  5646 D BluetoothPbap: Proxy object disconnected
12-01 13:09:23.679  5646  5646 D PbapServerProfile: Bluetooth service disconnected
12-01 13:09:23.680  5720  5720 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
12-01 13:09:23.680  5720  5720 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
12-01 13:09:23.680  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.680  5720  5736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 13:09:23.680  5720  5720 V BluetoothAdapterState: isTurningOn()=false
,12-01 13:09:23.680  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:23.680  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:23.680  5720  5720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
12-01 13:09:23.680  5720  5720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
12-01 13:09:23.681  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.681  5720  5720 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:23.681  5720  5736 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
12-01 13:09:23.681  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:23.681  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:23.681  5720  5720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,12-01 13:09:23.681  5720  5720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
12-01 13:09:23.682  5720  5720 D BluetoothMapService: MAP Service closeService in
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:23.682  5720  5720 D BluetoothMapService: cleanup()
12-01 13:09:23.682  5720  5720 D BluetoothMapService: MAP Service closeService in
,12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isTurningOff()=true
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:23.682  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:23.683  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
12-01 13:09:23.683  5720  5732 D BluetoothAdapterProperties: Setting state to 15
12-01 13:09:23.683  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
12-01 13:09:23.683  5720  5732 I BluetoothAdapterState: Entering BleOnState
12-01 13:09:23.683   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 13:09:23.684  3060  3076 D BluetoothMap: onBluetoothStateChange: up=false
12-01 13:09:23.684  5646  5658 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:23.685  5646  5661 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 13:09:23.686  3060  3074 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 13:09:23.686  3060  3935 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:23.687  5646  5658 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 13:09:23.688   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:23.688  3060  3902 D BluetoothPan: onBluetoothStateChange on: false
,12-01 13:09:23.690  3060  3076 D BluetoothPbap: onBluetoothStateChange: up=false
,12-01 13:09:23.691  3705  4060 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:23.691  5646  5661 D BluetoothPan: onBluetoothStateChange on: false
12-01 13:09:23.692   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 13:09:23.692   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 13:09:23.693  3060  3074 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 13:09:23.693  5646  5658 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 13:09:23.694  5646  5661 D BluetoothMap: onBluetoothStateChange: up=false
12-01 13:09:23.695  5720  5732 D BluetoothAdapterState: Current state: BLE ON, message: 20
12-01 13:09:23.695  5720  5732 D BluetoothAdapterProperties: Setting state to 16
,12-01 13:09:23.695  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
12-01 13:09:23.695  5720  5732 D BluetoothAdapterProperties: onBleDisable
12-01 13:09:23.695  5720  5732 I BluetoothAdapterState: Entering PendingCommandState
12-01 13:09:23.696  5720  5733 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
12-01 13:09:23.697  5720  5743 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
12-01 13:09:23.697  5720  5743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 13:09:23.697  5720  5736 D BluetoothAdapterProperties: Scan Mode:20
12-01 13:09:23.698  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 13:09:23.700  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 13:09:23.701  5576  5576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:23.707  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 13:09:23.717  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,12-01 13:09:23.913  5720  5736 I bt_hci  : shut_down
,12-01 13:09:23.919  5720  5740 D bt_hwcfg: hw_epilog_process
,12-01 13:09:23.920  5720  5740 I bt_vendor: low_power_mode_cb
,12-01 13:09:23.923  5720  5740 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,12-01 13:09:23.923  5720  5740 I bt_vendor: epilog_cb
12-01 13:09:23.923  5720  5740 I bt_hci  : epilog_finished_callback
,12-01 13:09:23.929  5720  5736 I bt_hci_h4: hal_close
,12-01 13:09:23.930  5720  5736 I bt_userial_vendor: device fd = 54 close
,12-01 13:09:24.054  5720  5733 D bt_stack_manager: event_shut_down_stack finished.
,12-01 13:09:24.055  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,12-01 13:09:24.060  5720  5732 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,12-01 13:09:24.060  5720  5720 D BtGatt.DebugUtils: handleDebugAction() action=null
,12-01 13:09:24.061  5720  5720 D BtGatt.GattService: Received stop request...Stopping profile...
,12-01 13:09:24.062  5720  5720 D BtGatt.GattService: stop()
,12-01 13:09:24.062  5720  5720 D BtGatt.AdvertiseManager: advertise clients cleared
,12-01 13:09:24.065  5720  5720 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:24.065  5720  5720 V BluetoothAdapterState: isTurningOn()=false
,12-01 13:09:24.066  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 13:09:24.066  5720  5720 V BluetoothAdapterState: isBleTurningOff()=true
,12-01 13:09:24.066  5720  5732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
12-01 13:09:24.067  5720  5732 D BluetoothAdapterProperties: Setting state to 10
12-01 13:09:24.067  5720  5732 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
12-01 13:09:24.068  5720  5732 I BluetoothAdapterState: Entering OffState
,12-01 13:09:24.069   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,12-01 13:09:24.093  5720  5720 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
12-01 13:09:24.093  5720  5720 W BluetoothSdpJni: Cleaning up Bluetooth Health object
12-01 13:09:24.093  5720  5720 I BluetoothServiceJni: cleanupNative: return from cleanup
,12-01 13:09:24.094  5720  5733 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,12-01 13:09:24.102  5720  5720 I art     : System.exit called, status: 0
,12-01 13:09:24.102  5720  5720 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,12-01 13:09:24.130   929  3363 I ActivityManager: Process com.android.bluetooth (pid 5720) has died
,12-01 13:09:24.263   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:25.264   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,12-01 13:09:25.404  3527  3527 I ConfigService: onDestroy
,12-01 13:09:28.635  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:09:28.636  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:09:28.640  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:09:28.641  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf789fc removed from the list
12-01 13:09:28.641  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:09:28.643  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:28.643  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b69c70b added. We now have 4 listener(s)
,12-01 13:09:28.644  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:28.646  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:09:28.647  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b69c70b removed from the list
12-01 13:09:28.647  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:09:28.650  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 13:09:28.651  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43149e8 added. We now have 4 listener(s)
,12-01 13:09:28.651  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 13:09:30.265   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:31.266   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:32.267   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:33.269   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:33.664  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:33.701   929   946 I ActivityManager: Start proc 5779:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,12-01 13:09:33.799  5779  5779 D AdapterServiceConfig: Adding HeadsetService
,12-01 13:09:33.799  5779  5779 D AdapterServiceConfig: Adding A2dpService
12-01 13:09:33.799  5779  5779 D AdapterServiceConfig: Adding HidService
12-01 13:09:33.800  5779  5779 D AdapterServiceConfig: Adding HealthService
12-01 13:09:33.800  5779  5779 D AdapterServiceConfig: Adding PanService
12-01 13:09:33.800  5779  5779 D AdapterServiceConfig: Adding GattService
,12-01 13:09:33.800  5779  5779 D AdapterServiceConfig: Adding BluetoothMapService
,12-01 13:09:33.800  5779  5779 D AdapterServiceConfig: Adding SapService
,12-01 13:09:33.815   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@386be9b:true
12-01 13:09:33.815  5779  5779 D BluetoothAdapterState: make() - Creating AdapterState
,12-01 13:09:33.819  5779  5779 I bt_bluedroid: init
,12-01 13:09:33.819  5779  5791 I BluetoothAdapterState: Entering OffState
,12-01 13:09:33.822  5779  5792 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,12-01 13:09:33.822  5779  5792 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
12-01 13:09:33.822  5779  5792 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
12-01 13:09:33.822  5779  5792 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
12-01 13:09:33.823  5779  5779 I bt_bluedroid: get_profile_interface socket
,12-01 13:09:33.825  5779  5795 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,12-01 13:09:33.825  5779  5779 I bt_bluedroid: get_profile_interface sdp
12-01 13:09:33.826  5779  5795 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 13:09:33.830  5779  5790 I bt_bluedroid: config_hci_snoop_log
,12-01 13:09:33.831   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,12-01 13:09:33.835  5779  5791 D BluetoothAdapterState: Current state: OFF, message: 0
12-01 13:09:33.836  5779  5791 D BluetoothAdapterProperties: Setting state to 14
12-01 13:09:33.836  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
12-01 13:09:33.837  5779  5791 D BluetoothBondStateMachine: make
,12-01 13:09:33.838  5779  5796 I BluetoothBondStateMachine: StableState(): Entering Off State
,12-01 13:09:33.841  5779  5791 I BluetoothAdapterState: Entering PendingCommandState
,12-01 13:09:33.842  5779  5779 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,12-01 13:09:33.845  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:33.845  5779  5779 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 13:09:33.846  5779  5779 D BtGatt.GattService: Received start request. Starting profile...
12-01 13:09:33.846  5779  5779 D BtGatt.GattService: start()
12-01 13:09:33.846  5779  5779 I bt_bluedroid: get_profile_interface gatt
12-01 13:09:33.846  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:33.847  5779  5779 D BtGatt.AdvertiseManager: advertise manager created
,12-01 13:09:33.851  5779  5779 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:33.851  5779  5779 V BluetoothAdapterState: isTurningOn()=false
12-01 13:09:33.851  5779  5779 V BluetoothAdapterState: isBleTurningOn()=true
12-01 13:09:33.851  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:33.852  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
12-01 13:09:33.853  5779  5791 I bt_bluedroid: bt_bluedroid
12-01 13:09:33.853  5779  5792 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,12-01 13:09:33.853  5779  5792 I bt_hci  : start_up
,12-01 13:09:33.858  5779  5792 I bt_vendor: alloc value 0xf4233871
,12-01 13:09:33.858  5779  5792 I bt_vendor: init
12-01 13:09:33.858  5779  5792 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
12-01 13:09:33.859  5779  5792 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,12-01 13:09:33.969  5779  5792 D bt_hci  : start_up starting async portion
12-01 13:09:33.970  5779  5799 I bt_hci  : event_finish_startup
,12-01 13:09:33.970  5779  5799 I bt_hci_h4: hal_open
12-01 13:09:33.970  5779  5799 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,12-01 13:09:33.970  5800  5800 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
12-01 13:09:33.975  5779  5799 I bt_userial_vendor: device fd = 54 open
,12-01 13:09:33.990  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 13:09:33.994  5779  5799 D bt_hwcfg: Chipset BCM4358A3
12-01 13:09:33.994  5779  5799 D bt_hwcfg: Target name = [BCM4358A3]
,12-01 13:09:33.995  5779  5799 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,12-01 13:09:34.270   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:34.491  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 115200
12-01 13:09:34.491  5779  5799 D bt_hwcfg: Settlement delay -- 100 ms
12-01 13:09:34.491  5779  5799 I bt_hwcfg: Setting fw settlement delay to 100 
,12-01 13:09:34.626  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 13:09:34.626  5779  5799 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,12-01 13:09:34.628  5779  5799 I bt_hwcfg: vendor lib fwcfg completed
,12-01 13:09:34.629  5779  5799 I bt_vendor: firmware callback
,12-01 13:09:34.629  5779  5799 I bt_hci  : firmware_config_callback
,12-01 13:09:34.638  5779  5802 I bt_btu  : btu_task pending for preload complete event
,12-01 13:09:34.638  5779  5802 I bt_btu_task: Bluetooth chip preload is complete
12-01 13:09:34.638  5779  5802 I bt_btu  : btu_task received preload complete event
,12-01 13:09:34.643  5779  5802 I         : BTE_InitTraceLevels -- TRC_HCI
12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_L2CAP
,12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_RFCOMM
12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_AVDT
12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_AVRC
12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_A2D
12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_BNEP
,12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTM
12-01 13:09:34.644  5779  5802 I         : BTE_InitTraceLevels -- TRC_GAP
12-01 13:09:34.645  5779  5802 I         : BTE_InitTraceLevels -- TRC_PAN
12-01 13:09:34.645  5779  5802 I         : BTE_InitTraceLevels -- TRC_SDP
12-01 13:09:34.645  5779  5802 I         : BTE_InitTraceLevels -- TRC_GATT
,12-01 13:09:34.645  5779  5802 I         : BTE_InitTraceLevels -- TRC_SMP
12-01 13:09:34.645  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTAPP
12-01 13:09:34.645  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTIF
,12-01 13:09:34.728  5779  5802 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41b1549
,12-01 13:09:34.728  5779  5802 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41b1549 
,12-01 13:09:34.745  5779  5795 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,12-01 13:09:34.746  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,12-01 13:09:34.747  5779  5795 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
12-01 13:09:34.749  5779  5795 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 13:09:34.751  5779  5795 D BluetoothAdapterProperties: Scan Mode:20
,12-01 13:09:34.753  5779  5795 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 13:09:34.753  5779  5795 D bt_hci  : do_postload posting postload work item
12-01 13:09:34.753  5779  5799 I bt_hci  : event_postload
12-01 13:09:34.753  5779  5799 I bt_vendor: sco_config_cb
12-01 13:09:34.753  5779  5799 I bt_hci  : sco_config_callback postload finished.
,12-01 13:09:34.756  5779  5795 D bt_bte_conf: Device ID record 1 : primary
,12-01 13:09:34.756  5779  5795 D bt_bte_conf:   vendorId            = 000f
12-01 13:09:34.756  5779  5795 D bt_bte_conf:   vendorIdSource      = 0001
12-01 13:09:34.757  5779  5795 D bt_bte_conf:   product             = 1200
12-01 13:09:34.757  5779  5795 D bt_bte_conf:   version             = 1436
12-01 13:09:34.757  5779  5795 D bt_bte_conf:   clientExecutableURL = 
12-01 13:09:34.757  5779  5795 D bt_bte_conf:   serviceDescription  = 
12-01 13:09:34.757  5779  5795 D bt_bte_conf:   documentationURL    = 
12-01 13:09:34.757  5779  5795 D bt_bte_conf: bte_load_did_conf no section named DID2.
,12-01 13:09:34.757  5779  5792 D bt_stack_manager: event_start_up_stack finished
12-01 13:09:34.758  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
12-01 13:09:34.759  5779  5791 D BluetoothAdapterProperties: Setting state to 15
12-01 13:09:34.759  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
12-01 13:09:34.760  5779  5791 I BluetoothAdapterState: Entering BleOnState
,12-01 13:09:34.761  5779  5799 I bt_vendor: low_power_mode_cb
,12-01 13:09:34.766  5779  5791 D BluetoothAdapterState: Current state: BLE ON, message: 1
12-01 13:09:34.767  5779  5791 D BluetoothAdapterProperties: Setting state to 11
,12-01 13:09:34.768  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,12-01 13:09:34.777  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:34.779  5779  5779 D HeadsetService: Received start request. Starting profile...
,12-01 13:09:34.782  5779  5779 I BluetoothHeadsetServiceJni: classInitNative: succeeds
12-01 13:09:34.783  5779  5779 D HeadsetStateMachine: make
,12-01 13:09:34.792  5779  5779 D HeadsetStateMachine: max_hf_connections = 1
,12-01 13:09:34.793  5779  5779 I bt_bluedroid: get_profile_interface handsfree
,12-01 13:09:34.793  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
12-01 13:09:34.793  5779  5791 I BluetoothAdapterState: Entering PendingCommandState
12-01 13:09:34.795  5779  5795 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
12-01 13:09:34.797  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:34.798  5779  5779 D A2dpService: Received start request. Starting profile...
12-01 13:09:34.798  5779  5779 I BluetoothAvrcpServiceJni: classInitNative: succeeds
12-01 13:09:34.799  5779  5779 I bt_bluedroid: get_profile_interface avrcp
,12-01 13:09:34.802  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 13:09:34.805  5779  5779 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,12-01 13:09:34.806  5779  5779 I BluetoothA2dpServiceJni: classInitNative: succeeds
12-01 13:09:34.806  5779  5779 D A2dpStateMachine: make
,12-01 13:09:34.808  5779  5779 I bt_bluedroid: get_profile_interface a2dp
,12-01 13:09:34.809  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
12-01 13:09:34.810  5779  5810 D A2dpStateMachine: Enter Disconnected: -2
12-01 13:09:34.810  5779  5779 I BluetoothHidServiceJni: classInitNative: succeeds
,12-01 13:09:34.811  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 13:09:34.812  5779  5779 D HidService: Received start request. Starting profile...
12-01 13:09:34.812  5779  5779 I bt_bluedroid: get_profile_interface hidhost
12-01 13:09:34.812  5779  5779 D HidService: setHidService(): set to: null
12-01 13:09:34.812  5779  5795 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf419256d
12-01 13:09:34.812  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
12-01 13:09:34.812  5779  5779 I BluetoothHealthServiceJni: classInitNative: succeeds
12-01 13:09:34.813  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:34.814  5779  5779 D HealthService: Received start request. Starting profile...
,12-01 13:09:34.815  5779  5779 I bt_bluedroid: get_profile_interface health
,12-01 13:09:34.816  5779  5779 I BluetoothPanServiceJni: classInitNative(L105): succeeds
12-01 13:09:34.817  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:34.817  5779  5779 D PanService: Received start request. Starting profile...
12-01 13:09:34.817  5779  5779 D BluetoothPanServiceJni: initializeNative(L110): pan
,12-01 13:09:34.817  5779  5779 I bt_bluedroid: get_profile_interface pan
12-01 13:09:34.818  5779  5795 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
12-01 13:09:34.821  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:34.822  5779  5779 D BluetoothMapService: Received start request. Starting profile...
12-01 13:09:34.822  5779  5779 D BluetoothMapService: start()
,12-01 13:09:34.824  5779  5779 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
12-01 13:09:34.825  5779  5779 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
12-01 13:09:34.825  5779  5779 D BluetoothMapAppObserver: createReceiver()
12-01 13:09:34.827  5779  5779 D BluetoothMapAppObserver: initObservers()
,12-01 13:09:34.827  5779  5779 D BluetoothMapAppObserver: getEnabledAccountItems()
,12-01 13:09:34.834  5779  5779 V SapService: SapBinder()
,12-01 13:09:34.834  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:34.835  5779  5779 D SapService: Received start request. Starting profile...
12-01 13:09:34.835  5779  5779 V SapService: start()
,12-01 13:09:34.836  5779  5779 V BluetoothAdapterState: isTurningOff()=false
,12-01 13:09:34.837  5779  5779 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:34.837  5779  5808 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
12-01 13:09:34.837  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:34.837  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:34.837  5779  5779 V BluetoothAdapterState: isTurningOff()=false
,12-01 13:09:34.837  5779  5779 V BluetoothAdapterState: isTurningOn()=true
,12-01 13:09:34.837  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:34.838  5779  5779 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isTurningOn()=true
,12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:34.839  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:34.840  5779  5779 V BluetoothAdapterState: isTurningOff()=false
12-01 13:09:34.840  5779  5779 V BluetoothAdapterState: isTurningOn()=true
12-01 13:09:34.840  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
12-01 13:09:34.840  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
12-01 13:09:34.840  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
12-01 13:09:34.840  5779  5791 D BluetoothAdapterProperties: ScanMode =  20
12-01 13:09:34.840  5779  5791 D BluetoothAdapterProperties: State =  11
12-01 13:09:34.842  5779  5795 D BluetoothAdapterProperties: Scan Mode:21
12-01 13:09:34.842  5779  5795 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 13:09:34.842  5779  5791 D BluetoothAdapterProperties: Setting state to 12
12-01 13:09:34.842  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
12-01 13:09:34.843   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 13:09:34.843  3060  3902 D BluetoothMap: onBluetoothStateChange: up=true
12-01 13:09:34.845  5779  5791 I BluetoothAdapterState: Entering OnState
12-01 13:09:34.845  5646  5658 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:34.846  3060  3060 D BluetoothMap: Proxy object connected
12-01 13:09:34.846  3060  3060 D MapProfile: Bluetooth service connected
12-01 13:09:34.846  5646  5661 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 13:09:34.846  3060  3060 D BluetoothMap: getConnectedDevices()
12-01 13:09:34.850  3060  3074 D BluetoothA2dp: onBluetoothStateChange: up=true
,12-01 13:09:34.852  3060  3902 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 13:09:34.852  3060  3060 D BluetoothA2dp: Proxy object connected
12-01 13:09:34.853  5646  5661 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 13:09:34.854  5779  5779 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 13:09:34.854   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:34.854  5779  5779 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
12-01 13:09:34.854  3060  3076 D BluetoothPan: onBluetoothStateChange on: true
12-01 13:09:34.855  5779  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:09:34.856  3060  3074 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 13:09:34.857  5779  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:09:34.857  3705  4060 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 13:09:34.858  5779  5779 D ObexServerSockets: Succeed to create listening sockets 
,12-01 13:09:34.858  5779  5779 D ObexServerSockets0: startAccept()
,12-01 13:09:34.858  5646  5658 D BluetoothPan: onBluetoothStateChange on: true
12-01 13:09:34.858  5779  5779 D ObexServerSockets0: prepareForNewConnect()
12-01 13:09:34.859  5646  5646 D BluetoothA2dp: Proxy object connected
12-01 13:09:34.860  5779  5779 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
12-01 13:09:34.860  5779  5779 D BluetoothSdpJni: SDP Create record success - handle: 0
12-01 13:09:34.860   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 13:09:34.860  5779  5815 D ObexServerSockets0: Accepting socket connection...
12-01 13:09:34.861   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 13:09:34.861   929   929 D BluetoothA2dp: Proxy object connected
12-01 13:09:34.861  3060  3935 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 13:09:34.861  3060  3060 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 13:09:34.861  3060  3060 D PanProfile: Bluetooth service connected
12-01 13:09:34.862  5779  5816 D ObexServerSockets0: Accepting socket connection...
12-01 13:09:34.863  5646  5658 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 13:09:34.863  3060  3060 D BluetoothInputDevice: Proxy object connected
12-01 13:09:34.863  3060  3060 D HidProfile: Bluetooth service connected
12-01 13:09:34.864  5646  5661 D BluetoothMap: onBluetoothStateChange: up=true
12-01 13:09:34.867   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
12-01 13:09:34.869  5646  5646 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 13:09:34.869  5646  5646 D PanProfile: Bluetooth service connected
12-01 13:09:34.869  5646  5646 D BluetoothInputDevice: Proxy object connected
12-01 13:09:34.869  5646  5646 D HidProfile: Bluetooth service connected
12-01 13:09:34.871  5646  5646 D BluetoothMap: Proxy object connected
12-01 13:09:34.871  5646  5646 D MapProfile: Bluetooth service connected
12-01 13:09:34.871  5646  5646 D BluetoothMap: getConnectedDevices()
,12-01 13:09:34.871  5779  5779 D BluetoothMapService: onReceive
,12-01 13:09:34.872  5779  5779 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 13:09:34.872  5779  5779 D BluetoothMapService: STATE_ON
12-01 13:09:34.874  5779  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 13:09:34.875  5779  5819 D BluetoothSdpJni: sdpCreateSapsRecordNative:
12-01 13:09:34.875  5779  5819 D BluetoothSdpJni: SDP Create record success - handle: 1
12-01 13:09:34.877  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 13:09:34.887  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,12-01 13:09:34.887  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 13:09:34.892  3060  3060 D BluetoothPbap: Proxy object connected
,12-01 13:09:34.893  3060  3060 D PbapServerProfile: Bluetooth service connected
,12-01 13:09:34.894  5646  5646 D BluetoothPbap: Proxy object connected
12-01 13:09:34.894  5646  5646 D PbapServerProfile: Bluetooth service connected
,12-01 13:09:34.898  5779  5779 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,12-01 13:09:34.898  5779  5779 D ObexServerSockets0: prepareForNewConnect()
12-01 13:09:34.900  5779  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 13:09:34.914  5779  5827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 13:09:34.919  5779  5827 I BtOppRfcommListener: Accept thread started.
,12-01 13:09:34.944  3060  3902 D BluetoothHeadset: Proxy object connected
12-01 13:09:34.945  3060  3060 D HeadsetProfile: Bluetooth service connected
12-01 13:09:34.945   929   929 D BluetoothHeadset: Proxy object connected
,12-01 13:09:34.945   929   929 D BluetoothHeadset: Proxy object connected
12-01 13:09:34.945  3705  3750 D BluetoothHeadset: Proxy object connected
12-01 13:09:34.945   929   929 D BluetoothHeadset: Proxy object connected
12-01 13:09:34.946  5646  5661 D BluetoothHeadset: Proxy object connected
12-01 13:09:34.946  5646  5661 D BluetoothHeadset: Proxy object connected
,12-01 13:09:34.947  5646  5646 D HeadsetProfile: Bluetooth service connected
,12-01 13:09:34.949  5646  5646 D HeadsetProfile: Bluetooth service connected
,12-01 13:09:34.953  3060  3935 D BluetoothHeadset: Proxy object connected
12-01 13:09:34.954  3060  3060 D HeadsetProfile: Bluetooth service connected
,12-01 13:09:34.955   929   946 D BluetoothHeadset: Proxy object connected
,12-01 13:09:34.958  3705  3942 D BluetoothHeadset: Proxy object connected
,12-01 13:09:34.961   929   946 D BluetoothHeadset: Proxy object connected
,12-01 13:09:35.270   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:38.680  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 13:09:38.687  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 13:09:38.688  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 13:09:38.689  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43149e8 removed from the list
12-01 13:09:38.689  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:09:38.691  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 13:09:38.691  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef15801 added. We now have 4 listener(s)
,12-01 13:09:38.691  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 13:09:38.696   929  3363 D WifiService: setWifiEnabled: false pid=5576, uid=10077
12-01 13:09:38.696   929  3363 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 13:09:43.707  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 13:09:43.709   929  3784 D WifiService: setWifiEnabled: true pid=5576, uid=10077
12-01 13:09:43.709   929  3784 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 13:09:43.717   508   926 D SoftapController: Softap fwReload - Ok
,12-01 13:09:43.723   508   926 D CommandListener: Setting iface cfg
12-01 13:09:43.723   508   926 D CommandListener: Trying to bring down wlan0
12-01 13:09:43.724   508   926 D CommandListener: Clearing all IP addresses on wlan0
12-01 13:09:43.729   929  2896 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 13:09:44.343   929  2896 D wifi    : set interface wlan0 flags (UP)
,12-01 13:09:44.343   929  2896 I WifiHAL : Initializing wifi
12-01 13:09:44.344   929  2896 I WifiHAL : Creating socket
,12-01 13:09:44.349   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,12-01 13:09:44.352   929  2896 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,12-01 13:09:44.352   929  2896 D wifi    : Did set static halHandle = 0x7f78382f00
,12-01 13:09:44.352   929  2896 D wifi    : halHandle = 0x7f78382f00, mVM = 0x7f94a0d140, mCls = 0x1966
,12-01 13:09:44.373   929  2896 D wifi    : array field set
12-01 13:09:44.373   929  2896 I WifiNative-HAL: interface[0] = wlan0
12-01 13:09:44.374   929  5832 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547477794560
,12-01 13:09:44.375   929  5832 D wifi    : waitForHalEvents called, vm = 0x7f94a0d140, obj = 0x1966, env = 0x7f783d86c0
,12-01 13:09:44.377   929  2896 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,12-01 13:09:44.378   929  2896 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,12-01 13:09:44.418  5833  5833 I wpa_supplicant: Successfully initialized wpa_supplicant
,12-01 13:09:44.482  5833  5833 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 13:09:44.504  5833  5833 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 13:09:44.504  5833  5833 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,12-01 13:09:45.272   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:45.387   929  2896 D WifiConfigStore: Loading config and enabling all networks 
,12-01 13:09:45.415   929  2896 D WifiConfigStore: loaded 0 passpoint configs
,12-01 13:09:45.415   929  2896 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
12-01 13:09:45.416   929  2896 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
12-01 13:09:45.416   929  2896 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,12-01 13:09:45.417   929  2896 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
12-01 13:09:45.417   929  2896 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,12-01 13:09:45.417   929  2896 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
12-01 13:09:45.418   929  2896 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
12-01 13:09:45.418   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,12-01 13:09:45.418   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,12-01 13:09:45.418   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
12-01 13:09:45.418   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
12-01 13:09:45.418   929  2896 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,12-01 13:09:45.420   929  2896 D WifiNative-HAL: Setting external_sim to 1
12-01 13:09:45.421   929  2896 D wifi    : setting dfs flag to true, 0x7f7b42baa0
12-01 13:09:45.421   929  2896 D WifiStateMachine: Setting OUI to DA-A1-19
12-01 13:09:45.421   929  2896 D wifi    : setting scan oui 0x7f7b42baa0
,12-01 13:09:45.421   929  2896 D WifiHAL : Sending mac address OUI
12-01 13:09:45.421  4970  4970 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 13:09:45.425   929  2896 E native  : do suspend false
,12-01 13:09:45.441   929  2896 D wifi    : android_net_wifi_setLinkLayerStats: 1
12-01 13:09:45.442   508   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,12-01 13:09:45.443   929   929 D RttService: SCAN_AVAILABLE : 3
12-01 13:09:45.445   929  3006 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
12-01 13:09:45.445   508   926 D CommandListener: Setting iface cfg
,12-01 13:09:45.451   929  2895 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
12-01 13:09:45.451   929  2895 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,12-01 13:09:45.472   929  2895 D WifiNative-HAL: p2pGetDeviceAddress
12-01 13:09:45.473   929  2895 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,12-01 13:09:45.479   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=253511 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=30 mControllerEnergyUsed=114 }
,12-01 13:09:46.273   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:47.275   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:48.276   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:48.593  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
12-01 13:09:48.597  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 13:09:48.604  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 13:09:48.667   929  2896 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,12-01 13:09:48.668   929  2896 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
12-01 13:09:48.668   929  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 13:09:48.684   929  2896 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,12-01 13:09:48.720   929  2896 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 13:09:48.725  5576  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 13:09:48.726  5833  5833 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,12-01 13:09:48.729  5576  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 13:09:48.730  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.730  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef15801 removed from the list
12-01 13:09:48.730  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 13:09:48.735  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
12-01 13:09:48.736  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,12-01 13:09:48.738  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c9cafc Bundle[{}]
12-01 13:09:48.740  5576  5624 I io.jxcore.node.LifeCycleMonitor: start: OK
12-01 13:09:48.740  5576  5624 I io.jxcore.node.LifeCycleMonitor: stop: OK
,12-01 13:09:48.742  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
12-01 13:09:48.743  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
12-01 13:09:48.745  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,12-01 13:09:48.746  5576  5624 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,12-01 13:09:48.752  5576  5624 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,12-01 13:09:48.752  5576  5624 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
12-01 13:09:48.753  5576  5624 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,12-01 13:09:48.754  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.755  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@758f6a6 added. We now have 3 listener(s)
,12-01 13:09:48.756  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,12-01 13:09:48.756  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.756  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.757  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.757  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66bc8e7 added. We now have 4 listener(s)
12-01 13:09:48.757  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.757  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 13:09:48.759  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.759  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc51c94 added. We now have 4 listener(s)
,12-01 13:09:48.760  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.761  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.761  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.761  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.761  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1a733d added. We now have 5 listener(s)
12-01 13:09:48.761  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.761  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:09:48.762  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.762  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:09:48.762  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.762  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.762  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.762  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@758f6a6 removed from the list
12-01 13:09:48.762  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.762  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66bc8e7 removed from the list
12-01 13:09:48.762  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:09:48.763  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.763  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.764  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.764  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.764  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.764  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.764  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.764  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.764  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66bc8e7 not in the list
12-01 13:09:48.764  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.764  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.766  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.766  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.766  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.766  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.766  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.766  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.766  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1a733d removed from the list
12-01 13:09:48.766  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.766  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.766  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.766  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc51c94 removed from the list
12-01 13:09:48.767  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.767  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18dd732 added. We now have 3 listener(s)
12-01 13:09:48.768  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.768  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.768  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.768  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.768  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a20c83 added. We now have 4 listener(s)
12-01 13:09:48.768  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.768  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 13:09:48.769  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.769  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c216e00 added. We now have 4 listener(s)
12-01 13:09:48.771  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.771  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.771  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.771  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.771  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc00639 added. We now have 5 listener(s)
12-01 13:09:48.771  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.771  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:09:48.771  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 13:09:48.771  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 13:09:48.771  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:09:48.771  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 13:09:48.772  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,12-01 13:09:48.775  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 13:09:48.775  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 13:09:48.775  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,12-01 13:09:48.779  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.779  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 13:09:48.779  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 13:09:48.779  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 13:09:48.780  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 13:09:48.783  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.783  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 13:09:48.783  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 13:09:48.783  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,12-01 13:09:48.783  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 13:09:48.783  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.784  5576  5624 D BluetoothAdapter: STATE_ON
,12-01 13:09:48.787  5779  5789 D BtGatt.GattService: registerClient() - UUID=0c41fb36-08d7-4984-b388-634a34ac5683
,12-01 13:09:48.787  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=0c41fb36-08d7-4984-b388-634a34ac5683, clientIf=5
12-01 13:09:48.788  5576  5587 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,12-01 13:09:48.789  5779  5807 D BtGatt.GattService: start scan with filters
,12-01 13:09:48.793  5779  5798 D BtGatt.ScanManager: handling starting scan
12-01 13:09:48.793  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 13:09:48.793  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.793  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 13:09:48.793  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.793  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 13:09:48.794  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 13:09:48.794  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.794  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 13:09:48.794  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 13:09:48.794  5779  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 13:09:48.794  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.794  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.794  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.794  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.795  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 13:09:48.795  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.798  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.798  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:09:48.798  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.798  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.798  5576  5624 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
12-01 13:09:48.799  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.799  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.799  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 13:09:48.799  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.799  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.799  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.799  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,12-01 13:09:48.801  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 13:09:48.801  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.802  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 13:09:48.802  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,12-01 13:09:48.802  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.802  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.802  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:09:48.802  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 13:09:48.802  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.802  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 13:09:48.802  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 13:09:48.803  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.803  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.803  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.803  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 13:09:48.803  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.803  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.804  5779  5807 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 13:09:48.804  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 13:09:48.804  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.805  5779  5818 D BtGatt.GattService: stopScan() - queue size =1
12-01 13:09:48.805  5779  5789 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.806  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 13:09:48.806  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 13:09:48.807  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:09:48.807  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.807  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 13:09:48.807  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.808  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
12-01 13:09:48.808  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 13:09:48.808  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.808  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:09:48.808  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.808  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.808  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:09:48.808  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:09:48.808  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to ,[NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.809  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:09:48.809  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.809  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.812  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:09:48.812  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.812  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:09:48.812  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.812  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.812  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.812  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.812  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.812  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.812  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18dd732 removed from the list
12-01 13:09:48.812  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.812  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a20c83 removed from the list
12-01 13:09:48.812  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:09:48.813  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.813  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.813  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.814  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.814  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.814  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.814  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.814  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.814  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a20c83 not in the list
12-01 13:09:48.814  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.814  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.816  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.816  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.816  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.816  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.816  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.816  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.816  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc00639 removed from the list
12-01 13:09:48.816  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.816  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.817  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.817  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c216e00 removed from the list
12-01 13:09:48.817  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.817  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3051a8a added. We now have 3 listener(s)
12-01 13:09:48.818  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 13:09:48.818  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.818  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.819  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.819  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.819  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.819  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fe88fb added. We now have 4 listener(s)
12-01 13:09:48.819  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.820  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 13:09:48.821  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.821  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23efd18 added. We now have 4 listener(s)
12-01 13:09:48.822  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.823  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.823  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.823  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.823  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7f4371 added. We now have 5 listener(s)
12-01 13:09:48.823  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.823  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:09:48.824  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:09:48.824  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 13:09:48.824  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 13:09:48.824  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:09:48.824  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 13:09:48.825  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 13:09:48.825  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 13:09:48.825  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.827  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 13:09:48.827  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 13:09:48.827  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 13:09:48.827  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 13:09:48.829  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.830  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 13:09:48.830  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 13:09:48.830  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 13:09:48.830  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 13:09:48.831  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:09:48.831  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.832  5779  5795 E BtGatt.ContextMap: Context not found for ID 5
12-01 13:09:48.834  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.834  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 13:09:48.834  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 13:09:48.834  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 13:09:48.834  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 13:09:48.834  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.835  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.837  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 13:09:48.838  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.838  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
12-01 13:09:48.838  5779  5789 D BtGatt.GattService: registerClient() - UUID=dc66963d-f2f5-4ed4-bd38-ee4d49d937de
12-01 13:09:48.839  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=dc66963d-f2f5-4ed4-bd38-ee4d49d937de, clientIf=5
12-01 13:09:48.839  5576  5587 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 13:09:48.839  5779  5818 D BtGatt.GattService: start scan with filters
12-01 13:09:48.841  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 13:09:48.842  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.842  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 13:09:48.842  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.842  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 13:09:48.842  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 13:09:48.842  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.842  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 13:09:48.842  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 13:09:48.842  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.842  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.842  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.842  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.843  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 13:09:48.843  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.843  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 13:09:48.843  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 13:09:48.843  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.847  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.847  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:09:48.847  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.847  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.847  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:09:48.848  5576  5624 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
12-01 13:09:48.848  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.848  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:09:48.848  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.848  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:09:48.848  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.848  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.848  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.848  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.848  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.849  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3051a8a removed from the list
12-01 13:09:48.849  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.849  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:09:48.849  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fe88fb removed from the list
12-01 13:09:48.849  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.849  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:09:48.849  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.849  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.849  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.849  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.849  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,12-01 13:09:48.849  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.849  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.849  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.850  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.850  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.850  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.851  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:09:48.851  5779  5798 D BtGatt.ScanManager: handling starting scan
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.851  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.851  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.851  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.851  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fe88fb not in the list
12-01 13:09:48.851  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.851  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.852  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.852  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 13:09:48.852  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.852  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.852  5779  5818 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 13:09:48.853  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 13:09:48.853  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.854  5779  5790 D BtGatt.GattService: stopScan() - queue size =1
12-01 13:09:48.854  5779  5807 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 13:09:48.854  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 13:09:48.854  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.854  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.855  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 13:09:48.855  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 13:09:48.856  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:09:48.856  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.856  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 13:09:48.856  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.856  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 13:09:48.857  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.857  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:09:48.857  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.857  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.857  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.857  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.857  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.857  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:09:48.857  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7f4371 removed from the list
12-01 13:09:48.857  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.857  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:09:48.857  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.857  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 13:09:48.857  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.857  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23efd18 removed from the list
12-01 13:09:48.857  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.857  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 13:09:48.857  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 13:09:48.857  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.858  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.858  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.858  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:09:48.858  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.858  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.858  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.858  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20670e2 added. We now have 3 listener(s)
12-01 13:09:48.859  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.859  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.859  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.859  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.859  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.859  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.859  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.859  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef1c73 added. We now have 4 listener(s)
12-01 13:09:48.859  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.861  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 13:09:48.861  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.861  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 13:09:48.861  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
12-01 13:09:48.861  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 13:09:48.862  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.862  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6c5730 added. We now have 4 listener(s)
12-01 13:09:48.863  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.863  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.863  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.863  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.863  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed1efa9 added. We now have 5 listener(s)
12-01 13:09:48.863  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.863  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:09:48.863  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 13:09:48.863  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 13:09:48.863  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 13:09:48.863  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 13:09:48.865  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 13:09:48.867  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 13:09:48.867  5576  5624 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 13:09:48.867  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 13:09:48.871  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 13:09:48.871  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.875  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.875  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 13:09:48.876  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 13:09:48.876  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 13:09:48.876  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.876  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 13:09:48.876  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 13:09:48.878  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 13:09:48.882  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.883  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 13:09:48.883  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:09:48.883  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 13:09:48.883  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.883  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 13:09:48.883  5779  5795 E BtGatt.ContextMap: Context not found for ID 5
12-01 13:09:48.883  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 13:09:48.883  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.884  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.886  5779  5818 D BtGatt.GattService: registerClient() - UUID=e1ec9043-70f6-4e0b-87dd-cd4e7c70d31a
12-01 13:09:48.886  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=e1ec9043-70f6-4e0b-87dd-cd4e7c70d31a, clientIf=5
12-01 13:09:48.886  5576  5587 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 13:09:48.887  5779  5790 D BtGatt.GattService: start scan with filters
12-01 13:09:48.888  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 13:09:48.888  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.888  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
,12-01 13:09:48.889  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 13:09:48.889  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.889  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 13:09:48.889  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.890  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 13:09:48.890  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,12-01 13:09:48.890  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.890  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 13:09:48.890  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 13:09:48.890  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.890  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.890  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.890  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.891  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 13:09:48.891  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.893  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.893  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 13:09:48.893  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.893  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.893  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.894  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 13:09:48.894  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.894  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:09:48.896  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 13:09:48.896  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.896  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:09:48.896  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.896  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.896  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.896  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.896  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.896  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20670e2 removed from the list
12-01 13:09:48.896  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.896  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef1c73 removed from the list
12-01 13:09:48.896  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:09:48.896  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.896  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.897  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.897  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
12-01 13:09:48.897  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.897  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
12-01 13:09:48.897  5576  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,12-01 13:09:48.897  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.897  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 13:09:48.897  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.897  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.897  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 13:09:48.898  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.898  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.898  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.898  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.898  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.898  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.898  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef1c73 not in the list
12-01 13:09:48.898  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 13:09:48.899  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 13:09:48.899  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.899  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 13:09:48.899  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.900  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.900  5779  5807 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 13:09:48.900  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 13:09:48.901  5779  5798 D BtGatt.ScanManager: handling starting scan
12-01 13:09:48.901  5576  5624 D BluetoothAdapter: STATE_ON
12-01 13:09:48.902  5779  5789 D BtGatt.GattService: stopScan() - queue size =1
,12-01 13:09:48.903  5779  5807 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.903  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 13:09:48.904  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 13:09:48.904  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 13:09:48.904  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.905  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.905  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:09:48.905  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,12-01 13:09:48.905  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.906  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.906  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.906  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.906  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed1efa9 removed from the list
12-01 13:09:48.906  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:09:48.906  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.906  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.906  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 13:09:48.906  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.906  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6c5730 removed from the list
12-01 13:09:48.906  5576  5576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5576  5576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 13:09:48.906  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 13:09:48.906  5576  5576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.906  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.906  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d613a3a added. We now have 3 listener(s)
12-01 13:09:48.907  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.908  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 13:09:48.908  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.908  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.908  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ffa6eb added. We now have 4 listener(s)
12-01 13:09:48.908  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.908  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.908  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.908  5576  5576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 13:09:48.911  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 13:09:48.911  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.911  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
12-01 13:09:48.911  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 13:09:48.911  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 13:09:48.912  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 13:09:48.912  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a77dc48 added. We now have 4 listener(s)
12-01 13:09:48.913  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 13:09:48.913  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,12-01 13:09:48.914  5576  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 13:09:48.914  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 13:09:48.914  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6eae1 added. We now have 5 listener(s)
12-01 13:09:48.914  5576  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 13:09:48.914  5576  5624 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 13:09:48.914  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.914  5576  5624 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 13:09:48.914  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 13:09:48.914  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.914  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.914  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d613a3a removed from the list
12-01 13:09:48.914  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.914  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ffa6eb removed from the list
12-01 13:09:48.914  5576  5624 D io.jxcore.node.ConnectivityMonitor: stop
12-01 13:09:48.914  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.914  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.915  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.915  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.916  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.916  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.916  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 13:09:48.916  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.916  5576  5624 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ffa6eb not in the list
12-01 13:09:48.916  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.916  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.917  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.917  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.917  5576  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
12-01 13:09:48.917  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 13:09:48.917  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 13:09:48.917  5576  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 13:09:48.917  5576  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6eae1 removed from the list
12-01 13:09:48.917  5576  5624 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 13:09:48.917  5576  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 13:09:48.917  5576  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 13:09:48.917  5576  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a77dc48 removed from the list
12-01 13:09:48.918  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
12-01 13:09:48.918  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
12-01 13:09:48.918  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
12-01 13:09:48.918  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:09:48.918  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
12-01 13:09:48.919  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 13:09:48.921  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 13:09:48.922  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:09:48.926  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 13:09:48.926  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:09:48.928  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:09:48.932  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 13:09:48.932  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.932  5779  5795 E BtGatt.ContextMap: Context not found for ID 5
,12-01 13:09:48.938  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 13:09:48.938  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.938  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
,12-01 13:09:48.943  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 13:09:48.943  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 13:09:48.943  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 13:09:48.947  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 13:09:48.947  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 13:09:49.147  5833  5833 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,12-01 13:09:49.176  5833  5833 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,12-01 13:09:49.176  5833  5833 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,12-01 13:09:49.185   929  2896 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 13:09:49.186   929  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
12-01 13:09:49.186   929  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,12-01 13:09:49.201   929  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 13:09:49.212   508   926 D CommandListener: Setting iface cfg
,12-01 13:09:49.216   929  2896 D WifiStateMachine: Start Dhcp Watchdog 2
,12-01 13:09:49.227   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
12-01 13:09:49.227   929  5838 D DhcpClient: Receive thread started
12-01 13:09:49.227   929  2896 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
12-01 13:09:49.227   929  2898 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,12-01 13:09:49.277   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:09:49.310  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 13:09:49.317   929  2896 E native  : do suspend false
,12-01 13:09:49.339   929  5837 D DhcpClient: Broadcasting DHCPDISCOVER
,12-01 13:09:49.352   929  5838 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172583, domain null
,12-01 13:09:49.353   929  5837 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172583 seconds
12-01 13:09:49.356   929  5837 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,12-01 13:09:49.359  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 13:09:49.393   929  5838 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,12-01 13:09:49.394   929  5837 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
12-01 13:09:49.397   508   926 D CommandListener: Setting iface cfg
,12-01 13:09:49.403   929  2896 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,12-01 13:09:49.407  5576  5576 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 13:09:49.414   929  5837 D DhcpClient: Scheduling renewal in 86399s
,12-01 13:09:49.423   929  2896 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,12-01 13:09:49.424   929  2896 D WifiConfigStore: No blacklist allowed without epno enabled
,12-01 13:09:49.425   929  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,12-01 13:09:49.427   929  2898 D ConnectivityService: Adding iface wlan0 to network 101
12-01 13:09:49.437   929  2896 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,12-01 13:09:49.479   929  2898 E ConnectivityService: Unexpected mtu value: 0, wlan0
12-01 13:09:49.479   929  2898 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,12-01 13:09:49.481   929  2898 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,12-01 13:09:49.482   929  2898 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
12-01 13:09:49.484   929  2898 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,12-01 13:09:49.490   929  2898 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:09:49.495   929  2898 D ConnectivityService: scheduleUnvalidatedPrompt 101
,12-01 13:09:49.496   929  2898 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
12-01 13:09:49.496   929  2898 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
12-01 13:09:49.496   929  2898 D ConnectivityService:    accepting network in place of null
12-01 13:09:49.496   929  2896 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
12-01 13:09:49.496   929  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 13:09:49.496   929  2898 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 13:09:49.518   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 13:09:49.540   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 13:09:49.544   929  2898 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,12-01 13:09:49.544   929  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
12-01 13:09:49.544  3677  3812 W QCNEJ   : |CORE| network available: 101
12-01 13:09:49.545   929  2898 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
12-01 13:09:49.546   929   946 D Tethering: MasterInitialState.processMessage what=3
12-01 13:09:49.549  3677  3812 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
12-01 13:09:49.550  3677  3812 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
12-01 13:09:49.550  3677  3812 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,12-01 13:09:49.558  5018  5040 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
12-01 13:09:49.559  5018  5040 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 13:09:49.559  5018  5040 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
12-01 13:09:49.559  5018  5040 E SarControlService: no key has been found,reset the power
,12-01 13:09:49.559  5018  5053 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 13:09:49.559  5018  5053 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 13:09:49.559  5018  5053 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 13:09:49.560  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 13:09:49.560  5043  5043 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,12-01 13:09:49.563  5018  5053 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 13:09:49.563  5018  5053 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 13:09:49.563  5018  5053 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,12-01 13:09:49.564  3923  3923 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
12-01 13:09:49.565  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 13:09:49.565  5043  5043 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 13:09:49.567  3790  3790 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,12-01 13:09:49.569  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ec03000000000000ffffffff]
12-01 13:09:49.569  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 13:09:49.569  5043  5057 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,12-01 13:09:49.572  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ed03000000000000ffffffff]
12-01 13:09:49.572  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 13:09:49.572  5043  5057 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,12-01 13:09:49.573  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 13:09:49.573  5018  5028 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 13:09:49.574  3790  3790 D SystemUpdateService: onCreate
12-01 13:09:49.576  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,12-01 13:09:49.576  5018  5029 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,12-01 13:09:49.579  3790  3790 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,12-01 13:09:49.591  3790  3790 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,12-01 13:09:49.598  3790  5369 I iu.UploadsManager: num queued entries: 0
12-01 13:09:49.598  3790  5369 I iu.UploadsManager: num updated entries: 0
,12-01 13:09:49.599  3790  5848 I SystemUpdateService: active receiver: enabled
,12-01 13:09:49.603  3790  3790 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 13:09:49.604  3790  3790 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 13:09:49.607  5684  5684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 13:09:49.611  5684  5684 D SprintDMHelper: simOperator: 
12-01 13:09:49.611  5684  5684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 13:09:49.624  3790  5369 I iu.SyncManager: NEXT; no task
,12-01 13:09:49.636  3790  5848 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,12-01 13:09:49.650  3790  5848 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,12-01 13:09:49.650  3790  5848 I SystemUpdateService: now status is 0 (complete)
12-01 13:09:49.650  3790  5848 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 13:09:49.650  3790  5848 I SystemUpdateService: file has been verified
12-01 13:09:49.650  3790  5848 I SystemUpdateService: OTA package size = 21989297
,12-01 13:09:49.657  3790  5848 I SystemUpdateService: showing system update notification
,12-01 13:09:49.665   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
12-01 13:09:49.666   929  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257697, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 13:09:49.667  3790  3790 D SystemUpdateService: onDestroy
,12-01 13:09:49.845   929  5835 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:81a::200e
,12-01 13:09:49.878  4970  5853 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,12-01 13:09:49.910   929  5835 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Dec 2016 12:09:49 GMT], X-Android-Received-Millis=[1480594189908], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480594189876]}
,12-01 13:09:49.912   929  2898 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,12-01 13:09:49.913   929  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,12-01 13:09:49.914   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:09:49.916   929  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,12-01 13:09:50.278   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,12-01 13:09:50.544   929  2898 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,12-01 13:09:51.074  5576  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 13:09:51.074  5576  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:09:51.864  5576  5860 W !!      : call onHalfStreamCopied
,12-01 13:09:51.864  5576  5860 I testCopyDataAndClose: closing input stream
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 13:09:52.643  5576  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,12-01 13:09:57.251  5576  5861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:09:57.251  5576  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:09:57.501   929  2898 D ConnectivityService: handlePromptUnvalidated 101
,12-01 13:09:59.251  5576  5624 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
12-01 13:09:59.251  5576  5624 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:09:59.251  5576  5624 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,12-01 13:09:59.264  5576  5861 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,12-01 13:09:59.265  5576  5861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:09:59.265  5576  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
,12-01 13:09:59.445  5576  5862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 13:09:59.445  5576  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:10:00.469   929  2896 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 13:10:01.062  5576  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,12-01 13:10:05.280   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:05.420  5576  5863 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:10:05.420  5576  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:10:05.420  5576  5863 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:10:05.420  5576  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
12-01 13:10:05.421  5576  5863 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 13:10:05.422  5576  5863 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:10:05.422  5576  5863 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
12-01 13:10:05.424  5576  5624 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,12-01 13:10:05.427  5576  5864 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:10:05.427  5576  5864 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 13:10:05.428  5576  5864 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
12-01 13:10:05.428  5576  5864 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:10:05.428  5576  5864 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
12-01 13:10:05.428  5576  5864 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,12-01 13:10:05.428  5576  5864 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
12-01 13:10:05.428  5576  5864 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,12-01 13:10:05.433  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
12-01 13:10:05.433  5576  5624 I jxcore-log: 
12-01 13:10:05.434  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'Number of passed tests:  82'
12-01 13:10:05.434  5576  5624 I jxcore-log: 
12-01 13:10:05.434  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'Number of failed tests:  0'
12-01 13:10:05.434  5576  5624 I jxcore-log: 
,12-01 13:10:05.434  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
12-01 13:10:05.434  5576  5624 I jxcore-log: 
12-01 13:10:05.434  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'Total duration:  92290'
12-01 13:10:05.434  5576  5624 I jxcore-log: 
,12-01 13:10:05.437  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'Unit Test app is loaded'
12-01 13:10:05.437  5576  5624 I jxcore-log: 
,12-01 13:10:05.443  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 13:10:05.443  5576  5624 I jxcore-log: 
,12-01 13:10:05.444  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 13:10:05.444  5576  5624 I jxcore-log: 
12-01 13:10:05.445  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
12-01 13:10:05.445  5576  5624 I jxcore-log: 
12-01 13:10:05.445  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
12-01 13:10:05.445  5576  5624 I jxcore-log: 
12-01 13:10:05.446  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.446  5576  5624 I jxcore-log: 
12-01 13:10:05.446  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 13:10:05.446  5576  5624 I jxcore-log: 
12-01 13:10:05.446  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.446  5576  5624 I jxcore-log: 
12-01 13:10:05.447  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 13:10:05.447  5576  5624 I jxcore-log: 
,12-01 13:10:05.447  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 13:10:05.447  5576  5624 I jxcore-log: 
12-01 13:10:05.447  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
12-01 13:10:05.447  5576  5624 I jxcore-log: 
12-01 13:10:05.448  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
12-01 13:10:05.448  5576  5624 I jxcore-log: 
12-01 13:10:05.448  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.448  5576  5624 I jxcore-log: 
,12-01 13:10:05.448  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 13:10:05.448  5576  5624 I jxcore-log: 
12-01 13:10:05.448  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.448  5576  5624 I jxcore-log: 
12-01 13:10:05.448  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 13:10:05.448  5576  5624 I jxcore-log: 
12-01 13:10:05.449  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.449  5576  5624 I jxcore-log: 
12-01 13:10:05.449  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 13:10:05.449  5576  5624 I jxcore-log: 
12-01 13:10:05.449  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 13:10:05.449  5576  5624 I jxcore-log: 
12-01 13:10:05.449  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 13:10:05.449  5576  5624 I jxcore-log: 
12-01 13:10:05.450  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 13:10:05.450  5576  5624 I jxcore-log: 
12-01 13:10:05.450  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 13:10:05.450  5576  5624 I jxcore-log: 
12-01 13:10:05.450  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
12-01 13:10:05.450  5576  5624 I jxcore-log: 
,12-01 13:10:05.450  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 13:10:05.450  5576  5624 I jxcore-log: 
12-01 13:10:05.451  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
12-01 13:10:05.451  5576  5624 I jxcore-log: 
,12-01 13:10:05.452  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
12-01 13:10:05.452  5576  5624 I jxcore-log: 
12-01 13:10:05.452  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 13:10:05.452  5576  5624 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
12-01 13:10:05.453  5576  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 13:10:05.453  5576  5624 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,12-01 13:10:05.453  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 13:10:05.453  5576  5624 I jxcore-log: 
12-01 13:10:05.453  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.453  5576  5624 I jxcore-log: 
12-01 13:10:05.453  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 13:10:05.453  5576  5624 I jxcore-log: 
12-01 13:10:05.454  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.454  5576  5624 I jxcore-log: 
,12-01 13:10:05.454  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 13:10:05.454  5576  5624 I jxcore-log: 
12-01 13:10:05.454  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 13:10:05.454  5576  5624 I jxcore-log: 
,12-01 13:10:05.459  5576  5576 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
12-01 13:10:05.459  5576  5576 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,12-01 13:10:05.459  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
12-01 13:10:05.459  5576  5624 I jxcore-log: 
12-01 13:10:05.459  5576  5624 I jxcore-log: 2016-12-01 12:10:05 - WARN testUtils: 'myNameCallback not set!'
12-01 13:10:05.459  5576  5624 I jxcore-log: 
,12-01 13:10:06.281   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:07.282   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:07.490  5576  5624 I jxcore-log: 2016-12-01 12:10:07 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
12-01 13:10:07.490  5576  5624 I jxcore-log: 
,12-01 13:10:07.492  5576  5624 I jxcore-log: 2016-12-01 12:10:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
12-01 13:10:07.492  5576  5624 I jxcore-log: 
,12-01 13:10:07.848  5576  5624 I jxcore-log: 2016-12-01 12:10:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
12-01 13:10:07.848  5576  5624 I jxcore-log: 
,12-01 13:10:07.863  5576  5624 I jxcore-log: 2016-12-01 12:10:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
12-01 13:10:07.863  5576  5624 I jxcore-log: 
,12-01 13:10:08.283   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:09.002  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
12-01 13:10:09.002  5576  5624 I jxcore-log: 
,12-01 13:10:09.191  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
12-01 13:10:09.191  5576  5624 I jxcore-log: 
,12-01 13:10:09.196  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
12-01 13:10:09.196  5576  5624 I jxcore-log: 
,12-01 13:10:09.201  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
12-01 13:10:09.201  5576  5624 I jxcore-log: 
,12-01 13:10:09.284   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:09.685  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
12-01 13:10:09.685  5576  5624 I jxcore-log: 
,12-01 13:10:09.729  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
12-01 13:10:09.729  5576  5624 I jxcore-log: 
,12-01 13:10:09.743  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
12-01 13:10:09.743  5576  5624 I jxcore-log: 
,12-01 13:10:09.772  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
12-01 13:10:09.772  5576  5624 I jxcore-log: 
,12-01 13:10:09.776  5576  5624 I jxcore-log: 2016-12-01 12:10:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
12-01 13:10:09.776  5576  5624 I jxcore-log: 
,12-01 13:10:10.035  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
12-01 13:10:10.035  5576  5624 I jxcore-log: 
,12-01 13:10:10.284   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,12-01 13:10:10.308  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
12-01 13:10:10.308  5576  5624 I jxcore-log: 
,12-01 13:10:10.529  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
12-01 13:10:10.529  5576  5624 I jxcore-log: 
,12-01 13:10:10.537  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
12-01 13:10:10.537  5576  5624 I jxcore-log: 
,12-01 13:10:10.541  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
12-01 13:10:10.541  5576  5624 I jxcore-log: 
,12-01 13:10:10.547  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
12-01 13:10:10.547  5576  5624 I jxcore-log: 
,12-01 13:10:10.552  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
12-01 13:10:10.552  5576  5624 I jxcore-log: 
,12-01 13:10:10.582  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
12-01 13:10:10.582  5576  5624 I jxcore-log: 
,12-01 13:10:10.619  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
12-01 13:10:10.619  5576  5624 I jxcore-log: 
,12-01 13:10:10.627  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
12-01 13:10:10.627  5576  5624 I jxcore-log: 
,12-01 13:10:10.634  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
12-01 13:10:10.634  5576  5624 I jxcore-log: 
,12-01 13:10:10.650  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
12-01 13:10:10.650  5576  5624 I jxcore-log: 
,12-01 13:10:10.665  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
12-01 13:10:10.665  5576  5624 I jxcore-log: 
,12-01 13:10:10.671  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
12-01 13:10:10.671  5576  5624 I jxcore-log: 
,12-01 13:10:10.676  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
12-01 13:10:10.676  5576  5624 I jxcore-log: 
,12-01 13:10:10.690  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
12-01 13:10:10.690  5576  5624 I jxcore-log: 
,12-01 13:10:10.708  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
12-01 13:10:10.708  5576  5624 I jxcore-log: 
,12-01 13:10:10.722  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
12-01 13:10:10.722  5576  5624 I jxcore-log: 
,12-01 13:10:10.733  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
12-01 13:10:10.733  5576  5624 I jxcore-log: 
,12-01 13:10:10.746  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
12-01 13:10:10.746  5576  5624 I jxcore-log: 
,12-01 13:10:10.756  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
12-01 13:10:10.756  5576  5624 I jxcore-log: 
,12-01 13:10:10.770  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
12-01 13:10:10.770  5576  5624 I jxcore-log: 
,12-01 13:10:10.789  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
12-01 13:10:10.789  5576  5624 I jxcore-log: 
,12-01 13:10:10.796  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
12-01 13:10:10.796  5576  5624 I jxcore-log: 
,12-01 13:10:10.810  5576  5624 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,12-01 13:10:10.811  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO testUtils: 'BLE multiple advertisement supported'
12-01 13:10:10.811  5576  5624 I jxcore-log: 
,12-01 13:10:10.841  5576  5624 I jxcore-log: 2016-12-01 12:10:10 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
12-01 13:10:10.841  5576  5624 I jxcore-log: 
,12-01 13:10:11.187  5576  5624 I jxcore-log: 2016-12-01 12:10:11 - DEBUG CoordinatedClient: 'connected to the test server'
12-01 13:10:11.187  5576  5624 I jxcore-log: 
,12-01 13:10:29.481   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:10:30.285   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:31.286   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:32.287   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:33.289   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:34.290   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:10:35.291   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 13:10:52.721   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:10:58.780   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:11:00.291   592   592 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,12-01 13:11:00.291   592   592 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 13:11:09.487   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:11:10.895   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:11:15.293   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:16.294   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:16.955   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:11:17.296   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:18.297   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:19.299   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:20.300   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,12-01 13:11:25.301   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:26.303   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:27.304   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:28.305   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:29.306   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:29.488   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:11:30.307   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,12-01 13:11:40.308   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:41.309   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:42.310   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:43.311   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:44.313   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:11:45.313   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,12-01 13:12:00.314   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:01.316   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:02.317   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:03.319   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:04.320   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:05.320   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,12-01 13:12:08.407   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:12:09.493   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:12:11.441   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:12:25.322   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:26.323   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:27.324   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:28.325   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:29.326   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:12:29.496   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:12:30.327   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 13:12:35.643   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:12:38.674   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:12:41.707   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:12:44.738   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:12:49.499   929  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 13:12:55.328   592   592 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,12-01 13:12:55.328   592   592 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 13:13:15.006   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:13:15.329   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:16.331   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:17.332   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:18.033   929  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 13:13:18.333   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:19.334   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:20.334   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,12-01 13:13:25.336   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:26.338   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:27.140  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - DEBUG CoordinatedClient: 'device disconnected from the test server'
12-01 13:13:27.140  5576  5624 I jxcore-log: 
,12-01 13:13:27.339   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:27.410  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
12-01 13:13:27.410  5576  5624 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
12-01 13:13:27.410  5576  5624 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
12-01 13:13:27.410  5576  5624 I jxcore-log: emit@events.js:82:1
12-01 13:13:27.410  5576  5624 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
12-01 13:13:27.410  5576  5624 I jxcore-log: emit@events.js:82:1''
12-01 13:13:27.410  5576  5624 I jxcore-log: 
,12-01 13:13:27.412  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - DEBUG CoordinatedClient: 'test client failed'
12-01 13:13:27.412  5576  5624 I jxcore-log: 
,12-01 13:13:27.427  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
12-01 13:13:27.427  5576  5624 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
12-01 13:13:27.427  5576  5624 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
12-01 13:13:27.427  5576  5624 I jxcore-log: emit@events.js:82:1
12-01 13:13:27.427  5576  5624 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
12-01 13:13:27.427  5576  5624 I jxcore-log: emit@events.js:82:1''
12-01 13:13:27.427  5576  5624 I jxcore-log: 
,12-01 13:13:27.431  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - DEBUG CoordinatedClient: 'test client failed'
12-01 13:13:27.431  5576  5624 I jxcore-log: 
,12-01 13:13:27.436  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
12-01 13:13:27.436  5576  5624 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
12-01 13:13:27.436  5576  5624 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
12-01 13:13:27.436  5576  5624 I jxcore-log: emit@events.js:82:1
12-01 13:13:27.436  5576  5624 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
12-01 13:13:27.436  5576  5624 I jxcore-log: emit@events.js:82:1''
12-01 13:13:27.436  5576  5624 I jxcore-log: 
,12-01 13:13:27.436  5576  5624 I jxcore-log: 2016-12-01 12:13:27 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
12-01 13:13:27.436  5576  5624 I jxcore-log: 
,12-01 13:13:28.048  5875  5875 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,12-01 13:13:28.070  5875  5875 D AndroidRuntime: CheckJNI is OFF
,12-01 13:13:28.094  5875  5875 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,12-01 13:13:28.123  5875  5875 I Radio-JNI: register_android_hardware_Radio DONE
,12-01 13:13:28.139  5875  5875 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,12-01 13:13:28.151   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,12-01 13:13:28.152   929   942 I ActivityManager: Killing 5576:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,12-01 13:13:28.250   929  3363 I WindowState: WIN DEATH: Window{ba82f7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
12-01 13:13:28.251   929  2897 D WifiService: Client connection lost with reason: 4
12-01 13:13:28.251   929   939 D GraphicsStats: Buffer count: 2
,12-01 13:13:28.262   929   942 W ActivityManager: Force removing ActivityRecord{fb9e2ba u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,12-01 13:13:28.291   929   952 I art     : Starting a blocking GC Explicit
,12-01 13:13:28.298   929  3721 W ActivityManager: Spurious death for ProcessRecord{6a65dc9 0:com.test.thalitest/u0a77}, curProc for 5576: null
,12-01 13:13:28.329   929  3103 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5576 uid 10077
,12-01 13:13:28.327  3103  3103 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[27353]" dev="sockfs" ino=27353 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 13:13:28.327  3103  3103 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[27353]" dev="sockfs" ino=27353 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 13:13:28.331  3612  3612 I Keyboard.Facilitator: onFinishInput()
,12-01 13:13:28.339   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 13:13:28.388   929   952 I art     : Explicit concurrent mark sweep GC freed 97241(6MB) AllocSpace objects, 54(1444KB) LOS objects, 33% free, 29MB/43MB, paused 1.788ms total 96.546ms
,12-01 13:13:28.407  3923  5887 I MicroRecognitionRnrImpl: Starting detection.
,12-01 13:13:28.408   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
12-01 13:13:28.408  3923  5888 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d2c637e
,12-01 13:13:28.410  5875  5875 I art     : System.exit called, status: 0
,12-01 13:13:28.410  5875  5875 I AndroidRuntime: VM exiting with result code 0.
12-01 13:13:28.411   513  5891 I AudioFlinger: AudioFlinger's thread 0xf1e40000 ready to run
,12-01 13:13:28.421   513  2944 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,12-01 13:13:28.422  3923  5888 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d2c637e
,12-01 13:13:28.423   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,12-01 13:13:28.432   513  5891 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,12-01 13:13:28.432   513  5891 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,12-01 13:13:28.433   513  5891 I ACDB-LOADER: ACDB AFE returned = -19
12-01 13:13:28.433   513  5891 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,12-01 13:13:28.433   513  5891 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
12-01 13:13:28.433   513  5891 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
12-01 13:13:28.437  3612  3612 I Keyboard.Facilitator: resetDictionaries() : en_US
12-01 13:13:28.440  5779  5779 D BluetoothMapAppObserver: onReceive
,12-01 13:13:28.440  5779  5779 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,12-01 13:13:28.443   513  5891 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,12-01 13:13:28.444  3612  5894 I Keyboard.Facilitator.DecoderInitializer: run()
12-01 13:13:28.444  4018  4114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
12-01 13:13:28.450   929  2888 I InputReader: Reconfiguring input devices.  changes=0x00000010
,12-01 13:13:28.462  3612  5894 I Decoder : createOrResetDecoder
,12-01 13:13:28.501   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,12-01 13:13:28.509  3705  3705 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,12-01 13:13:28.510  3527  3527 I ConfigService: onCreate
,12-01 13:13:28.515  3349  5899 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,12-01 13:13:28.525  3923  3923 I HotwordWorkerImpl: onReady
,12-01 13:13:28.527  3612  5894 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,12-01 13:13:28.540    28    28 W kworker/2:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
12-01 13:13:28.546  3527  3527 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,12-01 13:13:28.546  3527  3527 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,12-01 13:13:28.547    28    28 W kworker/2:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 13:13:28.561  3790  5904 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,12-01 13:13:28.561  3790  5904 D AccountUtils: Clearing selected account for com.test.thalitest
,12-01 13:13:28.578  3790  3790 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
12-01 13:13:28.578  3790  3790 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
12-01 13:13:28.574    28    28 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 13:13:28.580  3790  5904 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,12-01 13:13:28.586  3790  3790 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,12-01 13:13:28.586  3790  3790 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,12-01 13:13:28.596  3923  5912 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,12-01 13:13:28.599  3790  5904 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
12-01 13:13:28.599  3790  5904 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
12-01 13:13:28.601  3790  5904 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 13:13:28.603  3790  5904 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,12-01 13:13:28.604  3349  5899 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
12-01 13:13:28.604  3790  5909 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
12-01 13:13:28.605  3790  5909 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 13:13:28.607  3790  5909 W SQLiteOpenHelper: Opened metrics.db in read-only mode
12-01 13:13:28.607  3790  5909 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
12-01 13:13:28.607  3790  5909 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
12-01 13:13:28.608  3790  5909 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
12-01 13:13:28.609  3790  5909 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
12-01 13:13:28.609  3790  5909 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
12-01 13:13:28.609  3790  5909 E AndroidRuntime: Process: com.google.android.gms, PID: 3790
12-01 13:13:28.609  3790  5909 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
12-01 13:13:28.609  3790  5909 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 13:13:28.611  3612  5894 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,12-01 13:13:28.620   929  5915 E DropBoxManagerService: Can't write: system_app_crash
12-01 13:13:28.620   929  5915 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 13:13:28.620   929  5915 E DropBoxManagerService: 	... 5 more
,12-01 13:13:28.620  3349  5899 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
12-01 13:13:28.620  3349  5899 E AndroidRuntime: Process: android.process.acore, PID: 3349
12-01 13:13:28.620  3349  5899 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
12-01 13:13:28.620  3349  5899 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 13:13:28.622  3923  5912 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
12-01 13:13:28.623  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
12-01 13:13:28.623  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,12-01 13:13:28.630  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
12-01 13:13:28.630  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,12-01 13:13:28.631  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
12-01 13:13:28.631  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
12-01 13:13:28.632  3612  5894 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
12-01 13:13:28.633  3612  5894 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
12-01 13:13:28.633  3612  5894 I Keyboard.Facilitator.Delight2FileSweeper: run()
12-01 13:13:28.633  3612  5894 I Keyboard.Facilitator.RecurringTaskScheduler: run()
12-01 13:13:28.633  3612  5894 I StatsUtilsManager: startPeriodStatsRecorder() : Success
12-01 13:13:28.633  3612  5894 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
12-01 13:13:28.637  3783  3783 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34058]" dev="sockfs" ino=34058 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 13:13:28.637  3783  3783 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34058]" dev="sockfs" ino=34058 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 13:13:28.642   929  5917 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,12-01 13:13:28.640   408   408 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32746]" dev="sockfs" ino=32746 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-01 13:13:28.640   408   408 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32746]" dev="sockfs" ino=32746 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 13:13:28.657   929  3721 I ActivityManager: Start proc 5918:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,12-01 13:13:28.662   929  5923 E DropBoxManagerService: Can't write: system_app_crash
12-01 13:13:28.662   929  5923 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 13:13:28.662   929  5923 E DropBoxManagerService: 	... 5 more
,12-01 13:13:28.675   929  3103 I ActivityManager: Start proc 5925:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,12-01 13:13:28.678  3790  5914 W BaseAppContext: Using Auth Proxy for data requests.
,12-01 13:13:28.683  3790  5914 W BaseAppContext: Using Auth Proxy for data requests.
,12-01 13:13:28.687  3790  5904 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,12-01 13:13:28.694  3790  5931 I GMPM-SVC: App measurement is starting up
,12-01 13:13:28.698   929   942 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{725dce4 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{50a8a76 3790 com.google.android.gms/10012/u0 remote:a009911}: process crashing
12-01 13:13:28.698  3790  3790 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
12-01 13:13:28.699  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
12-01 13:13:28.699  3790  5931 E GMPM-SVC: AppMeasurementService not registered/enabled
12-01 13:13:28.700  3790  5931 E GMPM-SVC: Uploading is not possible. App measurement disabled
12-01 13:13:28.701  3790  5931 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
12-01 13:13:28.702  3790  5931 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,12-01 13:13:28.702  3790  5931 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
12-01 13:13:28.702  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,12-01 13:13:28.702  3790  5931 E GMPM-SVC: Opening the database failed, dropping and recreating it
12-01 13:13:28.703  3790  5931 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
12-01 13:13:28.703  3790  5931 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,12-01 13:13:28.704  3790  5931 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
12-01 13:13:28.704  3790  5931 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
12-01 13:13:28.704  3790  5931 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
12-01 13:13:28.704  3790  5931 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
12-01 13:13:28.705  3790  5931 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
12-01 13:13:28.706  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.707  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.androi,d.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.707  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.707  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.707  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.708  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.708  3790  4871 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
12-01 13:13:28.710  3790  3790 I ConfigFetchService: service connected
,12-01 13:13:28.712  3790  5934 I PeopleContactsSync: CP2 sync disabled
,12-01 13:13:28.713   929  3784 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3790 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
12-01 13:13:28.714  3790  4165 I Icing   : doRemovePackageData com.test.thalitest
,12-01 13:13:28.765  3790  5908 W DriveInitializer: Awaiting to be initialized
,12-01 13:13:28.766  3790  5936 W DriveInitializer: Background init thread started
,12-01 13:13:28.868  3736  3966 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,12-01 13:13:28.970   385   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
