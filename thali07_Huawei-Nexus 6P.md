#### Test 89975734f2db9ce_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-25 13:02:37.483  3977  4200 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-25 13:02:37.571  3977  4200 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-25 13:02:37.919  5584  5584 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 13:02:37.924  5584  5584 D AndroidRuntime: CheckJNI is OFF
11-25 13:02:37.952  5584  5584 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 13:02:37.984  5584  5584 I Radio-JNI: register_android_hardware_Radio DONE
11-25 13:02:37.999  5584  5584 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-25 13:02:38.009   930  3804 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 13:02:38.041  3960  5582 W SearchService: Abort, client detached.
11-25 13:02:38.049  3960  3960 I HotwordDetector: Closing mic
11-25 13:02:38.050  3960  4193 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@10e6866
11-25 13:02:38.051  3960  4197 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-25 13:02:38.062  5584  5584 D AndroidRuntime: Shutting down VM
11-25 13:02:38.106   930  3612 I ActivityManager: Start proc 5593:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 13:02:38.130   514  4199 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-25 13:02:38.131   514  4199 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-25 13:02:38.139   514  4199 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-25 13:02:38.139   514  4199 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 13:02:38.140   514  3000 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-25 13:02:38.142  3960  4196 I MicroRecognitionRnrImpl: Detection finished
11-25 13:02:38.143  3960  4194 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-25 13:02:38.206  5593  5593 I CordovaLog: Changing log level to DEBUG(3)
11-25 13:02:38.206  5593  5593 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 13:02:38.206  5593  5593 D CordovaActivity: CordovaActivity.onCreate()
11-25 13:02:38.212  5593  5593 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-25 13:02:38.234  5593  5593 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-25 13:02:38.311  5593  5593 I LibraryLoader: Time to load native libraries: 74 ms (timestamps 9900-9974)
11-25 13:02:38.311  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 13:02:38.353  5593  5593 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {68f6b78}
11-25 13:02:38.353  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 13:02:38.354  5593  5593 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 13:02:38.356  5593  5593 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-25 13:02:38.357  5593  5593 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 13:02:38.408  5593  5593 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 13:02:38.422  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 13:02:38.422  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 13:02:38.422  5593  5593 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 13:02:38.422  5593  5593 I Adreno  : Build Date                       : 12/06/15
11-25 13:02:38.422  5593  5593 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 13:02:38.422  5593  5593 I Adreno  : Local Branch                     : mybranch17112971
11-25 13:02:38.422  5593  5593 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 13:02:38.422  5593  5593 I Adreno  : Remote Branch                    : NONE
11-25 13:02:38.422  5593  5593 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 13:02:38.469   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f92ef6e:true
,11-25 13:02:38.497   405   405 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[25274]" dev="sockfs" ino=25274 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:02:38.497   405   405 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25274]" dev="sockfs" ino=25274 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:02:38.509  5593  5593 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 13:02:38.519  5593  5593 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 13:02:38.522  5593  5593 D PluginManager: init()
,11-25 13:02:38.524  5593  5593 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 13:02:38.539  5593  5593 D CordovaActivity: Started the activity.
,11-25 13:02:38.539  5593  5593 D CordovaActivity: Resumed the activity.
,11-25 13:02:38.541   771   771 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32463]" dev="sockfs" ino=32463 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:02:38.544  5593  5631 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-25 13:02:38.541   771   771 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32463]" dev="sockfs" ino=32463 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:02:38.544  3808  3808 W Binder_B: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[25286]" dev="sockfs" ino=25286 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:02:38.544  3808  3808 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[25286]" dev="sockfs" ino=25286 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:02:38.547  5593  5618 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 13:02:38.571  5593  5631 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 13:02:38.645   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +568ms
11-25 13:02:38.641  3162  3162 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32471]" dev="sockfs" ino=32471 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:02:38.641  3162  3162 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32471]" dev="sockfs" ino=32471 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:02:38.648  3661  3661 I Keyboard.Facilitator: onFinishInput()
11-25 13:02:38.644   940   940 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32470]" dev="sockfs" ino=32470 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:02:38.644   940   940 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32470]" dev="sockfs" ino=32470 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:02:38.664  5593  5593 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 13:02:38.695  5593  5593 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5593
,11-25 13:02:38.802  5593  5593 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 13:02:39.024  5593  5633 D jxcore_app_log: JniHelper::setJavaVM(0xf55bc000), pthread_self() = -564659920
,11-25 13:02:39.029  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 13:02:39.029  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 13:02:39.029  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 13:02:39.029  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 13:02:39.029  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 13:02:39.029  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eac666f added. We now have 1 listener(s)
,11-25 13:02:39.034  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-25 13:02:39.035  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:02:39.035  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:02:39.035  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-25 13:02:39.037  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@655185a added. We now have 1 listener(s)
11-25 13:02:39.038  5593  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:02:39.044   930  2979 D WifiService: New client listening to asynchronous messages
,11-25 13:02:39.044  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:02:39.044  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 13:02:39.045  5593  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 56
11-25 13:02:39.045  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-25 13:02:39.045  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 13:02:39.045  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 13:02:39.045  5593  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 56
,11-25 13:02:39.049  5593  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 13:02:39.180  5593  5593 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 13:02:39.183  5593  5593 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-25 13:02:39.183  5593  5593 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 13:02:39.524  5593  5601 I art     : Background sticky concurrent mark sweep GC freed 74245(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 2.497ms total 263.791ms
,11-25 13:02:40.604   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:02:40.913  5593  5601 I art     : Background partial concurrent mark sweep GC freed 56764(6MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 1.453ms total 387.819ms
,11-25 13:02:41.153  5593  5641 W jxcore-log: Initializing JXcore engine
,11-25 13:02:41.153  5593  5641 W jxcore-log: JXcore engine is ready
,11-25 13:02:41.174  5641  5641 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12537 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-25 13:02:41.174  5641  5641 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15439]" dev="sockfs" ino=15439 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-25 13:02:41.174  5641  5641 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 13:02:41.174  5641  5641 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31408]" dev="sockfs" ino=31408 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-25 13:02:41.186  5593  5641 W jxcore-log: Starting JXcore engine
,11-25 13:02:41.236  5593  5641 W jxcore-log: Platform android
11-25 13:02:41.236  5593  5641 W jxcore-log: 
11-25 13:02:41.236  5593  5641 W jxcore-log: Process ARCH arm
11-25 13:02:41.236  5593  5641 W jxcore-log: 
,11-25 13:02:41.414  5593  5641 I jxcore-log: JXcore Cordova bridge is ready!
11-25 13:02:41.414  5593  5641 I jxcore-log: 
,11-25 13:02:41.414  5593  5641 W jxcore-log: JXcore engine is started
,11-25 13:02:41.421  5593  5633 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 13:02:41.424  5593  5593 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-25 13:02:41.424  5593  5593 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 13:02:41.574  3579  3579 I ConfigService: onDestroy
,11-25 13:02:41.842   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:02:42.843   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:02:43.058   930  3808 I ActivityManager: Killing 5231:org.codeaurora.ims/1001 (adj 15): empty #17
,11-25 13:02:43.108   930  3808 I ActivityManager: Killing 5142:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-25 13:02:43.844   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:02:44.845   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:02:45.846   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:02:46.846   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:02:48.235   930  2979 D WifiService: New client listening to asynchronous messages
,11-25 13:02:48.238  3960  5642 W CronetSyncConnectionRcs: Upload content type not set.
,11-25 13:02:51.149  5593  5641 I jxcore-log: 2016-11-25 12:02:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 13:02:51.149  5593  5641 I jxcore-log: 
,11-25 13:02:51.151  5593  5641 I jxcore-log: 2016-11-25 12:02:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 13:02:51.151  5593  5641 I jxcore-log: 
,11-25 13:02:51.173  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:02:51.174  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:02:51.175  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:02:51.176  5593  5641 I jxcore-log: 2016-11-25 12:02:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 13:02:51.176  5593  5641 I jxcore-log: 
11-25 13:02:51.177  5593  5641 I jxcore-log: 2016-11-25 12:02:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 13:02:51.177  5593  5641 I jxcore-log: 
,11-25 13:02:51.243  4856  4905 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-25 13:02:51.245  4856  4856 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-25 13:02:51.423  5593  5641 I jxcore-log: 2016-11-25 12:02:51 - DEBUG UnitTest_app: 'Running unit tests'
11-25 13:02:51.423  5593  5641 I jxcore-log: 
,11-25 13:02:51.423  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:02:51.423  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d520056 added. We now have 2 listener(s)
11-25 13:02:51.424  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:02:51.424  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:02:51.424  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:02:51.424  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:02:51.425  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8888d7 added. We now have 2 listener(s)
,11-25 13:02:51.425  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:02:51.425  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:02:51.426  5593  5641 D executeNativeTests: Running unit tests
,11-25 13:02:51.466  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 13:02:51.466  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 added. We now have 3 listener(s)
11-25 13:02:51.467  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:02:51.467  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:02:51.467  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:02:51.467  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:02:51.467  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d added. We now have 3 listener(s)
11-25 13:02:51.467  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:02:51.467  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:02:51.469  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:02:51.469  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 13:02:51.469  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 13:02:51.469  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:02:51.470  5593  5641 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-25 13:02:51.470  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 13:02:51.470  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:02:51.470  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-25 13:02:51.470  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-25 13:02:51.470  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:02:51.470  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:02:51.470  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:02:51.470  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:02:51.471  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:02:51.471  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:02:51.471  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:02:51.471  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 removed from the list
11-25 13:02:51.471  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:02:51.472  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d removed from the list
11-25 13:02:51.472  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:02:51.472  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.472  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.472  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.472  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.472  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.472  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:02:51.473  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:02:51.473  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:02:51.473  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:02:51.473  5593  5641 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-25 13:02:51.474  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:02:51.474  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:02:51.474  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:02:51.474  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:02:51.474  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:02:51.474  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:02:51.474  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:02:51.474  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:02:51.474  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:02:51.474  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:02:51.474  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.475  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.475  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.475  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.475  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:02:51.475  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:02:51.475  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:02:51.475  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 13:02:51.477  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 13:02:51.478  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:02:51.478  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:02:51.478  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:02:51.478  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:02:51.478  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:02:51.478  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:02:51.478  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:02:51.478  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:02:51.478  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:02:51.478  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.479  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.479  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.479  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.479  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.479  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:02:51.479  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:02:51.479  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:02:51.479  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:02:51.480  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 13:02:51.481  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:02:51.481  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:02:51.488  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:02:51.489  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:02:51.489  5593  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:02:51.489  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:02:51.489  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:02:51.489  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:02:51.489  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:02:51.489  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:02:51.491  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:02:51.491  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:02:51.491  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:02:51.494  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.494  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:02:51.495  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:02:51.498  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:02:51.499  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:02:51.499  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:02:51.501  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:02:51.502  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-25 13:02:51.504  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 13:02:51.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.504  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:02:51.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:02:51.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:02:51.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:02:51.504  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.505  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:02:51.507  4661  4882 D BtGatt.GattService: registerClient() - UUID=7ef986c4-e62f-4ce6-b247-85fa043cd78a
11-25 13:02:51.507  4661  4724 D BtGatt.GattService: onClientRegistered() - UUID=7ef986c4-e62f-4ce6-b247-85fa043cd78a, clientIf=5
11-25 13:02:51.508  5593  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:02:51.510  4661  4674 D BtGatt.GattService: start scan with filters
11-25 13:02:51.515  4661  4735 D BtGatt.ScanManager: handling starting scan
11-25 13:02:51.515  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:02:51.515  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.515  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:02:51.515  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.516  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:02:51.516  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:02:51.516  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.516  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:02:51.516  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:02:51.516  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.516  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:02:51.516  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.516  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.517  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.517  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.517  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:51.517  4661  4735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:02:51.517  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.517  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:02:51.517  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.517  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.521  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.521  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:02:51.522  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.522  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:02:51.522  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:02:51.524  4661  4724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:02:51.524  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:02:51.525  4661  4735 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 13:02:51.531  4661  4724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:02:51.531  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:02:51.532  4661  4735 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:02:51.532  4661  4735 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:02:51.543  4661  4724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:02:51.543  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:02:51.549  4661  4724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:02:51.549  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:02:52.023  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 13:02:52.024  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:02:52.024  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:02:56.522  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:02:56.522  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:02:56.522  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:02:56.522  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 13:02:56.522  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:02:56.522  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:02:56.522  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 13:02:56.523  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:02:56.523  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.523  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:02:56.523  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:02:56.524  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:02:56.524  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.524  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.525  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 13:02:56.525  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.526  5593  5641 D BluetoothAdapter: STATE_ON
,11-25 13:02:56.526  4661  4676 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:02:56.527  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 13:02:56.527  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:02:56.528  4661  4735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:02:56.528  4661  4674 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:02:56.529  4661  4872 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:02:56.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:02:56.529  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.530  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:02:56.530  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:02:56.530  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.530  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.530  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.530  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:02:56.531  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.531  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.531  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.531  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:02:56.531  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:02:56.532  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:02:56.532  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.533  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:02:56.534  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:02:56.534  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:02:56.534  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:02:56.534  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:02:56.534  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:02:56.534  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:02:56.534  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:02:56.535  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:02:56.535  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:02:56.535  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:02:56.535  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:02:56.535  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:02:56.535  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:02:56.535  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 13:02:56.536  4661  4661 D BtGatt.ScanManager: awakened up at time 98199
11-25 13:02:56.536  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:02:56.536  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:02:56.536  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:02:56.537  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:02:56.537  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 13:02:56.537  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:02:56.537  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:02:56.537  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:02:56.538  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:02:56.538  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:02:56.542  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:02:56.543  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 13:02:56.543  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:02:56.558  4661  4724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-25 13:02:56.558  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:02:56.559  4661  4724 D BtGatt.GattService: current time is 98222514412
11-25 13:02:56.559  4661  4724 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -87, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-25 13:02:56.561  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 13:02:56.562  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 13:02:56.562  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 13:02:56.562  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 13:02:56.562  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 13:02:56.563  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 13:02:56.568  4661  4724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:02:56.568  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:02:56.568  4661  4735 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:02:56.574  4661  4724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:02:56.574  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:02:56.574  4661  4735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:02:56.579  4661  4724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:02:56.579  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:02:57.039  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:03:00.204   930   930 I ActivityManager: Killing 5271:com.android.settings/1000 (adj 15): empty #17
,11-25 13:03:01.537  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 13:03:01.546  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:03:01.547  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:03:01.560  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:03:01.562  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:03:01.563  5593  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-25 13:03:01.563  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:03:01.563  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:03:01.563  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:03:01.563  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:03:01.563  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:03:01.567  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:01.569  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:03:01.569  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 13:03:01.569  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:03:01.571  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:01.573  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:01.574  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 13:03:01.575  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:03:01.575  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:03:01.575  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:03:01.580  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:01.580  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:03:01.581  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:03:01.581  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:03:01.581  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:03:01.581  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.581  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:03:01.583  4661  4882 D BtGatt.GattService: registerClient() - UUID=507e3587-9aed-4406-b533-94809be344f6
,11-25 13:03:01.583  4661  4724 D BtGatt.GattService: onClientRegistered() - UUID=507e3587-9aed-4406-b533-94809be344f6, clientIf=5
,11-25 13:03:01.584  5593  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:03:01.584  4661  4674 D BtGatt.GattService: start scan with filters
11-25 13:03:01.587  4661  4735 D BtGatt.ScanManager: handling starting scan
11-25 13:03:01.587  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:03:01.587  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.587  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:03:01.587  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.587  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:03:01.587  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:03:01.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:03:01.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:03:01.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.588  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 13:03:01.589  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:03:01.589  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:01.591  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.592  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:03:01.592  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.592  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.592  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 13:03:01.592  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.594  4661  4724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:03:01.594  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:03:01.594  4661  4735 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 13:03:01.594  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:01.594  5593  5641 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 13:03:01.595  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:01.595  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:03:01.595  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:03:01.595  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:03:01.595  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:01.595  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:03:01.597  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.597  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.597  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:03:01.597  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:03:01.597  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:03:01.597  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.597  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:03:01.597  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:03:01.598  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.598  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.598  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.598  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 13:03:01.598  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:01.599  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:03:01.599  4661  4882 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:03:01.599  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:03:01.600  4661  4724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:03:01.600  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.600  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:03:01.601  4661  4735 D BtGatt.ScanManager: Starting BLE batch scan
,11-25 13:03:01.601  4661  4735 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 13:03:01.601  4661  4674 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:03:01.602  4661  4872 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:03:01.603  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.604  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.604  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.604  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:03:01.604  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:03:01.605  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:03:01.605  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.606  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.606  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:03:01.606  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.606  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.606  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:01.606  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:03:01.606  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:03:01.606  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:01.606  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:03:01.606  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:0,3:01.606  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:03:01.606  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.606  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:03:01.607  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:03:01.607  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.607  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.607  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.607  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:03:01.607  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.607  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.608  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:01.608  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:01.608  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:01.608  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:01.608  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:03:01.610  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.610  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.610  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.610  4661  4724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:03:01.611  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:03:01.611  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.611  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:01.612  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.612  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.612  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.612  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:03:01.612  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:01.612  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:01.612  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:01.612  5593  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 13:03:01.614  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:03:01.614  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:03:01.616  4661  4724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:03:01.616  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:03:01.618  4661  4735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:03:01.621  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:03:01.622  4661  4724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:03:01.622  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.622  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:03:01.622  4661  4724 E BtGatt.ContextMap: Context not found for ID 5
11-25 13:03:01.622  5593  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:03:01.623  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:03:01.623  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:03:01.623  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-25 13:03:01.623  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:03:01.623  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:03:01.625  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:01.627  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:01.629  4661  4724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 13:03:01.629  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.629  4661  4735 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:03:01.630  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 13:03:01.630  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:03:01.630  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:03:01.634  4661  4724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:03:01.634  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.634  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.634  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:03:01.634  4661  4735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:03:01.635  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:03:01.635  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:03:01.635  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:03:01.638  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.638  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:03:01.638  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:03:01.638  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:03:01.638  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:03:01.638  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.638  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:03:01.639  4661  4724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:03:01.639  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.640  4661  4674 D BtGatt.GattService: registerClient() - UUID=bec37999-9924-4957-89c0-a6ecd1397e9b
,11-25 13:03:01.641  4661  4724 D BtGatt.GattService: onClientRegistered() - UUID=bec37999-9924-4957-89c0-a6ecd1397e9b, clientIf=5
11-25 13:03:01.641  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:03:01.642  4661  4883 D BtGatt.GattService: start scan with filters
,11-25 13:03:01.643  4661  4735 D BtGatt.ScanManager: handling starting scan
11-25 13:03:01.644  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:03:01.644  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.644  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-25 13:03:01.645  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.645  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:03:01.645  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:03:01.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:03:01.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:03:01.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.645  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.646  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:03:01.646  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.648  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.648  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:03:01.648  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.648  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:01.648  5593  5641 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:03:01.648  4661  4724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:03:01.648  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.649  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.649  4661  4735 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 13:03:01.651  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.651  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.651  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:03:01.651  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 13:03:01.653  4661  4724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 13:03:01.653  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:01.653  4661  4735 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:03:01.654  4661  4735 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 13:03:01.661  4661  4724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 13:03:01.662  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:03:01.666  4661  4724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:03:01.666  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:03:02.152  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-25 13:03:02.152  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:03:02.153  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:03:06.649  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:06.649  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:03:06.649  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:03:06.650  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:03:06.650  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:03:06.650  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:03:06.650  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 13:03:06.650  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-25 13:03:06.651  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:06.651  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:03:06.651  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-25 13:03:06.651  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.652  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.652  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.652  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:03:06.653  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:06.657  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:03:06.658  4661  4674 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:03:06.659  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 13:03:06.660  4661  4735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:03:06.661  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:03:06.663  4661  4872 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:03:06.666  4661  4676 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:03:06.667  4661  4661 D BtGatt.ScanManager: awakened up at time 108330
11-25 13:03:06.668  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:03:06.668  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.668  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:03:06.668  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.669  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:03:06.669  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-25 13:03:06.677  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 13:03:06.677  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.678  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.678  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:03:06.678  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.678  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:06.679  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:03:06.679  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:03:06.679  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:03:06.679  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.679  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:03:06.679  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:03:06.679  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.679  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.679  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.680  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:03:06.681  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.681  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.683  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.683  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:03:06.683  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:03:06.688  4661  4724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-25 13:03:06.688  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:06.689  4661  4724 D BtGatt.GattService: current time is 108352420661
11-25 13:03:06.689  4661  4724 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -81, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -87, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 13:03:06.689  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 13:03:06.689  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 13:03:06.689  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 13:03:06.690  4661  4724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-25 13:03:06.695  4661  4724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 13:03:06.695  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:06.695  4661  4735 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:03:06.701  4661  4724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:03:06.701  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:03:06.701  4661  4735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:03:06.706  4661  4724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 13:03:06.706  4661  4724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:03:07.182  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:03:07.182  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:07.183  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:03:11.680  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
11-25 13:03:11.680  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:03:11.681  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:03:11.681  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.681  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:03:11.681  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 13:03:11.681  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:03:11.682  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.682  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:11.682  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.682  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:03:11.682  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:03:11.685  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.686  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.692  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.692  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.693  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.693  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.693  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.693  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:11.693  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:11.697  5593  5641 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-25 13:03:11.698  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.698  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.699  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.699  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:03:11.699  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.699  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.699  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.699  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.699  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.700  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.700  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.702  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.702  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.702  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.702  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.702  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.702  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.702  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.704  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 13:03:11.704  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:03:11.704  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.704  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.705  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.705  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.705  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.705  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:11.705  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:11.705  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.706  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.706  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.708  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.708  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.708  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.708  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.708  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.708  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.708  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:11.709  5593  5641 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 13:03:11.709  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.710  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:03:11.710  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.710  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.710  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.710  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.710  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:11.710  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.710  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.710  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.710  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.712  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.713  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.713  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.713  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.713  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.713  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:11.713  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:11.714  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 13:03:11.714  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.714  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.714  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.715  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.715  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.715  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.715  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.715  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.715  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:03:11.715  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.715  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.717  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.717  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.718  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.718  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.718  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.718  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:11.718  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.718  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:03:11.719  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:03:11.719  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:03:11.719  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:03:11.719  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:03:11.719  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:03:11.719  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-25 13:03:11.719  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:03:11.719  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:03:11.719  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.719  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.720  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.720  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.720  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.720  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.720  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.720  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.720  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.720  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.720  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:11.723  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.723  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.723  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.723  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.724  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.724  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.724  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.725  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:03:11.725  5593  5641 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 13:03:11.725  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-25 13:03:11.728  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:03:11.728  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 13:03:11.728  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 13:03:11.728  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 13:03:11.728  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 13:03:11.728  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 13:03:11.729  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-25 13:03:11.730  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 13:03:11.730  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 13:03:11.730  5593  5641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:03:11.730  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 13:03:11.730  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:03:11.731  5593  5641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:03:11.731  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-25 13:03:11.731  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:03:11.731  5593  5641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:03:11.731  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-25 13:03:11.735  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-25 13:03:11.735  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 13:03:11.735  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 13:03:11.736  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-25 13:03:11.736  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 13:03:11.736  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 13:03:11.736  5593  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:03:11.737  5593  5641 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 13:03:11.737  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.737  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.738  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.738  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.738  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.738  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-25 13:03:11.739  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.739  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.739  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.739  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.739  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.739  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.740  5593  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-25 13:03:11.740  5593  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-25 13:03:11.740  5593  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = true
11-25 13:03:11.740  5593  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 13:03:11.740  5593  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 13:03:11.740  5593  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-25 13:03:11.740  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.740  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.740  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.741  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.741  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.741  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.741  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.741  5593  5641 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 13:03:11.742  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.742  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.742  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.742  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.742  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.742  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.742  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.743  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.743  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.743  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.743  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.744  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.744  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.744  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.744  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.744  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.744  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.744  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.745  5593  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-25 13:03:11.745  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.745  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.745  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.745  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.745  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.746  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.746  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.746  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.746  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.746  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.746  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.747  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.747  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.747  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.747  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.747  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.747  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.747  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.748  5593  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 13:03:11.748  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 13:03:11.748  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:03:11.748  5593  5641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 13:03:11.748  5593  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 13:03:11.749  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 13:03:11.749  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:03:11.749  5593  5641 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 13:03:11.749  5593  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 13:03:11.749  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 13:03:11.749  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:03:11.749  5593  5641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 13:03:11.749  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:11.749  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:11.749  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:11.749  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.749  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.749  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.749  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.749  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.749  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:11.750  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.750  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.751  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.751  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.751  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:11.751  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:11.751  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:11.751  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.751  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.752  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:11.752  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:11.752  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:11.752  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:11.752  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:11.752  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:03:11.847   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-25 13:03:11.847   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:03:16.753  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:16.753  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:16.754  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:16.754  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:16.754  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
,11-25 13:03:16.754  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:16.754  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:16.755  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:16.755  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:03:16.755  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:16.755  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:16.755  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.755  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:16.756  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:16.756  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.756  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.761  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.762  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.762  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.762  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:16.762  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:03:16.762  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.762  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:16.766  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-25 13:03:16.767  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:03:16.767  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:03:16.774  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-25 13:03:16.776  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-25 13:03:16.776  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-25 13:03:16.776  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 13:03:16.777  5593  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-25 13:03:16.777  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-25 13:03:16.777  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:03:16.777  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-25 13:03:16.778  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:16.778  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-25 13:03:16.778  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 13:03:16.779  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 13:03:16.779  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:03:16.780  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 13:03:16.780  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-25 13:03:16.781  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:16.781  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 13:03:16.781  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:16.781  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-25 13:03:16.781  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.781  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:03:16.781  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:03:16.781  4882  4882 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32694]" dev="sockfs" ino=32694 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:03:16.782  5593  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:16.782  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.785  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.785  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:03:16.785  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.781  4882  4882 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32694]" dev="sockfs" ino=32694 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:03:16.785  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.785  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:16.786  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:16.786  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:03:16.786  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:16.786  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:03:16.786  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:16.786  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:03:16.786  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:16.786  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 13:03:16.787  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:16.787  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.787  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:16.787  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:16.787  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.788  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.788  5593  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 13:03:16.788  5593  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-25 13:03:16.788  5593  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 13:03:16.789  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-25 13:03:16.789  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:16.791  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.792  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.792  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.792  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:16.793  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:16.794  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.794  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:16.796  5593  5641 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-25 13:03:16.797  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 13:03:16.797  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:03:16.798  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-25 13:03:16.798  5593  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:03:16.798  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:16.798  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:16.798  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:16.799  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:03:16.799  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:16.799  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:16.799  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.799  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:16.799  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:03:16.800  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.800  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.802  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.802  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.802  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.803  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:16.803  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:03:16.803  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.803  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
,11-25 13:03:16.810  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:16.810  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:03:16.810  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:16.810  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:03:16.810  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:16.810  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:16.810  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:16.811  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:16.811  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:16.811  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.811  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.813  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.813  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.813  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.813  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:16.813  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:03:16.814  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.814  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:16.816  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:03:16.816  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:03:16.816  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:03:16.816  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:03:16.816  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:03:16.816  5593  5641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4c57f4 not in the list
11-25 13:03:16.817  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.817  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:16.817  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:03:16.817  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.817  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.818  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.818  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:03:16.819  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:03:16.819  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:03:16.819  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:03:16.819  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:16.819  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@705fb1d not in the list
11-25 13:03:16.820  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-25 13:03:16.820  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:03:16.821  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-25 13:03:16.821  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:03:16.821  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 13:03:16.821  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:03:16.823  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-25 13:03:16.823  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-25 13:03:16.824  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-25 13:03:16.824  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 13:03:16.824  5593  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 13:03:16.824  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 13:03:16.824  5593  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-25 13:03:16.824  5593  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-25 13:03:16.825  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-25 13:03:16.825  5593  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 13:03:16.826  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-25 13:03:16.826  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 13:03:16.826  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 13:03:16.826  5593  5641 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-25 13:03:16.827  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:03:16.827  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb0f53 added. We now have 3 listener(s)
11-25 13:03:16.827  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:03:16.830  5593  5641 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 13:03:16.831   930  3424 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-25 13:03:16.831   930  3424 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:03:16.847   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:17.287  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:03:17.848   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:18.849   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:18.921   930  5364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:03:18.938   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:03:19.850   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:20.609   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:03:20.851   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:21.837  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:03:21.838  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2530090 added. We now have 4 listener(s)
11-25 13:03:21.838  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:03:21.851  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:03:21.852  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2530090 removed from the list
11-25 13:03:21.852   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
11-25 13:03:21.852  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:21.854  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:03:21.854  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e34d89 added. We now have 4 listener(s)
,11-25 13:03:21.854  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:03:21.857  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:21.858  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e34d89 removed from the list
11-25 13:03:21.858  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:21.859  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:03:21.859  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15df18e added. We now have 4 listener(s)
11-25 13:03:21.860  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:03:21.865   930  3424 D WifiService: setWifiEnabled: false pid=5593, uid=10077
,11-25 13:03:21.865   930  3424 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:03:21.875   930  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 13:03:21.876   930  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 13:03:21.876   930  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:03:21.876   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:03:21.882  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:03:21.882  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:03:21.886  4661  4720 D BluetoothAdapterState: Current state: ON, message: 23
11-25 13:03:21.886  4661  4720 D BluetoothAdapterProperties: Setting state to 13
11-25 13:03:21.886  4661  4720 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 13:03:21.888  4661  4720 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 13:03:21.889  4661  4720 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:03:21.892  4661  4661 D BluetoothMapService: onReceive
11-25 13:03:21.892  4661  4661 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:03:21.892  4661  4661 D BluetoothMapService: STATE_TURNING_OFF
11-25 13:03:21.893  4661  4661 D BluetoothMapService: MAP Service closeService in
11-25 13:03:21.893  4661  4661 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 13:03:21.895  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:03:21.895  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:03:21.895  4661  4661 D ObexServerSockets0: shutdown(block = true)
11-25 13:03:21.897  4661  4885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-25 13:03:21.897   930  5366 D DhcpClient: Clearing IP address
11-25 13:03:21.897   509   924 D CommandListener: Clearing all IP addresses on wlan0
11-25 13:03:21.897  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:21.898  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:03:21.898  5593  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:03:21.900  4661  4661 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:03:21.900  4661  4661 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:03:21.900  4661  4870 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 13:03:21.900  4661  4886 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 13:03:21.901  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:21.903  4661  4661 I BtOppRfcommListener: stopping Accept Thread
,11-25 13:03:21.905  4661  5294 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-25 13:03:21.905  4661  5294 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 13:03:21.906   509   924 D CommandListener: Setting iface cfg
,11-25 13:03:21.908  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:21.909  3579  5417 V NativeCrypto: Read error: ssl=0x7f90d82000: I/O error during system call, Connection timed out
,11-25 13:03:21.911  3579  5417 V NativeCrypto: SSL shutdown failed: ssl=0x7f90d82000: I/O error during system call, Broken pipe
,11-25 13:03:21.913   930  5367 D DhcpClient: Receive thread stopped
11-25 13:03:21.913  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:21.915   930   943 I ActivityManager: Start proc 5661:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-25 13:03:21.916  4661  4724 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:03:21.917  4661  4720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 13:03:21.921   930   940 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 13:03:21.921   930  5363 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-25 13:03:21.922  4661  4661 D HeadsetService: Received stop request...Stopping profile...
11-25 13:03:21.923   930  5363 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-25 13:03:21.924  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:21.925   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-25 13:03:21.925   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 13:03:21.927   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 13:03:21.928  3135  3146 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:21.928   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:21.928  4661  4661 D A2dpService: Received stop request...Stopping profile...
11-25 13:03:21.928  4661  4877 D A2dpStateMachine: Exit Disconnected: -1
11-25 13:03:21.928  3783  3810 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:21.929   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:21.929   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:21.929   930   930 D BluetoothA2dp: Proxy object disconnected
11-25 13:03:21.930   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 13:03:21.930   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-25 13:03:21.930  4661  4661 D HidService: Received stop request...Stopping profile...
11-25 13:03:21.931  4661  4661 D HidService: Stopping Bluetooth HidService
11-25 13:03:21.933  4661  4661 D HealthService: Received stop request...Stopping profile...
11-25 13:03:21.935   930   930 D RttService: SCAN_AVAILABLE : 1
11-25 13:03:21.935   535   535 E Parcel  : Reading a NULL string not supported here.
11-25 13:03:21.937  4661  4661 D PanService: Received stop request...Stopping profile...
11-25 13:03:21.937   930  3087 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 13:03:21.938  4661  4661 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:21.938  4661  4661 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:21.938  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:21.938  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:21.941  4661  4661 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 13:03:21.940  3135  3135 D HeadsetProfile: Bluetooth service disconnected
,11-25 13:03:21.941  4661  4661 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 13:03:21.941  4661  4724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 13:03:21.941  4661  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:21.941  4661  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:21.941  4661  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:21.941  4661  4661 D BluetoothMapService: Received stop request...Stopping profile...
11-25 13:03:21.942  4661  4661 D BluetoothMapService: stop()
11-25 13:03:21.942  4661  4661 D BluetoothMapAppObserver: deinitObservers()
11-25 13:03:21.942  4661  4661 D BluetoothMapAppObserver: removeReceiver()
11-25 13:03:21.942   930  2980 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-25 13:03:21.943  3739  3878 W QCNEJ   : |CORE| network lost: 100
11-25 13:03:21.944  4661  4724 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 13:03:21.945  4661  4661 D SapService: Received stop request...Stopping profile...
11-25 13:03:21.945  4661  4661 V SapService: stop()
11-25 13:03:21.945  3739  3878 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 13:03:21.946  3135  3135 D BluetoothA2dp: Proxy object disconnected
,11-25 13:03:21.946  3135  3135 D BluetoothInputDevice: Proxy object disconnected
11-25 13:03:21.946  3135  3135 D HidProfile: Bluetooth service disconnected
11-25 13:03:21.946  3135  3135 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:03:21.946  3135  3135 D PanProfile: Bluetooth service disconnected
,11-25 13:03:21.950  4661  4661 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:21.950  4661  4661 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:21.950  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:21.950  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:03:21.951  4661  4724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 13:03:21.951  4661  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:21.951  4661  4661 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:21.951  4661  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:21.951  4661  4661 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:03:21.951  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:21.951  4661  4868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:03:21.951  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:21.951  4661  4868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 13:03:21.951  4661  4868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-25 13:03:21.951  4661  4868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 13:03:21.952  4661  4661 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-25 13:03:21.952  4661  4661 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 13:03:21.952  4661  4724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:03:21.952  4661  4661 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:03:21.952  4661  4661 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:03:21.952  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:21.952  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:21.952  4661  4661 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-25 13:03:21.952  4661  4724 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-25 13:03:21.953  4661  4661 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-25 13:03:21.953  4661  4661 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:03:21.953  4661  4661 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:03:21.953  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:03:21.953  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:03:21.953  3135  3135 D BluetoothMap: Proxy object disconnected
11-25 13:03:21.953  3135  3135 D MapProfile: Bluetooth service disconnected
11-25 13:03:21.954  4661  4661 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 13:03:21.955   930  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 13:03:21.954  4661  4661 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 13:03:21.956  4661  4661 D BluetoothMapService: MAP Service closeService in
11-25 13:03:21.956  4661  4661 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:21.956  4661  4661 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:21.956  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:03:21.956  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:21.957  4661  4661 D BluetoothMapService: cleanup()
11-25 13:03:21.957  4661  4661 D BluetoothMapService: MAP Service closeService in
11-25 13:03:21.957  4661  4661 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:21.957  4661  4661 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:21.957  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:21.957  4661  4661 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:21.957  4661  4720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 13:03:21.957  4661  4720 D BluetoothAdapterProperties: Setting state to 15
11-25 13:03:21.957  4661  4720 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 13:03:21.958  4661  4720 I BluetoothAdapterState: Entering BleOnState
11-25 13:03:21.964   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:03:21.964  3135  3146 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:03:21.966  3135  3974 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:03:21.968  3135  3147 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:03:21.969  3783  3799 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:21.969   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:03:21.970  3135  3146 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:21.970  3135  3974 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:03:21.970  3135  3147 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:03:21.971   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:03:21.971   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:21.972  4661  4720 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 13:03:21.972  4661  4720 D BluetoothAdapterProperties: Setting state to 16
11-25 13:03:21.972  4661  4720 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 13:03:21.972  4661  4720 D BluetoothAdapterProperties: onBleDisable
11-25 13:03:21.973  4661  4720 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:03:21.973  4661  4721 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 13:03:21.973   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:03:21.973  4661  4868 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-25 13:03:21.973  4661  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:21.974  4661  4724 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:03:21.978  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:21.978  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:03:21.979   930  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:03:21.980  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:21.980  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:03:21.989  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:21.990   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:03:21.991   509   924 D CommandListener: Clearing all IP addresses on wlan0
11-25 13:03:21.992   930  2980 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 13:03:21.992   509   924 D TetherController: Setting IP forward enable = 0
11-25 13:03:21.992   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 13:03:21.993   930   947 D Tethering: MasterInitialState.processMessage what=3
11-25 13:03:21.995   930  2975 D DhcpClient: doQuit
11-25 13:03:21.995   930  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 13:03:21.996  3454  3454 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 13:03:21.996   930  5366 D DhcpClient: onQuitting
,11-25 13:03:21.997  5246  5246 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6ef37e4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-25 13:03:21.998  3960  3960 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 13:03:21.998  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:21.998  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:03:21.999  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:22.000  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:03:22.001  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:22.002  5036  5060 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 13:03:22.002  5036  5060 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:03:22.002  5036  5060 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 13:03:22.002  5036  5060 E SarControlService: no key has been found,reset the power
11-25 13:03:22.003  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:03:22.003  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:03:22.003  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:03:22.003  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:03:22.003  5061  5061 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:03:22.005  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:03:22.005  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:03:22.005  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:03:22.006  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 13:03:22.007  5061  5061 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 13:03:22.009  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000ea03000000000000ffffffff]
11-25 13:03:22.010  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:03:22.010  5061  5075 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 13:03:22.010  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:03:22.010  5036  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:03:22.014  5661  5661 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-25 13:03:22.018  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000eb03000000000000ffffffff]
,11-25 13:03:22.018  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:03:22.018  5061  5075 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-25 13:03:22.019  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:03:22.019  5036  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:03:22.026  3454  3454 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:03:22.030  3454  3454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 13:03:22.031  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:03:22.032   509   917 W SocketClient: write error (Broken pipe)
11-25 13:03:22.032   509   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-25 13:03:22.032   509   917 W SocketListener: Error sending broadcast (Broken pipe)
,11-25 13:03:22.037   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccdba19:true
11-25 13:03:22.037  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:22.056  5661  5661 D LocalBluetoothProfileManager: Adding local MAP profile
11-25 13:03:22.058  5661  5661 D BluetoothMap: Create BluetoothMap proxy object
,11-25 13:03:22.064  5661  5661 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 13:03:22.071  3454  3454 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 13:03:22.072  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:03:22.075  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:03:22.080  3454  3454 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-25 13:03:22.080   509   917 W SocketClient: write error (Broken pipe)
,11-25 13:03:22.080   509   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-25 13:03:22.080   509   917 W SocketListener: Error sending broadcast (Broken pipe)
11-25 13:03:22.082  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:03:22.083  5661  5661 D DockEventReceiver: finishStartingService: stopping service
11-25 13:03:22.084   930  3836 I ActivityManager: Killing 5391:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-25 13:03:22.102  3977  3977 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:03:22.105  3977  3977 D SystemUpdateService: onCreate
,11-25 13:03:22.108  3977  3977 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:03:22.116  3977  3977 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 13:03:22.120  3977  5388 I iu.UploadsManager: num queued entries: 0
11-25 13:03:22.120  3977  5388 I iu.UploadsManager: num updated entries: 0
11-25 13:03:22.121  3977  5388 I iu.SyncManager: NEXT; no task
,11-25 13:03:22.122  3977  5694 I SystemUpdateService: active receiver: enabled
,11-25 13:03:22.125  3977  3977 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:03:22.127  3977  3977 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:03:22.130  3977  5694 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-25 13:03:22.131  3977  5694 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-25 13:03:22.132  3977  5694 I SystemUpdateService: now status is 0 (complete)
11-25 13:03:22.132  3977  5694 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:03:22.132  3977  5694 I SystemUpdateService: file has been verified
11-25 13:03:22.132  3977  5694 I SystemUpdateService: OTA package size = 21989297
,11-25 13:03:22.138  3977  5694 I SystemUpdateService: showing system update notification
,11-25 13:03:22.139   930  3129 I ActivityManager: Start proc 5696:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-25 13:03:22.153   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:03:22.155  3977  3977 D SystemUpdateService: onDestroy
,11-25 13:03:22.184   930  2975 D wifi    : In wifi stop Hal
,11-25 13:03:22.184   930  2975 D wifi    : halHandle = 0x7f7a6c8400, mVM = 0x7f96d0d140, mCls = 0x100a02
11-25 13:03:22.184   930  3452 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 13:03:22.184   930  3452 D WifiHAL : Got a signal to exit!!!
11-25 13:03:22.184   930  3452 I WifiHAL : Exit wifi_event_loop
11-25 13:03:22.184   930  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-25 13:03:22.184   930  2975 E WifiHAL : Event processing terminated
11-25 13:03:22.184   930  2975 D wifi    : In wifi cleaned up handler
11-25 13:03:22.185   930  2975 I WifiHAL : Internal cleanup completed
,11-25 13:03:22.186  4661  4724 I bt_hci  : shut_down
,11-25 13:03:22.187  5696  5696 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-25 13:03:22.188  4661  4738 I bt_vendor: low_power_mode_cb
,11-25 13:03:22.189  5011  5011 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:03:22.190  4109  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:03:22.191  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:22.191  4661  4738 D bt_hwcfg: hw_epilog_process
,11-25 13:03:22.194  4661  4738 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-25 13:03:22.194  4661  4738 I bt_vendor: epilog_cb
11-25 13:03:22.194  4661  4738 I bt_hci  : epilog_finished_callback
11-25 13:03:22.196  5696  5696 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 13:03:22.197  4661  4724 I bt_hci_h4: hal_close
11-25 13:03:22.198  4661  4724 I bt_userial_vendor: device fd = 54 close
,11-25 13:03:22.205  5696  5696 D SprintDMHelper: simOperator: 
,11-25 13:03:22.205  5696  5696 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:03:22.209   930  3452 D wifi    : set interface wlan0 flags (DOWN)
,11-25 13:03:22.209   930  2975 D WifiNative-HAL: HAL event thread stopped successfully
11-25 13:03:22.210   509   917 W SocketClient: write error (Broken pipe)
11-25 13:03:22.210   509   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
11-25 13:03:22.210   509   917 W SocketListener: Error sending broadcast (Broken pipe)
,11-25 13:03:22.219  5011  5708 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 13:03:22.233   930  3162 I ActivityManager: Start proc 5709:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 13:03:22.235   930  3162 I ActivityManager: Killing 5246:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 13:03:22.273  5709  5709 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 13:03:22.280   930  3162 I ActivityManager: Killing 5466:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-25 13:03:22.302  4661  4721 D bt_stack_manager: event_shut_down_stack finished.
,11-25 13:03:22.303  4661  4720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-25 13:03:22.304  4661  4661 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:03:22.304  4661  4720 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 13:03:22.305  4661  4661 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 13:03:22.305  4661  4661 D BtGatt.GattService: stop()
,11-25 13:03:22.305  4661  4661 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 13:03:22.306  4661  4661 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:22.306  4661  4661 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:22.306  4661  4661 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:22.306  4661  4661 V BluetoothAdapterState: isBleTurningOff()=true
11-25 13:03:22.306  4661  4720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 13:03:22.307  4661  4720 D BluetoothAdapterProperties: Setting state to 10
11-25 13:03:22.307  4661  4720 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 13:03:22.307  4661  4720 I BluetoothAdapterState: Entering OffState
11-25 13:03:22.307   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 13:03:22.313  4661  4661 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 13:03:22.313  4661  4661 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 13:03:22.314  4661  4661 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 13:03:22.315  4661  4721 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 13:03:22.317  4661  4661 I art     : System.exit called, status: 0
11-25 13:03:22.317  4661  4661 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 13:03:22.341   930  3424 I ActivityManager: Process com.android.bluetooth (pid 4661) has died
,11-25 13:03:22.413   930   947 D Tethering: InitialState.processMessage what=4
,11-25 13:03:22.420   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 13:03:23.075   509   924 E Netd    : netlink response contains error (No such file or directory)
,11-25 13:03:23.076   930  2980 E NetdConnector: NDC Command {114 network destroy 100} took too long (1083ms)
11-25 13:03:23.076   930  2980 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 13:03:23.079   930  2956 E NetdConnector: NDC Command {115 bandwidth setglobalalert 2097152} took too long (1082ms)
,11-25 13:03:23.079   930  2952 E NetdConnector: NDC Command {116 bandwidth gettetherstats} took too long (657ms)
11-25 13:03:23.079   509   924 D TetherController: Setting IP forward enable = 0
,11-25 13:03:26.853   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:26.901   930  3804 D WifiService: setWifiEnabled: true pid=5593, uid=10077
,11-25 13:03:26.901   930  3804 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:03:26.911   509   924 D SoftapController: Softap fwReload - Ok
,11-25 13:03:26.915   509   924 D CommandListener: Setting iface cfg
,11-25 13:03:26.915   509   924 D CommandListener: Trying to bring down wlan0
11-25 13:03:26.916   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:03:26.922   930  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 13:03:27.524   930  2975 D wifi    : set interface wlan0 flags (UP)
,11-25 13:03:27.528   930  2975 I WifiHAL : Initializing wifi
11-25 13:03:27.528   930  2975 I WifiHAL : Creating socket
,11-25 13:03:27.530   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 13:03:27.533   930  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 13:03:27.534   930  2975 D wifi    : Did set static halHandle = 0x7f7a6c8400
11-25 13:03:27.534   930  2975 D wifi    : halHandle = 0x7f7a6c8400, mVM = 0x7f96d0d140, mCls = 0x1962
,11-25 13:03:27.534   930  2975 D wifi    : array field set
11-25 13:03:27.534   930  2975 I WifiNative-HAL: interface[0] = wlan0
11-25 13:03:27.537   930  5729 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547514778624
11-25 13:03:27.537   930  5729 D wifi    : waitForHalEvents called, vm = 0x7f96d0d140, obj = 0x1962, env = 0x7f7e744040
,11-25 13:03:27.613  5730  5730 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 13:03:27.639   930  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 13:03:27.645  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:27.699  5730  5730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:03:27.725  5730  5730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:03:27.725  5730  5730 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 13:03:27.739   930  2975 D WifiConfigStore: Loading config and enabling all networks 
,11-25 13:03:27.746  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:27.746  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:03:27.747  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:27.747  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:03:27.760   930  2975 D WifiConfigStore: loaded 0 passpoint configs
,11-25 13:03:27.761   930  2975 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 13:03:27.761   930  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 13:03:27.762   930  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 13:03:27.762   930  2975 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-25 13:03:27.762   930  2975 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-25 13:03:27.763   930  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 13:03:27.763   930  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-25 13:03:27.763   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 13:03:27.763   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 13:03:27.763   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 13:03:27.763   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 13:03:27.763   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 13:03:27.765   930  2975 D WifiNative-HAL: Setting external_sim to 1
11-25 13:03:27.765   930  2975 D wifi    : setting dfs flag to true, 0x7f77eb51c0
11-25 13:03:27.766   930  2975 D WifiStateMachine: Setting OUI to DA-A1-19
,11-25 13:03:27.766   930  2975 D wifi    : setting scan oui 0x7f77eb51c0
11-25 13:03:27.766   930  2975 D WifiHAL : Sending mac address OUI
11-25 13:03:27.766  5011  5011 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:03:27.769   930  2975 E native  : do suspend false
,11-25 13:03:27.775   930  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-25 13:03:27.775   930   930 D RttService: SCAN_AVAILABLE : 3
11-25 13:03:27.775   930  3087 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 13:03:27.780   509   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-25 13:03:27.782   509   924 D CommandListener: Setting iface cfg
,11-25 13:03:27.784   930  2960 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-25 13:03:27.784   930  2960 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 13:03:27.791   930  2960 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 13:03:27.791   930  2960 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 13:03:27.797   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129460 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-25 13:03:27.853   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:28.855   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:29.856   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:30.852  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:03:30.856   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:30.861  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:03:30.888   930  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 13:03:30.889   930  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 13:03:30.889   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:03:30.899   930  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 13:03:30.932   930  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 13:03:30.937  5730  5730 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 13:03:31.359  5730  5730 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 13:03:31.419  5730  5730 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 13:03:31.420  5730  5730 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 13:03:31.439   930  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:03:31.439   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 13:03:31.440   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 13:03:31.456   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:03:31.470   509   924 D CommandListener: Setting iface cfg
,11-25 13:03:31.475   930  2975 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 13:03:31.484   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:03:31.484   930  2980 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 13:03:31.484   930  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-25 13:03:31.486   930  5738 D DhcpClient: Receive thread started
,11-25 13:03:31.568   930  2975 E native  : do suspend false
,11-25 13:03:31.582   930  5737 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 13:03:31.595   930  5738 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-25 13:03:31.596   930  5737 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-25 13:03:31.598   930  5737 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 13:03:31.611   930  5738 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 13:03:31.612   930  5737 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 13:03:31.619   509   924 D CommandListener: Setting iface cfg
,11-25 13:03:31.624   930  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 13:03:31.630   930  5737 D DhcpClient: Scheduling renewal in 86399s
,11-25 13:03:31.637   930  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 13:03:31.638   930  2975 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 13:03:31.639   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 13:03:31.641   930  2980 D ConnectivityService: Adding iface wlan0 to network 101
11-25 13:03:31.648   930  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 13:03:31.688   930  2980 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 13:03:31.688   930  2980 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 13:03:31.691   930  2980 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 13:03:31.696   930  2980 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 13:03:31.698   930  2980 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 13:03:31.708   930  2980 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:03:31.712   930  2980 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-25 13:03:31.713   930  2980 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-25 13:03:31.713   930  2980 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 13:03:31.713   930  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 13:03:31.713   930  2980 D ConnectivityService:    accepting network in place of null
11-25 13:03:31.713   930  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:03:31.714   930  2980 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:03:31.721   930  5736 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:03:31.737   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:03:31.761   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:03:31.764   930  2980 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 13:03:31.764   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 13:03:31.764  3739  3878 W QCNEJ   : |CORE| network available: 101
11-25 13:03:31.765   930  2980 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-25 13:03:31.766   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-25 13:03:31.769  3739  3878 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 13:03:31.770  3739  3878 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-25 13:03:31.770  3739  3878 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 13:03:31.772  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:03:31.772  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:03:31.772  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:31.772  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:03:31.776  3960  3960 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-25 13:03:31.780  5036  5060 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 13:03:31.780  5036  5060 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:03:31.780  5036  5060 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 13:03:31.780  5036  5060 E SarControlService: no key has been found,reset the power
11-25 13:03:31.780  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:03:31.780  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-25 13:03:31.780  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:03:31.781  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:03:31.781  5061  5061 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:03:31.782  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:03:31.782  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:03:31.782  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:03:31.783  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:03:31.783  5061  5061 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:03:31.786  3977  3977 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:03:31.789  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000ec03000000000000ffffffff]
11-25 13:03:31.789  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:03:31.789  5061  5075 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 13:03:31.789  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000ed03000000000000ffffffff]
11-25 13:03:31.789  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:03:31.789  5061  5075 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-25 13:03:31.790  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 13:03:31.791  5036  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:03:31.793   930  5735 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 13:03:31.793  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 13:03:31.794  5036  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:03:31.791  3977  3977 D SystemUpdateService: onCreate
,11-25 13:03:31.797  3977  3977 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:03:31.808  3977  3977 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 13:03:31.813  3977  5388 I iu.UploadsManager: num queued entries: 0
,11-25 13:03:31.813  3977  5388 I iu.UploadsManager: num updated entries: 0
11-25 13:03:31.814  3977  5388 I iu.SyncManager: NEXT; no task
,11-25 13:03:31.816  3977  5748 I SystemUpdateService: active receiver: enabled
,11-25 13:03:31.819  3977  3977 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:03:31.821  3977  3977 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:03:31.822  5696  5696 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:03:31.826  5696  5696 D SprintDMHelper: simOperator: 
11-25 13:03:31.826  5696  5696 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:03:31.844   930  5735 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:03:31 GMT], X-Android-Received-Millis=[1480075411844], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480075411818]}
,11-25 13:03:31.845   930  2980 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 13:03:31.845   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-25 13:03:31.845   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:03:31.846   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-25 13:03:31.857   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 13:03:31.863  3977  5748 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:03:31.870  3977  5748 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 13:03:31.870  3977  5748 I SystemUpdateService: now status is 0 (complete)
11-25 13:03:31.870  3977  5748 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:03:31.870  3977  5748 I SystemUpdateService: file has been verified
11-25 13:03:31.871  3977  5748 I SystemUpdateService: OTA package size = 21989297
,11-25 13:03:31.876  3977  5748 I SystemUpdateService: showing system update notification
,11-25 13:03:31.885   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:03:31.886  3977  3977 D SystemUpdateService: onDestroy
,11-25 13:03:31.907   930  3787 D WifiService: setWifiEnabled: false pid=5593, uid=10077
,11-25 13:03:31.907   930  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:03:31.908   930  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-25 13:03:31.909   930  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 13:03:31.909   930  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:03:31.909   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:03:31.917   930  5737 D DhcpClient: Clearing IP address
11-25 13:03:31.917   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:03:31.918   509   924 D CommandListener: Setting iface cfg
,11-25 13:03:31.922  3579  5749 V NativeCrypto: SSL handshake aborted: ssl=0x7f7c618000: I/O error during system call, Connection timed out
,11-25 13:03:31.926   930   941 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-25 13:03:31.926   930  5735 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-25 13:03:31.926   930  5735 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 13:03:31.932   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 13:03:31.932   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-25 13:03:31.935   930  5735 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-25 13:03:31.935   535   535 E Parcel  : Reading a NULL string not supported here.
11-25 13:03:31.938  5011  5752 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-25 13:03:31.938   930  2980 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-25 13:03:31.939  3739  3878 W QCNEJ   : |CORE| network lost: 101
11-25 13:03:31.940  3739  3878 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 13:03:31.941   930   930 D RttService: SCAN_AVAILABLE : 1
11-25 13:03:31.941   930  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 13:03:31.941   930  3087 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 13:03:31.945   930  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:03:31.952   930  5738 D DhcpClient: Receive thread stopped
,11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.22.110 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
11-25 13:03:31.954  5011  5752 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-25 13:03:31.954  5011  5752 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 13:03:31.963   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:03:31.982   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:03:31.982   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:03:31.983   930  2980 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 13:03:31.983   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:03:31.985   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-25 13:03:31.988   930  2975 D DhcpClient: doQuit
11-25 13:03:31.988   930  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 13:03:31.988   930  5737 D DhcpClient: onQuitting
11-25 13:03:31.989  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:31.989  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:03:31.989  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:31.989  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:03:31.989  5730  5730 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 13:03:31.990  3960  3960 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-25 13:03:31.994  3977  3977 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 13:03:31.994  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:31.995  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:03:31.995  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:31.995  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:03:31.995  5036  5060 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:03:31.995  5036  5060 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:03:31.995  5036  5060 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 13:03:31.995  5036  5060 E SarControlService: no key has been found,reset the power
11-25 13:03:31.996  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:03:31.996  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-25 13:03:31.996  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:03:31.997  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:03:31.997  5061  5061 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:03:31.998  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:03:31.998  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 13:03:31.998  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:03:31.999  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:03:31.999  5061  5061 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 13:03:32.002  3977  3977 D SystemUpdateService: onCreate
11-25 13:03:32.004  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000ee03000000000000ffffffff]
11-25 13:03:32.004  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-25 13:03:32.004  5061  5075 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 13:03:32.004  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:03:32.004  5036  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:03:32.005  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-25 13:03:32.006  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000ef03000000000000ffffffff]
11-25 13:03:32.006  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:03:32.007  5061  5075 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,11-25 13:03:32.008  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 13:03:32.008  5036  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 13:03:32.009  5730  5730 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-25 13:03:32.009  3977  3977 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:03:32.014  3977  5766 I SystemUpdateService: active receiver: enabled
,11-25 13:03:32.018  3977  3977 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 13:03:32.023  3977  5388 I iu.UploadsManager: num queued entries: 0
,11-25 13:03:32.024  3977  5388 I iu.UploadsManager: num updated entries: 0
,11-25 13:03:32.025  3977  5388 I iu.SyncManager: NEXT; no task
,11-25 13:03:32.028  3977  3977 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:03:32.030  3977  3977 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:03:32.031  5696  5696 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 13:03:32.035  5696  5696 D SprintDMHelper: simOperator: 
11-25 13:03:32.035  5696  5696 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:03:32.038   509   924 E Netd    : netlink response contains error (No such file or directory)
,11-25 13:03:32.040   930  2980 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 13:03:32.043  3977  5766 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:03:32.046  5730  5730 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 13:03:32.046  5011  5770 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 13:03:32.050  3977  5766 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 13:03:32.051  3977  5766 I SystemUpdateService: now status is 0 (complete)
11-25 13:03:32.051  3977  5766 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-25 13:03:32.051  3977  5766 I SystemUpdateService: file has been verified
11-25 13:03:32.052  3977  5766 I SystemUpdateService: OTA package size = 21989297
,11-25 13:03:32.057  5730  5730 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:03:32.068  3977  5766 I SystemUpdateService: showing system update notification
,11-25 13:03:32.075   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:03:32.077  3977  3977 D SystemUpdateService: onDestroy
,11-25 13:03:32.161   930  2975 D wifi    : In wifi stop Hal
,11-25 13:03:32.161   930  2975 D wifi    : halHandle = 0x7f7a6c8400, mVM = 0x7f96d0d140, mCls = 0x1962
11-25 13:03:32.162   930  5729 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 13:03:32.162   930  5729 D WifiHAL : Got a signal to exit!!!
11-25 13:03:32.162   930  5729 I WifiHAL : Exit wifi_event_loop
11-25 13:03:32.162  5011  5011 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:03:32.163   930  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-25 13:03:32.163   930  2975 E WifiHAL : Event processing terminated
11-25 13:03:32.163   930  2975 D wifi    : In wifi cleaned up handler
11-25 13:03:32.163   930  2975 I WifiHAL : Internal cleanup completed
11-25 13:03:32.164  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:32.168  4109  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:03:32.185   930  5729 D wifi    : set interface wlan0 flags (DOWN)
,11-25 13:03:32.185   930  2975 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 13:03:32.388   930   947 D Tethering: InitialState.processMessage what=4
,11-25 13:03:32.392   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 13:03:32.765   930  2980 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 13:03:36.944   930   947 I ActivityManager: Start proc 5772:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 13:03:37.037  5772  5772 D AdapterServiceConfig: Adding HeadsetService
,11-25 13:03:37.038  5772  5772 D AdapterServiceConfig: Adding A2dpService
11-25 13:03:37.038  5772  5772 D AdapterServiceConfig: Adding HidService
11-25 13:03:37.038  5772  5772 D AdapterServiceConfig: Adding HealthService
11-25 13:03:37.038  5772  5772 D AdapterServiceConfig: Adding PanService
11-25 13:03:37.038  5772  5772 D AdapterServiceConfig: Adding GattService
11-25 13:03:37.038  5772  5772 D AdapterServiceConfig: Adding BluetoothMapService
11-25 13:03:37.039  5772  5772 D AdapterServiceConfig: Adding SapService
,11-25 13:03:37.050   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ecef903:true
,11-25 13:03:37.050  5772  5772 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 13:03:37.053  5772  5772 I bt_bluedroid: init
,11-25 13:03:37.053  5772  5784 I BluetoothAdapterState: Entering OffState
,11-25 13:03:37.055  5772  5785 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 13:03:37.055  5772  5785 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-25 13:03:37.055  5772  5785 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 13:03:37.055  5772  5785 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 13:03:37.056  5772  5772 I bt_bluedroid: get_profile_interface socket
11-25 13:03:37.058  5772  5788 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 13:03:37.057  5772  5772 I bt_bluedroid: get_profile_interface sdp
11-25 13:03:37.059  5772  5788 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:03:37.062  5772  5782 I bt_bluedroid: config_hci_snoop_log
,11-25 13:03:37.063   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 13:03:37.066  5772  5784 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 13:03:37.066  5772  5784 D BluetoothAdapterProperties: Setting state to 14
11-25 13:03:37.066  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 13:03:37.068  5772  5784 D BluetoothBondStateMachine: make
,11-25 13:03:37.070  5772  5789 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 13:03:37.072  5772  5784 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:03:37.073  5772  5772 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 13:03:37.075  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:37.076  5772  5772 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 13:03:37.076  5772  5772 D BtGatt.GattService: Received start request. Starting profile...
11-25 13:03:37.076  5772  5772 D BtGatt.GattService: start()
11-25 13:03:37.076  5772  5772 I bt_bluedroid: get_profile_interface gatt
11-25 13:03:37.077  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:37.077  5772  5772 D BtGatt.AdvertiseManager: advertise manager created
,11-25 13:03:37.081  5772  5772 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:03:37.081  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:37.081  5772  5772 V BluetoothAdapterState: isBleTurningOn()=true
11-25 13:03:37.081  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.082  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 13:03:37.083  5772  5784 I bt_bluedroid: bt_bluedroid
11-25 13:03:37.083  5772  5785 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 13:03:37.084  5772  5785 I bt_hci  : start_up
,11-25 13:03:37.088  5772  5785 I bt_vendor: alloc value 0xf426b871
11-25 13:03:37.088  5772  5785 I bt_vendor: init
11-25 13:03:37.088  5772  5785 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 13:03:37.088  5772  5785 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 13:03:37.197  5772  5785 D bt_hci  : start_up starting async portion
11-25 13:03:37.197  5772  5792 I bt_hci  : event_finish_startup
,11-25 13:03:37.197  5772  5792 I bt_hci_h4: hal_open
11-25 13:03:37.197  5772  5792 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 13:03:37.194  5793  5793 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:03:37.199  5772  5792 I bt_userial_vendor: device fd = 54 open
,11-25 13:03:37.213  5772  5792 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:03:37.215  5772  5792 D bt_hwcfg: Chipset BCM4358A3
,11-25 13:03:37.215  5772  5792 D bt_hwcfg: Target name = [BCM4358A3]
11-25 13:03:37.215  5772  5792 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 13:03:37.616  5772  5792 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 13:03:37.617  5772  5792 D bt_hwcfg: Settlement delay -- 100 ms
,11-25 13:03:37.617  5772  5792 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 13:03:37.751  5772  5792 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:03:37.751  5772  5792 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-25 13:03:37.753  5772  5792 I bt_hwcfg: vendor lib fwcfg completed
,11-25 13:03:37.753  5772  5792 I bt_vendor: firmware callback
,11-25 13:03:37.753  5772  5792 I bt_hci  : firmware_config_callback
,11-25 13:03:37.763  5772  5795 I bt_btu  : btu_task pending for preload complete event
,11-25 13:03:37.763  5772  5795 I bt_btu_task: Bluetooth chip preload is complete
11-25 13:03:37.763  5772  5795 I bt_btu  : btu_task received preload complete event
,11-25 13:03:37.769  5772  5795 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 13:03:37.770  5772  5795 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_PAN
,11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 13:03:37.771  5772  5795 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 13:03:37.854  5772  5795 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41e9549
,11-25 13:03:37.854  5772  5795 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41e9549 
,11-25 13:03:37.878  5772  5788 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 13:03:37.878  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:03:37.879  5772  5788 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:03:37.881  5772  5788 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 13:03:37.885  5772  5788 D BluetoothAdapterProperties: Scan Mode:20
,11-25 13:03:37.885  5772  5788 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:03:37.885  5772  5788 D bt_hci  : do_postload posting postload work item
,11-25 13:03:37.885  5772  5792 I bt_hci  : event_postload
11-25 13:03:37.885  5772  5792 I bt_vendor: sco_config_cb
11-25 13:03:37.885  5772  5792 I bt_hci  : sco_config_callback postload finished.
11-25 13:03:37.888  5772  5788 D bt_bte_conf: Device ID record 1 : primary
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   vendorId            = 000f
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   vendorIdSource      = 0001
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   product             = 1200
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   version             = 1436
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   clientExecutableURL = 
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   serviceDescription  = 
11-25 13:03:37.888  5772  5788 D bt_bte_conf:   documentationURL    = 
11-25 13:03:37.888  5772  5788 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 13:03:37.889  5772  5785 D bt_stack_manager: event_start_up_stack finished
,11-25 13:03:37.890  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 13:03:37.890  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:37.890  5772  5784 D BluetoothAdapterProperties: Setting state to 15
11-25 13:03:37.890  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 13:03:37.891  5772  5784 I BluetoothAdapterState: Entering BleOnState
,11-25 13:03:37.893  5772  5792 I bt_vendor: low_power_mode_cb
,11-25 13:03:37.898  5772  5784 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 13:03:37.898  5772  5784 D BluetoothAdapterProperties: Setting state to 11
11-25 13:03:37.898  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 13:03:37.903  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:37.904  5772  5772 D HeadsetService: Received start request. Starting profile...
,11-25 13:03:37.906  5772  5772 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 13:03:37.907  5772  5772 D HeadsetStateMachine: make
11-25 13:03:37.907  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:37.918  5772  5784 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:03:37.921  5772  5772 D HeadsetStateMachine: max_hf_connections = 1
,11-25 13:03:37.921  5772  5772 I bt_bluedroid: get_profile_interface handsfree
11-25 13:03:37.921  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 13:03:37.921  5772  5788 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 13:03:37.924  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:37.925  5772  5772 D A2dpService: Received start request. Starting profile...
,11-25 13:03:37.925  5772  5772 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 13:03:37.925  5772  5772 I bt_bluedroid: get_profile_interface avrcp
,11-25 13:03:37.931  5772  5772 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 13:03:37.932  5772  5772 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 13:03:37.932  5772  5772 D A2dpStateMachine: make
,11-25 13:03:37.932  5772  5772 I bt_bluedroid: get_profile_interface a2dp
11-25 13:03:37.933  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 13:03:37.934  5772  5803 D A2dpStateMachine: Enter Disconnected: -2
,11-25 13:03:37.935  5772  5772 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 13:03:37.936  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:37.937  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:37.939  5772  5772 D HidService: Received start request. Starting profile...
,11-25 13:03:37.939  5772  5772 I bt_bluedroid: get_profile_interface hidhost
11-25 13:03:37.939  5772  5772 D HidService: setHidService(): set to: null
11-25 13:03:37.939  5772  5788 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41ca56d
11-25 13:03:37.939  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 13:03:37.940  5772  5772 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 13:03:37.940  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:37.941  5772  5772 D HealthService: Received start request. Starting profile...
11-25 13:03:37.941  5661  5661 D BluetoothInputDevice: Proxy object connected
11-25 13:03:37.942  5661  5661 D HidProfile: Bluetooth service connected
11-25 13:03:37.942  5772  5772 I bt_bluedroid: get_profile_interface health
11-25 13:03:37.942  5772  5772 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 13:03:37.943  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:37.945  5661  5661 D BluetoothPan: BluetoothPAN Proxy object connected
,11-25 13:03:37.945  5661  5661 D PanProfile: Bluetooth service connected
11-25 13:03:37.945  5772  5772 D PanService: Received start request. Starting profile...
11-25 13:03:37.946  5772  5772 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 13:03:37.946  5772  5772 I bt_bluedroid: get_profile_interface pan
11-25 13:03:37.946  5772  5788 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 13:03:37.950  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:37.950  5661  5661 D BluetoothMap: Proxy object connected
,11-25 13:03:37.951  5772  5772 D BluetoothMapService: Received start request. Starting profile...
11-25 13:03:37.951  5772  5772 D BluetoothMapService: start()
11-25 13:03:37.951  5661  5661 D MapProfile: Bluetooth service connected
11-25 13:03:37.951  5661  5661 D BluetoothMap: getConnectedDevices()
11-25 13:03:37.952  5661  5661 D BluetoothMap: Bluetooth is Not enabled
,11-25 13:03:37.953  5772  5772 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 13:03:37.954  5772  5772 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 13:03:37.954  5772  5772 D BluetoothMapAppObserver: createReceiver()
,11-25 13:03:37.955  5772  5772 D BluetoothMapAppObserver: initObservers()
,11-25 13:03:37.955  5772  5772 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 13:03:37.960  5772  5772 V SapService: SapBinder()
11-25 13:03:37.960  5772  5772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:37.961  5772  5772 D SapService: Received start request. Starting profile...
,11-25 13:03:37.961  5772  5772 V SapService: start()
,11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:03:37.963  5772  5801 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:37.963  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOn()=true
,11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:03:37.964  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.965  5772  5772 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:37.965  5772  5772 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:37.965  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:03:37.965  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:37.965  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 13:03:37.965  5772  5784 D BluetoothAdapterProperties: ScanMode =  20
11-25 13:03:37.965  5772  5784 D BluetoothAdapterProperties: State =  11
11-25 13:03:37.966  5772  5784 D BluetoothAdapterProperties: Setting state to 12
11-25 13:03:37.966  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 13:03:37.966   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:37.966  5772  5784 I BluetoothAdapterState: Entering OnState
11-25 13:03:37.966  3135  3974 D BluetoothPan: onBluetoothStateChange on: true
,11-25 13:03:37.969  5772  5788 D BluetoothAdapterProperties: Scan Mode:21
11-25 13:03:37.969  5772  5788 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:03:37.969  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 13:03:37.971  3135  3147 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:03:37.971  3135  3135 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:03:37.971  3135  3135 D PanProfile: Bluetooth service connected
,11-25 13:03:37.972  3135  3974 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:03:37.973  3135  3135 D BluetoothA2dp: Proxy object connected
11-25 13:03:37.974  3783  3799 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 13:03:37.975  5661  5673 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:03:37.975   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:37.975  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:03:37.975   930   930 D BluetoothA2dp: Proxy object connected
11-25 13:03:37.975  3135  3146 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:37.976  3135  3974 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:03:37.977  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:03:37.978  3135  3135 D BluetoothMap: Proxy object connected
11-25 13:03:37.978  3135  3135 D MapProfile: Bluetooth service connected
11-25 13:03:37.978  5661  5675 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:03:37.978  3135  3135 D BluetoothMap: getConnectedDevices()
11-25 13:03:37.979  5772  5772 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:03:37.979  5661  5673 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:03:37.979  3135  3147 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:03:37.980  5772  5772 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 13:03:37.981   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:37.981  3135  3135 D BluetoothInputDevice: Proxy object connected
11-25 13:03:37.981  3135  3135 D HidProfile: Bluetooth service connected
11-25 13:03:37.981  5772  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:03:37.981  5661  5675 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:03:37.981   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:37.982   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 13:03:37.983  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 13:03:37.984  5772  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:03:37.985  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:37.986  5772  5772 D ObexServerSockets: Succeed to create listening sockets 
,11-25 13:03:37.986  5772  5772 D ObexServerSockets0: startAccept()
11-25 13:03:37.986  5772  5772 D ObexServerSockets0: prepareForNewConnect()
11-25 13:03:37.986  5661  5661 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-25 13:03:37.988  5772  5772 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-25 13:03:37.988  5772  5772 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 13:03:37.988  5772  5810 D ObexServerSockets0: Accepting socket connection...
11-25 13:03:37.988  5772  5772 D BluetoothMapService: onReceive
11-25 13:03:37.988  5772  5772 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:03:37.988  5772  5772 D BluetoothMapService: STATE_ON
,11-25 13:03:37.990  5772  5811 D ObexServerSockets0: Accepting socket connection...
11-25 13:03:37.991  5661  5661 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 13:03:37.991  5772  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:37.992  5772  5812 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 13:03:37.992  5772  5812 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 13:03:37.997  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:03:37.999  5661  5661 D BluetoothA2dp: Proxy object connected
,11-25 13:03:38.002  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:38.005  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:03:38.009  5661  5661 D BluetoothPbap: Proxy object connected
,11-25 13:03:38.010  5661  5661 D PbapServerProfile: Bluetooth service connected
,11-25 13:03:38.016  5772  5772 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 13:03:38.016  5772  5772 D ObexServerSockets0: prepareForNewConnect()
,11-25 13:03:38.017  5772  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:03:38.018  3135  3135 D BluetoothPbap: Proxy object connected
11-25 13:03:38.018  3135  3135 D PbapServerProfile: Bluetooth service connected
,11-25 13:03:38.033  5772  5820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:38.034  5772  5820 I BtOppRfcommListener: Accept thread started.
,11-25 13:03:38.068  3135  3147 D BluetoothHeadset: Proxy object connected
,11-25 13:03:38.068  3135  3135 D HeadsetProfile: Bluetooth service connected
11-25 13:03:38.068   930   930 D BluetoothHeadset: Proxy object connected
11-25 13:03:38.068  3783  3976 D BluetoothHeadset: Proxy object connected
11-25 13:03:38.068   930   930 D BluetoothHeadset: Proxy object connected
11-25 13:03:38.068   930   930 D BluetoothHeadset: Proxy object connected
,11-25 13:03:38.076  3783  3810 D BluetoothHeadset: Proxy object connected
,11-25 13:03:38.076  3135  3974 D BluetoothHeadset: Proxy object connected
11-25 13:03:38.076  3135  3135 D HeadsetProfile: Bluetooth service connected
,11-25 13:03:38.080   930   947 D BluetoothHeadset: Proxy object connected
,11-25 13:03:38.082   930   947 D BluetoothHeadset: Proxy object connected
,11-25 13:03:38.093  5661  5675 D BluetoothHeadset: Proxy object connected
,11-25 13:03:38.094  5661  5661 D HeadsetProfile: Bluetooth service connected
,11-25 13:03:38.649  3661  3862 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-25 13:03:38.649  3661  3862 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-25 13:03:38.678  3579  3579 I ConfigService: onCreate
,11-25 13:03:39.720   930  2980 D ConnectivityService: handlePromptUnvalidated 101
,11-25 13:03:41.858   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:41.922  5772  5784 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 13:03:41.923  5772  5784 D BluetoothAdapterProperties: Setting state to 13
11-25 13:03:41.923  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 13:03:41.924  5772  5784 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 13:03:41.925  5772  5784 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:03:41.930  5772  5772 D BluetoothMapService: onReceive
11-25 13:03:41.930  5772  5772 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:03:41.930  5772  5772 D BluetoothMapService: STATE_TURNING_OFF
,11-25 13:03:41.931  5772  5772 D BluetoothMapService: MAP Service closeService in
11-25 13:03:41.931  5772  5772 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 13:03:41.931  5772  5772 D ObexServerSockets0: shutdown(block = true)
11-25 13:03:41.932  5772  5772 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 13:03:41.932  5772  5772 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 13:03:41.933  5772  5810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 13:03:41.933  5772  5788 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:03:41.933  5772  5811 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 13:03:41.934  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 13:03:41.936  5772  5797 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 13:03:41.936  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:41.936  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:03:41.938  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:03:41.938  5772  5772 I BtOppRfcommListener: stopping Accept Thread
11-25 13:03:41.939  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:03:41.939  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:03:41.939  5772  5820 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 13:03:41.941  5772  5820 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 13:03:41.943  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:41.944  5772  5772 D HeadsetService: Received stop request...Stopping profile...
11-25 13:03:41.947  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:03:41.949  3135  3974 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:41.950  3135  3135 D HeadsetProfile: Bluetooth service disconnected
11-25 13:03:41.951  5661  5673 D BluetoothHeadset: Proxy object disconnected
,11-25 13:03:41.953   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:41.953  3783  3799 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:41.954   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:41.954   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 13:03:41.956  5772  5772 D A2dpService: Received stop request...Stopping profile...
11-25 13:03:41.957  5661  5661 D HeadsetProfile: Bluetooth service disconnected
11-25 13:03:41.957  5772  5803 D A2dpStateMachine: Exit Disconnected: -1
,11-25 13:03:41.958   930   930 D BluetoothA2dp: Proxy object disconnected
11-25 13:03:41.958  5661  5661 D BluetoothA2dp: Proxy object disconnected
11-25 13:03:41.959  5772  5772 D HidService: Received stop request...Stopping profile...
11-25 13:03:41.959  5772  5772 D HidService: Stopping Bluetooth HidService
11-25 13:03:41.961  5772  5772 D HealthService: Received stop request...Stopping profile...
11-25 13:03:41.961  5661  5661 D BluetoothInputDevice: Proxy object disconnected
,11-25 13:03:41.961  5661  5661 D HidProfile: Bluetooth service disconnected
,11-25 13:03:41.965  5772  5772 D PanService: Received stop request...Stopping profile...
,11-25 13:03:41.967  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:41.967  5661  5661 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:03:41.967  5772  5772 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:41.967  5661  5661 D PanProfile: Bluetooth service disconnected
,11-25 13:03:41.968  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:41.968  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.968  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:03:41.969  5772  5772 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-25 13:03:41.969  5772  5772 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 13:03:41.969  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 13:03:41.970  5772  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 13:03:41.970  5772  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:41.970  5772  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:41.970  5772  5788 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 13:03:41.970  5772  5772 D BluetoothMapService: Received stop request...Stopping profile...
11-25 13:03:41.970  5772  5772 D BluetoothMapService: stop()
,11-25 13:03:41.971  5772  5772 D BluetoothMapAppObserver: deinitObservers()
,11-25 13:03:41.971  5772  5772 D BluetoothMapAppObserver: removeReceiver()
11-25 13:03:41.973  5772  5772 D SapService: Received stop request...Stopping profile...
,11-25 13:03:41.973  5772  5772 V SapService: stop()
11-25 13:03:41.974  3135  3135 D BluetoothA2dp: Proxy object disconnected,
11-25 13:03:41.974  3135  3135 D BluetoothInputDevice: Proxy object disconnected
11-25 13:03:41.974  3135  3135 D HidProfile: Bluetooth service disconnected
11-25 13:03:41.974  3135  3135 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:03:41.975  3135  3135 D PanProfile: Bluetooth service disconnected
11-25 13:03:41.975  3135  3135 D BluetoothMap: Proxy object disconnected
11-25 13:03:41.975  3135  3135 D MapProfile: Bluetooth service disconnected
11-25 13:03:41.976  5772  5772 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:41.976  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:41.976  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.976  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:41.978  5772  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:41.978  5772  5772 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:41.978  5772  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:41.978  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:41.978  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.978  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:41.978  5772  5772 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 13:03:41.978  5772  5772 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 13:03:41.978  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:03:41.978  5772  5795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:03:41.979  5772  5795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 13:03:41.979  5772  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:03:41.979  5772  5795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:03:41.979  5772  5795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 13:03:41.979  5661  5661 D BluetoothMap: Proxy object disconnected
,11-25 13:03:41.979  5661  5661 D MapProfile: Bluetooth service disconnected
,11-25 13:03:41.981  5772  5772 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:03:41.981  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:41.981  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.982  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:41.982  5772  5772 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 13:03:41.982  5772  5788 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 13:03:41.982  5772  5772 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 13:03:41.984  3135  3135 D BluetoothPbap: Proxy object disconnected
11-25 13:03:41.984  3135  3135 D PbapServerProfile: Bluetooth service disconnected
11-25 13:03:41.984  5661  5661 D BluetoothPbap: Proxy object disconnected
11-25 13:03:41.984  5661  5661 D PbapServerProfile: Bluetooth service disconnected
11-25 13:03:41.984  5772  5772 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:41.984  5772  5772 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:03:41.984  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.984  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:41.984  5772  5772 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 13:03:41.984  5772  5772 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 13:03:41.986  5772  5772 D BluetoothMapService: MAP Service closeService in
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:41.986  5772  5772 D BluetoothMapService: cleanup()
11-25 13:03:41.986  5772  5772 D BluetoothMapService: MAP Service closeService in
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isTurningOff()=true
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:41.986  5772  5772 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:41.987  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 13:03:41.987  5772  5784 D BluetoothAdapterProperties: Setting state to 15
11-25 13:03:41.987  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 13:03:41.987  5772  5784 I BluetoothAdapterState: Entering BleOnState
11-25 13:03:41.987   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:41.988  3135  3147 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:03:41.988  3135  3146 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:03:41.989  3135  3974 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:03:41.990  3783  3976 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:03:41.992  5661  5675 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:03:41.993   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 13:03:41.993  3135  3147 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:41.993  3135  3146 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:03:41.994  5661  5673 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:03:41.994  5661  5675 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:03:41.995  5661  5673 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:41.995  3135  3974 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:03:41.996   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:03:41.996  5661  5675 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:03:41.998  5661  5673 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:03:41.999   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:03:41.999  5772  5784 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 13:03:41.999  5772  5784 D BluetoothAdapterProperties: Setting state to 16
11-25 13:03:41.999  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 13:03:42.001  5772  5784 D BluetoothAdapterProperties: onBleDisable
11-25 13:03:42.001  5772  5784 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:03:42.001  5772  5785 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 13:03:42.002  5772  5788 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:03:42.003  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:03:42.003  5772  5795 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 13:03:42.004  5772  5795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:03:42.004  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:03:42.006  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:42.011  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:42.017  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:03:42.214  5772  5788 I bt_hci  : shut_down
,11-25 13:03:42.219  5772  5792 D bt_hwcfg: hw_epilog_process
,11-25 13:03:42.219  5772  5792 I bt_vendor: low_power_mode_cb
,11-25 13:03:42.221  5772  5792 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 13:03:42.221  5772  5792 I bt_vendor: epilog_cb
11-25 13:03:42.221  5772  5792 I bt_hci  : epilog_finished_callback
,11-25 13:03:42.223  5772  5788 I bt_hci_h4: hal_close
,11-25 13:03:42.224  5772  5788 I bt_userial_vendor: device fd = 54 close
,11-25 13:03:42.331  5772  5785 D bt_stack_manager: event_shut_down_stack finished.
,11-25 13:03:42.331  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 13:03:42.334  5772  5784 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 13:03:42.334  5772  5772 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 13:03:42.335  5772  5772 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 13:03:42.335  5772  5772 D BtGatt.GattService: stop()
11-25 13:03:42.335  5772  5772 D BtGatt.AdvertiseManager: advertise clients cleared
,11-25 13:03:42.338  5772  5772 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:03:42.338  5772  5772 V BluetoothAdapterState: isTurningOn()=false
11-25 13:03:42.338  5772  5772 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:42.338  5772  5772 V BluetoothAdapterState: isBleTurningOff()=true
11-25 13:03:42.338  5772  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 13:03:42.338  5772  5784 D BluetoothAdapterProperties: Setting state to 10
11-25 13:03:42.338  5772  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 13:03:42.339  5772  5784 I BluetoothAdapterState: Entering OffState
11-25 13:03:42.340   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 13:03:42.348  5772  5772 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 13:03:42.348  5772  5772 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 13:03:42.349  5772  5772 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-25 13:03:42.350  5772  5785 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 13:03:42.356  5772  5772 I art     : System.exit called, status: 0
,11-25 13:03:42.356  5772  5772 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 13:03:42.380   930  3425 I ActivityManager: Process com.android.bluetooth (pid 5772) has died
,11-25 13:03:42.859   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:43.708  3579  3579 I ConfigService: onDestroy
,11-25 13:03:43.859   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:44.860   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:45.861   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:03:46.862   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 13:03:46.921  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:46.922  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 13:03:46.928  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:46.929  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15df18e removed from the list
11-25 13:03:46.929  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:46.932  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:03:46.932  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2a3945 added. We now have 4 listener(s)
11-25 13:03:46.933  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:03:46.934  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:46.935  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2a3945 removed from the list
11-25 13:03:46.935  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:03:46.937  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:03:46.937  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5cb989a added. We now have 4 listener(s)
11-25 13:03:46.937  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:03:51.948  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:03:51.981   930   947 I ActivityManager: Start proc 5831:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 13:03:52.067  5831  5831 D AdapterServiceConfig: Adding HeadsetService
,11-25 13:03:52.067  5831  5831 D AdapterServiceConfig: Adding A2dpService
11-25 13:03:52.067  5831  5831 D AdapterServiceConfig: Adding HidService
11-25 13:03:52.067  5831  5831 D AdapterServiceConfig: Adding HealthService
11-25 13:03:52.068  5831  5831 D AdapterServiceConfig: Adding PanService
11-25 13:03:52.068  5831  5831 D AdapterServiceConfig: Adding GattService
11-25 13:03:52.068  5831  5831 D AdapterServiceConfig: Adding BluetoothMapService
11-25 13:03:52.068  5831  5831 D AdapterServiceConfig: Adding SapService
,11-25 13:03:52.079   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f0cc61f:true
,11-25 13:03:52.079  5831  5831 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 13:03:52.082  5831  5831 I bt_bluedroid: init
11-25 13:03:52.082  5831  5843 I BluetoothAdapterState: Entering OffState
,11-25 13:03:52.085  5831  5844 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 13:03:52.085  5831  5844 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 13:03:52.085  5831  5844 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 13:03:52.085  5831  5844 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 13:03:52.086  5831  5831 I bt_bluedroid: get_profile_interface socket
,11-25 13:03:52.089  5831  5831 I bt_bluedroid: get_profile_interface sdp
11-25 13:03:52.089  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 13:03:52.090  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:03:52.094  5831  5842 I bt_bluedroid: config_hci_snoop_log
11-25 13:03:52.095   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 13:03:52.099  5831  5843 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 13:03:52.099  5831  5843 D BluetoothAdapterProperties: Setting state to 14
11-25 13:03:52.099  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 13:03:52.101  5831  5843 D BluetoothBondStateMachine: make
,11-25 13:03:52.104  5831  5848 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 13:03:52.106  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:03:52.107  5831  5831 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 13:03:52.109  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:52.110  5831  5831 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:03:52.111  5831  5831 D BtGatt.GattService: Received start request. Starting profile...
11-25 13:03:52.111  5831  5831 D BtGatt.GattService: start()
11-25 13:03:52.111  5831  5831 I bt_bluedroid: get_profile_interface gatt
,11-25 13:03:52.112  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:52.112  5831  5831 D BtGatt.AdvertiseManager: advertise manager created
11-25 13:03:52.117  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:52.118  5831  5831 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:03:52.118  5831  5831 V BluetoothAdapterState: isBleTurningOn()=true
11-25 13:03:52.118  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:52.118  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 13:03:52.119  5831  5843 I bt_bluedroid: bt_bluedroid
,11-25 13:03:52.120  5831  5844 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 13:03:52.120  5831  5844 I bt_hci  : start_up
,11-25 13:03:52.127  5831  5844 I bt_vendor: alloc value 0xf426b871
11-25 13:03:52.127  5831  5844 I bt_vendor: init
,11-25 13:03:52.127  5831  5844 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 13:03:52.127  5831  5844 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 13:03:52.237  5831  5844 D bt_hci  : start_up starting async portion
11-25 13:03:52.238  5831  5851 I bt_hci  : event_finish_startup
,11-25 13:03:52.238  5831  5851 I bt_hci_h4: hal_open
11-25 13:03:52.238  5831  5851 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 13:03:52.237  5852  5852 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:03:52.241  5831  5851 I bt_userial_vendor: device fd = 54 open
,11-25 13:03:52.258  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:03:52.262  5831  5851 D bt_hwcfg: Chipset BCM4358A3
11-25 13:03:52.262  5831  5851 D bt_hwcfg: Target name = [BCM4358A3]
,11-25 13:03:52.262  5831  5851 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 13:03:52.768  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 13:03:52.769  5831  5851 D bt_hwcfg: Settlement delay -- 100 ms
11-25 13:03:52.769  5831  5851 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 13:03:52.905  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:03:52.905  5831  5851 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-25 13:03:52.907  5831  5851 I bt_hwcfg: vendor lib fwcfg completed
,11-25 13:03:52.907  5831  5851 I bt_vendor: firmware callback
,11-25 13:03:52.907  5831  5851 I bt_hci  : firmware_config_callback
,11-25 13:03:52.917  5831  5854 I bt_btu  : btu_task pending for preload complete event
,11-25 13:03:52.917  5831  5854 I bt_btu_task: Bluetooth chip preload is complete
11-25 13:03:52.917  5831  5854 I bt_btu  : btu_task received preload complete event
,11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-25 13:03:52.925  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_SDP
,11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 13:03:52.926  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 13:03:53.021  5831  5854 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41e9549
,11-25 13:03:53.022  5831  5854 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41e9549 
,11-25 13:03:53.053  5831  5847 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 13:03:53.055  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:03:53.056  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:03:53.058  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:03:53.061  5831  5847 D BluetoothAdapterProperties: Scan Mode:20
,11-25 13:03:53.061  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:03:53.061  5831  5847 D bt_hci  : do_postload posting postload work item
11-25 13:03:53.061  5831  5851 I bt_hci  : event_postload
11-25 13:03:53.062  5831  5851 I bt_vendor: sco_config_cb
,11-25 13:03:53.062  5831  5851 I bt_hci  : sco_config_callback postload finished.
11-25 13:03:53.063  5831  5847 D bt_bte_conf: Device ID record 1 : primary
11-25 13:03:53.063  5831  5847 D bt_bte_conf:   vendorId            = 000f
,11-25 13:03:53.063  5831  5847 D bt_bte_conf:   vendorIdSource      = 0001
11-25 13:03:53.063  5831  5847 D bt_bte_conf:   product             = 1200
11-25 13:03:53.063  5831  5847 D bt_bte_conf:   version             = 1436
11-25 13:03:53.064  5831  5847 D bt_bte_conf:   clientExecutableURL = 
11-25 13:03:53.064  5831  5847 D bt_bte_conf:   serviceDescription  = 
11-25 13:03:53.064  5831  5847 D bt_bte_conf:   documentationURL    = 
,11-25 13:03:53.064  5831  5847 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 13:03:53.064  5831  5844 D bt_stack_manager: event_start_up_stack finished
11-25 13:03:53.065  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 13:03:53.065  5831  5843 D BluetoothAdapterProperties: Setting state to 15
,11-25 13:03:53.065  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 13:03:53.066  5831  5843 I BluetoothAdapterState: Entering BleOnState
,11-25 13:03:53.071  5831  5851 I bt_vendor: low_power_mode_cb
,11-25 13:03:53.073  5831  5843 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 13:03:53.073  5831  5843 D BluetoothAdapterProperties: Setting state to 11
11-25 13:03:53.073  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 13:03:53.087  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:53.088  5831  5831 D HeadsetService: Received start request. Starting profile...
,11-25 13:03:53.090  5831  5831 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 13:03:53.091  5831  5831 D HeadsetStateMachine: make
,11-25 13:03:53.096  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:03:53.101  5831  5831 D HeadsetStateMachine: max_hf_connections = 1
,11-25 13:03:53.101  5831  5831 I bt_bluedroid: get_profile_interface handsfree
11-25 13:03:53.102  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 13:03:53.103  5831  5847 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 13:03:53.105  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:53.106  5831  5831 D A2dpService: Received start request. Starting profile...
11-25 13:03:53.107  5831  5831 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 13:03:53.107  5831  5831 I bt_bluedroid: get_profile_interface avrcp
,11-25 13:03:53.115  5831  5831 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 13:03:53.115  5831  5831 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 13:03:53.116  5831  5831 D A2dpStateMachine: make
11-25 13:03:53.118  5831  5831 I bt_bluedroid: get_profile_interface a2dp
,11-25 13:03:53.119  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 13:03:53.120  5831  5862 D A2dpStateMachine: Enter Disconnected: -2
11-25 13:03:53.121  5831  5831 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 13:03:53.122  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:53.122  5831  5831 D HidService: Received start request. Starting profile...
,11-25 13:03:53.123  5831  5831 I bt_bluedroid: get_profile_interface hidhost
11-25 13:03:53.123  5831  5831 D HidService: setHidService(): set to: null
11-25 13:03:53.123  5831  5847 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41ca56d
11-25 13:03:53.123  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 13:03:53.124  5831  5831 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-25 13:03:53.125  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:53.126  5831  5831 D HealthService: Received start request. Starting profile...
,11-25 13:03:53.126  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:53.127  5831  5831 I bt_bluedroid: get_profile_interface health
11-25 13:03:53.128  5831  5831 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 13:03:53.129  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:03:53.129  5831  5831 D PanService: Received start request. Starting profile...
11-25 13:03:53.129  5831  5831 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 13:03:53.129  5831  5831 I bt_bluedroid: get_profile_interface pan
11-25 13:03:53.130  5831  5847 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 13:03:53.131  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:53.132  5831  5831 D BluetoothMapService: Received start request. Starting profile...
11-25 13:03:53.132  5831  5831 D BluetoothMapService: start()
,11-25 13:03:53.134  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 13:03:53.135  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 13:03:53.135  5831  5831 D BluetoothMapAppObserver: createReceiver()
,11-25 13:03:53.136  5831  5831 D BluetoothMapAppObserver: initObservers()
,11-25 13:03:53.136  5831  5831 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 13:03:53.142  5831  5831 V SapService: SapBinder()
,11-25 13:03:53.142  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
,11-25 13:03:53.142  5831  5831 D SapService: Received start request. Starting profile...
11-25 13:03:53.142  5831  5831 V SapService: start()
,11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:53.145  5831  5860 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:03:53.145  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:53.146  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:53.147  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:53.147  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.147  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:53.147  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:03:53.147  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:53.147  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.148  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:53.148  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:03:53.148  5831  5831 V BluetoothAdapterState: isTurningOff()=false
11-25 13:03:53.148  5831  5831 V BluetoothAdapterState: isTurningOn()=true
11-25 13:03:53.149  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:03:53.149  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:03:53.149  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-25 13:03:53.149  5831  5843 D BluetoothAdapterProperties: ScanMode =  20
11-25 13:03:53.149  5831  5843 D BluetoothAdapterProperties: State =  11
11-25 13:03:53.149  5831  5843 D BluetoothAdapterProperties: Setting state to 12
11-25 13:03:53.149  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 13:03:53.150   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:53.150  5831  5843 I BluetoothAdapterState: Entering OnState
11-25 13:03:53.150  3135  3974 D BluetoothPan: onBluetoothStateChange on: true
,11-25 13:03:53.152  3135  3146 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:03:53.152  5831  5847 D BluetoothAdapterProperties: Scan Mode:21
11-25 13:03:53.152  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:03:53.153  3135  3135 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:03:53.153  3135  3135 D PanProfile: Bluetooth service connected
11-25 13:03:53.154  3135  3974 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:03:53.155  3135  3135 D BluetoothA2dp: Proxy object connected
,11-25 13:03:53.158  3783  3810 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 13:03:53.159  5661  5675 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 13:03:53.161  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:03:53.162  5831  5831 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 13:03:53.163  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:53.165   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 13:03:53.165   930   930 D BluetoothA2dp: Proxy object connected
,11-25 13:03:53.165  3135  3147 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:53.166  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:03:53.166  3135  3974 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:03:53.167  5831  5831 D ObexServerSockets: Succeed to create listening sockets 
11-25 13:03:53.167  5831  5831 D ObexServerSockets0: startAccept()
11-25 13:03:53.167  5831  5831 D ObexServerSockets0: prepareForNewConnect()
11-25 13:03:53.168  5661  5673 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:03:53.169  5831  5831 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 13:03:53.169  5831  5831 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-25 13:03:53.169  5661  5675 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:03:53.170  5831  5867 D ObexServerSockets0: Accepting socket connection...
11-25 13:03:53.170  5831  5868 D ObexServerSockets0: Accepting socket connection...
11-25 13:03:53.171  3135  3135 D BluetoothMap: Proxy object connected
11-25 13:03:53.171  3135  3135 D MapProfile: Bluetooth service connected
11-25 13:03:53.171  3135  3135 D BluetoothMap: getConnectedDevices()
11-25 13:03:53.172  5661  5673 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:53.172  3135  3147 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:03:53.173  5661  5661 D BluetoothMap: Proxy object connected
,11-25 13:03:53.173  5661  5661 D MapProfile: Bluetooth service connected
11-25 13:03:53.173  5661  5661 D BluetoothMap: getConnectedDevices()
11-25 13:03:53.174   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:53.174  5661  5675 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:03:53.175  3135  3135 D BluetoothInputDevice: Proxy object connected
11-25 13:03:53.175  3135  3135 D HidProfile: Bluetooth service connected
,11-25 13:03:53.177  5661  5869 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 13:03:53.179  5661  5661 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:03:53.179  5661  5661 D PanProfile: Bluetooth service connected
11-25 13:03:53.179  5661  5661 D BluetoothInputDevice: Proxy object connected
11-25 13:03:53.179  5661  5661 D HidProfile: Bluetooth service connected
11-25 13:03:53.180   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:03:53.181   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 13:03:53.182  5831  5831 D BluetoothMapService: onReceive
11-25 13:03:53.182  5831  5831 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:03:53.182  5831  5831 D BluetoothMapService: STATE_ON
,11-25 13:03:53.183  5661  5661 D BluetoothA2dp: Proxy object connected
,11-25 13:03:53.186  5831  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:53.188  5831  5870 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 13:03:53.188  5831  5870 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 13:03:53.191  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:03:53.197  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:03:53.200  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:03:53.205  3135  3135 D BluetoothPbap: Proxy object connected
11-25 13:03:53.206  5661  5661 D BluetoothPbap: Proxy object connected
11-25 13:03:53.206  5661  5661 D PbapServerProfile: Bluetooth service connected
,11-25 13:03:53.206  3135  3135 D PbapServerProfile: Bluetooth service connected
,11-25 13:03:53.211  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 13:03:53.211  5831  5831 D ObexServerSockets0: prepareForNewConnect()
,11-25 13:03:53.214  5831  5875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:53.224  5831  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:03:53.225  5831  5879 I BtOppRfcommListener: Accept thread started.
,11-25 13:03:53.252  3135  3147 D BluetoothHeadset: Proxy object connected
11-25 13:03:53.252  3135  3135 D HeadsetProfile: Bluetooth service connected
,11-25 13:03:53.252  5661  5869 D BluetoothHeadset: Proxy object connected
11-25 13:03:53.252   930   930 D BluetoothHeadset: Proxy object connected
11-25 13:03:53.253  3783  3799 D BluetoothHeadset: Proxy object connected
,11-25 13:03:53.253   930   930 D BluetoothHeadset: Proxy object connected
,11-25 13:03:53.253   930   930 D BluetoothHeadset: Proxy object connected
11-25 13:03:53.256  5661  5661 D HeadsetProfile: Bluetooth service connected
,11-25 13:03:53.259  3783  3976 D BluetoothHeadset: Proxy object connected
,11-25 13:03:53.267  3135  3974 D BluetoothHeadset: Proxy object connected
11-25 13:03:53.267  3135  3135 D HeadsetProfile: Bluetooth service connected
,11-25 13:03:53.273  5661  5675 D BluetoothHeadset: Proxy object connected
,11-25 13:03:53.273  5661  5661 D HeadsetProfile: Bluetooth service connected
11-25 13:03:53.274   930   947 D BluetoothHeadset: Proxy object connected
,11-25 13:03:53.281   930   947 D BluetoothHeadset: Proxy object connected
,11-25 13:03:55.904  4109  4484 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:03:56.963  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:03:56.970  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:03:56.972  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:03:56.972  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5cb989a removed from the list
,11-25 13:03:56.973  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:03:56.975  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:03:56.975  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14b15cb added. We now have 4 listener(s)
,11-25 13:03:56.975  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:03:56.978   930  3612 D WifiService: setWifiEnabled: false pid=5593, uid=10077
11-25 13:03:56.979   930  3612 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:04:01.863   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:01.990  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:04:01.991   930  3162 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-25 13:04:01.991   930  3162 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:04:02.000   509   924 D SoftapController: Softap fwReload - Ok
,11-25 13:04:02.006   509   924 D CommandListener: Setting iface cfg
,11-25 13:04:02.007   509   924 D CommandListener: Trying to bring down wlan0
11-25 13:04:02.009   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:04:02.013   930  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 13:04:02.688   930  2975 D wifi    : set interface wlan0 flags (UP)
11-25 13:04:02.694   930  2975 I WifiHAL : Initializing wifi
11-25 13:04:02.694   930  2975 I WifiHAL : Creating socket
11-25 13:04:02.700   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 13:04:02.701   930  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-25 13:04:02.701   930  2975 D wifi    : Did set static halHandle = 0x7f7a6c8400
,11-25 13:04:02.702   930  2975 D wifi    : halHandle = 0x7f7a6c8400, mVM = 0x7f96d0d140, mCls = 0x20188a
11-25 13:04:02.702   930  2975 D wifi    : array field set
11-25 13:04:02.702   930  2975 I WifiNative-HAL: interface[0] = wlan0
11-25 13:04:02.705   930  5884 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547514778624
,11-25 13:04:02.706   930  5884 D wifi    : waitForHalEvents called, vm = 0x7f96d0d140, obj = 0x20188a, env = 0x7f8c29e200
,11-25 13:04:02.750  5885  5885 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 13:04:02.808   930  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 13:04:02.815  5885  5885 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:04:02.864   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:02.869  5885  5885 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:04:02.870  5885  5885 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 13:04:02.889   930  2975 D WifiConfigStore: Loading config and enabling all networks 
,11-25 13:04:02.913   930  2975 D WifiConfigStore: loaded 0 passpoint configs
,11-25 13:04:02.914   930  2975 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 13:04:02.914   930  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 13:04:02.914   930  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 13:04:02.915   930  2975 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 13:04:02.915   930  2975 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-25 13:04:02.916   930  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 13:04:02.916   930  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-25 13:04:02.916   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 13:04:02.916   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 13:04:02.916   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 13:04:02.916   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 13:04:02.916   930  2975 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 13:04:02.919   930  2975 D WifiNative-HAL: Setting external_sim to 1
,11-25 13:04:02.919   930  2975 D wifi    : setting dfs flag to true, 0x7f77eb5600
11-25 13:04:02.919   930  2975 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 13:04:02.919   930  2975 D wifi    : setting scan oui 0x7f77eb5600
11-25 13:04:02.919  5011  5011 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:04:02.919   930  2975 D WifiHAL : Sending mac address OUI
,11-25 13:04:02.922   930  2975 E native  : do suspend false
,11-25 13:04:02.937   930  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 13:04:02.938   930   930 D RttService: SCAN_AVAILABLE : 3
11-25 13:04:02.938   930  3087 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 13:04:02.943   509   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 13:04:02.944   509   924 D CommandListener: Setting iface cfg
,11-25 13:04:02.945   930  2960 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-25 13:04:02.945   930  2960 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 13:04:02.954   930  2960 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 13:04:02.959   930  2960 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 13:04:02.959   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164622 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-25 13:04:03.865   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:04.866   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:05.867   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:06.010  5885  5885 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:04:06.023  5885  5885 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:04:06.052   930  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 13:04:06.053   930  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 13:04:06.053   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:04:06.065   930  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 13:04:06.099   930  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 13:04:06.103  5885  5885 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 13:04:06.524  5885  5885 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 13:04:06.560  5885  5885 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 13:04:06.562  5885  5885 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 13:04:06.571   930  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:04:06.571   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:04:06.571   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 13:04:06.588   930  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:04:06.601   509   924 D CommandListener: Setting iface cfg
,11-25 13:04:06.607   930  2975 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 13:04:06.613   930  5890 D DhcpClient: Receive thread started
,11-25 13:04:06.617   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 13:04:06.617   930  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-25 13:04:06.617   930  2980 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 13:04:06.698   930  2975 E native  : do suspend false
,11-25 13:04:06.709   930  5889 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 13:04:06.722   930  5890 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-25 13:04:06.723   930  5889 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-25 13:04:06.725   930  5889 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 13:04:06.740   930  5890 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 13:04:06.741   930  5889 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 13:04:06.745   509   924 D CommandListener: Setting iface cfg
,11-25 13:04:06.750   930  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 13:04:06.754   930  5889 D DhcpClient: Scheduling renewal in 86399s
,11-25 13:04:06.762   930  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 13:04:06.763   930  2975 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 13:04:06.764   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 13:04:06.769   930  2980 D ConnectivityService: Adding iface wlan0 to network 102
,11-25 13:04:06.778   930  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 13:04:06.813   930  2980 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 13:04:06.814   930  2980 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-25 13:04:06.815   930  2980 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-25 13:04:06.817   930  2980 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 13:04:06.818   930  2980 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-25 13:04:06.829   930  2980 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:04:06.834   930  2980 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-25 13:04:06.834   930  2980 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-25 13:04:06.834   930  2980 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-25 13:04:06.834   930  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 13:04:06.834   930  2980 D ConnectivityService:    accepting network in place of null
,11-25 13:04:06.835   930  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:04:06.835   930  2980 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:04:06.856   930  5888 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168519, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:04:06.866   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:04:06.868   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:04:06.890   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:04:06.894   930  2980 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-25 13:04:06.894  3739  3878 W QCNEJ   : |CORE| network available: 102
,11-25 13:04:06.894   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:04:06.895   930  2980 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-25 13:04:06.897   930   947 D Tethering: MasterInitialState.processMessage what=3
11-25 13:04:06.901  3739  3878 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 13:04:06.902  3739  3878 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 13:04:06.903  3739  3878 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 13:04:06.919  3960  3960 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-25 13:04:06.921  5036  5060 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 13:04:06.921  5036  5060 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:04:06.921  5036  5060 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 13:04:06.922  5036  5060 E SarControlService: no key has been found,reset the power
11-25 13:04:06.922  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:04:06.922  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:04:06.922  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:04:06.922  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:04:06.922  5061  5061 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 13:04:06.923  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:04:06.924  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:04:06.924  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:04:06.924  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:04:06.924  5061  5061 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:04:06.926  3977  3977 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:04:06.928  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000f003000000000000ffffffff]
,11-25 13:04:06.928  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:04:06.928  5061  5075 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-25 13:04:06.928  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:04:06.931   930  5887 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 13:04:06.929  5036  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-25 13:04:06.940  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bf089ea HexData = [00000000f103000000000000ffffffff]
,11-25 13:04:06.940  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:04:06.940  5061  5075 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-25 13:04:06.942  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:04:06.942  5036  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 13:04:06.947  3977  3977 D SystemUpdateService: onCreate
11-25 13:04:06.949  3977  3977 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:04:06.965  3977  3977 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 13:04:06.967  3977  5388 I iu.UploadsManager: num queued entries: 0
,11-25 13:04:06.967  3977  5388 I iu.UploadsManager: num updated entries: 0
11-25 13:04:06.967  3977  5388 I iu.SyncManager: NEXT; no task
,11-25 13:04:06.977  3977  3977 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:04:06.980   930  5887 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:04:06 GMT], X-Android-Received-Millis=[1480075446979], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480075446956]}
11-25 13:04:06.980   930  2980 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 13:04:06.980   930  2980 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-25 13:04:06.980  3977  3977 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:04:06.980   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:04:06.981   930  2980 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 13:04:06.982  5696  5696 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:04:06.990  5696  5696 D SprintDMHelper: simOperator: 
11-25 13:04:06.990  5696  5696 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:04:06.991  3977  5901 I SystemUpdateService: active receiver: enabled
,11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:04:07.004  5593  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:04:07.006  5593  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:04:07.007  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.007  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14b15cb removed from the list
11-25 13:04:07.007  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:04:07.012  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-25 13:04:07.012  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-25 13:04:07.014  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6310a8e Bundle[{}]
,11-25 13:04:07.014  5593  5641 I io.jxcore.node.LifeCycleMonitor: start: OK
11-25 13:04:07.014  5593  5641 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-25 13:04:07.015  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-25 13:04:07.015  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-25 13:04:07.016  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-25 13:04:07.016  5593  5641 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-25 13:04:07.021  5593  5641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-25 13:04:07.022  5593  5641 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 13:04:07.022  5593  5641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-25 13:04:07.023  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.023  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e51a8 added. We now have 3 listener(s)
11-25 13:04:07.023  3977  5901 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:04:07.024  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:04:07.024  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:04:07.024  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.024  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.024  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73a24c1 added. We now have 4 listener(s)
11-25 13:04:07.024  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:04:07.025  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:04:07.026  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.026  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93aa466 added. We now have 4 listener(s)
11-25 13:04:07.027  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.027  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.027  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.027  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:04:07.027  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f343a7 added. We now have 5 listener(s)
11-25 13:04:07.027  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.027  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:04:07.028  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.028  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:04:07.028  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.028  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.028  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-25 13:04:07.028  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e51a8 removed from the list
11-25 13:04:07.028  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.028  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73a24c1 removed from the list
11-25 13:04:07.028  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:04:07.028  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.028  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.029  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.029  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.029  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.029  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.029  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.029  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.029  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73a24c1 not in the list
11-25 13:04:07.029  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.029  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.031  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.031  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.031  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.031  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.031  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.031  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.031  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f343a7 removed from the list
11-25 13:04:07.031  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.031  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.031  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-25 13:04:07.031  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93aa466 removed from the list
11-25 13:04:07.032  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.032  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85ae054 added. We now have 3 listener(s)
11-25 13:04:07.033  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.033  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.033  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.033  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.033  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4034bfd added. We now have 4 listener(s)
11-25 13:04:07.033  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.034  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:04:07.035  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 13:04:07.035  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93ca0f2 added. We now have 4 listener(s)
11-25 13:04:07.036  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:04:07.036  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.036  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.036  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.036  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5067343 added. We now have 5 listener(s)
11-25 13:04:07.036  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.036  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 13:04:07.036  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:04:07.036  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:04:07.036  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:04:07.037  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:04:07.037  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:04:07.044  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 13:04:07.044  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 13:04:07.044  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 13:04:07.044  3579  5911 I VacuumService: Vacuum at: now=1480075447044 tag=VacuumService
,11-25 13:04:07.047  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.047  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:04:07.048  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:04:07.048  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:04:07.048  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:04:07.051  3977  5901 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 13:04:07.051  3977  5901 I SystemUpdateService: now status is 0 (complete)
11-25 13:04:07.052  3977  5901 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:04:07.052  3977  5901 I SystemUpdateService: file has been verified
11-25 13:04:07.052  3977  5901 I SystemUpdateService: OTA package size = 21989297
,11-25 13:04:07.054  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.054  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:04:07.054  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:04:07.054  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-25 13:04:07.054  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:04:07.054  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.055  5593  5641 D BluetoothAdapter: STATE_ON
,11-25 13:04:07.058  5831  5859 D BtGatt.GattService: registerClient() - UUID=0dbead2b-d132-4fbb-b6ab-7f486a7a8990
,11-25 13:04:07.059  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=0dbead2b-d132-4fbb-b6ab-7f486a7a8990, clientIf=5
,11-25 13:04:07.059  5593  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:04:07.060  5831  5871 D BtGatt.GattService: start scan with filters
11-25 13:04:07.062  3977  5901 I SystemUpdateService: showing system update notification
,11-25 13:04:07.064  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 13:04:07.065  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.065  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:04:07.065  5831  5850 D BtGatt.ScanManager: handling starting scan
,11-25 13:04:07.065  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.065  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-25 13:04:07.066  5831  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a6453
11-25 13:04:07.066  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 13:04:07.066  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:04:07.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:04:07.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.067  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.067  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:04:07.067  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.070  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.070  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:04:07.070  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.070  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.070  5593  5641 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 13:04:07.070  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.070  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.070  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:04:07.070  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.070  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:04:07.071  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:04:07.071  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:04:07.071  3579  5914 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-25 13:04:07.072  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.072  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.072  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.072  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:04:07.072  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.073  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:04:07.073  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.073  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:04:07.073  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.074  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.074  5831  5871 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:04:07.074  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:04:07.074  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:04:07.075  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.075  5831  5841 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:04:07.075   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-25 13:04:07.076  5831  5859 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 13:04:07.076  3977  3977 D SystemUpdateService: onDestroy
,11-25 13:04:07.076  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:04:07.076  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.076  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:04:07.076  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.076  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.077  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:04:07.077  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:04:07.082  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:04:07.083  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:04:07.083  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.084  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.084  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:04:07.084  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:04:07.084  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.085  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:04:07.085  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.085  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.085  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 13:04:07.085  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:04:07.085  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:04:07.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:04:07.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:04:07.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.086  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.086  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.086  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:04:07.086  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.086  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.087  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:04:07.087  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.087  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:04:07.087  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.087  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.087  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.087  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.087  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.087  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.087  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85ae054 removed from the list
11-25 13:04:07.087  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.087  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4034bfd removed from the list
11-25 13:04:07.087  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:04:07.088  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.088  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.089  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.089  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.089  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.089  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.089  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.089  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.089  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4034bfd not in the list
11-25 13:04:07.089  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.089  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.090  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.090  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.090  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.090  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.090  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.090  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.090  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5067343 removed from the list
,11-25 13:04:07.090  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.090  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.090  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.091  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93ca0f2 removed from the list
11-25 13:04:07.091  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.091  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec1e5ec added. We now have 3 listener(s)
11-25 13:04:07.092  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.092  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:04:07.092  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.093  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.093  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24fdb5 added. We now have 4 listener(s)
11-25 13:04:07.093  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.093  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:04:07.095  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:04:07.095  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.096  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.096  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0b5c4a added. We now have 4 listener(s)
11-25 13:04:07.097  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:04:07.097  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.097  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.097  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.097  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3107bb added. We now have 5 listener(s)
11-25 13:04:07.097  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:04:07.097  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:04:07.098  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:04:07.098  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:04:07.098  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:04:07.098  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:04:07.098  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:04:07.099  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:04:07.102  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:04:07.102  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:04:07.102  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:04:07.102  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:04:07.103  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.106  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.106  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 13:04:07.107  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:04:07.107  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:04:07.108  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:04:07.108  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:04:07.112  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 13:04:07.112  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.112  5831  5847 E BtGatt.ContextMap: Context not found for ID 5
11-25 13:04:07.113  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.113  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:04:07.113  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:04:07.113  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:04:07.113  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:04:07.113  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.114  5593  5641 D BluetoothAdapter: STATE_ON
,11-25 13:04:07.117  5831  5841 D BtGatt.GattService: registerClient() - UUID=335ab387-2532-40e5-bd18-c8244e2563df
,11-25 13:04:07.117  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=335ab387-2532-40e5-bd18-c8244e2563df, clientIf=5
,11-25 13:04:07.117  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:04:07.118  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:04:07.118  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.118  5831  5842 D BtGatt.GattService: start scan with filters
11-25 13:04:07.118  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:04:07.120  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:04:07.120  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.120  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:04:07.121  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.121  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:04:07.121  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:04:07.121  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.121  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:04:07.121  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:04:07.121  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.121  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.121  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.121  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.122  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:04:07.122  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.123  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:04:07.123  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:04:07.124  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.124  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:04:07.123  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:04:07.124  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.124  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.124  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:04:07.124  5593  5641 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 13:04:07.124  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.124  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:04:07.124  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.124  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:04:07.124  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.125  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.125  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.125  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec1e5ec removed from the list
11-25 13:04:07.125  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.125  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24fdb5 removed from the list
11-25 13:04:07.125  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:04:07.125  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.125  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:04:07.125  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 13:04:07.125  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.127  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.127  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.127  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:04:07.127  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.128  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.128  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.128  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.128  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24fdb5 not in the list
11-25 13:04:07.128  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:04:07.128  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.129  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.129  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.129  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:04:07.129  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:04:07.129  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.129  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.129  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.129  5831  5871 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:04:07.129  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:04:07.130  5831  5850 D BtGatt.ScanManager: handling starting scan
11-25 13:04:07.130  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.131  5831  5871 D BtGatt.GattService: stopScan() - queue size =0
11-25 13:04:07.131  3579  5912 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-25 13:04:07.131  5831  5859 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:04:07.131  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Curr,ent thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.132  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:04:07.132  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:04:07.133  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:04:07.134  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.135  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.135  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:04:07.135  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.135  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.136  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.136  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.136  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.136  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3107bb removed from the list
11-25 13:04:07.136  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:04:07.136  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.136  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.136  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:04:07.136  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.136  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0b5c4a removed from the list
11-25 13:04:07.136  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:04:07.136  5593  5593 D org.t,haliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.136  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:04:07.136  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:04:07.136  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.136  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.136  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.137  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:04:07.137  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.137  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.137  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.137  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c210684 added. We now have 3 listener(s)
11-25 13:04:07.137  3579  5912 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-25 13:04:07.138  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.138  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.138  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.138  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.138  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8242e6d added. We now have 4 listener(s)
11-25 13:04:07.138  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.139  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:04:07.139  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:04:07.139  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.139  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:04:07.139  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.140  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.140  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.144  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:04:07.144  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.144  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:04:07.144  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:04:07.150  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.150  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db2aa2 added. We now have 4 listener(s)
11-25 13:04:07.151  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.151  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.151  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.151  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.151  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99ab333 added. We now have 5 listener(s)
11-25 13:04:07.151  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.151  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:04:07.151  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:04:07.151  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:04:07.151  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:04:07.152  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:04:07.152  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:04:07.152  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.153  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:04:07.156  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:04:07.156  5593  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:04:07.157  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:04:07.157  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:04:07.157  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.158  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:04:07.161  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.161  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:04:07.162  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:04:07.162  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:04:07.162  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:04:07.163  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:04:07.163  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.163  5831  5847 E BtGatt.ContextMap: Context not found for ID 5
11-25 13:04:07.165  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.165  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:04:07.165  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:04:07.165  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:04:07.165  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:04:07.166  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.166  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.168  5831  5842 D BtGatt.GattService: registerClient() - UUID=b36b14e6-c342-46e8-b71b-01507b8c873f
11-25 13:04:07.168  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=b36b14e6-c342-46e8-b71b-01507b8c873f, clientIf=5
11-25 13:04:07.169  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:04:07.169  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:04:07.169  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.169  5831  5871 D BtGatt.GattService: start scan with filters
11-25 13:04:07.169  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:04:07.172  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:04:07.172  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.172  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:04:07.172  3579  5912 W Uploader:  no longer exists, so no auth token.
11-25 13:04:07.172  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.172  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:04:07.172  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:04:07.173  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.173  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:04:07.173  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:04:07.173  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.173  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.173  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.173  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.174  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:04:07.174  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.174  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:04:07.174  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.174  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:04:07.178  3579  5914 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-25 13:04:07.179  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-25 13:04:07.179  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:04:07.179  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.179  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.179  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.181  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:04:07.181  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.182  5011  5906 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-25 13:04:07.182  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:04:07.182  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.182  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:04:07.182  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.182  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.182  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:04:07.182  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.182  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.182  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c210684 removed from the list
11-25 13:04:07.182  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.183  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8242e6d removed from the list
11-25 13:04:07.183  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:04:07.183  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.183  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:04:07.183  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.183  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.183  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:04:07.183  5593  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:04:07.183  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:04:07.183  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.183  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.183  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.183  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.184  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:04:07.184  5831  5850 D BtGatt.ScanManager: handling starting scan
11-25 13:04:07.185  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.186  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.186  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.186  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8242e6d not in the list
11-25 13:04:07.186  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.186  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:04:07.186  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.187  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.187  5831  5859 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:04:07.188  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:04:07.189  5593  5641 D BluetoothAdapter: STATE_ON
11-25 13:04:07.190  5831  5842 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:04:07.190  5831  5841 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:04:07.190  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:04:07.190  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:04:07.190  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.190  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:04:07.191  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.191  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:04:07.191  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:04:07.192  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:04:07.193  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.194  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.194  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:04:07.194  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.194  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.194  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.194  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.194  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.194  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:04:07.194  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99ab333 removed from the list
11-25 13:04:07.194  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:04:07.194  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.194  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:04:07.194  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.194  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.194  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.194  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db2aa2 removed from the list
11-25 13:04:07.194  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:04:07.194  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:04:07.195  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.195  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.195  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.195  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:04:07.195  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.195  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.195  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.195  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e00a21c added. We now have 3 listener(s)
11-25 13:04:07.196  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:04:07.196  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.196  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.196  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.196  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:04:07.196  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:04:07.196  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:04:07.196  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.196  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.196  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.197  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.197  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@551be25 added. We now have 4 listener(s)
11-25 13:04:07.197  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.198  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:04:07.199  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:04:07.200  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b6bfa added. We now have 4 listener(s)
11-25 13:04:07.201  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:04:07.201  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:04:07.201  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:04:07.201  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:04:07.201  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f55ab added. We now have 5 listener(s)
11-25 13:04:07.201  5593  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:04:07.202  5593  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:04:07.202  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.202  5593  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:04:07.202  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.202  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.202  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.202  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e00a21c removed from the list
11-25 13:04:07.202  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.202  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@551be25 removed from the list
11-25 13:04:07.202  5593  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:04:07.202  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.202  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.203  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.203  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.203  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.203  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.203  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.203  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.203  5593  5641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@551be25 not in the list
11-25 13:04:07.203  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.203  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.205  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.205  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:04:07.205  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.205  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.205  5593  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-25 13:04:07.205  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:04:07.205  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:04:07.205  5593  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:04:07.205  5593  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f55ab removed from the list
11-25 13:04:07.205  5593  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:04:07.205  5593  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:04:07.205  5593  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:04:07.205  5593  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b6bfa removed from the list
11-25 13:04:07.206  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 13:04:07.206  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 13:04:07.206  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 13:04:07.207  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:04:07.207  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 13:04:07.207  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:07.210  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:04:07.210  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.212  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:04:07.215  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:04:07.215  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.215  5831  5847 E BtGatt.ContextMap: Context not found for ID 5
11-25 13:04:07.220  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:04:07.221  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.221  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:04:07.225  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:04:07.225  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:04:07.225  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:04:07.229  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:04:07.229  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:04:07.498  3579  5916 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 13:04:07.586  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:04:07.637  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:04:07.684  3579  5912 W Uploader:  no longer exists, so no auth token.
,11-25 13:04:07.690  3579  5914 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 13:04:07.695  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:04:07.775  3579  5916 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 13:04:07.862  3579  5914 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 13:04:07.944  3579  5916 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 13:04:08.462  3579  3579 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-25 13:04:08.465  3579  5917 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-25 13:04:09.368  5593  5922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:04:09.368  5593  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:09.630   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:04:10.180  5593  5922 W !!      : call onHalfStreamCopied
,11-25 13:04:10.180  5593  5922 I testCopyDataAndClose: closing input stream
,11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:04:10.948  5593  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 13:04:14.840   930  2980 D ConnectivityService: handlePromptUnvalidated 102
,11-25 13:04:15.503  5593  5923 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:15.503  5593  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:17.502  5593  5641 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-25 13:04:17.502  5593  5641 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:17.503  5593  5641 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-25 13:04:17.632  5593  5923 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 13:04:17.633  5593  5923 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:17.633  5593  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-25 13:04:17.641  5593  5924 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:04:17.641  5593  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:17.961   930  2975 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-25 13:04:18.702   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:04:19.243  5593  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 13:04:21.727   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:04:23.615  5593  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:23.615  5593  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:04:23.615  5593  5925 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:23.615  5593  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:04:23.615  5593  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:04:23.615  5593  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:23.616  5593  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-25 13:04:23.618  5593  5641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-25 13:04:23.621  5593  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:23.621  5593  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:04:23.622  5593  5926 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-25 13:04:23.623  5593  5926 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:23.623  5593  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-25 13:04:23.624  5593  5926 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-25 13:04:23.624  5593  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:04:23.624  5593  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 13:04:23.629  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 13:04:23.629  5593  5641 I jxcore-log: 
11-25 13:04:23.630  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 13:04:23.630  5593  5641 I jxcore-log: 
,11-25 13:04:23.630  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 13:04:23.630  5593  5641 I jxcore-log: 
11-25 13:04:23.630  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 13:04:23.630  5593  5641 I jxcore-log: 
,11-25 13:04:23.631  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'Total duration:  92161'
11-25 13:04:23.631  5593  5641 I jxcore-log: 
11-25 13:04:23.633  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 13:04:23.633  5593  5641 I jxcore-log: 
,11-25 13:04:23.636  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.636  5593  5641 I jxcore-log: 
,11-25 13:04:23.637  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.637  5593  5641 I jxcore-log: 
11-25 13:04:23.637  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 13:04:23.637  5593  5641 I jxcore-log: 
,11-25 13:04:23.638  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 13:04:23.638  5593  5641 I jxcore-log: 
11-25 13:04:23.638  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.638  5593  5641 I jxcore-log: 
11-25 13:04:23.638  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:04:23.638  5593  5641 I jxcore-log: 
11-25 13:04:23.638  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.638  5593  5641 I jxcore-log: 
11-25 13:04:23.639  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.639  5593  5641 I jxcore-log: 
,11-25 13:04:23.639  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.639  5593  5641 I jxcore-log: 
11-25 13:04:23.639  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 13:04:23.639  5593  5641 I jxcore-log: 
11-25 13:04:23.640  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 13:04:23.640  5593  5641 I jxcore-log: 
,11-25 13:04:23.640  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.640  5593  5641 I jxcore-log: 
11-25 13:04:23.640  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:04:23.640  5593  5641 I jxcore-log: 
11-25 13:04:23.640  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.640  5593  5641 I jxcore-log: 
11-25 13:04:23.640  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:04:23.640  5593  5641 I jxcore-log: 
,11-25 13:04:23.641  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.641  5593  5641 I jxcore-log: 
11-25 13:04:23.641  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.641  5593  5641 I jxcore-log: 
11-25 13:04:23.641  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:04:23.641  5593  5641 I jxcore-log: 
11-25 13:04:23.641  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:04:23.641  5593  5641 I jxcore-log: 
,11-25 13:04:23.642  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:04:23.642  5593  5641 I jxcore-log: 
11-25 13:04:23.642  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.642  5593  5641 I jxcore-log: 
11-25 13:04:23.642  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:04:23.642  5593  5641 I jxcore-log: 
11-25 13:04:23.642  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:04:23.642  5593  5641 I jxcore-log: 
,11-25 13:04:23.643  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 13:04:23.643  5593  5641 I jxcore-log: 
11-25 13:04:23.644  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:04:23.644  5593  5641 I jxcore-log: 
11-25 13:04:23.644  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 13:04:23.644  5593  5641 I jxcore-log: 
11-25 13:04:23.645  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:04:23.645  5593  5641 I jxcore-log: 
,11-25 13:04:23.645  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:04:23.645  5593  5641 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-25 13:04:23.645  5593  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:04:23.645  5593  5641 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-25 13:04:23.645  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:04:23.645  5593  5641 I jxcore-log: 
11-25 13:04:23.645  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.645  5593  5641 I jxcore-log: 
,11-25 13:04:23.646  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:04:23.646  5593  5641 I jxcore-log: 
11-25 13:04:23.646  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.646  5593  5641 I jxcore-log: 
11-25 13:04:23.646  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:04:23.646  5593  5641 I jxcore-log: 
11-25 13:04:23.646  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:04:23.646  5593  5641 I jxcore-log: 
11-25 13:04:23.651  5593  5593 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-25 13:04:23.651  5593  5593 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-25 13:04:23.651  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 13:04:23.651  5593  5641 I jxcore-log: 
11-25 13:04:23.652  5593  5641 I jxcore-log: 2016-11-25 12:04:23 - WARN testUtils: 'myNameCallback not set!'
11-25 13:04:23.652  5593  5641 I jxcore-log: 
,11-25 13:04:25.745  5593  5641 I jxcore-log: 2016-11-25 12:04:25 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 13:04:25.745  5593  5641 I jxcore-log: 
,11-25 13:04:25.747  5593  5641 I jxcore-log: 2016-11-25 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 13:04:25.747  5593  5641 I jxcore-log: 
,11-25 13:04:26.102  5593  5641 I jxcore-log: 2016-11-25 12:04:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 13:04:26.102  5593  5641 I jxcore-log: 
,11-25 13:04:26.114  5593  5641 I jxcore-log: 2016-11-25 12:04:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 13:04:26.114  5593  5641 I jxcore-log: 
,11-25 13:04:26.869   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:27.245  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 13:04:27.245  5593  5641 I jxcore-log: 
,11-25 13:04:27.442  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 13:04:27.442  5593  5641 I jxcore-log: 
,11-25 13:04:27.448  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 13:04:27.448  5593  5641 I jxcore-log: 
,11-25 13:04:27.453  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 13:04:27.453  5593  5641 I jxcore-log: 
,11-25 13:04:27.870   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:27.939  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 13:04:27.939  5593  5641 I jxcore-log: 
,11-25 13:04:27.985  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 13:04:27.985  5593  5641 I jxcore-log: 
,11-25 13:04:27.998  5593  5641 I jxcore-log: 2016-11-25 12:04:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 13:04:27.998  5593  5641 I jxcore-log: 
,11-25 13:04:28.003  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 13:04:28.003  5593  5641 I jxcore-log: 
,11-25 13:04:28.283  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 13:04:28.283  5593  5641 I jxcore-log: 
,11-25 13:04:28.414  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 13:04:28.414  5593  5641 I jxcore-log: 
,11-25 13:04:28.792  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 13:04:28.792  5593  5641 I jxcore-log: 
,11-25 13:04:28.800  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 13:04:28.800  5593  5641 I jxcore-log: 
,11-25 13:04:28.805  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 13:04:28.805  5593  5641 I jxcore-log: 
,11-25 13:04:28.810  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 13:04:28.810  5593  5641 I jxcore-log: 
,11-25 13:04:28.816  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 13:04:28.816  5593  5641 I jxcore-log: 
,11-25 13:04:28.844  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 13:04:28.844  5593  5641 I jxcore-log: 
,11-25 13:04:28.871   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:28.879  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 13:04:28.879  5593  5641 I jxcore-log: 
,11-25 13:04:28.886  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 13:04:28.886  5593  5641 I jxcore-log: 
,11-25 13:04:28.893  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 13:04:28.893  5593  5641 I jxcore-log: 
,11-25 13:04:28.908  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 13:04:28.908  5593  5641 I jxcore-log: 
,11-25 13:04:28.924  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 13:04:28.924  5593  5641 I jxcore-log: 
,11-25 13:04:28.930  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 13:04:28.930  5593  5641 I jxcore-log: 
,11-25 13:04:28.936  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 13:04:28.936  5593  5641 I jxcore-log: 
,11-25 13:04:28.949  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 13:04:28.949  5593  5641 I jxcore-log: 
,11-25 13:04:28.966  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 13:04:28.966  5593  5641 I jxcore-log: 
,11-25 13:04:28.981  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 13:04:28.981  5593  5641 I jxcore-log: 
,11-25 13:04:28.992  5593  5641 I jxcore-log: 2016-11-25 12:04:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 13:04:28.992  5593  5641 I jxcore-log: 
,11-25 13:04:29.004  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 13:04:29.004  5593  5641 I jxcore-log: 
,11-25 13:04:29.014  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 13:04:29.014  5593  5641 I jxcore-log: 
,11-25 13:04:29.028  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 13:04:29.028  5593  5641 I jxcore-log: 
,11-25 13:04:29.038  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 13:04:29.038  5593  5641 I jxcore-log: 
,11-25 13:04:29.044  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 13:04:29.044  5593  5641 I jxcore-log: 
,11-25 13:04:29.066  5593  5641 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 13:04:29.067  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 13:04:29.067  5593  5641 I jxcore-log: 
,11-25 13:04:29.102  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 13:04:29.102  5593  5641 I jxcore-log: 
,11-25 13:04:29.452  5593  5641 I jxcore-log: 2016-11-25 12:04:29 - DEBUG CoordinatedClient: 'connected to the test server'
11-25 13:04:29.452  5593  5641 I jxcore-log: 
,11-25 13:04:29.872   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:30.874   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:04:31.875   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:04:46.816   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:04:56.875   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:04:56.876   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:05:06.877   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:07.878   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:08.880   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:09.881   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:10.698  5885  5885 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:05:10.882   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:11.883   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 13:05:16.884   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:17.886   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:18.887   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:19.889   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:20.890   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:21.891   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 13:05:25.274   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:05:26.820   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:05:28.303   930  2980 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:05:31.893   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:32.894   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:33.896   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:34.897   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:35.899   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:36.900   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 13:05:46.821   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:05:51.901   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:52.902   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:53.904   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:54.906   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:55.907   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:05:56.908   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:06:16.909   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:06:17.910   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:06:18.911   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:06:19.912   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:06:20.914   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:06:21.914   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:06:26.826   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:06:46.829   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:06:46.915   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:06:46.915   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:07:01.917   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:02.918   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:03.919   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:04.921   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:05.922   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:06.831   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:07:06.923   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 13:07:11.924   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:12.926   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:13.927   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:14.928   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:15.930   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:16.390   930  3787 I ActivityManager: Start proc 5937:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-25 13:07:16.423  5937  5937 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-25 13:07:16.515  5937  5949 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-25 13:07:16.596  5937  5949 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-25 13:07:16.641  5937  5949 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-25 13:07:16.668  5962  5962 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-122995063.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-122995063.dex
,11-25 13:07:16.676  5937  5937 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-25 13:07:16.700  5962  5962 I dex2oat : dex2oat took 33.299ms (threads: 2) arena alloc=200KB java alloc=37KB native alloc=1258KB free=1045KB
,11-25 13:07:16.801  5937  5937 W InstanceID/Rpc: Found 10012
,11-25 13:07:16.854   930  3425 I ActivityManager: Killing 3880:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 13:07:16.931   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 13:07:26.932   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:27.934   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:28.935   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:29.936   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:30.938   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:31.938   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 13:07:46.833   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:07:46.939   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:47.940   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:48.941   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:49.942   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:50.944   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:07:51.944   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:08:06.835   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:08:11.946   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:08:12.947   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:08:13.948   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:08:14.950   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:08:15.951   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:08:16.952   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:08:26.837   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:08:41.954   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:08:41.954   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:08:46.838   930  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:09:01.955   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:09:02.956   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:09:03.958   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:09:04.959   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:09:05.087  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-25 13:09:05.087  5593  5641 I jxcore-log: 
,11-25 13:09:05.249  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 13:09:05.249  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 13:09:05.249  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 13:09:05.249  5593  5641 I jxcore-log: emit@events.js:82:1
11-25 13:09:05.249  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 13:09:05.249  5593  5641 I jxcore-log: emit@events.js:82:1''
11-25 13:09:05.249  5593  5641 I jxcore-log: 
,11-25 13:09:05.251  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - DEBUG CoordinatedClient: 'test client failed'
11-25 13:09:05.251  5593  5641 I jxcore-log: 
,11-25 13:09:05.261  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 13:09:05.261  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 13:09:05.261  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 13:09:05.261  5593  5641 I jxcore-log: emit@events.js:82:1
11-25 13:09:05.261  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 13:09:05.261  5593  5641 I jxcore-log: emit@events.js:82:1''
11-25 13:09:05.261  5593  5641 I jxcore-log: 
,11-25 13:09:05.262  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - DEBUG CoordinatedClient: 'test client failed'
11-25 13:09:05.262  5593  5641 I jxcore-log: 
,11-25 13:09:05.267  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 13:09:05.267  5593  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 13:09:05.267  5593  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 13:09:05.267  5593  5641 I jxcore-log: emit@events.js:82:1
11-25 13:09:05.267  5593  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 13:09:05.267  5593  5641 I jxcore-log: emit@events.js:82:1''
11-25 13:09:05.267  5593  5641 I jxcore-log: 
,11-25 13:09:05.268  5593  5641 I jxcore-log: 2016-11-25 12:09:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 13:09:05.268  5593  5641 I jxcore-log: 
,11-25 13:09:05.721  6023  6023 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 13:09:05.726  6023  6023 D AndroidRuntime: CheckJNI is OFF
,11-25 13:09:05.757  6023  6023 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 13:09:05.792  6023  6023 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 13:09:05.808  6023  6023 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 13:09:05.815   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 13:09:05.815   930   943 I ActivityManager: Killing 5593:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 13:09:05.931   930  2979 D WifiService: Client connection lost with reason: 4
11-25 13:09:05.932   930  3808 D GraphicsStats: Buffer count: 2
11-25 13:09:05.932   930  3808 I WindowState: WIN DEATH: Window{29b9515 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-25 13:09:05.949   930   943 W ActivityManager: Force removing ActivityRecord{8ea1972 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-25 13:09:05.956   930   953 I art     : Starting a blocking GC Explicit
,11-25 13:09:05.959   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:09:05.961   930  3787 W ActivityManager: Spurious death for ProcessRecord{f9be0b2 0:com.test.thalitest/u0a77}, curProc for 5593: null
,11-25 13:09:05.998   930  3425 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5593 uid 10077
,11-25 13:09:05.994  3425  3425 W Binder_6: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[24542]" dev="sockfs" ino=24542 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:09:05.994  3425  3425 W Binder_6: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[24542]" dev="sockfs" ino=24542 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:09:06.000  3661  3661 I Keyboard.Facilitator: onFinishInput()
,11-25 13:09:06.058   930   953 I art     : Explicit concurrent mark sweep GC freed 126037(8MB) AllocSpace objects, 80(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.835ms total 102.011ms
,11-25 13:09:06.069  3960  6036 I MicroRecognitionRnrImpl: Starting detection.
,11-25 13:09:06.071  3960  6037 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@2930f56
,11-25 13:09:06.072   514  6039 I AudioFlinger: AudioFlinger's thread 0xf1c40000 ready to run
11-25 13:09:06.076   514  3000 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 13:09:06.078  3960  6037 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@2930f56
,11-25 13:09:06.080   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 13:09:06.082  6023  6023 I art     : System.exit called, status: 0
,11-25 13:09:06.082  6023  6023 I AndroidRuntime: VM exiting with result code 0.
,11-25 13:09:06.088   514  6039 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-25 13:09:06.088   514  6039 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-25 13:09:06.088   514  6039 I ACDB-LOADER: ACDB AFE returned = -19
11-25 13:09:06.088   514  6039 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-25 13:09:06.088   514  6039 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-25 13:09:06.088   514  6039 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-25 13:09:06.096   514  6039 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-25 13:09:06.098   930   953 I ActivityManager: Start proc 6041:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-25 13:09:06.098   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 13:09:06.105  3661  3661 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-25 13:09:06.107  5831  5831 D BluetoothMapAppObserver: onReceive
11-25 13:09:06.107  5831  5831 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-25 13:09:06.115  4109  4192 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-25 13:09:06.120  3661  6050 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 13:09:06.126  3661  6050 I Decoder : createOrResetDecoder
,11-25 13:09:06.130   930  2944 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 13:09:06.156  3411  6057 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 13:09:06.171    17    17 W kworker/2:0: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:09:06.178  3960  3960 I HotwordWorkerImpl: onReady
,11-25 13:09:06.177    17    17 W kworker/2:0: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:09:06.194    17    17 W kworker/2:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:09:06.206   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 13:09:06.209  3783  3783 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 13:09:06.223  3579  3579 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-25 13:09:06.224  3579  3579 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-25 13:09:06.224  3579  3579 E AndroidRuntime: FATAL EXCEPTION: main
11-25 13:09:06.224  3579  3579 E AndroidRuntime: Process: com.google.process.gapps, PID: 3579
11-25 13:09:06.224  3579  3579 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-25 13:09:06.224  3579  3579 E AndroidRuntime: 	... 8 more
,11-25 13:09:06.229  3411  6057 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-25 13:09:06.232  3820  3911 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-25 13:09:06.232  3411  6057 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-25 13:09:06.232  3411  6057 E AndroidRuntime: Process: android.process.acore, PID: 3411
11-25 13:09:06.232  3411  6057 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:09:06.232  3411  6057 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:09:06.235   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-25 13:09:06.235  3411  3434 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-25 13:09:06.235  3411  3434 I Process : Sending signal. PID: 3411 SIG: 9
11-25 13:09:06.235   930   942 E PackageManager: Failed to write settings, restoring backup
11-25 13:09:06.235   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-25 13:09:06.235   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-25 13:09:06.235   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-25 13:09:06.235   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-25 13:09:06.235   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-25 13:09:06.235   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:09:06.235   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:09:06.235   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:09:06.239   930  6063 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:09:06.239   930  6063 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:09:06.239   930  6063 E DropBoxManagerService: 	... 5 more
,11-25 13:09:06.244   930   943 E DropBoxManagerService: Can't write: system_server_wtf
11-25 13:09:06.244   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-25 13:09:06.244   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:09:06.244   930   943 E DropBoxManagerService: 	... 13 more
,11-25 13:09:06.247   930  3129 I ActivityManager: Start proc 6064:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-25 13:09:06.248  3820  3911 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-25 13:09:06.248  3820  3911 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3820
11-25 13:09:06.248  3820  3911 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:09:06.248  3820  3911 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:09:06.249   930  6070 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:09:06.249   930  6070 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:09:06.249   930  6070 E DropBoxManagerService: 	... 5 more
,11-25 13:09:06.267   771   771 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35946]" dev="sockfs" ino=35946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:09:06.267   771   771 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35946]" dev="sockfs" ino=35946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:09:06.267   771   771 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34583]" dev="sockfs" ino=34583 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:09:06.267   771   771 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34583]" dev="sockfs" ino=34583 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:09:06.272   930  6077 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 13:09:06.287   930  3129 I ActivityManager: Process android.process.acore (pid 3411) has died
11-25 13:09:06.287   930  3129 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-25 13:09:06.291   930  6078 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:09:06.291   930  6078 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:09:06.291   930  6078 E DropBoxManagerService: 	... 5 more
,11-25 13:09:06.294   930  3787 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 13:09:06.297  3960  3970 W SearchService: Abort, client detached.
11-25 13:09:06.300  3960  3960 I HotwordDetector: Closing mic
11-25 13:09:06.300  3960  4193 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2930f56
,11-25 13:09:06.300  3960  6037 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-25 13:09:06.326   930  3804 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-25 13:09:06.338  3820  3820 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2d03190 new=com.google.android.velvet.VelvetApplication@2d03190
,11-25 13:09:06.372   514  6039 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-25 13:09:06.373   514  6039 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-25 13:09:06.377   514  6039 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-25 13:09:06.377   514  6039 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-25 13:09:06.378   514  3000 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 13:09:06.380  3960  6036 I MicroRecognitionRnrImpl: Detection finished
11-25 13:09:06.381  3960  4194 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-25 13:09:06.402  3820  3820 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,11-25 13:09:06.407  3836  3836 W Binder_C: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[30677]" dev="sockfs" ino=30677 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:09:06.407  3836  3836 W Binder_C: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[30677]" dev="sockfs" ino=30677 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:09:06.574   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
