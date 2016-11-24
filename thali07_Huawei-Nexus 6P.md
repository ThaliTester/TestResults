#### Test 9418709436e67d1_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 18:15:51.892  3979  4404 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 18:15:52.371  5539  5539 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 18:15:52.376  5539  5539 D AndroidRuntime: CheckJNI is OFF
11-24 18:15:52.405  5539  5539 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 18:15:52.449  5539  5539 I Radio-JNI: register_android_hardware_Radio DONE
11-24 18:15:52.464  5539  5539 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 18:15:52.467   932   943 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 18:15:52.485  5539  5539 D AndroidRuntime: Shutting down VM
11-24 18:15:52.501  3905  4151 W SearchService: Abort, client detached.
11-24 18:15:52.507  3905  3905 I HotwordDetector: Closing mic
11-24 18:15:52.507  3905  4130 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5374c57
11-24 18:15:52.507  3905  4143 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 18:15:52.530   932   943 I ActivityManager: Start proc 5548:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 18:15:52.592   513  4145 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 18:15:52.593   513  4145 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 18:15:52.599   513  4145 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 18:15:52.599   513  4145 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 18:15:52.600   513  2928 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 18:15:52.602  3905  4136 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 18:15:52.602  3905  4142 I MicroRecognitionRnrImpl: Detection finished
11-24 18:15:52.638  5548  5548 I CordovaLog: Changing log level to DEBUG(3)
11-24 18:15:52.638  5548  5548 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 18:15:52.638  5548  5548 D CordovaActivity: CordovaActivity.onCreate()
11-24 18:15:52.642  5548  5548 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 18:15:52.662  5548  5548 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-24 18:15:52.687  5548  5548 I LibraryLoader: Time to load native libraries: 23 ms (timestamps 8117-8140)
11-24 18:15:52.687  5548  5548 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 18:15:52.705  5548  5548 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ba15a14}
11-24 18:15:52.706  5548  5548 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 18:15:52.706  5548  5548 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-24 18:15:52.709  5548  5548 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-24 18:15:52.710  5548  5548 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 18:15:52.745  5548  5548 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 18:15:52.753  5548  5548 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 18:15:52.753  5548  5548 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 18:15:52.754  5548  5548 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 18:15:52.754  5548  5548 I Adreno  : Build Date                       : 12/06/15
11-24 18:15:52.754  5548  5548 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 18:15:52.754  5548  5548 I Adreno  : Local Branch                     : mybranch17112971
11-24 18:15:52.754  5548  5548 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 18:15:52.754  5548  5548 I Adreno  : Remote Branch                    : NONE
11-24 18:15:52.754  5548  5548 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 18:15:52.790   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1f883e:true
,11-24 18:15:52.824   407   407 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[24179]" dev="sockfs" ino=24179 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.827   407   407 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24179]" dev="sockfs" ino=24179 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.838  5548  5548 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 18:15:52.845  5548  5548 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 18:15:52.849  5548  5548 D PluginManager: init()
,11-24 18:15:52.851  5548  5548 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 18:15:52.864  5548  5548 D CordovaActivity: Started the activity.
,11-24 18:15:52.864  5548  5548 D CordovaActivity: Resumed the activity.
,11-24 18:15:52.864   761   761 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29436]" dev="sockfs" ino=29436 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.864   761   761 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29436]" dev="sockfs" ino=29436 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.869  5548  5585 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 18:15:52.874  5548  5572 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 18:15:52.867  3084  3084 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[24190]" dev="sockfs" ino=24190 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.867  3084  3084 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24190]" dev="sockfs" ino=24190 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.892  5548  5585 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 18:15:52.961  3349  3349 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24193]" dev="sockfs" ino=24193 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.964   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +454ms
,11-24 18:15:52.961  3349  3349 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[24193]" dev="sockfs" ino=24193 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 18:15:52.967  3592  3592 I Keyboard.Facilitator: onFinishInput()
,11-24 18:15:52.964  3084  3084 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[24192]" dev="sockfs" ino=24192 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 18:15:52.964  3084  3084 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[24192]" dev="sockfs" ino=24192 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 18:15:52.988  5548  5548 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 18:15:53.023  5548  5548 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5548
,11-24 18:15:53.116  5548  5548 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 18:15:53.323  5548  5587 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -583534288
,11-24 18:15:53.326  5548  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 18:15:53.326  5548  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 18:15:53.326  5548  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 18:15:53.326  5548  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 18:15:53.326  5548  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 18:15:53.326  5548  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d20143b added. We now have 1 listener(s)
,11-24 18:15:53.329  5548  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 18:15:53.329  5548  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 18:15:53.330   932  3767 I ActivityManager: Killing 5222:com.android.settings/1000 (adj 15): empty #17
11-24 18:15:53.330  5548  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:15:53.330  5548  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-24 18:15:53.332  5548  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5cc996 added. We now have 1 listener(s)
11-24 18:15:53.332  5548  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:15:53.338   932  2907 D WifiService: New client listening to asynchronous messages
,11-24 18:15:53.338  5548  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 18:15:53.338  5548  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 18:15:53.339  5548  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 18:15:53.339  5548  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-24 18:15:53.339  5548  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 18:15:53.339  5548  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 18:15:53.339  5548  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 18:15:53.341  5548  5587 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 18:15:53.361   932  3767 I ActivityManager: Killing 5183:org.codeaurora.ims/1001 (adj 15): empty #18
,11-24 18:15:53.427  5548  5548 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 18:15:53.429  5548  5548 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 18:15:53.429  5548  5548 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 18:15:53.912  5548  5595 W jxcore-log: Initializing JXcore engine
,11-24 18:15:53.912  5548  5595 W jxcore-log: JXcore engine is ready
,11-24 18:15:53.934  5595  5595 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12822 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 18:15:53.934  5595  5595 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13413]" dev="sockfs" ino=13413 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 18:15:53.934  5595  5595 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-24 18:15:53.934  5595  5595 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33153]" dev="sockfs" ino=33153 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 18:15:53.945  5548  5595 W jxcore-log: Starting JXcore engine
,11-24 18:15:53.996  5548  5595 W jxcore-log: Platform android
11-24 18:15:53.996  5548  5595 W jxcore-log: 
,11-24 18:15:53.996  5548  5595 W jxcore-log: Process ARCH arm
11-24 18:15:53.996  5548  5595 W jxcore-log: 
,11-24 18:15:54.188  5548  5595 I jxcore-log: JXcore Cordova bridge is ready!
11-24 18:15:54.188  5548  5595 I jxcore-log: 
,11-24 18:15:54.189  5548  5595 W jxcore-log: JXcore engine is started
11-24 18:15:54.196  5548  5587 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-24 18:15:54.204  5548  5548 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-24 18:15:54.205  5548  5548 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 18:15:58.528   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:15:59.529   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:00.530   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:01.532   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:02.533   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:02.635  3905  5596 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 18:16:02.722  3516  5600 I VacuumService: Vacuum at: now=1480007762722 tag=VacuumService
,11-24 18:16:02.743  3516  5603 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 18:16:02.791  3516  5601 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-24 18:16:02.794  3516  5601 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 18:16:02.816  3516  5603 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 18:16:03.113  3516  5601 W Uploader:  no longer exists, so no auth token.
,11-24 18:16:03.122  3516  5605 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 18:16:03.283  3516  5603 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 18:16:03.359  3516  5601 W Uploader:  no longer exists, so no auth token.
,11-24 18:16:03.368  3516  5605 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 18:16:03.437  3516  5603 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 18:16:03.517  3516  5605 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 18:16:03.534   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 18:16:03.801  5548  5595 I jxcore-log: 2016-11-24 17:16:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 18:16:03.801  5548  5595 I jxcore-log: 
,11-24 18:16:03.803  5548  5595 I jxcore-log: 2016-11-24 17:16:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 18:16:03.803  5548  5595 I jxcore-log: 
,11-24 18:16:03.808  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:03.809  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 18:16:03.810  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 18:16:03.812  5548  5595 I jxcore-log: 2016-11-24 17:16:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 18:16:03.812  5548  5595 I jxcore-log: 
11-24 18:16:03.814  5548  5595 I jxcore-log: 2016-11-24 17:16:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 18:16:03.814  5548  5595 I jxcore-log: 
,11-24 18:16:04.052  5548  5595 I jxcore-log: 2016-11-24 17:16:04 - DEBUG UnitTest_app: 'Running unit tests'
11-24 18:16:04.052  5548  5595 I jxcore-log: 
,11-24 18:16:04.053  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:16:04.053  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecf3852 added. We now have 2 listener(s)
11-24 18:16:04.054  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 18:16:04.054  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:16:04.054  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:16:04.054  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:16:04.054  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d02723 added. We now have 2 listener(s)
11-24 18:16:04.054  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:16:04.054  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 18:16:04.055  5548  5595 D executeNativeTests: Running unit tests
,11-24 18:16:04.090  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:16:04.090  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 added. We now have 3 listener(s)
,11-24 18:16:04.091  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 18:16:04.091  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:16:04.091  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:16:04.091  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:16:04.091  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 added. We now have 3 listener(s)
11-24 18:16:04.091  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:16:04.092  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 18:16:04.093  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 18:16:04.093  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 18:16:04.093  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 18:16:04.093  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 18:16:04.094  5548  5595 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 18:16:04.094  5548  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 18:16:04.094  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 18:16:04.094  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 18:16:04.094  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 18:16:04.094  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 18:16:04.094  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:04.095  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 18:16:04.095  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:04.095  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:04.095  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:04.095  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 18:16:04.095  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 removed from the list
11-24 18:16:04.095  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:04.095  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 removed from the list
,11-24 18:16:04.095  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:04.095  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.095  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.096  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:04.096  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:04.096  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.096  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 18:16:04.096  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:04.096  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:04.096  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:04.097  5548  5595 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 18:16:04.097  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:04.097  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 18:16:04.097  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:04.097  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:04.098  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:04.098  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:04.098  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:04.098  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:04.098  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:04.098  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.098  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.098  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.098  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.098  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.098  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 18:16:04.098  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:04.098  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:04.098  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 18:16:04.101  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 18:16:04.102  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-24 18:16:04.102  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 18:16:04.102  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 18:16:04.102  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:04.102  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:04.102  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:04.102  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 18:16:04.102  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:04.102  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:04.102  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:04.102  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:04.102  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:04.102  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:04.102  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.102  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.103  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.103  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.103  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 18:16:04.103  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:04.103  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:04.103  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:04.103  5548  5595 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 18:16:04.104  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:16:04.104  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:04.109  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 18:16:04.110  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 18:16:04.110  5548  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 18:16:04.110  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 18:16:04.110  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 18:16:04.110  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 18:16:04.110  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:16:04.111  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 18:16:04.114  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:04.115  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 18:16:04.115  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 18:16:04.115  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 18:16:04.118  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.118  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 18:16:04.118  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:04.119  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 18:16:04.119  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 18:16:04.119  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 18:16:04.120  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-24 18:16:04.121  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 18:16:04.121  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.121  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 18:16:04.121  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 18:16:04.121  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 18:16:04.122  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 18:16:04.122  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:04.122  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:04.124  4555  4778 D BtGatt.GattService: registerClient() - UUID=b5dca78b-16f9-438d-b8d3-3046ec70cc10
11-24 18:16:04.125  4555  4643 D BtGatt.GattService: onClientRegistered() - UUID=b5dca78b-16f9-438d-b8d3-3046ec70cc10, clientIf=5
11-24 18:16:04.126  5548  5558 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 18:16:04.126  4555  4567 D BtGatt.GattService: start scan with filters
,11-24 18:16:04.131  4555  4646 D BtGatt.ScanManager: handling starting scan
,11-24 18:16:04.131  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 18:16:04.131  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.131  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 18:16:04.131  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.131  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 18:16:04.132  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 18:16:04.132  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 18:16:04.132  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 18:16:04.132  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 18:16:04.132  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 18:16:04.132  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.132  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.132  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.133  4555  4646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:16:04.133  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.133  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.133  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:04.133  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.133  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:04.133  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.133  5548  5595 I io.jxcore.node.ConnectionHelper: start: OK
11-24 18:16:04.140  4555  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 18:16:04.140  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:04.140  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 18:16:04.140  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:16:04.141  4555  4646 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 18:16:04.141  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.141  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:04.141  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 18:16:04.147  4555  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 18:16:04.147  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:04.148  4555  4646 D BtGatt.ScanManager: Starting BLE batch scan
11-24 18:16:04.148  4555  4646 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 18:16:04.157  4555  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 18:16:04.157  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:04.163  4555  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 18:16:04.163  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:04.642  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 18:16:04.643  5548  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:16:04.643  5548  5548 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 18:16:07.664   932  5312 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173116, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 18:16:08.710   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 18:16:09.137  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:09.137  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:09.137  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 18:16:09.137  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:16:09.137  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 18:16:09.137  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:09.138  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 18:16:09.138  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 18:16:09.138  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.138  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:16:09.138  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:16:09.139  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.139  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.139  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:09.139  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 18:16:09.139  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.141  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:09.141  4555  4800 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 18:16:09.141  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 18:16:09.143  4555  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 18:16:09.144  5548  5595 D BluetoothAdapter: STATE_ON
,11-24 18:16:09.146  4555  4778 D BtGatt.GattService: stopScan() - queue size =1
,11-24 18:16:09.149  4555  4567 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 18:16:09.150  4555  4555 D BtGatt.ScanManager: awakened up at time 174603
11-24 18:16:09.151  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 18:16:09.152  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:09.152  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 18:16:09.152  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.152  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.153  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:09.153  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.154  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 18:16:09.154  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.154  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.154  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:09.154  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 18:16:09.154  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 18:16:09.155  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:16:09.155  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:09.159  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:09.160  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:09.160  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.160  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:09.161  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:09.161  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:09.161  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:16:09.161  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:16:09.161  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:09.161  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:09.161  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-24 18:16:09.161  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:09.161  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:09.161  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.161  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:09.161  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 18:16:09.161  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:09.161  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 18:16:09.162  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:16:09.162  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 18:16:09.162  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.162  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.162  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:09.162  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.162  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.164  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.164  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:09.165  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 18:16:09.175  4555  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 18:16:09.175  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:09.175  4555  4643 D BtGatt.GattService: current time is 174628752702
11-24 18:16:09.176  4555  4643 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -90, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -86, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -87, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-24 18:16:09.180  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-24 18:16:09.182  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 18:16:09.182  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 18:16:09.183  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 18:16:09.183  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 18:16:09.183  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-24 18:16:09.190  4555  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 18:16:09.190  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:09.190  4555  4646 D BtGatt.ScanManager: stopping BLe Batch
,11-24 18:16:09.196  4555  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 18:16:09.196  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:09.196  4555  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 18:16:09.203  4555  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 18:16:09.203  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:09.663  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 18:16:11.749   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 18:16:14.165  5548  5595 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 18:16:14.171  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 18:16:14.171  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:14.184  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 18:16:14.188  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 18:16:14.188  5548  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-24 18:16:14.189  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 18:16:14.189  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-24 18:16:14.189  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 18:16:14.189  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 18:16:14.189  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 18:16:14.195  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:14.196  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 18:16:14.197  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 18:16:14.197  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 18:16:14.200  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:14.204  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:14.204  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 18:16:14.206  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 18:16:14.206  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 18:16:14.206  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 18:16:14.212  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.212  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 18:16:14.212  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 18:16:14.212  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 18:16:14.213  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 18:16:14.213  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.214  5548  5595 D BluetoothAdapter: STATE_ON
,11-24 18:16:14.217  4555  4799 D BtGatt.GattService: registerClient() - UUID=f90e92cb-4a6d-4b32-9d79-e0639d087f93
,11-24 18:16:14.218  4555  4643 D BtGatt.GattService: onClientRegistered() - UUID=f90e92cb-4a6d-4b32-9d79-e0639d087f93, clientIf=5
,11-24 18:16:14.219  5548  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 18:16:14.219  4555  4800 D BtGatt.GattService: start scan with filters
11-24 18:16:14.223  4555  4646 D BtGatt.ScanManager: handling starting scan
11-24 18:16:14.224  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 18:16:14.224  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:14.224  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 18:16:14.224  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.225  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 18:16:14.225  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 18:16:14.225  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.225  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 18:16:14.225  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 18:16:14.225  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.226  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.226  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.226  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.227  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 18:16:14.227  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:14.233  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:14.233  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:16:14.233  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.233  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.234  5548  5595 I io.jxcore.node.ConnectionHelper: start: OK
11-24 18:16:14.234  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 18:16:14.235  4555  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 18:16:14.236  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:14.236  4555  4646 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 18:16:14.239  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:14.239  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 18:16:14.239  5548  5595 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 18:16:14.239  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.240  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 18:16:14.240  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.240  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 18:16:14.240  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:16:14.240  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:16:14.240  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 18:16:14.240  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:14.240  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 18:16:14.240  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 18:16:14.240  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.240  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:16:14.240  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:16:14.241  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.241  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.241  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.241  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 18:16:14.241  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.242  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:14.242  4555  4799 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 18:16:14.242  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 18:16:14.244  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:14.244  4555  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 18:16:14.244  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.244  4555  4800 D BtGatt.GattService: stopScan() - queue size =1
11-24 18:16:14.245  4555  4646 D BtGatt.ScanManager: Starting BLE batch scan
11-24 18:16:14.245  4555  4646 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 18:16:14.245  4555  4569 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.,internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.246  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.247  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 18:16:14.247  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.247  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.247  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.247  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 18:16:14.247  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 18:16:14.248  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:16:14.248  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.250  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.250  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:14.250  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.251  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.251  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:14.251  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:16:14.251  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:16:14.251  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:14.251  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:14.251  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:14.251  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:14.251  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:14.251  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 18:16:14.251  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:14.251  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:14.251  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.251  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:16:14.251  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 18:16:14.251  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 18:16:14.252  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.252  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.252  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.252  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:14.253  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.253  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.253  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.255  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.255  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.256  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.256  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:14.256  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:14.256  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:14.256  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:14.256  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.257  5548  5595 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 18:16:14.257  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.258  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.258  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.259  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:16:14.259  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 18:16:14.259  4555  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 18:16:14.259  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:14.266  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 18:16:14.266  4555  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 18:16:14.266  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.268  4555  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:16:14.269  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 18:16:14.269  5548  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 18:16:14.269  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:16:14.269  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 18:16:14.269  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 18:16:14.269  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:16:14.270  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 18:16:14.273  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:14.276  4555  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 18:16:14.276  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.276  4555  4643 E BtGatt.ContextMap: Context not found for ID 5
11-24 18:16:14.276  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 18:16:14.276  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 18:16:14.276  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 18:16:14.277  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:14.280  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.280  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 18:16:14.281  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 18:16:14.281  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 18:16:14.282  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 18:16:14.285  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.285  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 18:16:14.285  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 18:16:14.285  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 18:16:14.286  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 18:16:14.286  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.286  4555  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 18:16:14.286  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.286  4555  4646 D BtGatt.ScanManager: stopping BLe Batch
11-24 18:16:14.286  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:14.290  4555  4800 D BtGatt.GattService: registerClient() - UUID=89fad17b-520d-4c95-ae99-0a3507259f65
11-24 18:16:14.292  4555  4643 D BtGatt.GattService: onClientRegistered() - UUID=89fad17b-520d-4c95-ae99-0a3507259f65, clientIf=5
11-24 18:16:14.292  4555  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 18:16:14.292  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.292  5548  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 18:16:14.293  4555  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:16:14.293  4555  4567 D BtGatt.GattService: start scan with filters
11-24 18:16:14.296  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 18:16:14.296  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.296  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 18:16:14.296  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.296  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 18:16:14.296  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 18:16:14.296  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.296  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 18:16:14.296  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 18:16:14.296  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.296  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.297  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.297  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.297  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 18:16:14.297  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.298  4555  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 18:16:14.298  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.300  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.300  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:16:14.300  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.300  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:14.300  5548  5595 I io.jxcore.node.ConnectionHelper: start: OK
11-24 18:16:14.300  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.300  4555  4646 D BtGatt.ScanManager: handling starting scan
11-24 18:16:14.303  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.303  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.303  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:14.303  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:16:14.309  4555  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 18:16:14.309  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.309  4555  4646 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 18:16:14.314  4555  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 18:16:14.314  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.314  4555  4646 D BtGatt.ScanManager: Starting BLE batch scan
11-24 18:16:14.314  4555  4646 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 18:16:14.323  4555  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 18:16:14.323  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:14.329  4555  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 18:16:14.329  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:14.805  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 18:16:14.806  5548  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:16:14.806  5548  5548 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 18:16:15.663   932  2895 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 18:16:17.804   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 18:16:19.301  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:19.301  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 18:16:19.301  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 18:16:19.301  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:16:19.301  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 18:16:19.302  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:19.302  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 18:16:19.302  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 18:16:19.302  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.302  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:16:19.302  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:16:19.303  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.303  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:19.303  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.303  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 18:16:19.303  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.305  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:19.306  4555  4800 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 18:16:19.306  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 18:16:19.308  4555  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:16:19.308  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:16:19.310  4555  4778 D BtGatt.GattService: stopScan() - queue size =1
11-24 18:16:19.312  4555  4799 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 18:16:19.313  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 18:16:19.314  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.314  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 18:16:19.314  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.314  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:19.314  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.315  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.315  4555  4555 D BtGatt.ScanManager: awakened up at time 184768
11-24 18:16:19.315  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 18:16:19.315  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.315  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.315  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.316  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-24 18:16:19.316  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 18:16:19.319  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:16:19.319  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.322  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.322  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 18:16:19.322  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.322  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:19.322  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:19.323  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:19.323  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 18:16:19.323  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 18:16:19.323  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 18:16:19.323  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 18:16:19.323  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.323  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.323  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.324  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:19.324  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.324  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.325  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.325  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:16:19.325  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 18:16:19.334  4555  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-24 18:16:19.334  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:19.335  4555  4643 D BtGatt.GattService: current time is 184788042006
11-24 18:16:19.335  4555  4643 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -84, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -90, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -87, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 18:16:19.335  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 18:16:19.335  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 18:16:19.336  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 18:16:19.336  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 18:16:19.336  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 18:16:19.336  4555  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 18:16:19.342  4555  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 18:16:19.342  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:19.343  4555  4646 D BtGatt.ScanManager: stopping BLe Batch
,11-24 18:16:19.348  4555  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 18:16:19.348  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:16:19.348  4555  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 18:16:19.353  4555  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 18:16:19.353  4555  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:16:19.825  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 18:16:19.826  5548  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 18:16:19.826  5548  5548 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 18:16:20.836   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 18:16:23.535   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:24.324  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:24.324  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.324  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.325  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.325  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 18:16:24.325  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:16:24.325  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.325  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.325  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:24.326  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.326  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.326  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:16:24.328  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.329  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.332  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.332  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.332  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.332  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.333  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 18:16:24.333  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.333  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.335  5548  5595 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-24 18:16:24.336  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:24.336  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.337  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.337  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 18:16:24.337  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.337  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.337  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.338  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:24.338  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.338  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.338  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.341  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.341  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.341  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.341  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.342  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 18:16:24.342  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.342  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:24.344  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 18:16:24.345  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:24.345  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.345  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.345  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.345  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.346  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.346  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.346  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:24.346  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.346  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.346  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.349  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.349  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.349  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.349  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 18:16:24.349  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.349  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.349  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.351  5548  5595 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 18:16:24.351  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.351  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.352  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 18:16:24.352  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.352  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.352  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.352  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.352  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:24.352  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.352  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.353  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.354  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.355  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.355  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.355  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.355  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.355  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.355  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.357  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 18:16:24.357  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.357  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.357  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.358  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.358  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.358  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.358  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.358  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:24.358  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.358  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.358  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.361  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.361  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.361  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.361  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.362  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 18:16:24.362  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.362  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.363  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 18:16:24.363  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 18:16:24.364  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 18:16:24.364  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 18:16:24.364  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 18:16:24.364  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 18:16:24.364  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 18:16:24.364  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 18:16:24.364  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 18:16:24.364  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.365  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.365  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.365  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.365  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.365  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.365  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.365  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.365  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.366  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.366  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.368  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.368  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.368  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.368  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.368  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.368  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:24.368  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.369  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 18:16:24.370  5548  5595 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 18:16:24.370  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 18:16:24.375  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 18:16:24.375  5548  5595 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 18:16:24.376  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 18:16:24.377  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 18:16:24.378  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 18:16:24.378  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 18:16:24.379  5548  5595 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 18:16:24.379  5548  5595 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 18:16:24.379  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 18:16:24.379  5548  5595 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 18:16:24.379  5548  5595 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 18:16:24.379  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 18:16:24.379  5548  5595 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 18:16:24.379  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 18:16:24.384  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 18:16:24.385  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 18:16:24.385  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-24 18:16:24.386  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 18:16:24.386  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 18:16:24.386  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 18:16:24.387  5548  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 18:16:24.387  5548  5595 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 18:16:24.387  5548  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,11-24 18:16:24.387  5548  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 18:16:24.387  5548  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 18:16:24.387  5548  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-24 18:16:24.388  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.388  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.388  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 18:16:24.388  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.388  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 18:16:24.388  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 18:16:24.390  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.391  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.391  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.391  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:24.391  5548  5610 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 18:16:24.391  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.391  5548  5610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:16:24.391  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.393  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.393  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.393  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.393  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.393  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.393  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.394  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.394  5548  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-24 18:16:24.394  5548  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 18:16:24.394  5548  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-24 18:16:24.394  5548  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-24 18:16:24.395  4555  4772 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
11-24 18:16:24.395  5548  5595 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-24 18:16:24.391  4567  4567 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32301]" dev="sockfs" ino=32301 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 18:16:24.391  4567  4567 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32301]" dev="sockfs" ino=32301 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 18:16:24.395  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.396  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.396  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.396  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.396  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.396  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.396  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.396  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.396  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.396  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.396  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.397  5548  5610 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-24 18:16:24.397  5548  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 18:16:24.397  5548  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-24 18:16:24.400  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.400  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.400  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.400  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.400  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.400  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.400  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.401  5548  5595 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 18:16:24.401  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.401  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.401  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 18:16:24.401  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.402  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.402  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.402  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.402  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.402  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.402  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.402  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.404  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.404  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.404  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.404  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.404  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.404  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.404  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.405  5548  5595 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 18:16:24.405  5548  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 18:16:24.405  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 18:16:24.405  5548  5595 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 18:16:24.405  5548  5595 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 18:16:24.405  5548  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 18:16:24.405  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 18:16:24.405  5548  5595 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 18:16:24.405  5548  5595 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 18:16:24.405  5548  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 18:16:24.405  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 18:16:24.405  5548  5595 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-24 18:16:24.405  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:24.406  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:24.406  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:24.406  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.406  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.406  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.406  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.406  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.406  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:24.406  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:24.406  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.407  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.407  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.408  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:24.408  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:24.408  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:24.408  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:24.408  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.408  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:24.408  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:24.409  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:24.409  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:24.409  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:24.409  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:24.536   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:25.537   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:26.538   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:27.539   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:16:28.540   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 18:16:29.409  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:29.410  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.410  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:29.410  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:29.410  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
,11-24 18:16:29.411  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:29.411  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:29.411  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 18:16:29.411  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:29.412  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:29.412  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
,11-24 18:16:29.412  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:29.412  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:29.412  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:29.413  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.413  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.416  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.416  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.418  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.418  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 18:16:29.418  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:29.418  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.419  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:29.425  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-24 18:16:29.426  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:16:29.427  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 18:16:29.434  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 18:16:29.436  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-24 18:16:29.436  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 18:16:29.437  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-24 18:16:29.437  5548  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-24 18:16:29.437  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 18:16:29.438  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 18:16:29.438  5548  5548 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 18:16:29.439  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 18:16:29.439  5548  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:16:29.439  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 18:16:29.439  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 18:16:29.439  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 18:16:29.440  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:16:29.442  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-24 18:16:29.441  4799  4799 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31451]" dev="sockfs" ino=31451 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 18:16:29.442  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-24 18:16:29.443  5548  5548 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 18:16:29.443  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:29.443  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:29.443  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 18:16:29.443  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.443  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:16:29.444  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:16:29.444  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.441  4799  4799 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31451]" dev="sockfs" ino=31451 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 18:16:29.447  5548  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 18:16:29.447  5548  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 18:16:29.447  5548  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 18:16:29.448  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.448  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:29.449  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.449  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.450  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.450  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:29.450  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:29.450  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:16:29.450  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:29.450  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:29.450  5548  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 18:16:29.450  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:29.450  5548  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 18:16:29.451  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:16:29.451  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:29.451  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:29.451  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.451  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.451  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:29.451  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.452  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.453  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.453  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.453  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.454  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:29.454  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 18:16:29.454  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.454  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.455  5548  5595 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 18:16:29.455  5548  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-24 18:16:29.455  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 18:16:29.456  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 18:16:29.456  5548  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 18:16:29.456  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:29.456  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:29.456  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:29.456  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:29.456  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:29.456  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:29.456  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.456  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:29.456  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:29.457  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.457  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.458  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.458  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.458  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.458  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 18:16:29.459  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:29.459  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.459  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:29.464  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:16:29.465  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:29.465  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:29.465  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:29.465  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 18:16:29.465  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:29.465  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.465  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.465  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:29.465  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.465  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.467  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.467  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.467  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.467  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:29.467  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 18:16:29.468  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.468  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
,11-24 18:16:29.469  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 18:16:29.469  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:16:29.469  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:16:29.469  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:16:29.469  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:16:29.469  5548  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c3550 not in the list
11-24 18:16:29.469  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:29.469  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.469  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:29.469  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.469  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.471  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.471  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:16:29.471  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:16:29.471  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:16:29.471  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:16:29.471  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:16:29.471  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df14349 not in the list
11-24 18:16:29.472  5548  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 18:16:29.472  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 18:16:29.473  5548  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 18:16:29.473  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 18:16:29.473  5548  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 18:16:29.473  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 18:16:29.475  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-24 18:16:29.475  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 18:16:29.476  5548  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 18:16:29.476  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 18:16:29.477  5548  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 18:16:29.477  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-24 18:16:29.477  5548  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 18:16:29.477  5548  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 18:16:29.478  5548  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 18:16:29.478  5548  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 18:16:29.478  5548  5595 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-24 18:16:29.478  5548  5595 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 18:16:29.478  5548  5595 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 18:16:29.478  5548  5595 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 18:16:29.479  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:16:29.479  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6702cfe added. We now have 3 listener(s)
,11-24 18:16:29.479  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:16:29.481  5548  5595 D BluetoothAdapter: enable(): BT is already enabled..!
11-24 18:16:29.481   932  3744 D WifiService: setWifiEnabled: true pid=5548, uid=10077
11-24 18:16:29.482   932  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 18:16:29.523  4555  4749 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 18:16:29.523  4555  4749 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 18:16:29.952  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 18:16:34.487  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:16:34.487  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ecbc5f added. We now have 4 listener(s)
11-24 18:16:34.488  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:16:34.500  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:34.501  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ecbc5f removed from the list
,11-24 18:16:34.501  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:34.503  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:16:34.503  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ab56ac added. We now have 4 listener(s)
11-24 18:16:34.503  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:16:34.507  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:34.507  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ab56ac removed from the list
,11-24 18:16:34.508  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:34.509  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:16:34.510  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d647f75 added. We now have 4 listener(s)
11-24 18:16:34.510  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:16:34.515   932  3744 D WifiService: setWifiEnabled: false pid=5548, uid=10077
,11-24 18:16:34.515   932  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 18:16:34.526   932  2895 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 18:16:34.526   932  2895 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 18:16:34.526   932  2895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 18:16:34.526   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 18:16:34.532  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 18:16:34.532  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 18:16:34.533  4555  4639 D BluetoothAdapterState: Current state: ON, message: 23
11-24 18:16:34.533  4555  4639 D BluetoothAdapterProperties: Setting state to 13
11-24 18:16:34.533  4555  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 18:16:34.535  4555  4639 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 18:16:34.536  4555  4639 I BluetoothAdapterState: Entering PendingCommandState
,11-24 18:16:34.543  4555  4555 D BluetoothMapService: onReceive
,11-24 18:16:34.543  4555  4555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 18:16:34.543  4555  4555 D BluetoothMapService: STATE_TURNING_OFF
11-24 18:16:34.544  4555  4555 D BluetoothMapService: MAP Service closeService in
11-24 18:16:34.544  4555  4555 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 18:16:34.544  4555  4555 D ObexServerSockets0: shutdown(block = true)
11-24 18:16:34.545  4555  4555 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 18:16:34.546  4555  4803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 18:16:34.546  4555  4802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 18:16:34.547  4555  4772 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 18:16:34.547  4555  4555 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 18:16:34.548  4555  4555 I BtOppRfcommListener: stopping Accept Thread
11-24 18:16:34.548  4555  5242 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 18:16:34.549  4555  5242 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 18:16:34.553   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 18:16:34.554   932  5313 D DhcpClient: Clearing IP address
,11-24 18:16:34.561   508   925 D CommandListener: Setting iface cfg
,11-24 18:16:34.565   932  5314 D DhcpClient: Receive thread stopped
,11-24 18:16:34.568   932   945 I ActivityManager: Start proc 5616:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-24 18:16:34.568  4555  4643 D BluetoothAdapterProperties: Scan Mode:20
,11-24 18:16:34.569  4555  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 18:16:34.572  4555  4555 D HeadsetService: Received stop request...Stopping profile...
11-24 18:16:34.574   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:34.574   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:34.574   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:34.574  3064  3903 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:34.574  3064  3064 D HeadsetProfile: Bluetooth service disconnected
11-24 18:16:34.575  3692  3931 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:34.575  4555  4555 D A2dpService: Received stop request...Stopping profile...
11-24 18:16:34.575  4555  4782 D A2dpStateMachine: Exit Disconnected: -1
11-24 18:16:34.576   932   932 D BluetoothA2dp: Proxy object disconnected
11-24 18:16:34.577  3064  3064 D BluetoothA2dp: Proxy object disconnected
,11-24 18:16:34.577  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:34.578  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 18:16:34.578  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.578  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.578  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.578  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:16:34.578  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.579  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 18:16:34.579  4555  4555 D HidService: Received stop request...Stopping profile...
11-24 18:16:34.579  4555  4555 D HidService: Stopping Bluetooth HidService
11-24 18:16:34.579  5548  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 18:16:34.579  3064  3064 D BluetoothInputDevice: Proxy object disconnected
,11-24 18:16:34.579  3064  3064 D HidProfile: Bluetooth service disconnected
11-24 18:16:34.581  3516  5372 V NativeCrypto: Read error: ssl=0x7fa9505700: I/O error during system call, Connection timed out
11-24 18:16:34.582  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:34.583  3516  5372 V NativeCrypto: SSL shutdown failed: ssl=0x7fa9505700: I/O error during system call, Broken pipe
11-24 18:16:34.583   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 18:16:34.584   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 18:16:34.586  4555  4555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 18:16:34.586  4555  4555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 18:16:34.586   534   534 E Parcel  : Reading a NULL string not supported here.
11-24 18:16:34.586  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:34.586  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 18:16:34.587  4555  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:34.587  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.587  4555  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-24 18:16:34.588  4555  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:34.588  4555  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:34.588  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-24 18:16:34.589  4555  4643 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 18:16:34.589  4555  4555 D HealthService: Received stop request...Stopping profile...
,11-24 18:16:34.594   932   932 D RttService: SCAN_AVAILABLE : 1
,11-24 18:16:34.594  4555  4555 D PanService: Received stop request...Stopping profile...
11-24 18:16:34.594   932  3006 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 18:16:34.597   932  2908 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-24 18:16:34.598  3661  3812 W QCNEJ   : |CORE| network lost: 100
11-24 18:16:34.599  3661  3812 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 18:16:34.600  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.600  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.600  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.600  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:34.601  4555  4555 D BluetoothMapService: Received stop request...Stopping profile...
11-24 18:16:34.601  4555  4555 D BluetoothMapService: stop()
11-24 18:16:34.601   932  2895 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 18:16:34.601  4555  4555 D BluetoothMapAppObserver: deinitObservers()
11-24 18:16:34.601  4555  4555 D BluetoothMapAppObserver: removeReceiver()
,11-24 18:16:34.605  4555  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 18:16:34.605  4555  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:34.605  4555  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:34.605  4555  4749 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 18:16:34.605  4555  4749 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 18:16:34.606  4555  4749 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 18:16:34.606  4555  4749 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 18:16:34.606  4555  4555 D SapService: Received stop request...Stopping profile...
,11-24 18:16:34.606  4555  4555 V SapService: stop()
,11-24 18:16:34.608  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 18:16:34.608  3064  3064 D PanProfile: Bluetooth service disconnected
11-24 18:16:34.608  3064  3064 D BluetoothMap: Proxy object disconnected
11-24 18:16:34.609  3064  3064 D MapProfile: Bluetooth service disconnected
,11-24 18:16:34.614   932  2895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 18:16:34.614  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.614  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.614  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.614  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:34.615  4555  4555 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 18:16:34.615  4555  4555 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 18:16:34.615  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.615  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.615  4555  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 18:16:34.615  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.615  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:34.615  4555  4555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-24 18:16:34.616  4555  4555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-24 18:16:34.616  4555  4643 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 18:16:34.616  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.616  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.616  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.616  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:16:34.616  4555  4555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 18:16:34.616  4555  4555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 18:16:34.617  4555  4555 D BluetoothMapService: MAP Service closeService in
11-24 18:16:34.617  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.617  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.617  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.617  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:16:34.618  4555  4555 D BluetoothMapService: cleanup()
11-24 18:16:34.618  4555  4555 D BluetoothMapService: MAP Service closeService in
11-24 18:16:34.618  4555  4555 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:34.618  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.618  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.618  4555  4555 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:34.618  4555  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-24 18:16:34.618  4555  4639 D BluetoothAdapterProperties: Setting state to 15
11-24 18:16:34.618  4555  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 18:16:34.620  3064  3903 D BluetoothPan: onBluetoothStateChange on: false
11-24 18:16:34.620  4555  4639 I BluetoothAdapterState: Entering BleOnState
11-24 18:16:34.621   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:34.621   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:34.621   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 18:16:34.622  3064  3075 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 18:16:34.622  3064  3076 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:34.622  3064  3903 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 18:16:34.623   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:34.623  3064  3075 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 18:16:34.624  3064  3076 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 18:16:34.624  3692  3728 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:34.625  4555  4639 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 18:16:34.625  4555  4639 D BluetoothAdapterProperties: Setting state to 16
11-24 18:16:34.625  4555  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 18:16:34.626  4555  4639 D BluetoothAdapterProperties: onBleDisable
,11-24 18:16:34.626  4555  4639 I BluetoothAdapterState: Entering PendingCommandState
11-24 18:16:34.626  4555  4640 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 18:16:34.627  4555  4643 D BluetoothAdapterProperties: Scan Mode:20
11-24 18:16:34.627  4555  4749 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 18:16:34.628  4555  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 18:16:34.629  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:16:34.629  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:16:34.630  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.630  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 18:16:34.633  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:34.634   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 18:16:34.634  5616  5616 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 18:16:34.648  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 18:16:34.653   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@54fa8dc:true
,11-24 18:16:34.654  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 18:16:34.657   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:16:34.658   508   925 D CommandListener: Clearing all IP addresses on wlan0
11-24 18:16:34.658   508   925 D TetherController: Setting IP forward enable = 0
11-24 18:16:34.660   932  2908 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 18:16:34.660   932  2908 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:16:34.664   932   949 D Tethering: MasterInitialState.processMessage what=3
,11-24 18:16:34.664   932  2895 D DhcpClient: doQuit
,11-24 18:16:34.664  5198  5198 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ae93040 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 18:16:34.664   932  2895 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 18:16:34.665  3375  3375 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 18:16:34.665  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:34.666   932  5313 D DhcpClient: onQuitting
11-24 18:16:34.667  3905  3905 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 18:16:34.671  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.671  4985  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:16:34.671  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:16:34.671  4985  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 18:16:34.671  4985  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 18:16:34.671  4985  5007 E SarControlService: no key has been found,reset the power
11-24 18:16:34.671  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 18:16:34.671  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 18:16:34.671  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 18:16:34.671  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:34.671  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 18:16:34.672  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:16:34.672  5010  5010 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 18:16:34.674  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 18:16:34.674  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 18:16:34.674  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 18:16:34.676  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:16:34.676  5010  5010 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 18:16:34.679  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000ea03000000000000ffffffff]
11-24 18:16:34.679  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:16:34.679  5010  5024 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 18:16:34.679  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 18:16:34.679  4985  4995 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 18:16:34.685  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000eb03000000000000ffffffff]
11-24 18:16:34.686  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:16:34.686  5010  5024 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 18:16:34.686  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 18:16:34.686  4985  4996 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 18:16:34.689  3375  3375 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 18:16:34.693  3375  3375 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 18:16:34.694  5616  5616 D LocalBluetoothProfileManager: Adding local MAP profile
11-24 18:16:34.696  5616  5616 D BluetoothMap: Create BluetoothMap proxy object
11-24 18:16:34.705  5616  5616 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-24 18:16:34.711  5616  5616 D DockEventReceiver: finishStartingService: stopping service
11-24 18:16:34.714  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 18:16:34.714   508   925 E Netd    : netlink response contains error (No such file or directory)
11-24 18:16:34.715   932  2908 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 18:16:34.719  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 18:16:34.719  5616  5616 D DockEventReceiver: finishStartingService: stopping service
11-24 18:16:34.721   932  3767 I ActivityManager: Killing 5344:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-24 18:16:34.729  3375  3375 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 18:16:34.740  3375  3375 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 18:16:34.751  4934  4934 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 18:16:34.752   932  2895 D wifi    : In wifi stop Hal
11-24 18:16:34.752   932  2895 D wifi    : halHandle = 0x7f92f44d00, mVM = 0x7faf58d140, mCls = 0x100a02
11-24 18:16:34.752   932  3374 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 18:16:34.752   932  3374 D WifiHAL : Got a signal to exit!!!
11-24 18:16:34.752   932  3374 I WifiHAL : Exit wifi_event_loop
11-24 18:16:34.755  3979  4154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 18:16:34.755  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:34.756   932  2895 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 18:16:34.756   932  2895 E WifiHAL : Event processing terminated
11-24 18:16:34.756   932  2895 D wifi    : In wifi cleaned up handler
11-24 18:16:34.756   932  2895 I WifiHAL : Internal cleanup completed
,11-24 18:16:34.758  3781  3781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 18:16:34.762  3781  3781 D SystemUpdateService: onCreate
,11-24 18:16:34.766  3781  3781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 18:16:34.773   932  3374 D wifi    : set interface wlan0 flags (DOWN)
,11-24 18:16:34.774   932  2895 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 18:16:34.776  3781  3781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 18:16:34.782  3781  5342 I iu.UploadsManager: num queued entries: 0
,11-24 18:16:34.782  3781  5342 I iu.UploadsManager: num updated entries: 0
11-24 18:16:34.782  3781  5342 I iu.SyncManager: NEXT; no task
11-24 18:16:34.783  3781  5648 I SystemUpdateService: active receiver: enabled
,11-24 18:16:34.785  3781  3781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 18:16:34.786  3781  3781 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 18:16:34.790  3781  5648 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 18:16:34.792  3781  5648 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 18:16:34.792  3781  5648 I SystemUpdateService: now status is 0 (complete)
11-24 18:16:34.792  3781  5648 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 18:16:34.792  3781  5648 I SystemUpdateService: file has been verified
11-24 18:16:34.792  3781  5648 I SystemUpdateService: OTA package size = 21989297
,11-24 18:16:34.798   932  3738 I ActivityManager: Start proc 5650:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 18:16:34.801  3781  5648 I SystemUpdateService: showing system update notification
,11-24 18:16:34.812   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 18:16:34.815  3781  3781 D SystemUpdateService: onDestroy
,11-24 18:16:34.829  5650  5650 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 18:16:34.832  5650  5650 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:16:34.836  4555  4643 I bt_hci  : shut_down
,11-24 18:16:34.838  4555  4647 D bt_hwcfg: hw_epilog_process
,11-24 18:16:34.838  4555  4647 I bt_vendor: low_power_mode_cb
,11-24 18:16:34.841  5650  5650 D SprintDMHelper: simOperator: 
,11-24 18:16:34.841  5650  5650 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 18:16:34.841  4555  4647 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 18:16:34.841  4555  4647 I bt_vendor: epilog_cb
11-24 18:16:34.841  4555  4647 I bt_hci  : epilog_finished_callback
,11-24 18:16:34.845  4555  4643 I bt_hci_h4: hal_close
,11-24 18:16:34.845  4555  4643 I bt_userial_vendor: device fd = 54 close
,11-24 18:16:34.854  4934  5662 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 18:16:34.867   932   943 I ActivityManager: Start proc 5663:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 18:16:34.869   932   943 I ActivityManager: Killing 5198:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 18:16:34.904  5663  5663 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 18:16:34.911   932  3738 I ActivityManager: Killing 3826:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 18:16:34.950  4555  4640 D bt_stack_manager: event_shut_down_stack finished.
,11-24 18:16:34.950  4555  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 18:16:34.952  4555  4639 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 18:16:34.952  4555  4555 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 18:16:34.952  4555  4555 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 18:16:34.953  4555  4555 D BtGatt.GattService: stop()
,11-24 18:16:34.953  4555  4555 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 18:16:34.954  4555  4555 V BluetoothAdapterState: isTurningOff()=false
11-24 18:16:34.954  4555  4555 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:34.954  4555  4555 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:34.954  4555  4555 V BluetoothAdapterState: isBleTurningOff()=true
11-24 18:16:34.954  4555  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 18:16:34.954  4555  4639 D BluetoothAdapterProperties: Setting state to 10
11-24 18:16:34.954  4555  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-24 18:16:34.955  4555  4639 I BluetoothAdapterState: Entering OffState
,11-24 18:16:34.956   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 18:16:34.962  4555  4555 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 18:16:34.962  4555  4555 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 18:16:34.962  4555  4555 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 18:16:34.963  4555  4640 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 18:16:34.966  4555  4555 I art     : System.exit called, status: 0
,11-24 18:16:34.966  4555  4555 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 18:16:34.977   932   949 D Tethering: InitialState.processMessage what=4
,11-24 18:16:34.980   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 18:16:34.998   932  3738 I ActivityManager: Process com.android.bluetooth (pid 4555) has died
,11-24 18:16:35.739   508   925 D TetherController: Setting IP forward enable = 0
,11-24 18:16:39.581   932  3351 D WifiService: setWifiEnabled: true pid=5548, uid=10077
11-24 18:16:39.582   932  3351 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 18:16:39.589   508   925 D SoftapController: Softap fwReload - Ok
,11-24 18:16:39.595   508   925 D CommandListener: Setting iface cfg
11-24 18:16:39.595   508   925 D CommandListener: Trying to bring down wlan0
11-24 18:16:39.598   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 18:16:39.604   932  2895 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 18:16:40.189   932  2895 D wifi    : set interface wlan0 flags (UP)
,11-24 18:16:40.195   932  2895 I WifiHAL : Initializing wifi
,11-24 18:16:40.196   932  2895 I WifiHAL : Creating socket
,11-24 18:16:40.199   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 18:16:40.202   932  2895 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 18:16:40.202   932  2895 D wifi    : Did set static halHandle = 0x7f92f44d00
,11-24 18:16:40.203   932  2895 D wifi    : halHandle = 0x7f92f44d00, mVM = 0x7faf58d140, mCls = 0x10198e
11-24 18:16:40.203   932  2895 D wifi    : array field set
11-24 18:16:40.203   932  2895 I WifiNative-HAL: interface[0] = wlan0
,11-24 18:16:40.205   932  5684 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547926330624
,11-24 18:16:40.208   932  5684 D wifi    : waitForHalEvents called, vm = 0x7faf58d140, obj = 0x10198e, env = 0x7f953709c0
,11-24 18:16:40.281  5685  5685 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 18:16:40.307   932  2895 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 18:16:40.316  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:40.356  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 18:16:40.385  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 18:16:40.385  5685  5685 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 18:16:40.399   932  2895 D WifiConfigStore: Loading config and enabling all networks 
,11-24 18:16:40.405  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:16:40.405  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:16:40.405  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:40.405  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 18:16:40.415   932  2895 D WifiConfigStore: loaded 0 passpoint configs
,11-24 18:16:40.416   932  2895 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 18:16:40.416   932  2895 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 18:16:40.417   932  2895 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 18:16:40.417   932  2895 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 18:16:40.417   932  2895 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 18:16:40.418   932  2895 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 18:16:40.418   932  2895 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-24 18:16:40.418   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-24 18:16:40.418   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 18:16:40.418   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 18:16:40.418   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-24 18:16:40.419   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-24 18:16:40.421   932  2895 D WifiNative-HAL: Setting external_sim to 1
,11-24 18:16:40.421   932  2895 D wifi    : setting dfs flag to true, 0x7f93e6c4a0
11-24 18:16:40.421   932  2895 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 18:16:40.422   932  2895 D wifi    : setting scan oui 0x7f93e6c4a0
,11-24 18:16:40.422   932  2895 D WifiHAL : Sending mac address OUI
,11-24 18:16:40.422  4934  4934 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 18:16:40.425   932  2895 E native  : do suspend false
,11-24 18:16:40.432   932  2895 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 18:16:40.432   932   932 D RttService: SCAN_AVAILABLE : 3
11-24 18:16:40.433   932  3006 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 18:16:40.436   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 18:16:40.437   508   925 D CommandListener: Setting iface cfg
,11-24 18:16:40.443   932  2867 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 18:16:40.443   932  2867 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 18:16:40.446   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=205899 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,11-24 18:16:40.448   932  2867 D WifiNative-HAL: p2pGetDeviceAddress
11-24 18:16:40.448   932  2867 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 18:16:43.544  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 18:16:43.553  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 18:16:43.559  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 18:16:43.595   932  2895 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 18:16:43.596   932  2895 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 18:16:43.596   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 18:16:43.608   932  2895 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 18:16:43.640   932  2895 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 18:16:43.647  5685  5685 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 18:16:44.069  5685  5685 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 18:16:44.107  5685  5685 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 18:16:44.109  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 18:16:44.120   932  2895 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 18:16:44.121   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 18:16:44.121   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 18:16:44.137   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 18:16:44.153   508   925 D CommandListener: Setting iface cfg
,11-24 18:16:44.160   932  2895 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 18:16:44.166   932  5691 D DhcpClient: Receive thread started
,11-24 18:16:44.170   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 18:16:44.170   932  2895 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 18:16:44.170   932  2908 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 18:16:44.251   932  2895 E native  : do suspend false
,11-24 18:16:44.261   932  5690 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 18:16:44.278   932  5691 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172632, domain null
,11-24 18:16:44.278   932  5690 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172632 seconds
,11-24 18:16:44.280   932  5690 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 18:16:44.310   932  5691 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 18:16:44.312   932  5690 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 18:16:44.316   508   925 D CommandListener: Setting iface cfg
11-24 18:16:44.321   932  2895 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 18:16:44.325   932  5690 D DhcpClient: Scheduling renewal in 86399s
,11-24 18:16:44.332   932  2895 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 18:16:44.333   932  2895 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 18:16:44.334   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 18:16:44.341   932  2908 D ConnectivityService: Adding iface wlan0 to network 101,
,11-24 18:16:44.357   932  2895 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 18:16:44.391   932  2908 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 18:16:44.391   932  2908 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 18:16:44.393   932  2908 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 18:16:44.394   932  2908 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 18:16:44.398   932  2908 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 18:16:44.407   932  2908 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 18:16:44.411   932  2908 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-24 18:16:44.411   932  2908 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 18:16:44.411   932  2908 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 18:16:44.411   932  2908 D ConnectivityService:    accepting network in place of null
11-24 18:16:44.411   932  2895 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 18:16:44.411   932  2895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 18:16:44.412   932  2908 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 18:16:44.433   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:16:44.455   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:16:44.459   932  2908 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 18:16:44.459   932  2908 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 18:16:44.459  3661  3812 W QCNEJ   : |CORE| network available: 101
11-24 18:16:44.460   932  2908 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 18:16:44.461   932   949 D Tethering: MasterInitialState.processMessage what=3
11-24 18:16:44.461  3661  3812 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 18:16:44.463  3661  3812 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 18:16:44.463  3661  3812 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 18:16:44.464   932  5689 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 18:16:44.467  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 18:16:44.467  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 18:16:44.467  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:44.467  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 18:16:44.476  4985  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 18:16:44.477  4985  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 18:16:44.477  4985  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 18:16:44.477  4985  5007 E SarControlService: no key has been found,reset the power
11-24 18:16:44.477  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 18:16:44.477  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 18:16:44.477  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 18:16:44.478  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:16:44.478  5010  5010 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 18:16:44.479  3905  3905 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 18:16:44.480  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 18:16:44.481  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 18:16:44.481  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 18:16:44.481  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:16:44.481  5010  5010 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 18:16:44.483  3781  3781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 18:16:44.484  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000ec03000000000000ffffffff]
11-24 18:16:44.485  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 18:16:44.485  5010  5024 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-24 18:16:44.488  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 18:16:44.488  4985  4995 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 18:16:44.489  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000ed03000000000000ffffffff]
11-24 18:16:44.489  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:16:44.489  5010  5024 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 18:16:44.490  3781  3781 D SystemUpdateService: onCreate
11-24 18:16:44.491  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 18:16:44.491  4985  4996 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 18:16:44.495  3781  3781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 18:16:44.505  3781  3781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 18:16:44.508  3781  5342 I iu.UploadsManager: num queued entries: 0
,11-24 18:16:44.509  3781  5342 I iu.UploadsManager: num updated entries: 0
11-24 18:16:44.509  3781  5342 I iu.SyncManager: NEXT; no task
,11-24 18:16:44.515  3781  5703 I SystemUpdateService: active receiver: enabled
,11-24 18:16:44.518  3781  3781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 18:16:44.520  3781  3781 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 18:16:44.522  5650  5650 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:16:44.527  5650  5650 D SprintDMHelper: simOperator: 
,11-24 18:16:44.527  5650  5650 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 18:16:44.529   932  5688 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 18:16:44.551  3781  5703 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 18:16:44.564  3781  5703 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 18:16:44.564  3781  5703 I SystemUpdateService: now status is 0 (complete)
11-24 18:16:44.565  3781  5703 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 18:16:44.565  3781  5703 I SystemUpdateService: file has been verified
11-24 18:16:44.565  3781  5703 I SystemUpdateService: OTA package size = 21989297
,11-24 18:16:44.571  3781  5703 I SystemUpdateService: showing system update notification
,11-24 18:16:44.579   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 18:16:44.580   932  5688 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 17:16:44 GMT], X-Android-Received-Millis=[1480007804579], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480007804554]}
,11-24 18:16:44.581   932  2908 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 18:16:44.581   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 18:16:44.581   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 18:16:44.582   932  2908 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 18:16:44.583  3781  3781 D SystemUpdateService: onDestroy
,11-24 18:16:44.590   932  3744 D WifiService: setWifiEnabled: false pid=5548, uid=10077
,11-24 18:16:44.590   932  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 18:16:44.592   932  2895 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 18:16:44.592   932  2895 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 18:16:44.592   932  2895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 18:16:44.592   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 18:16:44.599   932  5690 D DhcpClient: Clearing IP address
,11-24 18:16:44.599   508   925 D CommandListener: Clearing all IP addresses on wlan0
11-24 18:16:44.601   508   925 D CommandListener: Setting iface cfg
,11-24 18:16:44.606  3516  5704 V NativeCrypto: SSL handshake aborted: ssl=0x7f939af180: I/O error during system call, Connection timed out
,11-24 18:16:44.610   932  5691 D DhcpClient: Receive thread stopped
11-24 18:16:44.613   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 18:16:44.613   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 18:16:44.616   932   932 D RttService: SCAN_AVAILABLE : 1
11-24 18:16:44.617   534   534 E Parcel  : Reading a NULL string not supported here.
11-24 18:16:44.617   932  3006 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 18:16:44.619   932  2908 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 18:16:44.619   932  2895 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 18:16:44.621  3661  3812 W QCNEJ   : |CORE| network lost: 101
,11-24 18:16:44.622  3661  3812 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 18:16:44.624   932  2895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 18:16:44.628  4934  5708 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-24 18:16:44.643   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.22.110 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
11-24 18:16:44.644  4934  5708 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-24 18:16:44.644  4934  5708 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 18:16:44.662   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:16:44.663   508   925 D CommandListener: Clearing all IP addresses on wlan0
11-24 18:16:44.663   932  2908 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 18:16:44.663   932  2908 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:16:44.664   932   949 D Tethering: MasterInitialState.processMessage what=3
,11-24 18:16:44.668   932  2895 D DhcpClient: doQuit
11-24 18:16:44.668   932  2895 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 18:16:44.668   932  5690 D DhcpClient: onQuitting
11-24 18:16:44.669  5685  5685 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 18:16:44.669  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:16:44.669  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:16:44.669  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:44.670  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 18:16:44.672  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:44.675  3905  3905 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 18:16:44.677  3781  3781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 18:16:44.679  4985  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 18:16:44.679  4985  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 18:16:44.679  4985  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 18:16:44.679  4985  5007 E SarControlService: no key has been found,reset the power
11-24 18:16:44.680  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 18:16:44.680  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 18:16:44.680  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 18:16:44.680  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 18:16:44.680  5010  5010 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 18:16:44.681  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 18:16:44.682  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-24 18:16:44.682  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 18:16:44.682  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:16:44.682  5010  5010 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 18:16:44.685  3781  3781 D SystemUpdateService: onCreate
11-24 18:16:44.685  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 18:16:44.686  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000ee03000000000000ffffffff]
11-24 18:16:44.686  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:16:44.686  5010  5024 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 18:16:44.686  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 18:16:44.687  4985  4996 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 18:16:44.690  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000ef03000000000000ffffffff]
,11-24 18:16:44.690  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:16:44.690  5010  5024 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 18:16:44.690  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 18:16:44.691  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 18:16:44.691  4985  4995 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 18:16:44.692  3781  3781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 18:16:44.698  3781  5724 I SystemUpdateService: active receiver: enabled
,11-24 18:16:44.700  3781  3781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 18:16:44.704  3781  5342 I iu.UploadsManager: num queued entries: 0
,11-24 18:16:44.707  3781  3781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 18:16:44.709  3781  3781 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 18:16:44.710  5650  5650 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:16:44.714  5650  5650 D SprintDMHelper: simOperator: 
11-24 18:16:44.714  5650  5650 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 18:16:44.715   508   925 E Netd    : netlink response contains error (No such file or directory)
,11-24 18:16:44.724  3781  5724 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 18:16:44.725  3781  5342 I iu.UploadsManager: num updated entries: 0
,11-24 18:16:44.729  4934  5727 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 18:16:44.729  5685  5685 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 18:16:44.736  3781  5342 I iu.SyncManager: NEXT; no task
,11-24 18:16:44.736  3781  5724 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 18:16:44.736  3781  5724 I SystemUpdateService: now status is 0 (complete)
11-24 18:16:44.736  3781  5724 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 18:16:44.737  3781  5724 I SystemUpdateService: file has been verified
11-24 18:16:44.737  3781  5724 I SystemUpdateService: OTA package size = 21989297
,11-24 18:16:44.744  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 18:16:44.745  3781  5724 I SystemUpdateService: showing system update notification
,11-24 18:16:44.753   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 18:16:44.756  3781  3781 D SystemUpdateService: onDestroy
,11-24 18:16:44.847   932  2895 D wifi    : In wifi stop Hal
,11-24 18:16:44.848   932  2895 D wifi    : halHandle = 0x7f92f44d00, mVM = 0x7faf58d140, mCls = 0x10198e
11-24 18:16:44.849   932  5684 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 18:16:44.849   932  5684 D WifiHAL : Got a signal to exit!!!
,11-24 18:16:44.849   932  5684 I WifiHAL : Exit wifi_event_loop
11-24 18:16:44.850   932  2895 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-24 18:16:44.850   932  2895 E WifiHAL : Event processing terminated
,11-24 18:16:44.850  4934  4934 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 18:16:44.850   932  2895 D wifi    : In wifi cleaned up handler
11-24 18:16:44.850  3979  4154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 18:16:44.850   932  2895 I WifiHAL : Internal cleanup completed
11-24 18:16:44.851  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:44.871   932  5684 D wifi    : set interface wlan0 flags (DOWN)
,11-24 18:16:44.872   932  2895 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 18:16:45.078   932   949 D Tethering: InitialState.processMessage what=4
,11-24 18:16:45.086   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 18:16:45.459   932  2908 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 18:16:49.627   932   949 I ActivityManager: Start proc 5729:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 18:16:49.714  5729  5729 D AdapterServiceConfig: Adding HeadsetService
,11-24 18:16:49.714  5729  5729 D AdapterServiceConfig: Adding A2dpService
11-24 18:16:49.714  5729  5729 D AdapterServiceConfig: Adding HidService
11-24 18:16:49.714  5729  5729 D AdapterServiceConfig: Adding HealthService
11-24 18:16:49.715  5729  5729 D AdapterServiceConfig: Adding PanService
,11-24 18:16:49.715  5729  5729 D AdapterServiceConfig: Adding GattService
11-24 18:16:49.715  5729  5729 D AdapterServiceConfig: Adding BluetoothMapService
11-24 18:16:49.715  5729  5729 D AdapterServiceConfig: Adding SapService
,11-24 18:16:49.726   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67d4cc9:true
,11-24 18:16:49.727  5729  5729 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 18:16:49.729  5729  5729 I bt_bluedroid: init
11-24 18:16:49.730  5729  5741 I BluetoothAdapterState: Entering OffState
,11-24 18:16:49.732  5729  5742 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 18:16:49.732  5729  5742 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 18:16:49.732  5729  5742 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 18:16:49.732  5729  5742 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 18:16:49.732  5729  5729 I bt_bluedroid: get_profile_interface socket
,11-24 18:16:49.734  5729  5729 I bt_bluedroid: get_profile_interface sdp
,11-24 18:16:49.734  5729  5745 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 18:16:49.735  5729  5745 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 18:16:49.739  5729  5740 I bt_bluedroid: config_hci_snoop_log
,11-24 18:16:49.740   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 18:16:49.744  5729  5741 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 18:16:49.745  5729  5741 D BluetoothAdapterProperties: Setting state to 14
,11-24 18:16:49.745  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 18:16:49.746  5729  5741 D BluetoothBondStateMachine: make
,11-24 18:16:49.748  5729  5746 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 18:16:49.751  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
,11-24 18:16:49.752  5729  5729 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 18:16:49.754  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:16:49.755  5729  5729 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 18:16:49.755  5729  5729 D BtGatt.GattService: Received start request. Starting profile...
11-24 18:16:49.755  5729  5729 D BtGatt.GattService: start()
11-24 18:16:49.755  5729  5729 I bt_bluedroid: get_profile_interface gatt
11-24 18:16:49.756  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:16:49.756  5729  5729 D BtGatt.AdvertiseManager: advertise manager created
,11-24 18:16:49.761  5729  5729 V BluetoothAdapterState: isTurningOff()=false
11-24 18:16:49.761  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:49.761  5729  5729 V BluetoothAdapterState: isBleTurningOn()=true
11-24 18:16:49.761  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:49.762  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 18:16:49.763  5729  5741 I bt_bluedroid: bt_bluedroid
,11-24 18:16:49.763  5729  5742 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 18:16:49.763  5729  5742 I bt_hci  : start_up
,11-24 18:16:49.768  5729  5742 I bt_vendor: alloc value 0xf3cab871
,11-24 18:16:49.768  5729  5742 I bt_vendor: init
11-24 18:16:49.768  5729  5742 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 18:16:49.769  5729  5742 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 18:16:49.880  5729  5742 D bt_hci  : start_up starting async portion
,11-24 18:16:49.881  5729  5749 I bt_hci  : event_finish_startup
11-24 18:16:49.881  5729  5749 I bt_hci_h4: hal_open
11-24 18:16:49.881  5729  5749 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 18:16:49.877  5750  5750 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 18:16:49.884  5729  5749 I bt_userial_vendor: device fd = 54 open
,11-24 18:16:49.900  5729  5749 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 18:16:49.903  5729  5749 D bt_hwcfg: Chipset BCM4358A3
,11-24 18:16:49.903  5729  5749 D bt_hwcfg: Target name = [BCM4358A3]
11-24 18:16:49.904  5729  5749 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 18:16:50.309  5729  5749 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 18:16:50.309  5729  5749 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 18:16:50.309  5729  5749 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 18:16:50.445  5729  5749 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 18:16:50.445  5729  5749 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 18:16:50.446  5729  5749 I bt_hwcfg: vendor lib fwcfg completed
11-24 18:16:50.447  5729  5749 I bt_vendor: firmware callback
11-24 18:16:50.447  5729  5749 I bt_hci  : firmware_config_callback
,11-24 18:16:50.455  5729  5752 I bt_btu  : btu_task pending for preload complete event
,11-24 18:16:50.455  5729  5752 I bt_btu_task: Bluetooth chip preload is complete
,11-24 18:16:50.455  5729  5752 I bt_btu  : btu_task received preload complete event
,11-24 18:16:50.464  5729  5752 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 18:16:50.465  5729  5752 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 18:16:50.466  5729  5752 I         : BTE_InitTraceLevels -- TRC_PAN
,11-24 18:16:50.466  5729  5752 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 18:16:50.466  5729  5752 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 18:16:50.466  5729  5752 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 18:16:50.466  5729  5752 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 18:16:50.466  5729  5752 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 18:16:50.552  5729  5752 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c29549
11-24 18:16:50.552  5729  5752 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c29549 
,11-24 18:16:50.574  5729  5745 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 18:16:50.575  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 18:16:50.575  5729  5745 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 18:16:50.578  5729  5745 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 18:16:50.580  5729  5745 D BluetoothAdapterProperties: Scan Mode:20
,11-24 18:16:50.580  5729  5745 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 18:16:50.581  5729  5745 D bt_hci  : do_postload posting postload work item
11-24 18:16:50.581  5729  5749 I bt_hci  : event_postload
11-24 18:16:50.581  5729  5749 I bt_vendor: sco_config_cb
11-24 18:16:50.581  5729  5749 I bt_hci  : sco_config_callback postload finished.
11-24 18:16:50.584  5729  5745 D bt_bte_conf: Device ID record 1 : primary
11-24 18:16:50.584  5729  5745 D bt_bte_conf:   vendorId            = 000f
11-24 18:16:50.584  5729  5745 D bt_bte_conf:   vendorIdSource      = 0001
,11-24 18:16:50.584  5729  5745 D bt_bte_conf:   product             = 1200
11-24 18:16:50.584  5729  5745 D bt_bte_conf:   version             = 1436
11-24 18:16:50.584  5729  5745 D bt_bte_conf:   clientExecutableURL = 
11-24 18:16:50.584  5729  5745 D bt_bte_conf:   serviceDescription  = 
11-24 18:16:50.584  5729  5745 D bt_bte_conf:   documentationURL    = 
11-24 18:16:50.584  5729  5745 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 18:16:50.585  5729  5742 D bt_stack_manager: event_start_up_stack finished
11-24 18:16:50.585  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 18:16:50.586  5729  5741 D BluetoothAdapterProperties: Setting state to 15
,11-24 18:16:50.586  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 18:16:50.588  5729  5741 I BluetoothAdapterState: Entering BleOnState
11-24 18:16:50.588  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:50.590  5729  5749 I bt_vendor: low_power_mode_cb
,11-24 18:16:50.591  5729  5741 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 18:16:50.591  5729  5741 D BluetoothAdapterProperties: Setting state to 11
11-24 18:16:50.591  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-24 18:16:50.596  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:16:50.598  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:16:50.600  5729  5729 D HeadsetService: Received start request. Starting profile...
11-24 18:16:50.602  5729  5729 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 18:16:50.603  5729  5729 D HeadsetStateMachine: make
11-24 18:16:50.608  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
,11-24 18:16:50.611  5729  5729 D HeadsetStateMachine: max_hf_connections = 1
11-24 18:16:50.611  5729  5729 I bt_bluedroid: get_profile_interface handsfree
11-24 18:16:50.612  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 18:16:50.612  5729  5745 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 18:16:50.614  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:16:50.615  5729  5729 D A2dpService: Received start request. Starting profile...
11-24 18:16:50.615  5729  5729 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 18:16:50.615  5729  5729 I bt_bluedroid: get_profile_interface avrcp
,11-24 18:16:50.620  5729  5729 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 18:16:50.620  5729  5729 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 18:16:50.621  5729  5729 D A2dpStateMachine: make
,11-24 18:16:50.621  5729  5729 I bt_bluedroid: get_profile_interface a2dp
11-24 18:16:50.622  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 18:16:50.623  5729  5761 D A2dpStateMachine: Enter Disconnected: -2
,11-24 18:16:50.624  5729  5729 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 18:16:50.625  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:16:50.626  5729  5729 D HidService: Received start request. Starting profile...
11-24 18:16:50.627  5729  5729 I bt_bluedroid: get_profile_interface hidhost
11-24 18:16:50.627  5729  5729 D HidService: setHidService(): set to: null
11-24 18:16:50.627  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 18:16:50.627  5729  5745 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0a56d
,11-24 18:16:50.627  5729  5729 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 18:16:50.627  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 18:16:50.628  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:16:50.629  5729  5729 D HealthService: Received start request. Starting profile...
,11-24 18:16:50.630  5729  5729 I bt_bluedroid: get_profile_interface health
,11-24 18:16:50.631  5729  5729 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 18:16:50.632  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:16:50.632  5616  5616 D BluetoothInputDevice: Proxy object connected
,11-24 18:16:50.633  5729  5729 D PanService: Received start request. Starting profile...
11-24 18:16:50.633  5729  5729 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 18:16:50.633  5616  5616 D HidProfile: Bluetooth service connected
11-24 18:16:50.633  5729  5729 I bt_bluedroid: get_profile_interface pan
11-24 18:16:50.634  5616  5616 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 18:16:50.635  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:16:50.635  5616  5616 D PanProfile: Bluetooth service connected
,11-24 18:16:50.636  5729  5729 D BluetoothMapService: Received start request. Starting profile...
11-24 18:16:50.636  5729  5729 D BluetoothMapService: start()
11-24 18:16:50.637  5616  5616 D BluetoothMap: Proxy object connected
11-24 18:16:50.637  5616  5616 D MapProfile: Bluetooth service connected
11-24 18:16:50.637  5616  5616 D BluetoothMap: getConnectedDevices()
11-24 18:16:50.638  5616  5616 D BluetoothMap: Bluetooth is Not enabled
11-24 18:16:50.638  5729  5729 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 18:16:50.639  5729  5729 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-24 18:16:50.639  5729  5729 D BluetoothMapAppObserver: createReceiver()
,11-24 18:16:50.640  5729  5729 D BluetoothMapAppObserver: initObservers()
,11-24 18:16:50.640  5729  5729 D BluetoothMapAppObserver: getEnabledAccountItems()
11-24 18:16:50.643  5729  5745 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 18:16:50.646  5729  5729 V SapService: SapBinder()
,11-24 18:16:50.646  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:16:50.646  5729  5729 D SapService: Received start request. Starting profile...
11-24 18:16:50.646  5729  5729 V SapService: start()
,11-24 18:16:50.649  5729  5729 V BluetoothAdapterState: isTurningOff()=false
,11-24 18:16:50.649  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.649  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:50.649  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isTurningOff()=false
,11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.650  5729  5759 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isTurningOff()=false
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:50.650  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isTurningOff()=false
11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isTurningOff()=false
11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.651  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:50.652  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:50.652  5729  5729 V BluetoothAdapterState: isTurningOff()=false
,11-24 18:16:50.652  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.652  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:50.652  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:16:50.653  5729  5729 V BluetoothAdapterState: isTurningOff()=false
11-24 18:16:50.653  5729  5729 V BluetoothAdapterState: isTurningOn()=true
11-24 18:16:50.653  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:50.653  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:16:50.653  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 18:16:50.653  5729  5741 D BluetoothAdapterProperties: ScanMode =  20
11-24 18:16:50.653  5729  5741 D BluetoothAdapterProperties: State =  11
,11-24 18:16:50.656  5729  5745 D BluetoothAdapterProperties: Scan Mode:21
,11-24 18:16:50.656  5729  5741 D BluetoothAdapterProperties: Setting state to 12
11-24 18:16:50.656  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 18:16:50.656  5729  5745 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 18:16:50.656  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 18:16:50.656  5729  5741 I BluetoothAdapterState: Entering OnState
11-24 18:16:50.656  5616  5626 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 18:16:50.658  3064  3903 D BluetoothPan: onBluetoothStateChange on: true
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:16:50.659  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 18:16:50.659   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:16:50.659  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 18:16:50.659   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:16:50.659  3064  3064 D PanProfile: Bluetooth service connected
11-24 18:16:50.660  5616  5628 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 18:16:50.660   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 18:16:50.661  5616  5626 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 18:16:50.661  3064  3075 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 18:16:50.661   932   932 D BluetoothA2dp: Proxy object connected
11-24 18:16:50.662  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 18:16:50.663  3064  3064 D BluetoothInputDevice: Proxy object connected
11-24 18:16:50.663  3064  3076 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:16:50.663  3064  3064 D HidProfile: Bluetooth service connected
,11-24 18:16:50.664  5616  5628 D BluetoothPan: onBluetoothStateChange on: true
11-24 18:16:50.664  3064  3075 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 18:16:50.665  5729  5729 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 18:16:50.666   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:16:50.666  5729  5729 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 18:16:50.666  3064  3903 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 18:16:50.667  5729  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:16:50.667  3064  3064 D BluetoothA2dp: Proxy object connected
11-24 18:16:50.667  3064  3075 D BluetoothMap: onBluetoothStateChange: up=true
11-24 18:16:50.668  5729  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:16:50.669  3064  3064 D BluetoothMap: Proxy object connected
11-24 18:16:50.669  3064  3064 D MapProfile: Bluetooth service connected
11-24 18:16:50.669  3064  3064 D BluetoothMap: getConnectedDevices()
11-24 18:16:50.669  5729  5729 D ObexServerSockets: Succeed to create listening sockets 
11-24 18:16:50.669  5729  5729 D ObexServerSockets0: startAccept()
11-24 18:16:50.669  5729  5729 D ObexServerSockets0: prepareForNewConnect()
11-24 18:16:50.670  3692  3728 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 18:16:50.671   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 18:16:50.672  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 18:16:50.674  5729  5729 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 18:16:50.674  5729  5729 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 18:16:50.674  5616  5616 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 18:16:50.675  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:50.675  5729  5729 D BluetoothMapService: onReceive
11-24 18:16:50.675  5729  5768 D ObexServerSockets0: Accepting socket connection...
11-24 18:16:50.675  5729  5767 D ObexServerSockets0: Accepting socket connection...
11-24 18:16:50.675  5729  5729 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 18:16:50.676  5729  5729 D BluetoothMapService: STATE_ON
11-24 18:16:50.678  5729  5770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:16:50.678  5616  5616 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-24 18:16:50.679  5729  5770 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 18:16:50.680  5729  5770 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 18:16:50.685  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 18:16:50.687  5616  5616 D BluetoothA2dp: Proxy object connected
,11-24 18:16:50.691  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 18:16:50.697  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-24 18:16:50.699  3064  3064 D BluetoothPbap: Proxy object connected
11-24 18:16:50.699  3064  3064 D PbapServerProfile: Bluetooth service connected
,11-24 18:16:50.702  5729  5729 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 18:16:50.703  5729  5729 D ObexServerSockets0: prepareForNewConnect()
,11-24 18:16:50.703  5616  5616 D BluetoothPbap: Proxy object connected
,11-24 18:16:50.704  5616  5616 D PbapServerProfile: Bluetooth service connected
,11-24 18:16:50.705  5729  5774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 18:16:50.719  5729  5778 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 18:16:50.720  5729  5778 I BtOppRfcommListener: Accept thread started.
,11-24 18:16:50.761   932   932 D BluetoothHeadset: Proxy object connected
11-24 18:16:50.761   932   932 D BluetoothHeadset: Proxy object connected
,11-24 18:16:50.761   932   932 D BluetoothHeadset: Proxy object connected
11-24 18:16:50.761  3064  3075 D BluetoothHeadset: Proxy object connected
11-24 18:16:50.761  3064  3064 D HeadsetProfile: Bluetooth service connected
11-24 18:16:50.762  3692  3925 D BluetoothHeadset: Proxy object connected
,11-24 18:16:50.763  3064  3903 D BluetoothHeadset: Proxy object connected
,11-24 18:16:50.763  3064  3064 D HeadsetProfile: Bluetooth service connected
,11-24 18:16:50.767   932   949 D BluetoothHeadset: Proxy object connected
,11-24 18:16:50.770  3692  3712 D BluetoothHeadset: Proxy object connected
,11-24 18:16:50.781  5616  5628 D BluetoothHeadset: Proxy object connected
,11-24 18:16:50.782  5616  5616 D HeadsetProfile: Bluetooth service connected
,11-24 18:16:52.419   932  2908 D ConnectivityService: handlePromptUnvalidated 101
,11-24 18:16:52.968  3592  3806 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 18:16:52.968  3592  3806 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 18:16:52.998  3516  3516 I ConfigService: onCreate
,11-24 18:16:53.540   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 18:16:53.540   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 18:16:54.607  5729  5741 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 18:16:54.607  5729  5741 D BluetoothAdapterProperties: Setting state to 13
11-24 18:16:54.607  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 18:16:54.608  5729  5741 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 18:16:54.611  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
11-24 18:16:54.616  5729  5729 D BluetoothMapService: onReceive
11-24 18:16:54.616  5729  5729 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 18:16:54.616  5729  5745 D BluetoothAdapterProperties: Scan Mode:20
11-24 18:16:54.616  5729  5729 D BluetoothMapService: STATE_TURNING_OFF
11-24 18:16:54.617  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 18:16:54.621  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 18:16:54.621  5729  5729 D BluetoothMapService: MAP Service closeService in
11-24 18:16:54.621  5729  5729 D BluetoothMapMasInstance0: MAP Service shutdown
,11-24 18:16:54.621  5729  5729 D ObexServerSockets0: shutdown(block = true)
11-24 18:16:54.623  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:16:54.623  5548  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:16:54.623  5729  5767 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-24 18:16:54.625  5548  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 18:16:54.625  5548  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 18:16:54.627  5729  5729 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 18:16:54.628  5729  5729 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 18:16:54.628  5729  5754 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-24 18:16:54.628  5729  5768 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 18:16:54.628  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:54.630  5729  5729 D HeadsetService: Received stop request...Stopping profile...
11-24 18:16:54.632   932   932 D BluetoothHeadset: Proxy object disconnected
,11-24 18:16:54.633   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:54.633   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:54.633  3064  3903 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:54.635  5616  5628 D BluetoothHeadset: Proxy object disconnected
,11-24 18:16:54.636  3692  3728 D BluetoothHeadset: Proxy object disconnected
11-24 18:16:54.639  5729  5729 I BtOppRfcommListener: stopping Accept Thread
,11-24 18:16:54.639  5729  5778 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 18:16:54.640  5729  5778 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 18:16:54.642  3064  3064 D HeadsetProfile: Bluetooth service disconnected
11-24 18:16:54.642  5729  5729 D A2dpService: Received stop request...Stopping profile...
11-24 18:16:54.642  5729  5761 D A2dpStateMachine: Exit Disconnected: -1
,11-24 18:16:54.643  5616  5616 D DockEventReceiver: finishStartingService: stopping service
11-24 18:16:54.645   932   932 D BluetoothA2dp: Proxy object disconnected
,11-24 18:16:54.646  3064  3064 D BluetoothA2dp: Proxy object disconnected
,11-24 18:16:54.649  5729  5729 D HidService: Received stop request...Stopping profile...
,11-24 18:16:54.649  5729  5729 D HidService: Stopping Bluetooth HidService
11-24 18:16:54.651  5616  5616 D HeadsetProfile: Bluetooth service disconnected
11-24 18:16:54.651  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 18:16:54.651  3064  3064 D BluetoothInputDevice: Proxy object disconnected
11-24 18:16:54.651  3064  3064 D HidProfile: Bluetooth service disconnected
11-24 18:16:54.652  5616  5616 D BluetoothA2dp: Proxy object disconnected
,11-24 18:16:54.652  5729  5729 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:54.652  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:54.652  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.652  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.653  5616  5616 D BluetoothInputDevice: Proxy object disconnected
,11-24 18:16:54.653  5616  5616 D HidProfile: Bluetooth service disconnected
11-24 18:16:54.653  5729  5729 D HealthService: Received stop request...Stopping profile...
,11-24 18:16:54.658  5729  5729 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 18:16:54.658  5729  5729 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-24 18:16:54.658  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-24 18:16:54.658  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:54.658  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:54.658  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:54.658  5729  5745 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 18:16:54.659  5729  5729 D PanService: Received stop request...Stopping profile...
11-24 18:16:54.659  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 18:16:54.659  5616  5616 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 18:16:54.659  3064  3064 D PanProfile: Bluetooth service disconnected
11-24 18:16:54.659  5616  5616 D PanProfile: Bluetooth service disconnected
,11-24 18:16:54.660  5729  5729 D BluetoothMapService: Received stop request...Stopping profile...
11-24 18:16:54.660  5729  5729 D BluetoothMapService: stop()
11-24 18:16:54.660  5729  5729 D BluetoothMapAppObserver: deinitObservers()
11-24 18:16:54.661  5729  5729 D BluetoothMapAppObserver: removeReceiver()
11-24 18:16:54.662  3064  3064 D BluetoothMap: Proxy object disconnected
11-24 18:16:54.662  3064  3064 D MapProfile: Bluetooth service disconnected
11-24 18:16:54.663  5729  5729 D SapService: Received stop request...Stopping profile...
11-24 18:16:54.663  5729  5729 V SapService: stop()
11-24 18:16:54.664  5729  5729 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:54.665  5729  5729 V BluetoothAdapterState: isTurningOn()=false
,11-24 18:16:54.665  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.665  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.666  5616  5616 D BluetoothMap: Proxy object disconnected
11-24 18:16:54.666  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 18:16:54.666  5616  5616 D MapProfile: Bluetooth service disconnected
11-24 18:16:54.666  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:54.666  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:54.667  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 18:16:54.667  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 18:16:54.667  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 18:16:54.667  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-24 18:16:54.671  3064  3064 D BluetoothPbap: Proxy object disconnected
,11-24 18:16:54.671  3064  3064 D PbapServerProfile: Bluetooth service disconnected
,11-24 18:16:54.671  5729  5729 V BluetoothAdapterState: isTurningOff()=true
,11-24 18:16:54.672  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:54.672  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.672  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.672  5729  5729 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 18:16:54.672  5729  5729 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 18:16:54.673  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 18:16:54.673  5729  5729 V BluetoothAdapterState: isTurningOff()=true
,11-24 18:16:54.673  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:54.673  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.673  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.673  5729  5729 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 18:16:54.674  5729  5745 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 18:16:54.674  5729  5729 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 18:16:54.674  5729  5729 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:54.675  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:54.675  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.675  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.676  5729  5729 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 18:16:54.676  5729  5729 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 18:16:54.677  5616  5616 D BluetoothPbap: Proxy object disconnected
11-24 18:16:54.677  5616  5616 D PbapServerProfile: Bluetooth service disconnected
,11-24 18:16:54.679  5729  5729 D BluetoothMapService: MAP Service closeService in
11-24 18:16:54.679  5729  5729 V BluetoothAdapterState: isTurningOff()=true
,11-24 18:16:54.679  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:54.679  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.679  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.679  5729  5729 D BluetoothMapService: cleanup()
11-24 18:16:54.679  5729  5729 D BluetoothMapService: MAP Service closeService in
,11-24 18:16:54.680  5729  5729 V BluetoothAdapterState: isTurningOff()=true
11-24 18:16:54.680  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:54.680  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:16:54.680  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:16:54.680  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 18:16:54.680  5729  5741 D BluetoothAdapterProperties: Setting state to 15
11-24 18:16:54.680  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 18:16:54.681  5729  5741 I BluetoothAdapterState: Entering BleOnState
11-24 18:16:54.681  5616  5628 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 18:16:54.682  3064  3903 D BluetoothPan: onBluetoothStateChange on: false
11-24 18:16:54.682   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:54.682   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 18:16:54.683  5616  5626 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 18:16:54.684   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 18:16:54.684  5616  5628 D BluetoothMap: onBluetoothStateChange: up=false
11-24 18:16:54.685  3064  3076 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 18:16:54.686  3064  3075 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:54.686  5616  5626 D BluetoothPan: onBluetoothStateChange on: false
11-24 18:16:54.687  3064  3903 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 18:16:54.687   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 18:16:54.688  3064  3076 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 18:16:54.688  3064  3075 D BluetoothMap: onBluetoothStateChange: up=false
11-24 18:16:54.689  3692  3925 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:54.689  5616  5628 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 18:16:54.689  5616  5626 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 18:16:54.690  5729  5741 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 18:16:54.690  5729  5741 D BluetoothAdapterProperties: Setting state to 16
11-24 18:16:54.690  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 18:16:54.694  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 18:16:54.694  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:54.694  5729  5741 D BluetoothAdapterProperties: onBleDisable
11-24 18:16:54.695  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
11-24 18:16:54.695  5729  5742 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 18:16:54.695  5729  5752 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 18:16:54.695  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 18:16:54.697  5729  5745 D BluetoothAdapterProperties: Scan Mode:20
11-24 18:16:54.697  5548  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 18:16:54.699  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 18:16:54.702  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-24 18:16:54.914  5729  5745 I bt_hci  : shut_down
,11-24 18:16:54.919  5729  5749 D bt_hwcfg: hw_epilog_process
11-24 18:16:54.920  5729  5749 I bt_vendor: low_power_mode_cb
,11-24 18:16:54.923  5729  5749 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 18:16:54.923  5729  5749 I bt_vendor: epilog_cb
11-24 18:16:54.924  5729  5749 I bt_hci  : epilog_finished_callback
,11-24 18:16:54.930  5729  5745 I bt_hci_h4: hal_close
,11-24 18:16:54.931  5729  5745 I bt_userial_vendor: device fd = 54 close
,11-24 18:16:55.048  5729  5742 D bt_stack_manager: event_shut_down_stack finished.
,11-24 18:16:55.049  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 18:16:55.053  5729  5729 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 18:16:55.053  5729  5741 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 18:16:55.054  5729  5729 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 18:16:55.054  5729  5729 D BtGatt.GattService: stop()
,11-24 18:16:55.054  5729  5729 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 18:16:55.058  5729  5729 V BluetoothAdapterState: isTurningOff()=false
,11-24 18:16:55.058  5729  5729 V BluetoothAdapterState: isTurningOn()=false
11-24 18:16:55.058  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 18:16:55.058  5729  5729 V BluetoothAdapterState: isBleTurningOff()=true
11-24 18:16:55.059  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-24 18:16:55.059  5729  5741 D BluetoothAdapterProperties: Setting state to 10
11-24 18:16:55.059  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 18:16:55.061  5729  5741 I BluetoothAdapterState: Entering OffState
11-24 18:16:55.062   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 18:16:55.074  5729  5729 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 18:16:55.075  5729  5729 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 18:16:55.075  5729  5729 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 18:16:55.077  5729  5742 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 18:16:55.084  5729  5729 I art     : System.exit called, status: 0
,11-24 18:16:55.085  5729  5729 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 18:16:55.116   932  3814 I ActivityManager: Process com.android.bluetooth (pid 5729) has died
,11-24 18:16:58.031  3516  3516 I ConfigService: onDestroy
,11-24 18:16:59.605  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:59.605  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 18:16:59.613  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:59.613  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d647f75 removed from the list
,11-24 18:16:59.613  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:16:59.616  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:16:59.616  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cd3198 added. We now have 4 listener(s)
11-24 18:16:59.616  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:16:59.618  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:16:59.619  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cd3198 removed from the list
11-24 18:16:59.619  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:16:59.623  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:16:59.623  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80a9df1 added. We now have 4 listener(s)
,11-24 18:16:59.626  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:17:03.542   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:04.543   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:04.635  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:17:04.668   932   949 I ActivityManager: Start proc 5787:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 18:17:04.759  5787  5787 D AdapterServiceConfig: Adding HeadsetService
,11-24 18:17:04.760  5787  5787 D AdapterServiceConfig: Adding A2dpService
11-24 18:17:04.760  5787  5787 D AdapterServiceConfig: Adding HidService
11-24 18:17:04.760  5787  5787 D AdapterServiceConfig: Adding HealthService
,11-24 18:17:04.760  5787  5787 D AdapterServiceConfig: Adding PanService
,11-24 18:17:04.760  5787  5787 D AdapterServiceConfig: Adding GattService
11-24 18:17:04.761  5787  5787 D AdapterServiceConfig: Adding BluetoothMapService
11-24 18:17:04.761  5787  5787 D AdapterServiceConfig: Adding SapService
,11-24 18:17:04.771   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4bd2645:true
,11-24 18:17:04.771  5787  5787 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 18:17:04.774  5787  5787 I bt_bluedroid: init
,11-24 18:17:04.774  5787  5799 I BluetoothAdapterState: Entering OffState
,11-24 18:17:04.777  5787  5800 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 18:17:04.777  5787  5800 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 18:17:04.777  5787  5800 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 18:17:04.777  5787  5800 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 18:17:04.778  5787  5787 I bt_bluedroid: get_profile_interface socket
,11-24 18:17:04.779  5787  5787 I bt_bluedroid: get_profile_interface sdp
,11-24 18:17:04.780  5787  5803 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 18:17:04.781  5787  5803 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 18:17:04.785  5787  5798 I bt_bluedroid: config_hci_snoop_log
11-24 18:17:04.786   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 18:17:04.790  5787  5799 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 18:17:04.790  5787  5799 D BluetoothAdapterProperties: Setting state to 14
11-24 18:17:04.790  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 18:17:04.792  5787  5799 D BluetoothBondStateMachine: make
,11-24 18:17:04.794  5787  5804 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 18:17:04.796  5787  5799 I BluetoothAdapterState: Entering PendingCommandState
,11-24 18:17:04.797  5787  5787 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-24 18:17:04.799  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:17:04.800  5787  5787 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 18:17:04.800  5787  5787 D BtGatt.GattService: Received start request. Starting profile...
11-24 18:17:04.800  5787  5787 D BtGatt.GattService: start()
11-24 18:17:04.800  5787  5787 I bt_bluedroid: get_profile_interface gatt
,11-24 18:17:04.801  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:17:04.801  5787  5787 D BtGatt.AdvertiseManager: advertise manager created
,11-24 18:17:04.807  5787  5787 V BluetoothAdapterState: isTurningOff()=false
11-24 18:17:04.807  5787  5787 V BluetoothAdapterState: isTurningOn()=false
11-24 18:17:04.807  5787  5787 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 18:17:04.807  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:04.807  5787  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 18:17:04.809  5787  5799 I bt_bluedroid: bt_bluedroid
,11-24 18:17:04.809  5787  5800 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 18:17:04.810  5787  5800 I bt_hci  : start_up
,11-24 18:17:04.815  5787  5800 I bt_vendor: alloc value 0xf3cab871
,11-24 18:17:04.815  5787  5800 I bt_vendor: init
11-24 18:17:04.815  5787  5800 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 18:17:04.815  5787  5800 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 18:17:04.927  5787  5800 D bt_hci  : start_up starting async portion
,11-24 18:17:04.928  5787  5807 I bt_hci  : event_finish_startup
11-24 18:17:04.928  5787  5807 I bt_hci_h4: hal_open
11-24 18:17:04.928  5787  5807 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 18:17:04.927  5808  5808 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 18:17:04.932  5787  5807 I bt_userial_vendor: device fd = 54 open
,11-24 18:17:04.949  5787  5807 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 18:17:04.952  5787  5807 D bt_hwcfg: Chipset BCM4358A3
,11-24 18:17:04.953  5787  5807 D bt_hwcfg: Target name = [BCM4358A3]
11-24 18:17:04.953  5787  5807 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 18:17:05.456  5787  5807 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 18:17:05.457  5787  5807 D bt_hwcfg: Settlement delay -- 100 ms
11-24 18:17:05.457  5787  5807 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 18:17:05.545   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:05.591  5787  5807 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 18:17:05.591  5787  5807 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 18:17:05.593  5787  5807 I bt_hwcfg: vendor lib fwcfg completed
,11-24 18:17:05.593  5787  5807 I bt_vendor: firmware callback
,11-24 18:17:05.621  5787  5807 I bt_hci  : firmware_config_callback
,11-24 18:17:05.629  5787  5810 I bt_btu  : btu_task pending for preload complete event
,11-24 18:17:05.629  5787  5810 I bt_btu_task: Bluetooth chip preload is complete
,11-24 18:17:05.629  5787  5810 I bt_btu  : btu_task received preload complete event
,11-24 18:17:05.635  5787  5810 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 18:17:05.635  5787  5810 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 18:17:05.635  5787  5810 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-24 18:17:05.635  5787  5810 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 18:17:05.635  5787  5810 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 18:17:05.635  5787  5810 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 18:17:05.636  5787  5810 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 18:17:05.637  5787  5810 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 18:17:05.734  5787  5810 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c29549
,11-24 18:17:05.734  5787  5810 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c29549 
,11-24 18:17:05.767  5787  5803 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 18:17:05.769  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 18:17:05.770  5787  5803 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 18:17:05.773  5787  5803 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 18:17:05.776  5787  5803 D BluetoothAdapterProperties: Scan Mode:20
,11-24 18:17:05.777  5787  5803 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 18:17:05.778  5787  5803 D bt_hci  : do_postload posting postload work item
,11-24 18:17:05.778  5787  5807 I bt_hci  : event_postload
,11-24 18:17:05.778  5787  5807 I bt_vendor: sco_config_cb
11-24 18:17:05.778  5787  5807 I bt_hci  : sco_config_callback postload finished.
11-24 18:17:05.780  5787  5803 D bt_bte_conf: Device ID record 1 : primary
11-24 18:17:05.780  5787  5803 D bt_bte_conf:   vendorId            = 000f
11-24 18:17:05.780  5787  5803 D bt_bte_conf:   vendorIdSource      = 0001
11-24 18:17:05.781  5787  5803 D bt_bte_conf:   product             = 1200
,11-24 18:17:05.781  5787  5803 D bt_bte_conf:   version             = 1436
11-24 18:17:05.781  5787  5803 D bt_bte_conf:   clientExecutableURL = 
11-24 18:17:05.781  5787  5803 D bt_bte_conf:   serviceDescription  = 
11-24 18:17:05.781  5787  5803 D bt_bte_conf:   documentationURL    = 
11-24 18:17:05.782  5787  5803 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 18:17:05.782  5787  5800 D bt_stack_manager: event_start_up_stack finished
,11-24 18:17:05.783  5787  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 18:17:05.783  5787  5799 D BluetoothAdapterProperties: Setting state to 15
11-24 18:17:05.783  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 18:17:05.785  5787  5799 I BluetoothAdapterState: Entering BleOnState
,11-24 18:17:05.790  5787  5807 I bt_vendor: low_power_mode_cb
,11-24 18:17:05.792  5787  5799 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 18:17:05.792  5787  5799 D BluetoothAdapterProperties: Setting state to 11
11-24 18:17:05.792  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 18:17:05.800  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:17:05.802  5787  5787 D HeadsetService: Received start request. Starting profile...
11-24 18:17:05.805  5787  5787 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 18:17:05.805  5787  5787 D HeadsetStateMachine: make
,11-24 18:17:05.819  5787  5799 I BluetoothAdapterState: Entering PendingCommandState
,11-24 18:17:05.821  5787  5787 D HeadsetStateMachine: max_hf_connections = 1
,11-24 18:17:05.821  5787  5787 I bt_bluedroid: get_profile_interface handsfree
11-24 18:17:05.821  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 18:17:05.822  5787  5803 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 18:17:05.825  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:17:05.826  5787  5787 D A2dpService: Received start request. Starting profile...
,11-24 18:17:05.826  5787  5787 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-24 18:17:05.827  5787  5787 I bt_bluedroid: get_profile_interface avrcp
,11-24 18:17:05.836  5787  5787 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 18:17:05.836  5787  5787 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 18:17:05.836  5787  5787 D A2dpStateMachine: make
,11-24 18:17:05.838  5787  5787 I bt_bluedroid: get_profile_interface a2dp
11-24 18:17:05.839  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 18:17:05.841  5787  5787 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 18:17:05.842  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:17:05.843  5787  5787 D HidService: Received start request. Starting profile...
11-24 18:17:05.843  5787  5817 D A2dpStateMachine: Enter Disconnected: -2
11-24 18:17:05.844  5787  5787 I bt_bluedroid: get_profile_interface hidhost
11-24 18:17:05.844  5787  5787 D HidService: setHidService(): set to: null
11-24 18:17:05.844  5787  5803 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0a56d
11-24 18:17:05.844  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 18:17:05.846  5787  5787 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-24 18:17:05.848  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:17:05.848  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 18:17:05.848  5787  5787 D HealthService: Received start request. Starting profile...
,11-24 18:17:05.851  5787  5787 I bt_bluedroid: get_profile_interface health
11-24 18:17:05.851  5787  5787 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 18:17:05.852  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:17:05.853  5787  5787 D PanService: Received start request. Starting profile...
11-24 18:17:05.853  5787  5787 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 18:17:05.853  5787  5787 I bt_bluedroid: get_profile_interface pan
11-24 18:17:05.853  5787  5803 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 18:17:05.855  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 18:17:05.856  5787  5787 D BluetoothMapService: Received start request. Starting profile...
11-24 18:17:05.856  5787  5787 D BluetoothMapService: start()
,11-24 18:17:05.859  5787  5787 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 18:17:05.859  5787  5787 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 18:17:05.860  5787  5787 D BluetoothMapAppObserver: createReceiver()
11-24 18:17:05.861  5787  5787 D BluetoothMapAppObserver: initObservers()
,11-24 18:17:05.861  5787  5787 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 18:17:05.868  5787  5787 V SapService: SapBinder()
11-24 18:17:05.868  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:17:05.869  5787  5787 D SapService: Received start request. Starting profile...
11-24 18:17:05.869  5787  5787 V SapService: start()
,11-24 18:17:05.871  5787  5787 V BluetoothAdapterState: isTurningOff()=false
,11-24 18:17:05.871  5787  5787 V BluetoothAdapterState: isTurningOn()=true
11-24 18:17:05.871  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:17:05.871  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:05.871  5787  5815 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 18:17:05.871  5787  5787 V BluetoothAdapterState: isTurningOff()=false
11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isTurningOn()=true
,11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isTurningOff()=false
11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isTurningOn()=true
11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:17:05.872  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:05.873  5787  5787 V BluetoothAdapterState: isTurningOff()=false
11-24 18:17:05.873  5787  5787 V BluetoothAdapterState: isTurningOn()=true
,11-24 18:17:05.873  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:17:05.873  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 18:17:05.873  5787  5787 V BluetoothAdapterState: isTurningOff()=false
,11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isTurningOn()=true
11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isTurningOff()=false
11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isTurningOn()=true
11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
11-24 18:17:05.874  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:05.875  5787  5787 V BluetoothAdapterState: isTurningOff()=false
11-24 18:17:05.875  5787  5787 V BluetoothAdapterState: isTurningOn()=true
11-24 18:17:05.875  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 18:17:05.875  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
11-24 18:17:05.875  5787  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 18:17:05.875  5787  5799 D BluetoothAdapterProperties: ScanMode =  20
11-24 18:17:05.875  5787  5799 D BluetoothAdapterProperties: State =  11
11-24 18:17:05.876  5787  5799 D BluetoothAdapterProperties: Setting state to 12
11-24 18:17:05.876  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 18:17:05.876  5787  5799 I BluetoothAdapterState: Entering OnState
11-24 18:17:05.877  5787  5803 D BluetoothAdapterProperties: Scan Mode:21
11-24 18:17:05.877  5616  5626 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 18:17:05.877  5787  5803 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 18:17:05.882  3064  3075 D BluetoothPan: onBluetoothStateChange on: true
,11-24 18:17:05.887  5787  5787 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 18:17:05.888   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:17:05.888  5787  5787 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 18:17:05.888   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:17:05.888  5616  5628 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 18:17:05.889   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 18:17:05.891  5616  5626 D BluetoothMap: onBluetoothStateChange: up=true
11-24 18:17:05.891  5787  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:17:05.893  3064  3076 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 18:17:05.894  5787  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:17:05.894  3064  3903 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:17:05.895  5616  5628 D BluetoothPan: onBluetoothStateChange on: true
11-24 18:17:05.895  5787  5787 D ObexServerSockets: Succeed to create listening sockets 
11-24 18:17:05.895  5787  5787 D ObexServerSockets0: startAccept()
11-24 18:17:05.895  5787  5787 D ObexServerSockets0: prepareForNewConnect()
,11-24 18:17:05.896  3064  3075 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 18:17:05.898  5787  5787 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 18:17:05.898  5787  5822 D ObexServerSockets0: Accepting socket connection...
11-24 18:17:05.898  5787  5787 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 18:17:05.899  5787  5823 D ObexServerSockets0: Accepting socket connection...
,11-24 18:17:05.899   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 18:17:05.900  3064  3076 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 18:17:05.900  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 18:17:05.900  3064  3064 D PanProfile: Bluetooth service connected
11-24 18:17:05.901  3064  3064 D BluetoothInputDevice: Proxy object connected
11-24 18:17:05.901  3064  3064 D HidProfile: Bluetooth service connected
11-24 18:17:05.902   932   932 D BluetoothA2dp: Proxy object connected
11-24 18:17:05.903  3064  3076 D BluetoothMap: onBluetoothStateChange: up=true
11-24 18:17:05.904  3064  3064 D BluetoothA2dp: Proxy object connected
,11-24 18:17:05.905  3692  3925 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:17:05.905  5616  5628 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 18:17:05.906  5616  5626 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 18:17:05.906  3064  3064 D BluetoothMap: Proxy object connected
11-24 18:17:05.906  3064  3064 D MapProfile: Bluetooth service connected
11-24 18:17:05.906  3064  3064 D BluetoothMap: getConnectedDevices()
11-24 18:17:05.908  5616  5616 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 18:17:05.908  5616  5616 D PanProfile: Bluetooth service connected
11-24 18:17:05.908  5616  5616 D BluetoothInputDevice: Proxy object connected
11-24 18:17:05.908  5616  5616 D HidProfile: Bluetooth service connected
11-24 18:17:05.909   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 18:17:05.909  5787  5787 D BluetoothMapService: onReceive
11-24 18:17:05.909  5787  5787 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 18:17:05.909  5787  5787 D BluetoothMapService: STATE_ON
,11-24 18:17:05.911  5616  5616 D BluetoothMap: Proxy object connected
11-24 18:17:05.911  5616  5616 D MapProfile: Bluetooth service connected
11-24 18:17:05.911  5616  5616 D BluetoothMap: getConnectedDevices()
11-24 18:17:05.912  5787  5826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 18:17:05.913  5787  5826 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 18:17:05.914  5787  5826 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 18:17:05.915  5616  5616 D BluetoothA2dp: Proxy object connected
,11-24 18:17:05.920  5616  5616 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 18:17:05.926  5616  5616 D DockEventReceiver: finishStartingService: stopping service
,11-24 18:17:05.926  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 18:17:05.934  5616  5616 D BluetoothPbap: Proxy object connected
11-24 18:17:05.934  5616  5616 D PbapServerProfile: Bluetooth service connected
11-24 18:17:05.934  3064  3064 D BluetoothPbap: Proxy object connected
11-24 18:17:05.934  3064  3064 D PbapServerProfile: Bluetooth service connected
,11-24 18:17:05.935  5787  5787 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 18:17:05.935  5787  5787 D ObexServerSockets0: prepareForNewConnect()
,11-24 18:17:05.944  5787  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 18:17:05.956  5787  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 18:17:05.957  5787  5835 I BtOppRfcommListener: Accept thread started.
,11-24 18:17:05.990   932   932 D BluetoothHeadset: Proxy object connected
,11-24 18:17:05.990   932   932 D BluetoothHeadset: Proxy object connected
11-24 18:17:05.990   932   932 D BluetoothHeadset: Proxy object connected
11-24 18:17:05.990  3064  3076 D BluetoothHeadset: Proxy object connected
11-24 18:17:05.991  3064  3064 D HeadsetProfile: Bluetooth service connected
,11-24 18:17:05.991  5616  5628 D BluetoothHeadset: Proxy object connected
,11-24 18:17:05.992  3692  3712 D BluetoothHeadset: Proxy object connected
,11-24 18:17:05.994  5616  5616 D HeadsetProfile: Bluetooth service connected
,11-24 18:17:05.995  3064  3075 D BluetoothHeadset: Proxy object connected
11-24 18:17:05.995  3064  3064 D HeadsetProfile: Bluetooth service connected
,11-24 18:17:05.999   932   949 D BluetoothHeadset: Proxy object connected
,11-24 18:17:06.006  3692  3931 D BluetoothHeadset: Proxy object connected
,11-24 18:17:06.006  5616  5626 D BluetoothHeadset: Proxy object connected
,11-24 18:17:06.007  5616  5616 D HeadsetProfile: Bluetooth service connected
,11-24 18:17:06.546   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:07.547   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:08.548   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:17:09.651  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:17:09.657  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 18:17:09.658  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:09.658  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80a9df1 removed from the list
11-24 18:17:09.658  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:17:09.660  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:17:09.661  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20addd6 added. We now have 4 listener(s)
11-24 18:17:09.661  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:17:09.667   932  3084 D WifiService: setWifiEnabled: false pid=5548, uid=10077
,11-24 18:17:09.667   932  3084 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 18:17:13.549   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:14.550   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:14.677  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 18:17:14.678   932  3351 D WifiService: setWifiEnabled: true pid=5548, uid=10077
,11-24 18:17:14.679   932  3351 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 18:17:14.688   508   925 D SoftapController: Softap fwReload - Ok
,11-24 18:17:14.694   508   925 D CommandListener: Setting iface cfg
,11-24 18:17:14.694   508   925 D CommandListener: Trying to bring down wlan0
,11-24 18:17:14.696   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 18:17:14.700   932  2895 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 18:17:15.376   932  2895 D wifi    : set interface wlan0 flags (UP)
11-24 18:17:15.377   932  2895 I WifiHAL : Initializing wifi
,11-24 18:17:15.377   932  2895 I WifiHAL : Creating socket
,11-24 18:17:15.384   932  2895 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 18:17:15.384   932  2895 D wifi    : Did set static halHandle = 0x7f92f44d00
,11-24 18:17:15.384   932  2895 D wifi    : halHandle = 0x7f92f44d00, mVM = 0x7faf58d140, mCls = 0x190a
11-24 18:17:15.385   932  2895 D wifi    : array field set
11-24 18:17:15.385   932  2895 I WifiNative-HAL: interface[0] = wlan0
11-24 18:17:15.387   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 18:17:15.389   932  5840 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547926330624
11-24 18:17:15.389   932  5840 D wifi    : waitForHalEvents called, vm = 0x7faf58d140, obj = 0x190a, env = 0x7f981d8300
,11-24 18:17:15.451  5841  5841 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 18:17:15.493   932  2895 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 18:17:15.494   932  2895 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-24 18:17:15.518  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 18:17:15.551   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:15.574  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 18:17:15.574  5841  5841 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 18:17:16.506   932  2895 D WifiConfigStore: Loading config and enabling all networks ,
,11-24 18:17:16.542   932  2895 D WifiConfigStore: loaded 0 passpoint configs
,11-24 18:17:16.543   932  2895 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-24 18:17:16.544   932  2895 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 18:17:16.545   932  2895 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 18:17:16.545   932  2895 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 18:17:16.546   932  2895 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 18:17:16.547   932  2895 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 18:17:16.548   932  2895 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-24 18:17:16.548   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 18:17:16.548   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-24 18:17:16.548   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 18:17:16.548   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 18:17:16.548   932  2895 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-24 18:17:16.552   536   536 I ServiceManager: Waiting for service AtCmdFwd...
11-24 18:17:16.552   932  2895 D WifiNative-HAL: Setting external_sim to 1
,11-24 18:17:16.553  4934  4934 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 18:17:16.553   932  2895 D wifi    : setting dfs flag to true, 0x7f93e6c780
11-24 18:17:16.554   932  2895 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 18:17:16.554   932  2895 D wifi    : setting scan oui 0x7f93e6c780
11-24 18:17:16.554   932  2895 D WifiHAL : Sending mac address OUI
,11-24 18:17:16.558   932  2895 E native  : do suspend false
,11-24 18:17:16.569   932  2895 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 18:17:16.569   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 18:17:16.569   932   932 D RttService: SCAN_AVAILABLE : 3
11-24 18:17:16.569   932  3006 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 18:17:16.570   508   925 D CommandListener: Setting iface cfg
,11-24 18:17:16.575   932  2867 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-24 18:17:16.575   932  2867 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 18:17:16.585   932  2867 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 18:17:16.590   932  2867 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 18:17:16.591   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=242043 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-24 18:17:17.553   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:18.554   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 18:17:19.658  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 18:17:19.662  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 18:17:19.666  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 18:17:19.694  5548  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 18:17:19.696  5548  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 18:17:19.697  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:17:19.698  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20addd6 removed from the list
11-24 18:17:19.698  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:17:19.702  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 18:17:19.703  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 18:17:19.706  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f77040a Bundle[{}]
,11-24 18:17:19.707  5548  5595 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 18:17:19.708  5548  5595 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-24 18:17:19.709  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 18:17:19.710  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 18:17:19.711  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 18:17:19.712  5548  5595 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 18:17:19.720  5548  5595 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-24 18:17:19.721  5548  5595 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 18:17:19.721  5548  5595 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-24 18:17:19.723  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.723  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bbd857 added. We now have 3 listener(s)
,11-24 18:17:19.723   932  2895 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 18:17:19.725   932  2895 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 18:17:19.725  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.725   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 18:17:19.725  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.726  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.726  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:17:19.726  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fcf44 added. We now have 4 listener(s)
,11-24 18:17:19.726  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.728  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 18:17:19.730  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.730  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51a282d added. We now have 4 listener(s)
11-24 18:17:19.732  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.732  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 18:17:19.732  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.732  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.733  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42f0162 added. We now have 5 listener(s)
11-24 18:17:19.733  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.733  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:17:19.733  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 18:17:19.733  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:17:19.734  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.734  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.734  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.734  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bbd857 removed from the list
11-24 18:17:19.734  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.734  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fcf44 removed from the list
11-24 18:17:19.734  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 18:17:19.734  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.734  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.736  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.737  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.737  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.737  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.737  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.737  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.737  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fcf44 not in the list
11-24 18:17:19.737  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.737  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.738   932  2895 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 18:17:19.738  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.738  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.739  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.739  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.739  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.739  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 18:17:19.739  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42f0162 removed from the list
11-24 18:17:19.739  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.739  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.739  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.739  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51a282d removed from the list
11-24 18:17:19.740  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.740  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3ba2f3 added. We now have 3 listener(s)
,11-24 18:17:19.742  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.742  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.742  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.742  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.742  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc9bb0 added. We now have 4 listener(s)
11-24 18:17:19.742  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:17:19.743  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 18:17:19.744  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.744  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1e1a29 added. We now have 4 listener(s)
,11-24 18:17:19.745  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 18:17:19.746  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.746  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.746  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.746  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fd1ae added. We now have 5 listener(s)
11-24 18:17:19.746  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 18:17:19.746  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:19.746  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 18:17:19.746  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 18:17:19.746  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:17:19.747  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 18:17:19.748  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 18:17:19.750  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 18:17:19.750  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 18:17:19.750  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 18:17:19.753  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.753  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 18:17:19.754  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 18:17:19.754  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 18:17:19.754  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 18:17:19.756  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.757  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 18:17:19.757  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 18:17:19.757  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 18:17:19.757  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-24 18:17:19.757  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.758  5548  5595 D BluetoothAdapter: STATE_ON
,11-24 18:17:19.760  5787  5825 D BtGatt.GattService: registerClient() - UUID=e7062c00-ac38-4851-83b0-e4ed7e2feb03
,11-24 18:17:19.761  5787  5803 D BtGatt.GattService: onClientRegistered() - UUID=e7062c00-ac38-4851-83b0-e4ed7e2feb03, clientIf=5
,11-24 18:17:19.761  5548  5558 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 18:17:19.762  5787  5827 D BtGatt.GattService: start scan with filters
,11-24 18:17:19.766  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 18:17:19.766  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.766  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 18:17:19.766  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.766  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 18:17:19.766  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 18:17:19.766  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 18:17:19.767  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 18:17:19.767  5787  5806 D BtGatt.ScanManager: handling starting scan
11-24 18:17:19.767  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 18:17:19.767  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 18:17:19.767  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.767  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.767  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.767  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.768  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.768  5787  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 18:17:19.768  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.768  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.768  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.768  5548  5595 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-24 18:17:19.768  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.768  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 18:17:19.768  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:17:19.769   932  2895 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 18:17:19.772  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.772  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:17:19.772  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 18:17:19.772  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.773  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 18:17:19.774  5787  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 18:17:19.774  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.775  5787  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 18:17:19.775  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:17:19.775  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:17:19.775  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 18:17:19.775  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.775  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.775  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.775  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.775  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.775  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3ba2f3 removed from the list
11-24 18:17:19.775  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.775  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc9bb0 removed from the list
11-24 18:17:19.776  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:17:19.776  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.776  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.776  5841  5841 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-24 18:17:19.776  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.776  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.776  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 18:17:19.776  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.776  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.776  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.777  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.777  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.777  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.777  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.777  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.777  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.777  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc9bb0 not in the list
11-24 18:17:19.777  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 18:17:19.777  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.777  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:17:19.778  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:17:19.778  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.778  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.778  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.778  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 18:17:19.778  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.780  5548  5595 D BluetoothAdapter: STATE_ON
,11-24 18:17:19.780  5787  5825 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 18:17:19.781  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 18:17:19.781  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:17:19.781  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 18:17:19.781  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.782  5787  5798 D BtGatt.GattService: stopScan() - queue size =1
11-24 18:17:19.782  5787  5806 D BtGatt.ScanManager: Starting BLE batch scan
11-24 18:17:19.782  5787  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 18:17:19.782  5787  5824 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.783  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 18:17:19.783  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 18:17:19.784  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:17:19.785  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.786  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.786  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:17:19.786  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.786  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.786  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.786  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.786  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.786  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:17:19.786  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fd1ae removed from the list
11-24 18:17:19.787  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:17:19.787  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.787  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.787  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 18:17:19.787  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.787  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.787  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1e1a29 removed from the list
11-24 18:17:19.787  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 18:17:19.787  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 18:17:19.787  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.787  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.787  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.787  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:17:19.788  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.788  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.788  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.788  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e867d6b added. We now have 3 listener(s)
11-24 18:17:19.789  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.789  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.789  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.789  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.789  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.789  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 18:17:19.789  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.790  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53c30c8 added. We now have 4 listener(s)
11-24 18:17:19.790  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.790  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 18:17:19.792  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 18:17:19.792  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42de561 added. We now have 4 listener(s)
11-24 18:17:19.793  5787  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 18:17:19.793  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.793  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.793  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.793  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.793  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 18:17:19.793  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d746886 added. We now have 5 listener(s)
11-24 18:17:19.793  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.794  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:19.794  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:19.794  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 18:17:19.794  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 18:17:19.794  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 18:17:19.794  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 18:17:19.795  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 18:17:19.798  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 18:17:19.798  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.798  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 18:17:19.798  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 18:17:19.798  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 18:17:19.800  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 18:17:19.802  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.802  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 18:17:19.803  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 18:17:19.803  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 18:17:19.803  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 18:17:19.804  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 18:17:19.805  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.805  5787  5803 E BtGatt.ContextMap: Context not found for ID 5
,11-24 18:17:19.807  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.807  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 18:17:19.807  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 18:17:19.807  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 18:17:19.807  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 18:17:19.807  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.809  5548  5595 D BluetoothAdapter: STATE_ON
,11-24 18:17:19.811  5787  5827 D BtGatt.GattService: registerClient() - UUID=57472d6b-2c38-4d5e-ac3e-28dfb028350e
,11-24 18:17:19.811  5787  5803 D BtGatt.GattService: onClientRegistered() - UUID=57472d6b-2c38-4d5e-ac3e-28dfb028350e, clientIf=5
,11-24 18:17:19.811  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 18:17:19.811  5548  5558 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 18:17:19.812  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.812  5787  5806 D BtGatt.ScanManager: stopping BLe Batch
11-24 18:17:19.812  5787  5798 D BtGatt.GattService: start scan with filters
,11-24 18:17:19.814  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 18:17:19.815  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.815  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 18:17:19.815  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.815  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 18:17:19.815  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 18:17:19.815  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.815  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 18:17:19.815  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 18:17:19.815  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.815  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.815  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.815  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.816  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 18:17:19.816  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.817  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 18:17:19.817  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.817  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:17:19.818  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.818  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:17:19.818  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 18:17:19.818  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.818  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.818  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:19.818  5548  5595 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 18:17:19.818  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:17:19.818  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:17:19.818  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:17:19.818  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.818  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.818  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 18:17:19.818  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.818  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.818  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e867d6b removed from the list
11-24 18:17:19.818  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.819  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53c30c8 removed from the list
11-24 18:17:19.819  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:17:19.819  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.819  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.819  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.819  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-24 18:17:19.819  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 18:17:19.819  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.819  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.819  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.820  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.820  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.820  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.820  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.821  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.821  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.821  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53c30c8 not in the list
11-24 18:17:19.821  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:17:19.821  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 18:17:19.821  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.821  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 18:17:19.821  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.822  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:17:19.822  5787  5824 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 18:17:19.822  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 18:17:19.822  5787  5806 D BtGatt.ScanManager: handling starting scan
11-24 18:17:19.823  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:17:19.823  5787  5797 D BtGatt.GattService: stopScan() - queue size =1
11-24 18:17:19.824  5787  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.Bl,ePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.824  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 18:17:19.824  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 18:17:19.825  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:17:19.825  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.826  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.826  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:17:19.826  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.826  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.826  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.826  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.827  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.827  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:17:19.827  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:17:19.827  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d746886 removed from the list
11-24 18:17:19.827  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 18:17:19.827  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.827  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.827  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.827  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 18:17:19.827  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 18:17:19.827  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.827  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluet,ooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.827  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42de561 removed from the list
11-24 18:17:19.827  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.827  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.827  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:17:19.828  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.828  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.828  5787  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 18:17:19.828  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.828  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.828  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e132ee3 added. We now have 3 listener(s)
11-24 18:17:19.828  5787  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 18:17:19.829  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.829  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.829  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.829  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.830  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.830  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.830  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.830  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0650e0 added. We now have 4 listener(s)
11-24 18:17:19.830  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.831  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 18:17:19.832  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.832  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@594df99 added. We now have 4 listener(s)
11-24 18:17:19.833  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 18:17:19.833  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.833  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.834  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.834  5787  5806 D BtGatt.ScanManager: Starting BLE batch scan
11-24 18:17:19.834  5787  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 18:17:19.834  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.834  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.834  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5da025e added. We now have 5 listener(s)
11-24 18:17:19.834  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.834  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:19.834  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 18:17:19.834  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 18:17:19.834  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 18:17:19.835  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 18:17:19.836  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 18:17:19.838  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 18:17:19.838  5548  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 18:17:19.838  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 18:17:19.842  5787  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 18:17:19.842  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.842  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.842  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 18:17:19.843  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 18:17:19.843  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 18:17:19.843  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 18:17:19.846  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.846  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 18:17:19.846  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 18:17:19.846  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 18:17:19.846  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 18:17:19.846  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.847  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 18:17:19.847  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:17:19.847  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.848  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:17:19.849  5787  5827 D BtGatt.GattService: registerClient() - UUID=27ca514c-dfe8-4ddd-b0e2-2a7cbf9cb89a
11-24 18:17:19.850  5787  5803 D BtGatt.GattService: onClientRegistered() - UUID=27ca514c-dfe8-4ddd-b0e2-2a7cbf9cb89a, clientIf=5
11-24 18:17:19.850  5548  5558 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 18:17:19.850  5787  5798 D BtGatt.GattService: start scan with filters
11-24 18:17:19.852  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 18:17:19.853  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 18:17:19.853  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.853  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 18:17:19.853  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.853  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.853  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 18:17:19.853  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 18:17:19.853  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.853  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 18:17:19.853  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 18:17:19.853  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.853  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.853  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.853  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.854  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 18:17:19.854  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.856  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.856  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:17:19.856  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.856  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.856  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.858  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 18:17:19.858  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.859  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.859  5787  5806 D BtGatt.ScanManager: stopping BLe Batch
11-24 18:17:19.859  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.859  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.859  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.859  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 18:17:19.859  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:17:19.860  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:17:19.860  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:17:19.860  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.860  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.860  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.860  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e132ee3 removed from the list
11-24 18:17:19.860  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.860  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0650e0 removed from the list
11-24 18:17:19.860  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:17:19.860  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.860  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 18:17:19.860  5548  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 18:17:19.860  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.861  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.862  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.862  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.862  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0650e0 not in the list
11-24 18:17:19.862  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.862  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 18:17:19.862  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.863  5548  5595 D BluetoothAdapter: STATE_ON
11-24 18:17:19.863  5787  5824 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 18:17:19.863  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 18:17:19.863  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.863  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 18:17:19.863  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:17:19.864  5548  5595 D BluetoothAdapter: STATE_ON
,11-24 18:17:19.864  5787  5827 D BtGatt.GattService: stopScan() - queue size =0
11-24 18:17:19.865  5787  5825 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.865  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 18:17:19.866  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 18:17:19.866  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 18:17:19.866  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.867  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.867  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:17:19.867  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 18:17:19.867  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.867  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.867  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.867  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.867  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.868  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.868  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:17:19.868  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5da025e removed from the list
11-24 18:17:19.868  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 18:17:19.868  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.868  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.868  5548  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@594df99 removed from the list
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 18:17:19.868  5548  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.868  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.868  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a65975b added. We now have 3 listener(s)
11-24 18:17:19.869  5787  5806 D BtGatt.ScanManager: handling starting scan
11-24 18:17:19.869  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.869  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.869  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.869  5548  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 18:17:19.869  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.869  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.869  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.870  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc15bf8 added. We now have 4 listener(s)
11-24 18:17:19.870  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.870  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 18:17:19.871  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 18:17:19.871  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@229e8d1 added. We now have 4 listener(s)
11-24 18:17:19.872  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 18:17:19.872  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 18:17:19.872  5548  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 18:17:19.872  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 18:17:19.872  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36dff36 added. We now have 5 listener(s)
11-24 18:17:19.872  5548  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 18:17:19.872  5548  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 18:17:19.872  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 18:17:19.873  5548  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 18:17:19.873  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.873  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.873  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.873  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a65975b removed from the list
11-24 18:17:19.873  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.873  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc15bf8 removed from the list
11-24 18:17:19.873  5548  5595 D io.jxcore.node.ConnectivityMonitor: stop
11-24 18:17:19.873  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.873  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.874  5787  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 18:17:19.874  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.874  5787  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 18:17:19.874  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.874  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.874  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.874  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.874  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.875  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.875  5548  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc15bf8 not in the list
11-24 18:17:19.875  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.875  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.876  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.876  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.876  5548  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 18:17:19.876  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 18:17:19.876  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 18:17:19.876  5548  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 18:17:19.876  5548  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36dff36 removed from the list
11-24 18:17:19.876  5548  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 18:17:19.876  5548  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 18:17:19.876  5548  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 18:17:19.876  5548  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@229e8d1 removed from the list
11-24 18:17:19.877  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 18:17:19.877  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 18:17:19.877  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 18:17:19.877  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:19.877  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 18:17:19.878  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 18:17:19.879  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 18:17:19.880  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.880  5787  5806 D BtGatt.ScanManager: Starting BLE batch scan
11-24 18:17:19.880  5787  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 18:17:19.887  5787  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 18:17:19.887  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.891  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 18:17:19.892  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.893  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 18:17:19.897  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 18:17:19.897  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.897  5787  5803 E BtGatt.ContextMap: Context not found for ID 5
11-24 18:17:19.902  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 18:17:19.902  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.902  5787  5806 D BtGatt.ScanManager: stopping BLe Batch
11-24 18:17:19.906  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 18:17:19.906  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 18:17:19.906  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 18:17:19.911  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 18:17:19.911  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 18:17:20.191  5841  5841 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 18:17:20.219  5841  5841 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 18:17:20.219  5841  5841 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 18:17:20.225   932  2895 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 18:17:20.225   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 18:17:20.225   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 18:17:20.243   932  2895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 18:17:20.254   508   925 D CommandListener: Setting iface cfg
,11-24 18:17:20.260   932  2895 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 18:17:20.265   932  5846 D DhcpClient: Receive thread started
,11-24 18:17:20.270   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 18:17:20.270   932  2895 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 18:17:20.270   932  2908 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 18:17:20.287  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 18:17:20.327  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 18:17:20.351   932  2895 E native  : do suspend false
,11-24 18:17:20.363   932  5845 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 18:17:20.369  5548  5548 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 18:17:20.377   932  5846 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-24 18:17:20.377   932  5845 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-24 18:17:20.379   932  5845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 18:17:20.391   932  5846 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 18:17:20.391   932  5845 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 18:17:20.394   508   925 D CommandListener: Setting iface cfg
,11-24 18:17:20.398   932  2895 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-24 18:17:20.401   932  5845 D DhcpClient: Scheduling renewal in 86399s
,11-24 18:17:20.414   932  2895 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 18:17:20.415   932  2895 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 18:17:20.416   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 18:17:20.421   932  2908 D ConnectivityService: Adding iface wlan0 to network 102
,11-24 18:17:20.427   932  2895 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 18:17:20.463   932  2908 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 18:17:20.463   932  2908 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 18:17:20.465   932  2908 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 18:17:20.466   932  2908 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 18:17:20.468   932  2908 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 18:17:20.476   932  2908 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 18:17:20.481   932  2908 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 18:17:20.481   932  2908 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 18:17:20.481   932  2908 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 18:17:20.481   932  2908 D ConnectivityService:    accepting network in place of null
11-24 18:17:20.481   932  2895 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 18:17:20.481   932  2895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 18:17:20.482   932  2908 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 18:17:20.489   932  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=245942, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 18:17:20.503   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:17:20.523   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 18:17:20.527   932  2908 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 18:17:20.527   932  2908 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:17:20.527  3661  3812 W QCNEJ   : |CORE| network available: 102
11-24 18:17:20.528   932  2908 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-24 18:17:20.528  3661  3812 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 18:17:20.529   932   949 D Tethering: MasterInitialState.processMessage what=3
11-24 18:17:20.530  3661  3812 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 18:17:20.531  3661  3812 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 18:17:20.543  4985  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 18:17:20.544  4985  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 18:17:20.544  4985  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 18:17:20.544  4985  5007 E SarControlService: no key has been found,reset the power
11-24 18:17:20.544  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 18:17:20.544  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 18:17:20.544  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 18:17:20.545  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:17:20.545  5010  5010 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 18:17:20.546  4985  5022 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 18:17:20.546  4985  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-24 18:17:20.546  4985  5022 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 18:17:20.546  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 18:17:20.547  5010  5010 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 18:17:20.548  3905  3905 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 18:17:20.550  3781  3781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 18:17:20.552  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000f003000000000000ffffffff]
11-24 18:17:20.552  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:17:20.552  5010  5024 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 18:17:20.555  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 18:17:20.555  4985  4996 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 18:17:20.556  5010  5024 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1d49826 HexData = [00000000f103000000000000ffffffff]
11-24 18:17:20.556  5010  5024 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 18:17:20.556  5010  5024 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 18:17:20.557  5010  5010 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 18:17:20.557   932  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 18:17:20.557  4985  4995 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 18:17:20.558  3781  3781 D SystemUpdateService: onCreate
11-24 18:17:20.562  3781  3781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 18:17:20.572  3781  3781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 18:17:20.579  3781  5342 I iu.UploadsManager: num queued entries: 0
,11-24 18:17:20.580  3781  5342 I iu.UploadsManager: num updated entries: 0
,11-24 18:17:20.582  3781  3781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 18:17:20.583  3781  3781 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 18:17:20.585  5650  5650 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 18:17:20.589  5650  5650 D SprintDMHelper: simOperator: 
,11-24 18:17:20.589  5650  5650 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 18:17:20.600  3781  5858 I SystemUpdateService: active receiver: enabled
,11-24 18:17:20.613  3781  5342 I iu.SyncManager: NEXT; no task
,11-24 18:17:20.619   932  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 17:17:20 GMT], X-Android-Received-Millis=[1480007840618], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480007840590]}
,11-24 18:17:20.620   932  2908 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 18:17:20.620   932  2908 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-24 18:17:20.620   932  2908 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 18:17:20.621   932  2908 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 18:17:20.626  3781  5858 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 18:17:20.633  3781  5858 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 18:17:20.633  3781  5858 I SystemUpdateService: now status is 0 (complete)
11-24 18:17:20.633  3781  5858 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 18:17:20.633  3781  5858 I SystemUpdateService: file has been verified
11-24 18:17:20.633  3781  5858 I SystemUpdateService: OTA package size = 21989297
,11-24 18:17:20.639  3781  5858 I SystemUpdateService: showing system update notification
,11-24 18:17:20.648   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 18:17:20.650  3781  3781 D SystemUpdateService: onDestroy
,11-24 18:17:20.705  4934  5862 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 18:17:22.013  5548  5870 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 18:17:22.013  5548  5870 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:22.798  5548  5870 W !!      : call onHalfStreamCopied
,11-24 18:17:22.798  5548  5870 I testCopyDataAndClose: closing input stream
,11-24 18:17:23.574  5548  5870 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 18:17:23.574  5548  5870 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 18:17:23.575  5548  5870 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 18:17:27.800  5548  5871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:27.800  5548  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:28.487   932  2908 D ConnectivityService: handlePromptUnvalidated 102
,11-24 18:17:28.555   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:29.556   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:29.800  5548  5595 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-24 18:17:29.800  5548  5595 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 18:17:29.800  5548  5595 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-24 18:17:29.948  5548  5871 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 18:17:29.948  5548  5871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:29.948  5548  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-24 18:17:29.964  5548  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 18:17:29.964  5548  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:30.558   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:31.559   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 18:17:31.577  5548  5872 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 18:17:31.578  5548  5872 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 18:17:31.578  5548  5872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 18:17:31.578  5548  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 18:17:31.588   932  2895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-24 18:17:32.560   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 18:17:33.561   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 18:17:35.732  5548  5873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:35.732  5548  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:35.732  5548  5873 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:35.732  5548  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 18:17:35.732  5548  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 18:17:35.732  5548  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:35.733  5548  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 18:17:35.735  5548  5595 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-24 18:17:35.738  5548  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:35.738  5548  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 18:17:35.739  5548  5874 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-24 18:17:35.739  5548  5874 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:35.739  5548  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 18:17:35.740  5548  5874 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-24 18:17:35.740  5548  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 18:17:35.740  5548  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 18:17:35.743  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 18:17:35.743  5548  5595 I jxcore-log: 
,11-24 18:17:35.743  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-24 18:17:35.743  5548  5595 I jxcore-log: 
11-24 18:17:35.743  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-24 18:17:35.743  5548  5595 I jxcore-log: 
11-24 18:17:35.744  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 18:17:35.744  5548  5595 I jxcore-log: 
11-24 18:17:35.744  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Total duration:  91652'
11-24 18:17:35.744  5548  5595 I jxcore-log: 
11-24 18:17:35.745  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Failures: 
11-24 18:17:35.745  5548  5595 I jxcore-log:  mCurrentOperation should not be null
11-24 18:17:35.745  5548  5595 I jxcore-log: Expected: is not null
11-24 18:17:35.745  5548  5595 I jxcore-log:      but: was null
11-24 18:17:35.745  5548  5595 I jxcore-log: '
11-24 18:17:35.745  5548  5595 I jxcore-log: 
,11-24 18:17:35.745  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-24 18:17:35.745  5548  5595 I jxcore-log: 
11-24 18:17:35.747  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 18:17:35.747  5548  5595 I jxcore-log: 
,11-24 18:17:35.749  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 18:17:35.749  5548  5595 I jxcore-log: 
,11-24 18:17:35.750  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 18:17:35.750  5548  5595 I jxcore-log: 
11-24 18:17:35.751  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 18:17:35.751  5548  5595 I jxcore-log: 
11-24 18:17:35.751  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 18:17:35.751  5548  5595 I jxcore-log: 
11-24 18:17:35.751  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.751  5548  5595 I jxcore-log: 
11-24 18:17:35.752  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 18:17:35.752  5548  5595 I jxcore-log: 
11-24 18:17:35.752  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.752  5548  5595 I jxcore-log: 
11-24 18:17:35.752  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 18:17:35.752  5548  5595 I jxcore-log: 
11-24 18:17:35.752  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 18:17:35.752  5548  5595 I jxcore-log: 
,11-24 18:17:35.753  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 18:17:35.753  5548  5595 I jxcore-log: 
11-24 18:17:35.753  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 18:17:35.753  5548  5595 I jxcore-log: 
11-24 18:17:35.753  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.753  5548  5595 I jxcore-log: 
11-24 18:17:35.753  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 18:17:35.753  5548  5595 I jxcore-log: 
11-24 18:17:35.753  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.753  5548  5595 I jxcore-log: 
11-24 18:17:35.754  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 18:17:35.754  5548  5595 I jxcore-log: 
,11-24 18:17:35.754  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.754  5548  5595 I jxcore-log: 
11-24 18:17:35.754  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-24 18:17:35.754  5548  5595 I jxcore-log: 
11-24 18:17:35.754  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 18:17:35.754  5548  5595 I jxcore-log: 
11-24 18:17:35.755  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 18:17:35.755  5548  5595 I jxcore-log: 
11-24 18:17:35.755  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 18:17:35.755  5548  5595 I jxcore-log: 
,11-24 18:17:35.755  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 18:17:35.755  5548  5595 I jxcore-log: 
11-24 18:17:35.756  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 18:17:35.756  5548  5595 I jxcore-log: 
11-24 18:17:35.757  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 18:17:35.757  5548  5595 I jxcore-log: 
11-24 18:17:35.758  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 18:17:35.758  5548  5595 I jxcore-log: 
11-24 18:17:35.758  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 18:17:35.758  5548  5595 I jxcore-log: 
11-24 18:17:35.758  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 18:17:35.758  5548  5595 I jxcore-log: 
,11-24 18:17:35.758  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 18:17:35.758  5548  5595 I jxcore-log: 
11-24 18:17:35.758  5548  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 18:17:35.759  5548  5595 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 18:17:35.759  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 18:17:35.759  5548  5595 I jxcore-log: 
,11-24 18:17:35.759  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.759  5548  5595 I jxcore-log: 
11-24 18:17:35.759  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 18:17:35.759  5548  5595 I jxcore-log: 
11-24 18:17:35.759  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.759  5548  5595 I jxcore-log: 
11-24 18:17:35.760  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 18:17:35.760  5548  5595 I jxcore-log: 
11-24 18:17:35.760  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 18:17:35.760  5548  5595 I jxcore-log: 
,11-24 18:17:35.765  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 18:17:35.765  5548  5595 I jxcore-log: 
11-24 18:17:35.765  5548  5595 I jxcore-log: 2016-11-24 17:17:35 - WARN testUtils: 'myNameCallback not set!'
11-24 18:17:35.765  5548  5595 I jxcore-log: 
,11-24 18:17:35.770  5548  5548 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 18:17:35.770  5548  5548 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 18:17:37.821  5548  5595 I jxcore-log: 2016-11-24 17:17:37 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 18:17:37.821  5548  5595 I jxcore-log: 
,11-24 18:17:37.822  5548  5595 I jxcore-log: 2016-11-24 17:17:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 18:17:37.822  5548  5595 I jxcore-log: 
,11-24 18:17:38.178  5548  5595 I jxcore-log: 2016-11-24 17:17:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 18:17:38.178  5548  5595 I jxcore-log: 
,11-24 18:17:38.191  5548  5595 I jxcore-log: 2016-11-24 17:17:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 18:17:38.191  5548  5595 I jxcore-log: 
,11-24 18:17:39.304  5548  5595 I jxcore-log: 2016-11-24 17:17:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 18:17:39.304  5548  5595 I jxcore-log: 
,11-24 18:17:39.495  5548  5595 I jxcore-log: 2016-11-24 17:17:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 18:17:39.495  5548  5595 I jxcore-log: 
,11-24 18:17:39.500  5548  5595 I jxcore-log: 2016-11-24 17:17:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 18:17:39.500  5548  5595 I jxcore-log: 
,11-24 18:17:39.505  5548  5595 I jxcore-log: 2016-11-24 17:17:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 18:17:39.505  5548  5595 I jxcore-log: 
,11-24 18:17:39.996  5548  5595 I jxcore-log: 2016-11-24 17:17:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 18:17:39.996  5548  5595 I jxcore-log: 
,11-24 18:17:40.041  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 18:17:40.041  5548  5595 I jxcore-log: 
,11-24 18:17:40.055  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 18:17:40.055  5548  5595 I jxcore-log: 
,11-24 18:17:40.059  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 18:17:40.059  5548  5595 I jxcore-log: 
,11-24 18:17:40.332  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 18:17:40.332  5548  5595 I jxcore-log: 
,11-24 18:17:40.461  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 18:17:40.461  5548  5595 I jxcore-log: 
,11-24 18:17:40.825  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 18:17:40.825  5548  5595 I jxcore-log: 
,11-24 18:17:40.833  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 18:17:40.833  5548  5595 I jxcore-log: 
,11-24 18:17:40.837  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 18:17:40.837  5548  5595 I jxcore-log: 
,11-24 18:17:40.843  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 18:17:40.843  5548  5595 I jxcore-log: 
,11-24 18:17:40.849  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 18:17:40.849  5548  5595 I jxcore-log: 
,11-24 18:17:40.876  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 18:17:40.876  5548  5595 I jxcore-log: 
,11-24 18:17:40.911  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 18:17:40.911  5548  5595 I jxcore-log: 
,11-24 18:17:40.919  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 18:17:40.919  5548  5595 I jxcore-log: 
,11-24 18:17:40.925  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 18:17:40.925  5548  5595 I jxcore-log: 
,11-24 18:17:40.941  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 18:17:40.941  5548  5595 I jxcore-log: 
,11-24 18:17:40.956  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 18:17:40.956  5548  5595 I jxcore-log: 
,11-24 18:17:40.962  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 18:17:40.962  5548  5595 I jxcore-log: 
,11-24 18:17:40.968  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 18:17:40.968  5548  5595 I jxcore-log: 
,11-24 18:17:40.981  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 18:17:40.981  5548  5595 I jxcore-log: 
,11-24 18:17:40.998  5548  5595 I jxcore-log: 2016-11-24 17:17:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 18:17:40.998  5548  5595 I jxcore-log: 
,11-24 18:17:41.013  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 18:17:41.013  5548  5595 I jxcore-log: 
,11-24 18:17:41.023  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 18:17:41.023  5548  5595 I jxcore-log: 
,11-24 18:17:41.036  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 18:17:41.036  5548  5595 I jxcore-log: 
,11-24 18:17:41.046  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 18:17:41.046  5548  5595 I jxcore-log: 
,11-24 18:17:41.060  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 18:17:41.060  5548  5595 I jxcore-log: 
,11-24 18:17:41.069  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 18:17:41.069  5548  5595 I jxcore-log: 
,11-24 18:17:41.076  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 18:17:41.076  5548  5595 I jxcore-log: 
,11-24 18:17:41.098  5548  5595 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 18:17:41.099  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 18:17:41.099  5548  5595 I jxcore-log: 
,11-24 18:17:41.133  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 18:17:41.133  5548  5595 I jxcore-log: 
,11-24 18:17:41.342  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 18:17:41.342  5548  5595 I jxcore-log: 
,11-24 18:17:41.690  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-24 18:17:41.690  5548  5595 I jxcore-log: 
,11-24 18:17:41.693  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - DEBUG CoordinatedClient: 'test client failed'
11-24 18:17:41.693  5548  5595 I jxcore-log: 
,11-24 18:17:41.699  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 18:17:41.699  5548  5595 I jxcore-log: 
,11-24 18:17:41.704  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:190:20
11-24 18:17:41.704  5548  5595 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-24 18:17:41.704  5548  5595 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-24 18:17:41.704  5548  5595 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-24 18:17:41.704  5548  5595 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-24 18:17:41.704  5548  5595 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-24 18:17:41.704  5548  5595 I jxcore-log: 
11-24 18:17:41.705  5548  5595 I jxcore-log: 2016-11-24 17:17:41 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 18:17:41.705  5548  5595 I jxcore-log: 
,11-24 18:17:42.300  5883  5883 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 18:17:42.323  5883  5883 D AndroidRuntime: CheckJNI is OFF
,11-24 18:17:42.352  5883  5883 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 18:17:42.392  5883  5883 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 18:17:42.409  5883  5883 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 18:17:42.422   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-24 18:17:42.423   932   945 I ActivityManager: Killing 5548:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 18:17:42.525   932  3744 I WindowState: WIN DEATH: Window{65d4425 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 18:17:42.525   932  3349 D GraphicsStats: Buffer count: 2
11-24 18:17:42.527   932  2907 D WifiService: Client connection lost with reason: 4
,11-24 18:17:42.542   932   945 W ActivityManager: Force removing ActivityRecord{8a23142 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 18:17:42.555   932   955 I art     : Starting a blocking GC Explicit
,11-24 18:17:42.561   932   943 W ActivityManager: Spurious death for ProcessRecord{5ad57c3 0:com.test.thalitest/u0a77}, curProc for 5548: null
,11-24 18:17:42.584  3084  3084 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[25425]" dev="sockfs" ino=25425 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 18:17:42.584  3084  3084 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[25425]" dev="sockfs" ino=25425 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 18:17:42.589   932  3084 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5548 uid 10077
11-24 18:17:42.590  3592  3592 I Keyboard.Facilitator: onFinishInput()
,11-24 18:17:42.648   932   955 I art     : Explicit concurrent mark sweep GC freed 51366(3MB) AllocSpace objects, 10(364KB) LOS objects, 33% free, 29MB/43MB, paused 2.446ms total 92.735ms
,11-24 18:17:42.665  3905  5895 I MicroRecognitionRnrImpl: Starting detection.
,11-24 18:17:42.666  3905  5896 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@f61c0ae
11-24 18:17:42.666   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 18:17:42.669  5883  5883 I art     : System.exit called, status: 0
,11-24 18:17:42.669  5883  5883 I AndroidRuntime: VM exiting with result code 0.
11-24 18:17:42.669   513  5899 I AudioFlinger: AudioFlinger's thread 0xf20c0000 ready to run
,11-24 18:17:42.678   513  2928 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 18:17:42.681  3905  5896 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@f61c0ae
,11-24 18:17:42.685   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 18:17:42.690   513  5899 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-24 18:17:42.690   513  5899 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 18:17:42.691   513  5899 I ACDB-LOADER: ACDB AFE returned = -19
11-24 18:17:42.691   513  5899 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-24 18:17:42.691   513  5899 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-24 18:17:42.691   513  5899 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-24 18:17:42.695  5787  5787 D BluetoothMapAppObserver: onReceive
11-24 18:17:42.695  5787  5787 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-24 18:17:42.700   513  5899 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
11-24 18:17:42.702   932  2827 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 18:17:42.707  3979  4097 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 18:17:42.709  3592  3592 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 18:17:42.717  3592  5902 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 18:17:42.732  3692  3692 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 18:17:42.736  3592  5902 I Decoder : createOrResetDecoder
,11-24 18:17:42.745  3334  5905 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 18:17:42.753   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 18:17:42.782  3516  3516 I ConfigService: onCreate
,11-24 18:17:42.786  3905  3905 I HotwordWorkerImpl: onReady
,11-24 18:17:42.787    17    17 W kworker/2:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 18:17:42.791    17    17 W kworker/2:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 18:17:42.799  3516  3516 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-24 18:17:42.799  3516  3516 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 18:17:42.801    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 18:17:42.810  3592  5902 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 18:17:42.820  3334  5905 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
11-24 18:17:42.822  3334  5905 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-24 18:17:42.822  3334  5905 E AndroidRuntime: Process: android.process.acore, PID: 3334
11-24 18:17:42.822  3334  5905 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.822  3334  5905 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 18:17:42.823   932   944 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-24 18:17:42.824   932   944 E PackageManager: Failed to write settings, restoring backup
11-24 18:17:42.824   932   944 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-24 18:17:42.824   932   944 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-24 18:17:42.824   932   944 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-24 18:17:42.824   932   944 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-24 18:17:42.824   932   944 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-24 18:17:42.824   932   944 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 18:17:42.824   932   944 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.824   932   944 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 18:17:42.824  3720  3865 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-24 18:17:42.825  3781  5909 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-24 18:17:42.825  3781  5909 D AccountUtils: Clearing selected account for com.test.thalitest
,11-24 18:17:42.828   932   945 E DropBoxManagerService: Can't write: system_server_wtf
11-24 18:17:42.828   932   945 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 18:17:42.828   932   945 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 18:17:42.828   932   945 E DropBoxManagerService: 	... 13 more
,11-24 18:17:42.840   932  3738 I ActivityManager: Start proc 5913:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-24 18:17:42.841  3720  3865 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 18:17:42.841  3720  3865 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3720
11-24 18:17:42.841  3720  3865 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.841  3720  3865 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 18:17:42.847   932  5922 E DropBoxManagerService: Can't write: system_app_crash
11-24 18:17:42.847   932  5922 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 18:17:42.847   932  5922 E DropBoxManagerService: 	... 5 more
,11-24 18:17:42.850  3781  5909 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-24 18:17:42.849  3781  3781 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-24 18:17:42.850  3781  3781 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-24 18:17:42.852   932  3137 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 18:17:42.855  3905  3912 W SearchService: Abort, client detached.
,11-24 18:17:42.858  3905  3905 I HotwordDetector: Closing mic
,11-24 18:17:42.858  3905  4130 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f61c0ae
,11-24 18:17:42.858  3905  5896 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-24 18:17:42.867   761   761 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[24488]" dev="sockfs" ino=24488 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 18:17:42.867   761   761 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[24488]" dev="sockfs" ino=24488 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 18:17:42.875   932  5928 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 18:17:42.876  3592  5902 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-24 18:17:42.871   760   760 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34924]" dev="sockfs" ino=34924 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 18:17:42.871   760   760 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34924]" dev="sockfs" ino=34924 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 18:17:42.879  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-24 18:17:42.879  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-24 18:17:42.882  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-24 18:17:42.882  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-24 18:17:42.883  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-24 18:17:42.883  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-24 18:17:42.884   932  5929 E DropBoxManagerService: Can't write: system_app_crash
11-24 18:17:42.884   932  5929 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 18:17:42.884   932  5929 E DropBoxManagerService: 	... 5 more
11-24 18:17:42.884  3592  5902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-24 18:17:42.884  3592  5902 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-24 18:17:42.884  3592  5902 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-24 18:17:42.884  3592  5902 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,11-24 18:17:42.884  3592  5902 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-24 18:17:42.884  3592  5902 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-24 18:17:42.885  3781  3781 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-24 18:17:42.885  3781  3781 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.896  3781  5909 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.898  3781  5909 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 18:17:42.924   513  5899 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-24 18:17:42.927   513  5899 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-24 18:17:42.929  3905  5934 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-24 18:17:42.933   513  5899 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-24 18:17:42.933   513  5899 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 18:17:42.934   513  2928 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 18:17:42.935  3905  4136 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 18:17:42.936  3905  5895 I MicroRecognitionRnrImpl: Detection finished
,11-24 18:17:42.951  3781  5933 W BaseAppContext: Using Auth Proxy for data requests.
,11-24 18:17:42.954  3781  5933 W BaseAppContext: Using Auth Proxy for data requests.
,11-24 18:17:42.959  3905  5934 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-24 18:17:42.963  3905  5934 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
11-24 18:17:42.963  3905  5934 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
11-24 18:17:42.963  3905  5934 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 3905
11-24 18:17:42.963  3905  5934 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 18:17:42.963  3905  5934 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 18:17:42.973   932  3606 I ActivityManager: Start proc 5937:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-24 18:17:42.976   932  3814 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,11-24 18:17:42.976   932  3814 I ActivityManager: Killing 3905:com.google.android.googlequicksearchbox:search/u0a29 (adj 1): crash
,11-24 18:17:42.979   932  5944 E DropBoxManagerService: Can't write: system_app_crash
11-24 18:17:42.979   932  5944 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 18:17:42.979   932  5944 E DropBoxManagerService: 	... 5 more
,11-24 18:17:43.015   932  2907 D WifiService: Client connection lost with reason: 4
,11-24 18:17:43.025   932  3767 W ActivityManager: Spurious death for ProcessRecord{76858b7 0:com.google.android.googlequicksearchbox:search/u0a29}, curProc for 3905: null
,11-24 18:17:43.033  3781  3781 E ConnectivityChangeReceiver: Ignoring connectivity change
,11-24 18:17:43.048   932  3084 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3781 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-24 18:17:43.136  3781  5923 W DriveInitializer: Awaiting to be initialized
,11-24 18:17:43.136  3781  5951 W DriveInitializer: Background init thread started
,11-24 18:17:43.199   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
