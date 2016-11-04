#### Test 92249550abf9100_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 12:25:41.124  3968  4228 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-04 12:25:41.221  3968  4228 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-04 12:25:41.612  5598  5598 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 12:25:41.618  5598  5598 D AndroidRuntime: CheckJNI is OFF
11-04 12:25:41.646  5598  5598 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 12:25:41.677  5598  5598 I Radio-JNI: register_android_hardware_Radio DONE
11-04 12:25:41.692  5598  5598 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 12:25:41.696   928  3405 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 12:25:41.719  5598  5598 D AndroidRuntime: Shutting down VM
11-04 12:25:41.728  3953  3967 W SearchService: Abort, client detached.
11-04 12:25:41.738  3953  3953 I HotwordDetector: Closing mic
11-04 12:25:41.739  3953  4220 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cdbcbb9
11-04 12:25:41.740  3953  4229 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 12:25:41.753   928   939 I ActivityManager: Start proc 5608:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 12:25:41.809   513  4231 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 12:25:41.811   513  4231 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 12:25:41.820   513  4231 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 12:25:41.821   513  4231 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 12:25:41.822   513  2985 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 12:25:41.825  3953  4222 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 12:25:41.827  3953  4227 I MicroRecognitionRnrImpl: Detection finished
11-04 12:25:41.853  5608  5608 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 12:25:41.876  5608  5608 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-04 12:25:41.935  5608  5608 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 9030-9085)
11-04 12:25:41.935  5608  5608 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 12:25:41.966  5608  5608 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4f12d0f}
11-04 12:25:41.967  5608  5608 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 12:25:41.967  5608  5608 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 12:25:41.970  5608  5608 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 12:25:41.971  5608  5608 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 12:25:42.026  5608  5608 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 12:25:42.041  5608  5608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 12:25:42.041  5608  5608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 12:25:42.041  5608  5608 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 12:25:42.041  5608  5608 I Adreno  : Build Date                       : 12/06/15
11-04 12:25:42.041  5608  5608 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 12:25:42.041  5608  5608 I Adreno  : Local Branch                     : mybranch17112971
11-04 12:25:42.041  5608  5608 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 12:25:42.041  5608  5608 I Adreno  : Remote Branch                    : NONE
11-04 12:25:42.041  5608  5608 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 12:25:42.083   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f3a060:true
,11-04 12:25:42.122   404   404 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[29145]" dev="sockfs" ino=29145 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.122   404   404 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[29145]" dev="sockfs" ino=29145 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.132  5608  5608 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 12:25:42.140  5608  5608 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 12:25:42.169   404   404 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33971]" dev="sockfs" ino=33971 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.169   404   404 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33971]" dev="sockfs" ino=33971 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 12:25:42.171  5608  5645 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 12:25:42.176  3406  3406 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[13171]" dev="sockfs" ino=13171 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.176  3406  3406 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13171]" dev="sockfs" ino=13171 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.178  5608  5632 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 12:25:42.200  5608  5645 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 12:25:42.272   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +541ms
,11-04 12:25:42.272  3405  3405 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31933]" dev="sockfs" ino=31933 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.272  3405  3405 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31933]" dev="sockfs" ino=31933 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.276   938   938 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31932]" dev="sockfs" ino=31932 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.276   938   938 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31932]" dev="sockfs" ino=31932 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:25:42.279  3639  3639 I Keyboard.Facilitator: onFinishInput()
,11-04 12:25:42.349  5608  5608 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5608
,11-04 12:25:42.443  5608  5608 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 12:25:42.762  5608  5648 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -585627344
,11-04 12:25:42.784  5608  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 12:25:42.784  5608  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 12:25:42.784  5608  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 12:25:42.784  5608  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 12:25:42.784  5608  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 12:25:42.785  5608  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67ce81d added. We now have 1 listener(s)
,11-04 12:25:42.800  5608  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 12:25:42.801  5608  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 12:25:42.808  5608  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 12:25:42.809  5608  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 12:25:42.814  5608  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df29060 added. We now have 1 listener(s)
11-04 12:25:42.814  5608  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:25:42.820   928  2938 D WifiService: New client listening to asynchronous messages
,11-04 12:25:42.821  5608  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 12:25:42.822  5608  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 12:25:42.822  5608  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-04 12:25:42.822  5608  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 12:25:42.822  5608  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 12:25:42.822  5608  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-04 12:25:42.823  5608  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-04 12:25:42.827  5608  5648 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 12:25:42.856  5608  5608 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 12:25:43.491  5608  5617 I art     : Background sticky concurrent mark sweep GC freed 75278(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 2.920ms total 300.803ms
,11-04 12:25:43.516   928  2937 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 12:25:44.555  5608  5617 I art     : Background partial concurrent mark sweep GC freed 54527(6MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.107ms total 336.947ms
,11-04 12:25:45.118  5608  5656 W jxcore-log: Initializing JXcore engine
,11-04 12:25:45.118  5608  5656 W jxcore-log: JXcore engine is ready
,11-04 12:25:45.139  5656  5656 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1628 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 12:25:45.139  5656  5656 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16460]" dev="sockfs" ino=16460 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-04 12:25:45.139  5656  5656 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-04 12:25:45.139  5656  5656 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33146]" dev="sockfs" ino=33146 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 12:25:45.150  5608  5656 W jxcore-log: Starting JXcore engine
,11-04 12:25:45.200  5608  5656 W jxcore-log: Platform android
11-04 12:25:45.200  5608  5656 W jxcore-log: 
,11-04 12:25:45.200  5608  5656 W jxcore-log: Process ARCH arm
11-04 12:25:45.200  5608  5656 W jxcore-log: 
,11-04 12:25:45.230  3573  3573 I ConfigService: onDestroy
,11-04 12:25:45.380  5608  5656 I jxcore-log: JXcore Cordova bridge is ready!
11-04 12:25:45.380  5608  5656 I jxcore-log: 
,11-04 12:25:45.381  5608  5656 W jxcore-log: JXcore engine is started
,11-04 12:25:45.389  5608  5648 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 12:25:45.394  5608  5608 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 12:25:46.697   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:25:46.748   928  3144 I ActivityManager: Killing 5051:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-04 12:25:47.698   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:25:48.699   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:25:49.700   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:25:50.701   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:25:51.702   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 12:25:54.783   928   941 I ActivityManager: Killing 5393:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-04 12:25:54.914   928  3405 I ActivityManager: Start proc 5659:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-04 12:25:54.925  3953  5657 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 12:25:54.947  5659  5659 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-04 12:25:54.995  5659  5673 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-04 12:25:55.038  5659  5673 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-04 12:25:55.064  5659  5673 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-04 12:25:55.083  5659  5659 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-04 12:25:55.086  4870  4913 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 12:25:55.087  4870  4870 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 12:25:55.114  5686  5686 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads540506651.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads540506651.dex
,11-04 12:25:55.137  5608  5656 I jxcore-log: 2016-11-04 11:25:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 12:25:55.137  5608  5656 I jxcore-log: 
,11-04 12:25:55.138  5608  5656 I jxcore-log: 2016-11-04 11:25:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 12:25:55.138  5608  5656 I jxcore-log: 
,11-04 12:25:55.142  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:25:55.142  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 12:25:55.143  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 12:25:55.144  5608  5656 I jxcore-log: 2016-11-04 11:25:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 12:25:55.144  5608  5656 I jxcore-log: 
,11-04 12:25:55.146  5608  5656 I jxcore-log: 2016-11-04 11:25:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 12:25:55.146  5608  5656 I jxcore-log: 
,11-04 12:25:55.176  5686  5686 I dex2oat : dex2oat took 62.119ms (threads: 2) arena alloc=177KB java alloc=37KB native alloc=1259KB free=1044KB
,11-04 12:25:55.179  5659  5659 W InstanceID/Rpc: Found 10012
,11-04 12:25:55.220   928  3405 I ActivityManager: Killing 5407:com.android.chrome/u0a39 (adj 15): empty #17
,11-04 12:25:55.310  3573  5740 I VacuumService: Vacuum at: now=1478258755310 tag=VacuumService
,11-04 12:25:55.373  5608  5656 I jxcore-log: 2016-11-04 11:25:55 - DEBUG UnitTest_app: 'Running unit tests'
11-04 12:25:55.373  5608  5656 I jxcore-log: 
,11-04 12:25:55.374  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:25:55.374  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bde772f added. We now have 2 listener(s)
11-04 12:25:55.374  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:25:55.374  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 12:25:55.374  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:25:55.375  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:25:55.375  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363413c added. We now have 2 listener(s)
11-04 12:25:55.375  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:25:55.375  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 12:25:55.376  5608  5656 D executeNativeTests: Running unit tests
,11-04 12:25:55.409  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:25:55.409  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 added. We now have 3 listener(s)
,11-04 12:25:55.410  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:25:55.410  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:25:55.410  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:25:55.410  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:25:55.410  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca added. We now have 3 listener(s)
11-04 12:25:55.410  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:25:55.410  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 12:25:55.412  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 12:25:55.412  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 12:25:55.412  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 12:25:55.412  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 12:25:55.413  5608  5656 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 12:25:55.413  5608  5656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-04 12:25:55.413  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 12:25:55.414  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 12:25:55.414  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 12:25:55.414  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 12:25:55.414  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:25:55.414  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 12:25:55.414  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:25:55.414  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:25:55.414  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:25:55.414  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:25:55.414  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 removed from the list
11-04 12:25:55.414  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:25:55.415  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca removed from the list
11-04 12:25:55.415  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 12:25:55.415  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.415  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.415  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.415  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.415  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:25:55.415  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 12:25:55.415  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:25:55.415  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:25:55.416  5608  5656 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 12:25:55.417  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:25:55.417  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:25:55.417  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 12:25:55.417  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:25:55.417  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:25:55.417  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:25:55.417  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:25:55.417  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:25:55.417  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:25:55.417  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.417  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:25:55.417  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.418  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.418  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:25:55.418  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:25:55.418  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:25:55.418  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-04 12:25:55.420  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 12:25:55.421  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 12:25:55.421  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:25:55.421  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 12:25:55.421  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:25:55.421  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:25:55.422  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:25:55.422  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:25:55.422  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:25:55.422  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:25:55.422  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:25:55.422  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.422  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.422  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.422  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.422  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:25:55.422  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:25:55.422  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:25:55.422  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:25:55.423  5608  5656 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 12:25:55.424  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:25:55.424  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:25:55.426  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 12:25:55.427  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 12:25:55.427  5608  5656 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 12:25:55.428  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:25:55.428  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 12:25:55.428  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 12:25:55.428  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:25:55.428  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 12:25:55.430  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:25:55.431  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:25:55.431  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 12:25:55.431  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 12:25:55.431  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 12:25:55.434  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.434  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 12:25:55.435  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 12:25:55.435  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 12:25:55.435  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 12:25:55.437  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-04 12:25:55.438  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 12:25:55.438  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.438  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 12:25:55.438  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 12:25:55.438  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 12:25:55.438  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 12:25:55.438  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.439  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:25:55.441  4672  4891 D BtGatt.GattService: registerClient() - UUID=dfa73e8c-6433-49b7-a45c-b940e2f22069
11-04 12:25:55.441  4672  4733 D BtGatt.GattService: onClientRegistered() - UUID=dfa73e8c-6433-49b7-a45c-b940e2f22069, clientIf=5
11-04 12:25:55.442  5608  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 12:25:55.443  4672  4685 D BtGatt.GattService: start scan with filters
11-04 12:25:55.446  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 12:25:55.446  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.446  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 12:25:55.446  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.446  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 12:25:55.446  4672  4736 D BtGatt.ScanManager: handling starting scan
11-04 12:25:55.447  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 12:25:55.447  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.447  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 12:25:55.447  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 12:25:55.447  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.447  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.447  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 12:25:55.447  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 12:25:55.447  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.448  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.448  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:25:55.448  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.448  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:25:55.449  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.449  5608  5656 I io.jxcore.node.ConnectionHelper: start: OK
11-04 12:25:55.449  4672  4736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
11-04 12:25:55.451  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.451  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.451  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.451  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:25:55.451  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:25:55.458  4672  4733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 12:25:55.458  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:25:55.458  4672  4736 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 12:25:55.464  4672  4733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 12:25:55.464  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:25:55.465  4672  4736 D BtGatt.ScanManager: Starting BLE batch scan
11-04 12:25:55.465  4672  4736 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 12:25:55.474  4672  4733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 12:25:55.474  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:25:55.479  4672  4733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 12:25:55.479  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:25:55.953  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 12:25:55.953  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:25:55.953  5608  5608 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 12:25:57.639   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 12:26:00.453  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:00.453  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-04 12:26:00.454  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 12:26:00.454  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:26:00.454  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 12:26:00.454  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 12:26:00.454  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 12:26:00.454  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 12:26:00.454  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 12:26:00.454  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 12:26:00.455  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.455  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.455  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.456  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-04 12:26:00.456  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.457  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:26:00.457  4672  4687 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 12:26:00.458  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 12:26:00.458  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:26:00.459  4672  4736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 12:26:00.459  4672  4685 D BtGatt.GattService: stopScan() - queue size =1
11-04 12:26:00.460  4672  4687 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 12:26:00.460  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 12:26:00.461  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.461  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 12:26:00.461  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:00.461  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.461  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.461  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:00.462  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 12:26:00.462  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.462  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.462  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.462  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 12:26:00.463  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 12:26:00.463  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:26:00.464  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.465  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.465  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:26:00.465  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.465  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:00.465  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:00.466  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:26:00.466  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:26:00.466  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:00.466  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:00.466  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:00.466  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:00.466  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:00.466  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:00.466  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:00.466  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 12:26:00.467  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 12:26:00.467  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.467  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 12:26:00.467  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 12:26:00.467  4672  4672 D BtGatt.ScanManager: awakened up at time 97617
11-04 12:26:00.467  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.468  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.468  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 12:26:00.468  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.474  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.474  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.474  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.474  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:26:00.474  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 12:26:00.491  4672  4733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-04 12:26:00.491  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:00.491  4672  4733 D BtGatt.GattService: current time is 97642107271
11-04 12:26:00.492  4672  4733 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -96, 77, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -85, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-04 12:26:00.494  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-04 12:26:00.496  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-04 12:26:00.496  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 12:26:00.496  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-04 12:26:00.497  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-04 12:26:00.504  4672  4733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 12:26:00.505  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:00.505  4672  4736 D BtGatt.ScanManager: stopping BLe Batch
,11-04 12:26:00.512  4672  4733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 12:26:00.512  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:00.512  4672  4736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:26:00.521  4672  4733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 12:26:00.521  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:26:00.672   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 12:26:00.975  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 12:26:05.469  5608  5656 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 12:26:05.475  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 12:26:05.476  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:26:05.489  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 12:26:05.491  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 12:26:05.491  5608  5656 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 12:26:05.491  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:26:05.492  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 12:26:05.492  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 12:26:05.492  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 12:26:05.492  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 12:26:05.495  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:05.496  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 12:26:05.496  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 12:26:05.497  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 12:26:05.498  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:05.501  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.501  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 12:26:05.503  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 12:26:05.503  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 12:26:05.503  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 12:26:05.507  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.507  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 12:26:05.507  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-04 12:26:05.507  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 12:26:05.507  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 12:26:05.507  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.508  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:26:05.511  4672  4685 D BtGatt.GattService: registerClient() - UUID=4f25429a-40ab-4755-bfc9-6c0bb38d056a
,11-04 12:26:05.512  4672  4733 D BtGatt.GattService: onClientRegistered() - UUID=4f25429a-40ab-4755-bfc9-6c0bb38d056a, clientIf=5
,11-04 12:26:05.513  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 12:26:05.513  4672  4891 D BtGatt.GattService: start scan with filters
,11-04 12:26:05.517  4672  4736 D BtGatt.ScanManager: handling starting scan
11-04 12:26:05.517  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 12:26:05.517  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.517  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 12:26:05.517  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:05.517  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 12:26:05.517  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 12:26:05.517  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.518  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 12:26:05.518  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 12:26:05.518  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.518  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.518  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 12:26:05.519  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 12:26:05.519  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:05.522  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.522  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 12:26:05.522  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.522  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.522  5608  5656 I io.jxcore.node.ConnectionHelper: start: OK
11-04 12:26:05.523  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 12:26:05.526  4672  4733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 12:26:05.526  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.527  4672  4736 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 12:26:05.527  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:05.527  5608  5656 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 12:26:05.527  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:05.527  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 12:26:05.527  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:26:05.527  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 12:26:05.527  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:05.527  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 12:26:05.531  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.531  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.532  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.532  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.532  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 12:26:05.532  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 12:26:05.532  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 12:26:05.532  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:26:05.532  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.532  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.532  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.532  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 12:26:05.532  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.533  4672  4733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 12:26:05.533  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.533  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:26:05.533  4672  4736 D BtGatt.ScanManager: Starting BLE batch scan
11-04 12:26:05.533  4672  4736 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 12:26:05.534  4672  4891 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 12:26:05.534  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 12:26:05.535  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:26:05.535  4672  4685 D BtGatt.GattService: stopScan() - queue size =1
,11-04 12:26:05.537  4672  4891 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 12:26:05.537  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 12:26:05.537  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.537  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 12:26:05.537  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.538  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 12:26:05.538  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 12:26:05.539  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:26:05.539  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.540  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.540  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:26:05.540  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.540  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.541  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 12:26:05.541  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:26:05.541  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:05.541  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:26:05.541  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:05.541  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:05.541  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:05.541  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 12:26:05.541  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:05.541  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.541  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:05.541  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:05.541  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 12:26:05.541  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 12:26:05.541  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 12:26:05.541  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.541  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.541  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 12:26:05.541  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.545  4672  4733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 12:26:05.545  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.546  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.546  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.546  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.546  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-04 12:26:05.546  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:26:05.546  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.547  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.547  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.547  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.547  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:05.547  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:05.547  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:05.548  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:05.548  5608  5656 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 12:26:05.550  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 12:26:05.550  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 12:26:05.552  4672  4733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 12:26:05.552  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.554  4672  4736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:26:05.557  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 12:26:05.559  4672  4733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 12:26:05.559  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.559  4672  4733 E BtGatt.ContextMap: Context not found for ID 5
11-04 12:26:05.559  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 12:26:05.560  5608  5656 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 12:26:05.560  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:26:05.560  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 12:26:05.560  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 12:26:05.560  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:26:05.560  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 12:26:05.563  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 12:26:05.563  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 12:26:05.563  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 12:26:05.563  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:05.567  4672  4733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 12:26:05.567  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.567  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:05.567  4672  4736 D BtGatt.ScanManager: stopping BLe Batch
11-04 12:26:05.568  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.568  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 12:26:05.569  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 12:26:05.569  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 12:26:05.569  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 12:26:05.573  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:05.573  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 12:26:05.573  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 12:26:05.573  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 12:26:05.573  4672  4733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 12:26:05.573  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.574  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 12:26:05.574  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.574  4672  4736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:26:05.574  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:26:05.577  4672  4685 D BtGatt.GattService: registerClient() - UUID=cdcbbc2e-d911-489e-89c1-0b40427aa752
11-04 12:26:05.577  4672  4733 D BtGatt.GattService: onClientRegistered() - UUID=cdcbbc2e-d911-489e-89c1-0b40427aa752, clientIf=5
,11-04 12:26:05.577  5608  5618 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 12:26:05.578  4672  4891 D BtGatt.GattService: start scan with filters
11-04 12:26:05.579  4672  4733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 12:26:05.579  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:26:05.581  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 12:26:05.581  4672  4736 D BtGatt.ScanManager: handling starting scan
11-04 12:26:05.581  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.581  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 12:26:05.581  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.581  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 12:26:05.582  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 12:26:05.582  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.582  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 12:26:05.582  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 12:26:05.582  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.582  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.582  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 12:26:05.583  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 12:26:05.584  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.586  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.586  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:26:05.586  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.587  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:05.587  5608  5656 I io.jxcore.node.ConnectionHelper: start: OK
11-04 12:26:05.587  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.589  4672  4733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 12:26:05.589  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.589  4672  4736 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 12:26:05.589  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.589  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.589  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.589  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:26:05.589  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 12:26:05.594  4672  4733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 12:26:05.594  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:05.594  4672  4736 D BtGatt.ScanManager: Starting BLE batch scan
11-04 12:26:05.594  4672  4736 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 12:26:05.602  4672  4733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 12:26:05.602  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:26:05.607  4672  4733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 12:26:05.607  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:26:06.091  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 12:26:06.091  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:26:06.091  5608  5608 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 12:26:06.716   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 12:26:06.723   928  2941 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-04 12:26:09.742   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 12:26:09.748   928  2941 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-04 12:26:10.587  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:10.587  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:10.588  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 12:26:10.588  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 12:26:10.588  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 12:26:10.588  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:10.588  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 12:26:10.588  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 12:26:10.588  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 12:26:10.589  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 12:26:10.589  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:10.589  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.590  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:10.590  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 12:26:10.590  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:10.592  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:26:10.592  4672  4685 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 12:26:10.593  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 12:26:10.594  4672  4736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 12:26:10.595  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:26:10.597  4672  4687 D BtGatt.GattService: stopScan() - queue size =1
,11-04 12:26:10.600  4672  4685 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 12:26:10.600  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 12:26:10.601  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:10.601  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 12:26:10.601  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.601  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.602  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:10.602  4672  4672 D BtGatt.ScanManager: awakened up at time 107752
11-04 12:26:10.602  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.602  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 12:26:10.602  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.602  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.602  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:10.603  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 12:26:10.603  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 12:26:10.604   928   939 I ActivityManager: Killing 4440:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-04 12:26:10.636  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 12:26:10.636  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.637  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.638  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:26:10.638  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.638  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:10.638  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 12:26:10.638  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:10.638  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 12:26:10.638  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.638  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 12:26:10.638  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 12:26:10.638  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.638  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.639  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 12:26:10.639  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.640  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.640  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.640  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.641  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:26:10.641  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 12:26:10.642  4672  4733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-04 12:26:10.642  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:10.642  4672  4733 D BtGatt.GattService: current time is 107792934679
11-04 12:26:10.642  4672  4733 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -88, 93, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -82, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
11-04 12:26:10.643  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-04 12:26:10.643  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-04 12:26:10.643  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 12:26:10.643  4672  4733 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-04 12:26:10.644  4672  4733 E BtGatt.ContextMap: Context not found for ID 5
,11-04 12:26:10.649  4672  4733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 12:26:10.649  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:10.650  4672  4736 D BtGatt.ScanManager: stopping BLe Batch
,11-04 12:26:10.655  4672  4733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 12:26:10.655  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:26:10.655  4672  4736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:26:10.661  4672  4733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 12:26:10.661  4672  4733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:26:11.142  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 12:26:11.142  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:11.142  5608  5608 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 12:26:15.639  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:15.640  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.640  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.640  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 12:26:15.641  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:26:15.641  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:26:15.641  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 12:26:15.641  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.641  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.641  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:15.641  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.642  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 12:26:15.645  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.649  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.649  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.650  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.650  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.650  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.651  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:15.651  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.653  5608  5656 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-04 12:26:15.655  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:15.655  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.655  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.655  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.655  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.656  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
,11-04 12:26:15.656  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.656  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.656  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.656  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.658  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.658  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.658  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.658  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.658  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.658  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.659  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.660  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 12:26:15.660  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.660  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.660  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.661  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.661  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.661  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
,11-04 12:26:15.661  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.661  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.661  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.661  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.663  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.663  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.663  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.663  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.663  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.663  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.663  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:15.664  5608  5656 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 12:26:15.664  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:15.664  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.665  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.665  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.665  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.665  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.665  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.665  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.665  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.665  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.667  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.667  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.667  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.667  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.667  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.667  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.667  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.668  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-04 12:26:15.668  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.668  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.668  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.669  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.669  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.669  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.669  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.669  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:15.669  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.669  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.670  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.671  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.671  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.671  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 12:26:15.671  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.671  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.671  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.672  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 12:26:15.672  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 12:26:15.672  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 12:26:15.672  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 12:26:15.672  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 12:26:15.672  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 12:26:15.672  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 12:26:15.673  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 12:26:15.673  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 12:26:15.673  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.673  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.673  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.673  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.673  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.673  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
,11-04 12:26:15.673  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.674  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.674  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.674  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.675  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.675  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.675  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.676  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.676  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.676  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.676  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.677  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 12:26:15.677  5608  5656 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 12:26:15.677  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 12:26:15.681  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 12:26:15.682  5608  5656 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 12:26:15.682  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 12:26:15.683  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 12:26:15.684  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 12:26:15.684  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 12:26:15.684  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 12:26:15.684  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 12:26:15.684  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 12:26:15.684  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 12:26:15.684  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-04 12:26:15.684  5608  5656 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 12:26:15.685  5608  5656 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-04 12:26:15.685  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 12:26:15.685  5608  5656 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 12:26:15.685  5608  5656 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-04 12:26:15.685  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 12:26:15.685  5608  5656 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 12:26:15.685  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-04 12:26:15.688  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-04 12:26:15.689  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-04 12:26:15.689  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-04 12:26:15.690  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-04 12:26:15.690  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-04 12:26:15.691  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-04 12:26:15.691  5608  5743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-04 12:26:15.691  5608  5656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 12:26:15.691  5608  5656 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-04 12:26:15.691  5608  5743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-04 12:26:15.691  5608  5743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-04 12:26:15.691  5608  5743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-04 12:26:15.692  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.692  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.692  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.692  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.692  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.693  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-04 12:26:15.694  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
,11-04 12:26:15.694  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.694  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.694  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.694  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.694  5608  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-04 12:26:15.694  5608  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-04 12:26:15.695  5608  5743 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-04 12:26:15.696  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.696  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.696  5608  5743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 12:26:15.696  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.696  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.696  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.696  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.696  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.697  5608  5656 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 12:26:15.697  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.697  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.698  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.698  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.698  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.698  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.698  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.698  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.698  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.698  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.699  4891  4891 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31250]" dev="sockfs" ino=31250 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 12:26:15.699  4891  4891 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31250]" dev="sockfs" ino=31250 ioctlcmd=7704 scontext=u:r:bluetooth:s0 ,tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 12:26:15.700  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.700  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.700  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.700  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.700  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.701  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.701  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.702  5608  5656 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-04 12:26:15.702  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.702  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.702  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.702  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 12:26:15.702  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.702  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.702  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.702  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.702  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.702  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.703  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.703  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:15.704  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.704  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.704  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.704  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.704  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.704  5608  5656 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 12:26:15.705  5608  5656 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-04 12:26:15.705  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-04 12:26:15.705  5608  5656 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 12:26:15.705  5608  5656 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 12:26:15.705  5608  5656 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 12:26:15.705  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 12:26:15.705  5608  5656 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 12:26:15.705  5608  5656 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 12:26:15.705  5608  5656 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 12:26:15.705  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 12:26:15.705  5608  5656 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 12:26:15.705  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:15.705  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:15.705  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:15.705  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.706  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.706  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.706  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:15.706  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.706  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:15.706  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.707  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.707  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.707  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:15.708  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:15.708  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:15.708  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:15.708  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.708  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:15.708  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:15.708  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:15.708  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:15.708  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:15.708  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 12:26:16.703   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-04 12:26:16.703   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 12:26:20.709  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.710  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.710  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:20.710  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:20.710  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:20.711  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:20.711  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:20.711  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:20.711  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:20.711  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 12:26:20.712  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:20.712  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.712  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:20.712  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 12:26:20.712  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.716  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.716  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:20.716  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:20.717  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:20.717  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:20.717  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.717  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.721  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 12:26:20.722  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:26:20.722  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 12:26:20.728  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 12:26:20.731  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 12:26:20.732  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-04 12:26:20.732  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-04 12:26:20.732  5608  5745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 12:26:20.733  5608  5608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 12:26:20.733  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 12:26:20.733  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 12:26:20.734  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 12:26:20.734  5608  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 12:26:20.735  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 12:26:20.735  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 12:26:20.735  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 12:26:20.735  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 12:26:20.737  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-04 12:26:20.737  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 12:26:20.737  5608  5608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 12:26:20.737  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
,11-04 12:26:20.738  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.736  4687  4687 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[34048]" dev="sockfs" ino=34048 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 12:26:20.738  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 12:26:20.738  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 12:26:20.738  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 12:26:20.738  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.739  5608  5745 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 12:26:20.739  5608  5745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 12:26:20.739  5608  5745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-04 12:26:20.736  4687  4687 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34048]" dev="sockfs" ino=34048 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 12:26:20.742  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.742  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 12:26:20.743  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.743  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.743  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:20.743  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.744  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:26:20.744  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:20.744  5608  5608 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 12:26:20.744  5608  5608 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 12:26:20.744  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:20.744  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:26:20.744  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:20.745  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 12:26:20.745  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:20.745  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:20.745  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.745  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.745  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:20.746  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.749  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:20.749  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.750  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.750  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:20.750  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 12:26:20.750  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.750  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:20.753  5608  5656 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-04 12:26:20.754  5608  5656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 12:26:20.754  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-04 12:26:20.755  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 12:26:20.755  5608  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 12:26:20.755  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:26:20.755  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:20.755  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:20.755  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:20.756  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 12:26:20.756  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:20.756  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.756  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:20.756  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:20.756  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:20.758  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.759  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.759  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.759  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 12:26:20.759  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:20.759  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.759  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.769  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:20.769  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:20.769  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:20.769  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:20.769  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:20.769  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:20.769  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:20.769  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:20.769  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:20.769  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.771  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:20.772  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.772  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.772  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:20.772  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:20.772  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.772  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.774  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 12:26:20.774  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:26:20.774  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:26:20.774  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:26:20.774  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:26:20.774  5608  5656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9926335 not in the list
11-04 12:26:20.774  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:20.775  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
11-04 12:26:20.775  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:20.775  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.776  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.776  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:26:20.776  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:26:20.776  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:26:20.776  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:26:20.776  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:26:20.776  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8c93ca not in the list
,11-04 12:26:20.780  5608  5656 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-04 12:26:20.780  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 12:26:20.780  5608  5656 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 12:26:20.780  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 12:26:20.780  5608  5656 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 12:26:20.780  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 12:26:20.782  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 12:26:20.782  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 12:26:20.783  5608  5656 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-04 12:26:20.783  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 12:26:20.783  5608  5656 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-04 12:26:20.784  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 12:26:20.784  5608  5656 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-04 12:26:20.784  5608  5656 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-04 12:26:20.785  5608  5656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-04 12:26:20.785  5608  5656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-04 12:26:20.786  5608  5656 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 12:26:20.786  5608  5656 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 12:26:20.786  5608  5656 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-04 12:26:20.786  5608  5656 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 12:26:20.787  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:26:20.787  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@488572b added. We now have 3 listener(s)
11-04 12:26:20.788  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:26:20.789  5608  5656 D BluetoothAdapter: enable(): BT is already enabled..!
11-04 12:26:20.789   928  3795 D WifiService: setWifiEnabled: true pid=5608, uid=10077
11-04 12:26:20.789   928  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 12:26:20.827  4672  4868 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-04 12:26:20.827  5608  5743 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-04 12:26:20.828  5608  5743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-04 12:26:20.828  5608  5743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-04 12:26:20.828  4672  4882 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-04 12:26:21.246  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 12:26:21.704   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:22.705   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:23.524   928  2937 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 12:26:23.706   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:24.707   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:25.479  3573  5751 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-04 12:26:25.508  3573  5749 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-04 12:26:25.511  3573  5749 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-04 12:26:25.535  3573  5749 W Uploader:  no longer exists, so no auth token.
,11-04 12:26:25.540  3573  5751 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 12:26:25.708   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:25.793  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 12:26:25.793  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ede6788 added. We now have 4 listener(s)
11-04 12:26:25.793  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:26:25.812  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:25.813  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ede6788 removed from the list
,11-04 12:26:25.813  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 12:26:25.816  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:26:25.816  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36db521 added. We now have 4 listener(s)
,11-04 12:26:25.816  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:26:25.820  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:25.821  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36db521 removed from the list
,11-04 12:26:25.821  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:25.822  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:26:25.823  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6c5d46 added. We now have 4 listener(s)
11-04 12:26:25.823  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:26:25.830   928  3798 D WifiService: setWifiEnabled: false pid=5608, uid=10077
,11-04 12:26:25.830   928  3798 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 12:26:25.834   928  2937 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 12:26:25.835   928  2937 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 12:26:25.835   928  2937 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 12:26:25.835   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:26:25.841  4672  4729 D BluetoothAdapterState: Current state: ON, message: 23
11-04 12:26:25.841  4672  4729 D BluetoothAdapterProperties: Setting state to 13
11-04 12:26:25.841  4672  4729 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 12:26:25.841  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 12:26:25.841  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 12:26:25.842  4672  4729 D BluetoothAdapterProperties: onBluetoothDisable()
,11-04 12:26:25.843  4672  4729 I BluetoothAdapterState: Entering PendingCommandState
11-04 12:26:25.844  4672  4733 D BluetoothAdapterProperties: Scan Mode:20
11-04 12:26:25.845  4672  4729 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 12:26:25.847   928  5365 D DhcpClient: Clearing IP address
11-04 12:26:25.847   508   925 D CommandListener: Clearing all IP addresses on wlan0
11-04 12:26:25.849   508   925 D CommandListener: Setting iface cfg
11-04 12:26:25.850  4672  4672 D HeadsetService: Received stop request...Stopping profile...
11-04 12:26:25.850  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:26:25.850  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 12:26:25.852  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:25.852  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 12:26:25.852  5608  5656 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 12:26:25.857  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:25.858  3573  5420 V NativeCrypto: Read error: ssl=0x7f9802ea80: I/O error during system call, Connection timed out
11-04 12:26:25.860  3573  5420 V NativeCrypto: SSL shutdown failed: ssl=0x7f9802ea80: I/O error during system call, Broken pipe
11-04 12:26:25.861  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:26:25.861  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 12:26:25.863  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:25.863  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 12:26:25.864   928  3605 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-04 12:26:25.864   928  5363 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-04 12:26:25.865  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:25.866   928   941 I ActivityManager: Start proc 5759:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-04 12:26:25.866   928  5363 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-04 12:26:25.867   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-04 12:26:25.867   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-04 12:26:25.867  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:25.868   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 12:26:25.872   540   540 E Parcel  : Reading a NULL string not supported here.
11-04 12:26:25.872   928  5366 D DhcpClient: Receive thread stopped
,11-04 12:26:25.873   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-04 12:26:25.873   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 12:26:25.877   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:25.878  3768  3989 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:25.879   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:25.879   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:25.879  4672  4672 D A2dpService: Received stop request...Stopping profile...
11-04 12:26:25.879  4672  4886 D A2dpStateMachine: Exit Disconnected: -1
,11-04 12:26:25.880  3131  3147 D BluetoothHeadset: Proxy object disconnected
,11-04 12:26:25.881   928   928 D RttService: SCAN_AVAILABLE : 1
11-04 12:26:25.881   928   928 D BluetoothA2dp: Proxy object disconnected
11-04 12:26:25.881   928  3048 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-04 12:26:25.881  4672  4672 D HidService: Received stop request...Stopping profile...
11-04 12:26:25.882  4672  4672 D HidService: Stopping Bluetooth HidService
11-04 12:26:25.882   928  2941 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-04 12:26:25.882  3573  5753 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-04 12:26:25.883  3723  3869 W QCNEJ   : |CORE| network lost: 100
11-04 12:26:25.884   928  2937 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 12:26:25.884  3723  3869 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-04 12:26:25.884  4672  4672 D BluetoothMapService: onReceive
11-04 12:26:25.885  4672  4672 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 12:26:25.885  4672  4672 D BluetoothMapService: STATE_TURNING_OFF
11-04 12:26:25.888   928  2937 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 12:26:25.890  4672  4672 D HealthService: Received stop request...Stopping profile...
11-04 12:26:25.891  4672  4672 V BluetoothAdapterState: isTurningOff()=true
,11-04 12:26:25.891  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:25.891  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.891  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.893  3131  3131 D HeadsetProfile: Bluetooth service disconnected
11-04 12:26:25.893  3131  3131 D BluetoothA2dp: Proxy object disconnected
11-04 12:26:25.893  3131  3131 D BluetoothInputDevice: Proxy object disconnected
11-04 12:26:25.893  3131  3131 D HidProfile: Bluetooth service disconnected
11-04 12:26:25.893  4672  4672 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-04 12:26:25.893  4672  4672 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-04 12:26:25.893  4672  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:25.893  4672  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:25.893  4672  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:25.893  4672  4733 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 12:26:25.893  4672  4733 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 12:26:25.894  4672  4672 D PanService: Received stop request...Stopping profile...
11-04 12:26:25.895  4672  4672 V BluetoothAdapterState: isTurningOff()=true
,11-04 12:26:25.895  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:25.895  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.895  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.896  3131  3131 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 12:26:25.896  3131  3131 D PanProfile: Bluetooth service disconnected
11-04 12:26:25.897  4672  4672 V BluetoothAdapterState: isTurningOff()=true
,11-04 12:26:25.897  4672  4733 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 12:26:25.897  4672  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:25.897  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:25.897  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.897  4672  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 12:26:25.897  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.897  4672  4868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 12:26:25.897  4672  4868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 12:26:25.897  4672  4868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 12:26:25.897  4672  4868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 12:26:25.897  4672  4672 D BluetoothMapService: Received stop request...Stopping profile...
11-04 12:26:25.897  4672  4672 D BluetoothMapService: stop()
11-04 12:26:25.898  4672  4672 D BluetoothMapAppObserver: deinitObservers()
11-04 12:26:25.898  4672  4672 D BluetoothMapAppObserver: removeReceiver()
11-04 12:26:25.899  3131  3131 D BluetoothMap: Proxy object disconnected
11-04 12:26:25.899  3131  3131 D MapProfile: Bluetooth service disconnected
11-04 12:26:25.899  4672  4672 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 12:26:25.899  4672  4672 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 12:26:25.899  4672  4672 D SapService: Received stop request...Stopping profile...
11-04 12:26:25.899  4672  4672 V SapService: stop()
,11-04 12:26:25.900  4672  4733 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 12:26:25.900  4672  4672 I BtOppRfcommListener: stopping Accept Thread
,11-04 12:26:25.900  4672  5300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-04 12:26:25.901  4672  5300 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 12:26:25.901  4672  4672 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:25.901  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:25.901  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.901  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.902  4672  4672 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 12:26:25.902  4672  4733 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 12:26:25.902  4672  4672 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-04 12:26:25.902  4672  4672 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:25.902  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:25.902  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.902  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.903  4672  4672 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 12:26:25.903  4672  4672 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 12:26:25.903  3573  5749 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.211.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
11-04 12:26:25.908  4672  4672 D BluetoothMapService: MAP Service closeService in
,11-04 12:26:25.908  4672  4672 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 12:26:25.908  4672  4672 D ObexServerSockets0: shutdown(block = true)
11-04 12:26:25.909  4672  4672 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 12:26:25.909  4672  4893 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-04 12:26:25.909  4672  4672 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 12:26:25.909  4672  4894 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 12:26:25.909  4672  4882 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 12:26:25.910  4672  4672 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:25.910  4672  4672 V BluetoothAdapterState: isTurningOn()=false
,11-04 12:26:25.910  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.910  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.910  4672  4672 D BluetoothMapService: cleanup()
11-04 12:26:25.910  4672  4672 D BluetoothMapService: MAP Service closeService in
11-04 12:26:25.911  4672  4672 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:25.911  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:25.911  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:25.911  4672  4672 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:25.911  4672  4729 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 12:26:25.911  4672  4729 D BluetoothAdapterProperties: Setting state to 15
11-04 12:26:25.911  4672  4729 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 12:26:25.911  4672  4729 I BluetoothAdapterState: Entering BleOnState
,11-04 12:26:25.914  3131  3146 D BluetoothPbap: onBluetoothStateChange: up=false
,11-04 12:26:25.914   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 12:26:25.914   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:25.915   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:25.915   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:25.915   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 12:26:25.915  3131  3147 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 12:26:25.916  3131  4130 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:25.916  3768  3793 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:25.916  3131  5607 D BluetoothMap: onBluetoothStateChange: up=false
11-04 12:26:25.917  3131  3146 D BluetoothPan: onBluetoothStateChange on: false
11-04 12:26:25.917  3131  3147 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 12:26:25.918  4672  4729 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-04 12:26:25.918  4672  4729 D BluetoothAdapterProperties: Setting state to 16
11-04 12:26:25.918  4672  4729 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 12:26:25.919  4672  4729 D BluetoothAdapterProperties: onBleDisable
11-04 12:26:25.919  4672  4729 I BluetoothAdapterState: Entering PendingCommandState
11-04 12:26:25.919  4672  4730 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 12:26:25.920  4672  4868 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 12:26:25.920  4672  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:25.920  4672  4733 D BluetoothAdapterProperties: Scan Mode:20
11-04 12:26:25.921  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:25.921  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:25.923  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:25.943   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:26:25.943   508   925 D CommandListener: Clearing all IP addresses on wlan0
11-04 12:26:25.944   508   925 D TetherController: Setting IP forward enable = 0
11-04 12:26:25.944   928  2941 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-04 12:26:25.944   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 12:26:25.945  5759  5759 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-04 12:26:25.947   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-04 12:26:25.947   928  2937 D DhcpClient: doQuit
11-04 12:26:25.947   928  2937 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 12:26:25.947   928  5365 D DhcpClient: onQuitting
11-04 12:26:25.948  3431  3431 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 12:26:25.949  5257  5257 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9bc333c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-04 12:26:25.949  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:25.954  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:25.954  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:25.956  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:25.956  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 12:26:25.957  3953  3953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 12:26:25.966  3431  3431 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 12:26:25.969  5759  5759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 12:26:25.970  3431  3431 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 12:26:25.975   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@455b4e5:true
,11-04 12:26:25.977  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 12:26:25.991   928  3141 I ActivityManager: Start proc 5787:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-04 12:26:25.994  3431  3431 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-04 12:26:25.998  5759  5759 D LocalBluetoothProfileManager: Adding local MAP profile
11-04 12:26:26.002  5759  5759 D BluetoothMap: Create BluetoothMap proxy object
11-04 12:26:26.009  5759  5759 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-04 12:26:26.010  3431  3431 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 12:26:26.023  5759  5759 D DockEventReceiver: finishStartingService: stopping service
,11-04 12:26:26.031  5787  5787 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 12:26:26.033   928  3795 I ActivityManager: Killing 5120:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-04 12:26:26.114   928  2937 D wifi    : In wifi stop Hal
,11-04 12:26:26.114   928  2937 D wifi    : halHandle = 0x7f869b0b80, mVM = 0x7fa2b0d140, mCls = 0x100a02
,11-04 12:26:26.114   928  3430 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 12:26:26.114   928  3430 D WifiHAL : Got a signal to exit!!!
11-04 12:26:26.114   928  3430 I WifiHAL : Exit wifi_event_loop
,11-04 12:26:26.114   928  2937 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 12:26:26.114   928  2937 E WifiHAL : Event processing terminated
11-04 12:26:26.115   928  2937 D wifi    : In wifi cleaned up handler
11-04 12:26:26.115  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 12:26:26.115   928  2937 I WifiHAL : Internal cleanup completed
11-04 12:26:26.116  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:26.117  3704  4189 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 12:26:26.127  4672  4733 I bt_hci  : shut_down
,11-04 12:26:26.131  4672  4737 D bt_hwcfg: hw_epilog_process
,11-04 12:26:26.131  4672  4737 I bt_vendor: low_power_mode_cb
,11-04 12:26:26.134  4672  4737 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 12:26:26.134  4672  4737 I bt_vendor: epilog_cb
11-04 12:26:26.134  4672  4737 I bt_hci  : epilog_finished_callback
11-04 12:26:26.135   928  3430 D wifi    : set interface wlan0 flags (DOWN)
11-04 12:26:26.135   928  2937 D WifiNative-HAL: HAL event thread stopped successfully
11-04 12:26:26.136  4672  4733 I bt_hci_h4: hal_close
11-04 12:26:26.137  4672  4733 I bt_userial_vendor: device fd = 54 close
,11-04 12:26:26.244  4672  4730 D bt_stack_manager: event_shut_down_stack finished.
,11-04 12:26:26.245  4672  4729 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 12:26:26.246  4672  4729 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 12:26:26.246  4672  4672 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 12:26:26.247  4672  4672 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 12:26:26.247  4672  4672 D BtGatt.GattService: stop()
,11-04 12:26:26.247  4672  4672 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 12:26:26.249  4672  4672 V BluetoothAdapterState: isTurningOff()=false
,11-04 12:26:26.249  4672  4672 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:26.249  4672  4672 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 12:26:26.249  4672  4672 V BluetoothAdapterState: isBleTurningOff()=true
11-04 12:26:26.249  4672  4729 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 12:26:26.249  4672  4729 D BluetoothAdapterProperties: Setting state to 10
11-04 12:26:26.250  4672  4729 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 12:26:26.250  4672  4729 I BluetoothAdapterState: Entering OffState
11-04 12:26:26.251   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-04 12:26:26.257  4672  4672 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 12:26:26.257  4672  4672 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 12:26:26.257  4672  4672 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 12:26:26.259  4672  4730 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 12:26:26.265  4672  4672 I art     : System.exit called, status: 0
,11-04 12:26:26.265  4672  4672 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 12:26:26.294  5787  5787 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-04 12:26:26.294  5787  5787 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.294  5787  5787 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.294  5787  5787 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.294  5787  5787 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.294  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.295  5787  5787 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.295  5787  5787 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.295  5787  5787 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 12:26:26.295  5787  5787 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 12:26:26.299  5759  5759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 12:26:26.301   928   939 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-04 12:26:26.302   928   939 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
11-04 12:26:26.303   928   939 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
11-04 12:26:26.303   928   939 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
11-04 12:26:26.303   928   939 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
11-04 12:26:26.330   928   939 I ActivityManager: Start proc 5819:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-04 12:26:26.331  5759  5759 D DockEventReceiver: finishStartingService: stopping service
11-04 12:26:26.331   928  3144 W ActivityManager: Spurious death for ProcessRecord{80a585d 5819:com.android.bluetooth/1002}, curProc for 4672: null
,11-04 12:26:26.332   928  3812 I ActivityManager: Killing 5437:com.qualcomm.timeservice/1000 (adj 15): empty #17
11-04 12:26:26.338   928   945 D Tethering: InitialState.processMessage what=4
11-04 12:26:26.359   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 12:26:26.411  5819  5819 D AdapterServiceConfig: Adding HeadsetService
11-04 12:26:26.411  5819  5819 D AdapterServiceConfig: Adding A2dpService
11-04 12:26:26.411  5819  5819 D AdapterServiceConfig: Adding HidService
11-04 12:26:26.411  5819  5819 D AdapterServiceConfig: Adding HealthService
11-04 12:26:26.412  5819  5819 D AdapterServiceConfig: Adding PanService
11-04 12:26:26.412  5819  5819 D AdapterServiceConfig: Adding GattService
11-04 12:26:26.412  5819  5819 D AdapterServiceConfig: Adding BluetoothMapService
11-04 12:26:26.412  5819  5819 D AdapterServiceConfig: Adding SapService
,11-04 12:26:26.414   928  3798 I ActivityManager: Killing 5424:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-04 12:26:26.441  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 12:26:26.450  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 12:26:26.453  3968  3968 D SystemUpdateService: onCreate
,11-04 12:26:26.458  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 12:26:26.464  3968  5831 I SystemUpdateService: active receiver: enabled
,11-04 12:26:26.466  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 12:26:26.472  3968  4268 I iu.UploadsManager: num queued entries: 0
,11-04 12:26:26.472  3968  4268 I iu.UploadsManager: num updated entries: 0
,11-04 12:26:26.477  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 12:26:26.478  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 12:26:26.480  3968  4268 I iu.SyncManager: NEXT; no task
,11-04 12:26:26.486  3968  5831 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 12:26:26.491   928  3795 I ActivityManager: Start proc 5833:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-04 12:26:26.494  3968  5831 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 12:26:26.494  3968  5831 I SystemUpdateService: now status is 0 (complete)
11-04 12:26:26.494  3968  5831 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 12:26:26.494  3968  5831 I SystemUpdateService: file has been verified
11-04 12:26:26.494  3968  5831 I SystemUpdateService: OTA package size = 21989297
,11-04 12:26:26.508  3968  5831 I SystemUpdateService: showing system update notification
,11-04 12:26:26.524  5833  5833 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-04 12:26:26.528  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 12:26:26.536  5833  5833 D SprintDMHelper: simOperator: 
,11-04 12:26:26.537  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 12:26:26.542   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 12:26:26.548   928  3812 I ActivityManager: Start proc 5845:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-04 12:26:26.552  3968  3968 D SystemUpdateService: onDestroy
,11-04 12:26:26.555   928  3406 I ActivityManager: Killing 5257:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 12:26:26.668   928  3405 I ActivityManager: Start proc 5861:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-04 12:26:26.670   928  3141 I ActivityManager: Killing 3873:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-04 12:26:26.685  5787  5813 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 12:26:26.695   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1909609:true
,11-04 12:26:26.708   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 12:26:26.731  5861  5861 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-04 12:26:26.912   928  3141 I ActivityManager: Killing 5484:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-04 12:26:26.948   928  3798 I ActivityManager: Start proc 5875:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 12:26:26.981  5875  5875 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 12:26:26.989   928  3406 I ActivityManager: Killing 3390:android.process.acore/u0a2 (adj 15): empty #17
,11-04 12:26:26.995   508   925 E Netd    : netlink response contains error (No such file or directory)
,11-04 12:26:26.997   928  2941 E NetdConnector: NDC Command {108 network destroy 100} took too long (1052ms)
11-04 12:26:26.997   928  2941 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 12:26:26.997   928  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 12:26:26.997   928  2935 E NetdConnector: NDC Command {109 bandwidth setglobalalert 2097152} took too long (1046ms)
11-04 12:26:26.997   508   925 D TetherController: Setting IP forward enable = 0
,11-04 12:26:26.999   928  2934 E NetdConnector: NDC Command {110 bandwidth gettetherstats} took too long (639ms)
,11-04 12:26:30.855   928  3798 D WifiService: setWifiEnabled: true pid=5608, uid=10077
,11-04 12:26:30.855   928  3798 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 12:26:30.865   508   925 D SoftapController: Softap fwReload - Ok
,11-04 12:26:30.870   508   925 D CommandListener: Setting iface cfg
,11-04 12:26:30.871   508   925 D CommandListener: Trying to bring down wlan0
11-04 12:26:30.873   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-04 12:26:30.878   928  2937 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 12:26:31.447   928  2937 D wifi    : set interface wlan0 flags (UP)
,11-04 12:26:31.450   928  2937 I WifiHAL : Initializing wifi
11-04 12:26:31.450   928  2937 I WifiHAL : Creating socket
11-04 12:26:31.451   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 12:26:31.455   928  2937 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 12:26:31.455   928  2937 D wifi    : Did set static halHandle = 0x7f869b0b80
11-04 12:26:31.455   928  2937 D wifi    : halHandle = 0x7f869b0b80, mVM = 0x7fa2b0d140, mCls = 0x1962
,11-04 12:26:31.456   928  2937 D wifi    : array field set
11-04 12:26:31.456   928  2937 I WifiNative-HAL: interface[0] = wlan0
11-04 12:26:31.458   928  5899 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547719154560
11-04 12:26:31.458   928  5899 D wifi    : waitForHalEvents called, vm = 0x7fa2b0d140, obj = 0x1962, env = 0x7f869bea00
,11-04 12:26:31.529  5900  5900 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 12:26:31.559   928  2937 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 12:26:31.562  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:31.602  5900  5900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 12:26:31.648  5900  5900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 12:26:31.649  5900  5900 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 12:26:31.669   928  2937 D WifiConfigStore: Loading config and enabling all networks 
,11-04 12:26:31.670  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:31.670  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:31.670  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:31.670  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 12:26:31.697   928  2937 D WifiConfigStore: loaded 0 passpoint configs
,11-04 12:26:31.698   928  2937 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 12:26:31.698   928  2937 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-04 12:26:31.699   928  2937 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 12:26:31.700   928  2937 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 12:26:31.700   928  2937 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 12:26:31.701   928  2937 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-04 12:26:31.701   928  2937 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 12:26:31.701   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 12:26:31.701   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 12:26:31.701   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-04 12:26:31.701   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 12:26:31.701   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 12:26:31.704   928  2937 D WifiNative-HAL: Setting external_sim to 1
,11-04 12:26:31.704   928  2937 D wifi    : setting dfs flag to true, 0x7f8a7cc880
,11-04 12:26:31.704  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 12:26:31.704   928  2937 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 12:26:31.704   928  2937 D wifi    : setting scan oui 0x7f8a7cc880
11-04 12:26:31.704   928  2937 D WifiHAL : Sending mac address OUI
,11-04 12:26:31.707   928  2937 E native  : do suspend false
,11-04 12:26:31.709   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:31.717   928  2937 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 12:26:31.717   928   928 D RttService: SCAN_AVAILABLE : 3
,11-04 12:26:31.718   928  3048 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 12:26:31.722   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-04 12:26:31.724   508   925 D CommandListener: Setting iface cfg
,11-04 12:26:31.727   928  2936 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-04 12:26:31.727   928  2936 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 12:26:31.735   928  2936 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 12:26:31.735   928  2936 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 12:26:31.741   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128891 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,11-04 12:26:32.711   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:33.711   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:34.712   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:34.784  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 12:26:34.788  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 12:26:34.792  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 12:26:34.840   928  2937 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 12:26:34.841   928  2937 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 12:26:34.841   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:26:34.854   928  2937 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 12:26:34.888   928  2937 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 12:26:34.895  5900  5900 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 12:26:35.337  5900  5900 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 12:26:35.383  5900  5900 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 12:26:35.383  5900  5900 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 12:26:35.397   928  2937 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 12:26:35.397   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:26:35.397   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 12:26:35.415   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:26:35.429   508   925 D CommandListener: Setting iface cfg
,11-04 12:26:35.434   928  2937 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 12:26:35.439   928  5906 D DhcpClient: Receive thread started
,11-04 12:26:35.443   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 12:26:35.443   928  2937 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-04 12:26:35.443   928  2941 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 12:26:35.524   928  2937 E native  : do suspend false
,11-04 12:26:35.539   928  5905 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 12:26:35.550   928  5906 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-04 12:26:35.551   928  5905 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-04 12:26:35.554   928  5905 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 12:26:35.580   928  5906 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 12:26:35.581   928  5905 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 12:26:35.585   508   925 D CommandListener: Setting iface cfg
,11-04 12:26:35.590   928  2937 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 12:26:35.596   928  5905 D DhcpClient: Scheduling renewal in 86399s
,11-04 12:26:35.605   928  2937 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 12:26:35.606   928  2937 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 12:26:35.607   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-04 12:26:35.608   928  2941 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 12:26:35.615   928  2937 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 12:26:35.651   928  2941 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-04 12:26:35.651   928  2941 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 12:26:35.655   928  2941 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 12:26:35.660   928  2941 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 12:26:35.662   928  2941 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 12:26:35.667   928  2941 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 12:26:35.671   928  2941 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 12:26:35.672   928  2941 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 12:26:35.672   928  2941 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 12:26:35.672   928  2941 D ConnectivityService:    accepting network in place of null
11-04 12:26:35.672   928  2937 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 12:26:35.672   928  2937 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 12:26:35.672   928  2941 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 12:26:35.695   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:26:35.713   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:35.717   928  5904 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132867, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 12:26:35.718   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:26:35.723   928  2941 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 12:26:35.724   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 12:26:35.724  3723  3869 W QCNEJ   : |CORE| network available: 101
11-04 12:26:35.725   928  2941 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-04 12:26:35.725   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-04 12:26:35.728  3723  3869 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 12:26:35.729  3723  3869 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 12:26:35.730  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:26:35.730  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 12:26:35.730  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:35.730  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 12:26:35.730  3723  3869 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 12:26:35.742  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 12:26:35.746  3953  3953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-04 12:26:35.747  3968  3968 D SystemUpdateService: onCreate
,11-04 12:26:35.751  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 12:26:35.760  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 12:26:35.766  3968  4268 I iu.UploadsManager: num queued entries: 0
,11-04 12:26:35.766  3968  4268 I iu.UploadsManager: num updated entries: 0
,11-04 12:26:35.767  3968  5915 I SystemUpdateService: active receiver: enabled
,11-04 12:26:35.770  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 12:26:35.772  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 12:26:35.773  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-04 12:26:35.777  5833  5833 D SprintDMHelper: simOperator: 
11-04 12:26:35.777  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 12:26:35.790   928  5903 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 12:26:35.802  3968  5915 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 12:26:35.792  3968  4268 I iu.SyncManager: NEXT; no task
,11-04 12:26:35.808  3968  5915 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 12:26:35.808  3968  5915 I SystemUpdateService: now status is 0 (complete)
11-04 12:26:35.808  3968  5915 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 12:26:35.808  3968  5915 I SystemUpdateService: file has been verified
11-04 12:26:35.808  3968  5915 I SystemUpdateService: OTA package size = 21989297
,11-04 12:26:35.815  3968  5915 I SystemUpdateService: showing system update notification
,11-04 12:26:35.822   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 12:26:35.823  3968  3968 D SystemUpdateService: onDestroy
,11-04 12:26:35.846   928  5903 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 11:26:35 GMT], X-Android-Received-Millis=[1478258795845], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478258795819]}
,11-04 12:26:35.847   928  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 12:26:35.847   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 12:26:35.847   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 12:26:35.849   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 12:26:35.863   928  3405 D WifiService: setWifiEnabled: false pid=5608, uid=10077
11-04 12:26:35.863   928  3405 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 12:26:35.865   928  2937 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 12:26:35.865   928  2937 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 12:26:35.865   928  2937 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 12:26:35.865   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:26:35.875   928  5905 D DhcpClient: Clearing IP address
,11-04 12:26:35.875   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-04 12:26:35.877   508   925 D CommandListener: Setting iface cfg
,11-04 12:26:35.882  3573  5916 V NativeCrypto: SSL handshake aborted: ssl=0x7fa12d9500: I/O error during system call, Connection timed out
,11-04 12:26:35.885   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 12:26:35.885   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-04 12:26:35.888   540   540 E Parcel  : Reading a NULL string not supported here.
11-04 12:26:35.890   928   928 D RttService: SCAN_AVAILABLE : 1
11-04 12:26:35.890   928  3048 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 12:26:35.894   928  2941 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-04 12:26:35.895   928  2937 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-04 12:26:35.896  3723  3869 W QCNEJ   : |CORE| network lost: 101
,11-04 12:26:35.897  3723  3869 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 12:26:35.898   928  2937 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 12:26:35.907   928  5906 D DhcpClient: Receive thread stopped,
,11-04 12:26:35.919   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:26:35.938   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:26:35.939   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-04 12:26:35.939   928  2941 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-04 12:26:35.939   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 12:26:35.942   928   945 D Tethering: MasterInitialState.processMessage what=3
11-04 12:26:35.944   928  2937 D DhcpClient: doQuit
11-04 12:26:35.944   928  2937 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 12:26:35.944   928  5905 D DhcpClient: onQuitting
11-04 12:26:35.944  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:35.944  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:35.944  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:35.945  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 12:26:35.945  5900  5900 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 12:26:35.946  3953  3953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-04 12:26:35.949  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:35.949  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:35.949  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:35.949  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 12:26:35.952  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 12:26:35.955  3968  3968 D SystemUpdateService: onCreate
,11-04 12:26:35.959  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 12:26:35.962  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-04 12:26:35.962  3968  5930 I SystemUpdateService: active receiver: enabled
,11-04 12:26:35.966  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 12:26:35.967  5900  5900 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 12:26:35.972  3968  4268 I iu.UploadsManager: num queued entries: 0
,11-04 12:26:35.972  3968  4268 I iu.UploadsManager: num updated entries: 0
,11-04 12:26:35.973  3968  4268 I iu.SyncManager: NEXT; no task
11-04 12:26:35.975  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 12:26:35.977  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 12:26:35.978  3968  5930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 12:26:35.979  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 12:26:35.984  5833  5833 D SprintDMHelper: simOperator: 
11-04 12:26:35.984  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 12:26:35.994  3968  5930 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-04 12:26:35.994  3968  5930 I SystemUpdateService: now status is 0 (complete)
11-04 12:26:35.994  3968  5930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 12:26:35.994  3968  5930 I SystemUpdateService: file has been verified
11-04 12:26:35.994  3968  5930 I SystemUpdateService: OTA package size = 21989297
,11-04 12:26:35.998   508   925 E Netd    : netlink response contains error (No such file or directory)
11-04 12:26:35.999   928  2941 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-04 12:26:36.009  5900  5900 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 12:26:36.012  3968  5930 I SystemUpdateService: showing system update notification
,11-04 12:26:36.021   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 12:26:36.023  3968  3968 D SystemUpdateService: onDestroy
,11-04 12:26:36.023  5900  5900 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 12:26:36.127   928  2937 D wifi    : In wifi stop Hal
,11-04 12:26:36.127   928  2937 D wifi    : halHandle = 0x7f869b0b80, mVM = 0x7fa2b0d140, mCls = 0x1962
,11-04 12:26:36.127   928  5899 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-04 12:26:36.127   928  5899 D WifiHAL : Got a signal to exit!!!
11-04 12:26:36.127   928  5899 I WifiHAL : Exit wifi_event_loop
11-04 12:26:36.128   928  2937 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 12:26:36.128   928  2937 E WifiHAL : Event processing terminated
11-04 12:26:36.128   928  2937 D wifi    : In wifi cleaned up handler
,11-04 12:26:36.129   928  2937 I WifiHAL : Internal cleanup completed
,11-04 12:26:36.129  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:36.129  3704  4189 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 12:26:36.130  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 12:26:36.158   928  5899 D wifi    : set interface wlan0 flags (DOWN)
,11-04 12:26:36.158   928  2937 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 12:26:36.364   928   945 D Tethering: InitialState.processMessage what=4
,11-04 12:26:36.371   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 12:26:36.714   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 12:26:36.725   928  2941 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 12:26:40.902   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2662f83:true
,11-04 12:26:40.903  5819  5819 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 12:26:40.907  5819  5819 I bt_bluedroid: init
,11-04 12:26:40.907  5819  5936 I BluetoothAdapterState: Entering OffState
,11-04 12:26:40.911  5819  5937 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 12:26:40.911  5819  5937 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 12:26:40.911  5819  5937 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 12:26:40.911  5819  5937 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 12:26:40.912  5819  5819 I bt_bluedroid: get_profile_interface socket
,11-04 12:26:40.916  5819  5940 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 12:26:40.916  5819  5819 I bt_bluedroid: get_profile_interface sdp
11-04 12:26:40.918  5819  5940 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 12:26:40.922  5819  5830 I bt_bluedroid: config_hci_snoop_log
,11-04 12:26:40.924   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 12:26:40.929  5819  5936 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 12:26:40.929  5819  5936 D BluetoothAdapterProperties: Setting state to 14
,11-04 12:26:40.930  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 12:26:40.932  5819  5936 D BluetoothBondStateMachine: make
,11-04 12:26:40.934  5819  5941 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 12:26:40.937  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
,11-04 12:26:40.938  5819  5819 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 12:26:40.941  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:40.941  5819  5819 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 12:26:40.942  5819  5819 D BtGatt.GattService: Received start request. Starting profile...
11-04 12:26:40.942  5819  5819 D BtGatt.GattService: start()
11-04 12:26:40.942  5819  5819 I bt_bluedroid: get_profile_interface gatt
11-04 12:26:40.943  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:40.943  5819  5819 D BtGatt.AdvertiseManager: advertise manager created
,11-04 12:26:40.949  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,11-04 12:26:40.949  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:40.949  5819  5819 V BluetoothAdapterState: isBleTurningOn()=true
11-04 12:26:40.950  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 12:26:40.950  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 12:26:40.952  5819  5936 I bt_bluedroid: bt_bluedroid
11-04 12:26:40.952  5819  5937 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 12:26:40.952  5819  5937 I bt_hci  : start_up
,11-04 12:26:40.958  5819  5937 I bt_vendor: alloc value 0xf3af8871
,11-04 12:26:40.958  5819  5937 I bt_vendor: init
11-04 12:26:40.958  5819  5937 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 12:26:40.958  5819  5937 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 12:26:41.070  5819  5937 D bt_hci  : start_up starting async portion
,11-04 12:26:41.070  5819  5944 I bt_hci  : event_finish_startup
11-04 12:26:41.071  5819  5944 I bt_hci_h4: hal_open
11-04 12:26:41.071  5819  5944 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 12:26:41.072  5945  5945 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 12:26:41.074  5819  5944 I bt_userial_vendor: device fd = 54 open
,11-04 12:26:41.088  5819  5944 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 12:26:41.094  5819  5944 D bt_hwcfg: Chipset BCM4358A3
,11-04 12:26:41.094  5819  5944 D bt_hwcfg: Target name = [BCM4358A3]
11-04 12:26:41.095  5819  5944 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 12:26:41.496  5819  5944 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-04 12:26:41.497  5819  5944 D bt_hwcfg: Settlement delay -- 100 ms
11-04 12:26:41.497  5819  5944 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 12:26:41.631  5819  5944 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 12:26:41.631  5819  5944 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 12:26:41.633  5819  5944 I bt_hwcfg: vendor lib fwcfg completed
11-04 12:26:41.633  5819  5944 I bt_vendor: firmware callback
11-04 12:26:41.633  5819  5944 I bt_hci  : firmware_config_callback
,11-04 12:26:41.644  5819  5947 I bt_btu  : btu_task pending for preload complete event
,11-04 12:26:41.644  5819  5947 I bt_btu_task: Bluetooth chip preload is complete
11-04 12:26:41.644  5819  5947 I bt_btu  : btu_task received preload complete event
,11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 12:26:41.651  5819  5947 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_GAP
,11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-04 12:26:41.652  5819  5947 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 12:26:41.732  5819  5947 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a76549
,11-04 12:26:41.732  5819  5947 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a76549 
,11-04 12:26:41.747  5819  5940 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 12:26:41.748  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 12:26:41.749  5819  5940 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 12:26:41.752  5819  5940 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 12:26:41.757  5819  5940 D BluetoothAdapterProperties: Scan Mode:20
,11-04 12:26:41.758  5819  5940 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 12:26:41.758  5819  5940 D bt_hci  : do_postload posting postload work item
11-04 12:26:41.758  5819  5944 I bt_hci  : event_postload
11-04 12:26:41.758  5819  5944 I bt_vendor: sco_config_cb
,11-04 12:26:41.758  5819  5944 I bt_hci  : sco_config_callback postload finished.
11-04 12:26:41.761  5819  5940 D bt_bte_conf: Device ID record 1 : primary
11-04 12:26:41.761  5819  5940 D bt_bte_conf:   vendorId            = 000f
11-04 12:26:41.761  5819  5940 D bt_bte_conf:   vendorIdSource      = 0001
11-04 12:26:41.761  5819  5940 D bt_bte_conf:   product             = 1200
11-04 12:26:41.761  5819  5940 D bt_bte_conf:   version             = 1436
11-04 12:26:41.762  5819  5940 D bt_bte_conf:   clientExecutableURL = 
11-04 12:26:41.762  5819  5940 D bt_bte_conf:   serviceDescription  = 
,11-04 12:26:41.762  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:41.762  5819  5940 D bt_bte_conf:   documentationURL    = 
11-04 12:26:41.762  5819  5940 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 12:26:41.762  5819  5937 D bt_stack_manager: event_start_up_stack finished
11-04 12:26:41.763  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 12:26:41.764  5819  5936 D BluetoothAdapterProperties: Setting state to 15
,11-04 12:26:41.764  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 12:26:41.765  5819  5936 I BluetoothAdapterState: Entering BleOnState
,11-04 12:26:41.768  5819  5944 I bt_vendor: low_power_mode_cb
,11-04 12:26:41.771  5819  5936 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 12:26:41.771  5819  5936 D BluetoothAdapterProperties: Setting state to 11
11-04 12:26:41.771  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 12:26:41.776  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:41.777  5819  5819 D HeadsetService: Received start request. Starting profile...
11-04 12:26:41.779  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:41.779  5819  5819 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-04 12:26:41.780  5819  5819 D HeadsetStateMachine: make
,11-04 12:26:41.790  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
,11-04 12:26:41.790  5819  5819 D HeadsetStateMachine: max_hf_connections = 1
11-04 12:26:41.790  5819  5819 I bt_bluedroid: get_profile_interface handsfree
11-04 12:26:41.791  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 12:26:41.791  5819  5940 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 12:26:41.795  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:41.795  5819  5819 D A2dpService: Received start request. Starting profile...
,11-04 12:26:41.796  5819  5819 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 12:26:41.796  5819  5819 I bt_bluedroid: get_profile_interface avrcp
,11-04 12:26:41.802  5819  5819 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 12:26:41.802  5819  5819 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 12:26:41.802  5819  5819 D A2dpStateMachine: make
11-04 12:26:41.803  5819  5819 I bt_bluedroid: get_profile_interface a2dp
,11-04 12:26:41.803  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 12:26:41.805  5819  5955 D A2dpStateMachine: Enter Disconnected: -2
,11-04 12:26:41.805  5819  5819 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 12:26:41.806  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:41.808  5819  5819 D HidService: Received start request. Starting profile...
,11-04 12:26:41.808  5819  5819 I bt_bluedroid: get_profile_interface hidhost
11-04 12:26:41.808  5759  5759 D BluetoothInputDevice: Proxy object connected
11-04 12:26:41.808  5819  5940 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a5756d
11-04 12:26:41.808  5819  5819 D HidService: setHidService(): set to: null
11-04 12:26:41.808  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 12:26:41.809  5819  5819 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 12:26:41.810  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
11-04 12:26:41.810  5819  5819 D HealthService: Received start request. Starting profile...
11-04 12:26:41.810  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 12:26:41.813  5759  5759 D HidProfile: Bluetooth service connected
,11-04 12:26:41.814  5819  5819 I bt_bluedroid: get_profile_interface health
11-04 12:26:41.814  5819  5819 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-04 12:26:41.815  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:41.817  5819  5819 D PanService: Received start request. Starting profile...
,11-04 12:26:41.817  5819  5819 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 12:26:41.817  5819  5819 I bt_bluedroid: get_profile_interface pan
,11-04 12:26:41.818  5759  5759 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 12:26:41.818  5759  5759 D PanProfile: Bluetooth service connected
11-04 12:26:41.819  5819  5940 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 12:26:41.822  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:41.823  5759  5759 D BluetoothMap: Proxy object connected
,11-04 12:26:41.823  5819  5819 D BluetoothMapService: Received start request. Starting profile...
11-04 12:26:41.823  5819  5819 D BluetoothMapService: start()
11-04 12:26:41.824  5759  5759 D MapProfile: Bluetooth service connected
11-04 12:26:41.824  5759  5759 D BluetoothMap: getConnectedDevices()
11-04 12:26:41.824  5759  5759 D BluetoothMap: Bluetooth is Not enabled
,11-04 12:26:41.826  5819  5819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 12:26:41.827  5819  5819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 12:26:41.827  5819  5819 D BluetoothMapAppObserver: createReceiver()
,11-04 12:26:41.829  5819  5819 D BluetoothMapAppObserver: initObservers()
11-04 12:26:41.829  5819  5819 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 12:26:41.836  5819  5819 V SapService: SapBinder()
,11-04 12:26:41.836  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a2146
,11-04 12:26:41.837  5819  5819 D SapService: Received start request. Starting profile...
11-04 12:26:41.837  5819  5819 V SapService: start()
,11-04 12:26:41.838  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,11-04 12:26:41.838  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.838  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:41.838  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.839  5819  5953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.839  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:41.840  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 12:26:41.841  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:41.841  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 12:26:41.841  5819  5936 D BluetoothAdapterProperties: ScanMode =  20
,11-04 12:26:41.841  5819  5936 D BluetoothAdapterProperties: State =  11
,11-04 12:26:41.841  5819  5936 D BluetoothAdapterProperties: Setting state to 12
11-04 12:26:41.841  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 12:26:41.842  5819  5936 I BluetoothAdapterState: Entering OnState
11-04 12:26:41.842  3131  3146 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 12:26:41.844  5819  5940 D BluetoothAdapterProperties: Scan Mode:21
11-04 12:26:41.844  5819  5940 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 12:26:41.844   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:41.844   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 12:26:41.844   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:41.844   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 12:26:41.845  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 12:26:41.846  3131  4130 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 12:26:41.847   928   928 D BluetoothA2dp: Proxy object connected
11-04 12:26:41.849  3131  3131 D BluetoothA2dp: Proxy object connected
11-04 12:26:41.849  5759  5774 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:41.850  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:41.850  5759  5770 D BluetoothMap: onBluetoothStateChange: up=true
11-04 12:26:41.851  5759  5774 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 12:26:41.851  3131  5607 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 12:26:41.851  3768  3797 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:41.852  5759  5770 D BluetoothPan: onBluetoothStateChange on: true
11-04 12:26:41.852  3131  3146 D BluetoothMap: onBluetoothStateChange: up=true
11-04 12:26:41.853  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 12:26:41.854  3131  3131 D BluetoothMap: Proxy object connected
11-04 12:26:41.854  3131  3147 D BluetoothPan: onBluetoothStateChange on: true
11-04 12:26:41.854  3131  3131 D MapProfile: Bluetooth service connected
11-04 12:26:41.854  3131  3131 D BluetoothMap: getConnectedDevices()
11-04 12:26:41.855  5819  5819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 12:26:41.855  5819  5819 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 12:26:41.856  3131  3146 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 12:26:41.856  3131  3131 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 12:26:41.856  3131  3131 D PanProfile: Bluetooth service connected
11-04 12:26:41.856  5819  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 12:26:41.857  3131  3131 D BluetoothInputDevice: Proxy object connected
11-04 12:26:41.857  3131  3131 D HidProfile: Bluetooth service connected
11-04 12:26:41.859  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 12:26:41.859   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 12:26:41.860  5819  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:41.861  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:41.862  5759  5759 D LocalBluetoothProfileManager: Adding local A2DP profile
11-04 12:26:41.862  5819  5819 D ObexServerSockets: Succeed to create listening sockets 
11-04 12:26:41.862  5819  5819 D ObexServerSockets0: startAccept()
,11-04 12:26:41.862  5819  5819 D ObexServerSockets0: prepareForNewConnect()
,11-04 12:26:41.865  5819  5819 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 12:26:41.865  5819  5819 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 12:26:41.865  5759  5759 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-04 12:26:41.866  5819  5962 D ObexServerSockets0: Accepting socket connection...
11-04 12:26:41.866  5819  5819 D BluetoothMapService: onReceive
11-04 12:26:41.866  5819  5819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 12:26:41.866  5819  5819 D BluetoothMapService: STATE_ON
11-04 12:26:41.866  5819  5963 D ObexServerSockets0: Accepting socket connection...
11-04 12:26:41.868  5819  5964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:41.869  5819  5964 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 12:26:41.869  5819  5964 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 12:26:41.873  5759  5759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 12:26:41.875  5759  5759 D BluetoothA2dp: Proxy object connected
,11-04 12:26:41.880  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 12:26:41.880  5759  5759 D DockEventReceiver: finishStartingService: stopping service
,11-04 12:26:41.888  3131  3131 D BluetoothPbap: Proxy object connected
,11-04 12:26:41.888  3131  3131 D PbapServerProfile: Bluetooth service connected
,11-04 12:26:41.890  5759  5759 D BluetoothPbap: Proxy object connected
,11-04 12:26:41.890  5759  5759 D PbapServerProfile: Bluetooth service connected
,11-04 12:26:41.894  5819  5819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 12:26:41.894  5819  5819 D ObexServerSockets0: prepareForNewConnect()
,11-04 12:26:41.897  5819  5968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:41.911  5819  5972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:41.912  5819  5972 I BtOppRfcommListener: Accept thread started.
,11-04 12:26:41.946   928   928 D BluetoothHeadset: Proxy object connected
,11-04 12:26:41.946  3768  3793 D BluetoothHeadset: Proxy object connected
11-04 12:26:41.946   928   928 D BluetoothHeadset: Proxy object connected
11-04 12:26:41.946   928   928 D BluetoothHeadset: Proxy object connected
11-04 12:26:41.947  3131  3147 D BluetoothHeadset: Proxy object connected
11-04 12:26:41.947  3131  3131 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:41.951  3131  3146 D BluetoothHeadset: Proxy object connected
11-04 12:26:41.951  3131  3131 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:41.952  3768  3989 D BluetoothHeadset: Proxy object connected
,11-04 12:26:41.968  5759  5774 D BluetoothHeadset: Proxy object connected
,11-04 12:26:41.969  5759  5759 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:42.281  3639  3823 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 12:26:42.281  3639  3823 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 12:26:42.309  3573  3573 I ConfigService: onCreate
,11-04 12:26:43.679   928  2941 D ConnectivityService: handlePromptUnvalidated 101
,11-04 12:26:45.883  5819  5936 D BluetoothAdapterState: Current state: ON, message: 23
,11-04 12:26:45.883  5819  5936 D BluetoothAdapterProperties: Setting state to 13
11-04 12:26:45.884  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 12:26:45.885  5819  5936 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 12:26:45.886  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
,11-04 12:26:45.892  5819  5819 D BluetoothMapService: onReceive
11-04 12:26:45.892  5819  5819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 12:26:45.893  5819  5819 D BluetoothMapService: STATE_TURNING_OFF
11-04 12:26:45.893  5819  5819 D BluetoothMapService: MAP Service closeService in
11-04 12:26:45.894  5819  5819 D BluetoothMapMasInstance0: MAP Service shutdown
,11-04 12:26:45.894  5819  5819 D ObexServerSockets0: shutdown(block = true)
11-04 12:26:45.897  5819  5962 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 12:26:45.898  5819  5940 D BluetoothAdapterProperties: Scan Mode:20
11-04 12:26:45.899  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 12:26:45.896  5819  5819 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 12:26:45.900  5819  5819 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 12:26:45.900  5819  5963 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 12:26:45.900  5819  5949 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 12:26:45.902  5819  5819 I BtOppRfcommListener: stopping Accept Thread
11-04 12:26:45.903  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:26:45.904  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 12:26:45.905  5819  5972 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 12:26:45.906  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 12:26:45.907  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 12:26:45.907  5819  5972 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-04 12:26:45.909  5819  5819 D HeadsetService: Received stop request...Stopping profile...
11-04 12:26:45.911  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:45.911   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:45.911  3768  3797 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:45.912   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 12:26:45.912  5759  5770 D BluetoothHeadset: Proxy object disconnected
,11-04 12:26:45.913   928   928 D BluetoothHeadset: Proxy object disconnected
,11-04 12:26:45.914  3131  4130 D BluetoothHeadset: Proxy object disconnected
,11-04 12:26:45.916  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:45.916  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.916  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:45.916  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:45.917  5819  5819 D A2dpService: Received stop request...Stopping profile...
11-04 12:26:45.917  5819  5955 D A2dpStateMachine: Exit Disconnected: -1
11-04 12:26:45.919   928   928 D BluetoothA2dp: Proxy object disconnected
11-04 12:26:45.919  5759  5759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 12:26:45.921  5819  5819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 12:26:45.924  5819  5819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 12:26:45.925  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 12:26:45.925  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:45.925  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:45.925  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:45.925  3131  3131 D HeadsetProfile: Bluetooth service disconnected
11-04 12:26:45.926  3131  3131 D BluetoothA2dp: Proxy object disconnected
11-04 12:26:45.926  5819  5819 D HidService: Received stop request...Stopping profile...
11-04 12:26:45.926  5819  5819 D HidService: Stopping Bluetooth HidService
,11-04 12:26:45.928  5819  5940 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 12:26:45.929  3131  3131 D BluetoothInputDevice: Proxy object disconnected
,11-04 12:26:45.929  3131  3131 D HidProfile: Bluetooth service disconnected
11-04 12:26:45.929  5759  5759 D HeadsetProfile: Bluetooth service disconnected
11-04 12:26:45.930  5759  5759 D BluetoothA2dp: Proxy object disconnected
11-04 12:26:45.932  5819  5819 D HealthService: Received stop request...Stopping profile...
,11-04 12:26:45.934  5819  5819 D PanService: Received stop request...Stopping profile...
,11-04 12:26:45.936  3131  3131 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 12:26:45.936  3131  3131 D PanProfile: Bluetooth service disconnected
11-04 12:26:45.936  5819  5819 D BluetoothMapService: Received stop request...Stopping profile...
11-04 12:26:45.937  5819  5819 D BluetoothMapService: stop()
11-04 12:26:45.938  5819  5819 D BluetoothMapAppObserver: deinitObservers()
11-04 12:26:45.938  5819  5819 D BluetoothMapAppObserver: removeReceiver()
11-04 12:26:45.939  5759  5759 D DockEventReceiver: finishStartingService: stopping service
11-04 12:26:45.939  3131  3131 D BluetoothMap: Proxy object disconnected
11-04 12:26:45.939  3131  3131 D MapProfile: Bluetooth service disconnected
11-04 12:26:45.939  5819  5819 D SapService: Received stop request...Stopping profile...
11-04 12:26:45.939  5819  5819 V SapService: stop()
11-04 12:26:45.940  5759  5759 D BluetoothInputDevice: Proxy object disconnected
11-04 12:26:45.940  5759  5759 D HidProfile: Bluetooth service disconnected
11-04 12:26:45.940  5759  5759 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 12:26:45.940  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:45.940  5759  5759 D PanProfile: Bluetooth service disconnected
11-04 12:26:45.940  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.940  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:45.940  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 12:26:45.941  5759  5759 D BluetoothMap: Proxy object disconnected
11-04 12:26:45.941  5759  5759 D MapProfile: Bluetooth service disconnected
11-04 12:26:45.941  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:45.941  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 12:26:45.942  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:45.942  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.942  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:45.942  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 12:26:45.942  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:45.942  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-04 12:26:45.942  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 12:26:45.942  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 12:26:45.942  5819  5819 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 12:26:45.942  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 12:26:45.942  5819  5819 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 12:26:45.942  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 12:26:45.944  5819  5819 V BluetoothAdapterState: isTurningOff()=true
,11-04 12:26:45.944  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.944  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:45.944  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:45.945  5819  5819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 12:26:45.945  5819  5940 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 12:26:45.945  5819  5819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 12:26:45.945  5819  5819 V BluetoothAdapterState: isTurningOff()=true
,11-04 12:26:45.945  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.945  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:45.945  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:45.946  5819  5819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 12:26:45.946  5819  5819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 12:26:45.947  5819  5819 D BluetoothMapService: MAP Service closeService in
,11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.947  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:45.947  5819  5819 D BluetoothMapService: cleanup()
11-04 12:26:45.947  5819  5819 D BluetoothMapService: MAP Service closeService in
11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 12:26:45.947  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:45.948  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 12:26:45.948  5819  5936 D BluetoothAdapterProperties: Setting state to 15
11-04 12:26:45.948  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 12:26:45.949  5819  5936 I BluetoothAdapterState: Entering BleOnState
11-04 12:26:45.949  3131  3146 D BluetoothPbap: onBluetoothStateChange: up=false
,11-04 12:26:45.950   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:45.950   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:45.950   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:45.950   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 12:26:45.951  5759  5759 D BluetoothPbap: Proxy object disconnected
11-04 12:26:45.951  3131  5607 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 12:26:45.953  5759  5774 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 12:26:45.953  5759  5770 D BluetoothMap: onBluetoothStateChange: up=false
,11-04 12:26:45.954  5759  5774 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 12:26:45.954  3131  3147 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:45.954  3768  3793 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:45.955  5759  5770 D BluetoothPan: onBluetoothStateChange on: false
11-04 12:26:45.955  3131  4130 D BluetoothMap: onBluetoothStateChange: up=false
11-04 12:26:45.956  3131  3146 D BluetoothPan: onBluetoothStateChange on: false
11-04 12:26:45.956  5759  5774 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 12:26:45.957  5759  5770 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 12:26:45.957  3131  5607 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 12:26:45.957  5819  5936 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 12:26:45.957  5819  5936 D BluetoothAdapterProperties: Setting state to 16
11-04 12:26:45.957  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 12:26:45.951  5759  5759 D PbapServerProfile: Bluetooth service disconnected
11-04 12:26:45.958  5819  5936 D BluetoothAdapterProperties: onBleDisable
11-04 12:26:45.959  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
11-04 12:26:45.959  5819  5937 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 12:26:45.959  5819  5940 D BluetoothAdapterProperties: Scan Mode:20
11-04 12:26:45.959  5819  5947 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 12:26:45.960  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 12:26:45.960  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 12:26:45.961  5759  5759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 12:26:45.967  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 12:26:45.973  5759  5759 D DockEventReceiver: finishStartingService: stopping service
11-04 12:26:45.973  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:46.170  5819  5940 I bt_hci  : shut_down
,11-04 12:26:46.182  5819  5944 D bt_hwcfg: hw_epilog_process
,11-04 12:26:46.182  5819  5944 I bt_vendor: low_power_mode_cb
,11-04 12:26:46.184  5819  5944 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 12:26:46.184  5819  5944 I bt_vendor: epilog_cb
11-04 12:26:46.185  5819  5944 I bt_hci  : epilog_finished_callback
,11-04 12:26:46.188  5819  5940 I bt_hci_h4: hal_close
,11-04 12:26:46.189  5819  5940 I bt_userial_vendor: device fd = 54 close
,11-04 12:26:46.310  5819  5937 D bt_stack_manager: event_shut_down_stack finished.
,11-04 12:26:46.310  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 12:26:46.314  5819  5936 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 12:26:46.315  5819  5819 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 12:26:46.316  5819  5819 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 12:26:46.316  5819  5819 D BtGatt.GattService: stop()
11-04 12:26:46.316  5819  5819 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 12:26:46.320  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,11-04 12:26:46.320  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:46.320  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:46.320  5819  5819 V BluetoothAdapterState: isBleTurningOff()=true
11-04 12:26:46.321  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 12:26:46.321  5819  5936 D BluetoothAdapterProperties: Setting state to 10
,11-04 12:26:46.321  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 12:26:46.322  5819  5936 I BluetoothAdapterState: Entering OffState
11-04 12:26:46.324   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 12:26:46.340  5819  5819 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 12:26:46.340  5819  5819 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 12:26:46.340  5819  5819 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 12:26:46.342  5819  5937 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 12:26:46.347  5819  5819 I art     : System.exit called, status: 0
,11-04 12:26:46.348  5819  5819 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 12:26:46.374   928   939 I ActivityManager: Process com.android.bluetooth (pid 5819) has died
,11-04 12:26:46.715   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:47.339  3573  3573 I ConfigService: onDestroy
,11-04 12:26:47.716   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:48.718   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:49.719   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:50.720   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:26:50.881  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:50.881  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 12:26:50.888  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:50.888  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6c5d46 removed from the list
,11-04 12:26:50.888  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 12:26:50.891  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 12:26:50.891  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a4f825d added. We now have 4 listener(s)
,11-04 12:26:50.891  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:26:50.893  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:26:50.894  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a4f825d removed from the list
,11-04 12:26:50.894  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:26:50.896  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 12:26:50.896  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8107d2 added. We now have 4 listener(s)
11-04 12:26:50.896  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:26:51.720   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 12:26:55.064   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 12:26:55.069  5857  5857 W Binder_B: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31932]" dev="sockfs" ino=31932 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 12:26:55.075  3639  3639 I Keyboard.Facilitator: onFinishInput()
,11-04 12:26:55.072  5857  5857 W Binder_B: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31932]" dev="sockfs" ino=31932 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:26:55.105   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 12:26:55.105   928   948 I Adreno  : Build Date                       : 12/06/15
11-04 12:26:55.105   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 12:26:55.105   928   948 I Adreno  : Local Branch                     : mybranch17112971
11-04 12:26:55.105   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 12:26:55.105   928   948 I Adreno  : Remote Branch                    : NONE
11-04 12:26:55.105   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 12:26:55.144   381   402 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (154 us)
,11-04 12:26:55.851  5608  5608 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 12:26:55.851  5608  5608 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 12:26:55.879   928   948 I sensors : batch
,11-04 12:26:55.880   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 12:26:55.881  5608  5608 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@31b165d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bbe80a3, 16908290=android.view.AbsSavedState$1@bbe80a3}, android:focusedViewId=100}]}]
,11-04 12:26:55.882  5608  5608 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 12:26:55.882  5608  5608 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 12:26:55.882  5608  5608 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-04 12:26:55.884   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 12:26:55.884   928   948 I sensors : activate
,11-04 12:26:55.885   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fade83c00
,11-04 12:26:55.885   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-04 12:26:55.885   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-04 12:26:55.886   928  2742 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-04 12:26:55.889   928  2742 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 12:26:55.904  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:26:55.916   928   945 I ActivityManager: Start proc 5984:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 12:26:55.960  5984  5984 D AdapterServiceConfig: Adding HeadsetService
11-04 12:26:55.961  5984  5984 D AdapterServiceConfig: Adding A2dpService
,11-04 12:26:55.961  5984  5984 D AdapterServiceConfig: Adding HidService
11-04 12:26:55.961  5984  5984 D AdapterServiceConfig: Adding HealthService
11-04 12:26:55.961  5984  5984 D AdapterServiceConfig: Adding PanService
11-04 12:26:55.961  5984  5984 D AdapterServiceConfig: Adding GattService
11-04 12:26:55.962  5984  5984 D AdapterServiceConfig: Adding BluetoothMapService
,11-04 12:26:55.962  5984  5984 D AdapterServiceConfig: Adding SapService
,11-04 12:26:55.971   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0601b5:true
,11-04 12:26:55.971  5984  5984 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 12:26:55.974  5984  5984 I bt_bluedroid: init
,11-04 12:26:55.974  5984  5996 I BluetoothAdapterState: Entering OffState
,11-04 12:26:55.976  5984  5997 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 12:26:55.976  5984  5997 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 12:26:55.976  5984  5997 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 12:26:55.976  5984  5997 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-04 12:26:55.977  5984  5984 I bt_bluedroid: get_profile_interface socket
,11-04 12:26:55.978  5984  6000 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 12:26:55.979  5984  5984 I bt_bluedroid: get_profile_interface sdp
11-04 12:26:55.980  5984  6000 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 12:26:55.982  5984  5995 I bt_bluedroid: config_hci_snoop_log
,11-04 12:26:55.983   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-04 12:26:55.986  5984  5996 D BluetoothAdapterState: Current state: OFF, message: 0
11-04 12:26:55.986  5984  5996 D BluetoothAdapterProperties: Setting state to 14
,11-04 12:26:55.986  5984  5996 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 12:26:55.988  5984  5996 D BluetoothBondStateMachine: make
,11-04 12:26:55.989  5984  6001 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 12:26:55.992  5984  5996 I BluetoothAdapterState: Entering PendingCommandState
,11-04 12:26:55.993  5984  5984 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-04 12:26:55.995  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
11-04 12:26:55.995  5984  5984 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 12:26:55.996  5984  5984 D BtGatt.GattService: Received start request. Starting profile...
11-04 12:26:55.996  5984  5984 D BtGatt.GattService: start()
11-04 12:26:55.996  5984  5984 I bt_bluedroid: get_profile_interface gatt
,11-04 12:26:55.997  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
11-04 12:26:55.997  5984  5984 D BtGatt.AdvertiseManager: advertise manager created
,11-04 12:26:56.002  5984  5984 V BluetoothAdapterState: isTurningOff()=false
,11-04 12:26:56.002  5984  5984 V BluetoothAdapterState: isTurningOn()=false
11-04 12:26:56.002  5984  5984 V BluetoothAdapterState: isBleTurningOn()=true
11-04 12:26:56.002  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.002  5984  5996 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-04 12:26:56.003  5984  5996 I bt_bluedroid: bt_bluedroid
,11-04 12:26:56.003  5984  5997 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 12:26:56.004  5984  5997 I bt_hci  : start_up
,11-04 12:26:56.008  5984  5997 I bt_vendor: alloc value 0xf3b6d871
11-04 12:26:56.009  5984  5997 I bt_vendor: init
11-04 12:26:56.009  5984  5997 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-04 12:26:56.009  5984  5997 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 12:26:56.117  5984  5997 D bt_hci  : start_up starting async portion
,11-04 12:26:56.118  5984  6004 I bt_hci  : event_finish_startup
11-04 12:26:56.118  5984  6004 I bt_hci_h4: hal_open
,11-04 12:26:56.118  5984  6004 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-04 12:26:56.121  5984  6004 I bt_userial_vendor: device fd = 54 open
,11-04 12:26:56.119  6005  6005 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 12:26:56.135  5984  6004 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 12:26:56.138  5984  6004 D bt_hwcfg: Chipset BCM4358A3
,11-04 12:26:56.138  5984  6004 D bt_hwcfg: Target name = [BCM4358A3]
11-04 12:26:56.138  5984  6004 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 12:26:56.179   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 12:26:56.181   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
11-04 12:26:56.183   928  3077 D SurfaceControl: Excessive delay in setPowerMode(): 297ms
,11-04 12:26:56.202   928   948 I DreamManagerService: Entering dreamland.
,11-04 12:26:56.207   928   948 I PowerManagerService: Dozing...
,11-04 12:26:56.211   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 12:26:56.236  3406  3406 W Binder_6: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33751]" dev="sockfs" ino=33751 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:26:56.236  3406  3406 W Binder_6: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33751]" dev="sockfs" ino=33751 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:26:56.239   928  3798 I sensors : batch
11-04 12:26:56.239   928  3798 I sensors : activate
,11-04 12:26:56.243   928  2742 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 12:26:56.244   928  2742 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 12:26:56.247   513   513 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 12:26:56.272  3768  4744 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 12:26:56.272  3768  4744 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 12:26:56.273  3768  4744 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 12:26:56.273   526  1440 D         : oem-qmi: Connection accepted
11-04 12:26:56.273   526  1440 D         : oem-qmi: Waiting to accept connection
,11-04 12:26:56.277   928   928 I sensors : activate
,11-04 12:26:56.277   513  3004 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-04 12:26:56.278  3768  4744 D         : oem_qmi_lib:output 0
,11-04 12:26:56.278  3768  4744 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-04 12:26:56.279   928  2742 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-04 12:26:56.296  3768  4744 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-04 12:26:56.296  3768  4744 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 12:26:56.296  3768  4744 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 12:26:56.296   526  1440 D         : oem-qmi: Connection accepted
11-04 12:26:56.296   526  1440 D         : oem-qmi: Waiting to accept connection
,11-04 12:26:56.301  3768  4744 D         : oem_qmi_lib:output 0
,11-04 12:26:56.301  3768  4744 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 12:26:56.474  5984  6004 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 12:26:56.474  5984  6004 D bt_hwcfg: Settlement delay -- 100 ms
11-04 12:26:56.474  5984  6004 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 12:26:56.610  5984  6004 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 12:26:56.610  5984  6004 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 12:26:56.611  5984  6004 I bt_hwcfg: vendor lib fwcfg completed
11-04 12:26:56.611  5984  6004 I bt_vendor: firmware callback
11-04 12:26:56.611  5984  6004 I bt_hci  : firmware_config_callback
,11-04 12:26:56.618  5984  6011 I bt_btu  : btu_task pending for preload complete event
,11-04 12:26:56.618  5984  6011 I bt_btu_task: Bluetooth chip preload is complete
11-04 12:26:56.619  5984  6011 I bt_btu  : btu_task received preload complete event
,11-04 12:26:56.625  5984  6011 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 12:26:56.625  5984  6011 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 12:26:56.625  5984  6011 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 12:26:56.625  5984  6011 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_BTM
,11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 12:26:56.626  5984  6011 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 12:26:56.627  5984  6011 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 12:26:56.627  5984  6011 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 12:26:56.627  5984  6011 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 12:26:56.627  5984  6011 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 12:26:56.707  5984  6011 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3aeb549
11-04 12:26:56.708  5984  6011 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3aeb549 
,11-04 12:26:56.721  5984  6000 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 12:26:56.723  5984  6000 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 12:26:56.724  5984  6000 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 12:26:56.726  5984  6000 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 12:26:56.728  5984  6000 D BluetoothAdapterProperties: Scan Mode:20
11-04 12:26:56.728  5984  6000 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 12:26:56.729  5984  6000 D bt_hci  : do_postload posting postload work item
11-04 12:26:56.729  5984  6004 I bt_hci  : event_postload,
11-04 12:26:56.729  5984  6004 I bt_vendor: sco_config_cb
11-04 12:26:56.730  5984  6004 I bt_hci  : sco_config_callback postload finished.
11-04 12:26:56.731  5984  6000 D bt_bte_conf: Device ID record 1 : primary
,11-04 12:26:56.732  5984  6000 D bt_bte_conf:   vendorId            = 000f
11-04 12:26:56.732  5984  6000 D bt_bte_conf:   vendorIdSource      = 0001
,11-04 12:26:56.732  5984  6000 D bt_bte_conf:   product             = 1200
11-04 12:26:56.732  5984  6000 D bt_bte_conf:   version             = 1436
11-04 12:26:56.732  5984  6000 D bt_bte_conf:   clientExecutableURL = 
,11-04 12:26:56.732  5984  6000 D bt_bte_conf:   serviceDescription  = 
11-04 12:26:56.732  5984  6000 D bt_bte_conf:   documentationURL    = 
11-04 12:26:56.732  5984  6000 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 12:26:56.733  5984  5997 D bt_stack_manager: event_start_up_stack finished
11-04 12:26:56.734  5984  5996 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 12:26:56.734  5984  5996 D BluetoothAdapterProperties: Setting state to 15
11-04 12:26:56.735  5984  5996 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 12:26:56.735  5984  5996 I BluetoothAdapterState: Entering BleOnState
,11-04 12:26:56.735  5984  6004 I bt_vendor: low_power_mode_cb
,11-04 12:26:56.740  5984  5996 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 12:26:56.740  5984  5996 D BluetoothAdapterProperties: Setting state to 11
11-04 12:26:56.740  5984  5996 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 12:26:56.745  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
,11-04 12:26:56.747  5984  5984 D HeadsetService: Received start request. Starting profile...
11-04 12:26:56.750  5984  5984 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 12:26:56.751  5984  5984 D HeadsetStateMachine: make
,11-04 12:26:56.763  5984  5996 I BluetoothAdapterState: Entering PendingCommandState
,11-04 12:26:56.766  5984  5984 D HeadsetStateMachine: max_hf_connections = 1
,11-04 12:26:56.766  5984  5984 I bt_bluedroid: get_profile_interface handsfree
11-04 12:26:56.767  5984  6000 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 12:26:56.767  5984  6000 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-04 12:26:56.770  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
11-04 12:26:56.771  5984  5984 D A2dpService: Received start request. Starting profile...
11-04 12:26:56.771  5984  5984 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-04 12:26:56.772  5984  5984 I bt_bluedroid: get_profile_interface avrcp
,11-04 12:26:56.779  5984  5984 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 12:26:56.779  5984  5984 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 12:26:56.779  5984  5984 D A2dpStateMachine: make
,11-04 12:26:56.780  5984  5984 I bt_bluedroid: get_profile_interface a2dp
,11-04 12:26:56.780  5984  6000 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-04 12:26:56.782  5984  6018 D A2dpStateMachine: Enter Disconnected: -2
11-04 12:26:56.782  5984  5984 I BluetoothHidServiceJni: classInitNative: succeeds
11-04 12:26:56.783  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
11-04 12:26:56.784  5984  5984 D HidService: Received start request. Starting profile...
11-04 12:26:56.784  5984  5984 I bt_bluedroid: get_profile_interface hidhost
11-04 12:26:56.784  5984  5984 D HidService: setHidService(): set to: null
11-04 12:26:56.784  5984  6000 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3acc56d
11-04 12:26:56.784  5984  6000 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 12:26:56.786  5984  5984 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 12:26:56.786  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
11-04 12:26:56.787  5984  5984 D HealthService: Received start request. Starting profile...
,11-04 12:26:56.787  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 12:26:56.789  5984  5984 I bt_bluedroid: get_profile_interface health
11-04 12:26:56.789  5984  5984 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 12:26:56.790  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
,11-04 12:26:56.791  5984  5984 D PanService: Received start request. Starting profile...
11-04 12:26:56.791  5984  5984 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 12:26:56.791  5984  5984 I bt_bluedroid: get_profile_interface pan
11-04 12:26:56.791  5984  6000 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 12:26:56.794  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
11-04 12:26:56.794  5984  5984 D BluetoothMapService: Received start request. Starting profile...
11-04 12:26:56.794  5984  5984 D BluetoothMapService: start()
11-04 12:26:56.797  5984  5984 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 12:26:56.797  5984  5984 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 12:26:56.797  5984  5984 D BluetoothMapAppObserver: createReceiver()
11-04 12:26:56.798  5984  5984 D BluetoothMapAppObserver: initObservers()
11-04 12:26:56.799  5984  5984 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 12:26:56.804  5984  5984 V SapService: SapBinder()
,11-04 12:26:56.804  5984  5984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
,11-04 12:26:56.805  5984  5984 D SapService: Received start request. Starting profile...
11-04 12:26:56.805  5984  5984 V SapService: start()
,11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOff()=false
,11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:56.808  5984  6016 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:56.808  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.809  5984  5984 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:56.809  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.809  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 12:26:56.809  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.809  5984  5984 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:56.809  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.810  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:56.810  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
11-04 12:26:56.811  5984  5984 V BluetoothAdapterState: isTurningOff()=false
11-04 12:26:56.811  5984  5984 V BluetoothAdapterState: isTurningOn()=true
11-04 12:26:56.811  5984  5984 V BluetoothAdapterState: isBleTurningOn()=false
11-04 12:26:56.811  5984  5984 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 12:26:56.812  5984  5996 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 12:26:56.812  5984  5996 D BluetoothAdapterProperties: ScanMode =  20
11-04 12:26:56.812  5984  5996 D BluetoothAdapterProperties: State =  11
,11-04 12:26:56.815  5984  6000 D BluetoothAdapterProperties: Scan Mode:21
11-04 12:26:56.815  5984  5996 D BluetoothAdapterProperties: Setting state to 12
11-04 12:26:56.815  5984  5996 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 12:26:56.815  5984  6000 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 12:26:56.815  3131  3146 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 12:26:56.815  5984  5996 I BluetoothAdapterState: Entering OnState
11-04 12:26:56.817   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:56.817   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 12:26:56.817   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:56.817   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 12:26:56.818  3131  5607 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 12:26:56.819   928   928 D BluetoothA2dp: Proxy object connected
11-04 12:26:56.819  3131  3131 D BluetoothA2dp: Proxy object connected
11-04 12:26:56.819  5759  5770 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 12:26:56.821  5759  5774 D BluetoothMap: onBluetoothStateChange: up=true
11-04 12:26:56.822  5759  5770 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 12:26:56.823  5984  5984 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 12:26:56.824  5984  5984 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 12:26:56.824  3131  4130 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:56.825  3768  3793 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 12:26:56.825  5984  5984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 12:26:56.825  5759  5774 D BluetoothPan: onBluetoothStateChange on: true
11-04 12:26:56.826  5984  5984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 12:26:56.827  3131  3146 D BluetoothMap: onBluetoothStateChange: up=true
11-04 12:26:56.827  5984  5984 D ObexServerSockets: Succeed to create listening sockets 
,11-04 12:26:56.827  5984  5984 D ObexServerSockets0: startAccept()
11-04 12:26:56.827  5984  5984 D ObexServerSockets0: prepareForNewConnect()
11-04 12:26:56.828  3131  3147 D BluetoothPan: onBluetoothStateChange on: true
11-04 12:26:56.828  3131  3131 D BluetoothMap: Proxy object connected
11-04 12:26:56.828  3131  3131 D MapProfile: Bluetooth service connected
11-04 12:26:56.828  3131  3131 D BluetoothMap: getConnectedDevices()
11-04 12:26:56.829  5984  5984 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 12:26:56.830  5984  5984 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 12:26:56.830  5759  5759 D BluetoothMap: Proxy object connected
11-04 12:26:56.830  5759  5759 D MapProfile: Bluetooth service connected
11-04 12:26:56.830  5759  5759 D BluetoothMap: getConnectedDevices()
,11-04 12:26:56.830  5984  6026 D ObexServerSockets0: Accepting socket connection...
11-04 12:26:56.830  5984  6027 D ObexServerSockets0: Accepting socket connection...
11-04 12:26:56.831  5759  5770 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 12:26:56.832  3131  3131 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 12:26:56.832  3131  3131 D PanProfile: Bluetooth service connected
,11-04 12:26:56.833  5759  5774 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 12:26:56.834  3131  3146 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 12:26:56.835  3131  3131 D BluetoothInputDevice: Proxy object connected
11-04 12:26:56.835  3131  3131 D HidProfile: Bluetooth service connected
11-04 12:26:56.836   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 12:26:56.837  5984  5984 D BluetoothMapService: onReceive
11-04 12:26:56.837  5984  5984 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 12:26:56.837  5984  5984 D BluetoothMapService: STATE_ON
11-04 12:26:56.838  5759  5759 D BluetoothInputDevice: Proxy object connected
11-04 12:26:56.838  5759  5759 D HidProfile: Bluetooth service connected
,11-04 12:26:56.840  5759  5759 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 12:26:56.840  5759  5759 D PanProfile: Bluetooth service connected
11-04 12:26:56.840  5759  5759 D BluetoothA2dp: Proxy object connected
11-04 12:26:56.840  5984  6029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:56.841  5984  6029 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 12:26:56.841  5984  6029 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 12:26:56.846  5759  5759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 12:26:56.853  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 12:26:56.855  5759  5759 D DockEventReceiver: finishStartingService: stopping service
,11-04 12:26:56.861  3131  3131 D BluetoothPbap: Proxy object connected
,11-04 12:26:56.861  3131  3131 D PbapServerProfile: Bluetooth service connected
,11-04 12:26:56.862  5759  5759 D BluetoothPbap: Proxy object connected
,11-04 12:26:56.862  5759  5759 D PbapServerProfile: Bluetooth service connected
11-04 12:26:56.865  5984  5984 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 12:26:56.865  5984  5984 D ObexServerSockets0: prepareForNewConnect()
,11-04 12:26:56.868  5984  6033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:56.880  5984  6037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 12:26:56.881  5984  6037 I BtOppRfcommListener: Accept thread started.
,11-04 12:26:56.919   928   928 D BluetoothHeadset: Proxy object connected
,11-04 12:26:56.919  3768  3989 D BluetoothHeadset: Proxy object connected
11-04 12:26:56.919   928   928 D BluetoothHeadset: Proxy object connected
,11-04 12:26:56.920  5759  5774 D BluetoothHeadset: Proxy object connected
,11-04 12:26:56.920   928   928 D BluetoothHeadset: Proxy object connected
11-04 12:26:56.920  3131  3146 D BluetoothHeadset: Proxy object connected
11-04 12:26:56.921  3131  3131 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:56.922  5759  5759 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:56.925  3131  4130 D BluetoothHeadset: Proxy object connected
11-04 12:26:56.925  3131  3131 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:56.926  3768  3797 D BluetoothHeadset: Proxy object connected
,11-04 12:26:56.933  5759  5770 D BluetoothHeadset: Proxy object connected
,11-04 12:26:56.933  5759  5759 D HeadsetProfile: Bluetooth service connected
,11-04 12:26:59.762  3704  4439 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 12:27:00.912  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 12:27:00.917  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 12:27:00.918  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:00.918  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8107d2 removed from the list
11-04 12:27:00.918  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:27:00.920  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 12:27:00.920  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c609fa0 added. We now have 4 listener(s)
11-04 12:27:00.920  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:00.922   928  3795 D WifiService: setWifiEnabled: false pid=5608, uid=10077
11-04 12:27:00.922   928  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 12:27:05.931  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 12:27:05.932   928  3141 D WifiService: setWifiEnabled: true pid=5608, uid=10077
11-04 12:27:05.933   928  3141 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 12:27:05.941   508   925 D SoftapController: Softap fwReload - Ok
,11-04 12:27:05.947   508   925 D CommandListener: Setting iface cfg
11-04 12:27:05.948   508   925 D CommandListener: Trying to bring down wlan0
11-04 12:27:05.949   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-04 12:27:05.954   928  2937 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 12:27:06.614   928  2937 D wifi    : set interface wlan0 flags (UP)
11-04 12:27:06.616   928  2937 I WifiHAL : Initializing wifi
,11-04 12:27:06.616   928  2937 I WifiHAL : Creating socket
,11-04 12:27:06.622   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 12:27:06.625   928  2937 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 12:27:06.625   928  2937 D wifi    : Did set static halHandle = 0x7f869b0b80
11-04 12:27:06.626   928  2937 D wifi    : halHandle = 0x7f869b0b80, mVM = 0x7fa2b0d140, mCls = 0x1014e2
,11-04 12:27:06.626   928  2937 D wifi    : array field set
,11-04 12:27:06.626   928  2937 I WifiNative-HAL: interface[0] = wlan0
,11-04 12:27:06.628   928  6042 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547719154560
,11-04 12:27:06.628   928  6042 D wifi    : waitForHalEvents called, vm = 0x7fa2b0d140, obj = 0x1014e2, env = 0x7f89e09f80
,11-04 12:27:06.687  6043  6043 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 12:27:06.721   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:06.730   928  2937 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 12:27:06.759  6043  6043 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 12:27:06.822  6043  6043 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 12:27:06.822  6043  6043 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 12:27:06.836   928  2937 D WifiConfigStore: Loading config and enabling all networks 
,11-04 12:27:06.862   928  2937 D WifiConfigStore: loaded 0 passpoint configs
,11-04 12:27:06.863   928  2937 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 12:27:06.863   928  2937 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 12:27:06.864   928  2937 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 12:27:06.864   928  2937 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 12:27:06.865   928  2937 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 12:27:06.865   928  2937 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 12:27:06.866   928  2937 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-04 12:27:06.866   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 12:27:06.866   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-04 12:27:06.866   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 12:27:06.866   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 12:27:06.866   928  2937 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 12:27:06.868   928  2937 D WifiNative-HAL: Setting external_sim to 1
11-04 12:27:06.869   928  2937 D wifi    : setting dfs flag to true, 0x7f8c021520
,11-04 12:27:06.869   928  2937 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 12:27:06.869   928  2937 D wifi    : setting scan oui 0x7f8c021520
11-04 12:27:06.869   928  2937 D WifiHAL : Sending mac address OUI
11-04 12:27:06.870  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 12:27:06.874   928  2937 E native  : do suspend true
,11-04 12:27:06.884   928  2937 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 12:27:06.885   928   928 D RttService: SCAN_AVAILABLE : 3
11-04 12:27:06.885   928  3048 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 12:27:06.896   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-04 12:27:06.897   508   925 D CommandListener: Setting iface cfg
,11-04 12:27:06.903   928  2936 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,11-04 12:27:06.903   928  2936 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 12:27:06.905   928  2936 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 12:27:06.905   928  2936 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 12:27:06.912   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164062 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
,11-04 12:27:07.722   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:08.723   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:09.724   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:10.048  6043  6043 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 12:27:10.077   928  2937 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 12:27:10.080   928  2937 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-04 12:27:10.081   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:27:10.096   928  2937 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 12:27:10.135   928  2937 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 12:27:10.480  6043  6043 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 12:27:10.515  6043  6043 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 12:27:10.516  6043  6043 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 12:27:10.527   928  2937 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-04 12:27:10.527   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:27:10.528   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 12:27:10.546   928  2937 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 12:27:10.559   508   925 D CommandListener: Setting iface cfg
,11-04 12:27:10.565   928  2937 D WifiStateMachine: Start Dhcp Watchdog 3
,11-04 12:27:10.569   928  2937 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 12:27:10.573   928  6048 D DhcpClient: Receive thread started
,11-04 12:27:10.656   928  2937 E native  : do suspend false
,11-04 12:27:10.671   928  6047 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 12:27:10.687   928  6048 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-04 12:27:10.687   928  6047 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-04 12:27:10.690   928  6047 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 12:27:10.708   928  6048 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 12:27:10.709   928  6047 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 12:27:10.712   508   925 D CommandListener: Setting iface cfg
11-04 12:27:10.717   928  2937 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 12:27:10.719   928  2937 E native  : do suspend true
11-04 12:27:10.720   928  6047 D DhcpClient: Scheduling renewal in 86399s
,11-04 12:27:10.725   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:10.740   928  2937 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-04 12:27:10.741   928  2937 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 12:27:10.742   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-04 12:27:10.745   928  2937 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 12:27:10.745   928  2941 D ConnectivityService: Adding iface wlan0 to network 102
,11-04 12:27:10.790   928  2941 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-04 12:27:10.790   928  2941 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-04 12:27:10.796   928  2941 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-04 12:27:10.798   928  2941 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-04 12:27:10.799   928  2941 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-04 12:27:10.805   928  2941 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 12:27:10.809   928  2941 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-04 12:27:10.810   928  2941 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-04 12:27:10.810   928  2941 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-04 12:27:10.810   928  2937 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 12:27:10.810   928  2941 D ConnectivityService:    accepting network in place of null
,11-04 12:27:10.810   928  2937 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 12:27:10.810   928  2941 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 12:27:10.822   928  6046 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167972, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 12:27:10.834   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:27:10.857   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 12:27:10.863   928  2941 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-04 12:27:10.863  3723  3869 W QCNEJ   : |CORE| network available: 102
11-04 12:27:10.863   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 12:27:10.864   928  2941 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-04 12:27:10.867   928   945 D Tethering: MasterInitialState.processMessage what=3
11-04 12:27:10.867  3723  3869 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 12:27:10.869  3723  3869 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 12:27:10.869  3723  3869 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 12:27:10.878  3953  3953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 12:27:10.881  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 12:27:10.884  3968  3968 D SystemUpdateService: onCreate
,11-04 12:27:10.888  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 12:27:10.898  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 12:27:10.904  3968  4268 I iu.UploadsManager: num queued entries: 0
,11-04 12:27:10.904  3968  4268 I iu.UploadsManager: num updated entries: 0
,11-04 12:27:10.905  3968  4268 I iu.SyncManager: NEXT; no task
11-04 12:27:10.906  3968  6057 I SystemUpdateService: active receiver: enabled
,11-04 12:27:10.909  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 12:27:10.911  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 12:27:10.912  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 12:27:10.916  5833  5833 D SprintDMHelper: simOperator: 
,11-04 12:27:10.916  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 12:27:10.936   928  6045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 12:27:10.938  3968  6057 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 12:27:10.945  5608  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 12:27:10.947  3968  6057 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 12:27:10.947  3968  6057 I SystemUpdateService: now status is 0 (complete)
11-04 12:27:10.947  3968  6057 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 12:27:10.947  3968  6057 I SystemUpdateService: file has been verified
11-04 12:27:10.947  5608  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 12:27:10.947  3968  6057 I SystemUpdateService: OTA package size = 21989297
11-04 12:27:10.947  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:10.947  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c609fa0 removed from the list
,11-04 12:27:10.947  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 12:27:10.951  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-04 12:27:10.951  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-04 12:27:10.953  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@31b165d Bundle[{}]
11-04 12:27:10.954  5608  5656 I io.jxcore.node.LifeCycleMonitor: start: OK
11-04 12:27:10.954  5608  5656 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-04 12:27:10.954  3968  6057 I SystemUpdateService: showing system update notification
11-04 12:27:10.954  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-04 12:27:10.955  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 12:27:10.955  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-04 12:27:10.955  5608  5656 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 12:27:10.962  5608  5656 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-04 12:27:10.962  5608  5656 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-04 12:27:10.962  5608  5656 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-04 12:27:10.963   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 12:27:10.964  3968  3968 D SystemUpdateService: onDestroy
11-04 12:27:10.964  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 12:27:10.964  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b86e759 added. We now have 3 listener(s)
11-04 12:27:10.966  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:10.966  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:10.966  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:10.966  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:10.966  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac3cf1e added. We now have 4 listener(s)
,11-04 12:27:10.966  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:27:10.970  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 12:27:10.971  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 12:27:10.971  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae83ff added. We now have 4 listener(s)
,11-04 12:27:10.973  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 12:27:10.973  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:10.973  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:10.973  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:10.973  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c015cc added. We now have 5 listener(s)
11-04 12:27:10.973  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 12:27:10.973  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:27:10.974  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:27:10.974  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:27:10.974  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:10.974  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 12:27:10.974  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:10.974  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b86e759 removed from the list
11-04 12:27:10.974  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:10.974  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac3cf1e removed from the list
11-04 12:27:10.974  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:27:10.974  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:10.976  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:10.976  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.976  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.976  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:10.976  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:10.976  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:27:10.976  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac3cf1e not in the list
11-04 12:27:10.977  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:10.978  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:10.978  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.978  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.978  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:10.978  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:10.978  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:10.978  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c015cc removed from the list
,11-04 12:27:10.978  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:10.979  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:10.979  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:10.979  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae83ff removed from the list
,11-04 12:27:10.979  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 12:27:10.980  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@135a015 added. We now have 3 listener(s)
11-04 12:27:10.981  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:10.981  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 12:27:10.981  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:10.981  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:10.981  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd9bf2a added. We now have 4 listener(s)
11-04 12:27:10.981  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:10.981  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 12:27:10.982  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:27:10.982  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c71611b added. We now have 4 listener(s)
11-04 12:27:10.983  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:10.983  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:10.983  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:10.983  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:10.983  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbec2b8 added. We now have 5 listener(s)
11-04 12:27:10.983  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:10.983  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:27:10.983  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 12:27:10.983  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 12:27:10.983  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:27:10.984  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 12:27:10.984  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 12:27:10.986  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 12:27:10.986  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 12:27:10.986  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 12:27:10.988  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:10.988  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 12:27:10.989  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 12:27:10.989  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 12:27:10.989  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 12:27:10.989   928  6045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 11:27:10 GMT], X-Android-Received-Millis=[1478258830988], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478258830959]}
,11-04 12:27:10.990   928  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 12:27:10.990   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-04 12:27:10.990   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 12:27:10.991  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.991  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-04 12:27:10.991   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-04 12:27:10.991  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 12:27:10.991  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 12:27:10.991  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 12:27:10.991  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.991  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:27:10.993  5984  5995 D BtGatt.GattService: registerClient() - UUID=52cf8ca1-1763-4037-9492-a26f127acacc
,11-04 12:27:10.994  5984  6000 D BtGatt.GattService: onClientRegistered() - UUID=52cf8ca1-1763-4037-9492-a26f127acacc, clientIf=5
,11-04 12:27:10.994  5608  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 12:27:10.995  5984  6023 D BtGatt.GattService: start scan with filters
11-04 12:27:10.997  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 12:27:10.997  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:10.997  5984  6003 D BtGatt.ScanManager: handling starting scan
11-04 12:27:10.997  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 12:27:10.997  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.997  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 12:27:10.997  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 12:27:10.998  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:27:10.998  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 12:27:10.998  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 12:27:10.998  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:27:10.998  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 12:27:10.998  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 12:27:10.998  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 12:27:10.998  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:10.998  5984  6003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d67af07
,11-04 12:27:11.000  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.000  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:27:11.000  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.000  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.000  5608  5656 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 12:27:11.000  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 12:27:11.000  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-04 12:27:11.000  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 12:27:11.000  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.000  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.000  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.000  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 12:27:11.002  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.002  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.002  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.002  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.002  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 12:27:11.002  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 12:27:11.002  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:27:11.002  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 12:27:11.003  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.003  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.003  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.003  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 12:27:11.003  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.003  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:27:11.003  5984  6023 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 12:27:11.004  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 12:27:11.004  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:27:11.004  5984  5994 D BtGatt.GattService: stopScan() - queue size =1
11-04 12:27:11.005  5984  6028 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.005  5984  6000 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 12:27:11.005  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.005  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 12:27:11.006  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 12:27:11.006  5984  6003 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 12:27:11.006  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 12:27:11.006  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.007  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.007  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:27:11.007  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.007  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.007  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:27:11.007  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:27:11.007  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 12:27:11.007  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.007  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 12:27:11.007  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 12:27:11.008  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-04 12:27:11.008  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.008  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 12:27:11.008  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.009  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:27:11.009  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:27:11.009  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:27:11.009  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.009  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.009  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.009  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.009  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.009  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.009  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.009  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@135a015 removed from the list
11-04 12:27:11.009  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 12:27:11.009  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:27:11.009  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd9bf2a removed from the list
11-04 12:27:11.009  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:27:11.009  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.011  5984  6000 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 12:27:11.011  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.011  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.011  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.011  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.011  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.011  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.011  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.011  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd9bf2a not in the list
11-04 12:27:11.011  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.011  5984  6003 D BtGatt.ScanManager: Starting BLE batch scan
11-04 12:27:11.011  5984  6003 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 12:27:11.012  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.012  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.012  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.012  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.012  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.012  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.012  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbec2b8 removed from the list
11-04 12:27:11.012  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.012  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.012  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.012  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c71611b removed from the list
11-04 12:27:11.013  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:27:11.013  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89abccd added. We now have 3 listener(s)
11-04 12:27:11.014  5608  5656 D org.thaliproject.p2p.b,tconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:11.014  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:11.014  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:11.014  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:11.014  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f70982 added. We now have 4 listener(s)
11-04 12:27:11.014  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:11.014  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 12:27:11.015  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:27:11.015  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a0d893 added. We now have 4 listener(s)
,11-04 12:27:11.016  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:11.016  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:11.016  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:11.016  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:11.016  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2b30d0 added. We now have 5 listener(s)
11-04 12:27:11.016  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:11.016  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 12:27:11.017  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:27:11.017  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 12:27:11.017  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 12:27:11.017  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:27:11.017  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 12:27:11.018  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 12:27:11.019  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 12:27:11.019  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 12:27:11.019  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 12:27:11.020  5984  6000 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 12:27:11.020  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.021  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.021  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 12:27:11.022  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 12:27:11.022  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 12:27:11.022  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 12:27:11.025  5984  6000 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 12:27:11.025  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.027  5984  6003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:27:11.028  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.028  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 12:27:11.028  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 12:27:11.028  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 12:27:11.028  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 12:27:11.028  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.029  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:27:11.031  5984  6028 D BtGatt.GattService: registerClient() - UUID=5850156f-3ef1-40bc-8985-a30178352782
11-04 12:27:11.031  5984  6000 D BtGatt.GattService: onClientRegistered() - UUID=5850156f-3ef1-40bc-8985-a30178352782, clientIf=5
11-04 12:27:11.031  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 12:27:11.032  5984  5994 D BtGatt.GattService: start scan with filters
11-04 12:27:11.032  5984  6000 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 12:27:11.032  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.033  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 12:27:11.034  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.034  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 12:27:11.034  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.034  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 12:27:11.034  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 12:27:11.034  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.034  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-04 12:27:11.034  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 12:27:11.034  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.034  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.034  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 12:27:11.035  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 12:27:11.035  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.036  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.036  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:27:11.036  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.036  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.036  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:27:11.036  5608  5656 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 12:27:11.036  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.036  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:27:11.036  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 12:27:11.037  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:27:11.037  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.037  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.037  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.037  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.037  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.037  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89abccd removed from the list
11-04 12:27:11.037  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.037  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f70982 removed from the list
11-04 12:27:11.037  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:27:11.037  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 12:27:11.037  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.037  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.037  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 12:27:11.037  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.037  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.037  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.038  5984  6000 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 12:27:11.039  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.039  5984  6003 D BtGatt.ScanManager: stopping BLe Batch
,11-04 12:27:11.040  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 12:27:11.040  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.040  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.040  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.040  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.040  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 12:27:11.042  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.042  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.042  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.043  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.043  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.043  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.043  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f70982 not in the list
11-04 12:27:11.043  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 12:27:11.043  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 12:27:11.043  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 12:27:11.043  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.043  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.043  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.043  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 12:27:11.043  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.043  5984  6000 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 12:27:11.043  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.043  5984  6003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 12:27:11.044  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:27:11.044  5984  5994 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 12:27:11.044  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 12:27:11.044  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:27:11.045  5984  6023 D BtGatt.GattService: stopScan() - queue size =0
,11-04 12:27:11.045  5984  6024 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 12:27:11.045  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 12:27:11.045  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.045  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 12:27:11.045  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.045  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.046  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 12:27:11.046  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 12:27:11.046  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 12:27:11.047  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.047  5984  6000 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 12:27:11.047  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.048  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.048  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 12:27:11.048  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.048  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.048  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.048  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.048  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.048  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2b30d0 removed from the list
,11-04 12:27:11.048  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.049  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.049  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.049  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a0d893 removed from the list
11-04 12:27:11.049  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:27:11.049  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 12:27:11.049  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 12:27:11.049  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.049  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 12:27:11.049  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 12:27:11.049  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.049  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 12:27:11.049  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.049  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fb885 added. We now have 3 listener(s)
11-04 12:27:11.049  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 12:27:11.049  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.049  5984  6003 D BtGatt.ScanManager: handling starting scan
11-04 12:27:11.050  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:11.050  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 12:27:11.050  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:11.050  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:11.050  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37846da added. We now have 4 listener(s)
11-04 12:27:11.050  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:11.050  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.050  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 12:27:11.050  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.050  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.051  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:27:11.051  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 12:27:11.051  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:27:11.051  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@668c70b added. We now have 4 listener(s)
11-04 12:27:11.052  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:11.052  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 12:27:11.052  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:11.052  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:11.052  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c449e8 added. We now have 5 listener(s)
11-04 12:27:11.052  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:11.052  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:27:11.052  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 12:27:11.053  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-04 12:27:11.053  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 12:27:11.053  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 12:27:11.054  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 12:27:11.055  5984  6000 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 12:27:11.055  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.055  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 12:27:11.055  5608  5656 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 12:27:11.055  5984  6003 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 12:27:11.055  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 12:27:11.057  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.057  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 12:27:11.058  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 12:27:11.058  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 12:27:11.058  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 12:27:11.059  5984  6000 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 12:27:11.059  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.060  5984  6003 D BtGatt.ScanManager: Starting BLE batch scan
11-04 12:27:11.060  5984  6003 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 12:27:11.060  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.060  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 12:27:11.060  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 12:27:11.060  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 12:27:11.060  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 12:27:11.060  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.061  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:27:11.062  5984  6023 D BtGatt.GattService: registerClient() - UUID=8d0b5425-bc7c-4952-a3b7-a567e0a20527
,11-04 12:27:11.062  5984  6000 D BtGatt.GattService: onClientRegistered() - UUID=8d0b5425-bc7c-4952-a3b7-a567e0a20527, clientIf=5
,11-04 12:27:11.062  5608  5618 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 12:27:11.063  5984  6028 D BtGatt.GattService: start scan with filters
,11-04 12:27:11.065  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 12:27:11.065  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.065  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 12:27:11.065  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.065  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 12:27:11.065  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 12:27:11.065  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.066  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 12:27:11.066  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 12:27:11.066  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.066  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.066  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 12:27:11.066  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 12:27:11.066  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.068  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.068  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 12:27:11.068  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.068  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.068  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 12:27:11.069  5984  6000 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 12:27:11.069  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.070  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.070  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 12:27:11.070  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:27:11.070  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.070  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:27:11.070  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.070  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:27:11.070  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 12:27:11.070  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.070  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.070  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.070  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.070  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.070  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fb885 removed from the list
,11-04 12:27:11.070  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.070  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37846da removed from the list
11-04 12:27:11.071  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:27:11.071  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.071  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-04 12:27:11.071  5608  5656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.071  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.071  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.072  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.072  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.072  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37846da not in the list
11-04 12:27:11.072  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 12:27:11.072  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 12:27:11.072  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 12:27:11.072  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.072  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.072  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.072  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 12:27:11.072  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.073  5608  5656 D BluetoothAdapter: STATE_ON
,11-04 12:27:11.073  5984  5995 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 12:27:11.073  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 12:27:11.073  5984  6000 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 12:27:11.073  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.073  5608  5656 D BluetoothAdapter: STATE_ON
11-04 12:27:11.074  5984  6028 D BtGatt.GattService: stopScan() - queue size =1
11-04 12:27:11.074  5984  5994 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 12:27:11.074  5984  6003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 12:27:11.074  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 12:27:11.074  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.074  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 12:27:11.074  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.074  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-04 12:27:11.075  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 12:27:11.075  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 12:27:11.075  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.078  5984  6000 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 12:27:11.078  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.078  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.078  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:27:11.078  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.078  5984  6000 E BtGatt.ContextMap: Context not found for ID 5
,11-04 12:27:11.078  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.078  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.078  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.078  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.078  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c449e8 removed from the list
11-04 12:27:11.078  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 12:27:11.078  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.078  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.078  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 12:27:11.078  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.078  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 12:27:11.078  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@668c70b removed from the list
11-04 12:27:11.078  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.078  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 12:27:11.078  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 12:27:11.078  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.078  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.079  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 12:27:11.079  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 12:27:11.079  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@821733d added. We now have 3 listener(s)
11-04 12:27:11.079  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.079  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.079  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.079  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:11.079  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.079  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:11.079  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 12:27:11.080  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 12:27:11.080  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 12:27:11.080  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:11.080  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588d732 added. We now have 4 listener(s)
11-04 12:27:11.080  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:11.080  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 12:27:11.081  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 12:27:11.081  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f810c83 added. We now have 4 listener(s)
11-04 12:27:11.081  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 12:27:11.081  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 12:27:11.081  5608  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 12:27:11.081  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 12:27:11.081  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c146e00 added. We now have 5 listener(s)
,11-04 12:27:11.082  5608  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 12:27:11.082  5608  5656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 12:27:11.082  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:27:11.082  5608  5656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 12:27:11.082  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 12:27:11.082  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.082  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.082  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@821733d removed from the list
11-04 12:27:11.082  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.082  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588d732 removed from the list
,11-04 12:27:11.082  5608  5656 D io.jxcore.node.ConnectivityMonitor: stop
11-04 12:27:11.082  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.083  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.083  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.083  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.083  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.083  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.083  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.083  5608  5656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588d732 not in the list
11-04 12:27:11.083  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 12:27:11.084  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.084  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.084  5608  5656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 12:27:11.084  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 12:27:11.084  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 12:27:11.084  5984  6000 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 12:27:11.084  5608  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 12:27:11.084  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.084  5608  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c146e00 removed from the list
11-04 12:27:11.084  5608  5656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 12:27:11.084  5608  5656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 12:27:11.084  5984  6003 D BtGatt.ScanManager: stopping BLe Batch
11-04 12:27:11.084  5608  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 12:27:11.084  5608  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f810c83 removed from the list
11-04 12:27:11.084  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 12:27:11.084  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 12:27:11.084  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 12:27:11.085  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:27:11.085  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-04 12:27:11.085  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-04 12:27:11.088  5984  6000 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 12:27:11.088  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.088  5984  6003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:27:11.092  5984  6000 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 12:27:11.092  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.094  5984  6003 D BtGatt.ScanManager: handling starting scan
,11-04 12:27:11.098  5984  6000 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 12:27:11.098  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.098  5984  6003 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 12:27:11.102  5984  6000 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 12:27:11.102  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.102  5984  6003 D BtGatt.ScanManager: Starting BLE batch scan
11-04 12:27:11.102  5984  6003 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 12:27:11.109  5984  6000 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 12:27:11.109  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.113  5984  6000 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 12:27:11.113  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.114  5984  6003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:27:11.119  5984  6000 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 12:27:11.119  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.119  5984  6000 E BtGatt.ContextMap: Context not found for ID 5
,11-04 12:27:11.124  5984  6000 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 12:27:11.124  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.124  5984  6003 D BtGatt.ScanManager: stopping BLe Batch
,11-04 12:27:11.128  5984  6000 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 12:27:11.128  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 12:27:11.128  5984  6003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 12:27:11.132  5984  6000 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 12:27:11.132  5984  6000 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 12:27:11.510  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 12:27:11.552  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 12:27:11.580  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 12:27:11.726   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-04 12:27:13.181  5608  6065 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 12:27:13.181  5608  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:14.026  5608  6065 W !!      : call onHalfStreamCopied
,11-04 12:27:14.026  5608  6065 I testCopyDataAndClose: closing input stream
,11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 12:27:14.805  5608  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 12:27:18.818   928  2941 D ConnectivityService: handlePromptUnvalidated 102
,11-04 12:27:19.341  5608  6066 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:19.341  5608  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:21.341  5608  5656 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-04 12:27:21.341  5608  5656 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:21.341  5608  5656 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-04 12:27:21.481  5608  6067 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 12:27:21.481  5608  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:21.534  5608  6066 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-04 12:27:21.534  5608  6066 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:21.534  5608  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 12:27:23.090  5608  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 12:27:27.498  5608  6069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:27.498  5608  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 12:27:27.499  5608  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 12:27:27.500  5608  6069 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 12:27:27.500  5608  6069 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-04 12:27:27.500  5608  6069 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:27.500  5608  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-04 12:27:27.502  5608  5656 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-04 12:27:27.505  5608  6070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:27.505  5608  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 12:27:27.506  5608  6070 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-04 12:27:27.507  5608  6070 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:27.507  5608  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 12:27:27.507  5608  6070 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 12:27:27.507  5608  6070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 12:27:27.507  5608  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 12:27:27.512  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-04 12:27:27.512  5608  5656 I jxcore-log: 
,11-04 12:27:27.513  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-04 12:27:27.513  5608  5656 I jxcore-log: 
11-04 12:27:27.513  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-04 12:27:27.513  5608  5656 I jxcore-log: 
,11-04 12:27:27.513  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-04 12:27:27.513  5608  5656 I jxcore-log: 
11-04 12:27:27.514  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'Total duration:  92101'
11-04 12:27:27.514  5608  5656 I jxcore-log: 
,11-04 12:27:27.516  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 12:27:27.516  5608  5656 I jxcore-log: 
,11-04 12:27:27.520  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.520  5608  5656 I jxcore-log: 
11-04 12:27:27.521  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.521  5608  5656 I jxcore-log: 
,11-04 12:27:27.521  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 12:27:27.521  5608  5656 I jxcore-log: 
11-04 12:27:27.522  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 12:27:27.522  5608  5656 I jxcore-log: 
,11-04 12:27:27.522  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.522  5608  5656 I jxcore-log: 
11-04 12:27:27.522  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 12:27:27.522  5608  5656 I jxcore-log: 
11-04 12:27:27.523  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.523  5608  5656 I jxcore-log: 
11-04 12:27:27.523  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.523  5608  5656 I jxcore-log: 
11-04 12:27:27.523  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.523  5608  5656 I jxcore-log: 
11-04 12:27:27.524  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 12:27:27.524  5608  5656 I jxcore-log: 
11-04 12:27:27.524  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 12:27:27.524  5608  5656 I jxcore-log: 
11-04 12:27:27.524  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.524  5608  5656 I jxcore-log: 
11-04 12:27:27.524  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 12:27:27.524  5608  5656 I jxcore-log: 
11-04 12:27:27.525  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.525  5608  5656 I jxcore-log: 
11-04 12:27:27.525  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 12:27:27.525  5608  5656 I jxcore-log: 
11-04 12:27:27.525  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.525  5608  5656 I jxcore-log: 
,11-04 12:27:27.525  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 12:27:27.525  5608  5656 I jxcore-log: 
11-04 12:27:27.525  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.525  5608  5656 I jxcore-log: 
11-04 12:27:27.526  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 12:27:27.526  5608  5656 I jxcore-log: 
11-04 12:27:27.526  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 12:27:27.526  5608  5656 I jxcore-log: 
11-04 12:27:27.526  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.526  5608  5656 I jxcore-log: 
11-04 12:27:27.527  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 12:27:27.527  5608  5656 I jxcore-log: 
,11-04 12:27:27.527  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 12:27:27.527  5608  5656 I jxcore-log: 
11-04 12:27:27.527  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 12:27:27.527  5608  5656 I jxcore-log: 
,11-04 12:27:27.529  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 12:27:27.529  5608  5656 I jxcore-log: 
,11-04 12:27:27.530  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 12:27:27.530  5608  5656 I jxcore-log: 
11-04 12:27:27.530  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 12:27:27.530  5608  5656 I jxcore-log: 
11-04 12:27:27.530  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 12:27:27.530  5608  5656 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-04 12:27:27.530  5608  5656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 12:27:27.531  5608  5656 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-04 12:27:27.531  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 12:27:27.531  5608  5656 I jxcore-log: 
11-04 12:27:27.531  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.531  5608  5656 I jxcore-log: 
11-04 12:27:27.531  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 12:27:27.531  5608  5656 I jxcore-log: 
11-04 12:27:27.531  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.531  5608  5656 I jxcore-log: 
11-04 12:27:27.532  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 12:27:27.532  5608  5656 I jxcore-log: 
11-04 12:27:27.532  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 12:27:27.532  5608  5656 I jxcore-log: 
,11-04 12:27:27.538  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 12:27:27.538  5608  5656 I jxcore-log: 
,11-04 12:27:27.538  5608  5656 I jxcore-log: 2016-11-04 11:27:27 - WARN testUtils: 'myNameCallback not set!'
11-04 12:27:27.538  5608  5656 I jxcore-log: 
,11-04 12:27:27.543  5608  5608 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-04 12:27:29.612  5608  5656 I jxcore-log: 2016-11-04 11:27:29 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-04 12:27:29.612  5608  5656 I jxcore-log: 
,11-04 12:27:29.614  5608  5656 I jxcore-log: 2016-11-04 11:27:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 12:27:29.614  5608  5656 I jxcore-log: 
,11-04 12:27:29.958  5608  5656 I jxcore-log: 2016-11-04 11:27:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 12:27:29.958  5608  5656 I jxcore-log: 
,11-04 12:27:29.970  5608  5656 I jxcore-log: 2016-11-04 11:27:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 12:27:29.970  5608  5656 I jxcore-log: 
,11-04 12:27:31.095  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 12:27:31.095  5608  5656 I jxcore-log: 
,11-04 12:27:31.284  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 12:27:31.284  5608  5656 I jxcore-log: 
,11-04 12:27:31.289  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 12:27:31.289  5608  5656 I jxcore-log: 
,11-04 12:27:31.294  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 12:27:31.294  5608  5656 I jxcore-log: 
,11-04 12:27:31.727   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:31.770  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 12:27:31.770  5608  5656 I jxcore-log: 
,11-04 12:27:31.815  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 12:27:31.815  5608  5656 I jxcore-log: 
,11-04 12:27:31.828  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 12:27:31.828  5608  5656 I jxcore-log: 
,11-04 12:27:31.832  5608  5656 I jxcore-log: 2016-11-04 11:27:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 12:27:31.832  5608  5656 I jxcore-log: 
,11-04 12:27:32.101  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 12:27:32.101  5608  5656 I jxcore-log: 
,11-04 12:27:32.229  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 12:27:32.229  5608  5656 I jxcore-log: 
,11-04 12:27:32.605  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 12:27:32.605  5608  5656 I jxcore-log: 
,11-04 12:27:32.614  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 12:27:32.614  5608  5656 I jxcore-log: 
,11-04 12:27:32.618  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 12:27:32.618  5608  5656 I jxcore-log: 
,11-04 12:27:32.623  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 12:27:32.623  5608  5656 I jxcore-log: 
,11-04 12:27:32.628  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 12:27:32.628  5608  5656 I jxcore-log: 
,11-04 12:27:32.656  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 12:27:32.656  5608  5656 I jxcore-log: 
,11-04 12:27:32.692  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 12:27:32.692  5608  5656 I jxcore-log: 
,11-04 12:27:32.699  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 12:27:32.699  5608  5656 I jxcore-log: 
,11-04 12:27:32.706  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 12:27:32.706  5608  5656 I jxcore-log: 
,11-04 12:27:32.721  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 12:27:32.721  5608  5656 I jxcore-log: 
,11-04 12:27:32.725  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 12:27:32.725  5608  5656 I jxcore-log: 
,11-04 12:27:32.728   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:32.731  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 12:27:32.731  5608  5656 I jxcore-log: 
,11-04 12:27:32.736  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 12:27:32.736  5608  5656 I jxcore-log: 
,11-04 12:27:32.749  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 12:27:32.749  5608  5656 I jxcore-log: 
,11-04 12:27:32.766  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 12:27:32.766  5608  5656 I jxcore-log: 
,11-04 12:27:32.781  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 12:27:32.781  5608  5656 I jxcore-log: 
,11-04 12:27:32.792  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 12:27:32.792  5608  5656 I jxcore-log: 
,11-04 12:27:32.815  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 12:27:32.815  5608  5656 I jxcore-log: 
,11-04 12:27:32.826  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 12:27:32.826  5608  5656 I jxcore-log: 
,11-04 12:27:32.839  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 12:27:32.839  5608  5656 I jxcore-log: 
,11-04 12:27:32.849  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 12:27:32.849  5608  5656 I jxcore-log: 
,11-04 12:27:32.856  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 12:27:32.856  5608  5656 I jxcore-log: 
,11-04 12:27:32.878  5608  5656 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 12:27:32.879  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 12:27:32.879  5608  5656 I jxcore-log: 
,11-04 12:27:32.956  5608  5656 I jxcore-log: 2016-11-04 11:27:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:32.956  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:32.956  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:32.956  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:32.956  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:32.956  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:32.956  5608  5656 I jxcore-log: 
,11-04 12:27:33.303  5608  5656 I jxcore-log: 2016-11-04 11:27:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:33.303  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:33.303  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:33.303  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:33.303  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:33.303  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:33.303  5608  5656 I jxcore-log: 
,11-04 12:27:33.308  5608  5656 I jxcore-log: 2016-11-04 11:27:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:33.308  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:33.308  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:33.308  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:33.308  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:33.308  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:33.308  5608  5656 I jxcore-log: 
,11-04 12:27:33.729   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:33.857  5608  5656 I jxcore-log: 2016-11-04 11:27:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:33.857  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:33.857  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:33.857  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:33.857  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:33.857  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:33.857  5608  5656 I jxcore-log: 
,11-04 12:27:33.860  5608  5656 I jxcore-log: 2016-11-04 11:27:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:33.860  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:33.860  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:33.860  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:33.860  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:33.860  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:33.860  5608  5656 I jxcore-log: 
,11-04 12:27:34.731   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:34.895  5608  5656 I jxcore-log: 2016-11-04 11:27:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:34.895  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:34.895  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:34.895  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:34.895  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:34.895  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:34.895  5608  5656 I jxcore-log: 
,11-04 12:27:34.897  5608  5656 I jxcore-log: 2016-11-04 11:27:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:34.897  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:34.897  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:34.897  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:34.897  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:34.897  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:34.897  5608  5656 I jxcore-log: 
,11-04 12:27:35.732   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 12:27:35.933  5608  5656 I jxcore-log: 2016-11-04 11:27:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:35.933  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:35.933  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:35.933  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:35.933  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:35.933  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:35.933  5608  5656 I jxcore-log: 
,11-04 12:27:35.937  5608  5656 I jxcore-log: 2016-11-04 11:27:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:35.937  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:35.937  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:35.937  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:35.937  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:35.937  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:35.937  5608  5656 I jxcore-log: 
,11-04 12:27:36.732   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 12:27:36.972  5608  5656 I jxcore-log: 2016-11-04 11:27:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:36.972  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:36.972  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:36.972  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:36.972  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:36.972  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:36.972  5608  5656 I jxcore-log: 
,11-04 12:27:36.974  5608  5656 I jxcore-log: 2016-11-04 11:27:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:36.974  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:36.974  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:36.974  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:36.974  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:36.974  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:36.974  5608  5656 I jxcore-log: 
,11-04 12:27:38.006  5608  5656 I jxcore-log: 2016-11-04 11:27:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:38.006  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:38.006  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:38.006  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:38.006  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:38.006  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:38.006  5608  5656 I jxcore-log: 
,11-04 12:27:38.010  5608  5656 I jxcore-log: 2016-11-04 11:27:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:38.010  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:38.010  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:38.010  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:38.010  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:38.010  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:38.010  5608  5656 I jxcore-log: 
,11-04 12:27:39.056  5608  5656 I jxcore-log: 2016-11-04 11:27:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:39.056  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:39.056  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:39.056  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:39.056  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:39.056  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:39.056  5608  5656 I jxcore-log: 
,11-04 12:27:39.060  5608  5656 I jxcore-log: 2016-11-04 11:27:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:39.060  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:39.060  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:39.060  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:39.060  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:39.060  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:39.060  5608  5656 I jxcore-log: 
,11-04 12:27:40.093  5608  5656 I jxcore-log: 2016-11-04 11:27:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:40.093  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:40.093  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:40.093  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:40.093  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:40.093  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:40.093  5608  5656 I jxcore-log: 
,11-04 12:27:40.096  5608  5656 I jxcore-log: 2016-11-04 11:27:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:40.096  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:40.096  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:40.096  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:40.096  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:40.096  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:40.096  5608  5656 I jxcore-log: 
,11-04 12:27:41.134  5608  5656 I jxcore-log: 2016-11-04 11:27:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:41.134  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:41.134  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:41.134  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:41.134  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:41.134  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:41.134  5608  5656 I jxcore-log: 
,11-04 12:27:41.140  5608  5656 I jxcore-log: 2016-11-04 11:27:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:41.140  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:41.140  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:41.140  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:41.140  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:41.140  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:41.140  5608  5656 I jxcore-log: 
,11-04 12:27:42.210  5608  5656 I jxcore-log: 2016-11-04 11:27:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:42.210  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:42.210  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:42.210  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:42.210  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:42.210  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:42.210  5608  5656 I jxcore-log: 
,11-04 12:27:42.215  5608  5656 I jxcore-log: 2016-11-04 11:27:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:42.215  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:42.215  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:42.215  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:42.215  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:42.215  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:42.215  5608  5656 I jxcore-log: 
,11-04 12:27:43.273  5608  5656 I jxcore-log: 2016-11-04 11:27:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:43.273  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:43.273  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:43.273  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:43.273  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:43.273  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:43.273  5608  5656 I jxcore-log: 
,11-04 12:27:43.278  5608  5656 I jxcore-log: 2016-11-04 11:27:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:43.278  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:43.278  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:43.278  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:43.278  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:43.278  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:43.278  5608  5656 I jxcore-log: 
,11-04 12:27:44.309  5608  5656 I jxcore-log: 2016-11-04 11:27:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:44.309  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:44.309  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:44.309  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:44.309  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:44.309  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:44.309  5608  5656 I jxcore-log: 
,11-04 12:27:44.312  5608  5656 I jxcore-log: 2016-11-04 11:27:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:44.312  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:44.312  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:44.312  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:44.312  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:44.312  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:44.312  5608  5656 I jxcore-log: 
,11-04 12:27:45.350  5608  5656 I jxcore-log: 2016-11-04 11:27:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:45.350  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:45.350  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:45.350  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:45.350  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:45.350  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:45.350  5608  5656 I jxcore-log: 
,11-04 12:27:45.354  5608  5656 I jxcore-log: 2016-11-04 11:27:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:45.354  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:45.354  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:45.354  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:45.354  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:45.354  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:45.354  5608  5656 I jxcore-log: 
,11-04 12:27:46.384  5608  5656 I jxcore-log: 2016-11-04 11:27:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:46.384  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:46.384  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:46.384  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:46.384  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:46.384  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:46.384  5608  5656 I jxcore-log: 
,11-04 12:27:46.387  5608  5656 I jxcore-log: 2016-11-04 11:27:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:46.387  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:46.387  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:46.387  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:46.387  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:46.387  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:46.387  5608  5656 I jxcore-log: 
,11-04 12:27:47.423  5608  5656 I jxcore-log: 2016-11-04 11:27:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 12:27:47.423  5608  5656 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 12:27:47.423  5608  5656 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 12:27:47.423  5608  5656 I jxcore-log: emit@events.js:82:1
11-04 12:27:47.423  5608  5656 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 12:27:47.423  5608  5656 I jxcore-log: emit@events.js:82:1'
11-04 12:27:47.423  5608  5656 I jxcore-log: 
,11-04 12:27:47.434  5608  5656 E jxcore  : Error!: error is undefined
11-04 12:27:47.434  5608  5656 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 12:27:47.438  5608  5656 I jxcore-log: 2016-11-04 11:27:47 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 12:27:47.438  5608  5656 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-04 12:27:47.438  5608  5656 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 12:27:47.438  5608  5656 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 12:27:47.438  5608  5656 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 12:27:47.438  5608  5656 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 12:27:47.438  5608  5656 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 12:27:47.438  5608  5656 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 12:27:47.441  5608  5656 I jxcore-log: 2016-11-04 11:27:47 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 12:27:47.441  5608  5656 I jxcore-log: 
11-04 12:27:47.442  5608  5656 E jxcore-log: TypeError: 
11-04 12:27:47.442  5608  5656 E jxcore-log: error is undefined
11-04 12:27:47.442  5608  5656 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-04 12:27:47.442  5608  5656 E jxcore-log: 
,11-04 12:27:47.531   928  3798 I WindowState: WIN DEATH: Window{4462af u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 12:27:47.532   928  2938 D WifiService: Client connection lost with reason: 4
11-04 12:27:47.533   928  3144 D GraphicsStats: Buffer count: 2
,11-04 12:27:47.548   928  3141 I ActivityManager: Process com.test.thalitest (pid 5608) has died
,11-04 12:27:47.544   528   528 I Zygote  : Process 5608 exited cleanly (139)
,11-04 12:27:47.559   928  3141 I ActivityManager: Start proc 6073:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 12:27:47.640  6073  6073 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 12:27:47.658  6073  6073 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 12:27:47.662  6073  6073 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 4811-4812)
11-04 12:27:47.662  6073  6073 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 12:27:47.671  6073  6073 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5d2326e}
11-04 12:27:47.671  6073  6073 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 12:27:47.672  6073  6073 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 12:27:47.675  6073  6073 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 12:27:47.675  6073  6073 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 12:27:47.685  6073  6073 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 12:27:47.692  6073  6073 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 12:27:47.692  6073  6073 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 12:27:47.693  6073  6073 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 12:27:47.693  6073  6073 I Adreno  : Build Date                       : 12/06/15
11-04 12:27:47.693  6073  6073 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 12:27:47.693  6073  6073 I Adreno  : Local Branch                     : mybranch17112971
11-04 12:27:47.693  6073  6073 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 12:27:47.693  6073  6073 I Adreno  : Remote Branch                    : NONE
11-04 12:27:47.693  6073  6073 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 12:27:47.723   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e76c2a3:true
,11-04 12:27:47.736   952   952 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[29281]" dev="sockfs" ino=29281 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 12:27:47.736   952   952 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[29281]" dev="sockfs" ino=29281 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.748  6073  6073 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 12:27:47.756  6073  6073 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 12:27:47.789   951   951 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34614]" dev="sockfs" ino=34614 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.791  6073  6109 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-04 12:27:47.789   951   951 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34614]" dev="sockfs" ino=34614 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.792  3406  3406 W Binder_6: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[29293]" dev="sockfs" ino=29293 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.792  3406  3406 W Binder_6: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[29293]" dev="sockfs" ino=29293 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.797  6073  6096 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 12:27:47.834  6073  6109 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 12:27:47.862  3605  3605 W Binder_7: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[35163]" dev="sockfs" ino=35163 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.863   928  3605 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5608 uid 10077
,11-04 12:27:47.862  3605  3605 W Binder_7: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[35163]" dev="sockfs" ino=35163 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.867  3639  3639 I Keyboard.Facilitator: onFinishInput()
,11-04 12:27:47.862  3405  3405 W Binder_5: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[35162]" dev="sockfs" ino=35162 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.862  3405  3405 W Binder_5: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[35162]" dev="sockfs" ino=35162 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 12:27:47.897   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +315ms (total +346ms)
,11-04 12:27:47.898  6073  6073 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6073
,11-04 12:27:47.908  6071  6071 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 12:27:47.920  6071  6071 D AndroidRuntime: CheckJNI is OFF
,11-04 12:27:47.944  6071  6071 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 12:27:47.968  6071  6071 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 12:27:47.978  6073  6073 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 12:27:47.983  6071  6071 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 12:27:47.988   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-04 12:27:47.989   928   941 I ActivityManager: Killing 6073:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 12:27:48.021   928  3141 D GraphicsStats: Buffer count: 2
,11-04 12:27:48.023   928  3795 I WindowState: WIN DEATH: Window{c4d65ce u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 12:27:48.096   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-04 12:27:48.096   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-04 12:27:48.098   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-04 12:27:48.098   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 12:27:48.098   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:27:48.098   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:27:48.098   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 12:27:48.098   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 12:27:48.099   928   941 I ActivityManager:   Force finishing activity ActivityRecord{c7246c4 u0 com.test.thalitest/.MainActivity t68}
,11-04 12:27:48.099   928   953 I art     : Starting a blocking GC Explicit
11-04 12:27:48.109   928  3406 W ActivityManager: Spurious death for ProcessRecord{734c3fc 0:com.test.thalitest/u0a77}, curProc for 6073: null
,11-04 12:27:48.195   928   953 I art     : Explicit concurrent mark sweep GC freed 48262(2MB) AllocSpace objects, 20(400KB) LOS objects, 33% free, 29MB/43MB, paused 1.977ms total 95.346ms
,11-04 12:27:48.217   928   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 12:27:48.220  6071  6071 I art     : System.exit called, status: 0
,11-04 12:27:48.220  6071  6071 I AndroidRuntime: VM exiting with result code 0.
,11-04 12:27:48.236   928   953 I ActivityManager: Start proc 6123:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-04 12:27:48.236   928   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 12:27:48.242   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-04 12:27:48.246  5984  5984 D BluetoothMapAppObserver: onReceive
,11-04 12:27:48.246  5984  5984 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 12:27:48.248  3704  4095 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-04 12:27:48.253  3639  3639 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 12:27:48.268   928  2929 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-04 12:27:48.274  3639  6135 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 12:27:48.281   928   941 I ActivityManager: Start proc 6136:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,11-04 12:27:48.299  3639  6135 I Decoder : createOrResetDecoder
,11-04 12:27:48.317  3768  3768 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-04 12:27:48.332    29    29 W kworker/3:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 12:27:48.342   928  3812 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6073 uid 10077
,11-04 12:27:48.339    29    29 W kworker/3:1: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 12:27:48.342  3573  3573 I ConfigService: onCreate
11-04 12:27:48.343  3639  3639 I Keyboard.Facilitator: onFinishInput()
11-04 12:27:48.339  3812  3812 W Binder_A: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[25373]" dev="sockfs" ino=25373 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 12:27:48.339  3812  3812 W Binder_A: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[25373]" dev="sockfs" ino=25373 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 12:27:48.344   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 12:27:48.349    29    29 W kworker/3:1: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 12:27:48.354  3802  3894 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-04 12:27:48.354   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-04 12:27:48.355   928   940 E PackageManager: Failed to write settings, restoring backup
11-04 12:27:48.355   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-04 12:27:48.355   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-04 12:27:48.355   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-04 12:27:48.355   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-04 12:27:48.355   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-04 12:27:48.355   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 12:27:48.355   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:27:48.355   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-04 12:27:48.358   928   941 E DropBoxManagerService: Can't write: system_server_wtf
11-04 12:27:48.358   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 12:27:48.358   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 12:27:48.358   928   941 E DropBoxManagerService: 	... 13 more
,11-04 12:27:48.362  3639  6135 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-04 12:27:48.369   928  3795 I ActivityManager: Start proc 6152:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-04 12:27:48.370  3802  3894 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-04 12:27:48.370  3802  3894 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3802
11-04 12:27:48.370  3802  3894 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 12:27:48.370  3802  3894 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 12:27:48.374   928  3605 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-04 12:27:48.375   928  6157 E DropBoxManagerService: Can't write: system_app_crash
11-04 12:27:48.375   928  6157 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 12:27:48.375   928  6157 E DropBoxManagerService: 	... 5 more
,11-04 12:27:48.378  3802  3894 I Process : Sending signal. PID: 3802 SIG: 9
11-04 12:27:48.392  6136  6136 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,11-04 12:27:48.428  3639  6135 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-04 12:27:48.430  3639  6135 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-04 12:27:48.430  3639  6135 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts

```
