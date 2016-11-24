#### Test 9418709498bebf3_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 12:17:44.832  4020  4233 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-24 12:17:44.919  4020  4233 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-24 12:17:45.288  5661  5661 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 12:17:45.293  5661  5661 D AndroidRuntime: CheckJNI is OFF
11-24 12:17:45.318  5661  5661 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 12:17:45.355  5661  5661 I Radio-JNI: register_android_hardware_Radio DONE
11-24 12:17:45.370  5661  5661 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 12:17:45.387   932   943 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 12:17:45.407  5661  5661 D AndroidRuntime: Shutting down VM
11-24 12:17:45.430  4002  4072 W SearchService: Abort, client detached.
11-24 12:17:45.435  4002  4002 I HotwordDetector: Closing mic
11-24 12:17:45.436  4002  4230 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cb9adaa
11-24 12:17:45.437  4002  4240 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 12:17:45.450   932  3640 I ActivityManager: Start proc 5670:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 12:17:45.517   516  4247 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 12:17:45.518   516  4247 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 12:17:45.522   516  4247 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 12:17:45.522   516  4247 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 12:17:45.522   516  3064 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 12:17:45.525  4002  4234 I MicroRecognitionRnrImpl: Detection finished
11-24 12:17:45.524  4002  4231 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 12:17:45.540  5670  5670 I CordovaLog: Changing log level to DEBUG(3)
11-24 12:17:45.541  5670  5670 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 12:17:45.541  5670  5670 D CordovaActivity: CordovaActivity.onCreate()
11-24 12:17:45.545  5670  5670 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 12:17:45.564  5670  5670 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-24 12:17:45.620  5670  5670 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 186-240)
11-24 12:17:45.621  5670  5670 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 12:17:45.652  5670  5670 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f768233}
,11-24 12:17:45.653  5670  5670 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 12:17:45.654  5670  5670 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 12:17:45.660  5670  5670 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 12:17:45.661  5670  5670 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 12:17:45.709  5670  5670 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 12:17:45.726  5670  5670 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 12:17:45.726  5670  5670 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 12:17:45.726  5670  5670 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 12:17:45.726  5670  5670 I Adreno  : Build Date                       : 12/06/15
11-24 12:17:45.726  5670  5670 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 12:17:45.726  5670  5670 I Adreno  : Local Branch                     : mybranch17112971
11-24 12:17:45.726  5670  5670 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 12:17:45.726  5670  5670 I Adreno  : Remote Branch                    : NONE
11-24 12:17:45.726  5670  5670 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 12:17:45.784   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8a534df:true
,11-24 12:17:45.811  4097  4097 W Binder_5: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14093]" dev="sockfs" ino=14093 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.811  4097  4097 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14093]" dev="sockfs" ino=14093 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.825  5670  5670 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 12:17:45.834  5670  5670 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 12:17:45.838  5670  5670 D PluginManager: init()
,11-24 12:17:45.840  5670  5670 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 12:17:45.860  5670  5670 D CordovaActivity: Started the activity.
,11-24 12:17:45.860  5670  5670 D CordovaActivity: Resumed the activity.
,11-24 12:17:45.861   404   404 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31975]" dev="sockfs" ino=31975 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.861   404   404 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31975]" dev="sockfs" ino=31975 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.864  4322  4322 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31719]" dev="sockfs" ino=31719 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.864  4322  4322 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31719]" dev="sockfs" ino=31719 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.871  5670  5694 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 12:17:45.902  5670  5707 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 12:17:45.978  4322  4322 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31724]" dev="sockfs" ino=31724 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.978  4322  4322 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31724]" dev="sockfs" ino=31724 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 12:17:45.981  3206  3206 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31723]" dev="sockfs" ino=31723 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 12:17:45.981  3206  3206 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31723]" dev="sockfs" ino=31723 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 12:17:45.984   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +552ms
,11-24 12:17:45.987  3726  3726 I Keyboard.Facilitator: onFinishInput()
,11-24 12:17:46.002  5670  5670 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 12:17:46.016  5670  5670 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5670
,11-24 12:17:46.123  5670  5670 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 12:17:46.321  5670  5709 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -566232784
,11-24 12:17:46.326  5670  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 12:17:46.326  5670  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 12:17:46.326  5670  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 12:17:46.326  5670  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 12:17:46.326  5670  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 12:17:46.326  5670  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110eb86 added. We now have 1 listener(s)
,11-24 12:17:46.328  5670  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 12:17:46.329  5670  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:17:46.329  5670  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:17:46.329  5670  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 12:17:46.332  5670  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55f159d added. We now have 1 listener(s)
11-24 12:17:46.332  5670  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:17:46.352   932  3017 D WifiService: New client listening to asynchronous messages
,11-24 12:17:46.353  5670  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:17:46.353  5670  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 12:17:46.353  5670  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 12:17:46.353  5670  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 12:17:46.353  5670  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 12:17:46.353  5670  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 12:17:46.353  5670  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 12:17:46.355  5670  5709 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 12:17:46.521  5670  5670 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 12:17:46.532  5670  5670 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 12:17:46.532  5670  5670 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 12:17:46.853  5670  5679 I art     : Background sticky concurrent mark sweep GC freed 74869(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 1.446ms total 283.100ms
,11-24 12:17:47.097   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:17:47.973  5670  5679 I art     : Background partial concurrent mark sweep GC freed 63660(7MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 1.864ms total 127.327ms
,11-24 12:17:48.066  5670  5718 W jxcore-log: Initializing JXcore engine
,11-24 12:17:48.066  5670  5718 W jxcore-log: JXcore engine is ready
,11-24 12:17:48.088  5718  5718 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12954 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 12:17:48.088  5718  5718 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15405]" dev="sockfs" ino=15405 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 12:17:48.088  5718  5718 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 12:17:48.088  5718  5718 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32792]" dev="sockfs" ino=32792 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 12:17:48.099  5670  5718 W jxcore-log: Starting JXcore engine
,11-24 12:17:48.150  5670  5718 W jxcore-log: Platform android
11-24 12:17:48.150  5670  5718 W jxcore-log: 
,11-24 12:17:48.150  5670  5718 W jxcore-log: Process ARCH arm
11-24 12:17:48.150  5670  5718 W jxcore-log: 
,11-24 12:17:48.336  5670  5718 I jxcore-log: JXcore Cordova bridge is ready!
11-24 12:17:48.336  5670  5718 I jxcore-log: 
,11-24 12:17:48.336  5670  5718 W jxcore-log: JXcore engine is started
,11-24 12:17:48.346  5670  5709 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 12:17:48.356  5670  5670 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 12:17:48.356  5670  5670 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 12:17:48.936  3619  3619 I ConfigService: onDestroy
,11-24 12:17:49.680   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:50.442   932  3854 I ActivityManager: Killing 5454:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 12:17:50.480   932  3854 I ActivityManager: Killing 5111:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,11-24 12:17:50.681   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:51.682   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:52.683   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:53.684   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:54.685   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:17:58.024  5670  5718 I jxcore-log: 2016-11-24 11:17:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 12:17:58.024  5670  5718 I jxcore-log: 
,11-24 12:17:58.026  5670  5718 I jxcore-log: 2016-11-24 11:17:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 12:17:58.026  5670  5718 I jxcore-log: 
,11-24 12:17:58.031  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:17:58.031  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 12:17:58.032  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:17:58.035  5670  5718 I jxcore-log: 2016-11-24 11:17:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 12:17:58.035  5670  5718 I jxcore-log: 
,11-24 12:17:58.036  5670  5718 I jxcore-log: 2016-11-24 11:17:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 12:17:58.036  5670  5718 I jxcore-log: 
,11-24 12:17:58.281  5670  5718 I jxcore-log: 2016-11-24 11:17:58 - DEBUG UnitTest_app: 'Running unit tests'
11-24 12:17:58.281  5670  5718 I jxcore-log: 
,11-24 12:17:58.282  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 12:17:58.282  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9dd789 added. We now have 2 listener(s)
,11-24 12:17:58.284  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:17:58.284  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:17:58.284  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:17:58.285  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:17:58.285  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d6b38e added. We now have 2 listener(s)
11-24 12:17:58.285  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:17:58.285  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:17:58.286  5670  5718 D executeNativeTests: Running unit tests
,11-24 12:17:58.328  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 12:17:58.328  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f added. We now have 3 listener(s)
11-24 12:17:58.328  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:17:58.329  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:17:58.329  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:17:58.329  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:17:58.329  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec added. We now have 3 listener(s)
11-24 12:17:58.329  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:17:58.329  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:17:58.331  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 12:17:58.331  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:17:58.331  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 12:17:58.331  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:17:58.332  5670  5718 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 12:17:58.332  5670  5718 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 12:17:58.332  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-24 12:17:58.332  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:17:58.332  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:17:58.332  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:17:58.332  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:17:58.332  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:17:58.332  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:17:58.333  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:17:58.333  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:17:58.333  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:17:58.333  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f removed from the list
11-24 12:17:58.333  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:17:58.333  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec removed from the list
11-24 12:17:58.333  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:17:58.333  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.333  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:17:58.334  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.334  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.334  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:17:58.334  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:17:58.334  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:17:58.334  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:17:58.334  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:17:58.335  5670  5718 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 12:17:58.335  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:17:58.335  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:17:58.335  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:17:58.335  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:17:58.335  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:17:58.335  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:17:58.335  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:17:58.336  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:17:58.336  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:17:58.336  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.336  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:17:58.336  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.336  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.336  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.336  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:17:58.336  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:17:58.336  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:17:58.336  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 12:17:58.339  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 12:17:58.340  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 12:17:58.340  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 12:17:58.340  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 12:17:58.340  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:17:58.340  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:17:58.340  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:17:58.340  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:17:58.340  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:17:58.340  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:17:58.340  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:17:58.340  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:17:58.340  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:17:58.340  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.340  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:17:58.341  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.341  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:17:58.341  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.341  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:17:58.341  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:17:58.341  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:17:58.341  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:17:58.341  5670  5718 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 12:17:58.342  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:17:58.342  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:17:58.354  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:17:58.356  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 12:17:58.356  5670  5718 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:17:58.356  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 12:17:58.356  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:17:58.356  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:17:58.357  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:17:58.357  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 12:17:58.360  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:17:58.360  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:17:58.361  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 12:17:58.361  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:17:58.361  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:17:58.365  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.365  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 12:17:58.367  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:17:58.368  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:17:58.368  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:17:58.369  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-24 12:17:58.370  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-24 12:17:58.370  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.370  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:17:58.370  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:17:58.370  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-24 12:17:58.371  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:17:58.371  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.371  5670  5718 D BluetoothAdapter: STATE_ON
,11-24 12:17:58.373  4724  4739 D BtGatt.GattService: registerClient() - UUID=6e230283-a002-492a-b7c8-c3e194b067d8
,11-24 12:17:58.374  4724  4786 D BtGatt.GattService: onClientRegistered() - UUID=6e230283-a002-492a-b7c8-c3e194b067d8, clientIf=5
,11-24 12:17:58.375  5670  5681 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 12:17:58.376  4724  4946 D BtGatt.GattService: start scan with filters
,11-24 12:17:58.380  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 12:17:58.380  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.380  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:17:58.380  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.380  4724  4790 D BtGatt.ScanManager: handling starting scan
11-24 12:17:58.380  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:17:58.380  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:17:58.381  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.381  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:17:58.381  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:17:58.381  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.381  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:17:58.381  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:17:58.381  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.382  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.382  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.382  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.382  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.382  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:17:58.382  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.383  5670  5718 I io.jxcore.node.ConnectionHelper: start: OK
11-24 12:17:58.383  4724  4790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:17:58.387  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.387  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:17:58.388  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.388  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:17:58.388  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 12:17:58.390  4724  4786 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 12:17:58.390  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:17:58.390  4724  4790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 12:17:58.396  4724  4786 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 12:17:58.396  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:17:58.396  4724  4790 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:17:58.397  4724  4790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:17:58.406  4724  4786 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:17:58.406  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:17:58.412  4724  4786 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:17:58.413  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:17:58.602  4907  4966 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 12:17:58.604  4907  4907 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 12:17:58.677   932  3017 D WifiService: New client listening to asynchronous messages
,11-24 12:17:58.682  4002  5719 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 12:17:58.889  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 12:17:58.890  5670  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:17:58.890  5670  5670 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:18:03.388  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:03.389  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:03.389  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 12:18:03.389  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:18:03.389  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 12:18:03.389  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:03.389  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:18:03.389  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 12:18:03.390  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.390  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:18:03.390  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:18:03.391  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.391  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:03.391  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.391  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:18:03.391  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.392  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:03.393  4724  4946 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:18:03.393  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 12:18:03.394  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:03.395  4724  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:18:03.396  4724  4737 D BtGatt.GattService: stopScan() - queue size =1
,11-24 12:18:03.399  4724  4739 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 12:18:03.401  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 12:18:03.401  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.401  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 12:18:03.401  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.402  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.402  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:03.402  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.403  4724  4724 D BtGatt.ScanManager: awakened up at time 98022
11-24 12:18:03.403  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:18:03.403  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.404  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.404  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.404  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:18:03.405  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:18:03.406  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:18:03.407  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.409  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.409  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:03.410  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.410  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:03.411  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:03.411  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:03.411  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:18:03.411  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:03.411  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:18:03.411  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:18:03.411  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:03.411  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.411  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:03.412  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 12:18:03.412  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:03.412  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:18:03.412  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:03.412  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:03.412  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.412  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:18:03.412  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.412  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 12:18:03.412  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:03.413  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.413  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.416  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.416  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:03.417  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 12:18:03.430  4724  4786 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 12:18:03.430  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:03.430  4724  4786 D BtGatt.GattService: current time is 98050147997
11-24 12:18:03.431  4724  4786 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -88, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -97, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -90, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 12:18:03.433  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 12:18:03.434  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 12:18:03.434  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 12:18:03.435  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-24 12:18:03.435  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 12:18:03.435  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-24 12:18:03.445  4724  4786 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 12:18:03.445  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:03.446  4724  4790 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:18:03.453  4724  4786 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 12:18:03.454  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:03.454  4724  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:18:03.462  4724  4786 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:18:03.463  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:18:03.914  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:18:08.418  5670  5718 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 12:18:08.424  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 12:18:08.426  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:18:08.439  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 12:18:08.441  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 12:18:08.442  5670  5718 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:18:08.442  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:18:08.442  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:18:08.442  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:18:08.442  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:18:08.442  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:18:08.445  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:08.446  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 12:18:08.446  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:18:08.446  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 12:18:08.448  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:08.451  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.451  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 12:18:08.452  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 12:18:08.452  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:18:08.452  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:18:08.456  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.456  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:18:08.456  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:18:08.456  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:18:08.456  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:18:08.456  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.457  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:08.459  4724  4737 D BtGatt.GattService: registerClient() - UUID=f5400a7b-62f5-4a12-8146-fd079f82927f
11-24 12:18:08.459  4724  4786 D BtGatt.GattService: onClientRegistered() - UUID=f5400a7b-62f5-4a12-8146-fd079f82927f, clientIf=5
11-24 12:18:08.460  5670  5680 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 12:18:08.461  4724  4946 D BtGatt.GattService: start scan with filters
,11-24 12:18:08.464  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:18:08.464  4724  4790 D BtGatt.ScanManager: handling starting scan
11-24 12:18:08.464  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.464  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:18:08.464  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.464  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:18:08.464  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:18:08.464  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.465  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:18:08.465  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:18:08.465  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.465  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.465  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.465  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.466  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:18:08.466  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.469  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.469  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:18:08.469  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.469  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.469  5670  5718 I io.jxcore.node.ConnectionHelper: start: OK
11-24 12:18:08.469  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 12:18:08.473  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:08.473  5670  5718 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 12:18:08.473  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:08.473  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 12:18:08.473  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:18:08.473  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 12:18:08.473  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:08.473  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:18:08.474  4724  4786 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:18:08.474  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.474  4724  4790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 12:18:08.475  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.475  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 12:18:08.476  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.476  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:18:08.476  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:18:08.476  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.476  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:18:08.476  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 12:18:08.476  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.476  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.476  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.476  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:18:08.477  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.477  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:08.478  4724  4936 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:18:08.478  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 12:18:08.479  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:08.480  4724  4946 D BtGatt.GattService: stopScan() - queue size =1
11-24 12:18:08.480  4724  4936 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.481  4724  4786 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:18:08.481  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:18:08.481  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.482  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.482  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.482  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.482  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:18:08.482  4724  4790 D BtGatt.ScanManager: Starting BLE batch scan
,11-24 12:18:08.482  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 12:18:08.482  4724  4790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:18:08.483  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:18:08.483  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.484  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.484  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:08.484  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.484  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.484  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:18:08.484  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:18:08.484  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:18:08.485  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:08.485  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:08.485  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:08.485  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 12:18:08.485  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:08.485  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:08.485  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:18:08.485  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:08.485  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.485  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:18:08.485  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:18:08.485  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:18:08.485  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.485  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.485  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.485  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:08.486  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.486  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.488  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.488  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.488  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.488  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.488  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.491  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.491  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.491  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.491  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:08.491  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:08.491  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:08.491  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:08.492  5670  5718 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 12:18:08.494  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:18:08.494  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 12:18:08.495  4724  4786 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:18:08.495  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.500  4724  4786 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:18:08.500  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:18:08.500  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:18:08.501  4724  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:18:08.502  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 12:18:08.502  5670  5718 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:18:08.502  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:18:08.502  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:18:08.502  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:18:08.503  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:18:08.503  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 12:18:08.505  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:08.506  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:18:08.506  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:18:08.506  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:18:08.508  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:08.508  4724  4786 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:18:08.508  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.508  4724  4786 E BtGatt.ContextMap: Context not found for ID 5
,11-24 12:18:08.511  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.511  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:18:08.511  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:18:08.511  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:18:08.511  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:18:08.514  4724  4786 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 12:18:08.514  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.514  4724  4790 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:18:08.515  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:08.515  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:18:08.515  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:18:08.515  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:18:08.515  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:18:08.515  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.516  5670  5718 D BluetoothAdapter: STATE_ON
,11-24 12:18:08.518  4724  4739 D BtGatt.GattService: registerClient() - UUID=c59f14bd-f771-4df9-a8a3-97a1eaf0c2cb
11-24 12:18:08.519  4724  4786 D BtGatt.GattService: onClientRegistered() - UUID=c59f14bd-f771-4df9-a8a3-97a1eaf0c2cb, clientIf=5
,11-24 12:18:08.519  4724  4786 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 12:18:08.520  5670  5681 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:18:08.520  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.520  4724  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:18:08.520  4724  4737 D BtGatt.GattService: start scan with filters
,11-24 12:18:08.523  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:18:08.523  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.523  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 12:18:08.523  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.523  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:18:08.523  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:18:08.523  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.524  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:18:08.524  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:18:08.524  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.524  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.524  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 12:18:08.524  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.524  4724  4786 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:18:08.524  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:18:08.525  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:18:08.525  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.526  4724  4790 D BtGatt.ScanManager: handling starting scan
11-24 12:18:08.527  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.527  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:18:08.527  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.527  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:08.527  5670  5718 I io.jxcore.node.ConnectionHelper: start: OK
11-24 12:18:08.527  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 12:18:08.530  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.530  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.530  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:08.530  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 12:18:08.532  4724  4786 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:18:08.532  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.532  4724  4790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 12:18:08.536  4724  4786 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:18:08.536  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:08.537  4724  4790 D BtGatt.ScanManager: Starting BLE batch scan
,11-24 12:18:08.537  4724  4790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:18:08.545  4724  4786 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:18:08.545  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:18:08.550  4724  4786 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:18:08.550  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:18:09.031  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 12:18:09.032  5670  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:18:09.032  5670  5670 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:18:10.323   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 12:18:10.326   932  3018 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-24 12:18:13.349   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 12:18:13.357   932  3018 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 12:18:13.528  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:13.528  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:18:13.528  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 12:18:13.528  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:18:13.529  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 12:18:13.529  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:13.529  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:18:13.529  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:18:13.529  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.529  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 12:18:13.530  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:18:13.530  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.530  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:13.530  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.531  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:18:13.531  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.533  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:13.534  4724  4737 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 12:18:13.534  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:18:13.535  4724  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:18:13.536  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:18:13.538  4724  4946 D BtGatt.GattService: stopScan() - queue size =1
,11-24 12:18:13.540  4724  4739 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:18:13.542  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 12:18:13.542  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.542  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:18:13.543  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.543  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:13.543  4724  4724 D BtGatt.ScanManager: awakened up at time 108163
11-24 12:18:13.543  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.544  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.544  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 12:18:13.544  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.544  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.545  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.545  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-24 12:18:13.545  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:18:13.549   932   943 I ActivityManager: Killing 5466:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 12:18:13.578  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 12:18:13.579  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.581  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:13.581  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:13.582  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:13.582  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:13.582  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:13.582  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:13.583  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-24 12:18:13.583  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:18:13.583  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:18:13.583  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:18:13.583  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:18:13.583  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:18:13.583  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:18:13.585  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:13.585  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:18:13.585  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 12:18:13.588  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 12:18:13.588  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:18:13.588  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 12:18:13.599  4724  4786 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 12:18:13.599  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:13.600  4724  4786 D BtGatt.GattService: current time is 108219532233
11-24 12:18:13.600  4724  4786 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -94, 71, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 35, 97, 126, -92, 22, -56, 1, -128, -94, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -94, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -90, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 12:18:13.601  4724  4786 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
11-24 12:18:13.601  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 12:18:13.601  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 12:18:13.601  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 12:18:13.602  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 12:18:13.602  4724  4786 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 12:18:13.608  4724  4786 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 12:18:13.608  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:13.609  4724  4790 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:18:13.615  4724  4786 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 12:18:13.615  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:18:13.615  4724  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:18:13.621  4724  4786 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:18:13.621  4724  4786 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:18:14.086  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:18:14.086  5670  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:18:14.086  5670  5670 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:18:18.583  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:18.584  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:18:18.584  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 12:18:18.584  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.584  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 12:18:18.584  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:18:18.585  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:18.585  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.585  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:18.585  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:18.585  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:18:18.585  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 12:18:18.588  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.588  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.591  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.591  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.591  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.591  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.591  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:18:18.592  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.592  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:18.593  5670  5718 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-24 12:18:18.595  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:18.595  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:18:18.595  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.595  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.596  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:18.596  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.596  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.596  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:18.596  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.596  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.597  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.600  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.601  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.601  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.601  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 12:18:18.601  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.601  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.602  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.604  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 12:18:18.604  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:18.604  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.604  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.605  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.605  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:18.605  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
,11-24 12:18:18.605  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.605  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.605  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.605  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.605  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.607  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.608  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.608  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.608  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 12:18:18.608  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.608  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.608  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.609  5670  5718 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 12:18:18.609  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:18.610  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.610  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.610  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.610  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:18.610  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.610  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.610  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.611  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.611  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.611  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.613  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.613  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.614  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.614  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.614  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:18:18.614  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.614  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.616  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 12:18:18.617  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:18.617  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.617  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.617  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.617  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:18.618  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.618  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.618  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:18.618  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.618  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.619  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.622  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.622  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.622  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.622  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.622  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.623  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.623  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.624  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 12:18:18.624  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 12:18:18.624  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:18:18.624  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 12:18:18.625  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:18:18.625  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:18:18.625  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 12:18:18.625  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:18:18.625  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:18:18.625  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:18.625  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.625  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.626  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.626  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:18.626  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.626  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.626  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.626  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.626  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.626  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:18.629  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.629  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.629  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.629  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.629  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.629  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.630  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:18.631  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 12:18:18.632  5670  5718 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 12:18:18.632  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 12:18:18.637  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 12:18:18.637  5670  5718 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 12:18:18.637  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-24 12:18:18.638  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 12:18:18.639  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 12:18:18.640  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 12:18:18.640  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 12:18:18.640  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 12:18:18.640  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 12:18:18.641  5670  5718 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 12:18:18.641  5670  5718 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 12:18:18.641  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:18:18.641  5670  5718 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 12:18:18.641  5670  5718 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 12:18:18.641  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:18:18.642  5670  5718 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 12:18:18.642  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 12:18:18.647  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-24 12:18:18.648  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 12:18:18.648  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 12:18:18.648  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 12:18:18.649  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 12:18:18.649  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 12:18:18.649  5670  5718 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:18:18.649  5670  5718 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,11-24 12:18:18.649  5670  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-24 12:18:18.649  5670  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 12:18:18.649  5670  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 12:18:18.650  5670  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-24 12:18:18.650  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:18.651  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.651  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.651  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.651  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:18:18.651  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 12:18:18.652  5670  5732 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 12:18:18.652  5670  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:18:18.652  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.652  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.653  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.653  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.653  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.653  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.653  5670  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-24 12:18:18.653  5670  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 12:18:18.653  5670  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-24 12:18:18.653  5670  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-24 12:18:18.651  4739  4739 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29664]" dev="sockfs" ino=29664 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 12:18:18.651  4739  4739 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29664]" dev="sockfs" ino=29664 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 12:18:18.654  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.654  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.654  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.654  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.655  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.655  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.655  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.655  5670  5732 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-24 12:18:18.656  5670  5718 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 12:18:18.656  5670  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 12:18:18.656  5670  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-24 12:18:18.656  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:18.,657  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.657  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.657  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.657  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:18.657  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.657  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.657  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.657  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.658  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.658  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.661  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.661  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.661  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.661  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.661  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.661  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.661  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.662  5670  5718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 12:18:18.663  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:18.663  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.663  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.663  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.663  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:18.663  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.663  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.663  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.663  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.663  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.663  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.665  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.665  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.665  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.665  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.665  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.665  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.665  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.666  5670  5718 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 12:18:18.666  5670  5718 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 12:18:18.666  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 12:18:18.666  5670  5718 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 12:18:18.666  5670  5718 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 12:18:18.666  5670  5718 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 12:18:18.666  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 12:18:18.666  5670  5718 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 12:18:18.666  5670  5718 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 12:18:18.666  5670  5718 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 12:18:18.666  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 12:18:18.666  5670  5718 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 12:18:18.667  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:18.667  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:18.667  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:18.667  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.667  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:18.667  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.667  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.667  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.667  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:18.667  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.667  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.669  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.669  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.669  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:18.669  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:18.669  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:18.669  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.669  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.670  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:18.670  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:18.670  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:18.670  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:18.670  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:18.670  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:18:19.685   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:18:19.686   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:18:23.671  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:23.671  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.671  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.671  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:23.672  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.672  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:23.672  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:23.672  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:23.672  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.673  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:23.673  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.673  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.673  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.673  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:23.674  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.674  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.678  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.678  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.678  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.678  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:23.678  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:18:23.678  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.679  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.682  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 12:18:23.683  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 12:18:23.684  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 12:18:23.690  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 12:18:23.691  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 12:18:23.691  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 12:18:23.692  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-24 12:18:23.692  5670  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 12:18:23.692  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 12:18:23.692  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:18:23.692  5670  5670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-24 12:18:23.693  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.693  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 12:18:23.693  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 12:18:23.693  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-24 12:18:23.693  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:18:23.694  5670  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:18:23.694  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 12:18:23.695  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 12:18:23.695  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.695  5670  5670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 12:18:23.695  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.695  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 12:18:23.695  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.695  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:18:23.695  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:18:23.696  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.694  4946  4946 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33854]" dev="sockfs" ino=33854 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 12:18:23.694  4946  4946 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33854]" dev="sockfs" ino=33854 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 12:18:23.698  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.698  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:23.698  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.698  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.698  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.698  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:23.699  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:23.699  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:18:23.699  5670  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-24 12:18:23.699  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:23.699  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:18:23.699  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:23.699  5670  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 12:18:23.699  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.699  5670  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 12:18:23.699  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-24 12:18:23.699  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.699  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.699  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.699  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:23.700  5670  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 12:18:23.700  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.700  5670  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:23.700  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.702  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.702  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.702  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.702  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:23.702  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:23.702  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.702  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:23.704  5670  5718 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 12:18:23.705  5670  5718 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 12:18:23.705  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 12:18:23.705  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:18:23.705  5670  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:18:23.705  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:23.705  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:23.705  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 12:18:23.706  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.706  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:23.706  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.706  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.706  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.706  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:23.706  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.706  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.708  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.709  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.709  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.709  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:23.709  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:23.709  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.709  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:23.716  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:18:23.716  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:23.717  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:23.717  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.717  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:23.717  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.717  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:23.717  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.717  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:23.717  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.717  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.719  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.719  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.719  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.719  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:23.719  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:23.719  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.719  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:23.720  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:18:23.720  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:18:23.721  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:18:23.721  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:18:23.721  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:18:23.721  5670  5718 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f41a9f not in the list
11-24 12:18:23.721  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:23.721  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
11-24 12:18:23.721  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:23.721  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.721  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.723  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:18:23.723  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.723  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:18:23.723  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:18:23.723  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:18:23.723  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:23.723  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f7ec not in the list
,11-24 12:18:23.724  5670  5718 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 12:18:23.724  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 12:18:23.724  5670  5718 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 12:18:23.725  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 12:18:23.725  5670  5718 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-24 12:18:23.725  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 12:18:23.727  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-24 12:18:23.727  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 12:18:23.728  5670  5718 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 12:18:23.728  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 12:18:23.728  5670  5718 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-24 12:18:23.728  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 12:18:23.728  5670  5718 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 12:18:23.728  5670  5718 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 12:18:23.729  5670  5718 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 12:18:23.729  5670  5718 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-24 12:18:23.730  5670  5718 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 12:18:23.730  5670  5718 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 12:18:23.730  5670  5718 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 12:18:23.730  5670  5718 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-24 12:18:23.731  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:18:23.731  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@107e825 added. We now have 3 listener(s)
,11-24 12:18:23.731  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:18:23.733  5670  5718 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 12:18:23.734   932  3268 D WifiService: setWifiEnabled: true pid=5670, uid=10077
11-24 12:18:23.734   932  3268 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:18:23.782  4724  4922 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 12:18:23.782  4724  4934 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 12:18:24.200  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:18:24.686   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:25.687   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:26.688   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:27.102   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:18:27.689   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:28.690   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:28.740  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:18:28.740  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab74dfa added. We now have 4 listener(s)
,11-24 12:18:28.741  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:18:28.752  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:28.753  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab74dfa removed from the list
,11-24 12:18:28.753  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:18:28.755  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:18:28.755  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32a8fab added. We now have 4 listener(s)
,11-24 12:18:28.755  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:18:28.758  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:28.759  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32a8fab removed from the list
,11-24 12:18:28.759  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:18:28.761  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:18:28.761  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a277608 added. We now have 4 listener(s)
11-24 12:18:28.761  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:18:28.767   932  3854 D WifiService: setWifiEnabled: false pid=5670, uid=10077
,11-24 12:18:28.768   932  3854 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:18:28.773   932  3016 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 12:18:28.773   932  3016 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 12:18:28.774   932  3016 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 12:18:28.774   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:18:28.778  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:18:28.778  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 12:18:28.783  4724  4782 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 12:18:28.783  4724  4782 D BluetoothAdapterProperties: Setting state to 13
,11-24 12:18:28.783  4724  4782 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 12:18:28.785  4724  4782 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 12:18:28.786  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:18:28.786  4724  4782 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:18:28.786  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:18:28.788  4724  4786 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:18:28.788  4724  4782 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 12:18:28.788  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:28.789  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 12:18:28.789  5670  5718 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:18:28.791  4724  4724 D BluetoothMapService: onReceive
11-24 12:18:28.791  4724  4724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:18:28.791  4724  4724 D BluetoothMapService: STATE_TURNING_OFF
11-24 12:18:28.792  4724  4724 D BluetoothMapService: MAP Service closeService in
11-24 12:18:28.792  4724  4724 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 12:18:28.792  4724  4724 D ObexServerSockets0: shutdown(block = true)
11-24 12:18:28.793  4724  4724 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 12:18:28.793  4724  4724 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 12:18:28.793  4724  4949 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 12:18:28.794  4724  4948 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 12:18:28.794  4724  4934 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 12:18:28.796   932  5428 D DhcpClient: Clearing IP address
,11-24 12:18:28.796   511   926 D CommandListener: Clearing all IP addresses on wlan0
11-24 12:18:28.797  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:18:28.798  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:18:28.798  4724  4724 I BtOppRfcommListener: stopping Accept Thread
,11-24 12:18:28.798  4724  5355 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 12:18:28.799  4724  5355 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 12:18:28.799  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:28.799  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:18:28.803  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:28.804   511   926 D CommandListener: Setting iface cfg
,11-24 12:18:28.806  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:28.807  3619  5479 V NativeCrypto: Read error: ssl=0x7f7101e000: I/O error during system call, Connection timed out
,11-24 12:18:28.809   932   945 I ActivityManager: Start proc 5738:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 12:18:28.809  3619  5479 V NativeCrypto: SSL shutdown failed: ssl=0x7f7101e000: I/O error during system call, Broken pipe
11-24 12:18:28.811   932  5429 D DhcpClient: Receive thread stopped
,11-24 12:18:28.812   932  5002 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-24 12:18:28.812   932  5426 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-24 12:18:28.812  4724  4724 D HeadsetService: Received stop request...Stopping profile...
11-24 12:18:28.814   932   932 D BluetoothHeadset: Proxy object disconnected
,11-24 12:18:28.814  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:28.814   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:28.814   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:28.815  3825  4056 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:28.815  3171  4047 D BluetoothHeadset: Proxy object disconnected
,11-24 12:18:28.816  3171  3171 D HeadsetProfile: Bluetooth service disconnected
11-24 12:18:28.816   932  5426 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-24 12:18:28.816  4724  4724 D A2dpService: Received stop request...Stopping profile...
11-24 12:18:28.817   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-24 12:18:28.817  4724  4939 D A2dpStateMachine: Exit Disconnected: -1
11-24 12:18:28.817   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-24 12:18:28.818   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 12:18:28.819   932   932 D BluetoothA2dp: Proxy object disconnected
11-24 12:18:28.820  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.820  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.820  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.820  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:28.821  4724  4724 D HidService: Received stop request...Stopping profile...
11-24 12:18:28.821  4724  4724 D HidService: Stopping Bluetooth HidService
11-24 12:18:28.821  3171  3171 D BluetoothA2dp: Proxy object disconnected
11-24 12:18:28.823  3171  3171 D BluetoothInputDevice: Proxy object disconnected
11-24 12:18:28.823  3171  3171 D HidProfile: Bluetooth service disconnected
11-24 12:18:28.824   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 12:18:28.824   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 12:18:28.825  4724  4724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 12:18:28.825  4724  4724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 12:18:28.825  4724  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:28.825  4724  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:28.825  4724  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:28.825  4724  4724 D HealthService: Received stop request...Stopping profile...
11-24 12:18:28.826  4724  4786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 12:18:28.826  4724  4786 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 12:18:28.828   537   537 E Parcel  : Reading a NULL string not supported here.
11-24 12:18:28.830   932   932 D RttService: SCAN_AVAILABLE : 1
11-24 12:18:28.831   932  3125 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 12:18:28.831  4724  4724 D PanService: Received stop request...Stopping profile...
11-24 12:18:28.833  4724  4724 D BluetoothMapService: Received stop request...Stopping profile...
11-24 12:18:28.833  4724  4724 D BluetoothMapService: stop()
11-24 12:18:28.834   932  3018 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 12:18:28.834  4724  4724 D BluetoothMapAppObserver: deinitObservers()
,11-24 12:18:28.834  4724  4724 D BluetoothMapAppObserver: removeReceiver()
11-24 12:18:28.835  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.835  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.835  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.835  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:28.835  3777  3915 W QCNEJ   : |CORE| network lost: 100
11-24 12:18:28.835  4724  4724 D SapService: Received stop request...Stopping profile...
11-24 12:18:28.835  4724  4724 V SapService: stop()
11-24 12:18:28.836  3777  3915 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 12:18:28.837  4724  4786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 12:18:28.837  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.837  4724  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:28.837  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.837  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.837  4724  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:28.837  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:28.837  4724  4922 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 12:18:28.837  4724  4922 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:18:28.838  4724  4922 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 12:18:28.838  4724  4724 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 12:18:28.838  4724  4922 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:18:28.838  4724  4786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 12:18:28.838  4724  4724 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 12:18:28.838  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.838  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.838  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.838  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:28.838  4724  4724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 12:18:28.838  4724  4786 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 12:18:28.838   932  3016 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 12:18:28.839  4724  4724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 12:18:28.839  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.839  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.839  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.839  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:28.839  4724  4724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 12:18:28.839  4724  4724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 12:18:28.840  4724  4724 D BluetoothMapService: MAP Service closeService in
11-24 12:18:28.840  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.840  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.840  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.841  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:28.841  4724  4724 D BluetoothMapService: cleanup()
11-24 12:18:28.841  4724  4724 D BluetoothMapService: MAP Service closeService in
11-24 12:18:28.841  4724  4724 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:28.841  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:28.841  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:28.841  4724  4724 V BluetoothAdapterState: isBleTurnin,gOff()=false
11-24 12:18:28.841  4724  4782 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 12:18:28.842  4724  4782 D BluetoothAdapterProperties: Setting state to 15
11-24 12:18:28.842  4724  4782 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 12:18:28.845   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 12:18:28.846  3171  3191 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:18:28.846  4724  4782 I BluetoothAdapterState: Entering BleOnState
11-24 12:18:28.847  3171  3171 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 12:18:28.847  3171  3171 D PanProfile: Bluetooth service disconnected
11-24 12:18:28.847  3171  3171 D BluetoothMap: Proxy object disconnected
11-24 12:18:28.847  3171  3171 D MapProfile: Bluetooth service disconnected
,11-24 12:18:28.848  3171  3187 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:28.848   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:28.848  3171  4047 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 12:18:28.848   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:28.849   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:18:28.849   932  3016 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:18:28.849  3171  3187 D BluetoothPan: onBluetoothStateChange on: false
11-24 12:18:28.850  3171  4047 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 12:18:28.851  3825  3837 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:28.851  3171  3191 D BluetoothMap: onBluetoothStateChange: up=false
11-24 12:18:28.852  4724  4782 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 12:18:28.853  4724  4782 D BluetoothAdapterProperties: Setting state to 16
11-24 12:18:28.853  4724  4782 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 12:18:28.853  4724  4782 D BluetoothAdapterProperties: onBleDisable
11-24 12:18:28.854  4724  4782 I BluetoothAdapterState: Entering PendingCommandState
11-24 12:18:28.854  4724  4783 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 12:18:28.855  4724  4922 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 12:18:28.855  4724  4786 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:18:28.855  4724  4922 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:28.855  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:18:28.856  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:18:28.856  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:28.856  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:18:28.857   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 12:18:28.858  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:28.880   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 12:18:28.880   511   926 D CommandListener: Clearing all IP addresses on wlan0
11-24 12:18:28.881   511   926 D TetherController: Setting IP forward enable = 0
,11-24 12:18:28.882   932  3018 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 12:18:28.882   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 12:18:28.884   932   949 D Tethering: MasterInitialState.processMessage what=3
,11-24 12:18:28.886  5310  5310 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d3b624f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-24 12:18:28.886  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:28.890  4002  4002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 12:18:28.894  5099  5123 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 12:18:28.894  5099  5123 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 12:18:28.894  5099  5123 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-24 12:18:28.894  5099  5123 E SarControlService: no key has been found,reset the power
11-24 12:18:28.894  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:18:28.894  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:18:28.894  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 12:18:28.895  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 12:18:28.895  5124  5124 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:18:28.897  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:18:28.897  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:18:28.897  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 12:18:28.898  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:18:28.898  5124  5124 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 12:18:28.901  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000ea03000000000000ffffffff]
11-24 12:18:28.901  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:18:28.901  5124  5138 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 12:18:28.901  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:18:28.901  5099  5110 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:18:28.905  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 12:18:28.908  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000eb03000000000000ffffffff]
,11-24 12:18:28.908  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:18:28.909  5124  5138 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 12:18:28.909  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:18:28.909  5099  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 12:18:28.917  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:18:28.922   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2728b33:true
,11-24 12:18:28.923  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:18:28.936   932   942 I ActivityManager: Start proc 5767:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 12:18:28.948  5738  5738 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 12:18:28.951  5738  5738 D BluetoothMap: Create BluetoothMap proxy object
,11-24 12:18:28.964  5738  5738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 12:18:28.977  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:18:28.978  5767  5767 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 12:18:28.987   932   943 I ActivityManager: Killing 4521:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 12:18:29.062  4724  4786 I bt_hci  : shut_down
,11-24 12:18:29.065  4724  4792 D bt_hwcfg: hw_epilog_process
,11-24 12:18:29.065  4724  4792 I bt_vendor: low_power_mode_cb
,11-24 12:18:29.068  4724  4792 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 12:18:29.068  4724  4792 I bt_vendor: epilog_cb
11-24 12:18:29.068  4724  4792 I bt_hci  : epilog_finished_callback
,11-24 12:18:29.070  4724  4786 I bt_hci_h4: hal_close
,11-24 12:18:29.071  4724  4786 I bt_userial_vendor: device fd = 54 close
,11-24 12:18:29.163  5767  5767 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.163  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 12:18:29.176  5,767  5767 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12,:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:18:29.176  5767  5767 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:18:29.176  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:18:29.181  4724  4783 D bt_stack_manager: event_shut_down_stack finished.
11-24 12:18:29.183  4724  4782 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-24 12:18:29.184  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 12:18:29.185  4724  4782 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 12:18:29.186  4724  4724 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 12:18:29.186  4724  4724 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 12:18:29.186  4724  4724 D BtGatt.GattService: stop()
11-24 12:18:29.187  4724  4724 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 12:18:29.189  4724  4724 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:29.189  4724  4724 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:29.189  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:29.190  4724  4724 V BluetoothAdapterState: isBleTurningOff()=true
11-24 12:18:29.190  4724  4782 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 12:18:29.190  4724  4782 D BluetoothAdapterProperties: Setting state to 10
11-24 12:18:29.190  4724  4782 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 12:18:29.191  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:18:29.191   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-24 12:18:29.192  4724  4782 I BluetoothAdapterState: Entering OffState
11-24 12:18:29.198  4724  4724 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 12:18:29.198  4724  4724 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 12:18:29.198  4724  4724 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 12:18:29.199  4724  4783 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-24 12:18:29.205  4724  4724 I art     : System.exit called, status: 0
11-24 12:18:29.206  4724  4724 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-24 12:18:29.209  4020  4020 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 12:18:29.212  4020  4020 D SystemUpdateService: onCreate
11-24 12:18:29.215  4020  4020 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:18:29.222  4020  4020 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-24 12:18:29.225  4020  5452 I iu.UploadsManager: num queued entries: 0
11-24 12:18:29.225  4020  5452 I iu.UploadsManager: num updated entries: 0
11-24 12:18:29.226  4020  5452 I iu.SyncManager: NEXT; no task
11-24 12:18:29.228  5738  5738 D DockEventReceiver: finishStartingService: stopping service
11-24 12:18:29.234  4020  4020 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 12:18:29.236  4020  4020 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 12:18:29.247   932  3592 I ActivityManager: Start proc 5800:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-24 12:18:29.240  4020  5798 I SystemUpdateService: active receiver: enabled
,11-24 12:18:29.268  4020  5798 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:18:29.268   932   943 I ActivityManager: Process com.android.bluetooth (pid 4724) has died
,11-24 12:18:29.291  4020  5798 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 12:18:29.291  4020  5798 I SystemUpdateService: now status is 0 (complete)
11-24 12:18:29.291  4020  5798 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:18:29.291  4020  5798 I SystemUpdateService: file has been verified
11-24 12:18:29.291  4020  5798 I SystemUpdateService: OTA package size = 21989297
,11-24 12:18:29.296  5800  5800 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 12:18:29.299  5800  5800 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:18:29.306  5800  5800 D SprintDMHelper: simOperator: 
,11-24 12:18:29.306  5800  5800 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:18:29.318   932  3206 I ActivityManager: Start proc 5814:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 12:18:29.319   932  3206 I ActivityManager: Killing 5174:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-24 12:18:29.332  4020  5798 I SystemUpdateService: showing system update notification
,11-24 12:18:29.387   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 12:18:29.429  4020  4020 D SystemUpdateService: onDestroy
,11-24 12:18:29.433   932  4322 I ActivityManager: Killing 5499:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-24 12:18:29.444  5054  5828 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 12:18:29.479   932  5812 I ActivityManager: Killing 5310:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 12:18:29.568  5767  5784 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 12:18:29.577   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5dd8ee4:true
,11-24 12:18:29.691   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:18:29.960   511   926 E Netd    : netlink response contains error (No such file or directory)
,11-24 12:18:29.962   932  3018 E NetdConnector: NDC Command {113 network destroy 100} took too long (1078ms)
,11-24 12:18:29.962   932  3018 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 12:18:29.963   932  3016 E NetdConnector: NDC Command {114 interface ipv6 wlan0 disable} took too long (1079ms)
11-24 12:18:29.964   932  3014 E NetdConnector: NDC Command {115 bandwidth setglobalalert 2097152} took too long (1076ms)
11-24 12:18:29.964   932  3016 D DhcpClient: doQuit
,11-24 12:18:29.964   932  3016 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 12:18:29.966   932  5428 D DhcpClient: onQuitting
,11-24 12:18:29.966  3516  3516 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 12:18:29.967   511   926 D TetherController: Setting IP forward enable = 0
11-24 12:18:29.972  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:18:29.972  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:18:29.972  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:29.973  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 12:18:29.991   932   945 I ActivityManager: Start proc 5835:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 12:18:29.992  3516  3516 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 12:18:29.997  3516  3516 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 12:18:30.024  5835  5835 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 12:18:30.032   932  5812 I ActivityManager: Killing 3919:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 12:18:30.038  3516  3516 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 12:18:30.044  3516  3516 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 12:18:30.147   932  3016 D wifi    : In wifi stop Hal
,11-24 12:18:30.150   932  3016 D wifi    : halHandle = 0x7f6eedd680, mVM = 0x7f8b50d140, mCls = 0x100a02
11-24 12:18:30.151   932  3515 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 12:18:30.151  5054  5054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 12:18:30.151   932  3515 D WifiHAL : Got a signal to exit!!!
11-24 12:18:30.151   932  3515 I WifiHAL : Exit wifi_event_loop
11-24 12:18:30.151   932  3016 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 12:18:30.152   932  3016 E WifiHAL : Event processing terminated
11-24 12:18:30.152   932  3016 D wifi    : In wifi cleaned up handler
,11-24 12:18:30.152   932  3016 I WifiHAL : Internal cleanup completed
11-24 12:18:30.153  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:30.156  4172  4291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 12:18:30.177   932  3515 D wifi    : set interface wlan0 flags (DOWN)
,11-24 12:18:30.177   932  3016 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 12:18:30.384   932   949 D Tethering: InitialState.processMessage what=4
,11-24 12:18:30.395   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 12:18:33.791   932  3854 D WifiService: setWifiEnabled: true pid=5670, uid=10077
11-24 12:18:33.792   932  3854 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:18:33.799   511   926 D SoftapController: Softap fwReload - Ok
,11-24 12:18:33.804   511   926 D CommandListener: Setting iface cfg
,11-24 12:18:33.805   511   926 D CommandListener: Trying to bring down wlan0
11-24 12:18:33.806   511   926 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:18:33.812   932  3016 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 12:18:34.372   932  3016 D wifi    : set interface wlan0 flags (UP)
,11-24 12:18:34.375   932  3016 I WifiHAL : Initializing wifi
,11-24 12:18:34.375   932  3016 I WifiHAL : Creating socket
,11-24 12:18:34.376   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 12:18:34.378   932  3016 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 12:18:34.379   932  3016 D wifi    : Did set static halHandle = 0x7f6eedd680
,11-24 12:18:34.379   932  3016 D wifi    : halHandle = 0x7f6eedd680, mVM = 0x7f8b50d140, mCls = 0x1018ee
11-24 12:18:34.380   932  3016 D wifi    : array field set
11-24 12:18:34.380   932  3016 I WifiNative-HAL: interface[0] = wlan0
11-24 12:18:34.383   932  5850 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547321927296
11-24 12:18:34.383   932  5850 D wifi    : waitForHalEvents called, vm = 0x7f8b50d140, obj = 0x1018ee, env = 0x7f6ca63080
,11-24 12:18:34.435  5851  5851 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 12:18:34.484   932  3016 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 12:18:34.491  5851  5851 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:18:34.493  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:34.528  5851  5851 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:18:34.528  5851  5851 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 12:18:34.546   932  3016 D WifiConfigStore: Loading config and enabling all networks 
,11-24 12:18:34.548  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:18:34.548  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:18:34.548  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:18:34.548  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 12:18:34.569   932  3016 D WifiConfigStore: loaded 0 passpoint configs
,11-24 12:18:34.569   932  3016 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 12:18:34.570   932  3016 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 12:18:34.570   932  3016 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 12:18:34.571   932  3016 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 12:18:34.571   932  3016 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 12:18:34.571   932  3016 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 12:18:34.572   932  3016 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 12:18:34.572   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 12:18:34.572   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 12:18:34.572   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 12:18:34.572   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-24 12:18:34.572   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 12:18:34.574   932  3016 D WifiNative-HAL: Setting external_sim to 1
,11-24 12:18:34.574   932  3016 D wifi    : setting dfs flag to true, 0x7f6cb3ebc0
11-24 12:18:34.574  5054  5054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 12:18:34.575   932  3016 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 12:18:34.575   932  3016 D wifi    : setting scan oui 0x7f6cb3ebc0
11-24 12:18:34.575   932  3016 D WifiHAL : Sending mac address OUI
,11-24 12:18:34.578   932  3016 E native  : do suspend false
,11-24 12:18:34.584   932  3016 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 12:18:34.584   932   932 D RttService: SCAN_AVAILABLE : 3
11-24 12:18:34.585   932  3125 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 12:18:34.588   511   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 12:18:34.589   511   926 D CommandListener: Setting iface cfg
,11-24 12:18:34.596   932  3015 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 12:18:34.596   932  3015 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 12:18:34.600   932  3015 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 12:18:34.605   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129225 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-24 12:18:34.605   932  3015 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 12:18:34.691   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:35.692   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:36.693   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:37.669  5851  5851 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:18:37.677  5851  5851 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:18:37.683  5851  5851 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:18:37.693   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:37.708   932  3016 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 12:18:37.709   932  3016 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 12:18:37.709   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:18:37.721   932  3016 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 12:18:37.755   932  3016 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 12:18:37.760  5851  5851 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 12:18:38.186  5851  5851 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 12:18:38.223  5851  5851 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 12:18:38.225  5851  5851 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 12:18:38.233   932  3016 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 12:18:38.234   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:18:38.234   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 12:18:38.252   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:18:38.265   511   926 D CommandListener: Setting iface cfg
,11-24 12:18:38.271   932  3016 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 12:18:38.277   932  5859 D DhcpClient: Receive thread started
,11-24 12:18:38.282   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 12:18:38.283   932  3016 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 12:18:38.283   932  3018 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 12:18:38.365   932  3016 E native  : do suspend false
,11-24 12:18:38.378   932  5858 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 12:18:38.401   932  5859 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
11-24 12:18:38.401   932  5858 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-24 12:18:38.404   932  5858 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 12:18:38.417   932  5859 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 12:18:38.418   932  5858 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 12:18:38.422   511   926 D CommandListener: Setting iface cfg
,11-24 12:18:38.427   932  3016 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 12:18:38.435   932  5858 D DhcpClient: Scheduling renewal in 86399s
,11-24 12:18:38.455   932  3016 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 12:18:38.456   932  3016 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 12:18:38.458   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 12:18:38.460   932  3018 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 12:18:38.470   932  3016 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 12:18:38.504   932  3018 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 12:18:38.504   932  3018 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 12:18:38.508   932  3018 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 12:18:38.512   932  3018 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 12:18:38.514   932  3018 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 12:18:38.521   932  3018 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 12:18:38.524   932  3018 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 12:18:38.525   932  3018 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 12:18:38.525   932  3018 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 12:18:38.525   932  3016 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 12:18:38.525   932  3018 D ConnectivityService:    accepting network in place of null
11-24 12:18:38.525   932  3016 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 12:18:38.526   932  3018 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:18:38.532   932  5857 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133152, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 12:18:38.549   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:18:38.574   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:18:38.578   932  3018 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 12:18:38.578   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 12:18:38.578  3777  3915 W QCNEJ   : |CORE| network available: 101
11-24 12:18:38.579   932  3018 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 12:18:38.580   932   949 D Tethering: MasterInitialState.processMessage what=3
,11-24 12:18:38.581  3777  3915 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 12:18:38.582  3777  3915 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 12:18:38.583  3777  3915 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 12:18:38.586  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:18:38.586  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 12:18:38.586  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:38.586  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:18:38.593  5099  5123 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 12:18:38.593  5099  5123 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 12:18:38.594  5099  5123 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 12:18:38.594  5099  5123 E SarControlService: no key has been found,reset the power
11-24 12:18:38.594  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:18:38.594  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:18:38.594  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 12:18:38.594  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:18:38.595  5124  5124 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:18:38.597  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:18:38.597   932  5856 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 12:18:38.597  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:18:38.597  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 12:18:38.598  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:18:38.598  5124  5124 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 12:18:38.599  4002  4002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 12:18:38.602  4020  4020 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 12:18:38.603  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000ec03000000000000ffffffff]
11-24 12:18:38.603  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:18:38.603  5124  5138 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 12:18:38.604  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000ed03000000000000ffffffff]
11-24 12:18:38.604  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:18:38.604  5124  5138 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-24 12:18:38.608  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 12:18:38.608  5099  5110 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:18:38.608  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:18:38.608  5099  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 12:18:38.607  4020  4020 D SystemUpdateService: onCreate
,11-24 12:18:38.612  4020  4020 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:18:38.624  4020  4020 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 12:18:38.629  4020  5452 I iu.UploadsManager: num queued entries: 0
11-24 12:18:38.629  4020  5452 I iu.UploadsManager: num updated entries: 0
11-24 12:18:38.630  4020  5452 I iu.SyncManager: NEXT; no task
,11-24 12:18:38.634  4020  5869 I SystemUpdateService: active receiver: enabled
,11-24 12:18:38.636  4020  4020 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:18:38.638  4020  4020 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:18:38.640  5800  5800 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 12:18:38.643  5800  5800 D SprintDMHelper: simOperator: 
11-24 12:18:38.643  5800  5800 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:18:38.646   932  5856 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 11:18:38 GMT], X-Android-Received-Millis=[1479986318646], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479986318622]}
,11-24 12:18:38.647   932  3018 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 12:18:38.647   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-24 12:18:38.647   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 12:18:38.648   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 12:18:38.685  4020  5869 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:18:38.687  4020  5869 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 12:18:38.687  4020  5869 I SystemUpdateService: now status is 0 (complete)
,11-24 12:18:38.688  4020  5869 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:18:38.688  4020  5869 I SystemUpdateService: file has been verified
11-24 12:18:38.688  4020  5869 I SystemUpdateService: OTA package size = 21989297
,11-24 12:18:38.693   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:38.696  4020  5869 I SystemUpdateService: showing system update notification
,11-24 12:18:38.706   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 12:18:38.707  4020  4020 D SystemUpdateService: onDestroy
,11-24 12:18:38.749  5054  5875 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 12:18:38.798   932  4322 D WifiService: setWifiEnabled: false pid=5670, uid=10077
,11-24 12:18:38.798   932  4322 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:18:38.802   932  3016 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 12:18:38.802   932  3016 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 12:18:38.802   932  3016 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:18:38.803   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:18:38.812   932  5858 D DhcpClient: Clearing IP address
,11-24 12:18:38.812   511   926 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:18:38.814   511   926 D CommandListener: Setting iface cfg
,11-24 12:18:38.817  3619  5879 V NativeCrypto: Read error: ssl=0x7f70529d80: I/O error during system call, Connection timed out
11-24 12:18:38.818  3619  5879 V NativeCrypto: SSL shutdown failed: ssl=0x7f70529d80: I/O error during system call, Broken pipe
11-24 12:18:38.822   932  3592 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-24 12:18:38.822   932  5856 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-24 12:18:38.823   932  5856 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 12:18:38.826   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 12:18:38.826   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 12:18:38.829   537   537 E Parcel  : Reading a NULL string not supported here.
11-24 12:18:38.832   932  3018 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 12:18:38.832   932   932 D RttService: SCAN_AVAILABLE : 1
11-24 12:18:38.832   932  5856 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-24 12:18:38.833   932  3125 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 12:18:38.835   932  3016 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 12:18:38.835  3777  3915 W QCNEJ   : |CORE| network lost: 101
11-24 12:18:38.835  3777  3915 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 12:18:38.837   932  3016 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 12:18:38.847   932  5859 D DhcpClient: Receive thread stopped
,11-24 12:18:38.856   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:18:38.877   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 12:18:38.877   511   926 D CommandListener: Clearing all IP addresses on wlan0
11-24 12:18:38.877   932  3018 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 12:18:38.878   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:18:38.879   932   949 D Tethering: MasterInitialState.processMessage what=3
11-24 12:18:38.880   932  3016 D DhcpClient: doQuit
,11-24 12:18:38.881   932  3016 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 12:18:38.881   932  5858 D DhcpClient: onQuitting
11-24 12:18:38.881  5851  5851 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 12:18:38.882  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:18:38.882  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:18:38.882  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:38.882  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:18:38.883  4002  4002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 12:18:38.887  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:38.888  4020  4020 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 12:18:38.889  5099  5123 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 12:18:38.890  5099  5123 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 12:18:38.892  5099  5123 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 12:18:38.892  5099  5123 E SarControlService: no key has been found,reset the power
11-24 12:18:38.893  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:18:38.893  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:18:38.893  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 12:18:38.893  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:18:38.893  5124  5124 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 12:18:38.894  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:18:38.895  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:18:38.895  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 12:18:38.895  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:18:38.895  5124  5124 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 12:18:38.896  4020  4020 D SystemUpdateService: onCreate
11-24 12:18:38.899  4020  4020 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 12:18:38.899  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000ee03000000000000ffffffff]
11-24 12:18:38.900  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:18:38.900  5124  5138 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,11-24 12:18:38.900  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:18:38.900  5099  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:18:38.901  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000ef03000000000000ffffffff]
11-24 12:18:38.901  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:18:38.901  5124  5138 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 12:18:38.902  5851  5851 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 12:18:38.902  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:18:38.902  5099  5110 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 12:18:38.906  5851  5851 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 12:18:38.912  4020  5889 I SystemUpdateService: active receiver: enabled
,11-24 12:18:38.914  4020  4020 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 12:18:38.919  4020  5452 I iu.UploadsManager: num queued entries: 0
11-24 12:18:38.919  4020  5452 I iu.UploadsManager: num updated entries: 0
,11-24 12:18:38.923  4020  4020 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:18:38.923  5851  5851 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-24 12:18:38.925  4020  4020 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:18:38.927  5800  5800 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:18:38.931  5800  5800 D SprintDMHelper: simOperator: 
,11-24 12:18:38.931  5800  5800 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:18:38.933   511   926 E Netd    : netlink response contains error (No such file or directory)
11-24 12:18:38.934   932  3018 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 12:18:38.934   932  3018 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 12:18:38.941  4020  5889 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:18:38.943  5851  5851 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-24 12:18:38.944  5054  5893 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 12:18:38.949  5054  5054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 12:18:38.949   932  3016 D wifi    : In wifi stop Hal
11-24 12:18:38.949   932  3016 D wifi    : halHandle = 0x7f6eedd680, mVM = 0x7f8b50d140, mCls = 0x1018ee
11-24 12:18:38.950   932  5850 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 12:18:38.950   932  5850 D WifiHAL : Got a signal to exit!!!
11-24 12:18:38.950   932  5850 I WifiHAL : Exit wifi_event_loop
11-24 12:18:38.951  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:38.951   932  3016 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 12:18:38.951   932  3016 E WifiHAL : Event processing terminated
,11-24 12:18:38.951  4172  4291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 12:18:38.951   932  3016 D wifi    : In wifi cleaned up handler
11-24 12:18:38.952   932  3016 I WifiHAL : Internal cleanup completed
,11-24 12:18:38.956  4020  5452 I iu.SyncManager: NEXT; no task
11-24 12:18:38.956  4020  5889 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 12:18:38.956  4020  5889 I SystemUpdateService: now status is 0 (complete)
11-24 12:18:38.956  4020  5889 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:18:38.956  4020  5889 I SystemUpdateService: file has been verified
11-24 12:18:38.956  4020  5889 I SystemUpdateService: OTA package size = 21989297
,11-24 12:18:38.965  4020  5889 I SystemUpdateService: showing system update notification
,11-24 12:18:38.973   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-24 12:18:38.973   932  5850 D wifi    : set interface wlan0 flags (DOWN)
11-24 12:18:38.974   932  3016 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 12:18:38.974  4020  4020 D SystemUpdateService: onDestroy
,11-24 12:18:39.178   932   949 D Tethering: InitialState.processMessage what=4
,11-24 12:18:39.184   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 12:18:39.579   932  3018 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 12:18:39.694   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:18:43.838   932   949 I ActivityManager: Start proc 5895:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 12:18:43.931  5895  5895 D AdapterServiceConfig: Adding HeadsetService
,11-24 12:18:43.931  5895  5895 D AdapterServiceConfig: Adding A2dpService
11-24 12:18:43.932  5895  5895 D AdapterServiceConfig: Adding HidService
,11-24 12:18:43.932  5895  5895 D AdapterServiceConfig: Adding HealthService
,11-24 12:18:43.932  5895  5895 D AdapterServiceConfig: Adding PanService
,11-24 12:18:43.932  5895  5895 D AdapterServiceConfig: Adding GattService
11-24 12:18:43.932  5895  5895 D AdapterServiceConfig: Adding BluetoothMapService
,11-24 12:18:43.932  5895  5895 D AdapterServiceConfig: Adding SapService
,11-24 12:18:43.945   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4cb8d4b:true
,11-24 12:18:43.945  5895  5895 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 12:18:43.948  5895  5895 I bt_bluedroid: init
,11-24 12:18:43.948  5895  5907 I BluetoothAdapterState: Entering OffState
,11-24 12:18:43.951  5895  5908 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 12:18:43.951  5895  5908 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 12:18:43.951  5895  5908 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 12:18:43.951  5895  5908 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 12:18:43.951  5895  5895 I bt_bluedroid: get_profile_interface socket
,11-24 12:18:43.953  5895  5911 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 12:18:43.953  5895  5895 I bt_bluedroid: get_profile_interface sdp
,11-24 12:18:43.955  5895  5911 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:18:43.958  5895  5906 I bt_bluedroid: config_hci_snoop_log
11-24 12:18:43.960   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 12:18:43.963  5895  5907 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 12:18:43.964  5895  5907 D BluetoothAdapterProperties: Setting state to 14
11-24 12:18:43.964  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 12:18:43.966  5895  5907 D BluetoothBondStateMachine: make
,11-24 12:18:43.967  5895  5912 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 12:18:43.970  5895  5907 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:18:43.971  5895  5895 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 12:18:43.973  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:18:43.974  5895  5895 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 12:18:43.975  5895  5895 D BtGatt.GattService: Received start request. Starting profile...
,11-24 12:18:43.975  5895  5895 D BtGatt.GattService: start()
11-24 12:18:43.976  5895  5895 I bt_bluedroid: get_profile_interface gatt
,11-24 12:18:43.977  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:43.977  5895  5895 D BtGatt.AdvertiseManager: advertise manager created
,11-24 12:18:43.982  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:43.982  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:43.982  5895  5895 V BluetoothAdapterState: isBleTurningOn()=true
11-24 12:18:43.982  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:43.982  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 12:18:43.983  5895  5907 I bt_bluedroid: bt_bluedroid
,11-24 12:18:43.984  5895  5908 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 12:18:43.984  5895  5908 I bt_hci  : start_up
,11-24 12:18:43.989  5895  5908 I bt_vendor: alloc value 0xf3ca3871
,11-24 12:18:43.989  5895  5908 I bt_vendor: init
11-24 12:18:43.989  5895  5908 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 12:18:43.989  5895  5908 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 12:18:44.100  5895  5908 D bt_hci  : start_up starting async portion
11-24 12:18:44.101  5895  5915 I bt_hci  : event_finish_startup
11-24 12:18:44.101  5895  5915 I bt_hci_h4: hal_open
,11-24 12:18:44.101  5895  5915 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 12:18:44.104  5895  5915 I bt_userial_vendor: device fd = 54 open
,11-24 12:18:44.098  5916  5916 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:18:44.118  5895  5915 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 12:18:44.121  5895  5915 D bt_hwcfg: Chipset BCM4358A3
,11-24 12:18:44.121  5895  5915 D bt_hwcfg: Target name = [BCM4358A3]
11-24 12:18:44.121  5895  5915 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 12:18:44.502  5895  5915 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 12:18:44.503  5895  5915 D bt_hwcfg: Settlement delay -- 100 ms
11-24 12:18:44.503  5895  5915 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 12:18:44.637  5895  5915 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 12:18:44.637  5895  5915 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 12:18:44.639  5895  5915 I bt_hwcfg: vendor lib fwcfg completed
11-24 12:18:44.639  5895  5915 I bt_vendor: firmware callback
11-24 12:18:44.639  5895  5915 I bt_hci  : firmware_config_callback
,11-24 12:18:44.648  5895  5918 I bt_btu  : btu_task pending for preload complete event
,11-24 12:18:44.649  5895  5918 I bt_btu_task: Bluetooth chip preload is complete
11-24 12:18:44.649  5895  5918 I bt_btu  : btu_task received preload complete event
,11-24 12:18:44.658  5895  5918 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 12:18:44.658  5895  5918 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 12:18:44.658  5895  5918 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 12:18:44.659  5895  5918 I         : BTE_InitTraceLevels -- TRC_GATT
,11-24 12:18:44.660  5895  5918 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 12:18:44.660  5895  5918 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 12:18:44.660  5895  5918 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 12:18:44.743  5895  5918 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c21549
11-24 12:18:44.743  5895  5918 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c21549 
,11-24 12:18:44.766  5895  5911 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 12:18:44.767  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 12:18:44.767  5895  5911 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 12:18:44.770  5895  5911 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:18:44.774  5895  5911 D BluetoothAdapterProperties: Scan Mode:20
,11-24 12:18:44.774  5895  5911 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 12:18:44.774  5895  5911 D bt_hci  : do_postload posting postload work item
,11-24 12:18:44.774  5895  5915 I bt_hci  : event_postload
11-24 12:18:44.774  5895  5915 I bt_vendor: sco_config_cb
11-24 12:18:44.774  5895  5915 I bt_hci  : sco_config_callback postload finished.
,11-24 12:18:44.779  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:44.781  5895  5915 I bt_vendor: low_power_mode_cb
,11-24 12:18:44.782  5895  5911 D bt_bte_conf: Device ID record 1 : primary
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   vendorId            = 000f
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   vendorIdSource      = 0001
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   product             = 1200
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   version             = 1436
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   clientExecutableURL = 
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   serviceDescription  = 
11-24 12:18:44.782  5895  5911 D bt_bte_conf:   documentationURL    = 
11-24 12:18:44.782  5895  5911 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-24 12:18:44.783  5895  5908 D bt_stack_manager: event_start_up_stack finished
11-24 12:18:44.783  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 12:18:44.783  5895  5907 D BluetoothAdapterProperties: Setting state to 15
11-24 12:18:44.783  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 12:18:44.785  5895  5907 I BluetoothAdapterState: Entering BleOnState
,11-24 12:18:44.787  5895  5907 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 12:18:44.788  5895  5907 D BluetoothAdapterProperties: Setting state to 11
11-24 12:18:44.788  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 12:18:44.792  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:44.794  5895  5895 D HeadsetService: Received start request. Starting profile...
11-24 12:18:44.796  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:44.796  5895  5895 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 12:18:44.797  5895  5895 D HeadsetStateMachine: make
,11-24 12:18:44.805  5895  5907 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:18:44.806  5895  5895 D HeadsetStateMachine: max_hf_connections = 1
,11-24 12:18:44.806  5895  5895 I bt_bluedroid: get_profile_interface handsfree
11-24 12:18:44.807  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 12:18:44.807  5895  5911 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-24 12:18:44.810  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:18:44.811  5895  5895 D A2dpService: Received start request. Starting profile...
,11-24 12:18:44.811  5895  5895 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 12:18:44.812  5895  5895 I bt_bluedroid: get_profile_interface avrcp
,11-24 12:18:44.817  5895  5895 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 12:18:44.818  5895  5895 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 12:18:44.818  5895  5895 D A2dpStateMachine: make
11-24 12:18:44.819  5895  5895 I bt_bluedroid: get_profile_interface a2dp
,11-24 12:18:44.819  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 12:18:44.821  5895  5927 D A2dpStateMachine: Enter Disconnected: -2
,11-24 12:18:44.821  5895  5895 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 12:18:44.822  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:44.823  5738  5738 D BluetoothInputDevice: Proxy object connected
,11-24 12:18:44.824  5895  5895 D HidService: Received start request. Starting profile...
11-24 12:18:44.824  5738  5738 D HidProfile: Bluetooth service connected
11-24 12:18:44.824  5895  5895 I bt_bluedroid: get_profile_interface hidhost
11-24 12:18:44.824  5895  5895 D HidService: setHidService(): set to: null
11-24 12:18:44.824  5895  5911 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0256d
11-24 12:18:44.824  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 12:18:44.824  5895  5895 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 12:18:44.825  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:44.826  5895  5895 D HealthService: Received start request. Starting profile...
,11-24 12:18:44.828  5895  5895 I bt_bluedroid: get_profile_interface health
,11-24 12:18:44.829  5895  5895 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 12:18:44.829  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:44.831  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:18:44.831  5895  5895 D PanService: Received start request. Starting profile...
11-24 12:18:44.831  5895  5895 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 12:18:44.831  5895  5895 I bt_bluedroid: get_profile_interface pan
11-24 12:18:44.832  5895  5911 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 12:18:44.832  5738  5738 D PanProfile: Bluetooth service connected
,11-24 12:18:44.835  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:44.836  5895  5895 D BluetoothMapService: Received start request. Starting profile...
,11-24 12:18:44.837  5895  5895 D BluetoothMapService: start()
,11-24 12:18:44.839  5895  5895 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 12:18:44.840  5895  5895 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 12:18:44.840  5895  5895 D BluetoothMapAppObserver: createReceiver()
,11-24 12:18:44.841  5895  5895 D BluetoothMapAppObserver: initObservers()
,11-24 12:18:44.842  5895  5895 D BluetoothMapAppObserver: getEnabledAccountItems()
11-24 12:18:44.844  5738  5738 D BluetoothMap: Proxy object connected
,11-24 12:18:44.844  5738  5738 D MapProfile: Bluetooth service connected
,11-24 12:18:44.844  5738  5738 D BluetoothMap: getConnectedDevices()
,11-24 12:18:44.849  5895  5895 V SapService: SapBinder()
,11-24 12:18:44.849  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:18:44.850  5895  5895 D SapService: Received start request. Starting profile...
11-24 12:18:44.850  5895  5895 V SapService: start()
,11-24 12:18:44.852  5895  5895 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:18:44.852  5895  5895 V BluetoothAdapterState: isTurningOn()=true
11-24 12:18:44.852  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.852  5895  5925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 12:18:44.852  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOn()=true
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOn()=true
,11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOn()=true
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isTurningOn()=true
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.853  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:18:44.853  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isTurningOn()=true
11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isTurningOn()=true
11-24 12:18:44.854  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:44.855  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:44.855  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 12:18:44.855  5895  5907 D BluetoothAdapterProperties: ScanMode =  20
11-24 12:18:44.855  5895  5907 D BluetoothAdapterProperties: State =  11
11-24 12:18:44.855  5895  5907 D BluetoothAdapterProperties: Setting state to 12
11-24 12:18:44.855  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 12:18:44.855  5738  5738 D BluetoothMap: Bluetooth is Not enabled
11-24 12:18:44.855   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:18:44.856  5738  5757 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 12:18:44.856  5895  5907 I BluetoothAdapterState: Entering OnState
11-24 12:18:44.857  3171  3187 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:18:44.858  5895  5911 D BluetoothAdapterProperties: Scan Mode:21
11-24 12:18:44.858  5895  5911 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 12:18:44.858  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 12:18:44.859  3171  3191 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:18:44.859  3171  3171 D BluetoothA2dp: Proxy object connected
11-24 12:18:44.859  5738  5753 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 12:18:44.861   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:18:44.861  3171  3187 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:18:44.862  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 12:18:44.863  3171  3171 D BluetoothInputDevice: Proxy object connected
,11-24 12:18:44.863  3171  3171 D HidProfile: Bluetooth service connected
11-24 12:18:44.864  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:18:44.865   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:18:44.865  5738  5757 D BluetoothMap: onBluetoothStateChange: up=true
11-24 12:18:44.865   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 12:18:44.866   932   932 D BluetoothA2dp: Proxy object connected
,11-24 12:18:44.866  3171  4047 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:18:44.868  5895  5895 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 12:18:44.868  3171  3171 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:18:44.868  5895  5895 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 12:18:44.868  3171  3171 D PanProfile: Bluetooth service connected
,11-24 12:18:44.869  3171  3187 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 12:18:44.870  5895  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:18:44.871  5738  5753 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:18:44.871  3825  4056 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:18:44.871  5895  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:18:44.872  3171  3191 D BluetoothMap: onBluetoothStateChange: up=true
11-24 12:18:44.872  5895  5895 D ObexServerSockets: Succeed to create listening sockets 
11-24 12:18:44.872  5895  5895 D ObexServerSockets0: startAccept()
11-24 12:18:44.872  5895  5895 D ObexServerSockets0: prepareForNewConnect()
11-24 12:18:44.874  3171  3171 D BluetoothMap: Proxy object connected
11-24 12:18:44.874  3171  3171 D MapProfile: Bluetooth service connected
,11-24 12:18:44.874  3171  3171 D BluetoothMap: getConnectedDevices()
11-24 12:18:44.875   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 12:18:44.875  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 12:18:44.878  5738  5738 D LocalBluetoothProfileManager: Adding local A2DP profile
11-24 12:18:44.878  5895  5895 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 12:18:44.878  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:44.878  5895  5895 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 12:18:44.878  5895  5933 D ObexServerSockets0: Accepting socket connection...
11-24 12:18:44.879  5895  5895 D BluetoothMapService: onReceive
11-24 12:18:44.879  5895  5895 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:18:44.879  5895  5895 D BluetoothMapService: STATE_ON
11-24 12:18:44.880  5895  5935 D ObexServerSockets0: Accepting socket connection...
,11-24 12:18:44.883  5895  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:18:44.884  5738  5738 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 12:18:44.884  5895  5936 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 12:18:44.884  5895  5936 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 12:18:44.890  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:18:44.892  5738  5738 D BluetoothA2dp: Proxy object connected
,11-24 12:18:44.898  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:18:44.902  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:18:44.906  5738  5738 D BluetoothPbap: Proxy object connected
11-24 12:18:44.906  5738  5738 D PbapServerProfile: Bluetooth service connected
,11-24 12:18:44.906  5895  5895 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 12:18:44.906  5895  5895 D ObexServerSockets0: prepareForNewConnect()
11-24 12:18:44.907  3171  3171 D BluetoothPbap: Proxy object connected
11-24 12:18:44.907  3171  3171 D PbapServerProfile: Bluetooth service connected
,11-24 12:18:44.914  5895  5940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:18:44.930  5895  5944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:18:44.931  5895  5944 I BtOppRfcommListener: Accept thread started.
,11-24 12:18:44.957   932   932 D BluetoothHeadset: Proxy object connected
,11-24 12:18:44.957   932   932 D BluetoothHeadset: Proxy object connected
11-24 12:18:44.957   932   932 D BluetoothHeadset: Proxy object connected
11-24 12:18:44.957  3825  3838 D BluetoothHeadset: Proxy object connected
11-24 12:18:44.958  3171  3191 D BluetoothHeadset: Proxy object connected
11-24 12:18:44.958  3171  3171 D HeadsetProfile: Bluetooth service connected
,11-24 12:18:44.959  3171  4047 D BluetoothHeadset: Proxy object connected
,11-24 12:18:44.960  3171  3171 D HeadsetProfile: Bluetooth service connected
11-24 12:18:44.961   932   949 D BluetoothHeadset: Proxy object connected
,11-24 12:18:44.965   932   949 D BluetoothHeadset: Proxy object connected
,11-24 12:18:44.972  3825  3837 D BluetoothHeadset: Proxy object connected
,11-24 12:18:44.988  5738  5753 D BluetoothHeadset: Proxy object connected
,11-24 12:18:44.989  5738  5738 D HeadsetProfile: Bluetooth service connected
,11-24 12:18:45.989  3726  3901 I Keyboard.Facilitator.LanguageModelFlusher: run()
11-24 12:18:45.989  3726  3901 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 12:18:46.020  3619  3619 I ConfigService: onCreate
,11-24 12:18:46.531   932  3018 D ConnectivityService: handlePromptUnvalidated 101
,11-24 12:18:48.815  5895  5907 D BluetoothAdapterState: Current state: ON, message: 23
11-24 12:18:48.815  5895  5907 D BluetoothAdapterProperties: Setting state to 13
11-24 12:18:48.816  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 12:18:48.817  5895  5907 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 12:18:48.824  5895  5895 D BluetoothMapService: onReceive
,11-24 12:18:48.824  5895  5911 D BluetoothAdapterProperties: Scan Mode:20
,11-24 12:18:48.824  5895  5895 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-24 12:18:48.824  5895  5895 D BluetoothMapService: STATE_TURNING_OFF
,11-24 12:18:48.824  5895  5895 D BluetoothMapService: MAP Service closeService in
11-24 12:18:48.824  5895  5895 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 12:18:48.825  5895  5895 D ObexServerSockets0: shutdown(block = true)
11-24 12:18:48.820  5895  5907 I BluetoothAdapterState: Entering PendingCommandState
11-24 12:18:48.826  5895  5895 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 12:18:48.826  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 12:18:48.826  5895  5895 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 12:18:48.827  5895  5920 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 12:18:48.827  5895  5933 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 12:18:48.827  5895  5935 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 12:18:48.834  5895  5895 I BtOppRfcommListener: stopping Accept Thread
11-24 12:18:48.834  5895  5944 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 12:18:48.835  5895  5944 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 12:18:48.835  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:18:48.835  5670  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:18:48.836  5670  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:18:48.836  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 12:18:48.836  5670  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:18:48.837  5895  5895 D HeadsetService: Received stop request...Stopping profile...
11-24 12:18:48.838  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:18:48.841   932   932 D BluetoothHeadset: Proxy object disconnected
,11-24 12:18:48.841   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:48.841   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:48.842  3825  4056 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:48.843  3171  3191 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:48.843  3171  3171 D HeadsetProfile: Bluetooth service disconnected
11-24 12:18:48.844  5738  5757 D BluetoothHeadset: Proxy object disconnected
11-24 12:18:48.846  5895  5895 D A2dpService: Received stop request...Stopping profile...
11-24 12:18:48.846  5895  5927 D A2dpStateMachine: Exit Disconnected: -1
11-24 12:18:48.847  5738  5738 D DockEventReceiver: finishStartingService: stopping service
11-24 12:18:48.847   932   932 D BluetoothA2dp: Proxy object disconnected
11-24 12:18:48.848  5738  5738 D HeadsetProfile: Bluetooth service disconnected
11-24 12:18:48.848  5738  5738 D BluetoothA2dp: Proxy object disconnected
11-24 12:18:48.851  5895  5895 D HidService: Received stop request...Stopping profile...
11-24 12:18:48.851  5895  5895 D HidService: Stopping Bluetooth HidService
,11-24 12:18:48.852  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.852  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:48.852  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.852  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:18:48.855  5738  5738 D BluetoothInputDevice: Proxy object disconnected
11-24 12:18:48.855  5738  5738 D HidProfile: Bluetooth service disconnected
,11-24 12:18:48.855  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:18:48.857  5895  5895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-24 12:18:48.857  5895  5895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 12:18:48.857  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 12:18:48.858  5895  5918 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 12:18:48.858  5895  5918 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:48.858  5895  5918 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 12:18:48.860  5895  5911 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 12:18:48.860  5895  5895 D HealthService: Received stop request...Stopping profile...
11-24 12:18:48.861  5895  5895 D PanService: Received stop request...Stopping profile...
11-24 12:18:48.862  5738  5738 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 12:18:48.862  5738  5738 D PanProfile: Bluetooth service disconnected
,11-24 12:18:48.867  5895  5895 D BluetoothMapService: Received stop request...Stopping profile...
,11-24 12:18:48.867  5895  5895 D BluetoothMapService: stop()
11-24 12:18:48.868  5895  5895 D BluetoothMapAppObserver: deinitObservers()
11-24 12:18:48.868  5895  5895 D BluetoothMapAppObserver: removeReceiver()
,11-24 12:18:48.870  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.871  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:48.871  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.871  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:48.871  5738  5738 D BluetoothMap: Proxy object disconnected
11-24 12:18:48.871  5738  5738 D MapProfile: Bluetooth service disconnected
,11-24 12:18:48.871  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 12:18:48.872  5895  5918 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:48.872  5895  5918 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:48.872  5895  5918 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 12:18:48.872  5895  5918 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:18:48.872  5895  5895 D SapService: Received stop request...Stopping profile...
11-24 12:18:48.872  5895  5895 V SapService: stop()
11-24 12:18:48.872  5895  5918 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 12:18:48.872  5895  5918 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:18:48.872  3171  3171 D BluetoothA2dp: Proxy object disconnected
11-24 12:18:48.872  3171  3171 D BluetoothInputDevice: Proxy object disconnected
11-24 12:18:48.873  3171  3171 D HidProfile: Bluetooth service disconnected
11-24 12:18:48.873  3171  3171 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 12:18:48.873  3171  3171 D PanProfile: Bluetooth service disconnected
11-24 12:18:48.873  3171  3171 D BluetoothMap: Proxy object disconnected
11-24 12:18:48.873  3171  3171 D MapProfile: Bluetooth service disconnected
11-24 12:18:48.874  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.874  5895  5895 V BluetoothAdapterState: isTurningOn()=false
,11-24 12:18:48.874  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.874  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:48.874  5895  5895 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 12:18:48.874  5895  5895 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 12:18:48.875  3171  3171 D BluetoothPbap: Proxy object disconnected
11-24 12:18:48.876  3171  3171 D PbapServerProfile: Bluetooth service disconnected
,11-24 12:18:48.876  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 12:18:48.877  5738  5738 D BluetoothPbap: Proxy object disconnected
11-24 12:18:48.877  5738  5738 D PbapServerProfile: Bluetooth service disconnected
,11-24 12:18:48.877  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.877  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:48.877  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.877  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:48.877  5895  5895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 12:18:48.878  5895  5911 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 12:18:48.878  5895  5895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 12:18:48.878  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.878  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:48.878  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.878  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:48.878  5895  5895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 12:18:48.878  5895  5895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 12:18:48.879  5895  5895 D BluetoothMapService: MAP Service closeService in
11-24 12:18:48.879  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.879  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:48.879  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.879  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:48.879  5895  5895 D BluetoothMapService: cleanup()
11-24 12:18:48.879  5895  5895 D BluetoothMapService: MAP Service closeService in
11-24 12:18:48.880  5895  5895 V BluetoothAdapterState: isTurningOff()=true
11-24 12:18:48.880  5895  5895 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:48.880  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:48.880  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:18:48.881  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 12:18:48.881  5895  5907 D BluetoothAdapterProperties: Setting state to 15
11-24 12:18:48.881  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 12:18:48.881  5895  5907 I BluetoothAdapterState: Entering BleOnState
,11-24 12:18:48.881   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 12:18:48.882  5738  5753 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 12:18:48.882  3171  4047 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:18:48.883  3171  3187 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:48.883  5738  5757 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:48.883  5738  5753 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 12:18:48.884   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:48.884  3171  3191 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 12:18:48.885  5738  5757 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:18:48.885   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:48.885  5738  5753 D BluetoothMap: onBluetoothStateChange: up=false
11-24 12:18:48.885   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 12:18:48.886  3171  4047 D BluetoothPan: onBluetoothStateChange on: false
,11-24 12:18:48.886  3171  3187 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 12:18:48.887  5738  5757 D BluetoothPan: onBluetoothStateChange on: false
11-24 12:18:48.887  3825  3838 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:18:48.888  3171  3191 D BluetoothMap: onBluetoothStateChange: up=false
11-24 12:18:48.888  5895  5907 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 12:18:48.888  5895  5907 D BluetoothAdapterProperties: Setting state to 16
11-24 12:18:48.888  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 12:18:48.889  5895  5907 D BluetoothAdapterProperties: onBleDisable
,11-24 12:18:48.889  5895  5907 I BluetoothAdapterState: Entering PendingCommandState
11-24 12:18:48.889  5895  5908 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 12:18:48.890  5895  5918 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 12:18:48.890  5895  5918 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:18:48.891  5895  5911 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:18:48.891  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:48.891  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 12:18:48.894  5670  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:48.898  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:18:48.900  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:18:49.107  5895  5911 I bt_hci  : shut_down
,11-24 12:18:49.111  5895  5915 D bt_hwcfg: hw_epilog_process
,11-24 12:18:49.113  5895  5915 I bt_vendor: low_power_mode_cb
,11-24 12:18:49.116  5895  5915 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 12:18:49.116  5895  5915 I bt_vendor: epilog_cb
11-24 12:18:49.116  5895  5915 I bt_hci  : epilog_finished_callback
,11-24 12:18:49.120  5895  5911 I bt_hci_h4: hal_close
,11-24 12:18:49.121  5895  5911 I bt_userial_vendor: device fd = 54 close
,11-24 12:18:49.236  5895  5908 D bt_stack_manager: event_shut_down_stack finished.
,11-24 12:18:49.237  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 12:18:49.241  5895  5907 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 12:18:49.241  5895  5895 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 12:18:49.243  5895  5895 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 12:18:49.243  5895  5895 D BtGatt.GattService: stop()
,11-24 12:18:49.243  5895  5895 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 12:18:49.247  5895  5895 V BluetoothAdapterState: isTurningOff()=false
11-24 12:18:49.247  5895  5895 V BluetoothAdapterState: isTurningOn()=false
,11-24 12:18:49.248  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:18:49.248  5895  5895 V BluetoothAdapterState: isBleTurningOff()=true
11-24 12:18:49.248  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 12:18:49.249  5895  5907 D BluetoothAdapterProperties: Setting state to 10
,11-24 12:18:49.249  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 12:18:49.250  5895  5907 I BluetoothAdapterState: Entering OffState
11-24 12:18:49.251   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 12:18:49.265  5895  5895 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 12:18:49.265  5895  5895 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 12:18:49.265  5895  5895 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 12:18:49.267  5895  5908 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 12:18:49.273  5895  5895 I art     : System.exit called, status: 0
,11-24 12:18:49.274  5895  5895 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 12:18:49.303   932  3268 I ActivityManager: Process com.android.bluetooth (pid 5895) has died
,11-24 12:18:49.695   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:50.696   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:51.051  3619  3619 I ConfigService: onDestroy
,11-24 12:18:51.697   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:52.698   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:53.699   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:53.813  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:18:53.813  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:18:53.819  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:18:53.819  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a277608 removed from the list
11-24 12:18:53.819  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:18:53.822  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:18:53.822  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1807b87 added. We now have 4 listener(s)
11-24 12:18:53.822  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:18:53.824  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:18:53.825  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1807b87 removed from the list
11-24 12:18:53.825  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:18:53.828  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:18:53.828  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac1eab4 added. We now have 4 listener(s)
,11-24 12:18:53.829  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:18:54.699   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 12:18:58.841  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:18:58.874   932   949 I ActivityManager: Start proc 5953:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 12:18:58.969  5953  5953 D AdapterServiceConfig: Adding HeadsetService
,11-24 12:18:58.969  5953  5953 D AdapterServiceConfig: Adding A2dpService
11-24 12:18:58.969  5953  5953 D AdapterServiceConfig: Adding HidService
11-24 12:18:58.970  5953  5953 D AdapterServiceConfig: Adding HealthService
11-24 12:18:58.970  5953  5953 D AdapterServiceConfig: Adding PanService
11-24 12:18:58.970  5953  5953 D AdapterServiceConfig: Adding GattService
,11-24 12:18:58.970  5953  5953 D AdapterServiceConfig: Adding BluetoothMapService
11-24 12:18:58.970  5953  5953 D AdapterServiceConfig: Adding SapService
,11-24 12:18:58.980   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4745ee7:true
,11-24 12:18:58.981  5953  5953 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 12:18:58.984  5953  5953 I bt_bluedroid: init
11-24 12:18:58.985  5953  5965 I BluetoothAdapterState: Entering OffState
,11-24 12:18:58.986  5953  5966 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 12:18:58.987  5953  5966 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 12:18:58.987  5953  5966 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 12:18:58.987  5953  5966 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 12:18:58.988  5953  5953 I bt_bluedroid: get_profile_interface socket
,11-24 12:18:58.989  5953  5969 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 12:18:58.990  5953  5953 I bt_bluedroid: get_profile_interface sdp
11-24 12:18:58.991  5953  5969 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:18:58.994  5953  5964 I bt_bluedroid: config_hci_snoop_log
11-24 12:18:58.995   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 12:18:58.999  5953  5965 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 12:18:58.999  5953  5965 D BluetoothAdapterProperties: Setting state to 14
11-24 12:18:58.999  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 12:18:59.000  5953  5965 D BluetoothBondStateMachine: make
11-24 12:18:59.002  5953  5970 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 12:18:59.005  5953  5965 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:18:59.006  5953  5953 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 12:18:59.008  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:59.008  5953  5953 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 12:18:59.009  5953  5953 D BtGatt.GattService: Received start request. Starting profile...
11-24 12:18:59.009  5953  5953 D BtGatt.GattService: start()
11-24 12:18:59.009  5953  5953 I bt_bluedroid: get_profile_interface gatt
,11-24 12:18:59.010  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:18:59.010  5953  5953 D BtGatt.AdvertiseManager: advertise manager created
,11-24 12:18:59.016  5953  5953 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:18:59.016  5953  5953 V BluetoothAdapterState: isTurningOn()=false
11-24 12:18:59.016  5953  5953 V BluetoothAdapterState: isBleTurningOn()=true
11-24 12:18:59.016  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:18:59.016  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 12:18:59.018  5953  5965 I bt_bluedroid: bt_bluedroid
,11-24 12:18:59.018  5953  5966 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 12:18:59.018  5953  5966 I bt_hci  : start_up
,11-24 12:18:59.022  5953  5966 I bt_vendor: alloc value 0xf3ca3871
,11-24 12:18:59.023  5953  5966 I bt_vendor: init
11-24 12:18:59.023  5953  5966 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 12:18:59.023  5953  5966 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 12:18:59.132  5953  5966 D bt_hci  : start_up starting async portion
11-24 12:18:59.133  5953  5973 I bt_hci  : event_finish_startup
,11-24 12:18:59.133  5953  5973 I bt_hci_h4: hal_open
11-24 12:18:59.133  5953  5973 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 12:18:59.135  5953  5973 I bt_userial_vendor: device fd = 54 open
,11-24 12:18:59.131  5974  5974 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:18:59.149  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 12:18:59.152  5953  5973 D bt_hwcfg: Chipset BCM4358A3
11-24 12:18:59.152  5953  5973 D bt_hwcfg: Target name = [BCM4358A3]
11-24 12:18:59.152  5953  5973 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 12:18:59.670  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 12:18:59.670  5953  5973 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 12:18:59.670  5953  5973 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 12:18:59.804  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 12:18:59.805  5953  5973 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 12:18:59.806  5953  5973 I bt_hwcfg: vendor lib fwcfg completed
,11-24 12:18:59.806  5953  5973 I bt_vendor: firmware callback
,11-24 12:18:59.806  5953  5973 I bt_hci  : firmware_config_callback
,11-24 12:18:59.815  5953  5976 I bt_btu  : btu_task pending for preload complete event
,11-24 12:18:59.815  5953  5976 I bt_btu_task: Bluetooth chip preload is complete
11-24 12:18:59.815  5953  5976 I bt_btu  : btu_task received preload complete event
,11-24 12:18:59.821  5953  5976 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 12:18:59.821  5953  5976 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 12:18:59.821  5953  5976 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 12:18:59.821  5953  5976 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 12:18:59.821  5953  5976 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_SDP
,11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 12:18:59.822  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 12:18:59.823  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 12:18:59.917  5953  5976 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c21549
11-24 12:18:59.917  5953  5976 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c21549 
,11-24 12:18:59.933  5953  5969 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 12:18:59.935  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 12:18:59.936  5953  5969 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 12:18:59.939  5953  5969 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 12:18:59.941  5953  5969 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:18:59.941  5953  5969 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 12:18:59.941  5953  5969 D bt_hci  : do_postload posting postload work item
,11-24 12:18:59.941  5953  5973 I bt_hci  : event_postload
11-24 12:18:59.941  5953  5973 I bt_vendor: sco_config_cb
,11-24 12:18:59.941  5953  5973 I bt_hci  : sco_config_callback postload finished.
11-24 12:18:59.943  5953  5969 D bt_bte_conf: Device ID record 1 : primary
,11-24 12:18:59.943  5953  5969 D bt_bte_conf:   vendorId            = 000f
11-24 12:18:59.943  5953  5969 D bt_bte_conf:   vendorIdSource      = 0001
11-24 12:18:59.943  5953  5969 D bt_bte_conf:   product             = 1200
11-24 12:18:59.943  5953  5969 D bt_bte_conf:   version             = 1436
11-24 12:18:59.943  5953  5969 D bt_bte_conf:   clientExecutableURL = 
11-24 12:18:59.943  5953  5969 D bt_bte_conf:   serviceDescription  = 
11-24 12:18:59.943  5953  5969 D bt_bte_conf:   documentationURL    = 
11-24 12:18:59.943  5953  5969 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 12:18:59.944  5953  5966 D bt_stack_manager: event_start_up_stack finished
11-24 12:18:59.944  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-24 12:18:59.945  5953  5965 D BluetoothAdapterProperties: Setting state to 15
11-24 12:18:59.945  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 12:18:59.946  5953  5965 I BluetoothAdapterState: Entering BleOnState
11-24 12:18:59.951  5953  5965 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 12:18:59.951  5953  5965 D BluetoothAdapterProperties: Setting state to 11
11-24 12:18:59.951  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-24 12:18:59.957  5953  5973 I bt_vendor: low_power_mode_cb
,11-24 12:18:59.964  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:59.966  5953  5953 D HeadsetService: Received start request. Starting profile...
11-24 12:18:59.969  5953  5953 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 12:18:59.969  5953  5953 D HeadsetStateMachine: make
,11-24 12:18:59.978  5953  5965 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:18:59.987  5953  5953 D HeadsetStateMachine: max_hf_connections = 1
11-24 12:18:59.987  5953  5953 I bt_bluedroid: get_profile_interface handsfree
11-24 12:18:59.987  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 12:18:59.987  5953  5969 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-24 12:18:59.991  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:18:59.991  5953  5953 D A2dpService: Received start request. Starting profile...
11-24 12:18:59.992  5953  5953 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 12:18:59.992  5953  5953 I bt_bluedroid: get_profile_interface avrcp
,11-24 12:19:00.000  5953  5953 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-24 12:19:00.000  5953  5953 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 12:19:00.000  5953  5953 D A2dpStateMachine: make
,11-24 12:19:00.001  5953  5953 I bt_bluedroid: get_profile_interface a2dp
,11-24 12:19:00.002  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 12:19:00.004  5953  5984 D A2dpStateMachine: Enter Disconnected: -2
,11-24 12:19:00.005  5953  5953 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 12:19:00.005  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:19:00.006  5953  5953 D HidService: Received start request. Starting profile...
11-24 12:19:00.006  5953  5953 I bt_bluedroid: get_profile_interface hidhost
11-24 12:19:00.006  5953  5953 D HidService: setHidService(): set to: null
11-24 12:19:00.006  5953  5969 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0256d
11-24 12:19:00.006  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 12:19:00.007  5953  5953 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-24 12:19:00.007  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:19:00.008  5953  5953 D HealthService: Received start request. Starting profile...
,11-24 12:19:00.009  5953  5953 I bt_bluedroid: get_profile_interface health
,11-24 12:19:00.010  5953  5953 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 12:19:00.011  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:19:00.011  5953  5953 D PanService: Received start request. Starting profile...
,11-24 12:19:00.011  5953  5953 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 12:19:00.011  5953  5953 I bt_bluedroid: get_profile_interface pan
11-24 12:19:00.012  5953  5969 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 12:19:00.012  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:19:00.013  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:19:00.014  5953  5953 D BluetoothMapService: Received start request. Starting profile...
11-24 12:19:00.014  5953  5953 D BluetoothMapService: start()
11-24 12:19:00.018  5953  5953 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 12:19:00.019  5953  5953 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 12:19:00.019  5953  5953 D BluetoothMapAppObserver: createReceiver()
,11-24 12:19:00.021  5953  5953 D BluetoothMapAppObserver: initObservers()
11-24 12:19:00.021  5953  5953 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 12:19:00.025  5953  5953 V SapService: SapBinder()
,11-24 12:19:00.025  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
11-24 12:19:00.025  5953  5953 D SapService: Received start request. Starting profile...
11-24 12:19:00.025  5953  5953 V SapService: start()
,11-24 12:19:00.027  5953  5953 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:19:00.027  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:19:00.028  5953  5982 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.028  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.029  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:19:00.029  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-24 12:19:00.029  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.029  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.029  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:19:00.030  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-24 12:19:00.030  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-24 12:19:00.030  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:19:00.030  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:19:00.030  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 12:19:00.030  5953  5965 D BluetoothAdapterProperties: ScanMode =  20
11-24 12:19:00.030  5953  5965 D BluetoothAdapterProperties: State =  11
11-24 12:19:00.031  5953  5965 D BluetoothAdapterProperties: Setting state to 12
11-24 12:19:00.031  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 12:19:00.031  5953  5965 I BluetoothAdapterState: Entering OnState
11-24 12:19:00.031   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:19:00.032  5738  5753 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 12:19:00.032  5953  5969 D BluetoothAdapterProperties: Scan Mode:21
11-24 12:19:00.032  5953  5969 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 12:19:00.035  3171  3191 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 12:19:00.037  5738  5738 D BluetoothInputDevice: Proxy object connected
11-24 12:19:00.037  5738  5738 D HidProfile: Bluetooth service connected
,11-24 12:19:00.040  3171  4047 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:19:00.041  5738  5753 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:19:00.041  5738  5757 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 12:19:00.043   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:19:00.043  3171  3191 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 12:19:00.044  5953  5953 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 12:19:00.044  5953  5953 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 12:19:00.045  3171  3171 D BluetoothA2dp: Proxy object connected
,11-24 12:19:00.045  5738  5753 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:19:00.046  5953  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:19:00.047  3171  3171 D BluetoothInputDevice: Proxy object connected
11-24 12:19:00.047  3171  3171 D HidProfile: Bluetooth service connected
,11-24 12:19:00.047   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:19:00.048  5738  5757 D BluetoothMap: onBluetoothStateChange: up=true
11-24 12:19:00.048  5953  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:19:00.049  5953  5953 D ObexServerSockets: Succeed to create listening sockets 
11-24 12:19:00.049  5953  5953 D ObexServerSockets0: startAccept()
11-24 12:19:00.049  5953  5953 D ObexServerSockets0: prepareForNewConnect()
,11-24 12:19:00.050   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:19:00.050   932   932 D BluetoothA2dp: Proxy object connected
11-24 12:19:00.051  3171  3191 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:19:00.051  5953  5953 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-24 12:19:00.051  5953  5953 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 12:19:00.052  5953  5991 D ObexServerSockets0: Accepting socket connection...
11-24 12:19:00.052  5738  5738 D BluetoothA2dp: Proxy object connected
11-24 12:19:00.053  3171  3187 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 12:19:00.052  5953  5990 D ObexServerSockets0: Accepting socket connection...
,11-24 12:19:00.053  3171  3171 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:19:00.054  3171  3171 D PanProfile: Bluetooth service connected
11-24 12:19:00.054  5738  5757 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:19:00.056  3825  3837 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:19:00.056  3171  4047 D BluetoothMap: onBluetoothStateChange: up=true
11-24 12:19:00.058  3171  3171 D BluetoothMap: Proxy object connected
11-24 12:19:00.058  3171  3171 D MapProfile: Bluetooth service connected
11-24 12:19:00.058  3171  3171 D BluetoothMap: getConnectedDevices()
11-24 12:19:00.058  5738  5738 D BluetoothMap: Proxy object connected
,11-24 12:19:00.058  5738  5738 D MapProfile: Bluetooth service connected
11-24 12:19:00.058  5738  5738 D BluetoothMap: getConnectedDevices()
11-24 12:19:00.059  5953  5953 D BluetoothMapService: onReceive
11-24 12:19:00.059  5953  5953 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:19:00.059  5953  5953 D BluetoothMapService: STATE_ON
11-24 12:19:00.059   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 12:19:00.061  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:19:00.061  5738  5738 D PanProfile: Bluetooth service connected
11-24 12:19:00.061  5953  5993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:19:00.064  5953  5993 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 12:19:00.064  5953  5993 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 12:19:00.067  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:19:00.073  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:19:00.073  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:19:00.079  5738  5738 D BluetoothPbap: Proxy object connected
,11-24 12:19:00.079  5738  5738 D PbapServerProfile: Bluetooth service connected
,11-24 12:19:00.083  3171  3171 D BluetoothPbap: Proxy object connected
,11-24 12:19:00.083  3171  3171 D PbapServerProfile: Bluetooth service connected
,11-24 12:19:00.087  5953  5953 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 12:19:00.087  5953  5953 D ObexServerSockets0: prepareForNewConnect()
,11-24 12:19:00.089  5953  5997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:19:00.102  5953  6001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:19:00.103  5953  6001 I BtOppRfcommListener: Accept thread started.
,11-24 12:19:00.134   932   932 D BluetoothHeadset: Proxy object connected
11-24 12:19:00.134   932   932 D BluetoothHeadset: Proxy object connected
,11-24 12:19:00.134   932   932 D BluetoothHeadset: Proxy object connected
,11-24 12:19:00.134  3825  4056 D BluetoothHeadset: Proxy object connected
,11-24 12:19:00.135  3171  4047 D BluetoothHeadset: Proxy object connected
11-24 12:19:00.135  3171  3171 D HeadsetProfile: Bluetooth service connected
11-24 12:19:00.135  5738  5989 D BluetoothHeadset: Proxy object connected
11-24 12:19:00.137  5738  5738 D HeadsetProfile: Bluetooth service connected
,11-24 12:19:00.141  3171  3191 D BluetoothHeadset: Proxy object connected
,11-24 12:19:00.142  3171  3171 D HeadsetProfile: Bluetooth service connected
11-24 12:19:00.142  5738  5753 D BluetoothHeadset: Proxy object connected
11-24 12:19:00.142  5738  5738 D HeadsetProfile: Bluetooth service connected
,11-24 12:19:00.144   932   949 D BluetoothHeadset: Proxy object connected
,11-24 12:19:00.147   932   949 D BluetoothHeadset: Proxy object connected
,11-24 12:19:00.157  3825  3838 D BluetoothHeadset: Proxy object connected
,11-24 12:19:02.790  4172  4519 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:19:03.857  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 12:19:03.864  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 12:19:03.865  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:19:03.865  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac1eab4 removed from the list
11-24 12:19:03.865  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:19:03.870  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:19:03.871  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54bf6dd added. We now have 4 listener(s)
11-24 12:19:03.871  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:19:03.874   932  3640 D WifiService: setWifiEnabled: false pid=5670, uid=10077
11-24 12:19:03.874   932  3640 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:19:08.886  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:19:08.887   932  3592 D WifiService: setWifiEnabled: true pid=5670, uid=10077
11-24 12:19:08.887   932  3592 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:19:08.899   511   926 D SoftapController: Softap fwReload - Ok
,11-24 12:19:08.905   511   926 D CommandListener: Setting iface cfg
,11-24 12:19:08.905   511   926 D CommandListener: Trying to bring down wlan0
,11-24 12:19:08.906   511   926 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:19:08.910   932  3016 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 12:19:09.576   932  3016 D wifi    : set interface wlan0 flags (UP)
,11-24 12:19:09.581   932  3016 I WifiHAL : Initializing wifi
11-24 12:19:09.581   932  3016 I WifiHAL : Creating socket
,11-24 12:19:09.588   932  3016 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 12:19:09.588   932  3016 D wifi    : Did set static halHandle = 0x7f6eedd680
11-24 12:19:09.588   932  3016 D wifi    : halHandle = 0x7f6eedd680, mVM = 0x7f8b50d140, mCls = 0x20175a
11-24 12:19:09.589   932  3016 D wifi    : array field set
11-24 12:19:09.589   932  3016 I WifiNative-HAL: interface[0] = wlan0
11-24 12:19:09.591   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 12:19:09.592   932  6006 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547321927296
,11-24 12:19:09.593   932  6006 D wifi    : waitForHalEvents called, vm = 0x7f8b50d140, obj = 0x20175a, env = 0x7f6ca64d00
,11-24 12:19:09.638  6007  6007 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 12:19:09.693   932  3016 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 12:19:09.700   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:09.709  6007  6007 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:19:09.756  6007  6007 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:19:09.756  6007  6007 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 12:19:09.772   932  3016 D WifiConfigStore: Loading config and enabling all networks 
,11-24 12:19:09.807   932  3016 D WifiConfigStore: loaded 0 passpoint configs
,11-24 12:19:09.808   932  3016 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 12:19:09.809   932  3016 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 12:19:09.810   932  3016 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 12:19:09.810   932  3016 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 12:19:09.811   932  3016 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-24 12:19:09.812   932  3016 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 12:19:09.813   932  3016 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 12:19:09.813   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 12:19:09.813   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 12:19:09.813   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 12:19:09.813   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-24 12:19:09.813   932  3016 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 12:19:09.816   932  3016 D WifiNative-HAL: Setting external_sim to 1
11-24 12:19:09.816   932  3016 D wifi    : setting dfs flag to true, 0x7f6ca7f9a0
11-24 12:19:09.816   932  3016 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 12:19:09.816  5054  5054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 12:19:09.817   932  3016 D wifi    : setting scan oui 0x7f6ca7f9a0
11-24 12:19:09.817   932  3016 D WifiHAL : Sending mac address OUI
,11-24 12:19:09.820   932  3016 E native  : do suspend false
,11-24 12:19:09.831   932  3016 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 12:19:09.832   932   932 D RttService: SCAN_AVAILABLE : 3
11-24 12:19:09.832   511   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 12:19:09.832   932  3125 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 12:19:09.833   511   926 D CommandListener: Setting iface cfg
,11-24 12:19:09.839   932  3015 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-24 12:19:09.839   932  3015 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 12:19:09.851   932  3015 D WifiNative-HAL: p2pGetDeviceAddress
11-24 12:19:09.851   932  3015 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 12:19:09.858   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164478 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-24 12:19:10.701   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:11.703   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:12.705   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:12.895  6007  6007 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:19:12.899  6007  6007 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:19:12.904  6007  6007 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:19:12.958   932  3016 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 12:19:12.959   932  3016 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 12:19:12.959   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:19:12.972   932  3016 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 12:19:13.007   932  3016 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 12:19:13.013  6007  6007 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 12:19:13.434  6007  6007 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 12:19:13.467  6007  6007 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 12:19:13.468  6007  6007 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 12:19:13.481   932  3016 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:19:13.482   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:19:13.482   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 12:19:13.500   932  3016 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:19:13.512   511   926 D CommandListener: Setting iface cfg
,11-24 12:19:13.519   932  3016 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 12:19:13.525   932  6012 D DhcpClient: Receive thread started
,11-24 12:19:13.530   932  3016 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 12:19:13.530   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 12:19:13.531   932  3018 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 12:19:13.611   932  3016 E native  : do suspend false
,11-24 12:19:13.622   932  6011 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 12:19:13.639   932  6012 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-24 12:19:13.640   932  6011 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-24 12:19:13.641   932  6011 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 12:19:13.656   932  6012 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 12:19:13.657   932  6011 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 12:19:13.662   511   926 D CommandListener: Setting iface cfg
,11-24 12:19:13.666   932  3016 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 12:19:13.670   932  6011 D DhcpClient: Scheduling renewal in 86399s
,11-24 12:19:13.680   932  3016 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 12:19:13.681   932  3016 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 12:19:13.682   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 12:19:13.684   932  3018 D ConnectivityService: Adding iface wlan0 to network 102
11-24 12:19:13.688   932  3016 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 12:19:13.705   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:13.737   932  3018 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 12:19:13.737   932  3018 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 12:19:13.739   932  3018 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-24 12:19:13.740   932  3018 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 12:19:13.742   932  3018 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 12:19:13.754   932  3018 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:19:13.758   932  3018 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 12:19:13.759   932  3018 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-24 12:19:13.759   932  3018 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 12:19:13.759   932  3018 D ConnectivityService:    accepting network in place of null
11-24 12:19:13.759   932  3016 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 12:19:13.759   932  3016 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:19:13.760   932  3018 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:19:13.771   932  6010 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168390, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 12:19:13.784   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:19:13.805   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:19:13.820   932  3018 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 12:19:13.820   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:19:13.821   932  3018 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-24 12:19:13.822   932   949 D Tethering: MasterInitialState.processMessage what=3
11-24 12:19:13.825  3777  3915 W QCNEJ   : |CORE| network available: 102
11-24 12:19:13.827  3777  3915 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 12:19:13.828  3777  3915 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 12:19:13.829  3777  3915 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 12:19:13.832  5099  5123 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 12:19:13.840  5099  5123 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 12:19:13.840  5099  5123 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 12:19:13.840  5099  5123 E SarControlService: no key has been found,reset the power
11-24 12:19:13.841  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:19:13.841  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:19:13.841  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 12:19:13.841  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:19:13.841  5124  5124 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:19:13.842  5099  5136 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:19:13.842  5099  5136 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:19:13.842  5099  5136 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 12:19:13.843  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:19:13.843  5124  5124 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 12:19:13.845  4020  4020 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 12:19:13.850   932  6009 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 12:19:13.849  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000f003000000000000ffffffff]
11-24 12:19:13.852  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:19:13.852  5124  5138 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 12:19:13.853  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:19:13.853  5099  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:19:13.853  4020  4020 D SystemUpdateService: onCreate
,11-24 12:19:13.855  4002  4002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 12:19:13.859  4020  4020 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:19:13.861  5124  5138 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2f1a56d HexData = [00000000f103000000000000ffffffff]
,11-24 12:19:13.861  5124  5138 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:19:13.861  5124  5138 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 12:19:13.862  5124  5124 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:19:13.862  5099  5110 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 12:19:13.874  4020  4020 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 12:19:13.885  4020  6022 I SystemUpdateService: active receiver: enabled
,11-24 12:19:13.887  4020  4020 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:19:13.888  4020  4020 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:19:13.890  5800  5800 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:19:13.894  5800  5800 D SprintDMHelper: simOperator: 
,11-24 12:19:13.894  5800  5800 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 12:19:13.894  4020  5452 I iu.UploadsManager: num queued entries: 0
,11-24 12:19:13.910   932  6009 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 11:19:13 GMT], X-Android-Received-Millis=[1479986353909], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479986353876]}
,11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:19:13.910  5670  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:19:13.911   932  3018 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 12:19:13.911   932  3018 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 12:19:13.911   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 12:19:13.912   932  3018 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 12:19:13.912  5670  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:19:13.913  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:13.913  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54bf6dd removed from the list
11-24 12:19:13.913  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:19:13.914  4020  5452 I iu.UploadsManager: num updated entries: 0
,11-24 12:19:13.916  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-24 12:19:13.917  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 12:19:13.919  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5a8dea1 Bundle[{}]
11-24 12:19:13.919  5670  5718 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 12:19:13.920  5670  5718 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 12:19:13.920  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-24 12:19:13.923  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-24 12:19:13.924  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 12:19:13.925  5670  5718 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 12:19:13.931  5670  5718 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-24 12:19:13.932  5670  5718 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 12:19:13.932  5670  5718 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-24 12:19:13.934  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 12:19:13.934  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27da252 added. We now have 3 listener(s)
,11-24 12:19:13.934  4020  6022 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:19:13.935  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:13.936  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 12:19:13.936  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:13.936  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:13.936  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45f4923 added. We now have 4 listener(s)
,11-24 12:19:13.936  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:13.936  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:19:13.938  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:13.938  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ecfe20 added. We now have 4 listener(s)
,11-24 12:19:13.923  4020  5452 I iu.SyncManager: NEXT; no task
,11-24 12:19:13.939  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:13.939  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:13.939  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:13.940  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:13.940  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1623d9 added. We now have 5 listener(s)
11-24 12:19:13.940  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:19:13.940  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:19:13.940  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:13.940  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:19:13.940  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:13.940  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:13.940  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:13.940  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27da252 removed from the list
11-24 12:19:13.941  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:19:13.941  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45f4923 removed from the list
11-24 12:19:13.941  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:19:13.941  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.941  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:13.942  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.942  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.942  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.942  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:13.942  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:13.943  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:13.943  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45f4923 not in the list
11-24 12:19:13.943  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:13.943  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.944  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.944  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.944  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.944  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:13.944  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:13.945  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:13.945  4020  6022 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 12:19:13.945  4020  6022 I SystemUpdateService: now status is 0 (complete)
11-24 12:19:13.945  4020  6022 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:19:13.945  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1623d9 removed from the list
11-24 12:19:13.945  4020  6022 I SystemUpdateService: file has been verified
11-24 12:19:13.945  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:13.945  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:13.945  4020  6022 I SystemUpdateService: OTA package size = 21989297
11-24 12:19:13.945  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:13.945  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ecfe20 removed from the list
11-24 12:19:13.946  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:13.946  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2f919e added. We now have 3 listener(s)
11-24 12:19:13.947  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:13.947  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:13.947  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:13.948  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:13.948  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d3547f added. We now have 4 listener(s)
11-24 12:19:13.948  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:13.948  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:19:13.950  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 12:19:13.950  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f3dc4c added. We now have 4 listener(s)
,11-24 12:19:13.952  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 12:19:13.952  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:13.952  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:13.952  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:13.952  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bc2495 added. We now have 5 listener(s)
11-24 12:19:13.952  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:13.952  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:13.952  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-24 12:19:13.952  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:19:13.953  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:19:13.953  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 12:19:13.953  4020  6022 I SystemUpdateService: showing system update notification
,11-24 12:19:13.954  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:19:13.957  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 12:19:13.958  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:19:13.958  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:19:13.961  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.961  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:19:13.962  3619  6033 I VacuumService: Vacuum at: now=1479986353961 tag=VacuumService
11-24 12:19:13.962  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:19:13.962  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-24 12:19:13.962  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 12:19:13.965   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-24 12:19:13.967  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:13.967  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:19:13.967  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:19:13.967  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-24 12:19:13.968  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-24 12:19:13.969  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.969  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:13.970  4020  4020 D SystemUpdateService: onDestroy
,11-24 12:19:13.974  5953  5963 D BtGatt.GattService: registerClient() - UUID=7a309a22-0b58-4944-b187-72865e90951f
,11-24 12:19:13.976  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=7a309a22-0b58-4944-b187-72865e90951f, clientIf=5
11-24 12:19:13.976  5670  5681 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:19:13.977  5953  5964 D BtGatt.GattService: start scan with filters
,11-24 12:19:13.980  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 12:19:13.980  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.980  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:19:13.980  5953  5972 D BtGatt.ScanManager: handling starting scan
11-24 12:19:13.980  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.980  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:19:13.980  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:19:13.980  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 12:19:13.980  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:19:13.980  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:19:13.980  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.980  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.980  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 12:19:13.981  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.981  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:19:13.981  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.981  5953  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dc376fa
,11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.984  5670  5718 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-24 12:19:13.984  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:13.984  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 12:19:13.984  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:13.984  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:19:13.984  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 12:19:13.984  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.985  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:19:13.985  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:19:13.985  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.985  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.985  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.985  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:19:13.985  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.985  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:13.986  5953  5964 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:19:13.986  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:19:13.986  5670  5718 D BluetoothAdapter: STATE_ON
,11-24 12:19:13.987  5953  5992 D BtGatt.GattService: stopScan() - queue size =1
11-24 12:19:13.987  5953  5963 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:13.988  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 12:19:13.988  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.988  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:19:13.988  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:19:13.989  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 12:19:13.989  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:19:13.989  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.990  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.990  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:19:13.990  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.991  3619  6036 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-24 12:19:13.991  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.991  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.993  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.993  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.993  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.993  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:19:13.993  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:19:13.993  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:19:13.993  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:19:13.993  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:13.993  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:19:13.993  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:19:13.993  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.993  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:13.994  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:19:13.994  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:19:13.994  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:19:13.994  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:13.994  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.994  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:13.994  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal,.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.994  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:13.994  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2f919e removed from the list
11-24 12:19:13.994  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.994  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:13.994  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:19:13.994  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:19:13.994  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d3547f removed from the list
11-24 12:19:13.994  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:19:13.994  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:19:13.994  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.994  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.994  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.994  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.996  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.996  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:13.996  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 12:19:13.996  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.996  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.996  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.996  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:13.996  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:13.996  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:13.996  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d3547f not in the list
11-24 12:19:13.996  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.996  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.998  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:13.998  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.998  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:13.998  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:13.998  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:13.998  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:13.998  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bc2495 removed from the list
11-24 12:19:13.998  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:13.998  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:13.998  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:13.998  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f3dc4c removed from the list
,11-24 12:19:13.999  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:13.999  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e3676 added. We now have 3 listener(s)
11-24 12:19:14.000  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:14.000  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:14.000  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:14.000  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:14.000  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7995477 added. We now have 4 listener(s)
11-24 12:19:14.000  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:14.001  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:19:14.002  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 12:19:14.002  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0f68e4 added. We now have 4 listener(s)
11-24 12:19:14.003  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:14.003  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:14.003  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:19:14.004  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:19:14.004  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdd514d added. We now have 5 listener(s)
11-24 12:19:14.004  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:14.004  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:14.004  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:14.004  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:19:14.005  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:19:14.005  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:19:14.005  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 12:19:14.006  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:19:14.006  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.006  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:19:14.011  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:19:14.011  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:19:14.011  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:19:14.014  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.014  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:19:14.015  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:19:14.015  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:19:14.015  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 12:19:14.016  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 12:19:14.016  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.018  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:19:14.019  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.019  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:19:14.019  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:19:14.019  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:19:14.019  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:19:14.019  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.020  5670  5718 D BluetoothAdapter: STATE_ON
,11-24 12:19:14.022  5953  5964 D BtGatt.GattService: registerClient() - UUID=5f99c6fc-0220-416f-8967-23ecc7e433d0
11-24 12:19:14.022  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:19:14.022  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.022  5953  5969 E BtGatt.ContextMap: Context not found for ID 5
11-24 12:19:14.022  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=5f99c6fc-0220-416f-8967-23ecc7e433d0, clientIf=5
11-24 12:19:14.023  5670  5681 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:19:14.023  5953  5992 D BtGatt.GattService: start scan with filters
,11-24 12:19:14.026  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 12:19:14.026  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.026  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:19:14.026  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.026  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:19:14.026  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:19:14.026  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.026  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-24 12:19:14.026  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:19:14.027  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.027  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.027  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.027  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.028  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:19:14.028  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.029  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.030  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 12:19:14.030  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.030  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.030  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.030  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:14.030  5670  5718 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:19:14.030  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:19:14.030  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:14.030  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:19:14.030  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:14.030  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 12:19:14.030  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:14.030  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:14.030  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:14.030  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e3676 removed from the list
,11-24 12:19:14.030  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:19:14.030  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7995477 removed from the list
11-24 12:19:14.031  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:19:14.031  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:19:14.031  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:14.031  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.031  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 12:19:14.031  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 12:19:14.031  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:19:14.031  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:14.031  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.032  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:19:14.032  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.032  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
11-24 12:19:14.032  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.032  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.032  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.033  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.033  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.033  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:14.033  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:19:14.033  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.033  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:19:14.033  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7995477 not in the list
11-24 12:19:14.033  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.033  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:19:14.033  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.034  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:14.034  5953  5981 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:19:14.034  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:19:14.035  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:14.035  5953  5964 D BtGatt.GattService: stopScan() - queue size =0
11-24 12:19:14.036  5953  5992 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.036  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:19:14.037  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.037  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.037  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.037  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:19:14.037  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:19:14.037  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:19:14.037  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 12:19:14.037  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.038  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:19:14.038  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.039  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.039  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:19:14.039  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.039  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.039  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:14.039  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:14.039  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:19:14.039  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:19:14.039  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdd514d removed from the list
11-24 12:19:14.039  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:14.039  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:19:14.039  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:14.039  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:14.039  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:19:14.039  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0f68e4 removed from the list
11-24 12:19:14.039  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.039  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 12:19:14.039  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:19:14.039  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.039  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.040  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.040  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:19:14.040  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.040  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:14.040  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.040  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19e4e added. We now have 3 listener(s)
11-24 12:19:14.041  5054  6027 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 12:19:14.041  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:14.041  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 12:19:14.041  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.041  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:14.041  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.041  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:14.041  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:14.041  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c305b6f added. We now have 4 listener(s)
11-24 12:19:14.041  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:14.042  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:19:14.042  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:14.042  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34cf07c added. We now have 4 listener(s)
,11-24 12:19:14.043  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:19:14.043  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.043  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:14.043  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:14.043  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:14.043  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:14.043  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f05d05 added. We now have 5 listener(s)
11-24 12:19:14.043  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:19:14.044  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:14.044  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:19:14.044  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:19:14.044  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:19:14.044  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 12:19:14.044  5953  5972 D BtGatt.ScanManager: handling starting scan
11-24 12:19:14.045  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 12:19:14.045  3619  6034 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-24 12:19:14.047  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:19:14.047  5670  5718 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:19:14.047  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:19:14.047  3619  6034 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-24 12:19:14.049  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.049  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:19:14.050  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 12:19:14.050  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:19:14.050  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 12:19:14.051  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:19:14.051  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.051  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 12:19:14.052  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.052  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:19:14.052  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:19:14.052  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:19:14.052  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:19:14.052  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.053  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:14.054  5953  5992 D BtGatt.GattService: registerClient() - UUID=bf573cab-b57f-4d3c-bac2-c3042c873ecf
11-24 12:19:14.054  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=bf573cab-b57f-4d3c-bac2-c3042c873ecf, clientIf=5
,11-24 12:19:14.055  5670  5681 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 12:19:14.055  5953  5981 D BtGatt.GattService: start scan with filters
11-24 12:19:14.056  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:19:14.056  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.056  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:19:14.056  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 12:19:14.058  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:19:14.058  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.058  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 12:19:14.058  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.058  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:19:14.058  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:19:14.058  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.058  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:19:14.058  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:19:14.058  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.058  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-24 12:19:14.058  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.058  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.059  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:19:14.059  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.061  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.061  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:19:14.061  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.061  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.062  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 12:19:14.064  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:19:14.064  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:14.064  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:19:14.064  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:14.064  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:14.064  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:14.064  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.064  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:14.064  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19e4e removed from the list
11-24 12:19:14.064  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.064  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c305b6f removed from the list
11-24 12:19:14.064  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:19:14.064  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.064  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 12:19:14.064  5670  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:19:14.064  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.064  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.065  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.065  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.065  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:19:14.065  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.065  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.065  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.065  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:14.065  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:14.065  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.066  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c305b6f not in the list
11-24 12:19:14.066  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.066  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:19:14.066  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.066  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:14.067  5953  5992 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 12:19:14.067  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:19:14.067  5670  5718 D BluetoothAdapter: STATE_ON
11-24 12:19:14.068  5953  5963 D BtGatt.GattService: stopScan() - queue size =1
11-24 12:19:14.068  5953  5981 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 12:19:14.068  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:19:14.068  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.068  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:19:14.068  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.068  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.069  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:19:14.069  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:19:14.069  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:19:14.069  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:19:14.069  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.070  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.071  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.071  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:19:14.071  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.071  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.071  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:14.071  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:14.071  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:19:14.071  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.071  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:19:14.071  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f05d05 removed from the list
11-24 12:19:14.071  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:19:14.071  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:14.071  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:14.071  5670  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:19:14.071  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:14.071  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.071  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34cf07c removed from the list
11-24 12:19:14.071  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 12:19:14.071  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:19:14.071  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.071  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.071  5670  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.071  5670  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:19:14.071  5670  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.072  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.072  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:14.072  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3f2926 added. We now have 3 listener(s)
11-24 12:19:14.072  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 12:19:14.072  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.073  5670  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:19:14.073  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:14.073  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:14.073  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:14.073  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:14.073  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed24967 added. We now have 4 listener(s)
11-24 12:19:14.073  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:14.074  3619  6034 W Uploader:  no longer exists, so no auth token.
11-24 12:19:14.075  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:19:14.075  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:19:14.075  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.075  5953  5969 E BtGatt.ContextMap: Context not found for ID 5
11-24 12:19:14.077  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:19:14.077  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e90d314 added. We now have 4 listener(s)
,11-24 12:19:14.078  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 12:19:14.078  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:19:14.078  5670  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:19:14.078  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:19:14.078  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97227bd added. We now have 5 listener(s)
11-24 12:19:14.078  5670  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:19:14.078  5670  5718 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:19:14.078  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:14.078  5670  5718 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:19:14.079  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:14.079  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:14.079  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:14.079  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3f2926 removed from the list
11-24 12:19:14.079  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.079  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed24967 removed from the list
11-24 12:19:14.079  5670  5718 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:19:14.079  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.079  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.080  3619  6036 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-24 12:19:14.080  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.080  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.080  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.080  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:14.080  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:14.080  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.080  5670  5718 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed24967 not in the list
11-24 12:19:14.080  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.080  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 12:19:14.081  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.081  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.081  5670  5718 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 12:19:14.081  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:19:14.081  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:19:14.081  5670  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:19:14.081  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:19:14.081  5670  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97227bd removed from the list
11-24 12:19:14.081  5670  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:19:14.081  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.081  5670  5718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:19:14.081  5670  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:19:14.081  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
11-24 12:19:14.081  5670  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e90d314 removed from the list
11-24 12:19:14.082  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 12:19:14.082  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 12:19:14.082  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 12:19:14.082  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:14.082  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 12:19:14.082  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:19:14.086  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 12:19:14.087  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.087  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:19:14.091  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:19:14.091  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.092  5953  5972 D BtGatt.ScanManager: handling starting scan
,11-24 12:19:14.097  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 12:19:14.097  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.097  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 12:19:14.101  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 12:19:14.101  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.101  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:19:14.101  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:19:14.109  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 12:19:14.109  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.113  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 12:19:14.113  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.114  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:19:14.118  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:19:14.118  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.118  5953  5969 E BtGatt.ContextMap: Context not found for ID 5
,11-24 12:19:14.123  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 12:19:14.124  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.124  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:19:14.128  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 12:19:14.128  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:19:14.128  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:19:14.132  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:19:14.132  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:19:14.494  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:19:14.540  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:19:14.572  5670  5670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:19:14.706   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 12:19:15.233  3619  6045 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:19:15.419  3619  6047 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:19:15.483  3619  6034 W Uploader:  no longer exists, so no auth token.
,11-24 12:19:15.496  3619  6045 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:19:15.582  3619  6047 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:19:15.660  3619  6045 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:19:16.178  5670  6048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 12:19:16.178  5670  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:16.552   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:19:16.983  5670  6048 W !!      : call onHalfStreamCopied
,11-24 12:19:16.983  5670  6048 I testCopyDataAndClose: closing input stream
,11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 12:19:17.742  5670  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 12:19:21.764   932  3018 D ConnectivityService: handlePromptUnvalidated 102
,11-24 12:19:21.812  5670  6049 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:21.812  5670  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:23.812  5670  5718 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 12:19:23.812  5670  5718 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:19:23.813  5670  5718 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 12:19:23.913  5670  6049 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 12:19:23.913  5670  6049 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:23.913  5670  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-24 12:19:23.953  5670  6050 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 12:19:23.953  5670  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:24.854   932  3016 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 12:19:25.581  5670  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 12:19:29.808  5670  6051 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 12:19:29.809  5670  6051 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 12:19:29.809  5670  6051 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-24 12:19:29.809  5670  6051 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 12:19:29.809  5670  6051 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:29.809  5670  6051 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 12:19:29.811  5670  5718 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 12:19:29.814  5670  6052 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:29.814  5670  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:19:29.814  5670  6052 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 12:19:29.815  5670  6052 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:29.815  5670  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 12:19:29.815  5670  6052 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-24 12:19:29.815  5670  6052 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:19:29.815  5670  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 12:19:29.820  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 12:19:29.820  5670  5718 I jxcore-log: 
11-24 12:19:29.821  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 12:19:29.821  5670  5718 I jxcore-log: 
11-24 12:19:29.821  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 12:19:29.821  5670  5718 I jxcore-log: 
11-24 12:19:29.821  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 12:19:29.821  5670  5718 I jxcore-log: 
,11-24 12:19:29.822  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'Total duration:  91490'
11-24 12:19:29.822  5670  5718 I jxcore-log: 
,11-24 12:19:29.824  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 12:19:29.824  5670  5718 I jxcore-log: 
,11-24 12:19:29.828  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.828  5670  5718 I jxcore-log: 
,11-24 12:19:29.828  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.828  5670  5718 I jxcore-log: 
11-24 12:19:29.829  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 12:19:29.829  5670  5718 I jxcore-log: 
11-24 12:19:29.829  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 12:19:29.829  5670  5718 I jxcore-log: 
,11-24 12:19:29.829  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.829  5670  5718 I jxcore-log: 
11-24 12:19:29.830  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:19:29.830  5670  5718 I jxcore-log: 
11-24 12:19:29.830  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.830  5670  5718 I jxcore-log: 
,11-24 12:19:29.830  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.830  5670  5718 I jxcore-log: 
11-24 12:19:29.831  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.831  5670  5718 I jxcore-log: 
11-24 12:19:29.831  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 12:19:29.831  5670  5718 I jxcore-log: 
11-24 12:19:29.831  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 12:19:29.831  5670  5718 I jxcore-log: 
,11-24 12:19:29.831  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.831  5670  5718 I jxcore-log: 
11-24 12:19:29.832  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:19:29.832  5670  5718 I jxcore-log: 
11-24 12:19:29.832  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.832  5670  5718 I jxcore-log: 
11-24 12:19:29.832  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:19:29.832  5670  5718 I jxcore-log: 
11-24 12:19:29.832  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.832  5670  5718 I jxcore-log: 
11-24 12:19:29.832  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.832  5670  5718 I jxcore-log: 
11-24 12:19:29.833  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.833  5670  5718 I jxcore-log: 
,11-24 12:19:29.833  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 12:19:29.833  5670  5718 I jxcore-log: 
11-24 12:19:29.833  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 12:19:29.833  5670  5718 I jxcore-log: 
11-24 12:19:29.834  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 12:19:29.834  5670  5718 I jxcore-log: 
11-24 12:19:29.834  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.834  5670  5718 I jxcore-log: 
11-24 12:19:29.834  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 12:19:29.834  5670  5718 I jxcore-log: 
,11-24 12:19:29.835  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 12:19:29.835  5670  5718 I jxcore-log: 
11-24 12:19:29.836  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 12:19:29.836  5670  5718 I jxcore-log: 
11-24 12:19:29.836  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 12:19:29.836  5670  5718 I jxcore-log: 
11-24 12:19:29.837  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:19:29.837  5670  5718 I jxcore-log: 
11-24 12:19:29.837  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:19:29.837  5670  5718 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 12:19:29.837  5670  5718 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:19:29.837  5670  5718 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 12:19:29.837  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:19:29.837  5670  5718 I jxcore-log: 
,11-24 12:19:29.838  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.838  5670  5718 I jxcore-log: 
11-24 12:19:29.838  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:19:29.838  5670  5718 I jxcore-log: 
11-24 12:19:29.838  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.838  5670  5718 I jxcore-log: 
11-24 12:19:29.838  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:19:29.838  5670  5718 I jxcore-log: 
11-24 12:19:29.838  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:19:29.838  5670  5718 I jxcore-log: 
,11-24 12:19:29.844  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 12:19:29.844  5670  5718 I jxcore-log: 
11-24 12:19:29.844  5670  5718 I jxcore-log: 2016-11-24 11:19:29 - WARN testUtils: 'myNameCallback not set!'
11-24 12:19:29.844  5670  5718 I jxcore-log: 
,11-24 12:19:29.844  5670  5670 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 12:19:29.845  5670  5670 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 12:19:31.893  5670  5718 I jxcore-log: 2016-11-24 11:19:31 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 12:19:31.893  5670  5718 I jxcore-log: 
,11-24 12:19:31.895  5670  5718 I jxcore-log: 2016-11-24 11:19:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 12:19:31.895  5670  5718 I jxcore-log: 
,11-24 12:19:32.232  5670  5718 I jxcore-log: 2016-11-24 11:19:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 12:19:32.232  5670  5718 I jxcore-log: 
,11-24 12:19:32.242  5670  5718 I jxcore-log: 2016-11-24 11:19:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 12:19:32.242  5670  5718 I jxcore-log: 
,11-24 12:19:33.358  5670  5718 I jxcore-log: 2016-11-24 11:19:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 12:19:33.358  5670  5718 I jxcore-log: 
,11-24 12:19:33.551  5670  5718 I jxcore-log: 2016-11-24 11:19:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 12:19:33.551  5670  5718 I jxcore-log: 
,11-24 12:19:33.556  5670  5718 I jxcore-log: 2016-11-24 11:19:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 12:19:33.556  5670  5718 I jxcore-log: 
,11-24 12:19:33.561  5670  5718 I jxcore-log: 2016-11-24 11:19:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 12:19:33.561  5670  5718 I jxcore-log: 
,11-24 12:19:34.045  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 12:19:34.045  5670  5718 I jxcore-log: 
,11-24 12:19:34.090  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 12:19:34.090  5670  5718 I jxcore-log: 
,11-24 12:19:34.103  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 12:19:34.103  5670  5718 I jxcore-log: 
,11-24 12:19:34.107  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 12:19:34.107  5670  5718 I jxcore-log: 
,11-24 12:19:34.377  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 12:19:34.377  5670  5718 I jxcore-log: 
,11-24 12:19:34.505  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 12:19:34.505  5670  5718 I jxcore-log: 
,11-24 12:19:34.707   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:34.883  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 12:19:34.883  5670  5718 I jxcore-log: 
,11-24 12:19:34.892  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 12:19:34.892  5670  5718 I jxcore-log: 
,11-24 12:19:34.896  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 12:19:34.896  5670  5718 I jxcore-log: 
,11-24 12:19:34.901  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 12:19:34.901  5670  5718 I jxcore-log: 
,11-24 12:19:34.907  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 12:19:34.907  5670  5718 I jxcore-log: 
,11-24 12:19:34.935  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 12:19:34.935  5670  5718 I jxcore-log: 
,11-24 12:19:34.969  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 12:19:34.969  5670  5718 I jxcore-log: 
,11-24 12:19:34.976  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 12:19:34.976  5670  5718 I jxcore-log: 
,11-24 12:19:34.982  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 12:19:34.982  5670  5718 I jxcore-log: 
,11-24 12:19:34.997  5670  5718 I jxcore-log: 2016-11-24 11:19:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 12:19:34.997  5670  5718 I jxcore-log: 
,11-24 12:19:35.013  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 12:19:35.013  5670  5718 I jxcore-log: 
,11-24 12:19:35.019  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 12:19:35.019  5670  5718 I jxcore-log: 
,11-24 12:19:35.024  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 12:19:35.024  5670  5718 I jxcore-log: 
,11-24 12:19:35.037  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 12:19:35.037  5670  5718 I jxcore-log: 
,11-24 12:19:35.054  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 12:19:35.054  5670  5718 I jxcore-log: 
,11-24 12:19:35.068  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 12:19:35.068  5670  5718 I jxcore-log: 
,11-24 12:19:35.079  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 12:19:35.079  5670  5718 I jxcore-log: 
,11-24 12:19:35.092  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 12:19:35.092  5670  5718 I jxcore-log: 
,11-24 12:19:35.102  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 12:19:35.102  5670  5718 I jxcore-log: 
,11-24 12:19:35.115  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 12:19:35.115  5670  5718 I jxcore-log: 
,11-24 12:19:35.125  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 12:19:35.125  5670  5718 I jxcore-log: 
,11-24 12:19:35.131  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 12:19:35.131  5670  5718 I jxcore-log: 
,11-24 12:19:35.153  5670  5718 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 12:19:35.154  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 12:19:35.154  5670  5718 I jxcore-log: 
,11-24 12:19:35.187  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 12:19:35.187  5670  5718 I jxcore-log: 
,11-24 12:19:35.482  5670  5718 I jxcore-log: 2016-11-24 11:19:35 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 12:19:35.482  5670  5718 I jxcore-log: 
,11-24 12:19:35.708   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:36.709   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:37.711   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:38.712   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:39.712   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:19:43.740   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:19:46.770   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:19:53.739   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:20:04.713   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:20:04.713   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:20:14.714   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:15.716   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:16.717   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:17.718   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:18.720   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:19.721   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:20:24.722   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:25.723   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:26.725   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:27.726   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:28.728   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:29.729   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:20:33.743   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:20:35.179   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:20:38.210   932  3018 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:20:39.730   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:40.732   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:41.733   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:42.735   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:43.736   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:44.737   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 12:20:50.708   932  3206 I ActivityManager: Start proc 6061:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-24 12:20:50.742  6061  6061 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-24 12:20:50.851  6061  6073 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-24 12:20:50.921  6061  6073 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-24 12:20:50.969  6061  6073 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-24 12:20:50.989  6086  6086 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1066397730.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1066397730.dex
,11-24 12:20:51.007  6061  6061 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-24 12:20:51.023  6086  6086 I dex2oat : dex2oat took 34.790ms (threads: 2) arena alloc=187KB java alloc=37KB native alloc=1258KB free=1045KB
,11-24 12:20:51.166  6061  6061 W InstanceID/Rpc: Found 10012
,11-24 12:20:51.216   932   942 I ActivityManager: Killing 5544:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 12:20:53.744   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:20:59.738   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:00.739   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:01.740   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:02.741   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:03.742   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:04.743   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 12:21:24.744   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:25.746   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:26.747   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:27.749   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:28.751   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:21:29.751   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:21:33.746   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:21:53.748   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:21:54.752   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:21:54.752   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:22:09.754   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:10.755   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:11.757   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:12.758   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:13.750   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:22:13.759   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:14.760   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:22:19.762   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:20.763   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:21.765   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:22.766   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:23.768   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:24.769   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:22:34.770   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:35.772   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:36.773   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:37.775   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:38.776   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:39.777   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 12:22:53.754   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:22:54.778   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:55.779   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:56.780   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:57.782   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:58.783   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:22:59.783   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 12:23:13.755   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:23:19.785   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:23:20.786   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:23:21.788   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:23:22.789   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:23:23.790   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:23:24.791   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:23:33.757   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:23:49.792   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:23:49.792   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:23:53.759   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:24:09.793   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:10.795   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:11.796   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:12.797   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:13.762   932  3016 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:24:13.798   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:14.799   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:24:19.801   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:20.802   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:21.804   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:22.805   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:23.807   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:24:24.808   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:24:25.648  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 12:24:25.648  5670  5718 I jxcore-log: 
,11-24 12:24:25.952  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 12:24:25.952  5670  5718 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 12:24:25.952  5670  5718 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 12:24:25.952  5670  5718 I jxcore-log: emit@events.js:82:1
11-24 12:24:25.952  5670  5718 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 12:24:25.952  5670  5718 I jxcore-log: emit@events.js:82:1''
11-24 12:24:25.952  5670  5718 I jxcore-log: 
,11-24 12:24:25.953  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedClient: 'test client failed'
11-24 12:24:25.953  5670  5718 I jxcore-log: 
,11-24 12:24:25.965  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 12:24:25.965  5670  5718 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 12:24:25.965  5670  5718 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 12:24:25.965  5670  5718 I jxcore-log: emit@events.js:82:1
11-24 12:24:25.965  5670  5718 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 12:24:25.965  5670  5718 I jxcore-log: emit@events.js:82:1''
11-24 12:24:25.965  5670  5718 I jxcore-log: 
,11-24 12:24:25.965  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedClient: 'test client failed'
11-24 12:24:25.965  5670  5718 I jxcore-log: 
,11-24 12:24:25.970  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 12:24:25.970  5670  5718 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 12:24:25.970  5670  5718 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 12:24:25.970  5670  5718 I jxcore-log: emit@events.js:82:1
11-24 12:24:25.970  5670  5718 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 12:24:25.970  5670  5718 I jxcore-log: emit@events.js:82:1''
11-24 12:24:25.970  5670  5718 I jxcore-log: 
,11-24 12:24:25.971  5670  5718 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 12:24:25.971  5670  5718 I jxcore-log: 
,11-24 12:24:26.477  6148  6148 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 12:24:26.481  6148  6148 D AndroidRuntime: CheckJNI is OFF
,11-24 12:24:26.509  6148  6148 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 12:24:26.543  6148  6148 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 12:24:26.559  6148  6148 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 12:24:26.567   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 12:24:26.568   932   945 I ActivityManager: Killing 5670:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 12:24:26.669   932  3268 D GraphicsStats: Buffer count: 2
,11-24 12:24:26.669   932   942 I WindowState: WIN DEATH: Window{23ab15c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 12:24:26.671   932  3017 D WifiService: Client connection lost with reason: 4
,11-24 12:24:26.689   932   945 W ActivityManager: Force removing ActivityRecord{8376d64 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 12:24:26.716   932   955 I art     : Starting a blocking GC Explicit
,11-24 12:24:26.724   932  5002 W ActivityManager: Spurious death for ProcessRecord{489ace6 0:com.test.thalitest/u0a77}, curProc for 5670: null
,11-24 12:24:26.758   943   943 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[27054]" dev="sockfs" ino=27054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 12:24:26.758   943   943 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[27054]" dev="sockfs" ino=27054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 12:24:26.762   932   943 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5670 uid 10077
11-24 12:24:26.763  3726  3726 I Keyboard.Facilitator: onFinishInput()
,11-24 12:24:26.830   932   955 I art     : Explicit concurrent mark sweep GC freed 129408(9MB) AllocSpace objects, 81(2MB) LOS objects, 33% free, 29MB/44MB, paused 2.036ms total 112.847ms
,11-24 12:24:26.840  4002  6165 I MicroRecognitionRnrImpl: Starting detection.
,11-24 12:24:26.842  4002  6166 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@e15aebc
11-24 12:24:26.846   516  6168 I AudioFlinger: AudioFlinger's thread 0xf1d80000 ready to run
,11-24 12:24:26.849   516  3064 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 12:24:26.851  4002  6166 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@e15aebc
,11-24 12:24:26.853   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 12:24:26.856  6148  6148 I art     : System.exit called, status: 0
11-24 12:24:26.856  6148  6148 I AndroidRuntime: VM exiting with result code 0.
,11-24 12:24:26.862   516  6168 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-24 12:24:26.862   516  6168 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 12:24:26.862   516  6168 I ACDB-LOADER: ACDB AFE returned = -19
11-24 12:24:26.862   516  6168 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-24 12:24:26.862   516  6168 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-24 12:24:26.862   516  6168 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-24 12:24:26.868   516  6168 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 12:24:26.871   932   955 I ActivityManager: Start proc 6170:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-24 12:24:26.872   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 12:24:26.880  5953  5953 D BluetoothMapAppObserver: onReceive
,11-24 12:24:26.880  5953  5953 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-24 12:24:26.882  3726  3726 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 12:24:26.887  4172  4229 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 12:24:26.888   932  3008 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 12:24:26.908  3726  6180 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 12:24:26.913  3466  6184 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 12:24:26.925  3726  6180 I Decoder : createOrResetDecoder
,11-24 12:24:26.942  3825  3825 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 12:24:26.956  4002  4002 I HotwordWorkerImpl: onReady
,11-24 12:24:26.958   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 12:24:26.968  3619  3619 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-24 12:24:26.968  3619  3619 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 12:24:26.971    21    21 W kworker/3:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:24:26.974    21    21 W kworker/3:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:24:26.993  3619  3619 I ConfigService: onCreate
,11-24 12:24:26.994  4020  6192 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
,11-24 12:24:26.994  4020  6192 D AccountUtils: Clearing selected account for com.test.thalitest
,11-24 12:24:27.001    21    21 W kworker/3:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:24:27.015  4020  6192 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-24 12:24:27.019  3726  6180 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 12:24:27.021  3466  3488 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjC39A4F9DB) - 
,11-24 12:24:27.022  4020  4020 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-24 12:24:27.022  4020  4020 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-24 12:24:27.026  4020  4020 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-24 12:24:27.026  4020  4020 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-24 12:24:27.031  4020  6198 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:24:27.031  4020  6198 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 12:24:27.031  4020  ,6198 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:24:27.031  4020  6198 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:24:27.033  4020  6198 W SQLiteOpenHelper: Opened metrics.db in read-only mode
,11-24 12:24:27.033  4020  6198 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,11-24 12:24:27.033  4020  6198 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-24 12:24:27.034  4020  6198 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:24:27.034  4020  6192 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:24:27.034  4020  6198 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android,.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:24:27.035  4020  6192 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
11-24 12:24:27.035  4020  6198 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-24 12:24:27.035  4020  6198 E AndroidRuntime: Process: com.google.android.gms, PID: 4020
11-24 12:24:27.035  4020  6198 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:24:27.035  4020  6198 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:24:27.035  4020  6192 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-24 12:24:27.039  4002  6202 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-24 12:24:27.043   932  6203 E DropBoxManagerService: Can't write: system_app_crash
11-24 12:24:27.043   932  6203 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS, (Read-only file system)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:24:27.043   932  6203 E DropBoxManagerService: 	... 5 more
11-24 12:24:27.055  3466  6184 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-24 12:24:27.058  3466  6184 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-24 12:24:27.058  3466  6184 E AndroidRuntime: Process: android.process.acore, PID: 3466
11-24 12:24:27.058  3466  6184 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:24:27.058  3466  6184 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:24:27.065  3466  3488 I Process : Sending signal. PID: 3466 SIG: 9
11-24 12:24:27.066  4002  6202 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-24 12:24:27.074  4097  4097 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32393]" dev="sockfs" ino=32393 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 12:24:27.074  4097  4097 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32393]" dev="sockfs" ino=32393 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:24:27.084   383   485 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown
11-24 12:24:27.084   383   485 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
11-24 12:24:27.084   932  6204 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-24 12:24:27.081  4097  4097 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[36050]" dev="sockfs" ino=36050 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 12:24:27.081  4097  4097 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[36050]" dev="sockfs" ino=36050 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 12:24:27.103   932  3592 I ActivityManager: Start proc 6206:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-24 12:24:27.106   932  6211 E DropBoxManagerService: Can't write: system_app_crash
11-24 12:24:27.106   932  6211 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:24:27.106   932  6211 E DropBoxManagerService: 	... 5 more
,11-24 12:24:27.118   932  3640 I ActivityManager: Start proc 6212:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-24 12:24:27.128  4020  6200 W BaseAppContext: Using Auth Proxy for data requests.
,11-24 12:24:27.135  4020  6192 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
11-24 12:24:27.135   932  5812 I ActivityManager: Process android.process.acore (pid 3466) has died
,11-24 12:24:27.136   932  5812 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-24 12:24:27.137  4020  6200 W BaseAppContext: Using Auth Proxy for data requests.
,11-24 12:24:27.143  4020  6219 I GMPM-SVC: App measurement is starting up
,11-24 12:24:27.147  4020  6219 E GMPM-SVC: AppMeasurementService not registered/enabled
11-24 12:24:27.147  4020  6219 E GMPM-SVC: Uploading is not possible. App measurement disabled
11-24 12:24:27.147  4020  4020 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-24 12:24:27.150  4020  6219 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-24 12:24:27.150  4020  6219 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,11-24 12:24:27.151  4020  6219 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 12:24:27.151  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-24 12:24:27.151  4020  6219 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-24 12:24:27.152  4020  6219 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-24 12:24:27.152  4020  6219 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 12:24:27.153  4020  6219 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-24 12:24:27.153  4020  6219 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-24 12:24:27.154  4020  6219 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-24 12:24:27.155  4020  6219 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-24 12:24:27.155   932   945 W Broadcast,Queue: Skipping deliver [background] BroadcastRecord{fea7266 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{989efa8 4020 com.google.android.gms/10012/u0 remote:f4a6bcb}: process crashing
,11-24 12:24:27.163   932  3206 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/4020 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-24 12:24:27.208  4020  6197 W DriveInitializer: Awaiting to be initialized
,11-24 12:24:27.209  4020  6224 W DriveInitializer: Background init thread started
,11-24 12:24:27.389   383   484 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
