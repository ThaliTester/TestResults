#### Test 949810482209bfa_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 12:22:30.591  3917  4187 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-23 12:22:30.667  3917  4187 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
--------- beginning of system
11-23 12:22:30.901   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 12:22:31.040  5574  5574 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 12:22:31.046  5574  5574 D AndroidRuntime: CheckJNI is OFF
11-23 12:22:31.070  5574  5574 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 12:22:31.102  5574  5574 I Radio-JNI: register_android_hardware_Radio DONE
11-23 12:22:31.117  5574  5574 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-23 12:22:31.121   926  3128 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 12:22:31.140  5574  5574 D AndroidRuntime: Shutting down VM
11-23 12:22:31.149  3936  3947 W SearchService: Abort, client detached.
11-23 12:22:31.157  3936  4149 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2a4350e
11-23 12:22:31.157  3936  3936 I HotwordDetector: Closing mic
11-23 12:22:31.157  3936  4164 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 12:22:31.180   926  3742 I ActivityManager: Start proc 5583:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 12:22:31.240   512  4172 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 12:22:31.243   512  4172 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 12:22:31.251   512  4172 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 12:22:31.252   512  4172 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 12:22:31.252   512  2966 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 12:22:31.254  3936  4150 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 12:22:31.255  3936  4163 I MicroRecognitionRnrImpl: Detection finished
11-23 12:22:31.288  5583  5583 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-23 12:22:31.316  5583  5583 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-23 12:22:31.376  5583  5583 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 487-544)
11-23 12:22:31.377  5583  5583 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 12:22:31.413  5583  5583 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6766151}
,11-23 12:22:31.414  5583  5583 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 12:22:31.414  5583  5583 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 12:22:31.420  5583  5583 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 12:22:31.422  5583  5583 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 12:22:31.467  5583  5583 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 12:22:31.481  5583  5583 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 12:22:31.481  5583  5583 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 12:22:31.481  5583  5583 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 12:22:31.481  5583  5583 I Adreno  : Build Date                       : 12/06/15
11-23 12:22:31.481  5583  5583 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 12:22:31.481  5583  5583 I Adreno  : Local Branch                     : mybranch17112971
11-23 12:22:31.481  5583  5583 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 12:22:31.481  5583  5583 I Adreno  : Remote Branch                    : NONE
11-23 12:22:31.481  5583  5583 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 12:22:31.524   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee89f38:true
,11-23 12:22:31.562   408   408 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21492]" dev="sockfs" ino=21492 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 12:22:31.562   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21492]" dev="sockfs" ino=21492 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 12:22:31.575  5583  5583 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 12:22:31.583  5583  5583 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 12:22:31.614  5583  5620 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 12:22:31.609   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32583]" dev="sockfs" ino=32583 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 12:22:31.609   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32583]" dev="sockfs" ino=32583 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 12:22:31.612  3128  3128 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21498]" dev="sockfs" ino=21498 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 12:22:31.612  3128  3128 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21498]" dev="sockfs" ino=21498 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 12:22:31.621  5583  5607 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 12:22:31.650  5583  5620 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 12:22:31.732  3382  3382 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32587]" dev="sockfs" ino=32587 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 12:22:31.732  3382  3382 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32587]" dev="sockfs" ino=32587 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 12:22:31.732   937   937 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32586]" dev="sockfs" ino=32586 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 12:22:31.732   937   937 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32586]" dev="sockfs" ino=32586 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 12:22:31.737   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +584ms
,11-23 12:22:31.741  3631  3631 I Keyboard.Facilitator: onFinishInput()
,11-23 12:22:31.766  5583  5583 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5583
,11-23 12:22:31.861   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:22:31.902  5583  5583 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 12:22:32.044  5583  5623 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -563345104
,11-23 12:22:32.048  5583  5623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 12:22:32.048  5583  5623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 12:22:32.048  5583  5623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 12:22:32.048  5583  5623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 12:22:32.048  5583  5623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 12:22:32.048  5583  5623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@494aa7c added. We now have 1 listener(s)
,11-23 12:22:32.052  5583  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-23 12:22:32.052  5583  5623 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:22:32.053  5583  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:22:32.053  5583  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 12:22:32.055  5583  5623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdfc18b added. We now have 1 listener(s)
11-23 12:22:32.055  5583  5623 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:22:32.060   926  2917 D WifiService: New client listening to asynchronous messages
,11-23 12:22:32.061  5583  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:22:32.061  5583  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 12:22:32.061  5583  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 12:22:32.061  5583  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 12:22:32.061  5583  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 12:22:32.061  5583  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 12:22:32.061  5583  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-23 12:22:32.063  5583  5623 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 12:22:32.106  5583  5583 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 12:22:32.336  3917  3917 I ConfigFetchService: fetch service done; releasing wakelock
,11-23 12:22:32.337  3917  3917 I ConfigFetchService: stopping self
,11-23 12:22:32.881  5583  5630 W jxcore-log: Initializing JXcore engine
11-23 12:22:32.881  5583  5630 W jxcore-log: JXcore engine is ready
,11-23 12:22:32.902  5630  5630 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12073 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 12:22:32.902  5630  5630 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[17729]" dev="sockfs" ino=17729 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-23 12:22:32.902  5630  5630 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 12:22:32.902  5630  5630 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32562]" dev="sockfs" ino=32562 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 12:22:32.913  5583  5630 W jxcore-log: Starting JXcore engine
,11-23 12:22:32.962  5583  5630 W jxcore-log: Platform android
11-23 12:22:32.962  5583  5630 W jxcore-log: 
,11-23 12:22:32.962  5583  5630 W jxcore-log: Process ARCH arm
11-23 12:22:32.962  5583  5630 W jxcore-log: 
,11-23 12:22:33.148  5583  5630 I jxcore-log: JXcore Cordova bridge is ready!
11-23 12:22:33.148  5583  5630 I jxcore-log: 
,11-23 12:22:33.149  5583  5630 W jxcore-log: JXcore engine is started
,11-23 12:22:33.162  5583  5623 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 12:22:33.170  5583  5583 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 12:22:33.923   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 12:22:34.892   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:22:35.893   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:22:36.162   926  3381 I ActivityManager: Killing 5227:org.codeaurora.ims/1001 (adj 15): empty #17
,11-23 12:22:36.205   926  3381 I ActivityManager: Killing 5136:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-23 12:22:36.894   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:22:36.957   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 12:22:37.348  3546  3546 I ConfigService: onDestroy
,11-23 12:22:37.896   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:22:38.897   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:22:39.897   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 12:22:42.912  5583  5630 I jxcore-log: 2016-11-23 11:22:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 12:22:42.912  5583  5630 I jxcore-log: 
,11-23 12:22:42.914  5583  5630 I jxcore-log: 2016-11-23 11:22:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 12:22:42.914  5583  5630 I jxcore-log: 
,11-23 12:22:42.919  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:22:42.919  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 12:22:42.920  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 12:22:42.923  5583  5630 I jxcore-log: 2016-11-23 11:22:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 12:22:42.923  5583  5630 I jxcore-log: 
,11-23 12:22:42.924  5583  5630 I jxcore-log: 2016-11-23 11:22:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 12:22:42.924  5583  5630 I jxcore-log: 
,11-23 12:22:43.174  5583  5630 I jxcore-log: 2016-11-23 11:22:43 - DEBUG UnitTest_app: 'Running unit tests'
11-23 12:22:43.174  5583  5630 I jxcore-log: 
,11-23 12:22:43.174  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:22:43.174  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f47fd7 added. We now have 2 listener(s)
,11-23 12:22:43.175  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:22:43.175  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:22:43.175  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:22:43.175  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 12:22:43.175  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55820c4 added. We now have 2 listener(s)
11-23 12:22:43.175  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:22:43.176  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 12:22:43.177  5583  5630 D executeNativeTests: Running unit tests
,11-23 12:22:43.217  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 12:22:43.217  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d added. We now have 3 listener(s)
11-23 12:22:43.218  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:22:43.218  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 12:22:43.218  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:22:43.218  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:22:43.218  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 added. We now have 3 listener(s)
11-23 12:22:43.218  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:22:43.218  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:22:43.220  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 12:22:43.220  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 12:22:43.220  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 12:22:43.220  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 12:22:43.221  5583  5630 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 12:22:43.221  5583  5630 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-23 12:22:43.221  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 12:22:43.221  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 12:22:43.221  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 12:22:43.221  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 12:22:43.221  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:22:43.222  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 12:22:43.222  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:22:43.222  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:22:43.223  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:43.223  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:22:43.223  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d removed from the list
11-23 12:22:43.223  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:43.223  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 removed from the list
11-23 12:22:43.223  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:22:43.223  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.223  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:43.224  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.224  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.224  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.224  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 12:22:43.224  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:22:43.224  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:43.224  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:43.225  5583  5630 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 12:22:43.225  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:22:43.225  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:22:43.225  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 12:22:43.225  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:22:43.225  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:43.225  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:22:43.225  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:43.225  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:43.225  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:22:43.225  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.225  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:43.226  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.226  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.226  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.226  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:22:43.226  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 12:22:43.226  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:43.226  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:43.228  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 12:22:43.228  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 12:22:43.228  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 12:22:43.228  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-23 12:22:43.229  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 12:22:43.229  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:22:43.229  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:22:43.229  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:22:43.229  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 12:22:43.229  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:43.230  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:22:43.230  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:43.230  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:43.230  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:22:43.230  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.230  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.230  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.230  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.230  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.230  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:22:43.230  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:22:43.230  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:43.230  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:43.231  5583  5630 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 12:22:43.232  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 12:22:43.232  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:22:43.251  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 12:22:43.254  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 12:22:43.254  5583  5630 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 12:22:43.254  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:22:43.254  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 12:22:43.255  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 12:22:43.255  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:22:43.255  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 12:22:43.259  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:22:43.262  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 12:22:43.262  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-23 12:22:43.262  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 12:22:43.263  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:22:43.267  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.267  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 12:22:43.268  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 12:22:43.268  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 12:22:43.268  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 12:22:43.269  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-23 12:22:43.270  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 12:22:43.271  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.271  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 12:22:43.271  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 12:22:43.271  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 12:22:43.271  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 12:22:43.271  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.272  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:43.274  4626  4643 D BtGatt.GattService: registerClient() - UUID=544446ac-6deb-4644-9902-8e23d1c5d2e5
,11-23 12:22:43.276  4626  4695 D BtGatt.GattService: onClientRegistered() - UUID=544446ac-6deb-4644-9902-8e23d1c5d2e5, clientIf=5
11-23 12:22:43.277  5583  5593 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 12:22:43.279  4626  4641 D BtGatt.GattService: start scan with filters
,11-23 12:22:43.285  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 12:22:43.285  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.285  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 12:22:43.285  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.286  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 12:22:43.286  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 12:22:43.286  4626  4698 D BtGatt.ScanManager: handling starting scan
11-23 12:22:43.286  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.286  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-23 12:22:43.286  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 12:22:43.286  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:43.286  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 12:22:43.287  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.287  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.287  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.287  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:43.287  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:43.287  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.287  5583  5630 I io.jxcore.node.ConnectionHelper: start: OK
11-23 12:22:43.287  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.287  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.291  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.291  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 12:22:43.292  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.292  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:43.292  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:22:43.293  4626  4698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:22:43.301  4626  4695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 12:22:43.301  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:43.302  4626  4698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 12:22:43.309  4626  4695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 12:22:43.309  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:43.310  4626  4698 D BtGatt.ScanManager: Starting BLE batch scan
11-23 12:22:43.310  4626  4698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 12:22:43.323  4626  4695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 12:22:43.323  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:43.331  4626  4695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 12:22:43.331  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:43.793  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 12:22:43.793  5583  5583 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:22:43.794  5583  5583 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 12:22:48.295  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 12:22:48.295  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 12:22:48.296  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 12:22:48.296  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:22:48.296  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 12:22:48.296  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:48.296  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 12:22:48.296  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 12:22:48.297  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.297  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 12:22:48.297  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 12:22:48.298  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.298  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.299  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.299  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 12:22:48.299  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.301  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:48.302  4626  4856 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 12:22:48.302  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 12:22:48.304  4626  4698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:22:48.304  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:48.307  4626  4643 D BtGatt.GattService: stopScan() - queue size =1
11-23 12:22:48.308  4626  4641 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 12:22:48.309  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 12:22:48.309  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.309  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 12:22:48.309  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:48.310  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.310  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.310  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.310  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 12:22:48.311  4626  4626 D BtGatt.ScanManager: awakened up at time 97479
11-23 12:22:48.311  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.311  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.311  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:48.311  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 12:22:48.311  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-23 12:22:48.317  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 12:22:48.318  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:48.339  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:48.339  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:22:48.339  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.339  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:48.339  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:22:48.339  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:22:48.339  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:22:48.340  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:22:48.340  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:48.340  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:22:48.340  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:22:48.340  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:48.340  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:48.340  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 12:22:48.340  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:22:48.340  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 12:22:48.340  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.340  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-23 12:22:48.340  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 12:22:48.340  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 12:22:48.340  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.340  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.341  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:22:48.341  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.341  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.342  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.343  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:48.343  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 12:22:48.357  4626  4695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-23 12:22:48.357  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:48.357  4626  4695 D BtGatt.GattService: current time is 97525357698
11-23 12:22:48.357  4626  4695 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -93, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -87, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-23 12:22:48.360  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-23 12:22:48.361  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-23 12:22:48.361  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-23 12:22:48.362  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 12:22:48.362  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-23 12:22:48.362  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 12:22:48.362  4626  4695 E BtGatt.ContextMap: Context not found for ID 5
,11-23 12:22:48.369  4626  4695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 12:22:48.369  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:48.369  4626  4698 D BtGatt.ScanManager: stopping BLe Batch
,11-23 12:22:48.373  4626  4695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 12:22:48.373  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:48.374  4626  4698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 12:22:48.379  4626  4695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:22:48.379  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:48.385  3936  5633 W CronetSyncConnectionRcs: Upload content type not set.
,11-23 12:22:48.445  4801  4876 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-23 12:22:48.446  4801  4801 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-23 12:22:48.842  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 12:22:53.345  5583  5630 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 12:22:53.351  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:22:53.351  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:22:53.366  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 12:22:53.368  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 12:22:53.369  5583  5630 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 12:22:53.369  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 12:22:53.369  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-23 12:22:53.369  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 12:22:53.369  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 12:22:53.369  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 12:22:53.372  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:22:53.374  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 12:22:53.374  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 12:22:53.374  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 12:22:53.376  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:22:53.379  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.379  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 12:22:53.380  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 12:22:53.380  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 12:22:53.380  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 12:22:53.384  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.384  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 12:22:53.384  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 12:22:53.384  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 12:22:53.384  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 12:22:53.384  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.385  5583  5630 D BluetoothAdapter: STATE_ON
,11-23 12:22:53.390  4626  4854 D BtGatt.GattService: registerClient() - UUID=b7f3b949-f45d-4c73-a2aa-2f8345208cd1
11-23 12:22:53.390  4626  4695 D BtGatt.GattService: onClientRegistered() - UUID=b7f3b949-f45d-4c73-a2aa-2f8345208cd1, clientIf=5
,11-23 12:22:53.391  5583  5594 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 12:22:53.391  4626  4843 D BtGatt.GattService: start scan with filters
,11-23 12:22:53.394  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 12:22:53.394  4626  4698 D BtGatt.ScanManager: handling starting scan
11-23 12:22:53.394  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.394  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 12:22:53.394  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.394  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 12:22:53.395  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 12:22:53.395  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.395  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 12:22:53.395  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 12:22:53.395  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.395  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.395  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.395  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.396  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 12:22:53.396  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.399  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.399  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 12:22:53.399  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.400  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.400  5583  5630 I io.jxcore.node.ConnectionHelper: start: OK
11-23 12:22:53.400  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.400  4626  4695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-23 12:22:53.400  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.400  4626  4698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 12:22:53.402  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:22:53.403  5583  5630 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 12:22:53.403  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 12:22:53.403  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 12:22:53.403  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:22:53.403  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 12:22:53.403  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 12:22:53.403  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 12:22:53.406  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.406  4626  4695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 12:22:53.406  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.406  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.406  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.406  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 12:22:53.406  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 12:22:53.406  4626  4698 D BtGatt.ScanManager: Starting BLE batch scan
11-23 12:22:53.406  4626  4698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.407  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 12:22:53.407  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.408  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:53.408  4626  4856 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 12:22:53.408  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 12:22:53.409  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:53.410  4626  4854 D BtGatt.GattService: stopScan() - queue size =1
11-23 12:22:53.410  4626  4843 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 12:22:53.411  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.412  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.412  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.412  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 12:22:53.412  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 12:22:53.412  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:22:53.412  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.416  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.416  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:22:53.416  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.416  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.416  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:22:53.416  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:22:53.416  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:22:53.416  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:22:53.416  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:22:53.416  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:53.416  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-23 12:22:53.416  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:22:53.416  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:53.416  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.416  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:22:53.416  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:22:53.416  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 12:22:53.417  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 12:22:53.417  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 12:22:53.417  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 12:22:53.417  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.417  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.417  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:22:53.417  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.417  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.419  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.419  4626  4695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 12:22:53.419  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.419  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:53.419  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.419  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.419  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.421  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.421  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.421  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.421  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:22:53.421  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:22:53.421  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:22:53.421  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:22:53.422  5583  5630 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 12:22:53.424  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:22:53.424  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 12:22:53.425  4626  4695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 12:22:53.425  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.426  4626  4698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:22:53.430  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 12:22:53.431  4626  4695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:22:53.432  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 12:22:53.432  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.432  4626  4695 E BtGatt.ContextMap: Context not found for ID 5
11-23 12:22:53.432  5583  5630 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 12:22:53.432  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:22:53.432  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 12:22:53.432  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 12:22:53.432  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:22:53.432  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 12:22:53.435  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:22:53.436  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 12:22:53.436  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 12:22:53.436  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 12:22:53.438  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:22:53.439  4626  4695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 12:22:53.439  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.439  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.440  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 12:22:53.440  4626  4698 D BtGatt.ScanManager: stopping BLe Batch
11-23 12:22:53.440  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 12:22:53.440  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 12:22:53.440  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 12:22:53.443  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:53.443  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 12:22:53.443  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 12:22:53.443  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 12:22:53.443  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 12:22:53.443  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.444  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:53.444  4626  4695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 12:22:53.444  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.445  4626  4698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:22:53.446  4626  4843 D BtGatt.GattService: registerClient() - UUID=23518203-dba4-4563-9abf-a31965bc17d3
11-23 12:22:53.447  4626  4695 D BtGatt.GattService: onClientRegistered() - UUID=23518203-dba4-4563-9abf-a31965bc17d3, clientIf=5
11-23 12:22:53.448  5583  5594 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 12:22:53.448  4626  4854 D BtGatt.GattService: start scan with filters
,11-23 12:22:53.451  4626  4695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:22:53.451  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.452  4626  4698 D BtGatt.ScanManager: handling starting scan
,11-23 12:22:53.452  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 12:22:53.452  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.452  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 12:22:53.452  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.453  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 12:22:53.453  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 12:22:53.453  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.453  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 12:22:53.453  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 12:22:53.453  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.453  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.453  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.453  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.454  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 12:22:53.454  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.457  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.457  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:22:53.457  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.457  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:53.457  5583  5630 I io.jxcore.node.ConnectionHelper: start: OK
11-23 12:22:53.457  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 12:22:53.458  4626  4695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 12:22:53.458  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.459  4626  4698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 12:22:53.460  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.460  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.460  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:53.460  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:22:53.464  4626  4695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 12:22:53.464  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.464  4626  4698 D BtGatt.ScanManager: Starting BLE batch scan
11-23 12:22:53.464  4626  4698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 12:22:53.473  4626  4695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 12:22:53.473  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:53.477  4626  4695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 12:22:53.477  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:53.961  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 12:22:53.962  5583  5583 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 12:22:53.962  5583  5583 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 12:22:58.457  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 12:22:58.458  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 12:22:58.458  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 12:22:58.458  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:22:58.459  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-23 12:22:58.459  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:22:58.459  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 12:22:58.459  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 12:22:58.459  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:58.459  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 12:22:58.460  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 12:22:58.460  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.460  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.460  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.460  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 12:22:58.461  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.464  5583  5630 D BluetoothAdapter: STATE_ON
,11-23 12:22:58.464  4626  4843 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 12:22:58.465  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 12:22:58.466  4626  4698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 12:22:58.466  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:22:58.468  4626  4856 D BtGatt.GattService: stopScan() - queue size =1
,11-23 12:22:58.469  4626  4641 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 12:22:58.470  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 12:22:58.470  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.471  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 12:22:58.471  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:58.471  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.471  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.471  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.472  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 12:22:58.472  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.472  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.472  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.472  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 12:22:58.473  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 12:22:58.474  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:22:58.474  4626  4626 D BtGatt.ScanManager: awakened up at time 107642
11-23 12:22:58.474  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.476   926  3707 I ActivityManager: Killing 5267:com.android.settings/1000 (adj 15): empty #17
11-23 12:22:58.477  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.477  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:22:58.478  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:22:58.478  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:22:58.479  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:22:58.479  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:22:58.479  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 12:22:58.479  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.479  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-23 12:22:58.479  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 12:22:58.479  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.480  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.480  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.480  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 12:22:58.480  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.480  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.482  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.483  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:22:58.483  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 12:22:58.518  4626  4695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-23 12:22:58.518  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:58.518  4626  4695 D BtGatt.GattService: current time is 107686544023
,11-23 12:22:58.519  4626  4695 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -90, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -83, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -88, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 12:22:58.519  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 12:22:58.519  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 12:22:58.519  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 12:22:58.520  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-23 12:22:58.520  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 12:22:58.520  4626  4695 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-23 12:22:58.525  4626  4695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 12:22:58.525  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:58.526  4626  4698 D BtGatt.ScanManager: stopping BLe Batch
,11-23 12:22:58.531  4626  4695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 12:22:58.531  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:22:58.531  4626  4698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 12:22:58.536  4626  4695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 12:22:58.536  4626  4695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:22:58.981  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 12:22:58.981  5583  5583 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:22:58.981  5583  5583 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 12:23:03.480  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 12:23:03.480  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 12:23:03.480  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.481  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.481  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 12:23:03.481  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:03.481  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.481  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.482  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:03.482  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.482  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.482  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 12:23:03.485  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.485  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.489  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.489  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.489  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.490  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.490  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 12:23:03.490  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.491  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.493  5583  5630 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-23 12:23:03.496  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.496  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.497  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.497  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.498  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.498  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
,11-23 12:23:03.498  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.499  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.499  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:03.499  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.499  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.502  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.502  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.502  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.502  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.502  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.503  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.503  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.504  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 12:23:03.504  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.504  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.504  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 12:23:03.505  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.505  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.505  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.505  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.505  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.505  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.505  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.505  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.507  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.508  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.508  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.508  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.508  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.508  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.508  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:03.510  5583  5630 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-23 12:23:03.510  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.510  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.510  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.511  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.511  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.511  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.511  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:03.511  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.511  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.511  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.511  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.514  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.514  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.514  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.514  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.514  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.514  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.514  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:03.515  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 12:23:03.515  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.516  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 12:23:03.516  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.516  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.516  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.516  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.516  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.516  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.516  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.516  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.516  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.519  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.519  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.519  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.519  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.519  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.520  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.520  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:03.521  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 12:23:03.521  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 12:23:03.521  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 12:23:03.521  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 12:23:03.521  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 12:23:03.521  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 12:23:03.521  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 12:23:03.521  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 12:23:03.521  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 12:23:03.522  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.522  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.522  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.522  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.522  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 12:23:03.522  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.522  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.522  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.522  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.523  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.523  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.525  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.526  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.526  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.526  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.526  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.526  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.526  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.528  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 12:23:03.528  5583  5630 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 12:23:03.528  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 12:23:03.533  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 12:23:03.533  5583  5630 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,11-23 12:23:03.533  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 12:23:03.533  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 12:23:03.533  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 12:23:03.533  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 12:23:03.534  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 12:23:03.535  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 12:23:03.536  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-23 12:23:03.536  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 12:23:03.536  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 12:23:03.536  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-23 12:23:03.537  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 12:23:03.537  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 12:23:03.537  5583  5630 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 12:23:03.538  5583  5630 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 12:23:03.538  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 12:23:03.538  5583  5630 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 12:23:03.538  5583  5630 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-23 12:23:03.539  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 12:23:03.539  5583  5630 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 12:23:03.539  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-23 12:23:03.542  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 12:23:03.543  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 12:23:03.543  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-23 12:23:03.544  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 12:23:03.544  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 12:23:03.544  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 12:23:03.544  5583  5630 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 12:23:03.544  5583  5630 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 12:23:03.544  5583  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,11-23 12:23:03.544  5583  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 12:23:03.544  5583  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 12:23:03.544  5583  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 12:23:03.545  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.545  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.545  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.545  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 12:23:03.545  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.545  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-23 12:23:03.546  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.546  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.546  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.546  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.546  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.546  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.547  5583  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 12:23:03.547  5583  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-23 12:23:03.547  5583  5637 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 12:23:03.547  5583  5637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 12:23:03.546  4856  4856 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30320]" dev="sockfs" ino=30320 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 12:23:03.548  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.548  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.548  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.548  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.548  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.548  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.548  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.549  5583  5630 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-23 12:23:03.550  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.550  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.550  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.550  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.550  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.550  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.549  4856  4856 W Binder_5: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30320]" dev="sockfs" ino=30320 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 12:23:03.550  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.550  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:03.550  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.550  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.551  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.556  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.556  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.556  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.556  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.556  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.556  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:03.556  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.557  5583  5630 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 12:23:03.557  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 12:23:03.557  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.557  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.557  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.558  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.558  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.558  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.558  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.558  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:03.558  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.558  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.560  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.560  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.560  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.560  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.560  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.560  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.560  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:03.561  5583  5630 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 12:23:03.561  5583  5630 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 12:23:03.561  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 12:23:03.561  5583  5630 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 12:23:03.561  5583  5630 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 12:23:03.561  5583  5630 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 12:23:03.561  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 12:23:03.562  5583  5630 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 12:23:03.562  5583  5630 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 12:23:03.562  5583  5630 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 12:23:03.562  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 12:23:03.562  5583  5630 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 12:23:03.562  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:03.562  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:03.562  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:03.562  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.563  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.563  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.563  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.563  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.563  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:03.563  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.563  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:03.564  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.564  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.565  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:03.565  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:03.565  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:03.565  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.565  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:03.565  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:03.566  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:03.566  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:03.566  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:03.566  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:03.566  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:04.898   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-23 12:23:04.899   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 12:23:08.567  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:08.567  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.567  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:08.567  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:08.567  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.568  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:08.568  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 12:23:08.568  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:08.568  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:08.569  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:08.569  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.569  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:08.569  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.569  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:08.569  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.570  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.573  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:08.574  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.575  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.575  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 12:23:08.575  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 12:23:08.575  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:08.576  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:08.581  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-23 12:23:08.582  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:23:08.583  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 12:23:08.588  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 12:23:08.590  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-23 12:23:08.590  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 12:23:08.590  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-23 12:23:08.591  5583  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-23 12:23:08.591  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 12:23:08.591  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 12:23:08.591  5583  5583 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-23 12:23:08.591  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 12:23:08.592  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 12:23:08.592  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 12:23:08.592  5583  5639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 12:23:08.592  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 12:23:08.592  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 12:23:08.589  4856  4856 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32646]" dev="sockfs" ino=32646 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 12:23:08.589  4856  4856 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32646]" dev="sockfs" ino=32646 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 12:23:08.593  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 12:23:08.593  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-23 12:23:08.594  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.594  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.594  5583  5583 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 12:23:08.594  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 12:23:08.594  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.594  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 12:23:08.594  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 12:23:08.595  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.595  5583  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 12:23:08.595  5583  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 12:23:08.595  5583  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 12:23:08.598  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:08.598  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 12:23:08.598  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.598  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.598  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.598  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 12:23:08.599  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:08.599  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:23:08.599  5583  5583 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 12:23:08.599  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:08.599  5583  5583 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:08.599  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:08.599  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 12:23:08.599  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:08.599  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:08.599  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.599  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.599  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.599  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:08.600  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.600  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:08.602  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.602  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.602  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.602  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:08.603  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:08.603  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.603  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.604  5583  5630 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 12:23:08.604  5583  5630 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 12:23:08.605  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 12:23:08.605  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 12:23:08.605  5583  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 12:23:08.605  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:08.605  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:08.605  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:08.605  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:08.605  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 12:23:08.606  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.606  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.606  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.606  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:08.606  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.606  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.608  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.608  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.608  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.609  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:08.609  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:08.609  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.609  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:08.614  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 12:23:08.614  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:08.614  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:08.614  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:08.614  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:08.614  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.614  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.614  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
,11-23 12:23:08.614  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:08.614  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.615  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:08.616  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:08.616  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.616  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.616  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:08.616  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:08.616  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.616  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.617  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:08.617  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:08.617  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 12:23:08.617  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:08.617  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:08.617  5583  5630 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6960a1d not in the list
11-23 12:23:08.618  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.618  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.618  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:08.618  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.618  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:08.619  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.619  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.619  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:08.619  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:08.619  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:08.619  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:08.619  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4655492 not in the list
11-23 12:23:08.621  5583  5630 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 12:23:08.621  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 12:23:08.621  5583  5630 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-23 12:23:08.621  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 12:23:08.621  5583  5630 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 12:23:08.621  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 12:23:08.624  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-23 12:23:08.624  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 12:23:08.624  5583  5630 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 12:23:08.625  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 12:23:08.625  5583  5630 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 12:23:08.625  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 12:23:08.625  5583  5630 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 12:23:08.625  5583  5630 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 12:23:08.626  5583  5630 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-23 12:23:08.626  5583  5630 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 12:23:08.626  5583  5630 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 12:23:08.626  5583  5630 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-23 12:23:08.626  5583  5630 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 12:23:08.626  5583  5630 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-23 12:23:08.627  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:08.627  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8bef653 added. We now have 3 listener(s)
11-23 12:23:08.627  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:08.628  5583  5630 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 12:23:08.629   926  3770 D WifiService: setWifiEnabled: true pid=5583, uid=10077
11-23 12:23:08.629   926  3770 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 12:23:08.675  4626  4816 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-23 12:23:08.675  4626  4841 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-23 12:23:08.676  5583  5637 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-23 12:23:08.676  5583  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 12:23:08.676  5583  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-23 12:23:09.100  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 12:23:09.900   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:10.901   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:11.866   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:23:11.902   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:12.903   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:13.635  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 12:23:13.636  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8e5b90 added. We now have 4 listener(s)
,11-23 12:23:13.636  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:23:13.646  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:13.646  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8e5b90 removed from the list
11-23 12:23:13.646  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:13.647  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:13.647  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e30c89 added. We now have 4 listener(s)
11-23 12:23:13.647  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:23:13.650  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:13.650  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e30c89 removed from the list
11-23 12:23:13.650  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:13.651  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 12:23:13.652  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@974448e added. We now have 4 listener(s)
11-23 12:23:13.652  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:23:13.657   926  3770 D WifiService: setWifiEnabled: false pid=5583, uid=10077
,11-23 12:23:13.657   926  3770 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 12:23:13.664   926  2916 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 12:23:13.664   926  2916 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 12:23:13.664   926  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 12:23:13.665   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 12:23:13.671  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 12:23:13.672  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 12:23:13.672  4626  4691 D BluetoothAdapterState: Current state: ON, message: 23
11-23 12:23:13.672  4626  4691 D BluetoothAdapterProperties: Setting state to 13
11-23 12:23:13.672  4626  4691 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 12:23:13.673  4626  4691 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 12:23:13.674  4626  4691 I BluetoothAdapterState: Entering PendingCommandState
,11-23 12:23:13.679  4626  4626 D BluetoothMapService: onReceive
11-23 12:23:13.680  4626  4626 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 12:23:13.681  4626  4626 D BluetoothMapService: STATE_TURNING_OFF
11-23 12:23:13.682  4626  4626 D BluetoothMapService: MAP Service closeService in
11-23 12:23:13.682  4626  4626 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 12:23:13.682  4626  4626 D ObexServerSockets0: shutdown(block = true)
11-23 12:23:13.682   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-23 12:23:13.683  4626  4626 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 12:23:13.683  4626  4626 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 12:23:13.683  4626  4841 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 12:23:13.683   926  5359 D DhcpClient: Clearing IP address
11-23 12:23:13.683  4626  4859 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 12:23:13.684  4626  4858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-23 12:23:13.687  4626  4626 I BtOppRfcommListener: stopping Accept Thread
11-23 12:23:13.688  4626  5289 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 12:23:13.688  4626  5289 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 12:23:13.690   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:13.693  3546  5411 V NativeCrypto: Read error: ssl=0x7f70705000: I/O error during system call, Connection timed out
,11-23 12:23:13.696  3546  5411 V NativeCrypto: SSL shutdown failed: ssl=0x7f70705000: I/O error during system call, Broken pipe
,11-23 12:23:13.698   926   939 I ActivityManager: Start proc 5643:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-23 12:23:13.698   926  3097 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-23 12:23:13.699   926  5357 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 12:23:13.699  4626  4695 D BluetoothAdapterProperties: Scan Mode:20
11-23 12:23:13.699  4626  4691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 12:23:13.703  4626  4626 D HeadsetService: Received stop request...Stopping profile...
,11-23 12:23:13.703   926  5357 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-23 12:23:13.704   926   926 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:13.704   926   926 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:13.704   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-23 12:23:13.705  3723  3745 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:13.705   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 12:23:13.705  3112  3124 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:13.705   926   926 D BluetoothHeadset: Proxy object disconnected
,11-23 12:23:13.706  4626  4626 D A2dpService: Received stop request...Stopping profile...
11-23 12:23:13.706  4626  4848 D A2dpStateMachine: Exit Disconnected: -1
11-23 12:23:13.707  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.707   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:23:13.707  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 12:23:13.708  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.708  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 12:23:13.708  5583  5630 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 12:23:13.709   926   926 D BluetoothA2dp: Proxy object disconnected
,11-23 12:23:13.710  4626  4626 D HidService: Received stop request...Stopping profile...
11-23 12:23:13.710  4626  4626 D HidService: Stopping Bluetooth HidService
11-23 12:23:13.711   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 12:23:13.711   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 12:23:13.712  4626  4626 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:13.712  4626  4626 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:13.712  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:13.712  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:13.716   533   533 E Parcel  : Reading a NULL string not supported here.
11-23 12:23:13.717   926   926 D RttService: SCAN_AVAILABLE : 1
11-23 12:23:13.717   926  3026 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 12:23:13.718  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:23:13.718  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 12:23:13.719  4626  4626 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-23 12:23:13.719  4626  4626 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 12:23:13.719  4626  4695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 12:23:13.719  4626  4816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:13.719  4626  4816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:13.719  4626  4816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:13.719  4626  4626 D HealthService: Received stop request...Stopping profile...
11-23 12:23:13.719  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.719  4626  4695 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 12:23:13.719  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-23 12:23:13.721  4626  4626 D PanService: Received stop request...Stopping profile...
,11-23 12:23:13.722  4626  4626 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:13.722  4626  4626 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:13.722  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:13.722  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.722  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:13.722  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 12:23:13.724  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.724  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 12:23:13.724  4626  4695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 12:23:13.724  4626  4626 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:13.724  4626  4816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:13.724  4626  4626 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:13.724  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 12:23:13.724  4626  4816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:13.724  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:13.724  4626  4816 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 12:23:13.724  4626  4816 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 12:23:13.724  4626  4816 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 12:23:13.724  4626  4816 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 12:23:13.724  4626  4626 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 12:23:13.724  4626  4626 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-23 12:23:13.725   926  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-23 12:23:13.725  4626  4626 D BluetoothMapService: Received stop request...Stopping profile...
11-23 12:23:13.725  4626  4626 D BluetoothMapService: stop()
11-23 12:23:13.725   926  5360 D DhcpClient: Receive thread stopped
11-23 12:23:13.726  4626  4626 D BluetoothMapAppObserver: deinitObservers()
,11-23 12:23:13.726  4626  4626 D BluetoothMapAppObserver: removeReceiver()
11-23 12:23:13.726  3112  3112 D HeadsetProfile: Bluetooth service disconnected
11-23 12:23:13.726  3694  3822 W QCNEJ   : |CORE| network lost: 100
11-23 12:23:13.726  3112  3112 D BluetoothA2dp: Proxy object disconnected
11-23 12:23:13.726  3112  3112 D BluetoothInputDevice: Proxy object disconnected
11-23 12:23:13.726  3112  3112 D HidProfile: Bluetooth service disconnected
11-23 12:23:13.728  3694  3822 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 12:23:13.728  4626  4695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 12:23:13.727  3112  3112 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 12:23:13.729  3112  3112 D PanProfile: Bluetooth service disconnected
,11-23 12:23:13.729  4626  4626 D SapService: Received stop request...Stopping profile...
,11-23 12:23:13.730  4626  4626 V SapService: stop()
11-23 12:23:13.733  4626  4626 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:13.733  4626  4626 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:13.733  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:13.733  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:13.733  4626  4626 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-23 12:23:13.733  4626  4695 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 12:23:13.734  4626  4626 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 12:23:13.734  4626  4626 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:13.734  4626  4626 V BluetoothAdapterState: isTurningOn()=false
,11-23 12:23:13.734  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:13.734  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:13.734  4626  4626 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 12:23:13.735  4626  4626 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 12:23:13.735  4626  4626 D BluetoothMapService: MAP Service closeService in
11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isTurningOn()=false
,11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 12:23:13.736  4626  4626 D BluetoothMapService: cleanup()
,11-23 12:23:13.736  4626  4626 D BluetoothMapService: MAP Service closeService in
11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isTurningOff()=true
,11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:13.736  4626  4626 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:13.737  4626  4691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 12:23:13.737  4626  4691 D BluetoothAdapterProperties: Setting state to 15
,11-23 12:23:13.737  4626  4691 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 12:23:13.737   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 12:23:13.737  3112  3124 D BluetoothMap: onBluetoothStateChange: up=false
11-23 12:23:13.738  3112  3898 D BluetoothPbap: onBluetoothStateChange: up=false
,11-23 12:23:13.738  4626  4691 I BluetoothAdapterState: Entering BleOnState
11-23 12:23:13.739  3112  3123 D BluetoothPan: onBluetoothStateChange on: false
,11-23 12:23:13.739   926  2916 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 12:23:13.740   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:13.740   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:13.740  3723  3967 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:13.740  3112  3949 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 12:23:13.741  3112  3124 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:13.741  3112  3898 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 12:23:13.741   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:13.742  4626  4691 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 12:23:13.742  4626  4691 D BluetoothAdapterProperties: Setting state to 16
,11-23 12:23:13.742  4626  4691 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-23 12:23:13.743  4626  4691 D BluetoothAdapterProperties: onBleDisable
11-23 12:23:13.743  4626  4691 I BluetoothAdapterState: Entering PendingCommandState
,11-23 12:23:13.744  4626  4692 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 12:23:13.745  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:13.745  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 12:23:13.745  4626  4695 D BluetoothAdapterProperties: Scan Mode:20
,11-23 12:23:13.748  4626  4816 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-23 12:23:13.748  4626  4816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 12:23:13.751  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:23:13.753   926  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 12:23:13.768   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 12:23:13.771  5643  5643 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 12:23:13.781  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 12:23:13.787   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@205a909:true
,11-23 12:23:13.788  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 12:23:13.788   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 12:23:13.789   926  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 12:23:13.789   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-23 12:23:13.789   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 12:23:13.790   507   920 D TetherController: Setting IP forward enable = 0
,11-23 12:23:13.792   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-23 12:23:13.793   926  2916 D DhcpClient: doQuit
,11-23 12:23:13.793   926  2916 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 12:23:13.793   926  5359 D DhcpClient: onQuitting
11-23 12:23:13.793  3409  3409 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 12:23:13.793  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:23:13.795  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 12:23:13.797  5244  5244 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8b2eafc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-23 12:23:13.801  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:13.801  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 12:23:13.802  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:13.802  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 12:23:13.801  5028  5046 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 12:23:13.802  5028  5046 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 12:23:13.802  5028  5046 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 12:23:13.803  5028  5046 E SarControlService: no key has been found,reset the power
11-23 12:23:13.803  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 12:23:13.803  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 12:23:13.803  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 12:23:13.803  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:13.803  5053  5053 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 12:23:13.804  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 12:23:13.804  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 12:23:13.804  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 12:23:13.805  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:13.806  5053  5053 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 12:23:13.808  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ea03000000000000ffffffff]
11-23 12:23:13.809  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-23 12:23:13.809  5053  5067 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 12:23:13.810  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 12:23:13.810  5028  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 12:23:13.811  3409  3409 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 12:23:13.814  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000eb03000000000000ffffffff]
11-23 12:23:13.814  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 12:23:13.814  5053  5067 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 12:23:13.815  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-23 12:23:13.816  5028  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 12:23:13.817  3409  3409 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 12:23:13.819   507   913 W SocketClient: write error (Broken pipe)
11-23 12:23:13.819   507   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-23 12:23:13.819   507   913 W SocketListener: Error sending broadcast (Broken pipe)
,11-23 12:23:13.830  5643  5643 D LocalBluetoothProfileManager: Adding local MAP profile
11-23 12:23:13.832  5643  5643 D BluetoothMap: Create BluetoothMap proxy object
11-23 12:23:13.835   507   920 E Netd    : netlink response contains error (No such file or directory)
11-23 12:23:13.836   507   920 D TetherController: Setting IP forward enable = 0
11-23 12:23:13.836   926  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 12:23:13.840  5643  5643 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-23 12:23:13.848  5643  5643 D DockEventReceiver: finishStartingService: stopping service
11-23 12:23:13.850  3409  3409 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-23 12:23:13.851  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 12:23:13.856  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 12:23:13.856  5643  5643 D DockEventReceiver: finishStartingService: stopping service
11-23 12:23:13.858   926  3707 I ActivityManager: Killing 5384:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 12:23:13.859  3409  3409 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 12:23:13.877   926  2916 D wifi    : In wifi stop Hal
,11-23 12:23:13.877  4990  4990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 12:23:13.877   926  2916 D wifi    : halHandle = 0x7f5a10f0c0, mVM = 0x7f7678d140, mCls = 0x100a02
11-23 12:23:13.877   926  3408 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 12:23:13.877   926  3408 D WifiHAL : Got a signal to exit!!!
11-23 12:23:13.877   926  3408 I WifiHAL : Exit wifi_event_loop
11-23 12:23:13.878   926  2916 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 12:23:13.878   926  2916 E WifiHAL : Event processing terminated
,11-23 12:23:13.878   926  2916 D wifi    : In wifi cleaned up handler
11-23 12:23:13.878   926  2916 I WifiHAL : Internal cleanup completed
11-23 12:23:13.881  4062  4205 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 12:23:13.881  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:13.883  3917  3917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 12:23:13.886  3917  3917 D SystemUpdateService: onCreate
,11-23 12:23:13.889  3917  3917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 12:23:13.896  3917  3917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 12:23:13.899   926  3408 D wifi    : set interface wlan0 flags (DOWN)
11-23 12:23:13.899   926  2916 D WifiNative-HAL: HAL event thread stopped successfully
11-23 12:23:13.901  3917  5381 I iu.UploadsManager: num queued entries: 0
11-23 12:23:13.901  3917  5381 I iu.UploadsManager: num updated entries: 0
,11-23 12:23:13.903   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:13.905  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 12:23:13.907  3917  3917 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 12:23:13.907  3917  5680 I SystemUpdateService: active receiver: enabled
11-23 12:23:13.909  3917  5381 I iu.SyncManager: NEXT; no task
,11-23 12:23:13.911  3917  5680 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 12:23:13.912  3917  5680 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-23 12:23:13.912  3917  5680 I SystemUpdateService: now status is 0 (complete)
11-23 12:23:13.913  3917  5680 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 12:23:13.913  3917  5680 I SystemUpdateService: file has been verified
11-23 12:23:13.913  3917  5680 I SystemUpdateService: OTA package size = 21989297
,11-23 12:23:13.918   926  3382 I ActivityManager: Start proc 5682:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 12:23:13.923  3917  5680 I SystemUpdateService: showing system update notification
,11-23 12:23:13.933   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 12:23:13.935  3917  3917 D SystemUpdateService: onDestroy
,11-23 12:23:13.951  5682  5682 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 12:23:13.953  5682  5682 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 12:23:13.954  4626  4695 I bt_hci  : shut_down
,11-23 12:23:13.959  4626  4699 I bt_vendor: low_power_mode_cb
,11-23 12:23:13.961  4626  4699 D bt_hwcfg: hw_epilog_process
,11-23 12:23:13.961  5682  5682 D SprintDMHelper: simOperator: 
11-23 12:23:13.961  5682  5682 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 12:23:13.964  4626  4699 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 12:23:13.964  4626  4699 I bt_vendor: epilog_cb
11-23 12:23:13.964  4626  4699 I bt_hci  : epilog_finished_callback
,11-23 12:23:13.969  4626  4695 I bt_hci_h4: hal_close
,11-23 12:23:13.970  4626  4695 I bt_userial_vendor: device fd = 54 close
,11-23 12:23:13.974  4990  5694 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 12:23:13.977   926  3381 I ActivityManager: Killing 5244:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 12:23:14.006   926   937 I ActivityManager: Start proc 5695:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 12:23:14.034  5695  5695 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 12:23:14.042   926   937 I ActivityManager: Killing 3830:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 12:23:14.077  4626  4692 D bt_stack_manager: event_shut_down_stack finished.
,11-23 12:23:14.078  4626  4691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 12:23:14.079  4626  4691 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 12:23:14.080  4626  4626 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 12:23:14.080  4626  4626 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 12:23:14.080  4626  4626 D BtGatt.GattService: stop()
11-23 12:23:14.080  4626  4626 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 12:23:14.083  4626  4626 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:14.083  4626  4626 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:14.083  4626  4626 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:14.083  4626  4626 V BluetoothAdapterState: isBleTurningOff()=true
11-23 12:23:14.083  4626  4691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 12:23:14.084  4626  4691 D BluetoothAdapterProperties: Setting state to 10
,11-23 12:23:14.084  4626  4691 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 12:23:14.084  4626  4691 I BluetoothAdapterState: Entering OffState
11-23 12:23:14.085   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 12:23:14.091  4626  4626 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 12:23:14.092  4626  4626 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 12:23:14.092  4626  4626 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-23 12:23:14.093  4626  4692 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 12:23:14.099  4626  4626 I art     : System.exit called, status: 0
11-23 12:23:14.099  4626  4626 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-23 12:23:14.102   926   943 D Tethering: InitialState.processMessage what=4
11-23 12:23:14.106   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 12:23:14.128   926  3128 I ActivityManager: Process com.android.bluetooth (pid 4626) has died
,11-23 12:23:14.903   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 12:23:18.711   926  3382 D WifiService: setWifiEnabled: true pid=5583, uid=10077
11-23 12:23:18.711   926  3382 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 12:23:18.723   507   920 D SoftapController: Softap fwReload - Ok
,11-23 12:23:18.728   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:18.729   507   920 D CommandListener: Trying to bring down wlan0
,11-23 12:23:18.731   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 12:23:18.738   926  2916 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 12:23:19.330   926  2916 D wifi    : set interface wlan0 flags (UP)
,11-23 12:23:19.335   926  2916 I WifiHAL : Initializing wifi
,11-23 12:23:19.336   926  2916 I WifiHAL : Creating socket
,11-23 12:23:19.337   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 12:23:19.341   926  2916 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 12:23:19.342   926  2916 D wifi    : Did set static halHandle = 0x7f5a10f0c0
,11-23 12:23:19.342   926  2916 D wifi    : halHandle = 0x7f5a10f0c0, mVM = 0x7f7678d140, mCls = 0x1019ea
11-23 12:23:19.342   926  2916 D wifi    : array field set
11-23 12:23:19.342   926  2916 I WifiNative-HAL: interface[0] = wlan0
11-23 12:23:19.344   926  5711 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546971906240
11-23 12:23:19.344   926  5711 D wifi    : waitForHalEvents called, vm = 0x7f7678d140, obj = 0x1019ea, env = 0x7f5b91d4c0
,11-23 12:23:19.417  5712  5712 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 12:23:19.449   926  2916 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 12:23:19.457  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:19.478  5712  5712 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 12:23:19.513  5712  5712 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 12:23:19.513  5712  5712 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 12:23:19.525   926  2916 D WifiConfigStore: Loading config and enabling all networks 
,11-23 12:23:19.528  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:19.528  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 12:23:19.528  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:19.528  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 12:23:19.541   926  2916 D WifiConfigStore: loaded 0 passpoint configs
,11-23 12:23:19.542   926  2916 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 12:23:19.542   926  2916 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 12:23:19.543   926  2916 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 12:23:19.543   926  2916 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 12:23:19.543   926  2916 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-23 12:23:19.544   926  2916 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 12:23:19.544   926  2916 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 12:23:19.544   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 12:23:19.544   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-23 12:23:19.544   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 12:23:19.544   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 12:23:19.544   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 12:23:19.546   926  2916 D WifiNative-HAL: Setting external_sim to 1
,11-23 12:23:19.546   926  2916 D wifi    : setting dfs flag to true, 0x7f6bcbd3a0
11-23 12:23:19.546  4990  4990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 12:23:19.546   926  2916 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 12:23:19.546   926  2916 D wifi    : setting scan oui 0x7f6bcbd3a0
11-23 12:23:19.546   926  2916 D WifiHAL : Sending mac address OUI
,11-23 12:23:19.549   926  2916 E native  : do suspend false
,11-23 12:23:19.555   926  2916 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 12:23:19.555   926   926 D RttService: SCAN_AVAILABLE : 3
11-23 12:23:19.556   926  3026 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 12:23:19.559   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 12:23:19.560   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:19.566   926  2915 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-23 12:23:19.566   926  2915 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 12:23:19.573   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128741 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-23 12:23:19.574   926  2915 D WifiNative-HAL: p2pGetDeviceAddress
11-23 12:23:19.574   926  2915 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 12:23:19.904   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:20.906   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:21.907   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:22.652  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:22.666  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:22.674  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:22.682  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:22.714   926  2916 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 12:23:22.715   926  2916 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 12:23:22.716   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 12:23:22.729   926  2916 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 12:23:22.763   926  2916 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 12:23:22.769  5712  5712 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 12:23:22.908   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:23.198  5712  5712 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 12:23:23.227  5712  5712 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-23 12:23:23.227  5712  5712 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 12:23:23.237   926  2916 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 12:23:23.238   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 12:23:23.238   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 12:23:23.254   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 12:23:23.268   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:23.274   926  2916 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 12:23:23.281   926  5721 D DhcpClient: Receive thread started
,11-23 12:23:23.286   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 12:23:23.286   926  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 12:23:23.287   926  2918 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 12:23:23.368   926  2916 E native  : do suspend false
,11-23 12:23:23.380   926  5720 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 12:23:23.394   926  5721 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-23 12:23:23.395   926  5720 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
11-23 12:23:23.397   926  5720 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 12:23:23.414   926  5721 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 12:23:23.415   926  5720 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 12:23:23.417   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:23.422   926  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 12:23:23.424   926  5720 D DhcpClient: Scheduling renewal in 86399s
,11-23 12:23:23.432   926  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-23 12:23:23.433   926  2916 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 12:23:23.434   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 12:23:23.440   926  2916 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 12:23:23.444   926  2918 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 12:23:23.483   926  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-23 12:23:23.484   926  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-23 12:23:23.485   926  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 12:23:23.486   926  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 12:23:23.488   926  2918 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 12:23:23.494   926  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 12:23:23.498   926  2918 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 12:23:23.498   926  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 12:23:23.498   926  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-23 12:23:23.498   926  2916 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 12:23:23.498   926  2918 D ConnectivityService:    accepting network in place of null
,11-23 12:23:23.498   926  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 12:23:23.499   926  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 12:23:23.507   926  5719 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132675, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 12:23:23.522   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 12:23:23.546   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 12:23:23.549   926  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 12:23:23.550   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 12:23:23.550  3694  3822 W QCNEJ   : |CORE| network available: 101
,11-23 12:23:23.551   926  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 12:23:23.552   926   943 D Tethering: MasterInitialState.processMessage what=3
11-23 12:23:23.555  3694  3822 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 12:23:23.556  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:23:23.556  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 12:23:23.556  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:23.556  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 12:23:23.557  3694  3822 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 12:23:23.557  3694  3822 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 12:23:23.566  5028  5046 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 12:23:23.566  5028  5046 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 12:23:23.566  5028  5046 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 12:23:23.566  5028  5046 E SarControlService: no key has been found,reset the power
11-23 12:23:23.567  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 12:23:23.567  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 12:23:23.567  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 12:23:23.567  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:23.567  5053  5053 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 12:23:23.572  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 12:23:23.573  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 12:23:23.573  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 12:23:23.573  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:23.573  5053  5053 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 12:23:23.574  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 12:23:23.575  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ec03000000000000ffffffff]
,11-23 12:23:23.575  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 12:23:23.575  5053  5067 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-23 12:23:23.576  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 12:23:23.577  3917  3917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 12:23:23.581  5028  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 12:23:23.582  3917  3917 D SystemUpdateService: onCreate
,11-23 12:23:23.586   926  5718 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:804::200e
,11-23 12:23:23.590  3917  3917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 12:23:23.592  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ed03000000000000ffffffff]
11-23 12:23:23.592  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-23 12:23:23.592  5053  5067 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-23 12:23:23.592  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 12:23:23.593  5028  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 12:23:23.601  3917  3917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 12:23:23.607  3917  5381 I iu.UploadsManager: num queued entries: 0
,11-23 12:23:23.608  3917  5381 I iu.UploadsManager: num updated entries: 0
,11-23 12:23:23.611  3917  5732 I SystemUpdateService: active receiver: enabled
,11-23 12:23:23.612  3917  5381 I iu.SyncManager: NEXT; no task
,11-23 12:23:23.615  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 12:23:23.617  3917  3917 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 12:23:23.619  5682  5682 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 12:23:23.622  5682  5682 D SprintDMHelper: simOperator: 
,11-23 12:23:23.622  5682  5682 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 12:23:23.643   926  5718 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 11:23:23 GMT], X-Android-Received-Millis=[1479900203643], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479900203616]}
,11-23 12:23:23.644   926  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 12:23:23.644   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-23 12:23:23.644   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 12:23:23.645   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 12:23:23.654  3917  5732 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 12:23:23.660  3917  5732 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 12:23:23.660  3917  5732 I SystemUpdateService: now status is 0 (complete)
11-23 12:23:23.660  3917  5732 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 12:23:23.660  3917  5732 I SystemUpdateService: file has been verified
11-23 12:23:23.660  3917  5732 I SystemUpdateService: OTA package size = 21989297
,11-23 12:23:23.666  3917  5732 I SystemUpdateService: showing system update notification
,11-23 12:23:23.673   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 12:23:23.675  3917  3917 D SystemUpdateService: onDestroy
,11-23 12:23:23.721   926  3707 D WifiService: setWifiEnabled: false pid=5583, uid=10077
,11-23 12:23:23.721   926  3707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 12:23:23.722   926  2916 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 12:23:23.722   926  2916 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 12:23:23.722   926  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 12:23:23.722   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 12:23:23.730   926  5720 D DhcpClient: Clearing IP address
,11-23 12:23:23.730   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 12:23:23.732   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:23.739  3546  5743 V NativeCrypto: Read error: ssl=0x7f70705000: I/O error during system call, Connection timed out
11-23 12:23:23.739  3546  5743 V NativeCrypto: SSL shutdown failed: ssl=0x7f70705000: I/O error during system call, Broken pipe
,11-23 12:23:23.741   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 12:23:23.741   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-23 12:23:23.746   926  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 12:23:23.747   533   533 E Parcel  : Reading a NULL string not supported here.
11-23 12:23:23.747  3694  3822 W QCNEJ   : |CORE| network lost: 101
11-23 12:23:23.748  3694  3822 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-23 12:23:23.753   926   926 D RttService: SCAN_AVAILABLE : 1
,11-23 12:23:23.753   926  3026 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 12:23:23.755   926  2916 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 12:23:23.755  4990  5737 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-23 12:23:23.757   926  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 12:23:23.758   926  5721 D DhcpClient: Receive thread stopped
,11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.21.78 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnec,ted(IoBridge.java:223)
11-23 12:23:23.767  4990  5737 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-23 12:23:23.767  4990  5737 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 12:23:23.772   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 12:23:23.790   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 12:23:23.791   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-23 12:23:23.791   926  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 12:23:23.791   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 12:23:23.792   926  2916 D DhcpClient: doQuit
,11-23 12:23:23.792   926  2916 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 12:23:23.793   926  5720 D DhcpClient: onQuitting
11-23 12:23:23.793  5712  5712 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 12:23:23.793   926   943 D Tethering: MasterInitialState.processMessage what=3
11-23 12:23:23.796  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:23.796  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 12:23:23.796  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 12:23:23.796  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 12:23:23.798  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 12:23:23.800  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:23.803  3917  3917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 12:23:23.805  5028  5046 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 12:23:23.805  5028  5046 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 12:23:23.805  5028  5046 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 12:23:23.805  5028  5046 E SarControlService: no key has been found,reset the power
,11-23 12:23:23.805  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-23 12:23:23.805  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 12:23:23.806  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 12:23:23.806  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:23.806  5053  5053 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 12:23:23.808  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 12:23:23.808  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 12:23:23.808  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 12:23:23.809  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 12:23:23.809  5053  5053 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 12:23:23.811  3917  3917 D SystemUpdateService: onCreate
11-23 12:23:23.813  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ee03000000000000ffffffff]
11-23 12:23:23.813  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 12:23:23.813  5053  5067 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,11-23 12:23:23.813  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 12:23:23.813  5028  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 12:23:23.814  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 12:23:23.814  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ef03000000000000ffffffff]
11-23 12:23:23.814  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 12:23:23.814  5053  5067 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-23 12:23:23.815  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 12:23:23.815  5028  5038 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 12:23:23.817  5712  5712 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 12:23:23.820  3917  3917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 12:23:23.823  3917  5752 I SystemUpdateService: active receiver: enabled
11-23 12:23:23.829  3917  3917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 12:23:23.835  3917  5381 I iu.UploadsManager: num queued entries: 0
,11-23 12:23:23.835  3917  5381 I iu.UploadsManager: num updated entries: 0
,11-23 12:23:23.836  3917  5381 I iu.SyncManager: NEXT; no task
,11-23 12:23:23.837  3917  5752 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 12:23:23.839  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 12:23:23.841  3917  3917 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 12:23:23.842  5682  5682 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 12:23:23.844   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-23 12:23:23.847  5682  5682 D SprintDMHelper: simOperator: 
11-23 12:23:23.847  5682  5682 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 12:23:23.847  5712  5712 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 12:23:23.857  3917  5752 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 12:23:23.857  3917  5752 I SystemUpdateService: now status is 0 (complete)
11-23 12:23:23.857  3917  5752 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 12:23:23.857  3917  5752 I SystemUpdateService: file has been verified
11-23 12:23:23.857  3917  5752 I SystemUpdateService: OTA package size = 21989297
,11-23 12:23:23.859  4990  5755 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-23 12:23:23.859  5712  5712 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 12:23:23.879  3917  5752 I SystemUpdateService: showing system update notification
,11-23 12:23:23.885   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 12:23:23.886  3917  3917 D SystemUpdateService: onDestroy
,11-23 12:23:23.908   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:23.964   926  2916 D wifi    : In wifi stop Hal,
11-23 12:23:23.964   926  2916 D wifi    : halHandle = 0x7f5a10f0c0, mVM = 0x7f7678d140, mCls = 0x1019ea
11-23 12:23:23.964   926  5711 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-23 12:23:23.964   926  5711 D WifiHAL : Got a signal to exit!!!
11-23 12:23:23.964   926  5711 I WifiHAL : Exit wifi_event_loop
11-23 12:23:23.965   926  2916 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 12:23:23.965   926  2916 E WifiHAL : Event processing terminated
11-23 12:23:23.965   926  2916 D wifi    : In wifi cleaned up handler
11-23 12:23:23.965   926  2916 I WifiHAL : Internal cleanup completed
,11-23 12:23:23.967  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:23:23.967  4062  4205 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 12:23:23.971  4990  4990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 12:23:23.987   926  5711 D wifi    : set interface wlan0 flags (DOWN)
,11-23 12:23:23.987   926  2916 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 12:23:24.194   926   943 D Tethering: InitialState.processMessage what=4
,11-23 12:23:24.200   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 12:23:24.550   926  2918 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 12:23:24.909   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 12:23:28.759   926   943 I ActivityManager: Start proc 5757:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 12:23:28.855  5757  5757 D AdapterServiceConfig: Adding HeadsetService
,11-23 12:23:28.855  5757  5757 D AdapterServiceConfig: Adding A2dpService
11-23 12:23:28.855  5757  5757 D AdapterServiceConfig: Adding HidService
11-23 12:23:28.855  5757  5757 D AdapterServiceConfig: Adding HealthService
11-23 12:23:28.856  5757  5757 D AdapterServiceConfig: Adding PanService
11-23 12:23:28.856  5757  5757 D AdapterServiceConfig: Adding GattService
11-23 12:23:28.856  5757  5757 D AdapterServiceConfig: Adding BluetoothMapService
11-23 12:23:28.856  5757  5757 D AdapterServiceConfig: Adding SapService
,11-23 12:23:28.866   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50926e2:true
,11-23 12:23:28.867  5757  5757 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 12:23:28.870  5757  5757 I bt_bluedroid: init
,11-23 12:23:28.870  5757  5769 I BluetoothAdapterState: Entering OffState
,11-23 12:23:28.872  5757  5770 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 12:23:28.873  5757  5770 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 12:23:28.873  5757  5770 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 12:23:28.873  5757  5770 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 12:23:28.873  5757  5757 I bt_bluedroid: get_profile_interface socket
,11-23 12:23:28.875  5757  5773 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 12:23:28.876  5757  5757 I bt_bluedroid: get_profile_interface sdp
11-23 12:23:28.877  5757  5773 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 12:23:28.881  5757  5768 I bt_bluedroid: config_hci_snoop_log
,11-23 12:23:28.882   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 12:23:28.886  5757  5769 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 12:23:28.887  5757  5769 D BluetoothAdapterProperties: Setting state to 14
11-23 12:23:28.887  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 12:23:28.889  5757  5769 D BluetoothBondStateMachine: make
,11-23 12:23:28.890  5757  5774 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 12:23:28.893  5757  5769 I BluetoothAdapterState: Entering PendingCommandState
,11-23 12:23:28.894  5757  5757 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 12:23:28.897  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:28.898  5757  5757 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 12:23:28.898  5757  5757 D BtGatt.GattService: Received start request. Starting profile...
11-23 12:23:28.898  5757  5757 D BtGatt.GattService: start()
11-23 12:23:28.899  5757  5757 I bt_bluedroid: get_profile_interface gatt
,11-23 12:23:28.900  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:28.900  5757  5757 D BtGatt.AdvertiseManager: advertise manager created
,11-23 12:23:28.906  5757  5757 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:28.906  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:28.906  5757  5757 V BluetoothAdapterState: isBleTurningOn()=true
11-23 12:23:28.906  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:28.906  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 12:23:28.908  5757  5769 I bt_bluedroid: bt_bluedroid
,11-23 12:23:28.908  5757  5770 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 12:23:28.908  5757  5770 I bt_hci  : start_up
,11-23 12:23:28.914  5757  5770 I bt_vendor: alloc value 0xf4049871
11-23 12:23:28.914  5757  5770 I bt_vendor: init
11-23 12:23:28.914  5757  5770 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 12:23:28.914  5757  5770 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 12:23:29.025  5757  5770 D bt_hci  : start_up starting async portion
11-23 12:23:29.026  5757  5777 I bt_hci  : event_finish_startup
,11-23 12:23:29.026  5757  5777 I bt_hci_h4: hal_open
11-23 12:23:29.026  5757  5777 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-23 12:23:29.022  5778  5778 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 12:23:29.030  5757  5777 I bt_userial_vendor: device fd = 54 open
,11-23 12:23:29.044  5757  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 12:23:29.047  5757  5777 D bt_hwcfg: Chipset BCM4358A3
,11-23 12:23:29.047  5757  5777 D bt_hwcfg: Target name = [BCM4358A3]
,11-23 12:23:29.048  5757  5777 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 12:23:29.431  5757  5777 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 12:23:29.432  5757  5777 D bt_hwcfg: Settlement delay -- 100 ms
,11-23 12:23:29.432  5757  5777 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 12:23:29.565  5757  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 12:23:29.566  5757  5777 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 12:23:29.567  5757  5777 I bt_hwcfg: vendor lib fwcfg completed
,11-23 12:23:29.567  5757  5777 I bt_vendor: firmware callback
,11-23 12:23:29.567  5757  5777 I bt_hci  : firmware_config_callback
,11-23 12:23:29.577  5757  5780 I bt_btu  : btu_task pending for preload complete event
,11-23 12:23:29.577  5757  5780 I bt_btu_task: Bluetooth chip preload is complete
,11-23 12:23:29.577  5757  5780 I bt_btu  : btu_task received preload complete event
,11-23 12:23:29.583  5757  5780 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 12:23:29.583  5757  5780 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 12:23:29.583  5757  5780 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 12:23:29.583  5757  5780 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 12:23:29.583  5757  5780 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_SDP
,11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 12:23:29.584  5757  5780 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 12:23:29.585  5757  5780 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 12:23:29.585  5757  5780 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 12:23:29.666  5757  5780 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fc7549
,11-23 12:23:29.667  5757  5780 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fc7549 
,11-23 12:23:29.692  5757  5773 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 12:23:29.693  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 12:23:29.694  5757  5773 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 12:23:29.696  5757  5773 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 12:23:29.699  5757  5773 D BluetoothAdapterProperties: Scan Mode:20
11-23 12:23:29.699  5757  5773 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 12:23:29.699  5757  5773 D bt_hci  : do_postload posting postload work item
11-23 12:23:29.699  5757  5777 I bt_hci  : event_postload
11-23 12:23:29.700  5757  5777 I bt_vendor: sco_config_cb
11-23 12:23:29.700  5757  5777 I bt_hci  : sco_config_callback postload finished.
,11-23 12:23:29.703  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:29.706  5757  5773 D bt_bte_conf: Device ID record 1 : primary
,11-23 12:23:29.706  5757  5773 D bt_bte_conf:   vendorId            = 000f
11-23 12:23:29.706  5757  5773 D bt_bte_conf:   vendorIdSource      = 0001
11-23 12:23:29.706  5757  5773 D bt_bte_conf:   product             = 1200
11-23 12:23:29.706  5757  5773 D bt_bte_conf:   version             = 1436
11-23 12:23:29.706  5757  5773 D bt_bte_conf:   clientExecutableURL = 
11-23 12:23:29.706  5757  5773 D bt_bte_conf:   serviceDescription  = 
11-23 12:23:29.706  5757  5773 D bt_bte_conf:   documentationURL    = 
11-23 12:23:29.707  5757  5773 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 12:23:29.707  5757  5770 D bt_stack_manager: event_start_up_stack finished
,11-23 12:23:29.708  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-23 12:23:29.708  5757  5769 D BluetoothAdapterProperties: Setting state to 15
11-23 12:23:29.709  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 12:23:29.710  5757  5769 I BluetoothAdapterState: Entering BleOnState
11-23 12:23:29.711  5757  5777 I bt_vendor: low_power_mode_cb
,11-23 12:23:29.714  5757  5769 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 12:23:29.714  5757  5769 D BluetoothAdapterProperties: Setting state to 11
11-23 12:23:29.714  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 12:23:29.718  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:29.719  5757  5757 D HeadsetService: Received start request. Starting profile...
11-23 12:23:29.722  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:23:29.722  5757  5757 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 12:23:29.723  5757  5757 D HeadsetStateMachine: make
,11-23 12:23:29.733  5757  5769 I BluetoothAdapterState: Entering PendingCommandState
11-23 12:23:29.733  5757  5757 D HeadsetStateMachine: max_hf_connections = 1
11-23 12:23:29.733  5757  5757 I bt_bluedroid: get_profile_interface handsfree
11-23 12:23:29.733  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 12:23:29.734  5757  5773 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-23 12:23:29.736  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:29.737  5757  5757 D A2dpService: Received start request. Starting profile...
11-23 12:23:29.737  5757  5757 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 12:23:29.738  5757  5757 I bt_bluedroid: get_profile_interface avrcp
,11-23 12:23:29.743  5757  5757 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 12:23:29.743  5757  5757 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 12:23:29.743  5757  5757 D A2dpStateMachine: make
11-23 12:23:29.744  5757  5757 I bt_bluedroid: get_profile_interface a2dp
11-23 12:23:29.745  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 12:23:29.746  5757  5788 D A2dpStateMachine: Enter Disconnected: -2
,11-23 12:23:29.747  5757  5757 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 12:23:29.748  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:29.749  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 12:23:29.751  5643  5643 D BluetoothInputDevice: Proxy object connected
11-23 12:23:29.751  5757  5757 D HidService: Received start request. Starting profile...
,11-23 12:23:29.751  5757  5757 I bt_bluedroid: get_profile_interface hidhost
11-23 12:23:29.752  5757  5757 D HidService: setHidService(): set to: null
11-23 12:23:29.752  5757  5773 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fa856d
11-23 12:23:29.752  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 12:23:29.752  5643  5643 D HidProfile: Bluetooth service connected
11-23 12:23:29.752  5757  5757 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 12:23:29.753  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:29.754  5757  5757 D HealthService: Received start request. Starting profile...
11-23 12:23:29.755  5757  5757 I bt_bluedroid: get_profile_interface health
11-23 12:23:29.756  5757  5757 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 12:23:29.756  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:29.757  5757  5757 D PanService: Received start request. Starting profile...
11-23 12:23:29.758  5643  5643 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 12:23:29.758  5757  5757 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 12:23:29.758  5757  5757 I bt_bluedroid: get_profile_interface pan
11-23 12:23:29.758  5757  5773 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 12:23:29.758  5643  5643 D PanProfile: Bluetooth service connected
,11-23 12:23:29.761  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:29.762  5643  5643 D BluetoothMap: Proxy object connected
,11-23 12:23:29.762  5757  5757 D BluetoothMapService: Received start request. Starting profile...
11-23 12:23:29.763  5757  5757 D BluetoothMapService: start()
11-23 12:23:29.763  5643  5643 D MapProfile: Bluetooth service connected
11-23 12:23:29.763  5643  5643 D BluetoothMap: getConnectedDevices()
11-23 12:23:29.763  5643  5643 D BluetoothMap: Bluetooth is Not enabled
,11-23 12:23:29.765  5757  5757 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 12:23:29.766  5757  5757 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 12:23:29.766  5757  5757 D BluetoothMapAppObserver: createReceiver()
11-23 12:23:29.767  5757  5757 D BluetoothMapAppObserver: initObservers()
,11-23 12:23:29.767  5757  5757 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 12:23:29.773  5757  5757 V SapService: SapBinder()
,11-23 12:23:29.773  5757  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:29.774  5757  5757 D SapService: Received start request. Starting profile...
11-23 12:23:29.774  5757  5757 V SapService: start()
,11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.776  5757  5786 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.776  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:29.777  5757  5757 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:29.777  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.777  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.777  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:29.777  5757  5757 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:29.777  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.778  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.779  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 12:23:29.780  5757  5757 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:29.780  5757  5757 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:29.780  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:29.780  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 12:23:29.780  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-23 12:23:29.780  5757  5769 D BluetoothAdapterProperties: ScanMode =  20
11-23 12:23:29.780  5757  5769 D BluetoothAdapterProperties: State =  11
11-23 12:23:29.781  5757  5769 D BluetoothAdapterProperties: Setting state to 12
11-23 12:23:29.781  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 12:23:29.781  5757  5769 I BluetoothAdapterState: Entering OnState
11-23 12:23:29.781   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 12:23:29.782  5643  5657 D BluetoothPan: onBluetoothStateChange on: true
11-23 12:23:29.782  5757  5773 D BluetoothAdapterProperties: Scan Mode:21
11-23 12:23:29.783  3112  3124 D BluetoothMap: onBluetoothStateChange: up=true
11-23 12:23:29.783  5757  5773 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 12:23:29.783   926   926 D BluetoothA2dp: Proxy object connected
11-23 12:23:29.783  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-23 12:23:29.784  3112  3112 D BluetoothMap: Proxy object connected
11-23 12:23:29.784  5643  5655 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 12:23:29.784  3112  3112 D MapProfile: Bluetooth service connected
,11-23 12:23:29.784  3112  3112 D BluetoothMap: getConnectedDevices()
11-23 12:23:29.786  3112  3949 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 12:23:29.788  3112  3123 D BluetoothPan: onBluetoothStateChange on: true
,11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:29.788  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 12:23:29.789   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:29.789  3112  3112 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 12:23:29.789   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:29.789  3112  3112 D PanProfile: Bluetooth service connected
,11-23 12:23:29.789  3723  3745 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:29.790  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 12:23:29.790  5643  5657 D BluetoothMap: onBluetoothStateChange: up=true
11-23 12:23:29.790  3112  3898 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 12:23:29.791  5757  5757 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 12:23:29.792  3112  3112 D BluetoothInputDevice: Proxy object connected
,11-23 12:23:29.792  5643  5655 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 12:23:29.792  3112  3112 D HidProfile: Bluetooth service connected
11-23 12:23:29.792  3112  3123 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:29.792  5757  5757 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 12:23:29.792  3112  3124 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 12:23:29.793  5757  5757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 12:23:29.795   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 12:23:29.795  3112  3112 D BluetoothA2dp: Proxy object connected
,11-23 12:23:29.796   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 12:23:29.797  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-23 12:23:29.797  5757  5757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 12:23:29.798  5643  5643 D LocalBluetoothProfileManager: Adding local A2DP profile
11-23 12:23:29.798  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:29.800  5757  5757 D ObexServerSockets: Succeed to create listening sockets 
11-23 12:23:29.800  5757  5757 D ObexServerSockets0: startAccept()
11-23 12:23:29.800  5757  5757 D ObexServerSockets0: prepareForNewConnect()
,11-23 12:23:29.802  5643  5643 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-23 12:23:29.803  5757  5757 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 12:23:29.803  5757  5757 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 12:23:29.804  5757  5795 D ObexServerSockets0: Accepting socket connection...
11-23 12:23:29.804  5757  5757 D BluetoothMapService: onReceive
11-23 12:23:29.804  5757  5757 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 12:23:29.804  5757  5796 D ObexServerSockets0: Accepting socket connection...
11-23 12:23:29.804  5757  5757 D BluetoothMapService: STATE_ON
11-23 12:23:29.806  5757  5797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 12:23:29.807  5757  5797 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 12:23:29.807  5757  5797 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 12:23:29.808  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 12:23:29.810  5643  5643 D BluetoothA2dp: Proxy object connected
,11-23 12:23:29.814  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 12:23:29.820  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,11-23 12:23:29.822  5643  5643 D BluetoothPbap: Proxy object connected
11-23 12:23:29.823  5643  5643 D PbapServerProfile: Bluetooth service connected
,11-23 12:23:29.825  3112  3112 D BluetoothPbap: Proxy object connected
11-23 12:23:29.825  3112  3112 D PbapServerProfile: Bluetooth service connected
,11-23 12:23:29.829  5757  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 12:23:29.837  5757  5757 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 12:23:29.838  5757  5757 D ObexServerSockets0: prepareForNewConnect()
,11-23 12:23:29.841  5757  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 12:23:29.843  5757  5805 I BtOppRfcommListener: Accept thread started.
,11-23 12:23:29.890   926   926 D BluetoothHeadset: Proxy object connected
,11-23 12:23:29.890   926   926 D BluetoothHeadset: Proxy object connected
11-23 12:23:29.891  3723  3967 D BluetoothHeadset: Proxy object connected
,11-23 12:23:29.892  3112  3949 D BluetoothHeadset: Proxy object connected
,11-23 12:23:29.892  3112  3112 D HeadsetProfile: Bluetooth service connected
11-23 12:23:29.892   926   926 D BluetoothHeadset: Proxy object connected
11-23 12:23:29.893  3112  3898 D BluetoothHeadset: Proxy object connected
11-23 12:23:29.894  3112  3112 D HeadsetProfile: Bluetooth service connected
11-23 12:23:29.896   926   943 D BluetoothHeadset: Proxy object connected
,11-23 12:23:29.904  5643  5655 D BluetoothHeadset: Proxy object connected
,11-23 12:23:29.905  5643  5643 D HeadsetProfile: Bluetooth service connected
,11-23 12:23:31.505   926  2918 D ConnectivityService: handlePromptUnvalidated 101
,11-23 12:23:31.742  3631  3794 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-23 12:23:31.742  3631  3794 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-23 12:23:31.768  3546  3546 I ConfigService: onCreate
,11-23 12:23:33.739  5757  5769 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 12:23:33.740  5757  5769 D BluetoothAdapterProperties: Setting state to 13
,11-23 12:23:33.740  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-23 12:23:33.741  5757  5769 D BluetoothAdapterProperties: onBluetoothDisable()
,11-23 12:23:33.743  5757  5769 I BluetoothAdapterState: Entering PendingCommandState
,11-23 12:23:33.753  5757  5757 D BluetoothMapService: onReceive
11-23 12:23:33.753  5757  5757 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 12:23:33.753  5757  5757 D BluetoothMapService: STATE_TURNING_OFF
11-23 12:23:33.755  5757  5757 D BluetoothMapService: MAP Service closeService in
,11-23 12:23:33.755  5757  5757 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 12:23:33.755  5757  5757 D ObexServerSockets0: shutdown(block = true)
11-23 12:23:33.757  5757  5757 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 12:23:33.757  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:33.757  5583  5583 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 12:23:33.757  5757  5782 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 12:23:33.757  5757  5757 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 12:23:33.757  5757  5796 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 12:23:33.758  5757  5795 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 12:23:33.758  5583  5583 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 12:23:33.758  5583  5583 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 12:23:33.758  5757  5773 D BluetoothAdapterProperties: Scan Mode:20
11-23 12:23:33.759  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 12:23:33.761  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 12:23:33.763  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:33.764  5757  5757 I BtOppRfcommListener: stopping Accept Thread
11-23 12:23:33.765  5757  5805 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-23 12:23:33.765  5757  5805 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 12:23:33.772  5757  5757 D HeadsetService: Received stop request...Stopping profile...
,11-23 12:23:33.777   926   926 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:33.778  5643  5655 D BluetoothHeadset: Proxy object disconnected
,11-23 12:23:33.778   926   926 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:33.778  5757  5757 D A2dpService: Received stop request...Stopping profile...
11-23 12:23:33.778  3723  3951 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:33.779  3112  3898 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:33.779  5757  5788 D A2dpStateMachine: Exit Disconnected: -1
11-23 12:23:33.780   926   926 D BluetoothHeadset: Proxy object disconnected
11-23 12:23:33.781  5643  5643 D DockEventReceiver: finishStartingService: stopping service
11-23 12:23:33.781  3112  3112 D HeadsetProfile: Bluetooth service disconnected
11-23 12:23:33.781   926   926 D BluetoothA2dp: Proxy object disconnected
11-23 12:23:33.782  3112  3112 D BluetoothA2dp: Proxy object disconnected
11-23 12:23:33.782  5643  5643 D HeadsetProfile: Bluetooth service disconnected
,11-23 12:23:33.782  5643  5643 D BluetoothA2dp: Proxy object disconnected
11-23 12:23:33.783  5757  5757 D HidService: Received stop request...Stopping profile...
11-23 12:23:33.783  5757  5757 D HidService: Stopping Bluetooth HidService
11-23 12:23:33.784  5643  5643 D BluetoothInputDevice: Proxy object disconnected
11-23 12:23:33.784  5643  5643 D HidProfile: Bluetooth service disconnected
11-23 12:23:33.786  3112  3112 D BluetoothInputDevice: Proxy object disconnected
11-23 12:23:33.786  3112  3112 D HidProfile: Bluetooth service disconnected
,11-23 12:23:33.789  5757  5757 D HealthService: Received stop request...Stopping profile...
,11-23 12:23:33.789  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 12:23:33.794  5757  5757 D PanService: Received stop request...Stopping profile...
,11-23 12:23:33.795  3112  3112 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-23 12:23:33.795  3112  3112 D PanProfile: Bluetooth service disconnected
11-23 12:23:33.796  5643  5643 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 12:23:33.796  5757  5757 D BluetoothMapService: Received stop request...Stopping profile...
11-23 12:23:33.796  5757  5757 D BluetoothMapService: stop()
11-23 12:23:33.796  5643  5643 D PanProfile: Bluetooth service disconnected
,11-23 12:23:33.797  5757  5757 D BluetoothMapAppObserver: deinitObservers()
,11-23 12:23:33.797  5757  5757 D BluetoothMapAppObserver: removeReceiver()
11-23 12:23:33.798  3112  3112 D BluetoothMap: Proxy object disconnected
11-23 12:23:33.798  3112  3112 D MapProfile: Bluetooth service disconnected
11-23 12:23:33.799  5643  5643 D BluetoothMap: Proxy object disconnected
11-23 12:23:33.799  5757  5757 D SapService: Received stop request...Stopping profile...
11-23 12:23:33.799  5643  5643 D MapProfile: Bluetooth service disconnected
,11-23 12:23:33.799  5757  5757 V SapService: stop()
11-23 12:23:33.800  5757  5757 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:33.800  5757  5757 V BluetoothAdapterState: isTurningOn()=false
,11-23 12:23:33.800  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:33.800  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:33.801  5757  5757 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-23 12:23:33.802  5757  5757 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 12:23:33.802  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 12:23:33.802  5757  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:33.802  5757  5757 V BluetoothAdapterState: isTurningOff()=true
,11-23 12:23:33.802  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:33.802  5757  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:33.802  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:33.802  5757  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 12:23:33.802  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:33.803  5757  5773 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 12:23:33.804  5757  5757 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:33.804  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:33.804  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:33.804  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 12:23:33.804  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 12:23:33.805  5757  5757 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 12:23:33.805  5757  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:33.805  5757  5757 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-23 12:23:33.805  5757  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:33.805  5757  5780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-23 12:23:33.805  5757  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 12:23:33.805  5757  5780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 12:23:33.805  5757  5780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 12:23:33.805  5757  5780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 12:23:33.807  3112  3112 D BluetoothPbap: Proxy object disconnected
11-23 12:23:33.807  3112  3112 D PbapServerProfile: Bluetooth service disconnected
,11-23 12:23:33.808  5757  5757 V BluetoothAdapterState: isTurningOff()=true
,11-23 12:23:33.808  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:33.808  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:33.808  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:33.808  5757  5757 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 12:23:33.809  5757  5757 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 12:23:33.809  5757  5757 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:33.809  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:33.809  5643  5643 D BluetoothPbap: Proxy object disconnected
11-23 12:23:33.809  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:33.809  5643  5643 D PbapServerProfile: Bluetooth service disconnected
11-23 12:23:33.809  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:33.809  5757  5757 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 12:23:33.810  5757  5757 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 12:23:33.810  5757  5773 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 12:23:33.811  5757  5757 D BluetoothMapService: MAP Service closeService in
11-23 12:23:33.811  5757  5757 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:33.811  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:33.811  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:33.811  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:33.811  5757  5757 D BluetoothMapService: cleanup()
11-23 12:23:33.811  5757  5757 D BluetoothMapService: MAP Service closeService in
11-23 12:23:33.811  5757  5757 V BluetoothAdapterState: isTurningOff()=true
11-23 12:23:33.812  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:33.812  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 12:23:33.812  5757  5757 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:33.812  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 12:23:33.812  5757  5769 D BluetoothAdapterProperties: Setting state to 15
11-23 12:23:33.812  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 12:23:33.813  5757  5769 I BluetoothAdapterState: Entering BleOnState
11-23 12:23:33.814   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 12:23:33.815  5643  5655 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 12:23:33.815  5643  5657 D BluetoothPan: onBluetoothStateChange on: false
11-23 12:23:33.816  3112  3898 D BluetoothMap: onBluetoothStateChange: up=false
11-23 12:23:33.817  5643  5655 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 12:23:33.817  3112  3124 D BluetoothPbap: onBluetoothStateChange: up=false
,11-23 12:23:33.818  3112  3123 D BluetoothPan: onBluetoothStateChange on: false
11-23 12:23:33.818   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:33.818   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 12:23:33.819  3723  3747 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:33.819  5643  5657 D BluetoothMap: onBluetoothStateChange: up=false
11-23 12:23:33.819  3112  3949 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 12:23:33.820  5643  5655 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 12:23:33.820  3112  3898 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:33.821  3112  3124 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 12:23:33.821  5643  5657 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:33.821   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 12:23:33.822  5757  5769 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 12:23:33.822  5757  5769 D BluetoothAdapterProperties: Setting state to 16
,11-23 12:23:33.822  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 12:23:33.823  5757  5769 D BluetoothAdapterProperties: onBleDisable
,11-23 12:23:33.823  5757  5769 I BluetoothAdapterState: Entering PendingCommandState
11-23 12:23:33.824  5757  5770 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 12:23:33.825  5757  5773 D BluetoothAdapterProperties: Scan Mode:20
11-23 12:23:33.825  5757  5780 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 12:23:33.826  5757  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 12:23:33.826  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 12:23:33.826  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:23:33.828  5583  5583 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:33.831  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 12:23:33.832  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,11-23 12:23:34.040  5757  5773 I bt_hci  : shut_down
,11-23 12:23:34.051  5757  5777 D bt_hwcfg: hw_epilog_process
,11-23 12:23:34.052  5757  5777 I bt_vendor: low_power_mode_cb
,11-23 12:23:34.055  5757  5777 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-23 12:23:34.055  5757  5777 I bt_vendor: epilog_cb
11-23 12:23:34.055  5757  5777 I bt_hci  : epilog_finished_callback
,11-23 12:23:34.060  5757  5773 I bt_hci_h4: hal_close
,11-23 12:23:34.061  5757  5773 I bt_userial_vendor: device fd = 54 close
,11-23 12:23:34.176  5757  5770 D bt_stack_manager: event_shut_down_stack finished.
,11-23 12:23:34.178  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 12:23:34.182  5757  5769 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 12:23:34.182  5757  5757 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 12:23:34.183  5757  5757 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 12:23:34.184  5757  5757 D BtGatt.GattService: stop()
11-23 12:23:34.184  5757  5757 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 12:23:34.189  5757  5757 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:34.189  5757  5757 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:34.190  5757  5757 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 12:23:34.190  5757  5757 V BluetoothAdapterState: isBleTurningOff()=true
11-23 12:23:34.190  5757  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 12:23:34.191  5757  5769 D BluetoothAdapterProperties: Setting state to 10
11-23 12:23:34.191  5757  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-23 12:23:34.192  5757  5769 I BluetoothAdapterState: Entering OffState
,11-23 12:23:34.193   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 12:23:34.207  5757  5757 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-23 12:23:34.207  5757  5757 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 12:23:34.207  5757  5757 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-23 12:23:34.209  5757  5770 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 12:23:34.217  5757  5757 I art     : System.exit called, status: 0
,11-23 12:23:34.218  5757  5757 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 12:23:34.248   926   936 I ActivityManager: Process com.android.bluetooth (pid 5757) has died
,11-23 12:23:34.910   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:35.911   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:36.797  3546  3546 I ConfigService: onDestroy
,11-23 12:23:36.912   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:37.913   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:38.737  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:38.737  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 12:23:38.742  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:38.743  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@974448e removed from the list
,11-23 12:23:38.743  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 12:23:38.747  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 12:23:38.747  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e6e845 added. We now have 4 listener(s)
11-23 12:23:38.747  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:23:38.749  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:38.749  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e6e845 removed from the list
11-23 12:23:38.749  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:38.751  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:38.751  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4741b9a added. We now have 4 listener(s)
,11-23 12:23:38.751  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:23:38.914   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:39.914   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 12:23:43.761  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 12:23:43.798   926   943 I ActivityManager: Start proc 5814:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 12:23:43.890  5814  5814 D AdapterServiceConfig: Adding HeadsetService
,11-23 12:23:43.891  5814  5814 D AdapterServiceConfig: Adding A2dpService
11-23 12:23:43.891  5814  5814 D AdapterServiceConfig: Adding HidService
11-23 12:23:43.891  5814  5814 D AdapterServiceConfig: Adding HealthService
11-23 12:23:43.891  5814  5814 D AdapterServiceConfig: Adding PanService
11-23 12:23:43.891  5814  5814 D AdapterServiceConfig: Adding GattService
11-23 12:23:43.891  5814  5814 D AdapterServiceConfig: Adding BluetoothMapService
11-23 12:23:43.892  5814  5814 D AdapterServiceConfig: Adding SapService
,11-23 12:23:43.902   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6eefe8f:true
,11-23 12:23:43.902  5814  5814 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 12:23:43.905  5814  5814 I bt_bluedroid: init
,11-23 12:23:43.905  5814  5826 I BluetoothAdapterState: Entering OffState
,11-23 12:23:43.908  5814  5827 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 12:23:43.908  5814  5827 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 12:23:43.908  5814  5827 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 12:23:43.908  5814  5827 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 12:23:43.909  5814  5814 I bt_bluedroid: get_profile_interface socket
,11-23 12:23:43.911  5814  5830 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 12:23:43.911  5814  5814 I bt_bluedroid: get_profile_interface sdp
,11-23 12:23:43.912  5814  5830 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 12:23:43.916  5814  5825 I bt_bluedroid: config_hci_snoop_log
,11-23 12:23:43.917   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 12:23:43.921  5814  5826 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 12:23:43.921  5814  5826 D BluetoothAdapterProperties: Setting state to 14
11-23 12:23:43.921  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 12:23:43.922  5814  5826 D BluetoothBondStateMachine: make
,11-23 12:23:43.924  5814  5831 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 12:23:43.927  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,11-23 12:23:43.928  5814  5814 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 12:23:43.930  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:43.930  5814  5814 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 12:23:43.931  5814  5814 D BtGatt.GattService: Received start request. Starting profile...
11-23 12:23:43.931  5814  5814 D BtGatt.GattService: start()
11-23 12:23:43.931  5814  5814 I bt_bluedroid: get_profile_interface gatt
,11-23 12:23:43.932  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:43.932  5814  5814 D BtGatt.AdvertiseManager: advertise manager created
,11-23 12:23:43.937  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:43.937  5814  5814 V BluetoothAdapterState: isTurningOn()=false
11-23 12:23:43.937  5814  5814 V BluetoothAdapterState: isBleTurningOn()=true
11-23 12:23:43.937  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:43.937  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 12:23:43.938  5814  5826 I bt_bluedroid: bt_bluedroid
11-23 12:23:43.938  5814  5827 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 12:23:43.939  5814  5827 I bt_hci  : start_up
,11-23 12:23:43.944  5814  5827 I bt_vendor: alloc value 0xf4049871
,11-23 12:23:43.944  5814  5827 I bt_vendor: init
11-23 12:23:43.944  5814  5827 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 12:23:43.944  5814  5827 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 12:23:44.054  5814  5827 D bt_hci  : start_up starting async portion
11-23 12:23:44.054  5814  5834 I bt_hci  : event_finish_startup
11-23 12:23:44.054  5814  5834 I bt_hci_h4: hal_open
11-23 12:23:44.054  5814  5834 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 12:23:44.057  5814  5834 I bt_userial_vendor: device fd = 54 open
,11-23 12:23:44.052  5835  5835 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 12:23:44.071  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 12:23:44.074  5814  5834 D bt_hwcfg: Chipset BCM4358A3
11-23 12:23:44.074  5814  5834 D bt_hwcfg: Target name = [BCM4358A3]
11-23 12:23:44.075  5814  5834 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 12:23:44.584  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 12:23:44.584  5814  5834 D bt_hwcfg: Settlement delay -- 100 ms
11-23 12:23:44.584  5814  5834 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 12:23:44.719  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 12:23:44.719  5814  5834 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 12:23:44.721  5814  5834 I bt_hwcfg: vendor lib fwcfg completed
,11-23 12:23:44.721  5814  5834 I bt_vendor: firmware callback
11-23 12:23:44.721  5814  5834 I bt_hci  : firmware_config_callback
,11-23 12:23:44.731  5814  5837 I bt_btu  : btu_task pending for preload complete event
,11-23 12:23:44.731  5814  5837 I bt_btu_task: Bluetooth chip preload is complete
,11-23 12:23:44.731  5814  5837 I bt_btu  : btu_task received preload complete event
,11-23 12:23:44.736  5814  5837 I         : BTE_InitTraceLevels -- TRC_HCI
11-23 12:23:44.736  5814  5837 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 12:23:44.736  5814  5837 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 12:23:44.736  5814  5837 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 12:23:44.736  5814  5837 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_SDP
,11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 12:23:44.737  5814  5837 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 12:23:44.738  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 12:23:44.738  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 12:23:44.831  5814  5837 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fc7549
,11-23 12:23:44.831  5814  5837 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fc7549 
,11-23 12:23:44.862  5814  5830 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 12:23:44.864  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 12:23:44.865  5814  5830 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 12:23:44.867  5814  5830 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 12:23:44.869  5814  5830 D BluetoothAdapterProperties: Scan Mode:20
11-23 12:23:44.869  5814  5830 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 12:23:44.869  5814  5830 D bt_hci  : do_postload posting postload work item
11-23 12:23:44.869  5814  5834 I bt_hci  : event_postload
11-23 12:23:44.869  5814  5834 I bt_vendor: sco_config_cb
11-23 12:23:44.869  5814  5834 I bt_hci  : sco_config_callback postload finished.
,11-23 12:23:44.871  5814  5830 D bt_bte_conf: Device ID record 1 : primary
11-23 12:23:44.871  5814  5830 D bt_bte_conf:   vendorId            = 000f
11-23 12:23:44.871  5814  5830 D bt_bte_conf:   vendorIdSource      = 0001
11-23 12:23:44.871  5814  5830 D bt_bte_conf:   product             = 1200
11-23 12:23:44.871  5814  5830 D bt_bte_conf:   version             = 1436
,11-23 12:23:44.871  5814  5830 D bt_bte_conf:   clientExecutableURL = 
11-23 12:23:44.871  5814  5830 D bt_bte_conf:   serviceDescription  = 
,11-23 12:23:44.871  5814  5830 D bt_bte_conf:   documentationURL    = 
11-23 12:23:44.872  5814  5830 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-23 12:23:44.872  5814  5827 D bt_stack_manager: event_start_up_stack finished
11-23 12:23:44.872  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 12:23:44.873  5814  5826 D BluetoothAdapterProperties: Setting state to 15
,11-23 12:23:44.873  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 12:23:44.874  5814  5826 I BluetoothAdapterState: Entering BleOnState
,11-23 12:23:44.876  5814  5834 I bt_vendor: low_power_mode_cb
11-23 12:23:44.877  5814  5826 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 12:23:44.877  5814  5826 D BluetoothAdapterProperties: Setting state to 11
11-23 12:23:44.877  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 12:23:44.882  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:44.883  5814  5814 D HeadsetService: Received start request. Starting profile...
11-23 12:23:44.886  5814  5814 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 12:23:44.887  5814  5814 D HeadsetStateMachine: make
,11-23 12:23:44.897  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,11-23 12:23:44.900  5814  5814 D HeadsetStateMachine: max_hf_connections = 1
,11-23 12:23:44.900  5814  5814 I bt_bluedroid: get_profile_interface handsfree
11-23 12:23:44.901  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 12:23:44.901  5814  5830 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 12:23:44.904  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:44.905  5814  5814 D A2dpService: Received start request. Starting profile...
11-23 12:23:44.905  5814  5814 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 12:23:44.906  5814  5814 I bt_bluedroid: get_profile_interface avrcp
,11-23 12:23:44.911  5814  5814 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 12:23:44.911  5814  5814 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-23 12:23:44.912  5814  5814 D A2dpStateMachine: make
11-23 12:23:44.913  5814  5814 I bt_bluedroid: get_profile_interface a2dp
,11-23 12:23:44.914  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 12:23:44.916  5814  5845 D A2dpStateMachine: Enter Disconnected: -2
11-23 12:23:44.916  5814  5814 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 12:23:44.917  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:44.918  5814  5814 D HidService: Received start request. Starting profile...
11-23 12:23:44.918  5814  5814 I bt_bluedroid: get_profile_interface hidhost
11-23 12:23:44.918  5814  5814 D HidService: setHidService(): set to: null
11-23 12:23:44.918  5814  5830 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fa856d
,11-23 12:23:44.919  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 12:23:44.919  5814  5814 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 12:23:44.920  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:44.920  5814  5814 D HealthService: Received start request. Starting profile...
,11-23 12:23:44.922  5814  5814 I bt_bluedroid: get_profile_interface health
,11-23 12:23:44.923  5814  5814 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 12:23:44.924  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:44.924  5814  5814 D PanService: Received start request. Starting profile...
11-23 12:23:44.925  5814  5814 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 12:23:44.925  5814  5814 I bt_bluedroid: get_profile_interface pan
11-23 12:23:44.925  5814  5830 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 12:23:44.926  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 12:23:44.928  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:44.929  5814  5814 D BluetoothMapService: Received start request. Starting profile...
11-23 12:23:44.929  5814  5814 D BluetoothMapService: start()
11-23 12:23:44.931  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 12:23:44.932  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 12:23:44.932  5814  5814 D BluetoothMapAppObserver: createReceiver()
,11-23 12:23:44.933  5814  5814 D BluetoothMapAppObserver: initObservers()
11-23 12:23:44.933  5814  5814 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 12:23:44.940  5814  5814 V SapService: SapBinder()
11-23 12:23:44.940  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
,11-23 12:23:44.941  5814  5814 D SapService: Received start request. Starting profile...
11-23 12:23:44.941  5814  5814 V SapService: start()
,11-23 12:23:44.943  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:44.943  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.943  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:44.943  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 12:23:44.944  5814  5842 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:44.944  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:44.945  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
11-23 12:23:44.946  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,11-23 12:23:44.946  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.946  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:44.946  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 12:23:44.947  5814  5814 V BluetoothAdapterState: isTurningOff()=false
11-23 12:23:44.947  5814  5814 V BluetoothAdapterState: isTurningOn()=true
11-23 12:23:44.947  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
11-23 12:23:44.947  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 12:23:44.947  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 12:23:44.948  5814  5826 D BluetoothAdapterProperties: ScanMode =  20
11-23 12:23:44.948  5814  5826 D BluetoothAdapterProperties: State =  11
11-23 12:23:44.948  5814  5826 D BluetoothAdapterProperties: Setting state to 12
11-23 12:23:44.948  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 12:23:44.948   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 12:23:44.949  5814  5826 I BluetoothAdapterState: Entering OnState
11-23 12:23:44.949  5814  5830 D BluetoothAdapterProperties: Scan Mode:21
11-23 12:23:44.949  5814  5830 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 12:23:44.949  5643  5655 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 12:23:44.950   926   926 D BluetoothA2dp: Proxy object connected
,11-23 12:23:44.951  5643  5657 D BluetoothPan: onBluetoothStateChange on: true
,11-23 12:23:44.953  3112  3898 D BluetoothMap: onBluetoothStateChange: up=true
11-23 12:23:44.955  5643  5655 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 12:23:44.955  3112  3112 D BluetoothMap: Proxy object connected
,11-23 12:23:44.955  3112  3112 D MapProfile: Bluetooth service connected
11-23 12:23:44.955  3112  3112 D BluetoothMap: getConnectedDevices()
,11-23 12:23:44.956  3112  3123 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 12:23:44.958  3112  3949 D BluetoothPan: onBluetoothStateChange on: true
11-23 12:23:44.960  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 12:23:44.960  5643  5643 D BluetoothA2dp: Proxy object connected
11-23 12:23:44.960  5814  5814 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 12:23:44.960   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:44.960   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:44.960  3112  3112 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 12:23:44.960  3112  3112 D PanProfile: Bluetooth service connected
11-23 12:23:44.961  3723  3747 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:44.961  5643  5657 D BluetoothMap: onBluetoothStateChange: up=true
11-23 12:23:44.961  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 12:23:44.963  3112  3123 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 12:23:44.964  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 12:23:44.964  5643  5850 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 12:23:44.965  5814  5814 D ObexServerSockets: Succeed to create listening sockets 
11-23 12:23:44.965  5814  5814 D ObexServerSockets0: startAccept()
11-23 12:23:44.965  5814  5814 D ObexServerSockets0: prepareForNewConnect()
11-23 12:23:44.966  3112  3949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 12:23:44.967  5814  5814 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 12:23:44.967  5814  5814 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 12:23:44.967  3112  3124 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 12:23:44.967  5643  5643 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 12:23:44.967  5643  5643 D PanProfile: Bluetooth service connected
11-23 12:23:44.967  5643  5643 D BluetoothMap: Proxy object connected
11-23 12:23:44.967  5643  5643 D MapProfile: Bluetooth service connected
11-23 12:23:44.967  5643  5643 D BluetoothMap: getConnectedDevices()
11-23 12:23:44.968  5814  5851 D ObexServerSockets0: Accepting socket connection...
11-23 12:23:44.968  5814  5852 D ObexServerSockets0: Accepting socket connection...
11-23 12:23:44.969  3112  3112 D BluetoothA2dp: Proxy object connected
,11-23 12:23:44.971  5643  5655 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 12:23:44.972   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 12:23:44.973  5643  5643 D BluetoothInputDevice: Proxy object connected
11-23 12:23:44.973  5643  5643 D HidProfile: Bluetooth service connected
11-23 12:23:44.974  3112  3112 D BluetoothInputDevice: Proxy object connected
11-23 12:23:44.974  3112  3112 D HidProfile: Bluetooth service connected
,11-23 12:23:44.977   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 12:23:44.978  5814  5814 D BluetoothMapService: onReceive
11-23 12:23:44.978  5814  5814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 12:23:44.978  5814  5814 D BluetoothMapService: STATE_ON
,11-23 12:23:44.981  5814  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 12:23:44.982  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 12:23:44.983  5814  5854 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 12:23:44.983  5814  5854 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 12:23:44.988  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,11-23 12:23:44.990  3546  3546 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 12:23:44.997  3112  3112 D BluetoothPbap: Proxy object connected
,11-23 12:23:44.997  5643  5643 D BluetoothPbap: Proxy object connected
11-23 12:23:44.997  5643  5643 D PbapServerProfile: Bluetooth service connected
11-23 12:23:44.997  3112  3112 D PbapServerProfile: Bluetooth service connected
,11-23 12:23:45.003  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 12:23:45.004  5814  5814 D ObexServerSockets0: prepareForNewConnect()
,11-23 12:23:45.007  5814  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 12:23:45.015  5814  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 12:23:45.016  5814  5862 I BtOppRfcommListener: Accept thread started.
,11-23 12:23:45.061   926   926 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.062  5643  5850 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.062   926   926 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.062  3723  3745 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.062  3723  3967 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.063  3112  3124 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.063  3112  3112 D HeadsetProfile: Bluetooth service connected
,11-23 12:23:45.063   926   926 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.064  5643  5643 D HeadsetProfile: Bluetooth service connected
,11-23 12:23:45.067  3112  3949 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.067  3112  3112 D HeadsetProfile: Bluetooth service connected
,11-23 12:23:45.072  5643  5657 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.073   926   943 D BluetoothHeadset: Proxy object connected
11-23 12:23:45.073  5643  5643 D HeadsetProfile: Bluetooth service connected
,11-23 12:23:48.375  4062  4454 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 12:23:48.777  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 12:23:48.784  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 12:23:48.785  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 12:23:48.785  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4741b9a removed from the list
,11-23 12:23:48.786  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:48.789  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:48.789  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f4dccb added. We now have 4 listener(s)
,11-23 12:23:48.789  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 12:23:48.792   926  3128 D WifiService: setWifiEnabled: false pid=5583, uid=10077
,11-23 12:23:48.793   926  3128 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 12:23:53.803  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 12:23:53.804   926   937 D WifiService: setWifiEnabled: true pid=5583, uid=10077
11-23 12:23:53.804   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 12:23:53.811   507   920 D SoftapController: Softap fwReload - Ok
,11-23 12:23:53.818   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:53.818   507   920 D CommandListener: Trying to bring down wlan0
,11-23 12:23:53.820   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 12:23:53.826   926  2916 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 12:23:54.508   926  2916 D wifi    : set interface wlan0 flags (UP)
,11-23 12:23:54.514   926  2916 I WifiHAL : Initializing wifi
11-23 12:23:54.514   926  2916 I WifiHAL : Creating socket
11-23 12:23:54.517   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-23 12:23:54.522   926  2916 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 12:23:54.523   926  2916 D wifi    : Did set static halHandle = 0x7f5a10f0c0
11-23 12:23:54.523   926  2916 D wifi    : halHandle = 0x7f5a10f0c0, mVM = 0x7f7678d140, mCls = 0x196e
11-23 12:23:54.524   926  2916 D wifi    : array field set
11-23 12:23:54.524   926  2916 I WifiNative-HAL: interface[0] = wlan0
11-23 12:23:54.528   926  5867 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546971906240
11-23 12:23:54.528   926  5867 D wifi    : waitForHalEvents called, vm = 0x7f7678d140, obj = 0x196e, env = 0x7f6c93b5c0
,11-23 12:23:54.592  5868  5868 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 12:23:54.629   926  2916 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 12:23:54.667  5868  5868 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 12:23:54.752  5868  5868 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 12:23:54.753  5868  5868 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 12:23:54.774   926  2916 D WifiConfigStore: Loading config and enabling all networks 
,11-23 12:23:54.803   926  2916 D WifiConfigStore: loaded 0 passpoint configs
,11-23 12:23:54.804   926  2916 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-23 12:23:54.804   926  2916 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 12:23:54.804   926  2916 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 12:23:54.805   926  2916 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 12:23:54.805   926  2916 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-23 12:23:54.806   926  2916 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 12:23:54.806   926  2916 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 12:23:54.806   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 12:23:54.807   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 12:23:54.807   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 12:23:54.807   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 12:23:54.807   926  2916 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 12:23:54.809   926  2916 D WifiNative-HAL: Setting external_sim to 1
11-23 12:23:54.810   926  2916 D wifi    : setting dfs flag to true, 0x7f577a1b80
,11-23 12:23:54.810   926  2916 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 12:23:54.810   926  2916 D wifi    : setting scan oui 0x7f577a1b80
11-23 12:23:54.810  4990  4990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 12:23:54.810   926  2916 D WifiHAL : Sending mac address OUI
,11-23 12:23:54.814   926  2916 E native  : do suspend false
,11-23 12:23:54.828   926  2916 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-23 12:23:54.828   926   926 D RttService: SCAN_AVAILABLE : 3
11-23 12:23:54.828   926  3026 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 12:23:54.828   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 12:23:54.830   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:54.835   926  2915 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-23 12:23:54.835   926  2915 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 12:23:54.853   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164021 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-23 12:23:54.853   926  2915 D WifiNative-HAL: p2pGetDeviceAddress
11-23 12:23:54.854   926  2915 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 12:23:54.915   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:55.917   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:56.918   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:57.918  5868  5868 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:57.919   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:23:57.927  5868  5868 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:57.933  5868  5868 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:23:57.953   926  2916 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 12:23:57.954   926  2916 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 12:23:57.955   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 12:23:57.964   926  2916 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 12:23:57.992   926  2916 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 12:23:57.997  5868  5868 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 12:23:58.415  5868  5868 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 12:23:58.452  5868  5868 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 12:23:58.453  5868  5868 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 12:23:58.462   926  2916 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 12:23:58.463   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 12:23:58.463   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 12:23:58.480   926  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 12:23:58.493   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:58.499   926  2916 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 12:23:58.506   926  5873 D DhcpClient: Receive thread started
,11-23 12:23:58.511   926  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 12:23:58.511   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 12:23:58.512   926  2918 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 12:23:58.593   926  2916 E native  : do suspend false
,11-23 12:23:58.604   926  5872 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 12:23:58.618   926  5873 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-23 12:23:58.619   926  5872 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-23 12:23:58.620   926  5872 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 12:23:58.632   926  5873 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 12:23:58.633   926  5872 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-23 12:23:58.635   507   920 D CommandListener: Setting iface cfg
,11-23 12:23:58.638   926  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 12:23:58.643   926  5872 D DhcpClient: Scheduling renewal in 86399s
,11-23 12:23:58.653   926  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 12:23:58.653   926  2916 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 12:23:58.655   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 12:23:58.658   926  2918 D ConnectivityService: Adding iface wlan0 to network 102
11-23 12:23:58.665   926  2916 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 12:23:58.701   926  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 12:23:58.701   926  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-23 12:23:58.703   926  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 12:23:58.705   926  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 12:23:58.709   926  2918 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 12:23:58.716   926  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:23:58.721   926  2918 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 12:23:58.721   926  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-23 12:23:58.734   926  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 12:23:58.734   926  2916 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 12:23:58.734   926  2918 D ConnectivityService:    accepting network in place of null
11-23 12:23:58.734   926  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 12:23:58.734   926  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 12:23:58.756   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 12:23:58.776   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 12:23:58.779   926  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-23 12:23:58.779  3694  3822 W QCNEJ   : |CORE| network available: 102
11-23 12:23:58.779   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 12:23:58.780   926  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-23 12:23:58.780  3694  3822 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 12:23:58.783   926   943 D Tethering: MasterInitialState.processMessage what=3
11-23 12:23:58.783  3694  3822 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 12:23:58.784  3694  3822 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 12:23:58.801  5028  5046 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 12:23:58.802  5028  5046 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-23 12:23:58.802  5028  5046 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 12:23:58.802  5028  5046 E SarControlService: no key has been found,reset the power
11-23 12:23:58.803  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 12:23:58.803  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 12:23:58.803  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 12:23:58.803  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:58.803  5053  5053 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 12:23:58.805  5028  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 12:23:58.805  5028  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-23 12:23:58.805  5028  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 12:23:58.806  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 12:23:58.806  5053  5053 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 12:23:58.808  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 12:23:58.812  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000f003000000000000ffffffff]
,11-23 12:23:58.812  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 12:23:58.812  5053  5067 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-23 12:23:58.813  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 12:23:58.813  5028  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 12:23:58.816  3917  3917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 12:23:58.817  5053  5067 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000f103000000000000ffffffff]
11-23 12:23:58.818  5053  5067 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 12:23:58.818  5053  5067 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-23 12:23:58.818  5053  5053 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-23 12:23:58.818  5028  5038 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 12:23:58.819  5583  5630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 12:23:58.820  5583  5630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 12:23:58.821  3917  3917 D SystemUpdateService: onCreate
11-23 12:23:58.821  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.821  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f4dccb removed from the list
11-23 12:23:58.821  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:58.824  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-23 12:23:58.825  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-23 12:23:58.827  3917  3917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 12:23:58.828  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1cc49af Bundle[{}]
,11-23 12:23:58.828  5583  5630 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 12:23:58.828  5583  5630 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-23 12:23:58.829  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-23 12:23:58.829  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 12:23:58.830  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 12:23:58.831  5583  5630 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-23 12:23:58.838  5583  5630 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-23 12:23:58.839  5583  5630 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 12:23:58.839  5583  5630 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-23 12:23:58.841  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:58.841  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8a0ca8 added. We now have 3 listener(s)
11-23 12:23:58.843  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 12:23:58.843  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.843  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.843  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:58.843  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b92c3c1 added. We now have 4 listener(s)
11-23 12:23:58.843  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.844  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:23:58.845  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:58.845  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d685766 added. We now have 4 listener(s)
,11-23 12:23:58.847  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:58.847  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.847  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.847  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 12:23:58.847  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef27aa7 added. We now have 5 listener(s)
11-23 12:23:58.847  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.848  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:58.848  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:58.848  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:58.848  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 12:23:58.848  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.848  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:58.848  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8a0ca8 removed from the list
11-23 12:23:58.848  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.848  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b92c3c1 removed from the list
11-23 12:23:58.848  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:58.849  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.849  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.850  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.850  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.850  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.850  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:58.850  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:58.850  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.850  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b92c3c1 not in the list
11-23 12:23:58.851  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.851  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.852  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.852  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.852  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.852  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:58.852  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:58.852  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.852  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef27aa7 removed from the list
11-23 12:23:58.852  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:58.852  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.852  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:58.852  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d685766 removed from the list
11-23 12:23:58.853  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:58.853  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c74b54 added. We now have 3 listener(s)
11-23 12:23:58.854  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 12:23:58.854  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.854  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.854  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:58.854  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec6dafd added. We now have 4 listener(s)
11-23 12:23:58.854  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.855  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:23:58.856  3917  3917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-23 12:23:58.856  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 12:23:58.856  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1283f2 added. We now have 4 listener(s)
11-23 12:23:58.857  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:58.857  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.857  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.857  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:58.858  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1421a43 added. We now have 5 listener(s)
11-23 12:23:58.858  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.858  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:23:58.858  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-23 12:23:58.858  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 12:23:58.858  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:23:58.858  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 12:23:58.859  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 12:23:58.864  3917  5381 I iu.UploadsManager: num queued entries: 0
11-23 12:23:58.865  3917  5381 I iu.UploadsManager: num updated entries: 0
,11-23 12:23:58.867  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 12:23:58.867  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 12:23:58.867  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 12:23:58.869  3917  5884 I SystemUpdateService: active receiver: enabled
,11-23 12:23:58.871  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 12:23:58.871  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.871  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 12:23:58.872  3917  3917 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 12:23:58.873  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 12:23:58.873  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 12:23:58.873  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 12:23:58.874  5682  5682 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 12:23:58.877  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.877  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 12:23:58.877  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 12:23:58.877  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 12:23:58.877  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 12:23:58.877  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.877  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:58.878  5682  5682 D SprintDMHelper: simOperator: 
11-23 12:23:58.878  5682  5682 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 12:23:58.881  5814  5843 D BtGatt.GattService: registerClient() - UUID=5b4e3d75-f37c-4646-bc07-10a71bfc20eb
,11-23 12:23:58.882  5814  5830 D BtGatt.GattService: onClientRegistered() - UUID=5b4e3d75-f37c-4646-bc07-10a71bfc20eb, clientIf=5
,11-23 12:23:58.883  5583  5593 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 12:23:58.884  5814  5824 D BtGatt.GattService: start scan with filters
,11-23 12:23:58.889  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 12:23:58.889  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.889  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 12:23:58.889  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.889  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 12:23:58.889  5814  5833 D BtGatt.ScanManager: handling starting scan
11-23 12:23:58.889  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 12:23:58.890  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.890  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 12:23:58.890  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 12:23:58.890  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.890  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 12:23:58.890  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.890  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.890  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 12:23:58.890  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.893  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.893  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:23:58.893  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.893  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.893  5583  5630 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 12:23:58.893  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:58.893  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.893  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 12:23:58.893  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.893  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:58.893  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.893  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 12:23:58.894  5814  5833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14f8c90
11-23 12:23:58.896  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.896  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.897  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.897  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 12:23:58.897  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.898  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 12:23:58.898  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.899  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:58.899  5814  5824 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 12:23:58.899  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 12:23:58.900  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:58.900  5814  5853 D BtGatt.GattService: stopScan() - queue size =1
11-23 12:23:58.901  5814  5843 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-23 12:23:58.901  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.902  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.902  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.902  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 12:23:58.902  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 12:23:58.902  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 12:23:58.895  3917  5381 I iu.SyncManager: NEXT; no task
11-23 12:23:58.903  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.903  5814  5830 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 12:23:58.903  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 12:23:58.903  5814  5833 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 12:23:58.903  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.903  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:23:58.904  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.904  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.904  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:23:58.904  3917  5884 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 12:23:58.905  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 12:23:58.905  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 12:23:58.905  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.906  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 12:23:58.906  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 12:23:58.906  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.906  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.906  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.906  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:23:58.906  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.907  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.908  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.908  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.908  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.908  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 12:23:58.908  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:58.908  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:58.909  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:58.909  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.909  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:58.909  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c74b54 removed from the list
11-23 12:23:58.909  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.909  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec6dafd removed from the list
11-23 12:23:58.909  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:58.909  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.909  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.910  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 12:23:58.910  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.911  5814  5833 D BtGatt.ScanManager: Starting BLE batch scan
11-23 12:23:58.911  5814  5833 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 12:23:58.913  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.913  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.913  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.913  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 12:23:58.913  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:58.913  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.913  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec6dafd not in the list
11-23 12:23:58.913  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.913  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.913  3917  5884 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-23 12:23:58.914  3917  5884 I SystemUpdateService: now status is 0 (complete)
11-23 12:23:58.914  3917  5884 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 12:23:58.914  3917  5884 I SystemUpdateService: file has been verified
11-23 12:23:58.914  3917  5884 I SystemUpdateService: OTA package size = 21989297
,11-23 12:23:58.916  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.916  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.916  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.916  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:58.916  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:58.916  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.916  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1421a43 removed from the list
11-23 12:23:58.916  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:58.916  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.916  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 12:23:58.916  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1283f2 removed from the list
11-23 12:23:58.917  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:58.917  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f0b0ec added. We now have 3 listener(s)
11-23 12:23:58.918  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:58.918  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.918  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.919  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:58.919  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceb6cb5 added. We now have 4 listener(s)
11-23 12:23:58.919  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.919  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:23:58.920   535   535 I ServiceManager: Waiting for service AtCmdFwd...
11-23 12:23:58.921  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 12:23:58.921  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45a9f4a added. We now have 4 listener(s)
11-23 12:23:58.921  5814  5830 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 12:23:58.922  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.922  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:58.922  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.922  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.922  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 12:23:58.923  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45a8ebb added. We now have 5 listener(s)
11-23 12:23:58.923  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.923  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:23:58.923  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 12:23:58.923  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 12:23:58.923  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 12:23:58.923  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:23:58.923  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 12:23:58.926  3917  5884 I SystemUpdateService: showing system update notification
11-23 12:23:58.926  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 12:23:58.928  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 12:23:58.928  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.929  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 12:23:58.929  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 12:23:58.929  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 12:23:58.929  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 12:23:58.931  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.931  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 12:23:58.932  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 12:23:58.932  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 12:23:58.932  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 12:23:58.933  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:23:58.934  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.934  5814  5830 E BtGatt.ContextMap: Context not found for ID 5
,11-23 12:23:58.936  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.936  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 12:23:58.936  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 12:23:58.936  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 12:23:58.936  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 12:23:58.936  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.936   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-23 12:23:58.936  5583  5630 D BluetoothAdapter: STATE_ON
,11-23 12:23:58.937  3917  3917 D SystemUpdateService: onDestroy
,11-23 12:23:58.940  5814  5825 D BtGatt.GattService: registerClient() - UUID=571a7a8d-d8ca-4fb8-b83a-a1e4bce69793
,11-23 12:23:58.940  5814  5830 D BtGatt.GattService: onClientRegistered() - UUID=571a7a8d-d8ca-4fb8-b83a-a1e4bce69793, clientIf=5
,11-23 12:23:58.940  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 12:23:58.940  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.941  5583  5717 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 12:23:58.941  5814  5833 D BtGatt.ScanManager: stopping BLe Batch
11-23 12:23:58.941  5814  5843 D BtGatt.GattService: start scan with filters
,11-23 12:23:58.944  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 12:23:58.944  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.944  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 12:23:58.944  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.944  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 12:23:58.944  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 12:23:58.944  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 12:23:58.944  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 12:23:58.944  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 12:23:58.944  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.944  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.944  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.945  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.945  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 12:23:58.945  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.947  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.947  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:23:58.947  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.948  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.948  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.948  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 12:23:58.948  5583  5630 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 12:23:58.948  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:58.948  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:58.948  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:58.948  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:58.948  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.948  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 12:23:58.948  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.948  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:58.948  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f0b0ec removed from the list
11-23 12:23:58.948  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.948  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceb6cb5 removed from the list
11-23 12:23:58.948  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:58.948  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.948  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:58.948  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 12:23:58.948  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.948  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.948  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.949  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 12:23:58.949  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.949  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:58.949  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:23:58.949  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.950  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.950  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 12:23:58.950  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.950  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:23:58.950  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.950  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.950  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.950  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:58.950  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:58.950  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.950  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceb6cb5 not in the list
,11-23 12:23:58.950  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 12:23:58.950  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.950  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 12:23:58.950  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 12:23:58.951  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.951  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.951  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.951  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 12:23:58.951  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.952  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:58.952  5814  5853 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 12:23:58.952  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 12:23:58.953  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 12:23:58.953  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.954  5814  5833 D BtGatt.ScanManager: handling starting scan
11-23 12:23:58.957  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:58.958  5814  5843 D BtGatt.GattService: stopScan() - queue size =1
11-23 12:23:58.958  3546  5893 I VacuumService: Vacuum at: now=1479900238958 tag=VacuumService
11-23 12:23:58.958  5814  5824 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.959  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 12:23:58.959  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 12:23:58.960  5814  5830 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 12:23:58.960  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.960  5814  5833 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 12:23:58.960  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 12:23:58.961  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.962  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.962  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:23:58.962  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.962  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.962  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:58.962  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:58.962  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.962  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45a8ebb removed from the list
11-23 12:23:58.962  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:58.962  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.962  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:23:58.962  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:58.962  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:23:58.962  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45a9f4a removed from the list
11-23 12:23:58.962  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 12:23:58.962  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.963  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 12:23:58.963  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 12:23:58.963  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.963  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.963  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:58.963  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfe3184 added. We now have 3 listener(s)
11-23 12:23:58.963  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.963  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:23:58.963  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,,main], id: 1
11-23 12:23:58.963  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.964  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:58.964  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.964  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.964  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:58.964  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e697d6d added. We now have 4 listener(s)
11-23 12:23:58.964  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.965  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:23:58.965  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.965  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.965  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.965  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:58.966  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66fcda2 added. We now have 4 listener(s)
11-23 12:23:58.966  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 12:23:58.966  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.966  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:58.966  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:58.966  5814  5833 D BtGatt.ScanManager: Starting BLE batch scan
11-23 12:23:58.967  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:58.967  5814  5833 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 12:23:58.967  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:58.967  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8e1a33 added. We now have 5 listener(s)
11-23 12:23:58.967  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:58.967  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:23:58.967  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 12:23:58.967  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 12:23:58.967  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 12:23:58.967  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 12:23:58.970  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 12:23:58.974  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 12:23:58.974  5583  5630 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 12:23:58.975  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 12:23:58.977  5814  5830 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 12:23:58.977  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.979  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.979  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 12:23:58.979  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 12:23:58.979  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 12:23:58.980  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 12:23:58.981  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 12:23:58.981  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.983  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:23:58.984  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.984  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 12:23:58.984  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 12:23:58.984  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 12:23:58.984  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 12:23:58.985  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.986  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:58.988  5814  5853 D BtGatt.GattService: registerClient() - UUID=011f746c-69d2-4fa4-bf24-e9518b169d5b
11-23 12:23:58.988  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:23:58.988  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.988  5814  5830 E BtGatt.ContextMap: Context not found for ID 5
11-23 12:23:58.988  5814  5830 D BtGatt.GattService: onClientRegistered() - UUID=011f746c-69d2-4fa4-bf24-e9518b169d5b, clientIf=5
11-23 12:23:58.989  3546  5896 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-23 12:23:58.989  5583  5717 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 12:23:58.989  5814  5824 D BtGatt.GattService: start scan with filters
11-23 12:23:58.992  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 12:23:58.992  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.992  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 12:23:58.992  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.992  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 12:23:58.992  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 12:23:58.993  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.993  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 12:23:58.993  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 12:23:58.993  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.993  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.993  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.993  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.993  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 12:23:58.993  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.995  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 12:23:58.995  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:58.995  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.995  5814  5833 D BtGatt.ScanManager: stopping BLe Batch
11-23 12:23:58.995  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:23:58.996  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.996  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 12:23:58.996  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.998  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:58.998  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:58.998  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:58.998  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:58.998  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.998  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:58.998  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:58.998  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:58.998  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.998  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfe3184 removed from the list
11-23 12:23:58.998  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.999  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:58.999  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:58.999  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e697d6d removed from the list
11-23 12:23:58.999  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:58.999  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 12:23:58.999  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.999  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:58.999  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:58.999  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.999  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 12:23:58.999  5583  5630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 12:23:58.999  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 12:23:58.999  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.001  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 12:23:59.001  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.001  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:23:59.001  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.002  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.002  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.002  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:59.002  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:59.002  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:59.002  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e697d6d not in the list
11-23 12:23:59.002  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 12:23:59.003  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.003  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 12:23:59.003  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 12:23:59.003  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.003  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.003  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.004  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 12:23:59.004  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.005  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:59.005  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:23:59.005  5814  5824 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 12:23:59.005  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.006  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 12:23:59.006  5583  5630 D BluetoothAdapter: STATE_ON
11-23 12:23:59.007  5814  5853 D BtGatt.GattService: stopScan() - queue size =0
11-23 12:23:59.008  5814  5843 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 12:23:59.008  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.009  5814  5833 D BtGatt.ScanManager: handling starting scan
11-23 12:23:59.009  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.009  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.009  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 12:23:59.009  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 12:23:59.009  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 12:23:59.009  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.011  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.011  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:23:59.011  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.011  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.011  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:59.012  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:59.012  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:59.012  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:23:59.012  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 12:23:59.012  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8e1a33 removed from the list
11-23 12:23:59.012  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:59.012  5583  5583 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:59.012  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66fcda2 removed from the list
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5583 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 12:23:59.012  5583  5583 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.012  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:59.013  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f82d1c added. We now have 3 listener(s)
11-23 12:23:59.013  5814  5830 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 12:23:59.013  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.013  5814  5833 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 12:23:59.014  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.014  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.014  5583  5583 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 12:23:59.014  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:59.014  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:59.014  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:59.014  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:59.014  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711ed25 added. We now have 4 listener(s)
11-23 12:23:59.014  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:59.015  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 12:23:59.016  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 12:23:59.016  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8816efa added. We now have 4 listener(s)
11-23 12:23:59.018  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 12:23:59.018  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 12:23:59.018  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 12:23:59.018  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.018  5583  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 12:23:59.018  5814  5833 D BtGatt.ScanManager: Starting BLE batch scan
11-23 12:23:59.018  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 12:23:59.018  5814  5833 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 12:23:59.018  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e489cab added. We now have 5 listener(s)
11-23 12:23:59.018  5583  5630 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 12:23:59.018  5583  5630 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 12:23:59.018  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:59.018  5583  5630 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 12:23:59.018  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:59.018  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:59.018  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:59.018  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f82d1c removed from the list
11-23 12:23:59.018  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:59.018  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711ed25 removed from the list
11-23 12:23:59.019  5583  5630 D io.jxcore.node.ConnectivityMonitor: stop
11-23 12:23:59.019  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.019  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.019  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.019  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.020  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.020  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:59.020  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:59.020  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:59.020  5583  5630 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711ed25 not in the list
11-23 12:23:59.020  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.020  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.021  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.021  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.021  5583  5630 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 12:23:59.021  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 12:23:59.021  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 12:23:59.021  5583  5630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 12:23:59.021  5583  5630 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e489cab removed from the list
11-23 12:23:59.021  5583  5630 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 12:23:59.021  5583  5630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 12:23:59.021  5583  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 12:23:59.021  5583  5630 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8816efa removed from the list
11-23 12:23:59.022  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 12:23:59.022  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 12:23:59.022  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 12:23:59.022  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:23:59.022  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 12:23:59.022  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 12:23:59.025  5814  5830 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 12:23:59.026  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.031  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 12:23:59.031  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.032  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:23:59.036  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:23:59.036  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.036  5814  5830 E BtGatt.ContextMap: Context not found for ID 5
,11-23 12:23:59.042  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 12:23:59.042  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.042  5814  5833 D BtGatt.ScanManager: stopping BLe Batch
11-23 12:23:59.046  3546  5894 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-23 12:23:59.047  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 12:23:59.047  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.047  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 12:23:59.049  3546  5894 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-23 12:23:59.052  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 12:23:59.052  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 12:23:59.070  3546  5894 W Uploader:  no longer exists, so no auth token.
11-23 12:23:59.075  3546  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 12:23:59.407  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 12:23:59.463  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 12:23:59.512  5583  5583 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 12:23:59.582   926  5871 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168749, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 12:23:59.920   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 12:24:01.044   926  5870 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 12:24:01.156  5583  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 12:24:01.156  5583  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:01.515   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:24:01.799   926  5870 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 11:24:01 GMT], X-Android-Received-Millis=[1479900241796], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479900241423]}
,11-23 12:24:01.800   926  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 12:24:01.801   926  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 12:24:01.802   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 12:24:01.803  4990  5889 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 12:24:01.808   926  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 12:24:01.930  5583  5901 W !!      : call onHalfStreamCopied
,11-23 12:24:01.930  5583  5901 I testCopyDataAndClose: closing input stream
,11-23 12:24:02.216  3546  5907 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 12:24:02.705  5583  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 12:24:02.705  5583  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 12:24:02.706  5583  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 12:24:02.869  3546  5894 W Uploader:  no longer exists, so no auth token.
,11-23 12:24:02.876  3546  5909 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 12:24:03.567  3546  5912 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 12:24:03.726  3546  5913 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 12:24:04.517  3546  5914 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 12:24:06.727   926  2918 D ConnectivityService: handlePromptUnvalidated 102
,11-23 12:24:06.736  5583  5916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:06.736  5583  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:07.541   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:24:08.736  5583  5630 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-23 12:24:08.736  5583  5630 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:08.737  5583  5630 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-23 12:24:08.755  5583  5916 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 12:24:08.755  5583  5916 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:08.755  5583  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,11-23 12:24:08.874  5583  5917 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 12:24:08.874  5583  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:09.850   926  2916 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-23 12:24:10.485  5583  5917 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 12:24:10.485  5583  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 12:24:10.486  5583  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 12:24:10.564   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 12:24:14.600  5583  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-23 12:24:14.601  5583  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 12:24:14.601  5583  5918 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 12:24:14.601  5583  5918 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 12:24:14.601  5583  5918 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:14.601  5583  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 12:24:14.602  5583  5630 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-23 12:24:14.606  5583  5919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:14.606  5583  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 12:24:14.607  5583  5919 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-23 12:24:14.608  5583  5919 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:14.608  5583  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 12:24:14.608  5583  5919 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 12:24:14.609  5583  5919 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 12:24:14.609  5583  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 12:24:14.615  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 12:24:14.615  5583  5630 I jxcore-log: 
,11-23 12:24:14.616  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 12:24:14.616  5583  5630 I jxcore-log: 
11-23 12:24:14.616  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 12:24:14.616  5583  5630 I jxcore-log: 
11-23 12:24:14.616  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 12:24:14.616  5583  5630 I jxcore-log: 
11-23 12:24:14.617  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'Total duration:  91396'
11-23 12:24:14.617  5583  5630 I jxcore-log: 
,11-23 12:24:14.619  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 12:24:14.619  5583  5630 I jxcore-log: 
,11-23 12:24:14.623  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.623  5583  5630 I jxcore-log: 
,11-23 12:24:14.624  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.624  5583  5630 I jxcore-log: 
11-23 12:24:14.624  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 12:24:14.624  5583  5630 I jxcore-log: 
11-23 12:24:14.625  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 12:24:14.625  5583  5630 I jxcore-log: 
,11-23 12:24:14.625  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.625  5583  5630 I jxcore-log: 
11-23 12:24:14.626  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 12:24:14.626  5583  5630 I jxcore-log: 
11-23 12:24:14.626  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.626  5583  5630 I jxcore-log: 
11-23 12:24:14.626  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.626  5583  5630 I jxcore-log: 
,11-23 12:24:14.627  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.627  5583  5630 I jxcore-log: 
11-23 12:24:14.627  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 12:24:14.627  5583  5630 I jxcore-log: 
11-23 12:24:14.627  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 12:24:14.627  5583  5630 I jxcore-log: 
11-23 12:24:14.627  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.627  5583  5630 I jxcore-log: 
11-23 12:24:14.627  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 12:24:14.627  5583  5630 I jxcore-log: 
11-23 12:24:14.628  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.628  5583  5630 I jxcore-log: 
11-23 12:24:14.628  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 12:24:14.628  5583  5630 I jxcore-log: 
11-23 12:24:14.628  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.628  5583  5630 I jxcore-log: 
11-23 12:24:14.628  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-23 12:24:14.628  5583  5630 I jxcore-log: 
11-23 12:24:14.629  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 12:24:14.629  5583  5630 I jxcore-log: 
11-23 12:24:14.629  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.629  5583  5630 I jxcore-log: 
11-23 12:24:14.629  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 12:24:14.629  5583  5630 I jxcore-log: 
11-23 12:24:14.630  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 12:24:14.630  5583  5630 I jxcore-log: 
,11-23 12:24:14.630  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.630  5583  5630 I jxcore-log: 
11-23 12:24:14.630  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 12:24:14.630  5583  5630 I jxcore-log: 
11-23 12:24:14.631  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 12:24:14.631  5583  5630 I jxcore-log: 
,11-23 12:24:14.633  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 12:24:14.633  5583  5630 I jxcore-log: 
11-23 12:24:14.633  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 12:24:14.633  5583  5630 I jxcore-log: 
11-23 12:24:14.633  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 12:24:14.633  5583  5630 I jxcore-log: 
11-23 12:24:14.634  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 12:24:14.634  5583  5630 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-23 12:24:14.634  5583  5630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 12:24:14.634  5583  5630 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 12:24:14.634  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 12:24:14.634  5583  5630 I jxcore-log: 
11-23 12:24:14.634  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.634  5583  5630 I jxcore-log: 
,11-23 12:24:14.635  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 12:24:14.635  5583  5630 I jxcore-log: 
11-23 12:24:14.635  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.635  5583  5630 I jxcore-log: 
,11-23 12:24:14.635  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 12:24:14.635  5583  5630 I jxcore-log: 
11-23 12:24:14.635  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 12:24:14.635  5583  5630 I jxcore-log: 
,11-23 12:24:14.641  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 12:24:14.641  5583  5630 I jxcore-log: 
11-23 12:24:14.642  5583  5630 I jxcore-log: 2016-11-23 11:24:14 - WARN testUtils: 'myNameCallback not set!'
11-23 12:24:14.642  5583  5630 I jxcore-log: 
,11-23 12:24:14.647  5583  5583 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 12:24:16.726  5583  5630 I jxcore-log: 2016-11-23 11:24:16 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 12:24:16.726  5583  5630 I jxcore-log: 
,11-23 12:24:16.727  5583  5630 I jxcore-log: 2016-11-23 11:24:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 12:24:16.727  5583  5630 I jxcore-log: 
,11-23 12:24:17.081  5583  5630 I jxcore-log: 2016-11-23 11:24:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 12:24:17.081  5583  5630 I jxcore-log: 
,11-23 12:24:17.092  5583  5630 I jxcore-log: 2016-11-23 11:24:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 12:24:17.092  5583  5630 I jxcore-log: 
,11-23 12:24:18.218  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 12:24:18.218  5583  5630 I jxcore-log: 
,11-23 12:24:18.413  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 12:24:18.413  5583  5630 I jxcore-log: 
,11-23 12:24:18.418  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 12:24:18.418  5583  5630 I jxcore-log: 
,11-23 12:24:18.423  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 12:24:18.423  5583  5630 I jxcore-log: 
,11-23 12:24:18.915  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 12:24:18.915  5583  5630 I jxcore-log: 
,11-23 12:24:18.961  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 12:24:18.961  5583  5630 I jxcore-log: 
,11-23 12:24:18.974  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 12:24:18.974  5583  5630 I jxcore-log: 
,11-23 12:24:18.979  5583  5630 I jxcore-log: 2016-11-23 11:24:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 12:24:18.979  5583  5630 I jxcore-log: 
,11-23 12:24:19.254  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 12:24:19.254  5583  5630 I jxcore-log: 
,11-23 12:24:19.385  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 12:24:19.385  5583  5630 I jxcore-log: 
,11-23 12:24:19.758  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 12:24:19.758  5583  5630 I jxcore-log: 
,11-23 12:24:19.767  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 12:24:19.767  5583  5630 I jxcore-log: 
,11-23 12:24:19.771  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 12:24:19.771  5583  5630 I jxcore-log: 
,11-23 12:24:19.776  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 12:24:19.776  5583  5630 I jxcore-log: 
,11-23 12:24:19.782  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 12:24:19.782  5583  5630 I jxcore-log: 
,11-23 12:24:19.810  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 12:24:19.810  5583  5630 I jxcore-log: 
,11-23 12:24:19.845  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 12:24:19.845  5583  5630 I jxcore-log: 
,11-23 12:24:19.853  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 12:24:19.853  5583  5630 I jxcore-log: 
,11-23 12:24:19.859  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 12:24:19.859  5583  5630 I jxcore-log: 
,11-23 12:24:19.874  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 12:24:19.874  5583  5630 I jxcore-log: 
,11-23 12:24:19.890  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 12:24:19.890  5583  5630 I jxcore-log: 
,11-23 12:24:19.896  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 12:24:19.896  5583  5630 I jxcore-log: 
,11-23 12:24:19.901  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 12:24:19.901  5583  5630 I jxcore-log: 
,11-23 12:24:19.914  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 12:24:19.914  5583  5630 I jxcore-log: 
,11-23 12:24:19.921   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:24:19.932  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 12:24:19.932  5583  5630 I jxcore-log: 
,11-23 12:24:19.946  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 12:24:19.946  5583  5630 I jxcore-log: 
,11-23 12:24:19.957  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 12:24:19.957  5583  5630 I jxcore-log: 
,11-23 12:24:19.969  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 12:24:19.969  5583  5630 I jxcore-log: 
,11-23 12:24:19.980  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 12:24:19.980  5583  5630 I jxcore-log: 
,11-23 12:24:19.993  5583  5630 I jxcore-log: 2016-11-23 11:24:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 12:24:19.993  5583  5630 I jxcore-log: 
,11-23 12:24:20.003  5583  5630 I jxcore-log: 2016-11-23 11:24:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 12:24:20.003  5583  5630 I jxcore-log: 
,11-23 12:24:20.010  5583  5630 I jxcore-log: 2016-11-23 11:24:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 12:24:20.010  5583  5630 I jxcore-log: 
,11-23 12:24:20.032  5583  5630 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 12:24:20.033  5583  5630 I jxcore-log: 2016-11-23 11:24:20 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 12:24:20.033  5583  5630 I jxcore-log: 
,11-23 12:24:20.066  5583  5630 I jxcore-log: 2016-11-23 11:24:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 12:24:20.066  5583  5630 I jxcore-log: 
,11-23 12:24:20.377  5583  5630 I jxcore-log: 2016-11-23 11:24:20 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 12:24:20.377  5583  5630 I jxcore-log: 
,11-23 12:24:20.923   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:24:21.924   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:24:22.925   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:24:23.926   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:24:24.927   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 12:24:38.706   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:24:49.928   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 12:24:49.928   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 12:24:59.929   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:00.930   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:01.932   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:02.557  5868  5868 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 12:25:02.933   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:03.934   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:04.935   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 12:25:09.936   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:10.938   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:11.939   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:12.940   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:13.942   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:14.943   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 12:25:18.712   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:25:24.944   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:25.945   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:26.221   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:25:26.947   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:27.948   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:28.950   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:29.254   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:25:29.951   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 12:25:35.321   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:25:38.351   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:25:38.713   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:25:41.391   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:25:44.953   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:45.954   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:46.956   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:47.957   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:48.958   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:25:49.958   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 12:25:50.480   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:26:08.621   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:26:09.960   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:10.961   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:11.962   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:12.963   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:13.964   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:14.664   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:26:14.965   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 12:26:18.718   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:26:38.721   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:26:39.966   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 12:26:39.966   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 12:26:54.967   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:55.968   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:56.969   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:57.970   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:58.723   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:26:58.971   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:26:59.972   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 12:27:04.973   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:05.974   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:06.108   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:06.976   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:07.977   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:08.978   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:09.141   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:09.979   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 12:27:12.174   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:18.245   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:19.981   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:20.982   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:21.272   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:21.984   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:22.985   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:23.986   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:24.305   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:24.987   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 12:27:38.727   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:27:39.989   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:40.990   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:41.991   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:42.993   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:43.994   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:27:44.995   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 12:27:45.496   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:48.525   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:27:58.730   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:28:03.670   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:04.996   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:05.997   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:06.999   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:08.000   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:09.001   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:09.716   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:10.002   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 12:28:12.749   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:18.733   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:28:18.784   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:27.885   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:33.951   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:35.003   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 12:28:35.003   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 12:28:36.985   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:38.736   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:28:40.018   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:43.051   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:52.141   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:28:55.004   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:56.006   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:57.007   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:58.008   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:28:58.738   926  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 12:28:59.009   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:29:00.009   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 12:29:01.230   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:29:04.264   926  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 12:29:04.866  5583  5630 I jxcore-log: 2016-11-23 11:29:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 12:29:04.866  5583  5630 I jxcore-log: 
,11-23 12:29:05.011   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:29:05.104  5583  5630 I jxcore-log: 2016-11-23 11:29:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 12:29:05.104  5583  5630 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 12:29:05.104  5583  5630 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 12:29:05.104  5583  5630 I jxcore-log: emit@events.js:82:1
11-23 12:29:05.104  5583  5630 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 12:29:05.104  5583  5630 I jxcore-log: emit@events.js:82:1''
11-23 12:29:05.104  5583  5630 I jxcore-log: 
,11-23 12:29:05.106  5583  5630 I jxcore-log: 2016-11-23 11:29:05 - DEBUG CoordinatedClient: 'test client failed'
11-23 12:29:05.106  5583  5630 I jxcore-log: 
,11-23 12:29:05.116  5583  5630 I jxcore-log: 2016-11-23 11:29:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 12:29:05.116  5583  5630 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 12:29:05.116  5583  5630 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 12:29:05.116  5583  5630 I jxcore-log: emit@events.js:82:1
11-23 12:29:05.116  5583  5630 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 12:29:05.116  5583  5630 I jxcore-log: emit@events.js:82:1''
11-23 12:29:05.116  5583  5630 I jxcore-log: 
,11-23 12:29:05.117  5583  5630 I jxcore-log: 2016-11-23 11:29:05 - DEBUG CoordinatedClient: 'test client failed'
11-23 12:29:05.117  5583  5630 I jxcore-log: 
,11-23 12:29:05.122  5583  5630 I jxcore-log: 2016-11-23 11:29:05 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 12:29:05.122  5583  5630 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 12:29:05.122  5583  5630 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 12:29:05.122  5583  5630 I jxcore-log: emit@events.js:82:1
11-23 12:29:05.122  5583  5630 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 12:29:05.122  5583  5630 I jxcore-log: emit@events.js:82:1''
11-23 12:29:05.122  5583  5630 I jxcore-log: 
,11-23 12:29:05.123  5583  5630 I jxcore-log: 2016-11-23 11:29:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 12:29:05.123  5583  5630 I jxcore-log: 
,11-23 12:29:05.725  5930  5930 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 12:29:05.747  5930  5930 D AndroidRuntime: CheckJNI is OFF
,11-23 12:29:05.776  5930  5930 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 12:29:05.812  5930  5930 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 12:29:05.830  5930  5930 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 12:29:05.846   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 12:29:05.847   926   939 I ActivityManager: Killing 5583:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 12:29:05.970   926   937 D GraphicsStats: Buffer count: 2
,11-23 12:29:05.970   926  3382 I WindowState: WIN DEATH: Window{2284f67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 12:29:05.970   926  2917 D WifiService: Client connection lost with reason: 4
,11-23 12:29:05.988   926   939 W ActivityManager: Force removing ActivityRecord{957021c u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-23 12:29:06.002   926   950 I art     : Starting a blocking GC Explicit
,11-23 12:29:06.007   926  3381 W ActivityManager: Spurious death for ProcessRecord{3f697da 0:com.test.thalitest/u0a77}, curProc for 5583: null
,11-23 12:29:06.011   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 12:29:06.042  3382  3382 W Binder_6: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28799]" dev="sockfs" ino=28799 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 12:29:06.042  3382  3382 W Binder_6: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28799]" dev="sockfs" ino=28799 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 12:29:06.045   926  3382 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5583 uid 10077
11-23 12:29:06.046  3631  3631 I Keyboard.Facilitator: onFinishInput()
,11-23 12:29:06.104   926   950 I art     : Explicit concurrent mark sweep GC freed 140895(9MB) AllocSpace objects, 88(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.915ms total 102.476ms
,11-23 12:29:06.121  3936  5945 I MicroRecognitionRnrImpl: Starting detection.
,11-23 12:29:06.122   926   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 12:29:06.123  3936  5946 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a0389e0
,11-23 12:29:06.124  5930  5930 I art     : System.exit called, status: 0
11-23 12:29:06.124  5930  5930 I AndroidRuntime: VM exiting with result code 0.
11-23 12:29:06.125   512  5949 I AudioFlinger: AudioFlinger's thread 0xf1fc0000 ready to run
,11-23 12:29:06.131   512  2966 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 12:29:06.132   926   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
11-23 12:29:06.133  3936  5946 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a0389e0
,11-23 12:29:06.140  5814  5814 D BluetoothMapAppObserver: onReceive
11-23 12:29:06.140  5814  5814 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 12:29:06.142   512  5949 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-23 12:29:06.142   512  5949 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-23 12:29:06.142   512  5949 I ACDB-LOADER: ACDB AFE returned = -19
,11-23 12:29:06.142   512  5949 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-23 12:29:06.142   512  5949 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-23 12:29:06.143   512  5949 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-23 12:29:06.147   926  2908 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 12:29:06.150   512  5949 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-23 12:29:06.152  3631  3631 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 12:29:06.152  4062  4141 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 12:29:06.169  3631  5954 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 12:29:06.178  3631  5954 I Decoder : createOrResetDecoder
,11-23 12:29:06.199  3364  5956 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 12:29:06.207   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 12:29:06.221  3723  3723 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 12:29:06.225  3546  3546 I ConfigService: onCreate
,11-23 12:29:06.237  3936  3936 I HotwordWorkerImpl: onReady
,11-23 12:29:06.246  3631  5954 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-23 12:29:06.252    21    21 W kworker/3:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 12:29:06.257  3546  3546 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-23 12:29:06.257  3546  3546 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-23 12:29:06.259    21    21 W kworker/3:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 12:29:06.275  3917  5962 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-23 12:29:06.275  3917  5962 D AccountUtils: Clearing selected account for com.test.thalitest
,11-23 12:29:06.282    21    21 W kworker/3:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 12:29:06.286  3917  5962 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-23 12:29:06.291  3364  5956 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-23 12:29:06.298  3917  5962 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:29:06.298  3917  5962 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:29:06.298  3917  5962 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 12:29:06.299  3917  5962 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-23 12:29:06.304  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-23 12:29:06.304  3917  3917 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-23 12:29:06.308  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-23 12:29:06.308  3917  3917 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,--------- beginning of crash
11-23 12:29:06.307  3364  5956 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-23 12:29:06.307  3364  5956 E AndroidRuntime: Process: android.process.acore, PID: 3364
11-23 12:29:06.307  3364  5956 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:29:06.307  3364  5956 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.j,ava:571)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:29:06.310  3917  5967 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMes,sage(Handler.java:102)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:29:06.311  3917  5967 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 12:29:06.313  3917  5967 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-23 12:29:06.313  3917  5967 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-23 12:29:06.313  3917  5967 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-23 12:29:06.314  3917  5967 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-23 12:29:06.314  3917  5967 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-23 12:29:06.315  3917  5967 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-23 12:29:06.315  3917  5967 E AndroidRuntime: Process: com.google.android.gms, PID: 3917
11-23 12:29:06.315  3917  5967 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 12:29:06.315  3917  5967 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 12:29:06.317  3936  5971 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-23 12:29:06.318   926  5972 E DropBoxManagerService: Can't write: system_app_crash
11-23 12:29:06.318   926  5972 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 12:29:06.318   926  5972 E DropBoxManagerService: 	... 5 more
11-23 12:29:06.329   405   405 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34101]" dev="sockfs" ino=34101 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 12:29:06.329   405   405 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34101]" dev="sockfs" ino=34101 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 12:29:06.332   408   408 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31504]" dev="sockfs" ino=31504 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 12:29:06.332   408   408 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31504]" dev="sockfs" ino=31504 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 12:29:06.336   926  5974 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-23 12:29:06.340  3631  5954 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-23 12:29:06.343  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-23 12:29:06.343  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-23 12:29:06.345   926  5975 E DropBoxManagerService: Can't write: system_app_crash
11-23 12:29:06.345   926  5975 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 12:29:06.345   926  5975 E DropBoxManagerService: 	... 5 more
11-23 12:29:06.345  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-23 12:29:06.346  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-23 12:29:06.348  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-23 12:29:06.348  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-23 12:29:06.349  3936  5971 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-23 12:29:06.352  3631  5954 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-23 12:29:06.352  3631  5954 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-23 12:29:06.352  3631  5954 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-23 12:29:06.352  3631  5954 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-23 12:29:06.352  3631  5954 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-23 12:29:06.352  3631  5954 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-23 12:29:06.371   926  3693 I ActivityManager: Start proc 5978:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-23 12:29:06.386   926  3097 I ActivityManager: Start proc 5983:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
11-23 12:29:06.396  3917  5969 W BaseAppContext: Using Auth Proxy for data requests.
11-23 12:29:06.398  3917  5969 W BaseAppContext: Using Auth Proxy for data requests.
,11-23 12:29:06.400  3917  5962 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-23 12:29:06.409  3917  5989 I GMPM-SVC: App measurement is starting up
,11-23 12:29:06.412  3917  3917 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
11-23 12:29:06.412  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
,11-23 12:29:06.413  3917  5989 E GMPM-SVC: AppMeasurementService not registered/enabled
11-23 12:29:06.413  3917  5989 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-23 12:29:06.413  3917  3917 I ConfigFetchService: service connected
,11-23 12:29:06.415  3917  5989 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-23 12:29:06.416  3917  5989 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-23 12:29:06.417  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-23 12:29:06.417  3917  5989 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-23 12:29:06.418   926   939 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{63165b2 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{b596714 3917 com.google.android.gms/10012/u0 remote:dd0ad67}: process crashing
11-23 12:29:06.418  3917  5989 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-23 12:29:06.418  3917  5989 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-23 12:29:06.419  3917  5989 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-23 12:29:06.419  3917  5989 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-23 12:29:06.420  3917  5989 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-23 12:29:06.420  3917  5991 I PeopleContactsSync: CP2 sync disabled
11-23 12:29:06.421  3917  5989 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-23 12:29:06.422  3917  4187 I Icing   : doRemovePackageData com.test.thalitest
11-23 12:29:06.425  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,11-23 12:29:06.425  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-23 12:29:06.425  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-23 12:29:06.426  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-23 12:29:06.426  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-23 12:29:06.426  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-23 12:29:06.426  3917  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,11-23 12:29:06.430   926   936 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3917 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-23 12:29:06.485  3917  5966 W DriveInitializer: Awaiting to be initialized
,11-23 12:29:06.485  3917  5994 W DriveInitializer: Background init thread started
,11-23 12:29:06.675   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
