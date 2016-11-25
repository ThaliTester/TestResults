#### Test 89975734f660a83_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-25 13:25:36.574   924  2901 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:25:37.015  5547  5547 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 13:25:37.021  5547  5547 D AndroidRuntime: CheckJNI is OFF
11-25 13:25:37.046  5547  5547 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 13:25:37.077  5547  5547 I Radio-JNI: register_android_hardware_Radio DONE
11-25 13:25:37.092  5547  5547 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-25 13:25:37.103   924   934 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 13:25:37.147  3889  3905 W SearchService: Abort, client detached.
11-25 13:25:37.149  5547  5547 D AndroidRuntime: Shutting down VM
11-25 13:25:37.154  3889  3889 I HotwordDetector: Closing mic
11-25 13:25:37.154  3889  4114 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2fe22ab
11-25 13:25:37.155  3889  4121 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-25 13:25:37.177   924  3529 I ActivityManager: Start proc 5556:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 13:25:37.221   512  4135 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-25 13:25:37.224   512  4135 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-25 13:25:37.231   512  4135 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-25 13:25:37.231   512  4135 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 13:25:37.232   512  2949 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-25 13:25:37.235  3889  4115 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-25 13:25:37.235  3889  4118 I MicroRecognitionRnrImpl: Detection finished
11-25 13:25:37.283  5556  5556 I CordovaLog: Changing log level to DEBUG(3)
11-25 13:25:37.284  5556  5556 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 13:25:37.284  5556  5556 D CordovaActivity: CordovaActivity.onCreate()
11-25 13:25:37.287  5556  5556 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-25 13:25:37.307  5556  5556 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-25 13:25:37.334  5556  5556 I LibraryLoader: Time to load native libraries: 24 ms (timestamps 1784-1808)
11-25 13:25:37.334  5556  5556 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-25 13:25:37.353  5556  5556 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4c5bb5}
11-25 13:25:37.354  5556  5556 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-25 13:25:37.354  5556  5556 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-25 13:25:37.357  5556  5556 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-25 13:25:37.358  5556  5556 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 13:25:37.392  5556  5556 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 13:25:37.402  5556  5556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 13:25:37.402  5556  5556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 13:25:37.402  5556  5556 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 13:25:37.402  5556  5556 I Adreno  : Build Date                       : 12/06/15
11-25 13:25:37.402  5556  5556 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 13:25:37.402  5556  5556 I Adreno  : Local Branch                     : mybranch17112971
11-25 13:25:37.402  5556  5556 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 13:25:37.402  5556  5556 I Adreno  : Remote Branch                    : NONE
11-25 13:25:37.402  5556  5556 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 13:25:37.451   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d38427e:true
,11-25 13:25:37.495   405   405 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[27490]" dev="sockfs" ino=27490 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.495   405   405 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27490]" dev="sockfs" ino=27490 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.504  5556  5556 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 13:25:37.514  5556  5556 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 13:25:37.518  5556  5556 D PluginManager: init()
,11-25 13:25:37.520  5556  5556 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 13:25:37.540  5556  5556 D CordovaActivity: Started the activity.
11-25 13:25:37.540  5556  5556 D CordovaActivity: Resumed the activity.
,11-25 13:25:37.541   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33949]" dev="sockfs" ino=33949 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:25:37.544  5556  5593 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-25 13:25:37.541   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33949]" dev="sockfs" ino=33949 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.548   934   934 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[27942]" dev="sockfs" ino=27942 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:25:37.548   934   934 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27942]" dev="sockfs" ino=27942 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.550  5556  5580 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 13:25:37.576  5556  5593 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 13:25:37.663   924   942 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +512ms
,11-25 13:25:37.665  3699  3699 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33953]" dev="sockfs" ino=33953 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.665  3699  3699 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33953]" dev="sockfs" ino=33953 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.668  3721  3721 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33952]" dev="sockfs" ino=33952 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.670  3616  3616 I Keyboard.Facilitator: onFinishInput()
11-25 13:25:37.668  3721  3721 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33952]" dev="sockfs" ino=33952 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:25:37.686  5556  5556 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 13:25:37.707  5556  5556 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5556
,11-25 13:25:37.804  5556  5556 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 13:25:37.977   924  3106 I ActivityManager: Killing 5219:com.android.settings/1000 (adj 15): empty #17
,11-25 13:25:37.999   924  3106 I ActivityManager: Killing 5178:org.codeaurora.ims/1001 (adj 15): empty #18
,11-25 13:25:38.014  5556  5596 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -585627344
,11-25 13:25:38.019  5556  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 13:25:38.019  5556  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 13:25:38.019  5556  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 13:25:38.019  5556  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 13:25:38.019  5556  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 13:25:38.019  5556  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57459b0 added. We now have 1 listener(s)
,11-25 13:25:38.022  5556  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-25 13:25:38.023  5556  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:25:38.023  5556  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:25:38.023  5556  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-25 13:25:38.026  5556  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f14d14f added. We now have 1 listener(s)
11-25 13:25:38.026  5556  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:25:38.030   924  2902 D WifiService: New client listening to asynchronous messages
,11-25 13:25:38.031  5556  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:25:38.031  5556  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 13:25:38.032  5556  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-25 13:25:38.032  5556  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-25 13:25:38.032  5556  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 13:25:38.032  5556  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 13:25:38.032  5556  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-25 13:25:38.034  5556  5596 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 13:25:38.147  5556  5556 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 13:25:38.149  5556  5556 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-25 13:25:38.149  5556  5556 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 13:25:38.527  5556  5565 I art     : Background partial concurrent mark sweep GC freed 58220(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.671ms total 122.854ms
,11-25 13:25:38.620  5556  5603 W jxcore-log: Initializing JXcore engine
,11-25 13:25:38.620  5556  5603 W jxcore-log: JXcore engine is ready
,11-25 13:25:38.645  5603  5603 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1268 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-25 13:25:38.645  5603  5603 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15364]" dev="sockfs" ino=15364 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-25 13:25:38.645  5603  5603 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 13:25:38.645  5603  5603 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33921]" dev="sockfs" ino=33921 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-25 13:25:38.653  5556  5603 W jxcore-log: Starting JXcore engine
,11-25 13:25:38.704  5556  5603 W jxcore-log: Platform android
11-25 13:25:38.704  5556  5603 W jxcore-log: 
,11-25 13:25:38.704  5556  5603 W jxcore-log: Process ARCH arm
11-25 13:25:38.704  5556  5603 W jxcore-log: 
,11-25 13:25:38.892   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:25:38.893  5556  5603 I jxcore-log: JXcore Cordova bridge is ready!
11-25 13:25:38.893  5556  5603 I jxcore-log: 
11-25 13:25:38.894  5556  5603 W jxcore-log: JXcore engine is started
,11-25 13:25:38.910  5556  5596 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 13:25:38.915  5556  5556 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-25 13:25:38.916  5556  5556 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 13:25:44.660   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:25:44.946   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:25:45.661   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:25:46.662   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:25:47.348   924  2902 D WifiService: New client listening to asynchronous messages
,11-25 13:25:47.351  3889  5604 W CronetSyncConnectionRcs: Upload content type not set.
,11-25 13:25:47.663   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:25:48.628  5556  5603 I jxcore-log: 2016-11-25 12:25:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 13:25:48.628  5556  5603 I jxcore-log: 
,11-25 13:25:48.630  5556  5603 I jxcore-log: 2016-11-25 12:25:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 13:25:48.630  5556  5603 I jxcore-log: 
,11-25 13:25:48.635  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:25:48.636  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:25:48.637  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:25:48.639  5556  5603 I jxcore-log: 2016-11-25 12:25:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 13:25:48.639  5556  5603 I jxcore-log: 
,11-25 13:25:48.641  5556  5603 I jxcore-log: 2016-11-25 12:25:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 13:25:48.641  5556  5603 I jxcore-log: 
,11-25 13:25:48.664   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:25:48.887  5556  5603 I jxcore-log: 2016-11-25 12:25:48 - DEBUG UnitTest_app: 'Running unit tests'
11-25 13:25:48.887  5556  5603 I jxcore-log: 
,11-25 13:25:48.888  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:25:48.888  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29758db added. We now have 2 listener(s)
,11-25 13:25:48.889  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:25:48.889  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:25:48.889  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:25:48.889  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:25:48.889  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be5bf78 added. We now have 2 listener(s)
11-25 13:25:48.889  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:25:48.890  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:25:48.891  5556  5603 D executeNativeTests: Running unit tests
,11-25 13:25:48.933  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 13:25:48.933  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 added. We now have 3 listener(s)
,11-25 13:25:48.934  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:25:48.934  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:25:48.934  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:25:48.934  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:25:48.934  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 added. We now have 3 listener(s)
11-25 13:25:48.934  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:25:48.935  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:25:48.937  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:25:48.937  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:25:48.938  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:25:48.938  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:25:48.938  5556  5603 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-25 13:25:48.939  5556  5603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 13:25:48.939  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:25:48.939  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:25:48.939  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:25:48.939  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:25:48.939  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:25:48.939  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:25:48.939  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:25:48.940  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:25:48.940  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:25:48.940  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:25:48.940  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 removed from the list
11-25 13:25:48.940  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:48.940  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 removed from the list
11-25 13:25:48.940  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:25:48.940  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.940  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.941  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.941  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.941  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.941  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:25:48.941  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:25:48.941  5556  5603 I org.thaliproject,.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:48.941  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:48.942  5556  5603 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-25 13:25:48.943  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:25:48.943  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:25:48.943  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:25:48.943  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:25:48.943  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:25:48.943  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:25:48.943  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:48.943  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:48.943  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:25:48.943  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.943  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.944  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.944  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.944  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.944  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:25:48.944  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:25:48.944  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
11-25 13:25:48.944  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-25 13:25:48.947  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 13:25:48.948  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:25:48.948  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:25:48.948  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:25:48.948  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:25:48.948  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:25:48.948  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:25:48.948  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:25:48.948  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:48.948  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:25:48.948  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.948  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.949  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.949  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.949  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.949  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:25:48.949  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:25:48.949  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:48.949  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:48.950  5556  5603 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 13:25:48.951  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:25:48.951  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:25:48.960  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:25:48.961  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:25:48.961  5556  5603 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:25:48.962  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:25:48.962  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:25:48.962  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:25:48.962  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:25:48.962  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listen,er
11-25 13:25:48.964  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:25:48.964  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:25:48.964  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:25:48.966  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:25:48.970  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:25:48.971  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.971  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 13:25:48.972  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:25:48.972  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:25:48.972  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:25:48.973  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-25 13:25:48.974  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 13:25:48.974  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.974  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:25:48.974  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-25 13:25:48.974  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:25:48.975  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:25:48.975  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.975  5556  5603 D BluetoothAdapter: STATE_ON
,11-25 13:25:48.977  4609  4821 D BtGatt.GattService: registerClient() - UUID=341d8adf-214f-409d-bb64-c560bdc423e2
,11-25 13:25:48.978  4609  4684 D BtGatt.GattService: onClientRegistered() - UUID=341d8adf-214f-409d-bb64-c560bdc423e2, clientIf=5
,11-25 13:25:48.979  5556  5567 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:25:48.982  4609  4831 D BtGatt.GattService: start scan with filters
,11-25 13:25:48.989  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:25:48.989  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.989  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:25:48.989  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.989  4609  4687 D BtGatt.ScanManager: handling starting scan
11-25 13:25:48.989  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 13:25:48.989  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:25:48.989  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 13:25:48.990  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:25:48.990  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 13:25:48.990  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:25:48.990  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:25:48.990  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.990  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:25:48.990  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:25:48.990  4609  4687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:25:48.990  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 13:25:48.991  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.991  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.991  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:48.991  5556  5603 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:25:48.991  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 13:25:48.995  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:25:48.995  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 13:25:48.995  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:48.995  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:48.996  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 13:25:48.999  4609  4684 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 13:25:48.999  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:49.000  4609  4687 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 13:25:49.007  4609  4684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:25:49.007  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:49.008  4609  4687 D BtGatt.ScanManager: Starting BLE batch scan
,11-25 13:25:49.008  4609  4687 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 13:25:49.020  4609  4684 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 13:25:49.020  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:25:49.027  4609  4684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 13:25:49.027  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:25:49.497  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 13:25:49.498  5556  5556 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 13:25:49.498  5556  5556 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:25:49.665   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:25:53.996  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:25:53.996  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:25:53.996  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:25:53.996  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:25:53.996  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:25:53.996  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:25:53.997  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 13:25:53.997  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:25:53.997  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:25:53.997  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:25:53.997  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-25 13:25:53.998  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:53.998  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:53.998  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:53.998  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:25:53.998  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:53.999  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:25:54.000  4609  4623 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:25:54.000  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:25:54.002  4609  4687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:25:54.002  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:25:54.003  4609  4830 D BtGatt.GattService: stopScan() - queue size =1
,11-25 13:25:54.005  4609  5269 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:25:54.006  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:25:54.007  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.007  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-25 13:25:54.007  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.008  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.008  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.008  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.009  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:25:54.009  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-25 13:25:54.010  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.010  4609  4609 D BtGatt.ScanManager: awakened up at time 198484
11-25 13:25:54.010  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.010  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:25:54.010  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:25:54.013  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:25:54.013  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.016  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.016  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:25:54.016  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.016  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:54.017  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:25:54.017  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:25:54.017  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:25:54.017  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:25:54.017  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:25:54.017  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:25:54.017  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:25:54.017  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:25:54.017  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:54.017  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.017  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:54.017  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:25:54.017  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:25:54.017  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:25:54.017  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:25:54.017  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.018  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.018  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.018  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:25:54.018  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.019  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.022  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.022  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.022  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:54.026   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:25:54.037  4609  4684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-25 13:25:54.038  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:25:54.038  4609  4684 D BtGatt.GattService: current time is 198513179566
11-25 13:25:54.038  4609  4684 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -80, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 13:25:54.040  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 13:25:54.042  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 13:25:54.043  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 13:25:54.043  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 13:25:54.044  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-25 13:25:54.051  4609  4684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:25:54.051  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:54.051  4609  4687 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:25:54.058  4609  4684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:25:54.058  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:54.058  4609  4687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:25:54.065  4609  4684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:25:54.065  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:25:54.520  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:25:56.577   924  2901 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:25:59.020  5556  5603 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 13:25:59.025  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:25:59.026  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:25:59.039  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:25:59.044  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:25:59.044  5556  5603 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:25:59.045  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:25:59.045  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:25:59.045  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:25:59.045  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:25:59.045  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:25:59.051  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:25:59.053  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:25:59.053  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 13:25:59.053  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:25:59.055  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:25:59.058  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:25:59.058  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 13:25:59.059  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 13:25:59.059  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:25:59.059  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:25:59.064  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.064  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-25 13:25:59.064  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:25:59.064  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:25:59.065  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:25:59.065  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:25:59.066  5556  5603 D BluetoothAdapter: STATE_ON
,11-25 13:25:59.069  4609  4623 D BtGatt.GattService: registerClient() - UUID=7dd0338c-5cc3-4377-9c20-1156cdda3736
11-25 13:25:59.070  4609  4684 D BtGatt.GattService: onClientRegistered() - UUID=7dd0338c-5cc3-4377-9c20-1156cdda3736, clientIf=5
,11-25 13:25:59.070  5556  5567 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:25:59.070  4609  4830 D BtGatt.GattService: start scan with filters
,11-25 13:25:59.074  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:25:59.074  4609  4687 D BtGatt.ScanManager: handling starting scan
11-25 13:25:59.074  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.074  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:25:59.074  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.074  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:25:59.074  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:25:59.074  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 13:25:59.074  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:25:59.074  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:25:59.075  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.075  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.075  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.075  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.076  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:25:59.076  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.080  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.080  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:25:59.080  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.080  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.080  5556  5603 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:25:59.080  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.081  4609  4684 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:25:59.081  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.081  4609  4687 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:25:59.083  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:25:59.083  5556  5603 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 13:25:59.083  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:25:59.083  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:25:59.083  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:25:59.083  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:25:59.083  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:25:59.083  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:25:59.084  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.085  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.085  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.085  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:25:59.085  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:25:59.085  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.085  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:25:59.085  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:25:59.085  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.085  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.086  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.086  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:25:59.086  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.086  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:25:59.087  4609  4622 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:25:59.087  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:25:59.087  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:25:59.088  4609  4623 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:25:59.089  4609  4821 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:25:59.089  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:25:59.089  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.089  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:25:59.089  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.090  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:25:59.090  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:25:59.091  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:25:59.091  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.091  4609  4684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:25:59.091  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.091  4609  4687 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:25:59.091  4609  4687 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:25:59.092  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.092  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:25:59.092  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.092  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.092  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:25:59.092  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:25:59.092  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:25:59.093  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:25:59.093  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:25:59.093  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:59.093  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:59.093  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:25:59.093  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:25:59.094  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.095  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.099  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.099  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.099  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.099  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:25:59.099  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:25:59.099  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:25:59.099  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:25:59.099  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:25:59.099  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:25:59.099  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.100  5556  5603 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.100  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:25:59.100  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.100  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.102  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.102  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.102  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:25:59.102  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.102  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:25:59.103  4609  4684 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:25:59.103  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:25:59.108  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:25:59.108  4609  4684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:25:59.108  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.110  4609  4687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:25:59.110  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:25:59.110  5556  5603 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:25:59.110  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:25:59.110  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:25:59.110  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:25:59.111  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:25:59.111  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:25:59.113  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:25:59.116  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:25:59.116  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:25:59.116  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:25:59.116  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:25:59.116  4609  4684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:25:59.116  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.116  4609  4684 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:25:59.119  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.119  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:25:59.120  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:25:59.120  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:25:59.120  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:25:59.122  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.122  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:25:59.122  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:25:59.122  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:25:59.122  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:25:59.122  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.123  4609  4684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:25:59.123  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.123  4609  4687 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:25:59.123  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:25:59.125  4609  4831 D BtGatt.GattService: registerClient() - UUID=a500317d-a646-4473-ac33-ec3e52224f07
11-25 13:25:59.126  4609  4684 D BtGatt.GattService: onClientRegistered() - UUID=a500317d-a646-4473-ac33-ec3e52224f07, clientIf=5
11-25 13:25:59.127  5556  5567 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:25:59.127  4609  4821 D BtGatt.GattService: start scan with filters
11-25 13:25:59.128  4609  4684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:25:59.128  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.128  4609  4687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:25:59.131  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:25:59.131  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.131  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:25:59.131  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.131  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:25:59.131  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:25:59.131  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.131  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:25:59.131  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:25:59.132  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.132  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.132  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.132  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.132  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:25:59.132  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.134  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.134  4609  4684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:25:59.134  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:25:59.134  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.134  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.135  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:25:59.135  5556  5603 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:25:59.135  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.136  4609  4687 D BtGatt.ScanManager: handling starting scan
11-25 13:25:59.137  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.137  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.137  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:25:59.138  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:25:59.141  4609  4684 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:25:59.141  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.141  4609  4687 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:25:59.146  4609  4684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:25:59.146  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:25:59.147  4609  4687 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:25:59.147  4609  4687 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:25:59.154  4609  4684 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:25:59.155  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:25:59.159  4609  4684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:25:59.159  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:25:59.639  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-25 13:25:59.640  5556  5556 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 13:25:59.640  5556  5556 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:26:00.070   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:26:00.071   924  2903 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-25 13:26:03.096   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:26:03.100   924  2903 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-25 13:26:04.135  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:26:04.136  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:26:04.136  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:26:04.136  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:26:04.136  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:26:04.136  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:04.136  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:26:04.137  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:26:04.137  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.137  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 13:26:04.137  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:26:04.137  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.138  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.138  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.138  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:26:04.138  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.141  5556  5603 D BluetoothAdapter: STATE_ON
,11-25 13:26:04.141  4609  4830 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:26:04.143  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:26:04.144  4609  4687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:26:04.147  5556  5603 D BluetoothAdapter: STATE_ON
,11-25 13:26:04.149  4609  4821 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:26:04.150  4609  4609 D BtGatt.ScanManager: awakened up at time 208625
,11-25 13:26:04.150  4609  5269 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 13:26:04.151  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:26:04.151  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.152  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:26:04.152  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:04.152  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.152  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.152  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.153  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-25 13:26:04.153  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.153  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.153  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:04.154  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:26:04.154  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:26:04.157  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:26:04.157  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:04.160  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:04.160  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:26:04.160  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:04.160  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:04.161  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 13:26:04.161  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:26:04.161  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:26:04.162  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.162  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:26:04.162  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:26:04.162  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.162  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.162  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.162  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:26:04.163  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.163  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.165  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.166  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:26:04.166  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:26:04.175  4609  4684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-25 13:26:04.175  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:26:04.175  4609  4684 D BtGatt.GattService: current time is 208650370272
11-25 13:26:04.175  4609  4684 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -83, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-25 13:26:04.176  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 13:26:04.176  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 13:26:04.176  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-25 13:26:04.177  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 13:26:04.177  4609  4684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-25 13:26:04.184  4609  4684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 13:26:04.185  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:26:04.185  4609  4687 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:26:04.192  4609  4684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:26:04.192  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:26:04.192  4609  4687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:26:04.199  4609  4684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:26:04.199  4609  4684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:26:04.663  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:26:04.663  5556  5556 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:04.663  5556  5556 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:26:09.163  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.163  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:26:09.163  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.164  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.164  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:26:09.164  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 13:26:09.164  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.164  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
,11-25 13:26:09.164  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.164  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.165  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:09.165  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 13:26:09.169  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.173  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.176  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.176  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.179  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.179  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:26:09.179  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.179  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.179  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:09.181  5556  5603 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-25 13:26:09.182  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.183  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:26:09.183  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:26:09.183  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:26:09.183  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.183  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.183  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.183  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.183  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.184  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.184  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.187  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.187  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.187  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.187  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.187  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.187  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.188  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.190  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 13:26:09.190  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.190  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.190  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:26:09.191  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.191  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.191  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.191  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.191  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.191  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:09.191  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.192  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.194  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.195  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.195  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.195  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.195  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.195  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.195  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:09.197  5556  5603 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-25 13:26:09.197  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.197  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:26:09.197  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.197  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:26:09.198  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.198  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.198  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.198  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.198  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.198  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.198  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.201  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.201  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.201  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.201  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.201  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.202  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.202  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:09.203  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 13:26:09.203  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.203  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.203  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.204  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.204  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.204  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.204  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.204  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.204  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.204  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.204  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.207  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.207  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.207  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.207  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.207  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.207  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.207  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.208  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:26:09.209  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:26:09.209  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:26:09.209  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:26:09.209  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:26:09.209  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:26:09.209  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:26:09.209  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:26:09.210  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:26:09.210  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.210  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.210  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.210  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.210  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.210  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.210  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.210  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.210  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.211  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.211  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.212  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.213  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.213  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.213  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.213  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.213  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.213  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:09.214  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:26:09.214  5556  5603 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 13:26:09.214  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 13:26:09.219  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:26:09.219  5556  5603 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 13:26:09.219  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 13:26:09.220  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 13:26:09.221  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 13:26:09.221  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 13:26:09.222  5556  5603 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:26:09.222  5556  5603 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 13:26:09.222  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:26:09.222  5556  5603 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:26:09.222  5556  5603 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-25 13:26:09.222  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:26:09.223  5556  5603 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:26:09.223  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-25 13:26:09.227  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-25 13:26:09.228  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 13:26:09.228  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-25 13:26:09.229  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-25 13:26:09.229  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 13:26:09.229  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 13:26:09.229  5556  5603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:26:09.229  5556  5603 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 13:26:09.230  5556  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-25 13:26:09.230  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.231  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.231  5556  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-25 13:26:09.231  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.231  5556  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-25 13:26:09.231  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:26:09.231  5556  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 13:26:09.231  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.231  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-25 13:26:09.232  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.232  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.232  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.232  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.232  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.232  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.235  5269  5269 W Binder_6: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31741]" dev="sockfs" ino=31741 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:26:09.234  5556  5616 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,11-25 13:26:09.234  5556  5616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:26:09.234  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.234  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.234  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.234  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.234  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.235  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.235  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.235  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-25 13:26:09.235  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 13:26:09.236  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-25 13:26:09.236  5556  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-25 13:26:09.236  5556  5603 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 13:26:09.237  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.237  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.237  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.237  5556  5616 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-25 13:26:09.237  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.235  5269  5269 W Binder_6: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31741]" dev="sockfs" ino=31741 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:26:09.238  5556  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 13:26:09.238  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.238  5556  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-25 13:26:09.238  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.238  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.238  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.238  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:09.238  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.238  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.240  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.240  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.240  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.240  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.240  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.240  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.241  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:09.242  5556  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-25 13:26:09.242  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.242  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.242  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.242  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.242  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.242  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.242  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.242  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:09.242  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.242  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.243  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.244  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.244  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.244  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.244  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.244  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.244  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:09.244  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.245  5556  5603 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 13:26:09.245  5556  5603 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 13:26:09.245  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:26:09.245  5556  5603 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 13:26:09.245  5556  5603 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 13:26:09.245  5556  5603 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 13:26:09.245  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:26:09.245  5556  5603 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 13:26:09.245  5556  5603 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-25 13:26:09.245  5556  5603 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 13:26:09.245  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:26:09.246  5556  5603 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 13:26:09.246  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:09.246  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:09.246  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:09.246  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.246  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.246  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.246  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.246  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.246  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:09.246  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:09.246  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.247  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.247  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.247  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:09.247  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:09.247  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:09.248  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.248  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.248  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:09.248  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:09.248  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:09.248  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:09.248  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:09.249  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:14.249  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.250  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:14.250  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:14.250  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:14.250  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:14.251  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:26:14.251  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:14.251  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:14.251  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:14.252  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:14.252  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
,11-25 13:26:14.252  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.252  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.252  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:14.253  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.253  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.258  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.259  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.259  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.259  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:26:14.259  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:26:14.259  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.260  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.264  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-25 13:26:14.265  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:26:14.265  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:26:14.270  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-25 13:26:14.272  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-25 13:26:14.272  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-25 13:26:14.273  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-25 13:26:14.273  5556  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-25 13:26:14.273  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-25 13:26:14.273  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:26:14.273  5556  5556 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-25 13:26:14.274  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:26:14.274  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-25 13:26:14.274  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 13:26:14.274  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 13:26:14.275  5556  5618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:26:14.275  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 13:26:14.276  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 13:26:14.276  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-25 13:26:14.276  5556  5556 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 13:26:14.276  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:14.277  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:14.275  5269  5269 W Binder_6: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31743]" dev="sockfs" ino=31743 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:26:14.277  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:26:14.277  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.277  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:26:14.278  5269  5269 W Binder_6: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31743]" dev="sockfs" ino=31743 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:26:14.277  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-25 13:26:14.278  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.279  5556  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 13:26:14.279  5556  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-25 13:26:14.279  5556  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 13:26:14.281  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.281  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:26:14.281  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.282  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.282  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.282  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 13:26:14.282  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:14.282  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:26:14.282  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:26:14.282  5556  5556 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-25 13:26:14.282  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:14.282  5556  5556 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:26:14.282  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:14.282  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:14.282  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:26:14.282  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:14.283  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.283  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.283  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:14.283  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.283  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.285  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.285  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.285  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.285  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:14.286  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:14.286  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.286  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.288  5556  5603 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-25 13:26:14.288  5556  5603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 13:26:14.288  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:26:14.288  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:26:14.289  5556  5603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:26:14.289  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:14.289  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:14.289  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:14.289  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:14.289  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:26:14.289  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:14.290  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:14.290  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.290  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:14.290  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.290  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.292  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.292  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.292  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.293  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:26:14.293  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:14.293  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.293  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:14.301  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:26:14.301  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:14.301  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:14.301  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:14.301  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:26:14.302  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:14.302  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:14.302  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.302  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:14.302  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.302  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.304  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.304  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.304  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.305  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:26:14.305  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:14.305  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:14.305  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
,11-25 13:26:14.306  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:26:14.307  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:26:14.307  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:26:14.307  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:26:14.307  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:26:14.307  5556  5603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c765c1 not in the list
11-25 13:26:14.307  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.307  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.307  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:14.307  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.307  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:26:14.310  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.310  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.310  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:26:14.310  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:26:14.310  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:26:14.310  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:14.310  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d5166 not in the list
11-25 13:26:14.311  5556  5603 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-25 13:26:14.311  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:26:14.312  5556  5603 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-25 13:26:14.312  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:26:14.312  5556  5603 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 13:26:14.312  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:26:14.314  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 13:26:14.314  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-25 13:26:14.314  5556  5603 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-25 13:26:14.314  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 13:26:14.315  5556  5603 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 13:26:14.315  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 13:26:14.315  5556  5603 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-25 13:26:14.315  5556  5603 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-25 13:26:14.316  5556  5603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-25 13:26:14.316  5556  5603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 13:26:14.317  5556  5603 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-25 13:26:14.317  5556  5603 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 13:26:14.317  5556  5603 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 13:26:14.317  5556  5603 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-25 13:26:14.318  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:26:14.319  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c244d97 added. We now have 3 listener(s)
11-25 13:26:14.319  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:14.321  5556  5603 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 13:26:14.322   924  3362 D WifiService: setWifiEnabled: true pid=5556, uid=10077
,11-25 13:26:14.322   924  3362 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:26:14.365  4609  4817 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-25 13:26:14.365  4609  4819 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-25 13:26:14.665   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:26:14.666   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:26:14.783  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:26:16.580   924  2901 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:26:18.226   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:26:19.328  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:26:19.329  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e33b84 added. We now have 4 listener(s)
11-25 13:26:19.329  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:19.342  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:19.342  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e33b84 removed from the list
,11-25 13:26:19.342  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:19.345  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:26:19.346  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfabf6d added. We now have 4 listener(s)
,11-25 13:26:19.346  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:19.350  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:19.350  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfabf6d removed from the list
11-25 13:26:19.350  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:19.352  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:26:19.352  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@864e7a2 added. We now have 4 listener(s)
11-25 13:26:19.352  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:19.357   924  3697 D WifiService: setWifiEnabled: false pid=5556, uid=10077
11-25 13:26:19.358   924  3697 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:26:19.363   924  2901 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-25 13:26:19.364   924  2901 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 13:26:19.364   924  2901 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:26:19.364   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:26:19.371  4609  4680 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 13:26:19.371  4609  4680 D BluetoothAdapterProperties: Setting state to 13
11-25 13:26:19.371  4609  4680 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 13:26:19.374  4609  4680 D BluetoothAdapterProperties: onBluetoothDisable()
,11-25 13:26:19.374  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:26:19.375  4609  4680 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:26:19.376  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:26:19.380  4609  4684 D BluetoothAdapterProperties: Scan Mode:20
,11-25 13:26:19.381  4609  4680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 13:26:19.381  4609  4609 D BluetoothMapService: onReceive
11-25 13:26:19.381  4609  4609 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:26:19.382  4609  4609 D BluetoothMapService: STATE_TURNING_OFF
11-25 13:26:19.382  4609  4609 D BluetoothMapService: MAP Service closeService in
,11-25 13:26:19.382  4609  4609 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 13:26:19.382  4609  4609 D ObexServerSockets0: shutdown(block = true)
11-25 13:26:19.383  4609  4609 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:26:19.383  4609  4609 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:26:19.383  4609  4833 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-25 13:26:19.383   924  5313 D DhcpClient: Clearing IP address
11-25 13:26:19.383  4609  4819 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 13:26:19.384  4609  4834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-25 13:26:19.384   507   918 D CommandListener: Clearing all IP addresses on wlan0
11-25 13:26:19.387  4609  4609 I BtOppRfcommListener: stopping Accept Thread
11-25 13:26:19.387  4609  5240 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 13:26:19.388  4609  5240 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-25 13:26:19.392   507   918 D CommandListener: Setting iface cfg
,11-25 13:26:19.398   924   937 I ActivityManager: Start proc 5622:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-25 13:26:19.401  4609  4609 D HeadsetService: Received stop request...Stopping profile...
,11-25 13:26:19.403   924   924 D BluetoothHeadset: Proxy object disconnected
,11-25 13:26:19.404  3709  3728 D BluetoothHeadset: Proxy object disconnected
,11-25 13:26:19.405   924   924 D BluetoothHeadset: Proxy object disconnected
11-25 13:26:19.405  3059  3086 D BluetoothHeadset: Proxy object disconnected
,11-25 13:26:19.405  3502  5367 V NativeCrypto: Read error: ssl=0x7f759b9000: I/O error during system call, Connection timed out
,11-25 13:26:19.406   924   924 D BluetoothHeadset: Proxy object disconnected
11-25 13:26:19.406  4609  4609 D A2dpService: Received stop request...Stopping profile...
11-25 13:26:19.407  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:26:19.407  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:26:19.407  4609  4824 D A2dpStateMachine: Exit Disconnected: -1
11-25 13:26:19.408  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:26:19.408  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:26:19.408   924  5314 D DhcpClient: Receive thread stopped
11-25 13:26:19.408  5556  5603 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:26:19.408   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-25 13:26:19.408   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-25 13:26:19.410  3502  5367 V NativeCrypto: SSL shutdown failed: ssl=0x7f759b9000: I/O error during system call, Broken pipe
11-25 13:26:19.413   924   924 D RttService: SCAN_AVAILABLE : 1
11-25 13:26:19.413   538   538 E Parcel  : Reading a NULL string not supported here.
11-25 13:26:19.414  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:19.414  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:26:19.414   924  3010 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 13:26:19.415  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:19.415  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:26:19.416  3059  3059 D HeadsetProfile: Bluetooth service disconnected
11-25 13:26:19.417  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:19.417   924  2903 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 13:26:19.419  3673  3801 W QCNEJ   : |CORE| network lost: 100
11-25 13:26:19.420  3673  3801 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 13:26:19.421  3059  3059 D BluetoothA2dp: Proxy object disconnected
11-25 13:26:19.421  4609  4609 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:19.421  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.421  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.421  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:19.422  4609  4609 D HidService: Received stop request...Stopping profile...
11-25 13:26:19.422  4609  4609 D HidService: Stopping Bluetooth HidService
11-25 13:26:19.421   924   924 D BluetoothA2dp: Proxy object disconnected
11-25 13:26:19.423  3059  3059 D BluetoothInputDevice: Proxy object disconnected
11-25 13:26:19.423  3059  3059 D HidProfile: Bluetooth service disconnected
11-25 13:26:19.424  4609  4609 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 13:26:19.424  4609  4609 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 13:26:19.424  4609  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:19.424  4609  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:19.424  4609  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:19.425  4609  4684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 13:26:19.425  4609  4684 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 13:26:19.425  4609  4609 D HealthService: Received stop request...Stopping profile...
11-25 13:26:19.427  4609  4609 D PanService: Received stop request...Stopping profile...
,11-25 13:26:19.429  4609  4609 D BluetoothMapService: Received stop request...Stopping profile...
11-25 13:26:19.429  4609  4609 D BluetoothMapService: stop()
,11-25 13:26:19.429  4609  4609 D BluetoothMapAppObserver: deinitObservers()
11-25 13:26:19.429  4609  4609 D BluetoothMapAppObserver: removeReceiver()
11-25 13:26:19.431  4609  4609 D SapService: Received stop request...Stopping profile...
11-25 13:26:19.431  4609  4609 V SapService: stop()
11-25 13:26:19.432   924  2901 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 13:26:19.432  4609  4609 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:19.432  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.432  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.432  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:19.434  4609  4609 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 13:26:19.434  4609  4684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 13:26:19.434  4609  4609 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 13:26:19.434  4609  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:19.434  4609  4684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:26:19.434  4609  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:19.434  4609  4817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:19.434  4609  4817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.434  4609  4817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.434  4609  4817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 13:26:19.434  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:19.435  4609  4609 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 13:26:19.435  4609  4684 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 13:26:19.435  4609  4609 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 13:26:19.435  4609  4609 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:19.435  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.435  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.435  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:19.435  4609  4609 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 13:26:19.435  4609  4609 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 13:26:19.436  4609  4609 D BluetoothMapService: MAP Service closeService in
11-25 13:26:19.436  4609  4609 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:19.436  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.436  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.436  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:19.437  4609  4609 D BluetoothMapService: cleanup()
11-25 13:26:19.437  4609  4609 D BluetoothMapService: MAP Service closeService in
11-25 13:26:19.437  4609  4609 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:19.437  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.437  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.437  4609  4609 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:19.437  4609  4680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 13:26:19.437  4609  4680 D BluetoothAdapterProperties: Setting state to 15
11-25 13:26:19.437  4609  4680 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 13:26:19.438  4609  4680 I BluetoothAdapterState: Entering BleOnState
11-25 13:26:19.438  3059  3937 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:26:19.439   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:26:19.442  3709  3941 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:19.442   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:26:19.442  3059  3086 ,D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:26:19.443  3059  3079 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:26:19.443   924  2901 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:26:19.443   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:19.444   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:19.444  3059  3933 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:26:19.444  3059  3934 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:19.445   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:19.445  3059  3937 D BluetoothPan: onBluetoothStateChange on: false
,11-25 13:26:19.448  4609  4680 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 13:26:19.448  4609  4680 D BluetoothAdapterProperties: Setting state to 16
11-25 13:26:19.448  4609  4680 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 13:26:19.449  4609  4680 D BluetoothAdapterProperties: onBleDisable
11-25 13:26:19.449  4609  4680 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:26:19.449  4609  4681 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 13:26:19.450  4609  4684 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:26:19.451  4609  4817 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 13:26:19.451  4609  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:19.451  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:19.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:26:19.455  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:26:19.464   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:26:19.464   507   918 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:26:19.465   507   918 D TetherController: Setting IP forward enable = 0
,11-25 13:26:19.466   924  2903 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-25 13:26:19.466   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 13:26:19.467   924   941 D Tethering: MasterInitialState.processMessage what=3
11-25 13:26:19.469  5194  5194 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@babc3f1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-25 13:26:19.469  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:19.471  3889  3889 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 13:26:19.473   924  2901 D DhcpClient: doQuit
11-25 13:26:19.474   924  2901 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 13:26:19.474  3401  3401 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-25 13:26:19.475   924  5313 D DhcpClient: onQuitting
11-25 13:26:19.477  4982  5004 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:26:19.477  4982  5004 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:26:19.477  4982  5004 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 13:26:19.477  4982  5004 E SarControlService: no key has been found,reset the power
11-25 13:26:19.477  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:26:19.478  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:26:19.478  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:26:19.478  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:19.478  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:26:19.479  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:19.479  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:26:19.479  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:26:19.479  5007  5007 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:26:19.481  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:26:19.485  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:26:19.486  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-25 13:26:19.486  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:26:19.487  5007  5007 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:26:19.487  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000ea03000000000000ffffffff]
11-25 13:26:19.488  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:26:19.488  5007  5021 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 13:26:19.488  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:26:19.488  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:26:19.490  5622  5622 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-25 13:26:19.496  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000eb03000000000000ffffffff]
,11-25 13:26:19.496  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:26:19.496  5007  5021 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-25 13:26:19.497  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:26:19.497  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:26:19.498  3401  3401 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:26:19.503  3401  3401 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 13:26:19.504   507   911 W SocketClient: write error (Broken pipe)
11-25 13:26:19.504   507   911 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-25 13:26:19.504   507   911 W SocketListener: Error sending broadcast (Broken pipe)
11-25 13:26:19.504  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:26:19.513   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7e6184:true
,11-25 13:26:19.514  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:26:19.520   507   918 E Netd    : netlink response contains error (No such file or directory)
11-25 13:26:19.521   924  2903 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-25 13:26:19.531  3401  3401 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 13:26:19.533  5622  5622 D LocalBluetoothProfileManager: Adding local MAP profile
11-25 13:26:19.534  5622  5622 D BluetoothMap: Create BluetoothMap proxy object
,11-25 13:26:19.543  5622  5622 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 13:26:19.549  3401  3401 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-25 13:26:19.549  5622  5622 D DockEventReceiver: finishStartingService: stopping service
11-25 13:26:19.552  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:26:19.557  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:26:19.557  5622  5622 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:26:19.561   924  3622 I ActivityManager: Killing 5342:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-25 13:26:19.592  3910  3910 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:26:19.597  3910  3910 D SystemUpdateService: onCreate
,11-25 13:26:19.601  3910  3910 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:26:19.605  3910  5655 I SystemUpdateService: active receiver: enabled
,11-25 13:26:19.610  3910  3910 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 13:26:19.614  3910  5338 I iu.UploadsManager: num queued entries: 0
,11-25 13:26:19.617  3910  3910 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 13:26:19.618  3910  3910 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:26:19.620  3910  5655 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:26:19.621  3910  5338 I iu.UploadsManager: num updated entries: 0
,11-25 13:26:19.622  3910  5338 I iu.SyncManager: NEXT; no task
,11-25 13:26:19.624  3910  5655 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 13:26:19.624  3910  5655 I SystemUpdateService: now status is 0 (complete)
11-25 13:26:19.624  3910  5655 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:26:19.624  3910  5655 I SystemUpdateService: file has been verified
11-25 13:26:19.624  3910  5655 I SystemUpdateService: OTA package size = 21989297
,11-25 13:26:19.630   924  3113 I ActivityManager: Start proc 5657:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-25 13:26:19.634  3910  5655 I SystemUpdateService: showing system update notification
,11-25 13:26:19.644   924   924 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:26:19.646  3910  3910 D SystemUpdateService: onDestroy
,11-25 13:26:19.653  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:26:19.654   924  2901 D wifi    : In wifi stop Hal
,11-25 13:26:19.654   924  2901 D wifi    : halHandle = 0x7f5f4e0680, mVM = 0x7f7bb0d140, mCls = 0x100a02
11-25 13:26:19.654   924  3400 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 13:26:19.654   924  3400 D WifiHAL : Got a signal to exit!!!
11-25 13:26:19.654   924  3400 I WifiHAL : Exit wifi_event_loop
11-25 13:26:19.655   924  2901 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-25 13:26:19.655   924  2901 E WifiHAL : Event processing terminated
11-25 13:26:19.655   924  2901 D wifi    : In wifi cleaned up handler
11-25 13:26:19.655   924  2901 I WifiHAL : Internal cleanup completed
,11-25 13:26:19.656  4609  4684 I bt_hci  : shut_down
11-25 13:26:19.658  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:19.661  4609  4690 D bt_hwcfg: hw_epilog_process
11-25 13:26:19.661  4609  4690 I bt_vendor: low_power_mode_cb
,11-25 13:26:19.664  4609  4690 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 13:26:19.664  4609  4690 I bt_vendor: epilog_cb
11-25 13:26:19.664  4609  4690 I bt_hci  : epilog_finished_callback
11-25 13:26:19.666  4055  4185 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:26:19.667  4609  4684 I bt_hci_h4: hal_close
11-25 13:26:19.667  4609  4684 I bt_userial_vendor: device fd = 54 close
,11-25 13:26:19.670  5657  5657 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-25 13:26:19.673  5657  5657 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 13:26:19.676   924  3400 D wifi    : set interface wlan0 flags (DOWN)
11-25 13:26:19.676   924  2901 D WifiNative-HAL: HAL event thread stopped successfully
11-25 13:26:19.681  5657  5657 D SprintDMHelper: simOperator: 
11-25 13:26:19.681  5657  5657 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 13:26:19.693  4957  5669 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-25 13:26:19.707   924  3758 I ActivityManager: Start proc 5670:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
11-25 13:26:19.709   924  3753 I ActivityManager: Killing 5194:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 13:26:19.745  5670  5670 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 13:26:19.751   924  3622 I ActivityManager: Killing 3805:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 13:26:19.777  4609  4681 D bt_stack_manager: event_shut_down_stack finished.
,11-25 13:26:19.777  4609  4680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 13:26:19.779  4609  4680 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-25 13:26:19.779  4609  4609 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:26:19.779  4609  4609 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 13:26:19.779  4609  4609 D BtGatt.GattService: stop()
11-25 13:26:19.779  4609  4609 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 13:26:19.781  4609  4609 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:19.781  4609  4609 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:19.781  4609  4609 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:19.781  4609  4609 V BluetoothAdapterState: isBleTurningOff()=true
11-25 13:26:19.782  4609  4680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 13:26:19.782  4609  4680 D BluetoothAdapterProperties: Setting state to 10
11-25 13:26:19.782  4609  4680 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-25 13:26:19.782  4609  4680 I BluetoothAdapterState: Entering OffState
11-25 13:26:19.783   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 13:26:19.789  4609  4609 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 13:26:19.789  4609  4609 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 13:26:19.790  4609  4609 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 13:26:19.791  4609  4681 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 13:26:19.800  4609  4609 I art     : System.exit called, status: 0
11-25 13:26:19.800  4609  4609 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 13:26:19.821   924  3753 I ActivityManager: Process com.android.bluetooth (pid 4609) has died
,11-25 13:26:19.878   924   941 D Tethering: InitialState.processMessage what=4
,11-25 13:26:19.883   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 13:26:20.538   507   918 D TetherController: Setting IP forward enable = 0
,11-25 13:26:24.410   924  3113 D WifiService: setWifiEnabled: true pid=5556, uid=10077
,11-25 13:26:24.411   924  3113 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-25 13:26:24.422   507   918 D SoftapController: Softap fwReload - Ok
,11-25 13:26:24.430   507   918 D CommandListener: Setting iface cfg
,11-25 13:26:24.431   507   918 D CommandListener: Trying to bring down wlan0
11-25 13:26:24.433   507   918 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:26:24.439   924  2901 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 13:26:24.666   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:25.022   924  2901 D wifi    : set interface wlan0 flags (UP)
,11-25 13:26:25.026   924  2901 I WifiHAL : Initializing wifi
11-25 13:26:25.027   924  2901 I WifiHAL : Creating socket
,11-25 13:26:25.030   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 13:26:25.034   924  2901 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 13:26:25.034   924  2901 D wifi    : Did set static halHandle = 0x7f5f4e0680
11-25 13:26:25.034   924  2901 D wifi    : halHandle = 0x7f5f4e0680, mVM = 0x7f7bb0d140, mCls = 0x1902
11-25 13:26:25.036   924  2901 D wifi    : array field set
11-25 13:26:25.036   924  2901 I WifiNative-HAL: interface[0] = wlan0
,11-25 13:26:25.038   924  5691 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547059795584
11-25 13:26:25.039   924  5691 D wifi    : waitForHalEvents called, vm = 0x7f7bb0d140, obj = 0x1902, env = 0x7f62f3a580
,11-25 13:26:25.126  5692  5692 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 13:26:25.140   924  2901 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 13:26:25.147  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:26:25.209  5692  5692 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:26:25.243  5692  5692 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:26:25.243  5692  5692 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 13:26:25.281  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:25.282  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:26:25.282  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:26:25.282  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:26:25.283   924  2901 D WifiConfigStore: Loading config and enabling all networks 
,11-25 13:26:25.316   924  2901 D WifiConfigStore: loaded 0 passpoint configs
,11-25 13:26:25.317   924  2901 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 13:26:25.318   924  2901 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 13:26:25.319   924  2901 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 13:26:25.320   924  2901 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-25 13:26:25.320   924  2901 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-25 13:26:25.322   924  2901 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 13:26:25.322   924  2901 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 13:26:25.322   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 13:26:25.322   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 13:26:25.322   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 13:26:25.322   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 13:26:25.322   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 13:26:25.327  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:26:25.328   924  2901 D WifiNative-HAL: Setting external_sim to 1
,11-25 13:26:25.329   924  2901 D wifi    : setting dfs flag to true, 0x7f5ec223e0
11-25 13:26:25.329   924  2901 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 13:26:25.329   924  2901 D wifi    : setting scan oui 0x7f5ec223e0
11-25 13:26:25.330   924  2901 D WifiHAL : Sending mac address OUI
,11-25 13:26:25.333   924  2901 E native  : do suspend false
,11-25 13:26:25.340   924  2901 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 13:26:25.340   924   924 D RttService: SCAN_AVAILABLE : 3
,11-25 13:26:25.340   507   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 13:26:25.340   924  3010 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-25 13:26:25.341   507   918 D CommandListener: Setting iface cfg
,11-25 13:26:25.345   924  2900 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-25 13:26:25.345   924  2900 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 13:26:25.354   924  2900 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 13:26:25.354   924  2900 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 13:26:25.361   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=229836 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-25 13:26:25.667   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:26.669   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:27.669   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:28.379  5692  5692 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:26:28.433   924  2901 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 13:26:28.434   924  2901 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 13:26:28.434   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:26:28.446   924  2901 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 13:26:28.480   924  2901 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 13:26:28.486  5692  5692 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 13:26:28.670   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:28.909  5692  5692 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 13:26:28.943  5692  5692 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 13:26:28.944  5692  5692 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 13:26:28.954   924  2901 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:26:28.954   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 13:26:28.954   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 13:26:28.973   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:26:28.986   507   918 D CommandListener: Setting iface cfg
,11-25 13:26:28.992   924  2901 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 13:26:28.998   924  5698 D DhcpClient: Receive thread started
,11-25 13:26:29.003   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:26:29.003   924  2901 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 13:26:29.003   924  2903 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 13:26:29.085   924  2901 E native  : do suspend false
,11-25 13:26:29.101   924  5697 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 13:26:29.119   924  5698 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172607, domain null
,11-25 13:26:29.120   924  5697 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172607 seconds
11-25 13:26:29.122   924  5697 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 13:26:29.142   924  5698 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 13:26:29.143   924  5697 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 13:26:29.147   507   918 D CommandListener: Setting iface cfg
,11-25 13:26:29.151   924  2901 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 13:26:29.156   924  5697 D DhcpClient: Scheduling renewal in 86399s
,11-25 13:26:29.170   924  2901 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 13:26:29.172   924  2901 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 13:26:29.173   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 13:26:29.180   924  2901 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-25 13:26:29.181   924  2903 D ConnectivityService: Adding iface wlan0 to network 101
,11-25 13:26:29.230   924  2903 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 13:26:29.230   924  2903 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 13:26:29.234   924  2903 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 13:26:29.236   924  2903 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 13:26:29.239   924  2903 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 13:26:29.247   924  2903 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:26:29.253   924  2903 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-25 13:26:29.253   924  2903 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-25 13:26:29.253   924  2903 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 13:26:29.253   924  2901 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 13:26:29.253   924  2903 D ConnectivityService:    accepting network in place of null
11-25 13:26:29.253   924  2901 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:26:29.254   924  2903 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:26:29.270   924  5696 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233745, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:26:29.282   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:26:29.304   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:26:29.307   924  2903 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 13:26:29.308   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:26:29.308  3673  3801 W QCNEJ   : |CORE| network available: 101
,11-25 13:26:29.310  3673  3801 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 13:26:29.310   924  2903 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-25 13:26:29.312  3673  3801 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 13:26:29.312  3673  3801 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 13:26:29.313   924   941 D Tethering: MasterInitialState.processMessage what=3
,11-25 13:26:29.316  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:26:29.316  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:26:29.316  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:26:29.316  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:26:29.324  4982  5004 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 13:26:29.324  4982  5004 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:26:29.324  4982  5004 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 13:26:29.324  4982  5004 E SarControlService: no key has been found,reset the power
11-25 13:26:29.324  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:26:29.324  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:26:29.324  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:26:29.325  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:26:29.325  5007  5007 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:26:29.330  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-25 13:26:29.333  3910  3910 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:26:29.337  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000ec03000000000000ffffffff]
,11-25 13:26:29.337  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:26:29.337  5007  5021 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 13:26:29.337  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:26:29.337  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:26:29.338  3889  3889 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 13:26:29.339  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 13:26:29.339  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-25 13:26:29.339  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:26:29.339  5007  5007 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:26:29.342  3910  3910 D SystemUpdateService: onCreate
11-25 13:26:29.343  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000ed03000000000000ffffffff]
11-25 13:26:29.343  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:26:29.343  5007  5021 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-25 13:26:29.344  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:26:29.344   924  5695 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 13:26:29.344  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:26:29.350   924  3699 I ActivityManager: Start proc 5710:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-25 13:26:29.354  3910  3910 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:26:29.367  3910  3910 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 13:26:29.374  3910  5338 I iu.UploadsManager: num queued entries: 0
,11-25 13:26:29.374  3910  5338 I iu.UploadsManager: num updated entries: 0
11-25 13:26:29.375  3910  5338 I iu.SyncManager: NEXT; no task
11-25 13:26:29.375  3910  5720 I SystemUpdateService: active receiver: enabled
,11-25 13:26:29.378  3910  3910 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:26:29.380  3910  3910 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:26:29.382  5657  5657 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:26:29.386  5657  5657 D SprintDMHelper: simOperator: 
11-25 13:26:29.386  5657  5657 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:26:29.397  5710  5710 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-25 13:26:29.404  3910  5720 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:26:29.404   924  5695 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:26:29 GMT], X-Android-Received-Millis=[1480076789403], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480076789380]}
11-25 13:26:29.404   924  2903 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 13:26:29.404   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-25 13:26:29.405   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-25 13:26:29.406   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-25 13:26:29.416  3910  5720 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 13:26:29.416  3910  5720 I SystemUpdateService: now status is 0 (complete)
11-25 13:26:29.416  3910  5720 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:26:29.417  3910  5720 I SystemUpdateService: file has been verified
11-25 13:26:29.417  3910  5720 I SystemUpdateService: OTA package size = 21989297
,11-25 13:26:29.419   924  3758 D WifiService: setWifiEnabled: false pid=5556, uid=10077
11-25 13:26:29.419   924  3758 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:26:29.421   924  2901 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-25 13:26:29.422   924  2901 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 13:26:29.422   924  2901 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:26:29.422   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:26:29.423  3910  5720 I SystemUpdateService: showing system update notification
,11-25 13:26:29.429   924  5697 D DhcpClient: Clearing IP address
,11-25 13:26:29.429   507   918 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:26:29.432   507   918 D CommandListener: Setting iface cfg
11-25 13:26:29.435   924   924 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:26:29.436  3910  3910 D SystemUpdateService: onDestroy
11-25 13:26:29.440   924   934 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-25 13:26:29.440   924  5695 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-25 13:26:29.442   924  5695 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 13:26:29.447   924  5695 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-25 13:26:29.448   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
11-25 13:26:29.448   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:26:29.449   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 13:26:29.449   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 13:26:29.449   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-25 13:26:29.453   924   924 D RttService: SCAN_AVAILABLE : 1
,11-25 13:26:29.453   924  3010 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 13:26:29.453   538   538 E Parcel  : Reading a NULL string not supported here.
11-25 13:26:29.455   924  2903 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-25 13:26:29.456  3673  3801 W QCNEJ   : |CORE| network lost: 101
11-25 13:26:29.457  3673  3801 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 13:26:29.458   924  2901 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 13:26:29.461   924  2901 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:26:29.465   924  5698 D DhcpClient: Receive thread stopped
,11-25 13:26:29.479   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:26:29.489  5710  5732 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-25 13:26:29.501   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:26:29.501   507   918 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:26:29.502   924  2903 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 13:26:29.503   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:26:29.504   924   941 D Tethering: MasterInitialState.processMessage what=3
11-25 13:26:29.506   924  2901 D DhcpClient: doQuit
11-25 13:26:29.506   924  2901 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 13:26:29.506   924  5697 D DhcpClient: onQuitting
,11-25 13:26:29.507  5692  5692 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 13:26:29.508  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:29.508  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:26:29.508  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:26:29.508  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:26:29.509  3889  3889 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 13:26:29.512  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:26:29.516  3910  3910 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:26:29.517  4982  5004 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:26:29.517  4982  5004 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:26:29.517  4982  5004 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-25 13:26:29.517  4982  5004 E SarControlService: no key has been found,reset the power
,11-25 13:26:29.521  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:26:29.521  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:26:29.521  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:26:29.522  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 13:26:29.522  5007  5007 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:26:29.523  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:26:29.523  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 13:26:29.523  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:26:29.524  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:26:29.524  5007  5007 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:26:29.525  3910  3910 D SystemUpdateService: onCreate
11-25 13:26:29.528  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000ee03000000000000ffffffff]
11-25 13:26:29.528  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:26:29.528  5007  5021 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 13:26:29.529  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000ef03000000000000ffffffff]
11-25 13:26:29.529  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:26:29.529  5007  5021 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 13:26:29.529  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:26:29.530  5692  5692 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:26:29.530  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:26:29.530  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:26:29.530  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 13:26:29.531  3910  3910 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:26:29.536  5692  5692 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 13:26:29.538  3910  5752 I SystemUpdateService: active receiver: enabled
,11-25 13:26:29.540  3910  3910 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 13:26:29.547  3910  3910 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:26:29.549  3910  3910 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:26:29.550  5657  5657 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:26:29.556  5657  5657 D SprintDMHelper: simOperator: 
,11-25 13:26:29.556  5657  5657 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 13:26:29.557  3910  5338 I iu.UploadsManager: num queued entries: 0
11-25 13:26:29.560  5710  5732 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-25 13:26:29.562  3910  5752 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:26:29.566  3910  5338 I iu.UploadsManager: num updated entries: 0
,11-25 13:26:29.567  3910  5338 I iu.SyncManager: NEXT; no task
,11-25 13:26:29.569   507   918 E Netd    : netlink response contains error (No such file or directory)
11-25 13:26:29.570  3910  5752 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-25 13:26:29.570  3910  5752 I SystemUpdateService: now status is 0 (complete)
11-25 13:26:29.570   924  2903 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 13:26:29.570  3910  5752 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:26:29.570  3910  5752 I SystemUpdateService: file has been verified
11-25 13:26:29.570  3910  5752 I SystemUpdateService: OTA package size = 21989297
,11-25 13:26:29.574  5692  5692 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 13:26:29.586  3910  5752 I SystemUpdateService: showing system update notification
,11-25 13:26:29.588  5692  5692 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:26:29.589  5710  5732 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-25 13:26:29.594   924   924 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-25 13:26:29.595  3910  3910 D SystemUpdateService: onDestroy
,11-25 13:26:29.609  5710  5710 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-25 13:26:29.618  5759  5759 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1515517348.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1515517348.dex
,11-25 13:26:29.651  5759  5759 I dex2oat : dex2oat took 33.920ms (threads: 2) arena alloc=159KB java alloc=37KB native alloc=1257KB free=1302KB
,11-25 13:26:29.671   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 13:26:29.693   924  2901 D wifi    : In wifi stop Hal
,11-25 13:26:29.693   924  2901 D wifi    : halHandle = 0x7f5f4e0680, mVM = 0x7f7bb0d140, mCls = 0x1902
11-25 13:26:29.693   924  5691 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 13:26:29.693   924  5691 D WifiHAL : Got a signal to exit!!!
11-25 13:26:29.693   924  5691 I WifiHAL : Exit wifi_event_loop
11-25 13:26:29.694   924  2901 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 13:26:29.694   924  2901 E WifiHAL : Event processing terminated
11-25 13:26:29.694   924  2901 D wifi    : In wifi cleaned up handler
11-25 13:26:29.694   924  2901 I WifiHAL : Internal cleanup completed
11-25 13:26:29.694  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:26:29.697  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:29.699  4055  4185 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:26:29.699  5710  5710 W InstanceID/Rpc: Found 10012
,11-25 13:26:29.717   924  5691 D wifi    : set interface wlan0 flags (DOWN)
,11-25 13:26:29.717   924  2901 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 13:26:29.921   924   941 D Tethering: InitialState.processMessage what=4
,11-25 13:26:29.924   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 13:26:30.309   924  2903 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 13:26:34.413  4957  5727 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-25 13:26:34.413  4957  5727 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 13:26:34.415  4957  5727 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 13:26:34.418   924  3697 I ActivityManager: Killing 5418:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-25 13:26:34.464   924   941 I ActivityManager: Start proc 5813:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 13:26:34.518  5813  5813 D AdapterServiceConfig: Adding HeadsetService
,11-25 13:26:34.518  5813  5813 D AdapterServiceConfig: Adding A2dpService
11-25 13:26:34.518  5813  5813 D AdapterServiceConfig: Adding HidService
11-25 13:26:34.518  5813  5813 D AdapterServiceConfig: Adding HealthService
11-25 13:26:34.518  5813  5813 D AdapterServiceConfig: Adding PanService
11-25 13:26:34.519  5813  5813 D AdapterServiceConfig: Adding GattService
11-25 13:26:34.519  5813  5813 D AdapterServiceConfig: Adding BluetoothMapService
11-25 13:26:34.519  5813  5813 D AdapterServiceConfig: Adding SapService
,11-25 13:26:34.526   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@686c304:true
,11-25 13:26:34.526  5813  5813 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 13:26:34.527  5813  5813 I bt_bluedroid: init
11-25 13:26:34.528  5813  5825 I BluetoothAdapterState: Entering OffState
,11-25 13:26:34.529  5813  5826 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-25 13:26:34.529  5813  5826 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 13:26:34.529  5813  5826 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 13:26:34.529  5813  5826 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-25 13:26:34.530  5813  5813 I bt_bluedroid: get_profile_interface socket
11-25 13:26:34.531  5813  5813 I bt_bluedroid: get_profile_interface sdp
,11-25 13:26:34.531  5813  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 13:26:34.532  5813  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:26:34.534  5813  5824 I bt_bluedroid: config_hci_snoop_log
,11-25 13:26:34.535   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 13:26:34.539  5813  5825 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 13:26:34.539  5813  5825 D BluetoothAdapterProperties: Setting state to 14
11-25 13:26:34.539  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-25 13:26:34.541  5813  5825 D BluetoothBondStateMachine: make
,11-25 13:26:34.542  5813  5830 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 13:26:34.544  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:26:34.545  5813  5813 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 13:26:34.546  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:34.547  5813  5813 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:26:34.547  5813  5813 D BtGatt.GattService: Received start request. Starting profile...
11-25 13:26:34.547  5813  5813 D BtGatt.GattService: start()
11-25 13:26:34.547  5813  5813 I bt_bluedroid: get_profile_interface gatt
11-25 13:26:34.548  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:34.548  5813  5813 D BtGatt.AdvertiseManager: advertise manager created
,11-25 13:26:34.551  5813  5813 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:26:34.551  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:34.551  5813  5813 V BluetoothAdapterState: isBleTurningOn()=true
11-25 13:26:34.551  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:34.551  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-25 13:26:34.552  5813  5825 I bt_bluedroid: bt_bluedroid
11-25 13:26:34.552  5813  5826 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 13:26:34.553  5813  5826 I bt_hci  : start_up
,11-25 13:26:34.557  5813  5826 I bt_vendor: alloc value 0xf41bf871
11-25 13:26:34.557  5813  5826 I bt_vendor: init
11-25 13:26:34.557  5813  5826 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 13:26:34.557  5813  5826 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 13:26:34.668  5813  5826 D bt_hci  : start_up starting async portion
,11-25 13:26:34.669  5813  5833 I bt_hci  : event_finish_startup
11-25 13:26:34.669  5813  5833 I bt_hci_h4: hal_open
11-25 13:26:34.669  5813  5833 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 13:26:34.672   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:34.672  5813  5833 I bt_userial_vendor: device fd = 54 open
,11-25 13:26:34.668  5834  5834 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:26:34.686  5813  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:26:34.689  5813  5833 D bt_hwcfg: Chipset BCM4358A3
,11-25 13:26:34.689  5813  5833 D bt_hwcfg: Target name = [BCM4358A3]
11-25 13:26:34.689  5813  5833 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 13:26:35.091  5813  5833 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 13:26:35.091  5813  5833 D bt_hwcfg: Settlement delay -- 100 ms
11-25 13:26:35.091  5813  5833 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 13:26:35.225  5813  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-25 13:26:35.226  5813  5833 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-25 13:26:35.228  5813  5833 I bt_hwcfg: vendor lib fwcfg completed
11-25 13:26:35.228  5813  5833 I bt_vendor: firmware callback
11-25 13:26:35.228  5813  5833 I bt_hci  : firmware_config_callback
,11-25 13:26:35.236  5813  5836 I bt_btu  : btu_task pending for preload complete event
,11-25 13:26:35.236  5813  5836 I bt_btu_task: Bluetooth chip preload is complete
,11-25 13:26:35.236  5813  5836 I bt_btu  : btu_task received preload complete event
,11-25 13:26:35.242  5813  5836 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 13:26:35.243  5813  5836 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 13:26:35.243  5813  5836 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 13:26:35.243  5813  5836 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 13:26:35.243  5813  5836 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 13:26:35.243  5813  5836 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 13:26:35.243  5813  5836 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_SDP
,11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 13:26:35.244  5813  5836 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 13:26:35.329  5813  5836 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf413d549
11-25 13:26:35.329  5813  5836 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf413d549 
,11-25 13:26:35.343  5813  5829 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 13:26:35.344  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:26:35.345  5813  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:26:35.348  5813  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:26:35.351  5813  5829 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:26:35.351  5813  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:26:35.352  5813  5829 D bt_hci  : do_postload posting postload work item
11-25 13:26:35.352  5813  5833 I bt_hci  : event_postload
,11-25 13:26:35.352  5813  5833 I bt_vendor: sco_config_cb
11-25 13:26:35.352  5813  5833 I bt_hci  : sco_config_callback postload finished.
,11-25 13:26:35.358  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:26:35.359  5813  5829 D bt_bte_conf: Device ID record 1 : primary
,11-25 13:26:35.360  5813  5833 I bt_vendor: low_power_mode_cb
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   vendorId            = 000f
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   vendorIdSource      = 0001
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   product             = 1200
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   version             = 1436
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   clientExecutableURL = 
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   serviceDescription  = 
11-25 13:26:35.360  5813  5829 D bt_bte_conf:   documentationURL    = 
,11-25 13:26:35.360  5813  5829 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 13:26:35.361  5813  5826 D bt_stack_manager: event_start_up_stack finished
11-25 13:26:35.361  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 13:26:35.362  5813  5825 D BluetoothAdapterProperties: Setting state to 15
11-25 13:26:35.362  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 13:26:35.364  5813  5825 I BluetoothAdapterState: Entering BleOnState
,11-25 13:26:35.366  5813  5825 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 13:26:35.366  5813  5825 D BluetoothAdapterProperties: Setting state to 11
,11-25 13:26:35.366  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 13:26:35.370  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:35.371  5813  5813 D HeadsetService: Received start request. Starting profile...
11-25 13:26:35.374  5813  5813 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 13:26:35.374  5813  5813 D HeadsetStateMachine: make
,11-25 13:26:35.375  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:26:35.389  5813  5813 D HeadsetStateMachine: max_hf_connections = 1
,11-25 13:26:35.389  5813  5813 I bt_bluedroid: get_profile_interface handsfree
11-25 13:26:35.390  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 13:26:35.390  5813  5829 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-25 13:26:35.393  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:26:35.394  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:35.395  5813  5813 D A2dpService: Received start request. Starting profile...
11-25 13:26:35.396  5813  5813 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-25 13:26:35.396  5813  5813 I bt_bluedroid: get_profile_interface avrcp
,11-25 13:26:35.403  5813  5813 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 13:26:35.403  5813  5813 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 13:26:35.403  5813  5813 D A2dpStateMachine: make
11-25 13:26:35.404  5813  5813 I bt_bluedroid: get_profile_interface a2dp
,11-25 13:26:35.405  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-25 13:26:35.406  5813  5844 D A2dpStateMachine: Enter Disconnected: -2
11-25 13:26:35.408  5813  5813 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 13:26:35.409  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:35.410  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:26:35.411  5813  5813 D HidService: Received start request. Starting profile...
,11-25 13:26:35.411  5813  5813 I bt_bluedroid: get_profile_interface hidhost
,11-25 13:26:35.411  5813  5813 D HidService: setHidService(): set to: null
11-25 13:26:35.411  5813  5829 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf411e56d
11-25 13:26:35.411  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 13:26:35.413  5622  5622 D BluetoothInputDevice: Proxy object connected
11-25 13:26:35.413  5813  5813 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 13:26:35.414  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:35.414  5622  5622 D HidProfile: Bluetooth service connected
11-25 13:26:35.415  5813  5813 D HealthService: Received start request. Starting profile...
11-25 13:26:35.416  5813  5813 I bt_bluedroid: get_profile_interface health
11-25 13:26:35.417  5813  5813 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 13:26:35.418  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:35.420  5813  5813 D PanService: Received start request. Starting profile...
,11-25 13:26:35.420  5622  5622 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:26:35.420  5813  5813 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 13:26:35.420  5813  5813 I bt_bluedroid: get_profile_interface pan
11-25 13:26:35.420  5622  5622 D PanProfile: Bluetooth service connected
11-25 13:26:35.420  5813  5829 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 13:26:35.423  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:35.425  5813  5813 D BluetoothMapService: Received start request. Starting profile...
,11-25 13:26:35.426  5813  5813 D BluetoothMapService: start()
11-25 13:26:35.429  5813  5813 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 13:26:35.430  5813  5813 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 13:26:35.430  5813  5813 D BluetoothMapAppObserver: createReceiver()
11-25 13:26:35.431  5813  5813 D BluetoothMapAppObserver: initObservers()
11-25 13:26:35.431  5813  5813 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 13:26:35.437  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:35.437  5813  5813 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:35.437  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:26:35.437  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:35.438  5813  5813 V SapService: SapBinder()
,11-25 13:26:35.438  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:35.439  5813  5813 D SapService: Received start request. Starting profile...
11-25 13:26:35.439  5813  5813 V SapService: start()
11-25 13:26:35.440  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:35.440  5813  5813 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:35.440  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:35.440  5813  5842 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 13:26:35.440  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:35.440  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:35.441  5813  5813 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:35.442  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:35.442  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:35.442  5813  5813 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:26:35.443  5813  5813 V BluetoothAdapterState: isTurningOn()=true
,11-25 13:26:35.443  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:35.443  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:35.444  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:35.444  5813  5813 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:35.444  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:35.445  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:35.445  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 13:26:35.445  5813  5825 D BluetoothAdapterProperties: ScanMode =  20
11-25 13:26:35.445  5813  5825 D BluetoothAdapterProperties: State =  11
,11-25 13:26:35.446  5622  5622 D BluetoothMap: Proxy object connected
,11-25 13:26:35.447  5813  5829 D BluetoothAdapterProperties: Scan Mode:21
,11-25 13:26:35.447  5622  5622 D MapProfile: Bluetooth service connected
11-25 13:26:35.447  5813  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:26:35.447  5622  5622 D BluetoothMap: getConnectedDevices()
11-25 13:26:35.447  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 13:26:35.448  5813  5825 D BluetoothAdapterProperties: Setting state to 12
11-25 13:26:35.448  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 13:26:35.448  5622  5622 D BluetoothMap: Bluetooth is Not enabled
11-25 13:26:35.448  5622  5635 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:26:35.449  3059  3086 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:26:35.449  5813  5825 I BluetoothAdapterState: Entering OnState
11-25 13:26:35.450  3059  3059 D BluetoothMap: Proxy object connected
11-25 13:26:35.451  3709  3941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:35.451  3059  3059 D MapProfile: Bluetooth service connected
11-25 13:26:35.451  3059  3059 D BluetoothMap: getConnectedDevices()
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:35.451  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:26:35.451  5622  5640 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:26:35.452   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:26:35.453  3059  3937 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:26:35.453  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:26:35.453   924   924 D BluetoothA2dp: Proxy object connected
11-25 13:26:35.454  3059  3059 D BluetoothA2dp: Proxy object connected
11-25 13:26:35.454  3059  3933 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:26:35.456   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:35.456   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:35.456  3059  3086 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:26:35.457  5813  5813 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:26:35.457  3059  3059 D BluetoothInputDevice: Proxy object connected
11-25 13:26:35.457  5622  5635 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:26:35.457  3059  3059 D HidProfile: Bluetooth service connected
,11-25 13:26:35.457  5813  5813 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 13:26:35.459  5813  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:26:35.459  5622  5640 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:26:35.459  3059  3937 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:35.460   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:35.460  3059  3079 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:26:35.460  5813  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:26:35.461  5813  5813 D ObexServerSockets: Succeed to create listening sockets 
11-25 13:26:35.461  5813  5813 D ObexServerSockets0: startAccept()
11-25 13:26:35.461  5813  5813 D ObexServerSockets0: prepareForNewConnect()
11-25 13:26:35.461  3059  3059 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:26:35.461  3059  3059 D PanProfile: Bluetooth service connected
11-25 13:26:35.463  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 13:26:35.463  5813  5813 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 13:26:35.463  5813  5813 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 13:26:35.463  5813  5813 D BluetoothMapService: onReceive
11-25 13:26:35.463  5813  5813 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:26:35.463  5813  5813 D BluetoothMapService: STATE_ON
11-25 13:26:35.464   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 13:26:35.464  5813  5851 D ObexServerSockets0: Accepting socket connection...
,11-25 13:26:35.465  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:35.465  5813  5850 D ObexServerSockets0: Accepting socket connection...
11-25 13:26:35.465  5622  5622 D LocalBluetoothProfileManager: Adding local A2DP profile
11-25 13:26:35.466  5813  5852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:26:35.468  5813  5852 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 13:26:35.468  5813  5852 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 13:26:35.470  5622  5622 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 13:26:35.477  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:26:35.479  5622  5622 D BluetoothA2dp: Proxy object connected
,11-25 13:26:35.484  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:26:35.489  5622  5622 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:26:35.490  5622  5622 D BluetoothPbap: Proxy object connected
11-25 13:26:35.491  5813  5813 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:26:35.491  5813  5813 D ObexServerSockets0: prepareForNewConnect()
11-25 13:26:35.491  3059  3059 D BluetoothPbap: Proxy object connected
11-25 13:26:35.491  3059  3059 D PbapServerProfile: Bluetooth service connected
11-25 13:26:35.492  5622  5622 D PbapServerProfile: Bluetooth service connected
,11-25 13:26:35.498  5813  5857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:26:35.514  5813  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:26:35.515  5813  5861 I BtOppRfcommListener: Accept thread started.
,11-25 13:26:35.553   924   924 D BluetoothHeadset: Proxy object connected
,11-25 13:26:35.553  3709  3738 D BluetoothHeadset: Proxy object connected
11-25 13:26:35.553   924   924 D BluetoothHeadset: Proxy object connected
11-25 13:26:35.553  3059  3933 D BluetoothHeadset: Proxy object connected
11-25 13:26:35.553  3059  3059 D HeadsetProfile: Bluetooth service connected
11-25 13:26:35.554   924   924 D BluetoothHeadset: Proxy object connected
11-25 13:26:35.555   924   941 D BluetoothHeadset: Proxy object connected
11-25 13:26:35.556   924   941 D BluetoothHeadset: Proxy object connected
,11-25 13:26:35.560  3059  3086 D BluetoothHeadset: Proxy object connected
,11-25 13:26:35.560  3059  3059 D HeadsetProfile: Bluetooth service connected
11-25 13:26:35.560   924   941 D BluetoothHeadset: Proxy object connected
,11-25 13:26:35.573  5622  5640 D BluetoothHeadset: Proxy object connected
11-25 13:26:35.575  5622  5622 D HeadsetProfile: Bluetooth service connected
,11-25 13:26:35.673   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:36.674   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:37.260   924  2903 D ConnectivityService: handlePromptUnvalidated 101
,11-25 13:26:37.671  3616  3788 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-25 13:26:37.671  3616  3788 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-25 13:26:37.675   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:37.698  3502  3502 I ConfigService: onCreate
,11-25 13:26:38.676   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:39.464  5813  5825 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 13:26:39.464  5813  5825 D BluetoothAdapterProperties: Setting state to 13
11-25 13:26:39.464  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 13:26:39.466  5813  5825 D BluetoothAdapterProperties: onBluetoothDisable()
,11-25 13:26:39.467  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:26:39.471  5813  5813 D BluetoothMapService: onReceive
11-25 13:26:39.471  5813  5813 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:26:39.471  5813  5813 D BluetoothMapService: STATE_TURNING_OFF
11-25 13:26:39.472  5813  5813 D BluetoothMapService: MAP Service closeService in
,11-25 13:26:39.472  5813  5813 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 13:26:39.472  5813  5813 D ObexServerSockets0: shutdown(block = true)
11-25 13:26:39.474  5813  5813 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:26:39.474  5813  5813 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:26:39.474  5813  5851 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 13:26:39.474  5813  5850 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 13:26:39.476  5813  5838 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 13:26:39.477  5813  5829 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:26:39.478  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 13:26:39.481  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:26:39.482  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:39.483  5556  5556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:26:39.484  5556  5556 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:26:39.484  5556  5556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:26:39.485  5813  5813 I BtOppRfcommListener: stopping Accept Thread
11-25 13:26:39.486  5813  5861 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 13:26:39.486  5813  5861 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-25 13:26:39.489  5813  5813 D HeadsetService: Received stop request...Stopping profile...
,11-25 13:26:39.490   924   924 D BluetoothHeadset: Proxy object disconnected
,11-25 13:26:39.491  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:39.491  3709  4077 D BluetoothHeadset: Proxy object disconnected
11-25 13:26:39.492  5622  5635 D BluetoothHeadset: Proxy object disconnected
11-25 13:26:39.493   924   924 D BluetoothHeadset: Proxy object disconnected
,11-25 13:26:39.493  3059  3933 D BluetoothHeadset: Proxy object disconnected
11-25 13:26:39.493   924   924 D BluetoothHeadset: Proxy object disconnected
11-25 13:26:39.495  5813  5813 D A2dpService: Received stop request...Stopping profile...
11-25 13:26:39.495  5813  5844 D A2dpStateMachine: Exit Disconnected: -1
11-25 13:26:39.496  5622  5622 D DockEventReceiver: finishStartingService: stopping service
11-25 13:26:39.497  5622  5622 D HeadsetProfile: Bluetooth service disconnected
11-25 13:26:39.497   924   924 D BluetoothA2dp: Proxy object disconnected
11-25 13:26:39.498  5622  5622 D BluetoothA2dp: Proxy object disconnected
,11-25 13:26:39.501  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:26:39.502  5813  5813 D HidService: Received stop request...Stopping profile...
11-25 13:26:39.503  5813  5813 D HidService: Stopping Bluetooth HidService
11-25 13:26:39.504  5622  5622 D BluetoothInputDevice: Proxy object disconnected
11-25 13:26:39.504  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.504  5622  5622 D HidProfile: Bluetooth service disconnected
11-25 13:26:39.504  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.504  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.504  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:39.507  5813  5813 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-25 13:26:39.507  5813  5813 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 13:26:39.507  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:39.507  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:39.507  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 13:26:39.508  5813  5813 D HealthService: Received stop request...Stopping profile...
,11-25 13:26:39.508  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 13:26:39.509  5813  5829 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 13:26:39.509  3059  3059 D HeadsetProfile: Bluetooth service disconnected
11-25 13:26:39.509  3059  3059 D BluetoothA2dp: Proxy object disconnected
11-25 13:26:39.509  3059  3059 D BluetoothInputDevice: Proxy object disconnected
11-25 13:26:39.509  3059  3059 D HidProfile: Bluetooth service disconnected
,11-25 13:26:39.513  5813  5813 D PanService: Received stop request...Stopping profile...
11-25 13:26:39.514  3059  3059 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:26:39.514  5813  5813 D BluetoothMapService: Received stop request...Stopping profile...
11-25 13:26:39.514  3059  3059 D PanProfile: Bluetooth service disconnected
11-25 13:26:39.514  5813  5813 D BluetoothMapService: stop()
,11-25 13:26:39.514  5813  5813 D BluetoothMapAppObserver: deinitObservers()
11-25 13:26:39.515  5813  5813 D BluetoothMapAppObserver: removeReceiver()
,11-25 13:26:39.516  3059  3059 D BluetoothMap: Proxy object disconnected
11-25 13:26:39.516  3059  3059 D MapProfile: Bluetooth service disconnected
11-25 13:26:39.516  5813  5813 D SapService: Received stop request...Stopping profile...
11-25 13:26:39.516  5622  5622 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:26:39.516  5813  5813 V SapService: stop()
11-25 13:26:39.516  5622  5622 D PanProfile: Bluetooth service disconnected
11-25 13:26:39.516  5622  5622 D BluetoothMap: Proxy object disconnected
11-25 13:26:39.516  5622  5622 D MapProfile: Bluetooth service disconnected
11-25 13:26:39.518  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.519  5813  5813 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:26:39.519  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.519  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:39.520  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:39.520  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:39.520  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 13:26:39.520  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:26:39.520  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 13:26:39.520  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:26:39.520  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 13:26:39.523  5622  5622 D BluetoothPbap: Proxy object disconnected
11-25 13:26:39.523  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.523  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.523  5622  5622 D PbapServerProfile: Bluetooth service disconnected
11-25 13:26:39.523  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.524  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:39.524  5813  5813 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 13:26:39.524  5813  5813 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 13:26:39.524  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:26:39.524  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.524  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.524  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.524  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:39.525  5813  5813 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 13:26:39.525  5813  5829 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 13:26:39.525  5813  5813 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 13:26:39.525  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.525  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.525  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.525  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:39.525  3059  3059 D BluetoothPbap: Proxy object disconnected
,11-25 13:26:39.526  3059  3059 D PbapServerProfile: Bluetooth service disconnected
11-25 13:26:39.526  5813  5813 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 13:26:39.526  5813  5813 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 13:26:39.526  5813  5813 D BluetoothMapService: MAP Service closeService in
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:39.527  5813  5813 D BluetoothMapService: cleanup()
11-25 13:26:39.527  5813  5813 D BluetoothMapService: MAP Service closeService in
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isTurningOff()=true
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.527  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:39.527  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 13:26:39.527  5813  5825 D BluetoothAdapterProperties: Setting state to 15
11-25 13:26:39.527  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 13:26:39.528  5813  5825 I BluetoothAdapterState: Entering BleOnState
,11-25 13:26:39.531  5622  5640 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-25 13:26:39.533  3059  3933 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:26:39.533  3709  3728 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:39.533  5622  5635 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:26:39.534   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:26:39.534  5622  5640 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:39.534  5622  5635 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 13:26:39.536  3059  3086 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:26:39.536  3059  3934 D BluetoothPbap: onBluetoothStateChange: up=false
,11-25 13:26:39.537   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:26:39.537   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:39.537  3059  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:26:39.538  5622  5640 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:26:39.539  5622  5635 D BluetoothPan: onBluetoothStateChange on: false
,11-25 13:26:39.539  3059  3079 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:26:39.540   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:26:39.540  3059  3933 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:26:39.541  5813  5825 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 13:26:39.541  5813  5825 D BluetoothAdapterProperties: Setting state to 16
11-25 13:26:39.541  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 13:26:39.541  5813  5825 D BluetoothAdapterProperties: onBleDisable
11-25 13:26:39.542  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:26:39.542  5813  5826 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 13:26:39.542  5813  5829 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:26:39.543  5813  5836 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 13:26:39.543  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:26:39.543  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:39.545  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:39.549  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:26:39.556  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:26:39.558  5622  5622 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:26:39.676   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 13:26:39.757  5813  5829 I bt_hci  : shut_down
,11-25 13:26:39.767  5813  5833 D bt_hwcfg: hw_epilog_process
,11-25 13:26:39.768  5813  5833 I bt_vendor: low_power_mode_cb
,11-25 13:26:39.770  5813  5833 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 13:26:39.771  5813  5833 I bt_vendor: epilog_cb
11-25 13:26:39.771  5813  5833 I bt_hci  : epilog_finished_callback
,11-25 13:26:39.776  5813  5829 I bt_hci_h4: hal_close
,11-25 13:26:39.777  5813  5829 I bt_userial_vendor: device fd = 54 close
,11-25 13:26:39.901  5813  5826 D bt_stack_manager: event_shut_down_stack finished.
,11-25 13:26:39.902  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-25 13:26:39.906  5813  5825 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-25 13:26:39.908  5813  5813 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:26:39.909  5813  5813 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 13:26:39.910  5813  5813 D BtGatt.GattService: stop()
,11-25 13:26:39.910  5813  5813 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 13:26:39.913  5813  5813 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:39.914  5813  5813 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:39.914  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:39.914  5813  5813 V BluetoothAdapterState: isBleTurningOff()=true
,11-25 13:26:39.914  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-25 13:26:39.916  5813  5825 D BluetoothAdapterProperties: Setting state to 10
11-25 13:26:39.916  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 13:26:39.917  5813  5825 I BluetoothAdapterState: Entering OffState
,11-25 13:26:39.917   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 13:26:39.928  5813  5813 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 13:26:39.928  5813  5813 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-25 13:26:39.928  5813  5813 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 13:26:39.931  5813  5826 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 13:26:39.938  5813  5813 I art     : System.exit called, status: 0
,11-25 13:26:39.938  5813  5813 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 13:26:39.972   924  3529 I ActivityManager: Process com.android.bluetooth (pid 5813) has died
,11-25 13:26:42.727  3502  3502 I ConfigService: onDestroy
,11-25 13:26:44.461  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:44.461  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 13:26:44.467  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:26:44.467  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@864e7a2 removed from the list
11-25 13:26:44.468  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:44.470  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:26:44.470  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a90e569 added. We now have 4 listener(s)
,11-25 13:26:44.470  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:44.472  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:44.472  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a90e569 removed from the list
,11-25 13:26:44.472  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:26:44.474  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:26:44.474  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dcddbee added. We now have 4 listener(s)
11-25 13:26:44.475  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:49.485  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:26:49.515   924   941 I ActivityManager: Start proc 5872:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 13:26:49.602  5872  5872 D AdapterServiceConfig: Adding HeadsetService
,11-25 13:26:49.602  5872  5872 D AdapterServiceConfig: Adding A2dpService
,11-25 13:26:49.602  5872  5872 D AdapterServiceConfig: Adding HidService
,11-25 13:26:49.602  5872  5872 D AdapterServiceConfig: Adding HealthService
11-25 13:26:49.603  5872  5872 D AdapterServiceConfig: Adding PanService
11-25 13:26:49.603  5872  5872 D AdapterServiceConfig: Adding GattService
11-25 13:26:49.603  5872  5872 D AdapterServiceConfig: Adding BluetoothMapService
11-25 13:26:49.603  5872  5872 D AdapterServiceConfig: Adding SapService
,11-25 13:26:49.619   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f15a830:true
,11-25 13:26:49.619  5872  5872 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 13:26:49.623  5872  5872 I bt_bluedroid: init
,11-25 13:26:49.624  5872  5884 I BluetoothAdapterState: Entering OffState
,11-25 13:26:49.626  5872  5885 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-25 13:26:49.626  5872  5885 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 13:26:49.627  5872  5885 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 13:26:49.627  5872  5885 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-25 13:26:49.628  5872  5872 I bt_bluedroid: get_profile_interface socket
,11-25 13:26:49.629  5872  5888 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:26:49.631  5872  5888 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 13:26:49.631  5872  5872 I bt_bluedroid: get_profile_interface sdp
,11-25 13:26:49.637  5872  5883 I bt_bluedroid: config_hci_snoop_log
,11-25 13:26:49.638   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 13:26:49.643  5872  5884 D BluetoothAdapterState: Current state: OFF, message: 0
11-25 13:26:49.643  5872  5884 D BluetoothAdapterProperties: Setting state to 14
,11-25 13:26:49.643  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 13:26:49.645  5872  5884 D BluetoothBondStateMachine: make
,11-25 13:26:49.646  5872  5889 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 13:26:49.649  5872  5884 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:26:49.650  5872  5872 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 13:26:49.653  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:49.654  5872  5872 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:26:49.654  5872  5872 D BtGatt.GattService: Received start request. Starting profile...
11-25 13:26:49.654  5872  5872 D BtGatt.GattService: start()
11-25 13:26:49.654  5872  5872 I bt_bluedroid: get_profile_interface gatt
,11-25 13:26:49.656  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:49.656  5872  5872 D BtGatt.AdvertiseManager: advertise manager created
,11-25 13:26:49.661  5872  5872 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:26:49.661  5872  5872 V BluetoothAdapterState: isTurningOn()=false
11-25 13:26:49.662  5872  5872 V BluetoothAdapterState: isBleTurningOn()=true
11-25 13:26:49.662  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:49.662  5872  5884 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 13:26:49.664  5872  5884 I bt_bluedroid: bt_bluedroid
11-25 13:26:49.664  5872  5885 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 13:26:49.664  5872  5885 I bt_hci  : start_up
,11-25 13:26:49.670  5872  5885 I bt_vendor: alloc value 0xf41bf871
,11-25 13:26:49.670  5872  5885 I bt_vendor: init
11-25 13:26:49.670  5872  5885 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 13:26:49.670  5872  5885 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 13:26:49.677   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:49.782  5872  5885 D bt_hci  : start_up starting async portion
,11-25 13:26:49.783  5872  5892 I bt_hci  : event_finish_startup
,11-25 13:26:49.783  5872  5892 I bt_hci_h4: hal_open
11-25 13:26:49.783  5872  5892 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 13:26:49.785  5893  5893 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-25 13:26:49.786  5872  5892 I bt_userial_vendor: device fd = 54 open
,11-25 13:26:49.803  5872  5892 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:26:49.806  5872  5892 D bt_hwcfg: Chipset BCM4358A3
,11-25 13:26:49.806  5872  5892 D bt_hwcfg: Target name = [BCM4358A3]
11-25 13:26:49.807  5872  5892 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 13:26:50.306  5872  5892 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 13:26:50.306  5872  5892 D bt_hwcfg: Settlement delay -- 100 ms
11-25 13:26:50.306  5872  5892 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 13:26:50.440  5872  5892 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:26:50.441  5872  5892 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-25 13:26:50.442  5872  5892 I bt_hwcfg: vendor lib fwcfg completed
,11-25 13:26:50.442  5872  5892 I bt_vendor: firmware callback
11-25 13:26:50.442  5872  5892 I bt_hci  : firmware_config_callback
,11-25 13:26:50.453  5872  5895 I bt_btu  : btu_task pending for preload complete event
,11-25 13:26:50.453  5872  5895 I bt_btu_task: Bluetooth chip preload is complete
,11-25 13:26:50.453  5872  5895 I bt_btu  : btu_task received preload complete event
,11-25 13:26:50.460  5872  5895 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 13:26:50.460  5872  5895 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 13:26:50.460  5872  5895 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 13:26:50.460  5872  5895 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_GAP
,11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 13:26:50.461  5872  5895 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 13:26:50.462  5872  5895 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 13:26:50.462  5872  5895 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 13:26:50.462  5872  5895 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-25 13:26:50.462  5872  5895 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 13:26:50.557  5872  5895 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf413d549
11-25 13:26:50.557  5872  5895 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf413d549 
,11-25 13:26:50.583  5872  5888 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 13:26:50.586  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:26:50.587  5872  5888 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:26:50.590  5872  5888 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 13:26:50.594  5872  5888 D BluetoothAdapterProperties: Scan Mode:20
,11-25 13:26:50.594  5872  5888 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:26:50.594  5872  5888 D bt_hci  : do_postload posting postload work item
11-25 13:26:50.594  5872  5892 I bt_hci  : event_postload
11-25 13:26:50.594  5872  5892 I bt_vendor: sco_config_cb
,11-25 13:26:50.595  5872  5892 I bt_hci  : sco_config_callback postload finished.
11-25 13:26:50.597  5872  5888 D bt_bte_conf: Device ID record 1 : primary
11-25 13:26:50.597  5872  5888 D bt_bte_conf:   vendorId            = 000f
11-25 13:26:50.597  5872  5888 D bt_bte_conf:   vendorIdSource      = 0001
11-25 13:26:50.597  5872  5888 D bt_bte_conf:   product             = 1200
11-25 13:26:50.597  5872  5888 D bt_bte_conf:   version             = 1436
11-25 13:26:50.598  5872  5888 D bt_bte_conf:   clientExecutableURL = 
11-25 13:26:50.598  5872  5888 D bt_bte_conf:   serviceDescription  = 
11-25 13:26:50.598  5872  5888 D bt_bte_conf:   documentationURL    = 
11-25 13:26:50.598  5872  5888 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-25 13:26:50.598  5872  5885 D bt_stack_manager: event_start_up_stack finished
11-25 13:26:50.599  5872  5884 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 13:26:50.599  5872  5884 D BluetoothAdapterProperties: Setting state to 15
11-25 13:26:50.599  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-25 13:26:50.601  5872  5884 I BluetoothAdapterState: Entering BleOnState
,11-25 13:26:50.603  5872  5892 I bt_vendor: low_power_mode_cb
,11-25 13:26:50.605  5872  5884 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 13:26:50.605  5872  5884 D BluetoothAdapterProperties: Setting state to 11
,11-25 13:26:50.605  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 13:26:50.611  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:50.612  5872  5872 D HeadsetService: Received start request. Starting profile...
11-25 13:26:50.614  5872  5872 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 13:26:50.615  5872  5872 D HeadsetStateMachine: make
,11-25 13:26:50.627  5872  5884 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:26:50.627  5872  5872 D HeadsetStateMachine: max_hf_connections = 1
,11-25 13:26:50.628  5872  5872 I bt_bluedroid: get_profile_interface handsfree
11-25 13:26:50.628  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 13:26:50.628  5872  5888 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 13:26:50.634  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:50.635  5872  5872 D A2dpService: Received start request. Starting profile...
,11-25 13:26:50.636  5872  5872 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 13:26:50.637  5872  5872 I bt_bluedroid: get_profile_interface avrcp
,11-25 13:26:50.643  5872  5872 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 13:26:50.643  5872  5872 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 13:26:50.643  5872  5872 D A2dpStateMachine: make
,11-25 13:26:50.645  5872  5872 I bt_bluedroid: get_profile_interface a2dp
,11-25 13:26:50.649  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 13:26:50.650  5872  5903 D A2dpStateMachine: Enter Disconnected: -2
,11-25 13:26:50.650  5872  5872 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 13:26:50.651  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:50.652  5872  5872 D HidService: Received start request. Starting profile...
11-25 13:26:50.652  5872  5872 I bt_bluedroid: get_profile_interface hidhost
11-25 13:26:50.652  5872  5872 D HidService: setHidService(): set to: null
,11-25 13:26:50.653  5872  5872 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 13:26:50.653  5872  5888 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf411e56d
11-25 13:26:50.653  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 13:26:50.653  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:50.654  5872  5872 D HealthService: Received start request. Starting profile...
,11-25 13:26:50.658  5872  5872 I bt_bluedroid: get_profile_interface health
,11-25 13:26:50.661  5872  5872 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 13:26:50.662  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:26:50.662  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
11-25 13:26:50.663  5872  5872 D PanService: Received start request. Starting profile...
11-25 13:26:50.663  5872  5872 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 13:26:50.663  5872  5872 I bt_bluedroid: get_profile_interface pan
11-25 13:26:50.665  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:50.666  5872  5872 D BluetoothMapService: Received start request. Starting profile...
,11-25 13:26:50.666  5872  5872 D BluetoothMapService: start()
11-25 13:26:50.669  5872  5872 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 13:26:50.670  5872  5872 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 13:26:50.670  5872  5872 D BluetoothMapAppObserver: createReceiver()
11-25 13:26:50.671  5872  5872 D BluetoothMapAppObserver: initObservers()
11-25 13:26:50.671  5872  5872 D BluetoothMapAppObserver: getEnabledAccountItems()
11-25 13:26:50.671  5872  5888 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 13:26:50.677   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:50.683  5872  5872 V SapService: SapBinder()
11-25 13:26:50.683  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:26:50.684  5872  5872 D SapService: Received start request. Starting profile...
11-25 13:26:50.684  5872  5872 V SapService: start()
,11-25 13:26:50.686  5872  5872 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:26:50.686  5872  5872 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:50.686  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.686  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:50.686  5872  5872 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:50.686  5872  5872 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:50.687  5872  5900 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isTurningOn()=true
,11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.687  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:50.688  5872  5872 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:26:50.688  5872  5872 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:50.688  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.688  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:50.688  5872  5872 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:26:50.688  5872  5872 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:50.689  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.689  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:26:50.689  5872  5872 V BluetoothAdapterState: isTurningOff()=false
11-25 13:26:50.689  5872  5872 V BluetoothAdapterState: isTurningOn()=true
11-25 13:26:50.690  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:26:50.690  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:26:50.690  5872  5884 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 13:26:50.690  5872  5884 D BluetoothAdapterProperties: ScanMode =  20
11-25 13:26:50.690  5872  5884 D BluetoothAdapterProperties: State =  11
11-25 13:26:50.690  5872  5884 D BluetoothAdapterProperties: Setting state to 12
11-25 13:26:50.691  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-25 13:26:50.691  5872  5884 I BluetoothAdapterState: Entering OnState
11-25 13:26:50.691  5622  5640 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:26:50.691  5872  5888 D BluetoothAdapterProperties: Scan Mode:21
11-25 13:26:50.691  5872  5888 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 13:26:50.693  3059  3086 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 13:26:50.696  3709  3941 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 13:26:50.696  5622  5640 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:26:50.696  3059  3059 D BluetoothMap: Proxy object connected
11-25 13:26:50.696  3059  3059 D MapProfile: Bluetooth service connected
11-25 13:26:50.697  3059  3059 D BluetoothMap: getConnectedDevices()
,11-25 13:26:50.699   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:26:50.699  5872  5872 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:26:50.699  5622  5635 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:50.700  5872  5872 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 13:26:50.700  5622  5640 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:26:50.701  5872  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:26:50.701  3059  3933 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:26:50.702  5872  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:26:50.703  3059  3937 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:26:50.703  5872  5872 D ObexServerSockets: Succeed to create listening sockets 
11-25 13:26:50.703  5872  5872 D ObexServerSockets0: startAccept()
11-25 13:26:50.703  5872  5872 D ObexServerSockets0: prepareForNewConnect()
11-25 13:26:50.704   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:50.704   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:50.704  3059  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:26:50.705  5872  5872 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 13:26:50.705  5872  5872 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 13:26:50.705  5622  5622 D BluetoothInputDevice: Proxy object connected
11-25 13:26:50.705  5622  5622 D HidProfile: Bluetooth service connected
,11-25 13:26:50.705  5872  5909 D ObexServerSockets0: Accepting socket connection...
11-25 13:26:50.706  3059  3059 D BluetoothInputDevice: Proxy object connected
11-25 13:26:50.706  3059  3059 D HidProfile: Bluetooth service connected
11-25 13:26:50.706  5872  5910 D ObexServerSockets0: Accepting socket connection...
11-25 13:26:50.706  5622  5635 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:26:50.706   924   924 D BluetoothA2dp: Proxy object connected
11-25 13:26:50.709  5622  5640 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:26:50.709  3059  3059 D BluetoothA2dp: Proxy object connected
11-25 13:26:50.710  3059  3937 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 13:26:50.711   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:26:50.711  3059  3086 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:26:50.713  3059  3059 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:26:50.713  3059  3059 D PanProfile: Bluetooth service connected
11-25 13:26:50.713   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 13:26:50.714  5872  5872 D BluetoothMapService: onReceive
11-25 13:26:50.714  5872  5872 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:26:50.714  5872  5872 D BluetoothMapService: STATE_ON
11-25 13:26:50.716  5872  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:26:50.716  5622  5622 D BluetoothMap: Proxy object connected
11-25 13:26:50.716  5622  5622 D MapProfile: Bluetooth service connected
11-25 13:26:50.716  5622  5622 D BluetoothMap: getConnectedDevices()
,11-25 13:26:50.718  5622  5622 D BluetoothA2dp: Proxy object connected
11-25 13:26:50.718  5872  5912 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 13:26:50.718  5872  5912 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 13:26:50.720  5622  5622 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:26:50.720  5622  5622 D PanProfile: Bluetooth service connected
,11-25 13:26:50.724  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:26:50.730  3502  3502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:26:50.730  5622  5622 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:26:50.736  5622  5622 D BluetoothPbap: Proxy object connected
11-25 13:26:50.736  5622  5622 D PbapServerProfile: Bluetooth service connected
,11-25 13:26:50.737  5872  5872 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:26:50.737  5872  5872 D ObexServerSockets0: prepareForNewConnect()
,11-25 13:26:50.743  5872  5916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:26:50.744  3059  3059 D BluetoothPbap: Proxy object connected
11-25 13:26:50.745  3059  3059 D PbapServerProfile: Bluetooth service connected
,11-25 13:26:50.762  5872  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:26:50.764  5872  5920 I BtOppRfcommListener: Accept thread started.
,11-25 13:26:50.798   924   924 D BluetoothHeadset: Proxy object connected
,11-25 13:26:50.798  3709  3738 D BluetoothHeadset: Proxy object connected
11-25 13:26:50.799  5622  5908 D BluetoothHeadset: Proxy object connected
11-25 13:26:50.799   924   924 D BluetoothHeadset: Proxy object connected
,11-25 13:26:50.799  3059  3934 D BluetoothHeadset: Proxy object connected
,11-25 13:26:50.800  5622  5640 D BluetoothHeadset: Proxy object connected
11-25 13:26:50.800  3059  3059 D HeadsetProfile: Bluetooth service connected
11-25 13:26:50.800   924   924 D BluetoothHeadset: Proxy object connected
11-25 13:26:50.801  5622  5622 D HeadsetProfile: Bluetooth service connected
,11-25 13:26:50.803  5622  5622 D HeadsetProfile: Bluetooth service connected
,11-25 13:26:50.805   924   941 D BluetoothHeadset: Proxy object connected
11-25 13:26:50.805   924   941 D BluetoothHeadset: Proxy object connected
,11-25 13:26:50.812  3059  3933 D BluetoothHeadset: Proxy object connected
11-25 13:26:50.813  3059  3059 D HeadsetProfile: Bluetooth service connected
11-25 13:26:50.813   924   941 D BluetoothHeadset: Proxy object connected
,11-25 13:26:51.678   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:52.679   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:53.680   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:26:54.502  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:26:54.509  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:26:54.510  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:26:54.510  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dcddbee removed from the list
11-25 13:26:54.510  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:26:54.513  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:26:54.515  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bd588f added. We now have 4 listener(s)
11-25 13:26:54.516  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:26:54.520   924  3699 D WifiService: setWifiEnabled: false pid=5556, uid=10077
11-25 13:26:54.520   924  3699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:26:54.681   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 13:26:59.532  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:26:59.533   924  3732 D WifiService: setWifiEnabled: true pid=5556, uid=10077
11-25 13:26:59.533   924  3732 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:26:59.540   507   918 D SoftapController: Softap fwReload - Ok
,11-25 13:26:59.545   507   918 D CommandListener: Setting iface cfg
,11-25 13:26:59.546   507   918 D CommandListener: Trying to bring down wlan0
11-25 13:26:59.547   507   918 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:26:59.554   924  2901 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 13:27:00.193   924  2901 D wifi    : set interface wlan0 flags (UP)
,11-25 13:27:00.193   924  2901 I WifiHAL : Initializing wifi
11-25 13:27:00.193   924  2901 I WifiHAL : Creating socket
,11-25 13:27:00.199   924  2901 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 13:27:00.199   924  2901 D wifi    : Did set static halHandle = 0x7f5f4e0680
,11-25 13:27:00.199   924  2901 D wifi    : halHandle = 0x7f5f4e0680, mVM = 0x7f7bb0d140, mCls = 0x1015ee
11-25 13:27:00.199   924  2901 D wifi    : array field set
11-25 13:27:00.200   924  2901 I WifiNative-HAL: interface[0] = wlan0
11-25 13:27:00.203   924  5926 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547059795584
11-25 13:27:00.204   924  5926 D wifi    : waitForHalEvents called, vm = 0x7f7bb0d140, obj = 0x1015ee, env = 0x7f71014880
11-25 13:27:00.204   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 13:27:00.267  5927  5927 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 13:27:00.308   924  2901 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 13:27:00.341  5927  5927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:27:00.406  5927  5927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:27:00.406  5927  5927 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 13:27:00.451   924  2901 D WifiConfigStore: Loading config and enabling all networks 
,11-25 13:27:00.486   924  2901 D WifiConfigStore: loaded 0 passpoint configs
,11-25 13:27:00.487   924  2901 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 13:27:00.488   924  2901 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 13:27:00.488   924  2901 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 13:27:00.489   924  2901 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 13:27:00.490   924  2901 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-25 13:27:00.491   924  2901 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 13:27:00.491   924  2901 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 13:27:00.492   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 13:27:00.492   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 13:27:00.492   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 13:27:00.492   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 13:27:00.492   924  2901 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 13:27:00.497  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:27:00.497   924  2901 D WifiNative-HAL: Setting external_sim to 1
11-25 13:27:00.498   924  2901 D wifi    : setting dfs flag to true, 0x7f5ec227a0
,11-25 13:27:00.498   924  2901 D WifiStateMachine: Setting OUI to DA-A1-19
,11-25 13:27:00.499   924  2901 D wifi    : setting scan oui 0x7f5ec227a0
11-25 13:27:00.499   924  2901 D WifiHAL : Sending mac address OUI
,11-25 13:27:00.504   924  2901 E native  : do suspend false
,11-25 13:27:00.514   924  2901 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-25 13:27:00.514   924   924 D RttService: SCAN_AVAILABLE : 3
11-25 13:27:00.514   507   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 13:27:00.515   924  3010 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-25 13:27:00.516   507   918 D CommandListener: Setting iface cfg
,11-25 13:27:00.521   924  2900 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-25 13:27:00.521   924  2900 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 13:27:00.531   924  2900 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 13:27:00.531   924  2900 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 13:27:00.538   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=265013 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-25 13:27:03.586  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:27:03.592  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:27:03.600  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:27:03.653   924  2901 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 13:27:03.654   924  2901 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 13:27:03.655   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:27:03.671   924  2901 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 13:27:03.711   924  2901 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 13:27:03.718  5927  5927 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 13:27:04.201  5927  5927 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 13:27:04.237  5927  5927 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 13:27:04.239  5927  5927 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 13:27:04.247   924  2901 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-25 13:27:04.247   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:27:04.247   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 13:27:04.267   924  2901 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:27:04.280   507   918 D CommandListener: Setting iface cfg
,11-25 13:27:04.286   924  2901 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 13:27:04.295   924  5932 D DhcpClient: Receive thread started
,11-25 13:27:04.300   924  2901 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-25 13:27:04.301   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 13:27:04.301   924  2903 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 13:27:04.390   924  2901 E native  : do suspend false
,11-25 13:27:04.414   924  5931 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 13:27:04.428   924  5932 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-25 13:27:04.429   924  5931 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-25 13:27:04.431   924  5931 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 13:27:04.451   924  5932 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 13:27:04.452   924  5931 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 13:27:04.455   507   918 D CommandListener: Setting iface cfg
,11-25 13:27:04.460   924  2901 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 13:27:04.466   924  5931 D DhcpClient: Scheduling renewal in 86399s
,11-25 13:27:04.483   924  2901 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 13:27:04.486   924  2901 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 13:27:04.487   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 13:27:04.489   924  2903 D ConnectivityService: Adding iface wlan0 to network 102
11-25 13:27:04.492   924  2901 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 13:27:04.539   924  2903 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 13:27:04.539   924  2903 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:27:04.546  5556  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:27:04.552  5556  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:27:04.558  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.543   924  2903 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-25 13:27:04.558  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bd588f removed from the list
11-25 13:27:04.558  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:27:04.563   924  2903 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 13:27:04.563  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-25 13:27:04.564  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-25 13:27:04.564   924  2903 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-25 13:27:04.566  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6300133 Bundle[{}]
11-25 13:27:04.567  5556  5603 I io.jxcore.node.LifeCycleMonitor: start: OK
11-25 13:27:04.567  5556  5603 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-25 13:27:04.568  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-25 13:27:04.572  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-25 13:27:04.572   924  2903 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 13:27:04.572  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-25 13:27:04.573  5556  5603 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-25 13:27:04.576   924  2903 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-25 13:27:04.577   924  2903 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-25 13:27:04.577   924  2903 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-25 13:27:04.577   924  2903 D ConnectivityService:    accepting network in place of null
11-25 13:27:04.577   924  2901 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 13:27:04.577   924  2901 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:27:04.577   924  2903 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:27:04.580  5556  5603 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-25 13:27:04.580  5556  5603 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 13:27:04.580  5556  5603 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-25 13:27:04.583  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 13:27:04.583  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c34771c added. We now have 3 listener(s)
11-25 13:27:04.584  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.584  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.584  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.584  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.584  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a496f25 added. We now have 4 listener(s)
11-25 13:27:04.584  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:27:04.585  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:27:04.586  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.586  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfc8fa added. We now have 4 listener(s)
,11-25 13:27:04.587  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.588  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.588  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.588  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.588  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@840eeab added. We now have 5 listener(s)
11-25 13:27:04.588  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:27:04.589  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:27:04.589  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:27:04.589  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:27:04.589  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.589  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.589  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.589  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c34771c removed from the list
11-25 13:27:04.589  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.589  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a496f25 removed from the list
11-25 13:27:04.590  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:27:04.590  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.590  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.591  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.591  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.591  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.592  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.592  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.592  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.592  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a496f25 not in the list
11-25 13:27:04.592  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.592  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.593  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.593  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.593  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.593  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.594  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.594  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.594  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@840eeab removed from the list
11-25 13:27:04.594  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.594  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:27:04.594  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.594  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfc8fa removed from the list
11-25 13:27:04.595  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.595  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9fe908 added. We now have 3 listener(s)
,11-25 13:27:04.597  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.597  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.597  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.597  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.597  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@446d8a1 added. We now have 4 listener(s)
11-25 13:27:04.598  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.598  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:27:04.599   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:27:04.599  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.599   924  5930 D NetlinkSocketObserver: NeighborEvent{elapsedMs=269074, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-25 13:27:04.599  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b17ac6 added. We now have 4 listener(s)
,11-25 13:27:04.601  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.601  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.601  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:27:04.601  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.601  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1dca87 added. We now have 5 listener(s)
11-25 13:27:04.602  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.602  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:04.602  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:27:04.602  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:27:04.602  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:27:04.602  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:27:04.603  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:27:04.606  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 13:27:04.606  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:27:04.606  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 13:27:04.609  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.609  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 13:27:04.610  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:27:04.610  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:27:04.610  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:27:04.614  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.614  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:27:04.614  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:27:04.614  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:27:04.614  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:27:04.614  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.615  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.617  5872  5883 D BtGatt.GattService: registerClient() - UUID=b42b71f6-6fe6-4dea-bcbd-8d97b0e57720
,11-25 13:27:04.618  5872  5888 D BtGatt.GattService: onClientRegistered() - UUID=b42b71f6-6fe6-4dea-bcbd-8d97b0e57720, clientIf=5
11-25 13:27:04.619   507   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:27:04.619  5556  5566 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:27:04.620  5872  5901 D BtGatt.GattService: start scan with filters
,11-25 13:27:04.622   924  2903 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-25 13:27:04.622   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 13:27:04.622  3673  3801 W QCNEJ   : |CORE| network available: 102
11-25 13:27:04.624   924  2903 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-25 13:27:04.624  3673  3801 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 13:27:04.626   924   941 D Tethering: MasterInitialState.processMessage what=3
11-25 13:27:04.627  3673  3801 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 13:27:04.627  3673  3801 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 13:27:04.628  5872  5891 D BtGatt.ScanManager: handling starting scan
,11-25 13:27:04.629  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:27:04.629  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.629  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:27:04.629  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.629  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:27:04.630  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:27:04.630  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.630  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:27:04.630  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:27:04.631  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:27:04.631  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.631  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.631  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.631  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.631  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.632  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.632  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.632  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.632  5556  5603 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 13:27:04.632  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:27:04.632  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.632  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:27:04.632  5872  5891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55fdc84
,11-25 13:27:04.636  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.636  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:27:04.636  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.636  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.636  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:27:04.641  5872  5888 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:27:04.641  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.641  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:27:04.641  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:27:04.641  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:27:04.641  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.642  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.642  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-25 13:27:04.642  5872  5891 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 13:27:04.642  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9fe908 removed from the list
11-25 13:27:04.642  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.642  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@446d8a1 removed from the list
11-25 13:27:04.642  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:27:04.642  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.642  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:27:04.642  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.642  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.642  3889  3889 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 13:27:04.643  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.643  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.643  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.643  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.643  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.644  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.644  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@446d8a1 not in the list
11-25 13:27:04.644  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.644  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:27:04.644  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.645  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.645  5872  5882 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:27:04.646  3910  3910 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:27:04.649  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 13:27:04.650  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:27:04.650  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.650  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.650  5872  5891 D BtGatt.ScanManager: Starting BLE batch scan
,11-25 13:27:04.650  5872  5891 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:27:04.651  5872  5911 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:27:04.651  4982  5004 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:27:04.652  4982  5004 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:27:04.652  4982  5004 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 13:27:04.652  4982  5004 E SarControlService: no key has been found,reset the power
11-25 13:27:04.652  5872  5883 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:27:04.652  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.652  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:27:04.652  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:27:04.653  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.653  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:27:04.653  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.653  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.653  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:27:04.653  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:27:04.654  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:27:04.654  5007  5007 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 13:27:04.654  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:27:04.655  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.656  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.656  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:27:04.656  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.656  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.656  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.656  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.656  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.656  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 13:27:04.656  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1dca87 removed from the list
,11-25 13:27:04.655  4982  5019 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-25 13:27:04.656  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.656  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:27:04.656  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.656  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.656  4982  5019 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 13:27:04.656  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:27:04.656  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b17ac6 removed from the list
11-25 13:27:04.656  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.657  4982  5019 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:27:04.657  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:27:04.657  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:27:04.657  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.657  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.657  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.657  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:27:04.657  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.657  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.657  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:27:04.657  5007  5007 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:27:04.657  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.657  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0d120 added. We now have 3 listener(s)
11-25 13:27:04.658  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.659  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.659  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.659  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.659  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.659  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.659  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.659  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f0fad9 added. We now have 4 listener(s)
11-25 13:27:04.659  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.660  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:27:04.661  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000f003000000000000ffffffff]
11-25 13:27:04.662  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:27:04.662  5007  5021 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-25 13:27:04.662  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.662  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:27:04.662  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9df1c9e added. We now have 4 listener(s)
11-25 13:27:04.662  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:27:04.663  3910  3910 D SystemUpdateService: onCreate
,11-25 13:27:04.663  5872  5888 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:27:04.663  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.663  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.663  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.663  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.663  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.664  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb837f added. We now have 5 listener(s)
11-25 13:27:04.664  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.664  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:04.664  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa7ae9f HexData = [00000000f103000000000000ffffffff]
11-25 13:27:04.664  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:27:04.664  5007  5021 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-25 13:27:04.664  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:04.664  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:27:04.664  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:27:04.664  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:27:04.665  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:27:04.665  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:27:04.665  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 13:27:04.668   924  5929 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 13:27:04.668  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:27:04.670  3910  3910 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 13:27:04.671  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 13:27:04.671  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.672  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:27:04.672  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:27:04.672  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:27:04.674  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:27:04.677  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.677  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:27:04.678  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 13:27:04.678  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:27:04.678  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:27:04.680  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:27:04.680  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.680  5872  5888 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:27:04.686  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.686  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:27:04.686  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:27:04.686  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-25 13:27:04.686  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-25 13:27:04.686  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.686  3910  5945 I SystemUpdateService: active receiver: enabled
11-25 13:27:04.687  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.688  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:27:04.688  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.688  5872  5891 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:27:04.690  5872  5882 D BtGatt.GattService: registerClient() - UUID=bc9d0f9a-4ef7-4410-a701-e8c2ff782198
,11-25 13:27:04.691  5872  5888 D BtGatt.GattService: onClientRegistered() - UUID=bc9d0f9a-4ef7-4410-a701-e8c2ff782198, clientIf=5
11-25 13:27:04.692  5556  5566 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:27:04.692  3910  5945 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:27:04.692  5872  5911 D BtGatt.GattService: start scan with filters
11-25 13:27:04.693  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:27:04.693  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.693  3910  5945 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 13:27:04.693  3910  5945 I SystemUpdateService: now status is 0 (complete)
11-25 13:27:04.694  3910  5945 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:27:04.694  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:27:04.694  3910  5945 I SystemUpdateService: file has been verified
11-25 13:27:04.694  3910  5945 I SystemUpdateService: OTA package size = 21989297
11-25 13:27:04.694  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:27:04.694  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.694  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:27:04.695  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.695  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:27:04.695  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:27:04.695  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.695  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:27:04.695  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:27:04.695  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.695  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.695  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.695  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.696  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-25 13:27:04.696  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.699  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.699  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:27:04.699  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.699  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.699  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:04.699  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.699  5556  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 13:27:04.699  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:27:04.699  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:27:04.700  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:27:04.700  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.700  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.700  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.700  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:27:04.700  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.700  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.700  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.700  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0d120 removed from the list
,11-25 13:27:04.700  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.700  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f0fad9 removed from the list
11-25 13:27:04.700  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:27:04.700  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.700  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.700  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.701  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.701  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:27:04.701  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.701  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.701  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.702  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.702  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.702  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.702  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:27:04.702  5872  5891 D BtGatt.ScanManager: handling starting scan
11-25 13:27:04.702  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.702  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.702  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.702  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:27:04.702  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.702  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.702  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f0fad9 not in the list
11-25 13:27:04.703  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.703  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:27:04.703  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.705  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.705  5872  5911 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:27:04.705  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:27:04.706  3910  5945 I SystemUpdateService: showing system update notification
11-25 13:27:04.706  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.706  5872  5901 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:27:04.707  5872  5882 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:27:04.707  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.708  5872  5888 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.708  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.708  5872  5891 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.708  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.709  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:27:04.709  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:27:04.709  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:27:04.710  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.711  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.711  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:27:04.711  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.711  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.711  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.711  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.711  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.711  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb837f removed from the list
11-25 13:27:04.711  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.711  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.711  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.711  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:27:04.711  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9df1c9e removed from the list
11-25 13:27:04.711  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:27:04.712  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-25 13:27:04.712  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.712  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:27:04.712  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.712  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:27:04.712  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a438 added. We now have 3 listener(s)
11-25 13:27:04.712  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.712  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.712  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.712  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:27:04.712  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.713  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.713  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:27:04.713  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.713  5872  5891 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:27:04.713  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.713  5872  5891 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:27:04.713  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.713  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.713  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.713  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d062c11 added. We now have 4 listener(s)
11-25 13:27:04.714  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.714  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.714  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.714  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.714  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:27:04.717  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.717  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3342176 added. We now have 4 listener(s)
11-25 13:27:04.717   924  5929 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:27:04 GMT], X-Android-Received-Millis=[1480076824716], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480076824694]}
11-25 13:27:04.718  3910  3910 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-25 13:27:04.718   924  2903 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 13:27:04.718   924  2903 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-25 13:27:04.718   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 13:27:04.718  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.719  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.719  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.719  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.719  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a86377 added. We now have 5 listener(s)
11-25 13:27:04.719  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.719  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:04.719  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:27:04.719  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:27:04.719   924  2903 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 13:27:04.719  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:27:04.719  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:27:04.721  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:27:04.725   924   924 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:27:04.725  3910  5338 I iu.UploadsManager: num queued entries: 0
,11-25 13:27:04.726  3910  3910 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 13:27:04.727  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:27:04.727  5556  5603 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 13:27:04.727  5872  5888 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:27:04.727  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:27:04.727  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.728  3910  3910 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:27:04.730  5657  5657 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 13:27:04.732  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.732  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:27:04.733  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:27:04.733  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:27:04.734  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:27:04.734  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:27:04.734  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.736  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:27:04.737  3910  3910 D SystemUpdateService: onDestroy
11-25 13:27:04.737  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.737  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:27:04.738  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-25 13:27:04.738  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:27:04.738  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:27:04.738  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.739  5657  5657 D SprintDMHelper: simOperator: 
11-25 13:27:04.739  5657  5657 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 13:27:04.739  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.742  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:27:04.742  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.742  5872  5888 E BtGatt.ContextMap: Context not found for ID 5
11-25 13:27:04.743  5872  5901 D BtGatt.GattService: registerClient() - UUID=574d0485-401c-415f-941a-ab531f8fc003
11-25 13:27:04.743  5872  5888 D BtGatt.GattService: onClientRegistered() - UUID=574d0485-401c-415f-941a-ab531f8fc003, clientIf=5
11-25 13:27:04.744  5556  5566 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:27:04.744  5872  5883 D BtGatt.GattService: start scan with filters
,11-25 13:27:04.747  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:27:04.747  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.747  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:27:04.748  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.748  3910  5338 I iu.UploadsManager: num updated entries: 0
11-25 13:27:04.748  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:27:04.748  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:27:04.748  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.748  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:27:04.748  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:27:04.748  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.748  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.748  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.749  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.749  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:27:04.749  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.751  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.751  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:27:04.751  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.752  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.752  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.754  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:27:04.754  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:27:04.754  5872  5891 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:27:04.756  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:27:04.756  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:27:04.756  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:27:04.756  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.756  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.756  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.756  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.756  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.757  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a438 removed from the list
11-25 13:27:04.757  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.757  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d062c11 removed from the list
11-25 13:27:04.757  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:27:04.757  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.757  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.757  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.757  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.757  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:27:04.757  5556  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:27:04.757  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:27:04.757  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.758  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.758  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 13:27:04.758  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.758  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:27:04.759  3910  5338 I iu.SyncManager: NEXT; no task
,11-25 13:27:04.759  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:27:04.759  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.759  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:27:04.760  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.760  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.760  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.760  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.760  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.760  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.760  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d062c11 not in the list
11-25 13:27:04.760  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.761  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:27:04.761  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.762  5556  5603 D BluetoothAdapter: STATE_ON
,11-25 13:27:04.763  5872  5911 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:27:04.763  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:27:04.764  5556  5603 D BluetoothAdapter: STATE_ON
11-25 13:27:04.764  5872  5901 D BtGatt.GattService: stopScan() - queue size =0
11-25 13:27:04.765  5872  5882 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:27:04.766  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:27:04.766  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.766  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:27:04.766  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.766  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.766  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.767  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:27:04.767  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.767  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.767  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:27:04.767  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.767  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.767  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.767  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:27:04.767  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:27:04.767  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:27:04.768  5872  5891 D BtGatt.ScanManager: handling starting scan
11-25 13:27:04.769  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.772  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.772  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:27:04.772  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.772  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.772  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.772  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.772  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.772  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a86377 removed from the list
11-25 13:27:04.772  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.772  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:27:04.772  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.772  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:27:04.772  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.772  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3342176 removed from the list
11-25 13:27:04.772  5556  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:27:04.772  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.773  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:27:04.773  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:27:04.773  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.773  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.773  5556  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.773  5556  5556 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:27:04.773  5556  5556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.773  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.773  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.773  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9ac250 added. We now have 3 listener(s)
11-25 13:27:04.774  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.774  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.774  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.774  5556  5603 V, org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.775  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f94c49 added. We now have 4 listener(s)
11-25 13:27:04.775  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.775  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:27:04.775  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.775  5556  5556 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:27:04.775  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:27:04.776  5872  5888 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:27:04.776  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.776  5872  5891 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:27:04.777  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:27:04.777  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd9e94e added. We now have 4 listener(s)
11-25 13:27:04.779  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:27:04.779  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:27:04.779  5556  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:27:04.779  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:27:04.779  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e324a6f added. We now have 5 listener(s)
11-25 13:27:04.779  5556  5603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:27:04.779  5556  5603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:27:04.779  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:27:04.779  5556  5603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:27:04.779  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.780  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.780  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.780  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9ac250 removed from the list
11-25 13:27:04.780  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.780  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f94c49 removed from the list
11-25 13:27:04.780  5556  5603 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:27:04.780  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.780  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.782  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 13:27:04.782  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.782  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.782  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.782  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.782  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.782  5556  5603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f94c49 not in the list
11-25 13:27:04.782  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.782  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.782  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:27:04.782  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.783  5872  5891 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:27:04.783  5872  5891 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 13:27:04.784  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.784  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.784  5556  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 13:27:04.784  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:27:04.784  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:27:04.784  5556  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:27:04.784  5556  5603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e324a6f removed from the list
11-25 13:27:04.784  5556  5603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:27:04.784  5556  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:27:04.784  5556  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:27:04.784  5556  5603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd9e94e removed from the list
11-25 13:27:04.785  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 13:27:04.785  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-25 13:27:04.785  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 13:27:04.785  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:04.785  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 13:27:04.785  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:27:04.791  5872  5888 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:27:04.791  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:27:04.796  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:27:04.796  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:27:04.797  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:27:04.801  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:27:04.802  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.802  5872  5888 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:27:04.807  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 13:27:04.807  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.807  5872  5891 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:27:04.812  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:27:04.812  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:27:04.812  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:27:04.817  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:27:04.818  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:27:04.841  4957  5952 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 13:27:05.158  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:27:05.213  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:27:05.274  5556  5556 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:27:06.938  5556  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:27:06.938  5556  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:07.320   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:27:07.725  5556  5958 W !!      : call onHalfStreamCopied
,11-25 13:27:07.725  5556  5958 I testCopyDataAndClose: closing input stream
,11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:27:08.503  5556  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 13:27:09.682   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:27:10.342   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:27:10.683   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:27:11.684   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:27:12.579   924  2903 D ConnectivityService: handlePromptUnvalidated 102
,11-25 13:27:12.685   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:27:12.879  5556  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:12.879  5556  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:13.687   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:27:14.688   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:27:14.879  5556  5603 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-25 13:27:14.879  5556  5603 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:27:14.879  5556  5603 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-25 13:27:15.015  5556  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:27:15.015  5556  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:15.062  5556  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 13:27:15.063  5556  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:15.063  5556  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,11-25 13:27:15.534   924  2901 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,11-25 13:27:16.385   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:27:16.618  5556  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 13:27:19.420   924  2903 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:27:21.072  5556  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:21.072  5556  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:21.072  5556  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:21.072  5556  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-25 13:27:21.073  5556  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 13:27:21.074  5556  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:21.074  5556  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-25 13:27:21.075  5556  5603 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-25 13:27:21.078  5556  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:21.078  5556  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:27:21.079  5556  5962 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-25 13:27:21.079  5556  5962 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:21.079  5556  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-25 13:27:21.079  5556  5962 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-25 13:27:21.080  5556  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:27:21.080  5556  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 13:27:21.085  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 13:27:21.085  5556  5603 I jxcore-log: 
11-25 13:27:21.085  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-25 13:27:21.085  5556  5603 I jxcore-log: 
11-25 13:27:21.085  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-25 13:27:21.085  5556  5603 I jxcore-log: 
11-25 13:27:21.086  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 13:27:21.086  5556  5603 I jxcore-log: 
11-25 13:27:21.086  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Total duration:  92149'
11-25 13:27:21.086  5556  5603 I jxcore-log: 
11-25 13:27:21.087  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Failures: 
11-25 13:27:21.087  5556  5603 I jxcore-log:  mCurrentOperation should not be null
11-25 13:27:21.087  5556  5603 I jxcore-log: Expected: is not null
11-25 13:27:21.087  5556  5603 I jxcore-log:      but: was null
11-25 13:27:21.087  5556  5603 I jxcore-log: '
11-25 13:27:21.087  5556  5603 I jxcore-log: 
,11-25 13:27:21.087  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-25 13:27:21.087  5556  5603 I jxcore-log: 
11-25 13:27:21.089  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 13:27:21.089  5556  5603 I jxcore-log: 
,11-25 13:27:21.091  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:27:21.091  5556  5603 I jxcore-log: 
11-25 13:27:21.092  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:27:21.092  5556  5603 I jxcore-log: 
11-25 13:27:21.093  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 13:27:21.093  5556  5603 I jxcore-log: 
11-25 13:27:21.093  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 13:27:21.093  5556  5603 I jxcore-log: 
,11-25 13:27:21.093  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.093  5556  5603 I jxcore-log: 
11-25 13:27:21.093  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:27:21.093  5556  5603 I jxcore-log: 
11-25 13:27:21.094  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.094  5556  5603 I jxcore-log: 
,11-25 13:27:21.094  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:27:21.094  5556  5603 I jxcore-log: 
11-25 13:27:21.094  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:27:21.094  5556  5603 I jxcore-log: 
11-25 13:27:21.095  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 13:27:21.095  5556  5603 I jxcore-log: 
11-25 13:27:21.095  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 13:27:21.095  5556  5603 I jxcore-log: 
11-25 13:27:21.095  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.095  5556  5603 I jxcore-log: 
,11-25 13:27:21.095  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:27:21.095  5556  5603 I jxcore-log: 
11-25 13:27:21.095  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.095  5556  5603 I jxcore-log: 
11-25 13:27:21.096  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:27:21.096  5556  5603 I jxcore-log: 
11-25 13:27:21.096  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.096  5556  5603 I jxcore-log: 
11-25 13:27:21.096  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:27:21.096  5556  5603 I jxcore-log: 
11-25 13:27:21.096  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:27:21.096  5556  5603 I jxcore-log: 
11-25 13:27:21.096  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:27:21.096  5556  5603 I jxcore-log: 
11-25 13:27:21.097  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:27:21.097  5556  5603 I jxcore-log: 
11-25 13:27:21.097  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:27:21.097  5556  5603 I jxcore-log: 
11-25 13:27:21.097  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:27:21.097  5556  5603 I jxcore-log: 
11-25 13:27:21.099  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 13:27:21.099  5556  5603 I jxcore-log: 
11-25 13:27:21.099  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:27:21.099  5556  5603 I jxcore-log: 
11-25 13:27:21.099  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 13:27:21.099  5556  5603 I jxcore-log: 
11-25 13:27:21.100  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-25 13:27:21.100  5556  5603 I jxcore-log: 
11-25 13:27:21.100  5556  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:27:21.100  5556  5603 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-25 13:27:21.100  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:27:21.100  5556  5603 I jxcore-log: 
,11-25 13:27:21.100  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.100  5556  5603 I jxcore-log: 
11-25 13:27:21.101  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:27:21.101  5556  5603 I jxcore-log: 
11-25 13:27:21.101  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.101  5556  5603 I jxcore-log: 
11-25 13:27:21.101  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:27:21.101  5556  5603 I jxcore-log: 
11-25 13:27:21.101  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:27:21.101  5556  5603 I jxcore-log: 
,11-25 13:27:21.104  5556  5556 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 13:27:21.104  5556  5556 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-25 13:27:21.106  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 13:27:21.106  5556  5603 I jxcore-log: 
,11-25 13:27:21.106  5556  5603 I jxcore-log: 2016-11-25 12:27:21 - WARN testUtils: 'myNameCallback not set!'
11-25 13:27:21.106  5556  5603 I jxcore-log: 
,11-25 13:27:23.173  5556  5603 I jxcore-log: 2016-11-25 12:27:23 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 13:27:23.173  5556  5603 I jxcore-log: 
,11-25 13:27:23.175  5556  5603 I jxcore-log: 2016-11-25 12:27:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 13:27:23.175  5556  5603 I jxcore-log: 
,11-25 13:27:23.522  5556  5603 I jxcore-log: 2016-11-25 12:27:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 13:27:23.522  5556  5603 I jxcore-log: 
,11-25 13:27:23.534  5556  5603 I jxcore-log: 2016-11-25 12:27:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 13:27:23.534  5556  5603 I jxcore-log: 
,11-25 13:27:24.653  5556  5603 I jxcore-log: 2016-11-25 12:27:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 13:27:24.653  5556  5603 I jxcore-log: 
,11-25 13:27:24.848  5556  5603 I jxcore-log: 2016-11-25 12:27:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 13:27:24.848  5556  5603 I jxcore-log: 
,11-25 13:27:24.853  5556  5603 I jxcore-log: 2016-11-25 12:27:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 13:27:24.853  5556  5603 I jxcore-log: 
,11-25 13:27:24.858  5556  5603 I jxcore-log: 2016-11-25 12:27:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 13:27:24.858  5556  5603 I jxcore-log: 
,11-25 13:27:25.339  5556  5603 I jxcore-log: 2016-11-25 12:27:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 13:27:25.339  5556  5603 I jxcore-log: 
,11-25 13:27:25.384  5556  5603 I jxcore-log: 2016-11-25 12:27:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 13:27:25.384  5556  5603 I jxcore-log: 
,11-25 13:27:25.398  5556  5603 I jxcore-log: 2016-11-25 12:27:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 13:27:25.398  5556  5603 I jxcore-log: 
,11-25 13:27:25.402  5556  5603 I jxcore-log: 2016-11-25 12:27:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 13:27:25.402  5556  5603 I jxcore-log: 
,11-25 13:27:25.675  5556  5603 I jxcore-log: 2016-11-25 12:27:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 13:27:25.675  5556  5603 I jxcore-log: 
,11-25 13:27:25.804  5556  5603 I jxcore-log: 2016-11-25 12:27:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 13:27:25.804  5556  5603 I jxcore-log: 
,11-25 13:27:26.170  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 13:27:26.170  5556  5603 I jxcore-log: 
,11-25 13:27:26.178  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 13:27:26.178  5556  5603 I jxcore-log: 
,11-25 13:27:26.182  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 13:27:26.182  5556  5603 I jxcore-log: 
,11-25 13:27:26.188  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 13:27:26.188  5556  5603 I jxcore-log: 
,11-25 13:27:26.193  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 13:27:26.193  5556  5603 I jxcore-log: 
,11-25 13:27:26.222  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 13:27:26.222  5556  5603 I jxcore-log: 
,11-25 13:27:26.256  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 13:27:26.256  5556  5603 I jxcore-log: 
,11-25 13:27:26.263  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 13:27:26.263  5556  5603 I jxcore-log: 
,11-25 13:27:26.269  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 13:27:26.269  5556  5603 I jxcore-log: 
,11-25 13:27:26.285  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 13:27:26.285  5556  5603 I jxcore-log: 
,11-25 13:27:26.300  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 13:27:26.300  5556  5603 I jxcore-log: 
,11-25 13:27:26.307  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 13:27:26.307  5556  5603 I jxcore-log: 
,11-25 13:27:26.312  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 13:27:26.312  5556  5603 I jxcore-log: 
,11-25 13:27:26.325  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 13:27:26.325  5556  5603 I jxcore-log: 
,11-25 13:27:26.342  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 13:27:26.342  5556  5603 I jxcore-log: 
,11-25 13:27:26.357  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 13:27:26.357  5556  5603 I jxcore-log: 
,11-25 13:27:26.368  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 13:27:26.368  5556  5603 I jxcore-log: 
,11-25 13:27:26.380  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 13:27:26.380  5556  5603 I jxcore-log: 
,11-25 13:27:26.391  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 13:27:26.391  5556  5603 I jxcore-log: 
,11-25 13:27:26.404  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 13:27:26.404  5556  5603 I jxcore-log: 
,11-25 13:27:26.414  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 13:27:26.414  5556  5603 I jxcore-log: 
,11-25 13:27:26.420  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 13:27:26.420  5556  5603 I jxcore-log: 
,11-25 13:27:26.443  5556  5603 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 13:27:26.444  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 13:27:26.444  5556  5603 I jxcore-log: 
,11-25 13:27:26.474  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 13:27:26.474  5556  5603 I jxcore-log: 
,11-25 13:27:26.679  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - DEBUG CoordinatedClient: 'connected to the test server'
11-25 13:27:26.679  5556  5603 I jxcore-log: 
,11-25 13:27:26.986  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-25 13:27:26.986  5556  5603 I jxcore-log: 
,11-25 13:27:26.989  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - DEBUG CoordinatedClient: 'test client failed'
11-25 13:27:26.989  5556  5603 I jxcore-log: 
,11-25 13:27:26.993  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-25 13:27:26.993  5556  5603 I jxcore-log: 
,11-25 13:27:26.999  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:190:20
11-25 13:27:26.999  5556  5603 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-25 13:27:26.999  5556  5603 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-25 13:27:26.999  5556  5603 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-25 13:27:26.999  5556  5603 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-25 13:27:26.999  5556  5603 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-25 13:27:26.999  5556  5603 I jxcore-log: 
,11-25 13:27:26.999  5556  5603 I jxcore-log: 2016-11-25 12:27:26 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 13:27:26.999  5556  5603 I jxcore-log: 
,11-25 13:27:27.536  5971  5971 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 13:27:27.542  5971  5971 D AndroidRuntime: CheckJNI is OFF
,11-25 13:27:27.570  5971  5971 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 13:27:27.605  5971  5971 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 13:27:27.623  5971  5971 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 13:27:27.633   924   937 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 13:27:27.634   924   937 I ActivityManager: Killing 5556:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 13:27:27.735   924  3758 D GraphicsStats: Buffer count: 2
11-25 13:27:27.736   924  3622 I WindowState: WIN DEATH: Window{538472e u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-25 13:27:27.736   924  2902 D WifiService: Client connection lost with reason: 4
,11-25 13:27:27.743   924   937 W ActivityManager: Force removing ActivityRecord{c7da9f7 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-25 13:27:27.784   924   947 I art     : Starting a blocking GC Explicit
,11-25 13:27:27.791   924  3362 W ActivityManager: Spurious death for ProcessRecord{5b59d12 0:com.test.thalitest/u0a77}, curProc for 5556: null
,11-25 13:27:27.823   924  3697 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5556 uid 10077
,11-25 13:27:27.821  3697  3697 W Binder_8: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[24179]" dev="sockfs" ino=24179 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:27:27.821  3697  3697 W Binder_8: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[24179]" dev="sockfs" ino=24179 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:27:27.824  3616  3616 I Keyboard.Facilitator: onFinishInput()
,11-25 13:27:27.848  3889  3889 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-25 13:27:27.881   924   947 I art     : Explicit concurrent mark sweep GC freed 53548(3MB) AllocSpace objects, 9(260KB) LOS objects, 33% free, 29MB/43MB, paused 1.754ms total 96.127ms
,11-25 13:27:27.898   924   947 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 13:27:27.900  5971  5971 I art     : System.exit called, status: 0
,11-25 13:27:27.900  5971  5971 I AndroidRuntime: VM exiting with result code 0.
,11-25 13:27:27.901  3889  5984 I MicroRecognitionRnrImpl: Starting detection.
,11-25 13:27:27.903  3889  5985 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@39c1cd5
,11-25 13:27:27.904   512  5987 I AudioFlinger: AudioFlinger's thread 0xf1d80000 ready to run
,11-25 13:27:27.909   512  2949 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 13:27:27.910  3889  5985 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@39c1cd5
,11-25 13:27:27.919   924   947 I ActivityManager: Start proc 5988:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-25 13:27:27.919   924   947 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 13:27:27.921   512  5987 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-25 13:27:27.921   512  5987 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-25 13:27:27.921   512  5987 I ACDB-LOADER: ACDB AFE returned = -19
,11-25 13:27:27.921   512  5987 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-25 13:27:27.921   512  5987 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-25 13:27:27.921   512  5987 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-25 13:27:27.926  5872  5872 D BluetoothMapAppObserver: onReceive
11-25 13:27:27.927  5872  5872 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-25 13:27:27.929   512  5987 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
11-25 13:27:27.930  4055  4113 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-25 13:27:27.935   924  2892 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 13:27:27.938  3616  3616 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-25 13:27:27.958  3709  3709 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 13:27:27.959  3616  6001 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 13:27:27.964  3616  6001 I Decoder : createOrResetDecoder
,11-25 13:27:27.986   924   924 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 13:27:28.005  3502  3502 I ConfigService: onCreate
,11-25 13:27:28.011    28    28 W kworker/1:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:27:28.018    28    28 W kworker/1:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:27:28.030  3502  3502 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM packages WHERE package_name = ? AND uid = ?] disk I/O error
,11-25 13:27:28.031  3502  3502 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-25 13:27:28.033  3502  3502 E AndroidRuntime: FATAL EXCEPTION: main
11-25 13:27:28.033  3502  3502 E AndroidRuntime: Process: com.google.process.gapps, PID: 3502
11-25 13:27:28.033  3502  3502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:130)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-25 13:27:28.033  3502  3502 E AndroidRuntime: 	... 8 more
,11-25 13:27:28.040  3741  3830 E SQLiteLog: (1546) os_unix.c:29096: (22) ftruncate(/data/user/0/com.google.android.googlequicksearchbox/databases/app_icons.db) - 
,11-25 13:27:28.042  3616  6001 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-25 13:27:28.048    28    28 W kworker/1:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:27:28.051  3348  6004 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 13:27:28.059   924  6010 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 13:27:28.055   405   405 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[36918]" dev="sockfs" ino=36918 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:27:28.055   405   405 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36918]" dev="sockfs" ino=36918 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:27:28.058   407   407 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[36039]" dev="sockfs" ino=36039 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:27:28.058   407   407 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[36039]" dev="sockfs" ino=36039 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:27:28.073   924  3113 I ActivityManager: Start proc 6011:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-25 13:27:28.074  3741  3830 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-25 13:27:28.074  3741  3830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3741
11-25 13:27:28.074  3741  3830 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1546)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:27:28.074  3741  3830 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:27:28.077   924  3699 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 13:27:28.080   924  6016 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:27:28.080   924  6016 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:27:28.080   924  6016 E DropBoxManagerService: 	... 5 more
11-25 13:27:28.081  3889  3909 W SearchService: Abort, client detached.
,11-25 13:27:28.084  3889  4114 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@39c1cd5
,11-25 13:27:28.084  3889  5985 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-25 13:27:28.085  3889  3889 I HotwordDetector: Closing mic
,11-25 13:27:28.102   924  6010 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 13:27:28.102   924  6010 I Adreno  : Build Date                       : 12/06/15
11-25 13:27:28.102   924  6010 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 13:27:28.102   924  6010 I Adreno  : Local Branch                     : mybranch17112971
11-25 13:27:28.102   924  6010 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 13:27:28.102   924  6010 I Adreno  : Remote Branch                    : NONE
11-25 13:27:28.102   924  6010 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 13:27:28.108  3348  6004 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-25 13:27:28.114   924  6010 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 13:27:28.119  3348  6004 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-25 13:27:28.119  3348  6004 E AndroidRuntime: Process: android.process.acore, PID: 3348
11-25 13:27:28.119  3348  6004 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:27:28.119  3348  6004 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:27:28.122   924  6024 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:27:28.122   924  6024 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:27:28.122   924  6024 E DropBoxManagerService: 	... 5 more
,11-25 13:27:28.144   512  5987 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-25 13:27:28.146   512  5987 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-25 13:27:28.148   512  5987 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-25 13:27:28.148   512  5987 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 13:27:28.149   512  2949 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 13:27:28.151  3889  4115 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-25 13:27:28.152  3889  5984 I MicroRecognitionRnrImpl: Detection finished
,11-25 13:27:28.416   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
