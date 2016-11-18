#### Test 921522864f1c710_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 14:30:44.510  3886  4157 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-18 14:30:44.513   550   550 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
11-18 14:30:44.614  3886  4157 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-18 14:30:44.919  5442  5442 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 14:30:44.925  5442  5442 D AndroidRuntime: CheckJNI is OFF
11-18 14:30:44.949  5442  5442 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 14:30:44.981  5442  5442 I Radio-JNI: register_android_hardware_Radio DONE
11-18 14:30:44.996  5442  5442 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 14:30:45.000   930  5337 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 14:30:45.015  5442  5442 D AndroidRuntime: Shutting down VM
11-18 14:30:45.027  3872  5440 W SearchService: Abort, client detached.
11-18 14:30:45.034  3872  3872 I HotwordDetector: Closing mic
11-18 14:30:45.034  3872  4108 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3449619
11-18 14:30:45.034  3872  4137 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 14:30:45.079   930   940 I ActivityManager: Start proc 5451:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 14:30:45.113   513  4143 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-18 14:30:45.114   513  4143 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-18 14:30:45.119   513  4143 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 14:30:45.119   513  4143 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 14:30:45.119   513  2928 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 14:30:45.121  3872  4109 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 14:30:45.123  3872  4136 I MicroRecognitionRnrImpl: Detection finished
11-18 14:30:45.172  5451  5451 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-18 14:30:45.194  5451  5451 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-18 14:30:45.238  5451  5451 I LibraryLoader: Time to load native libraries: 40 ms (timestamps 4896-4936)
,11-18 14:30:45.239  5451  5451 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 14:30:45.271  5451  5451 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ebabb2e}
,11-18 14:30:45.271  5451  5451 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-18 14:30:45.272  5451  5451 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-18 14:30:45.277  5451  5451 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 14:30:45.278  5451  5451 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 14:30:45.310  5451  5451 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 14:30:45.324  5451  5451 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 14:30:45.324  5451  5451 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 14:30:45.324  5451  5451 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 14:30:45.324  5451  5451 I Adreno  : Build Date                       : 12/06/15
11-18 14:30:45.324  5451  5451 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 14:30:45.324  5451  5451 I Adreno  : Local Branch                     : mybranch17112971
11-18 14:30:45.324  5451  5451 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 14:30:45.324  5451  5451 I Adreno  : Remote Branch                    : NONE
11-18 14:30:45.324  5451  5451 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 14:30:45.373   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69522ca:true
,11-18 14:30:45.404   785   785 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30938]" dev="sockfs" ino=30938 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 14:30:45.404   785   785 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30938]" dev="sockfs" ino=30938 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 14:30:45.417  5451  5451 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 14:30:45.425  5451  5451 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 14:30:45.447   400   400 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33017]" dev="sockfs" ino=33017 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 14:30:45.447   400   400 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33017]" dev="sockfs" ino=33017 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 14:30:45.450  5451  5489 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-18 14:30:45.450  3332  3332 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32418]" dev="sockfs" ino=32418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 14:30:45.454  3332  3332 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32418]" dev="sockfs" ino=32418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 14:30:45.456  5451  5476 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 14:30:45.489  5451  5489 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 14:30:45.564  3116  3116 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[27567]" dev="sockfs" ino=27567 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 14:30:45.571   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +512ms
11-18 14:30:45.570  3582  3582 I Keyboard.Facilitator: onFinishInput()
,11-18 14:30:45.601  5451  5451 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5451
,11-18 14:30:45.695  5451  5451 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 14:30:45.841  5451  5492 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -576976592
,11-18 14:30:45.847  5451  5492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 14:30:45.847  5451  5492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 14:30:45.847  5451  5492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 14:30:45.847  5451  5492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 14:30:45.847  5451  5492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-18 14:30:45.847  5451  5492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ae8fdd added. We now have 1 listener(s)
,11-18 14:30:45.849  5451  5492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-18 14:30:45.849  5451  5492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:30:45.850  5451  5492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 14:30:45.850  5451  5492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-18 14:30:45.852  5451  5492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff2b20 added. We now have 1 listener(s)
,11-18 14:30:45.852  5451  5492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 14:30:45.858   930  2897 D WifiService: New client listening to asynchronous messages
,11-18 14:30:45.858  5451  5492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 14:30:45.858  5451  5492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-18 14:30:45.859  5451  5492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-18 14:30:45.859  5451  5492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-18 14:30:45.859  5451  5492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-18 14:30:45.859  5451  5492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 14:30:45.859  5451  5492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-18 14:30:45.860  5451  5492 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 14:30:45.970  5451  5451 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 14:30:46.150  5451  5460 I art     : Background sticky concurrent mark sweep GC freed 85973(8MB) AllocSpace objects, 16(1476KB) LOS objects, 21% free, 25MB/32MB, paused 1.649ms total 102.123ms
,11-18 14:30:46.360  5451  5499 W jxcore-log: Initializing JXcore engine
11-18 14:30:46.361  5451  5499 W jxcore-log: JXcore engine is ready
,11-18 14:30:46.384  5499  5499 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10808 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 14:30:46.384  5499  5499 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[15433]" dev="sockfs" ino=15433 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 14:30:46.384  5499  5499 W Thread-58: type=1400 audit(0.0:113): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-18 14:30:46.384  5499  5499 W Thread-58: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30148]" dev="sockfs" ino=30148 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 14:30:46.392  5451  5499 W jxcore-log: Starting JXcore engine
,11-18 14:30:46.442  5451  5499 W jxcore-log: Platform android
11-18 14:30:46.442  5451  5499 W jxcore-log: 
,11-18 14:30:46.442  5451  5499 W jxcore-log: Process ARCH arm
11-18 14:30:46.442  5451  5499 W jxcore-log: 
,11-18 14:30:46.587  5451  5499 I jxcore-log: JXcore Cordova bridge is ready!
11-18 14:30:46.587  5451  5499 I jxcore-log: 
,11-18 14:30:46.587  5451  5499 W jxcore-log: JXcore engine is started
,11-18 14:30:46.600  5451  5492 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 14:30:46.607  5451  5451 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 14:30:48.035   930   940 I ActivityManager: Killing 4924:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-18 14:30:48.625   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 14:30:48.664  3504  3504 I ConfigService: onDestroy
,11-18 14:30:50.036   930  3029 I ActivityManager: Killing 5074:org.codeaurora.ims/1001 (adj 15): empty #17
,11-18 14:30:51.648   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 14:30:55.173  3872  5502 W CronetSyncConnectionRcs: Upload content type not set.
,11-18 14:30:56.405  5451  5499 I jxcore-log: 2016-11-18 13:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 14:30:56.405  5451  5499 I jxcore-log: 
,11-18 14:30:56.407  5451  5499 I jxcore-log: 2016-11-18 13:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 14:30:56.407  5451  5499 I jxcore-log: 
11-18 14:30:56.408  5451  5499 I jxcore-log: 2016-11-18 13:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-18 14:30:56.408  5451  5499 I jxcore-log: 
,11-18 14:30:56.413  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 14:30:56.413  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 14:30:56.414  5451  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 14:30:56.417  5451  5499 I jxcore-log: 2016-11-18 13:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 14:30:56.417  5451  5499 I jxcore-log: 
11-18 14:30:56.419  5451  5499 I jxcore-log: 2016-11-18 13:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 14:30:56.419  5451  5499 I jxcore-log: 
,11-18 14:30:56.680  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 14:30:56.680  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8e315b added. We now have 2 listener(s)
,11-18 14:30:56.680  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:30:56.681  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 14:30:56.681  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 14:30:56.681  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 14:30:56.681  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f6edf8 added. We now have 2 listener(s)
11-18 14:30:56.681  5451  5499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 14:30:56.682  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 14:30:56.683  5451  5499 D ExecuteNativeTests: Running unit tests
11-18 14:30:56.683  5451  5499 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 14:30:56.684   930   940 D WifiService: setWifiEnabled: true pid=5451, uid=10077
,11-18 14:30:56.684   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 14:30:58.322  4624  4659 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-18 14:30:58.324  4624  4624 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-18 14:31:01.625   930  2896 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 14:31:04.515   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:05.516   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:06.518   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:06.689  5451  5499 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 14:31:06.797  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 14:31:06.797  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fab335 added. We now have 3 listener(s)
,11-18 14:31:06.798  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:06.798  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 14:31:06.798  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 14:31:06.798  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 14:31:06.798  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@756a3ca added. We now have 3 listener(s)
11-18 14:31:06.798  5451  5499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 14:31:06.799  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 14:31:06.802  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-18 14:31:06.802  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 14:31:06.802  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 14:31:06.802  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 14:31:06.802  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 14:31:06.803  5451  5499 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-18 14:31:06.803  5451  5499 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 14:31:06.803  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 14:31:06.803  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 14:31:06.803  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 14:31:06.803  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 14:31:06.804  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-18 14:31:06.804  5451  5499 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-18 14:31:06.805  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-18 14:31:06.807  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,11-18 14:31:06.807  5451  5499 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 14:31:06.808  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:06.809  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 14:31:06.812  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 14:31:06.813  5451  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 14:31:06.813  5451  5499 D io.jxcore.node.ConnectivityMonitor: start: OK
11-18 14:31:06.813  5451  5499 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-18 14:31:06.813  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-18 14:31:06.813  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.813  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:06.813  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.813  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:06.814  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 14:31:06.814  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 14:31:06.814  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:06.814  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 14:31:06.815  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 14:31:06.815  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 14:31:06.815  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 14:31:06.815  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 14:31:06.816  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 14:31:06.816  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 14:31:06.816  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:06.816  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 14:31:06.817  5451  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 14:31:06.817  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 14:31:06.818  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 14:31:06.820  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 14:31:06.820  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 14:31:06.820  5451  5507 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:06.820  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 14:31:06.820  4369  4369 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32459]" dev="sockfs" ino=32459 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 14:31:06.820  4369  4369 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32459]" dev="sockfs" ino=32459 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:06.823  5451  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 14:31:06.824  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.824  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 14:31:06.825  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:06.825  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:06.825  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-18 14:31:06.827  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.827  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.827  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-18 14:31:06.827  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 14:31:06.828  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:06.828  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-18 14:31:06.828  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:06.828  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:06.828  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.829  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 14:31:06.829  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 14:31:06.829  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.829  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.829  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:06.830  5451  5499 D BluetoothAdapter: STATE_ON
,11-18 14:31:06.834  4138  4369 D BtGatt.GattService: registerClient() - UUID=f277ce52-3ffe-4422-9f3c-ae864698e613
,11-18 14:31:06.834  4138  4184 D BtGatt.GattService: onClientRegistered() - UUID=f277ce52-3ffe-4422-9f3c-ae864698e613, clientIf=5
,11-18 14:31:06.835  5451  5461 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 14:31:06.837  4138  4202 D BtGatt.AdvertiseManager: message : 0
11-18 14:31:06.838  4138  4202 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 14:31:06.850  4138  4184 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 14:31:06.856  4138  4184 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 14:31:06.857  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.857  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.857  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 14:31:06.858  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 14:31:06.858  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:06.859  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:06.859  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.859  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:06.859  5451  5499 I io.jxcore.node.ConnectionHelper: start: OK
11-18 14:31:06.860  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 14:31:06.861  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.861  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:06.861  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-18 14:31:06.861  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.861  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.861  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:06.861  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.862  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-18 14:31:06.862  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-18 14:31:06.862  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.862  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.862  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 14:31:06.862  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.864  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.864  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 14:31:06.865  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.865  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.865  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:06.865  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 14:31:07.363  5451  5499 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-18 14:31:07.363  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-18 14:31:07.364  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-18 14:31:07.364  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-18 14:31:07.364  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-18 14:31:07.364  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-18 14:31:07.364  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-18 14:31:07.364  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-18 14:31:07.365  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-18 14:31:07.366  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-18 14:31:07.366  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-18 14:31:07.367  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-18 14:31:07.367  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 14:31:07.367  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 14:31:07.367  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-18 14:31:07.367  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 14:31:07.367  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-18 14:31:07.367  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-18 14:31:07.368  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 14:31:07.368  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 14:31:07.368  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 14:31:07.368  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 14:31:07.368  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 14:31:07.368  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 14:31:07.369  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 14:31:07.369  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 14:31:07.369  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 14:31:07.369  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 14:31:07.369  5451  5507 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 14:31:07.369  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 14:31:07.369  5451  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 14:31:07.369  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 14:31:07.369  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 14:31:07.369  5451  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 14:31:07.370  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.370  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.370  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.370  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.372  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:07.372  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 14:31:07.373  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:07.373  5451  5499 D BluetoothLeScanner: could not find callback wrapper
11-18 14:31:07.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 14:31:07.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.374  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.374  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 14:31:07.374  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.375  4138  4202 D BtGatt.AdvertiseManager: message : 1
11-18 14:31:07.376  4138  4202 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 14:31:07.388  4138  4184 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 14:31:07.388  4138  4184 D BtGatt.GattService: Client app is not null!
,11-18 14:31:07.389  4138  4371 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 14:31:07.390  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 14:31:07.391  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.391  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 14:31:07.391  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.391  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.391  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.392  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 14:31:07.392  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 14:31:07.394  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 14:31:07.394  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.397  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.397  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:07.397  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.397  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.398  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 14:31:07.398  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 14:31:07.398  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:07.398  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:07.398  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 14:31:07.398  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:07.399  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:07.399  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.399  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 14:31:07.399  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 14:31:07.399  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.399  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.399  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 14:31:07.399  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.400  5451  5499 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 14:31:07.400  5451  5499 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 14:31:07.400  5451  5499 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 14:31:07.400  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-18 14:31:07.400  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.400  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.401  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.401  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.401  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start ,operation: Should start/stop everything
11-18 14:31:07.401  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.401  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 14:31:07.401  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.401  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 14:31:07.401  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.401  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:07.401  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:07.402  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 14:31:07.403  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 14:31:07.403  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 14:31:07.403  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 14:31:07.403  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 14:31:07.403  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 14:31:07.404  5451  5510 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 14:31:07.403  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 14:31:07.405  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:07.405  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 14:31:07.405  5451  5510 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 14:31:07.412  5451  5510 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 14:31:07.412  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 14:31:07.412  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 14:31:07.412  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 14:31:07.407  4151  4151 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33048]" dev="sockfs" ino=33048 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:07.410  4151  4151 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33048]" dev="sockfs" ino=33048 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:07.417  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.417  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 14:31:07.418  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:07.418  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:07.418  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-18 14:31:07.420  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.420  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.420  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 14:31:07.420  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 14:31:07.420  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:07.421  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-18 14:31:07.421  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:07.421  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:07.421  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.421  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 14:31:07.421  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:07.422  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.422  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.422  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.423  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:07.426  4138  4152 D BtGatt.GattService: registerClient() - UUID=79c6c350-2bf8-452a-bd2b-40974a9ffbd6
11-18 14:31:07.426  4138  4184 D BtGatt.GattService: onClientRegistered() - UUID=79c6c350-2bf8-452a-bd2b-40974a9ffbd6, clientIf=5
11-18 14:31:07.426  5451  5461 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 14:31:07.427  4138  4202 D BtGatt.AdvertiseManager: message : 0
11-18 14:31:07.429  4138  4202 D BtGatt.AdvertiseManager: starting multi advertising
11-18 14:31:07.440  4138  4184 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-18 14:31:07.445  4138  4184 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 14:31:07.446  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.446  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 14:31:07.448  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 14:31:07.448  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.449  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.449  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.449  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.449  5451  5499 I io.jxcore.node.ConnectionHelper: start: OK
11-18 14:31:07.449  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.450  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 14:31:07.450  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.453  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.453  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 14:31:07.453  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.453  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.453  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:07.453  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 14:31:07.518   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:07.953  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-18 14:31:07.953  5451  5499 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 14:31:07.954  5451  5499 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 14:31:07.954  5451  5499 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-18 14:31:07.954  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 14:31:07.954  5451  5499 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-18 14:31:07.954  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-18 14:31:07.955  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.955  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.955  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 14:31:07.959  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-18 14:31:07.961  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.962  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.962  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.963  4138  4202 D BtGatt.AdvertiseManager: message : 1
,11-18 14:31:07.965  4138  4202 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 14:31:07.978  4138  4184 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 14:31:07.978  4138  4184 D BtGatt.GattService: Client app is not null!
,11-18 14:31:07.979  4138  4152 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 14:31:07.980  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 14:31:07.981  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.981  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 14:31:07.981  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.981  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.982  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 14:31:07.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.983  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 14:31:07.983  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 14:31:07.983  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:07.983  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-18 14:31:07.983  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:07.984  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:07.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 14:31:07.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:07.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:07.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.985  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:07.987  5451  5499 D BluetoothAdapter: STATE_ON
,11-18 14:31:07.992  4138  4152 D BtGatt.GattService: registerClient() - UUID=b6b598f0-6b9f-4c61-a7c3-18b9e94baef1
,11-18 14:31:07.993  4138  4184 D BtGatt.GattService: onClientRegistered() - UUID=b6b598f0-6b9f-4c61-a7c3-18b9e94baef1, clientIf=5
11-18 14:31:07.993  5451  5462 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 14:31:07.996  4138  4202 D BtGatt.AdvertiseManager: message : 0
,11-18 14:31:07.999  4138  4202 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 14:31:08.012  4138  4184 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 14:31:08.018  4138  4184 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 14:31:08.019  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.019  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.019  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-18 14:31:08.019  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.019  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.019  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.019  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.020  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.020  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.020  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:08.020  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.020  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:08.020  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 14:31:08.020  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-18 14:31:08.020  5451  5499 I io.jxcore.node.ConnectionHelper: start: OK
11-18 14:31:08.020  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.021  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.021  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.021  5451  5499 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 14:31:08.022  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 14:31:08.022  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 14:31:08.022  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 14:31:08.022  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 14:31:08.022  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 14:31:08.022  5451  5510 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 14:31:08.022  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 14:31:08.022  5451  5510 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 14:31:08.022  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 14:31:08.022  5451  5510 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 14:31:08.022  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 14:31:08.022  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 14:31:08.022  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 14:31:08.022  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 14:31:08.022  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:08.022  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 14:31:08.023  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 14:31:08.023  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 14:31:08.023  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.023  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.023  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.023  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.024  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:08.024  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 14:31:08.025  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:08.025  5451  5499 D BluetoothLeScanner: could not find callback wrapper
11-18 14:31:08.025  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 14:31:08.025  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.025  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.025  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.025  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 14:31:08.026  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.027  4138  4202 D BtGatt.AdvertiseManager: message : 1
,11-18 14:31:08.027  4138  4202 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 14:31:08.033  4138  4184 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 14:31:08.033  4138  4184 D BtGatt.GattService: Client app is not null!
,11-18 14:31:08.034  4138  4152 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 14:31:08.035  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 14:31:08.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 14:31:08.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.037  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.037  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:08.037  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.038  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.038  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-18 14:31:08.038  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 14:31:08.038  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:08.038  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:08.038  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:08.038  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.038  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 14:31:08.038  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 14:31:08.038  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.038  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.039  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 14:31:08.039  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.039  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 14:31:08.040  5451  5499 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 14:31:08.040  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.040  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.040  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.040  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.040  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 14:31:08.041  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-18 14:31:08.042  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-18 14:31:08.043  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-18 14:31:08.043  5451  5499 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-18 14:31:08.044  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-18 14:31:08.044  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-18 14:31:08.045  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-18 14:31:08.045  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-18 14:31:08.045  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 14:31:08.046  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 14:31:08.046  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 14:31:08.046  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 14:31:08.047  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-18 14:31:08.048  5451  5499 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-18 14:31:08.048  5451  5499 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
,11-18 14:31:08.051  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-18 14:31:08.052  5451  5499 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-18 14:31:08.053  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-18 14:31:08.053  5451  5499 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 14:31:08.053  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-18 14:31:08.054  5451  5499 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 14:31:08.054  5451  5499 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 14:31:08.054  5451  5499 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 14:31:08.054  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 14:31:08.054  5451  5499 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-18 14:31:08.054  5451  5499 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-18 14:31:08.054  5451  5499 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 14:31:08.054  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 14:31:08.054  5451  5499 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 14:31:08.054  5451  5499 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 14:31:08.054  5451  5499 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 14:31:08.054  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 14:31:08.054  5451  5499 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-18 14:31:08.056  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,11-18 14:31:08.056  5451  5499 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 14:31:08.056  5451  5499 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 14:31:08.056  5451  5499 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 14:31:08.056  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 14:31:08.056  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.056  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.056  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.056  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 14:31:08.057  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 14:31:08.057  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 14:31:08.057  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 14:31:08.057  4151  4151 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33878]" dev="sockfs" ino=33878 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:08.057  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 14:31:08.058  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 14:31:08.058  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 14:31:08.057  4151  4151 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33878]" dev="sockfs" ino=33878 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:08.058  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 14:31:08.058  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 14:31:08.058  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 14:31:08.058  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 14:31:08.058  5451  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 14:31:08.059  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:08.059  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 14:31:08.060  5451  5514 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 14:31:08.062  5451  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 14:31:08.063  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 14:31:08.063  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 14:31:08.063  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 14:31:08.067  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.067  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 14:31:08.068  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:08.068  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:08.068  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-18 14:31:08.071  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.071  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.071  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 14:31:08.071  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 14:31:08.071  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:08.071  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-18 14:31:08.072  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:08.072  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:08.072  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.072  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 14:31:08.072  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:08.072  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.072  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.073  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.073  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:08.076  4138  4369 D BtGatt.GattService: registerClient() - UUID=da4f3a3c-da1f-4b06-9825-035bf3b5836e
11-18 14:31:08.076  4138  4184 D BtGatt.GattService: onClientRegistered() - UUID=da4f3a3c-da1f-4b06-9825-035bf3b5836e, clientIf=5
11-18 14:31:08.077  5451  5462 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 14:31:08.078  4138  4202 D BtGatt.AdvertiseManager: message : 0
,11-18 14:31:08.079  4138  4202 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 14:31:08.087  4138  4184 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 14:31:08.092  4138  4184 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 14:31:08.092  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.092  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.092  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 14:31:08.092  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.092  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.093  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.093  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.093  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.093  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 14:31:08.094  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 14:31:08.094  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.095  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.095  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.095  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.096  5451  5499 I io.jxcore.node.ConnectionHelper: start: OK
11-18 14:31:08.096  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.096  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.096  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.096  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 14:31:08.097  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.098  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 14:31:08.099  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 14:31:08.099  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.099  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.099  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.099  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 14:31:08.519   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:08.596  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 14:31:08.597  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 14:31:08.597  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 14:31:08.597  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 14:31:08.597  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 14:31:08.597  5451  5514 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 14:31:08.598  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 14:31:08.598  5451  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 14:31:08.598  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 14:31:08.598  5451  5514 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 14:31:08.599  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 14:31:08.599  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 14:31:08.599  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 14:31:08.599  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fab335 removed from the list
,11-18 14:31:08.599  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:08.599  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 14:31:08.599  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 14:31:08.599  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 14:31:08.599  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 14:31:08.600  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 14:31:08.600  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.600  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.601  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.602  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.604  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:08.604  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 14:31:08.606  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:08.606  5451  5499 D BluetoothLeScanner: could not find callback wrapper
11-18 14:31:08.606  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 14:31:08.606  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.607  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.607  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.607  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 14:31:08.607  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.609  4138  4202 D BtGatt.AdvertiseManager: message : 1
11-18 14:31:08.610  4138  4202 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 14:31:08.621  4138  4184 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 14:31:08.621  4138  4184 D BtGatt.GattService: Client app is not null!
,11-18 14:31:08.622  4138  4338 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 14:31:08.623  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 14:31:08.623  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.623  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 14:31:08.623  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.623  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.623  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:08.624  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 14:31:08.624  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 14:31:08.624  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 14:31:08.625  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.627  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.627  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:08.627  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.627  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:08.627  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@756a3ca removed from the list
11-18 14:31:08.627  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:08.628  5451  5499 D io.jxcore.node.ConnectivityMonitor: stop
11-18 14:31:08.628  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:08.628  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 14:31:08.628  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:08.628  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.628  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 14:31:08.628  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 14:31:08.628  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.628  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.629  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 14:31:08.629  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.631  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.631  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.631  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.631  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:08.631  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 14:31:09.132  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 14:31:09.520   550   550 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 14:31:13.632  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 14:31:13.634  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 14:31:13.635  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:13.635  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 14:31:13.641  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 14:31:13.643  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 14:31:13.643  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-18 14:31:13.643  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 14:31:13.643  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-18 14:31:13.643  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 14:31:13.643  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 14:31:13.644  5451  5516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 14:31:13.646  5451  5516 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:13.652  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-18 14:31:13.650  4338  4338 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[30187]" dev="sockfs" ino=30187 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 14:31:13.654  4338  4338 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[30187]" dev="sockfs" ino=30187 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:13.656  5451  5516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 14:31:13.657  5451  5499 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-18 14:31:13.657  5451  5499 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 14:31:13.657  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 14:31:13.658  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 14:31:13.658  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-18 14:31:13.660  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-18 14:31:13.669  5451  5499 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-18 14:31:13.670  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 14:31:13.670  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 14:31:13.670  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 14:31:13.670  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 14:31:13.670  5451  5516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 14:31:13.670  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 14:31:13.671  5451  5516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 14:31:13.671  5451  5516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 14:31:13.671  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 14:31:13.672  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:13.672  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 14:31:13.672  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-18 14:31:13.672  5451  5499 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fab335 not in the list
11-18 14:31:13.672  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 14:31:13.672  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 14:31:13.672  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 14:31:13.672  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 14:31:13.672  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 14:31:13.673  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:13.675  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:13.675  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:13.675  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:13.675  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:13.675  5451  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@756a3ca not in the list
,11-18 14:31:13.675  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:13.675  5451  5499 D io.jxcore.node.ConnectivityMonitor: stop
11-18 14:31:13.676  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:13.676  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 14:31:13.677  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-18 14:31:13.678  5451  5499 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-18 14:31:13.678  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 14:31:13.679  5451  5499 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 14:31:13.680  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-18 14:31:13.680  5451  5499 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-18 14:31:13.680  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 14:31:13.680  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-18 14:31:13.681  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-18 14:31:13.683  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-18 14:31:13.683  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 14:31:13.683  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-18 14:31:13.684  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-18 14:31:13.684  5451  5499 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 14:31:13.684  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 14:31:13.684  5451  5499 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-18 14:31:13.684  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 14:31:13.685  5451  5499 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 14:31:13.685  5451  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-18 14:31:13.685  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-18 14:31:13.686  5451  5499 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-18 14:31:13.686  5451  5499 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-18 14:31:13.686  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-18 14:31:13.687  5451  5499 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 14:31:13.687  5451  5499 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-18 14:31:13.687  5451  5499 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 14:31:13.687  5451  5499 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-18 14:31:13.687  5451  5499 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 14:31:13.688  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 14:31:13.688  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a2f788 added. We now have 3 listener(s)
11-18 14:31:13.690  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:13.690  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 14:31:13.690  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 14:31:13.690  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 14:31:13.690  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff0521 added. We now have 3 listener(s)
11-18 14:31:13.690  5451  5499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 14:31:13.692  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 14:31:13.694  5451  5499 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 14:31:13.695   930  3518 D WifiService: setWifiEnabled: true pid=5451, uid=10077
,11-18 14:31:13.695   930  3518 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 14:31:13.697  5451  5499 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 14:31:13.700  5451  5499 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-18 14:31:13.700  5451  5499 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 14:31:13.703  5451  5499 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-18 14:31:13.704  5451  5499 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 14:31:13.710  4138  4173 D BluetoothAdapterState: Current state: ON, message: 23
,11-18 14:31:13.710  4138  4173 D BluetoothAdapterProperties: Setting state to 13
11-18 14:31:13.710  4138  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 14:31:13.711  5451  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 14:31:13.711  4138  4173 D BluetoothAdapterProperties: onBluetoothDisable()
11-18 14:31:13.714  4138  4173 I BluetoothAdapterState: Entering PendingCommandState
11-18 14:31:13.714  5451  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 14:31:13.714  5451  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 14:31:13.717   930   943 I ActivityManager: Killing 4448:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-18 14:31:13.718  4138  4138 D BluetoothMapService: onReceive
11-18 14:31:13.718  4138  4138 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 14:31:13.718  4138  4184 D BluetoothAdapterProperties: Scan Mode:20
11-18 14:31:13.718  4138  4138 D BluetoothMapService: STATE_TURNING_OFF
11-18 14:31:13.718  4138  4138 D BluetoothMapService: MAP Service closeService in
,11-18 14:31:13.719  4138  4138 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 14:31:13.719  4138  4138 D ObexServerSockets0: shutdown(block = true)
11-18 14:31:13.719  4138  4372 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-18 14:31:13.719  4138  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-18 14:31:13.720  4138  4138 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 14:31:13.720  4138  4138 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-18 14:31:13.720  4138  4334 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-18 14:31:13.720  4138  4373 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-18 14:31:13.724  4138  4138 I BtOppRfcommListener: stopping Accept Thread
,11-18 14:31:13.724  4138  5171 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-18 14:31:13.724  4138  5171 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-18 14:31:13.759  5124  5124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 14:31:13.761  4138  4138 D HeadsetService: Received stop request...Stopping profile...
,11-18 14:31:13.764  3717  3903 D BluetoothHeadset: Proxy object disconnected
,11-18 14:31:13.764   930   930 D BluetoothHeadset: Proxy object disconnected
,11-18 14:31:13.764   930   930 D BluetoothHeadset: Proxy object disconnected
11-18 14:31:13.764  4138  4138 D A2dpService: Received stop request...Stopping profile...
11-18 14:31:13.764   930   930 D BluetoothHeadset: Proxy object disconnected
11-18 14:31:13.765  4138  4345 D A2dpStateMachine: Exit Disconnected: -1
11-18 14:31:13.765  5124  5140 D BluetoothHeadset: Proxy object disconnected
11-18 14:31:13.766  3065  3902 D BluetoothHeadset: Proxy object disconnected
,11-18 14:31:13.766  3065  3065 D BluetoothA2dp: Proxy object disconnected
11-18 14:31:13.766  3065  3065 D HeadsetProfile: Bluetooth service disconnected
11-18 14:31:13.767   930   930 D BluetoothA2dp: Proxy object disconnected
11-18 14:31:13.767  4138  4138 V BluetoothAdapterState: isTurningOff()=true
11-18 14:31:13.767  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:13.767  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.767  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.768  4138  4138 D HidService: Received stop request...Stopping profile...
11-18 14:31:13.768  4138  4138 D HidService: Stopping Bluetooth HidService
11-18 14:31:13.772  3065  3065 D BluetoothInputDevice: Proxy object disconnected
,11-18 14:31:13.772  3065  3065 D HidProfile: Bluetooth service disconnected
,11-18 14:31:13.773  4138  4138 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-18 14:31:13.773  4138  4138 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-18 14:31:13.773  4138  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-18 14:31:13.773  4138  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 14:31:13.773  4138  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 14:31:13.773  4138  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 14:31:13.774  4138  4184 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 14:31:13.775  4138  4138 V BluetoothAdapterState: isTurningOff()=true
11-18 14:31:13.775  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:13.775  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.775  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.775  4138  4138 D HealthService: Received stop request...Stopping profile...
11-18 14:31:13.777  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 14:31:13.777  5124  5124 D DockEventReceiver: finishStartingService: stopping service
,11-18 14:31:13.779  5124  5124 D HeadsetProfile: Bluetooth service disconnected
11-18 14:31:13.779  5124  5124 D BluetoothA2dp: Proxy object disconnected
11-18 14:31:13.779  4138  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-18 14:31:13.779  4138  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 14:31:13.780  5124  5124 D BluetoothInputDevice: Proxy object disconnected
11-18 14:31:13.780  5124  5124 D HidProfile: Bluetooth service disconnected
11-18 14:31:13.780  4138  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 14:31:13.780  4138  4313 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 14:31:13.780  4138  4313 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-18 14:31:13.780  4138  4313 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 14:31:13.780  4138  4313 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 14:31:13.780  4138  4138 D PanService: Received stop request...Stopping profile...
11-18 14:31:13.780   930  3029 I ActivityManager: Killing 4794:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-18 14:31:13.797  3065  3065 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 14:31:13.797  3065  3065 D PanProfile: Bluetooth service disconnected
,11-18 14:31:13.797  4138  4138 V BluetoothAdapterState: isTurningOff()=true
11-18 14:31:13.797  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:13.798  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.798  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.798  4138  4138 D BluetoothMapService: Received stop request...Stopping profile...
11-18 14:31:13.798  4138  4138 D BluetoothMapService: stop()
11-18 14:31:13.799  5124  5124 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 14:31:13.799  5124  5124 D PanProfile: Bluetooth service disconnected
,11-18 14:31:13.799  4138  4138 D BluetoothMapAppObserver: deinitObservers()
,11-18 14:31:13.799  4138  4138 D BluetoothMapAppObserver: removeReceiver()
11-18 14:31:13.800  4138  4138 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 14:31:13.801  3065  3065 D BluetoothMap: Proxy object disconnected
11-18 14:31:13.801  4138  4138 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-18 14:31:13.801  3065  3065 D MapProfile: Bluetooth service disconnected
11-18 14:31:13.801  5124  5124 D BluetoothMap: Proxy object disconnected
11-18 14:31:13.801  4138  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 14:31:13.801  5124  5124 D MapProfile: Bluetooth service disconnected
11-18 14:31:13.801  4138  4138 D SapService: Received stop request...Stopping profile...
11-18 14:31:13.801  4138  4138 V SapService: stop()
11-18 14:31:13.804  5124  5124 D BluetoothPbap: Proxy object disconnected
11-18 14:31:13.804  5124  5124 D PbapServerProfile: Bluetooth service disconnected
11-18 14:31:13.804  4138  4138 V BluetoothAdapterState: isTurningOff()=true
11-18 14:31:13.804  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:13.804  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.804  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.805  3065  3065 D BluetoothPbap: Proxy object disconnected
11-18 14:31:13.805  3065  3065 D PbapServerProfile: Bluetooth service disconnected
11-18 14:31:13.805  4138  4138 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-18 14:31:13.805  4138  4184 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-18 14:31:13.805  4138  4138 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-18 14:31:13.806  4138  4138 V BluetoothAdapterState: isTurningOff()=true
,11-18 14:31:13.806  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:13.806  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.806  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.806  4138  4138 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 14:31:13.806  4138  4138 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-18 14:31:13.808  4138  4138 D BluetoothMapService: MAP Service closeService in
,11-18 14:31:13.808  4138  4138 V BluetoothAdapterState: isTurningOff()=true
11-18 14:31:13.808  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:13.808  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.808  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.808  4138  4138 D BluetoothMapService: cleanup()
11-18 14:31:13.808  4138  4138 D BluetoothMapService: MAP Service closeService in
11-18 14:31:13.809  4138  4138 V BluetoothAdapterState: isTurningOff()=true
11-18 14:31:13.809  4138  4138 V BluetoothAdapterState: isTurningOn()=false
,11-18 14:31:13.809  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:13.809  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:13.809  4138  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-18 14:31:13.809  4138  4173 D BluetoothAdapterProperties: Setting state to 15
11-18 14:31:13.809  4138  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 14:31:13.810  4138  4173 I BluetoothAdapterState: Entering BleOnState
,11-18 14:31:13.821   930   941 I ActivityManager: Start proc 5522:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-18 14:31:13.822  3065  3077 D BluetoothMap: onBluetoothStateChange: up=false
,11-18 14:31:13.823  5124  5140 D BluetoothMap: onBluetoothStateChange: up=false
,11-18 14:31:13.824  3065  3078 D BluetoothPan: onBluetoothStateChange on: false
11-18 14:31:13.825   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 14:31:13.826  5124  5520 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 14:31:13.826  5124  5139 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-18 14:31:13.827  3065  3902 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 14:31:13.827  3065  3077 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-18 14:31:13.828   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 14:31:13.828   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 14:31:13.828  3717  3738 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 14:31:13.829  3065  3078 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 14:31:13.831  3065  3902 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 14:31:13.832  5124  5140 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 14:31:13.832  5124  5520 D BluetoothPan: onBluetoothStateChange on: false
11-18 14:31:13.833  5124  5139 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-18 14:31:13.833   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 14:31:13.834  4138  4173 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 14:31:13.834  4138  4173 D BluetoothAdapterProperties: Setting state to 16
11-18 14:31:13.834  4138  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-18 14:31:13.835  4138  4173 D BluetoothAdapterProperties: onBleDisable
,11-18 14:31:13.835  4138  4173 I BluetoothAdapterState: Entering PendingCommandState
11-18 14:31:13.835  4138  4177 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-18 14:31:13.836  4138  4313 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-18 14:31:13.836  4138  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 14:31:13.838  4138  4184 D BluetoothAdapterProperties: Scan Mode:20
,11-18 14:31:13.861  5522  5522 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-18 14:31:14.024  5522  5522 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.024  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 14:31:14.025  5522  5522 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 14:31:14.025  5522  5522 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.025  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 14:31:14.026  5522  5522 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 14:31:14.026  5522  5522 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.k.d(PG:583)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 14:31:14.026  5522  5522 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 14:31:14.026  5522  5522 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.026  5522  5522 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 14:31:14.026  5522  5522 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 14:31:14.026  5522  5522 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 14:31:14.029  5124  5124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 14:31:14.035  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 14:31:14.037  5124  5124 D DockEventReceiver: finishStartingService: stopping service
11-18 14:31:14.040   930  3116 I ActivityManager: Killing 5097:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-18 14:31:14.076  4138  4184 I bt_hci  : shut_down
,11-18 14:31:14.080  4138  4205 D bt_hwcfg: hw_epilog_process
11-18 14:31:14.080  4138  4205 I bt_vendor: low_power_mode_cb
,11-18 14:31:14.082  4138  4205 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-18 14:31:14.082  4138  4205 I bt_vendor: epilog_cb
11-18 14:31:14.083  4138  4205 I bt_hci  : epilog_finished_callback
,11-18 14:31:14.085  4138  4184 I bt_hci_h4: hal_close
,11-18 14:31:14.085  4138  4184 I bt_userial_vendor: device fd = 54 close
,11-18 14:31:14.176  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 14:31:14.193  4138  4177 D bt_stack_manager: event_shut_down_stack finished.
,11-18 14:31:14.194  4138  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-18 14:31:14.195  4138  4173 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-18 14:31:14.195  4138  4138 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 14:31:14.196  4138  4138 D BtGatt.GattService: Received stop request...Stopping profile...
11-18 14:31:14.196  4138  4138 D BtGatt.GattService: stop()
11-18 14:31:14.196  4138  4138 D BtGatt.AdvertiseManager: advertise clients cleared
,11-18 14:31:14.198  4138  4138 V BluetoothAdapterState: isTurningOff()=false
,11-18 14:31:14.198  4138  4138 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:14.198  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:14.198  4138  4138 V BluetoothAdapterState: isBleTurningOff()=true
11-18 14:31:14.198  4138  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-18 14:31:14.198  4138  4173 D BluetoothAdapterProperties: Setting state to 10
,11-18 14:31:14.198  4138  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-18 14:31:14.199  4138  4173 I BluetoothAdapterState: Entering OffState
,11-18 14:31:14.200   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-18 14:31:14.206  4138  4138 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-18 14:31:14.206  4138  4138 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 14:31:14.206  4138  4138 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 14:31:14.207  4138  4177 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-18 14:31:14.212  5451  5517 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 14:31:14.212  4138  4138 I art     : System.exit called, status: 0
11-18 14:31:14.212  4138  4138 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 14:31:14.212  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 14:31:14.212  5451  5517 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 14:31:14.212  5451  5517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 14:31:14.214   378   378 E lowmemorykiller: Error writing /proc/4138/oom_score_adj; errno=22
,11-18 14:31:14.216  5451  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 14:31:14.218   930  5230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=93916, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 14:31:14.238   930  3116 I ActivityManager: Process com.android.bluetooth (pid 4138) has died
11-18 14:31:14.239  5522  5540 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
11-18 14:31:14.239   930  3116 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,11-18 14:31:14.249   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cedd37e:true
,11-18 14:31:15.272   930   943 I ActivityManager: Start proc 5553:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 14:31:15.364  5553  5553 D AdapterServiceConfig: Adding HeadsetService
,11-18 14:31:15.364  5553  5553 D AdapterServiceConfig: Adding A2dpService
11-18 14:31:15.364  5553  5553 D AdapterServiceConfig: Adding HidService
11-18 14:31:15.365  5553  5553 D AdapterServiceConfig: Adding HealthService
11-18 14:31:15.365  5553  5553 D AdapterServiceConfig: Adding PanService
,11-18 14:31:15.365  5553  5553 D AdapterServiceConfig: Adding GattService
,11-18 14:31:15.365  5553  5553 D AdapterServiceConfig: Adding BluetoothMapService
11-18 14:31:15.365  5553  5553 D AdapterServiceConfig: Adding SapService
,11-18 14:31:15.378   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c6d456:true
,11-18 14:31:15.379  5553  5553 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 14:31:15.382  5553  5553 I bt_bluedroid: init
,11-18 14:31:15.382  5553  5565 I BluetoothAdapterState: Entering OffState
,11-18 14:31:15.385  5553  5566 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-18 14:31:15.386  5553  5566 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-18 14:31:15.386  5553  5566 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-18 14:31:15.386  5553  5566 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-18 14:31:15.387  5553  5553 I bt_bluedroid: get_profile_interface socket
,11-18 14:31:15.389  5553  5569 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-18 14:31:15.389  5553  5553 I bt_bluedroid: get_profile_interface sdp
11-18 14:31:15.390  5553  5569 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 14:31:15.394  5553  5564 I bt_bluedroid: config_hci_snoop_log
,11-18 14:31:15.395   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-18 14:31:15.399  5553  5565 D BluetoothAdapterState: Current state: OFF, message: 0
,11-18 14:31:15.399  5553  5565 D BluetoothAdapterProperties: Setting state to 14
11-18 14:31:15.399  5553  5565 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-18 14:31:15.400  5553  5565 D BluetoothBondStateMachine: make
,11-18 14:31:15.402  5553  5570 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 14:31:15.405  5553  5565 I BluetoothAdapterState: Entering PendingCommandState
,11-18 14:31:15.406  5553  5553 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 14:31:15.408  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
11-18 14:31:15.409  5553  5553 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-18 14:31:15.409  5553  5553 D BtGatt.GattService: Received start request. Starting profile...
11-18 14:31:15.409  5553  5553 D BtGatt.GattService: start()
11-18 14:31:15.410  5553  5553 I bt_bluedroid: get_profile_interface gatt
,11-18 14:31:15.411  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
,11-18 14:31:15.411  5553  5553 D BtGatt.AdvertiseManager: advertise manager created
,11-18 14:31:15.415  5553  5553 V BluetoothAdapterState: isTurningOff()=false
,11-18 14:31:15.416  5553  5553 V BluetoothAdapterState: isTurningOn()=false
11-18 14:31:15.416  5553  5553 V BluetoothAdapterState: isBleTurningOn()=true
11-18 14:31:15.416  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:15.416  5553  5565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 14:31:15.417  5553  5565 I bt_bluedroid: bt_bluedroid
11-18 14:31:15.418  5553  5566 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-18 14:31:15.418  5553  5566 I bt_hci  : start_up
,11-18 14:31:15.423  5553  5566 I bt_vendor: alloc value 0xf42b9871
,11-18 14:31:15.423  5553  5566 I bt_vendor: init
11-18 14:31:15.423  5553  5566 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 14:31:15.423  5553  5566 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 14:31:15.535  5553  5566 D bt_hci  : start_up starting async portion
,11-18 14:31:15.536  5553  5573 I bt_hci  : event_finish_startup
11-18 14:31:15.536  5553  5573 I bt_hci_h4: hal_open
11-18 14:31:15.536  5553  5573 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-18 14:31:15.538  5553  5573 I bt_userial_vendor: device fd = 54 open
,11-18 14:31:15.534  5574  5574 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 14:31:15.553  5553  5573 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 14:31:15.555  5553  5573 D bt_hwcfg: Chipset BCM4358A3
,11-18 14:31:15.555  5553  5573 D bt_hwcfg: Target name = [BCM4358A3]
11-18 14:31:15.556  5553  5573 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 14:31:15.724  5553  5565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 14:31:15.951  5553  5573 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-18 14:31:15.952  5553  5573 D bt_hwcfg: Settlement delay -- 100 ms
11-18 14:31:15.952  5553  5573 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 14:31:16.075  5553  5573 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-18 14:31:16.076  5553  5573 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-18 14:31:16.077  5553  5573 I bt_hwcfg: vendor lib fwcfg completed
11-18 14:31:16.077  5553  5573 I bt_vendor: firmware callback
11-18 14:31:16.077  5553  5573 I bt_hci  : firmware_config_callback
,11-18 14:31:16.086  5553  5576 I bt_btu  : btu_task pending for preload complete event
,11-18 14:31:16.086  5553  5576 I bt_btu_task: Bluetooth chip preload is complete
11-18 14:31:16.086  5553  5576 I bt_btu  : btu_task received preload complete event
,11-18 14:31:16.093  5553  5576 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 14:31:16.093  5553  5576 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-18 14:31:16.093  5553  5576 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 14:31:16.093  5553  5576 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_A2D
11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_BTM
,11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_GAP
11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_PAN
11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_SDP
,11-18 14:31:16.094  5553  5576 I         : BTE_InitTraceLevels -- TRC_GATT
11-18 14:31:16.095  5553  5576 I         : BTE_InitTraceLevels -- TRC_SMP
,11-18 14:31:16.095  5553  5576 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-18 14:31:16.095  5553  5576 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 14:31:16.180  5553  5576 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4237549
,11-18 14:31:16.180  5553  5576 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4237549 
,11-18 14:31:16.196  5553  5569 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-18 14:31:16.197  5553  5569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 14:31:16.198  5553  5569 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-18 14:31:16.200  5553  5569 D BluetoothAdapterProperties: Name is: Nexus 6P
11-18 14:31:16.202  5553  5569 D BluetoothAdapterProperties: Scan Mode:20
11-18 14:31:16.203  5553  5569 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 14:31:16.203  5553  5569 D bt_hci  : do_postload posting postload work item
,11-18 14:31:16.204  5553  5573 I bt_hci  : event_postload
11-18 14:31:16.204  5553  5573 I bt_vendor: sco_config_cb
11-18 14:31:16.204  5553  5573 I bt_hci  : sco_config_callback postload finished.
11-18 14:31:16.207  5553  5569 D bt_bte_conf: Device ID record 1 : primary
11-18 14:31:16.207  5553  5569 D bt_bte_conf:   vendorId            = 000f
11-18 14:31:16.207  5553  5569 D bt_bte_conf:   vendorIdSource      = 0001
,11-18 14:31:16.207  5553  5569 D bt_bte_conf:   product             = 1200
11-18 14:31:16.207  5553  5569 D bt_bte_conf:   version             = 1436
11-18 14:31:16.207  5553  5569 D bt_bte_conf:   clientExecutableURL = 
11-18 14:31:16.207  5553  5569 D bt_bte_conf:   serviceDescription  = 
11-18 14:31:16.207  5553  5569 D bt_bte_conf:   documentationURL    = 
11-18 14:31:16.207  5553  5569 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 14:31:16.208  5553  5566 D bt_stack_manager: event_start_up_stack finished
11-18 14:31:16.209  5553  5565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-18 14:31:16.209  5553  5565 D BluetoothAdapterProperties: Setting state to 15
11-18 14:31:16.210  5553  5565 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-18 14:31:16.212  5553  5565 I BluetoothAdapterState: Entering BleOnState
11-18 14:31:16.216  5553  5573 I bt_vendor: low_power_mode_cb
11-18 14:31:16.220  5553  5565 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-18 14:31:16.220  5553  5565 D BluetoothAdapterProperties: Setting state to 11
11-18 14:31:16.220  5553  5565 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-18 14:31:16.232  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
11-18 14:31:16.233  5553  5553 D HeadsetService: Received start request. Starting profile...
11-18 14:31:16.235  5553  5553 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 14:31:16.236  5553  5553 D HeadsetStateMachine: make
,11-18 14:31:16.245  5553  5565 I BluetoothAdapterState: Entering PendingCommandState
,11-18 14:31:16.245  5553  5565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-18 14:31:16.245  5553  5553 D HeadsetStateMachine: max_hf_connections = 1
11-18 14:31:16.246  5553  5553 I bt_bluedroid: get_profile_interface handsfree
11-18 14:31:16.246  5553  5569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-18 14:31:16.246  5553  5569 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-18 14:31:16.250  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
11-18 14:31:16.251  5553  5553 D A2dpService: Received start request. Starting profile...
11-18 14:31:16.251  5553  5553 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 14:31:16.251  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 14:31:16.252  5553  5553 I bt_bluedroid: get_profile_interface avrcp
,11-18 14:31:16.257  5553  5553 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-18 14:31:16.257  5553  5553 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-18 14:31:16.257  5553  5553 D A2dpStateMachine: make
11-18 14:31:16.259  5553  5553 I bt_bluedroid: get_profile_interface a2dp
,11-18 14:31:16.259  5553  5569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-18 14:31:16.264  5553  5585 D A2dpStateMachine: Enter Disconnected: -2
,11-18 14:31:16.264  5553  5553 I BluetoothHidServiceJni: classInitNative: succeeds
,11-18 14:31:16.266  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
,11-18 14:31:16.267  5553  5553 D HidService: Received start request. Starting profile...
,11-18 14:31:16.267  5553  5553 I bt_bluedroid: get_profile_interface hidhost
11-18 14:31:16.267  5553  5553 D HidService: setHidService(): set to: null
11-18 14:31:16.267  5553  5569 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf421856d
11-18 14:31:16.268  5553  5569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 14:31:16.268  5553  5553 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 14:31:16.268  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
,11-18 14:31:16.269  5553  5553 D HealthService: Received start request. Starting profile...
,11-18 14:31:16.270  5553  5553 I bt_bluedroid: get_profile_interface health
11-18 14:31:16.271  5553  5553 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-18 14:31:16.271  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
,11-18 14:31:16.272  5553  5553 D PanService: Received start request. Starting profile...
,11-18 14:31:16.272  5553  5553 D BluetoothPanServiceJni: initializeNative(L110): pan
11-18 14:31:16.272  5553  5553 I bt_bluedroid: get_profile_interface pan
11-18 14:31:16.273  5553  5569 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-18 14:31:16.276  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
11-18 14:31:16.276  5553  5553 D BluetoothMapService: Received start request. Starting profile...
,11-18 14:31:16.276  5553  5553 D BluetoothMapService: start()
,11-18 14:31:16.279  5553  5553 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-18 14:31:16.279  5553  5553 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-18 14:31:16.280  5553  5553 D BluetoothMapAppObserver: createReceiver()
11-18 14:31:16.281  5553  5553 D BluetoothMapAppObserver: initObservers()
11-18 14:31:16.281  5553  5553 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-18 14:31:16.288  5553  5553 V SapService: SapBinder()
11-18 14:31:16.288  5553  5553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
,11-18 14:31:16.289  5553  5553 D SapService: Received start request. Starting profile...
11-18 14:31:16.289  5553  5553 V SapService: start()
,11-18 14:31:16.291  5553  5553 V BluetoothAdapterState: isTurningOff()=false
,11-18 14:31:16.291  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.291  5553  5583 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
11-18 14:31:16.291  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.291  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isTurningOff()=false
,11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isTurningOff()=false
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.292  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isTurningOff()=false
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isTurningOff()=false
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isTurningOff()=false
,11-18 14:31:16.293  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.294  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.294  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:16.294  5553  5553 V BluetoothAdapterState: isTurningOff()=false
11-18 14:31:16.294  5553  5553 V BluetoothAdapterState: isTurningOn()=true
11-18 14:31:16.295  5553  5553 V BluetoothAdapterState: isBleTurningOn()=false
11-18 14:31:16.295  5553  5553 V BluetoothAdapterState: isBleTurningOff()=false
11-18 14:31:16.295  5553  5565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-18 14:31:16.295  5553  5565 D BluetoothAdapterProperties: ScanMode =  20
,11-18 14:31:16.295  5553  5565 D BluetoothAdapterProperties: State =  11
11-18 14:31:16.295  5553  5565 D BluetoothAdapterProperties: Setting state to 12
11-18 14:31:16.295  5553  5565 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 14:31:16.296  5553  5565 I BluetoothAdapterState: Entering OnState
11-18 14:31:16.296  3065  3078 D BluetoothMap: onBluetoothStateChange: up=true
11-18 14:31:16.298  5124  5520 D BluetoothMap: onBluetoothStateChange: up=true
11-18 14:31:16.298  5553  5569 D BluetoothAdapterProperties: Scan Mode:21
11-18 14:31:16.298  5553  5569 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-18 14:31:16.300  3065  3902 D BluetoothPan: onBluetoothStateChange on: true
,11-18 14:31:16.300  3065  3065 D BluetoothMap: Proxy object connected
11-18 14:31:16.300  5124  5124 D BluetoothMap: Proxy object connected
11-18 14:31:16.300  3065  3065 D MapProfile: Bluetooth service connected
11-18 14:31:16.300  5124  5124 D MapProfile: Bluetooth service connected
11-18 14:31:16.300  5124  5124 D BluetoothMap: getConnectedDevices()
11-18 14:31:16.300  3065  3065 D BluetoothMap: getConnectedDevices()
11-18 14:31:16.301   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 14:31:16.302  5124  5520 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 14:31:16.302  3065  3065 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 14:31:16.302  3065  3065 D PanProfile: Bluetooth service connected
,11-18 14:31:16.303  5124  5139 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-18 14:31:16.304  3065  3077 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 14:31:16.305  3065  3902 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 14:31:16.306   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 14:31:16.306  3065  3065 D BluetoothInputDevice: Proxy object connected
11-18 14:31:16.306   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 14:31:16.306  3065  3065 D HidProfile: Bluetooth service connected
11-18 14:31:16.307  3717  3736 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 14:31:16.307  5124  5124 D BluetoothInputDevice: Proxy object connected
11-18 14:31:16.307  5124  5124 D HidProfile: Bluetooth service connected
11-18 14:31:16.307  3065  3077 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 14:31:16.307  5553  5553 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 14:31:16.308  5553  5553 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-18 14:31:16.309  3065  3902 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 14:31:16.309  5553  5553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:16.311  5124  5520 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 14:31:16.311  5553  5553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:16.313  5124  5139 D BluetoothPan: onBluetoothStateChange on: true
,11-18 14:31:16.313  5553  5553 D ObexServerSockets: Succeed to create listening sockets 
11-18 14:31:16.313  5553  5553 D ObexServerSockets0: startAccept()
11-18 14:31:16.313  5553  5553 D ObexServerSockets0: prepareForNewConnect()
,11-18 14:31:16.315  5124  5520 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 14:31:16.315  5553  5553 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-18 14:31:16.315  5553  5553 D BluetoothSdpJni: SDP Create record success - handle: 0
11-18 14:31:16.315  5553  5590 D ObexServerSockets0: Accepting socket connection...
11-18 14:31:16.316  3065  3065 D BluetoothA2dp: Proxy object connected
11-18 14:31:16.316  5553  5591 D ObexServerSockets0: Accepting socket connection...
11-18 14:31:16.317   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-18 14:31:16.317   930   930 D BluetoothA2dp: Proxy object connected
11-18 14:31:16.318  5124  5124 D BluetoothPan: BluetoothPAN Proxy object connected
,11-18 14:31:16.318  5124  5124 D PanProfile: Bluetooth service connected
11-18 14:31:16.318  5124  5124 D BluetoothA2dp: Proxy object connected
,11-18 14:31:16.319  5553  5553 D BluetoothMapService: onReceive
,11-18 14:31:16.319  5553  5553 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 14:31:16.319  5553  5553 D BluetoothMapService: STATE_ON
,11-18 14:31:16.321   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-18 14:31:16.322  5553  5592 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:16.323  5553  5592 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-18 14:31:16.323  5553  5592 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 14:31:16.325  5124  5124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 14:31:16.330  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 14:31:16.332  5124  5124 D DockEventReceiver: finishStartingService: stopping service
,11-18 14:31:16.337  5124  5124 D BluetoothPbap: Proxy object connected
,11-18 14:31:16.337  5124  5124 D PbapServerProfile: Bluetooth service connected
,11-18 14:31:16.342  5553  5553 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-18 14:31:16.342  5553  5553 D ObexServerSockets0: prepareForNewConnect()
11-18 14:31:16.347  5553  5596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 14:31:16.347  3065  3065 D BluetoothPbap: Proxy object connected
11-18 14:31:16.347  3065  3065 D PbapServerProfile: Bluetooth service connected
,11-18 14:31:16.359  5553  5600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:16.361  5553  5600 I BtOppRfcommListener: Accept thread started.
,11-18 14:31:16.403  3717  3903 D BluetoothHeadset: Proxy object connected
,11-18 14:31:16.403   930   930 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.403   930   930 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.403   930   930 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.403  5124  5139 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.404  3065  3902 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.404  3065  3065 D HeadsetProfile: Bluetooth service connected
11-18 14:31:16.405  3065  3078 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.406  3065  3065 D HeadsetProfile: Bluetooth service connected
,11-18 14:31:16.407  5124  5124 D HeadsetProfile: Bluetooth service connected
,11-18 14:31:16.407   930   947 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.407   930   947 D BluetoothHeadset: Proxy object connected
11-18 14:31:16.408  3717  3738 D BluetoothHeadset: Proxy object connected
,11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 14:31:16.743  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 14:31:16.749  5451  5517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 14:31:16.753  5451  5499 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-18 14:31:16.755   930  5337 D WifiService: setWifiEnabled: false pid=5451, uid=10077
11-18 14:31:16.755   930  5337 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 14:31:16.760  5451  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 14:31:16.760   930  2896 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-18 14:31:16.761   930  2896 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-18 14:31:16.761   930  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 14:31:16.762   930  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 14:31:16.781   930  5231 D DhcpClient: Clearing IP address
,11-18 14:31:16.781   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-18 14:31:16.789   508   923 D CommandListener: Setting iface cfg
,11-18 14:31:16.795  3504  5284 V NativeCrypto: Read error: ssl=0x7fa3247300: I/O error during system call, Connection timed out
,11-18 14:31:16.798  3504  5284 V NativeCrypto: SSL shutdown failed: ssl=0x7fa3247300: I/O error during system call, Broken pipe
11-18 14:31:16.801   930  3758 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-18 14:31:16.802   930  5229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-18 14:31:16.804   930  5229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-18 14:31:16.805   930  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-18 14:31:16.806   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-18 14:31:16.809   930  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 14:31:16.814   930  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-18 14:31:16.814   930  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-18 14:31:16.818   545   545 E Parcel  : Reading a NULL string not supported here.
,11-18 14:31:16.823   930   930 D RttService: SCAN_AVAILABLE : 1
,11-18 14:31:16.823   930  3006 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 14:31:16.825   930  2898 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-18 14:31:16.826  3680  3793 W QCNEJ   : |CORE| network lost: 100
11-18 14:31:16.828  3680  3793 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-18 14:31:16.829   930  5232 D DhcpClient: Receive thread stopped
,11-18 14:31:16.839   930  2896 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-18 14:31:16.847   930  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 14:31:16.855   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 14:31:16.875   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 14:31:16.876   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-18 14:31:16.876   508   923 D TetherController: Setting IP forward enable = 0
11-18 14:31:16.876   930  2898 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-18 14:31:16.877   930  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 14:31:16.878   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-18 14:31:16.881   930  2896 D DhcpClient: doQuit
11-18 14:31:16.881   930  2896 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-18 14:31:16.881  3381  3381 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-18 14:31:16.882   930  5231 D DhcpClient: onQuitting
11-18 14:31:16.883  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-18 14:31:16.887  3886  3886 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-18 14:31:16.891  4774  4793 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 14:31:16.891  4774  4793 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 14:31:16.891  4774  4793 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-18 14:31:16.891  4774  4793 E SarControlService: no key has been found,reset the power
11-18 14:31:16.891  4774  4820 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 14:31:16.891  4774  4820 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 14:31:16.892  4774  4820 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 14:31:16.892  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 14:31:16.892  4808  4808 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 14:31:16.893  4774  4820 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 14:31:16.893  4774  4820 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 14:31:16.893  4774  4820 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 14:31:16.894  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 14:31:16.894  4808  4808 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 14:31:16.897  4808  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6d40930 HexData = [00000000ea03000000000000ffffffff]
11-18 14:31:16.897  4808  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 14:31:16.897  4808  4826 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-18 14:31:16.898  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 14:31:16.898  4774  4787 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-18 14:31:16.899  3886  3886 D SystemUpdateService: onCreate
,11-18 14:31:16.903  3886  3886 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 14:31:16.906  4808  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6d40930 HexData = [00000000eb03000000000000ffffffff]
11-18 14:31:16.906  4808  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 14:31:16.906  4808  4826 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-18 14:31:16.908  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-18 14:31:16.908  4774  4788 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 14:31:16.909  3381  3381 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 14:31:16.912  3886  3886 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-18 14:31:16.914  3381  3381 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-18 14:31:16.916   508   916 W SocketClient: write error (Broken pipe)
11-18 14:31:16.916   508   916 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-18 14:31:16.916   508   916 W SocketListener: Error sending broadcast (Broken pipe)
11-18 14:31:16.917  3886  5619 I SystemUpdateService: active receiver: enabled
,11-18 14:31:16.919  3886  5255 I iu.UploadsManager: num queued entries: 0
11-18 14:31:16.919  3886  5255 I iu.UploadsManager: num updated entries: 0
,11-18 14:31:16.920  3886  5255 I iu.SyncManager: NEXT; no task
,11-18 14:31:16.922  3886  3886 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 14:31:16.924  3886  3886 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 14:31:16.927  5258  5258 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 14:31:16.931  5258  5258 D SprintDMHelper: simOperator: 
11-18 14:31:16.931  5258  5258 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 14:31:16.938   508   923 E Netd    : netlink response contains error (No such file or directory)
,11-18 14:31:16.939   508   923 D TetherController: Setting IP forward enable = 0
11-18 14:31:16.939  3886  5619 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-18 14:31:16.939   930  2898 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-18 14:31:16.939   930  2898 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-18 14:31:16.943  4376  5625 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-18 14:31:16.943  3381  3381 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-18 14:31:16.946  3886  5619 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-18 14:31:16.946  3886  5619 I SystemUpdateService: now status is 0 (complete)
11-18 14:31:16.947  3886  5619 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 14:31:16.947  3886  5619 I SystemUpdateService: file has been verified
,11-18 14:31:16.947  3886  5619 I SystemUpdateService: OTA package size = 21989297
,11-18 14:31:16.953  3886  5619 I SystemUpdateService: showing system update notification
,11-18 14:31:16.956   930   941 I ActivityManager: Start proc 5628:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 14:31:16.962  3381  3381 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-18 14:31:16.972   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 14:31:16.974  3886  3886 D SystemUpdateService: onDestroy
,11-18 14:31:17.000  5628  5628 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 14:31:17.006   930   940 I ActivityManager: Killing 5294:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-18 14:31:17.065   930  2896 D wifi    : In wifi stop Hal
,11-18 14:31:17.065  4376  4376 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 14:31:17.066   930  2896 D wifi    : halHandle = 0x7f8d186080, mVM = 0x7fa92cd140, mCls = 0x100a12
11-18 14:31:17.066   930  3375 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-18 14:31:17.066   930  3375 D WifiHAL : Got a signal to exit!!!
,11-18 14:31:17.066   930  3375 I WifiHAL : Exit wifi_event_loop
11-18 14:31:17.066   930  2896 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-18 14:31:17.066   930  2896 E WifiHAL : Event processing terminated
11-18 14:31:17.066   930  2896 D wifi    : In wifi cleaned up handler
11-18 14:31:17.066   930  2896 I WifiHAL : Internal cleanup completed
11-18 14:31:17.068  4033  4166 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 14:31:17.090   930  3375 D wifi    : set interface wlan0 flags (DOWN)
,11-18 14:31:17.090   930  2896 D WifiNative-HAL: HAL event thread stopped successfully
,11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 14:31:17.269  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 14:31:17.274  5451  5517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 14:31:17.279   930  5337 D WifiService: setWifiEnabled: true pid=5451, uid=10077
,11-18 14:31:17.279   930  5337 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 14:31:17.280  5451  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 14:31:17.293   508   923 D SoftapController: Softap fwReload - Ok
11-18 14:31:17.294   930   947 D Tethering: InitialState.processMessage what=4
,11-18 14:31:17.297   508   923 D CommandListener: Setting iface cfg
,11-18 14:31:17.297   508   923 D CommandListener: Trying to bring down wlan0
11-18 14:31:17.299   508   923 D CommandListener: Clearing all IP addresses on wlan0
11-18 14:31:17.299   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 14:31:17.302   930  2896 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 14:31:17.783   930  3777 D WifiService: setWifiEnabled: true pid=5451, uid=10077
11-18 14:31:17.787   930  3777 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 14:31:17.918   930  2896 D wifi    : set interface wlan0 flags (UP)
,11-18 14:31:17.919   930  2896 I WifiHAL : Initializing wifi
,11-18 14:31:17.919   930  2896 I WifiHAL : Creating socket
,11-18 14:31:17.922   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-18 14:31:17.925   930  2896 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-18 14:31:17.925   930  2896 D wifi    : Did set static halHandle = 0x7f8d186080
,11-18 14:31:17.926   930  2896 D wifi    : halHandle = 0x7f8d186080, mVM = 0x7fa92cd140, mCls = 0x12ee
,11-18 14:31:17.926   930  2896 D wifi    : array field set
11-18 14:31:17.926   930  2896 I WifiNative-HAL: interface[0] = wlan0
,11-18 14:31:17.930   930  5644 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547828031616
,11-18 14:31:17.931   930  5644 D wifi    : waitForHalEvents called, vm = 0x7fa92cd140, obj = 0x12ee, env = 0x7f908a2b40
11-18 14:31:17.934   930  2896 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 14:31:17.989  5645  5645 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 14:31:18.052  5645  5645 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 14:31:18.101  5645  5645 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 14:31:18.101  5645  5645 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 14:31:18.127   930  2896 D WifiConfigStore: Loading config and enabling all networks 
,11-18 14:31:18.166   930  2896 D WifiConfigStore: loaded 0 passpoint configs
,11-18 14:31:18.168   930  2896 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-18 14:31:18.169   930  2896 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-18 14:31:18.170   930  2896 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-18 14:31:18.171   930  2896 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-18 14:31:18.172   930  2896 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-18 14:31:18.173   930  2896 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-18 14:31:18.174   930  2896 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-18 14:31:18.174   930  2896 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-18 14:31:18.174   930  2896 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-18 14:31:18.174   930  2896 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-18 14:31:18.174   930  2896 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-18 14:31:18.174   930  2896 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-18 14:31:18.179   930  2896 D WifiNative-HAL: Setting external_sim to 1
,11-18 14:31:18.179  4376  4376 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 14:31:18.180   930  2896 D wifi    : setting dfs flag to true, 0x7f912a5460
,11-18 14:31:18.181   930  2896 D WifiStateMachine: Setting OUI to DA-A1-19
11-18 14:31:18.181   930  2896 D wifi    : setting scan oui 0x7f912a5460
11-18 14:31:18.181   930  2896 D WifiHAL : Sending mac address OUI
,11-18 14:31:18.186   930  2896 E native  : do suspend false
,11-18 14:31:18.195   930  2896 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-18 14:31:18.195   508   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-18 14:31:18.195   930   930 D RttService: SCAN_AVAILABLE : 3
11-18 14:31:18.196   930  3006 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 14:31:18.197   508   923 D CommandListener: Setting iface cfg
,11-18 14:31:18.201   930  2895 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-18 14:31:18.201   930  2895 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 14:31:18.212   930  2895 D WifiNative-HAL: p2pGetDeviceAddress
,11-18 14:31:18.213   930  2895 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-18 14:31:18.221   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=97919 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 14:31:18.292  5451  5517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 14:31:18.294  5451  5517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 14:31:18.296  5451  5499 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 14:31:18.296   930  3029 D WifiService: setWifiEnabled: true pid=5451, uid=10077
11-18 14:31:18.296   930  3029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 14:31:18.297  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 14:31:18.297  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:18.297  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-18 14:31:18.297  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a2f788 removed from the list
,11-18 14:31:18.297  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 14:31:18.297  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff0521 removed from the list
11-18 14:31:18.297  5451  5499 D io.jxcore.node.ConnectivityMonitor: stop
11-18 14:31:18.299  5451  5499 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-18 14:31:18.301  5451  5499 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-18 14:31:18.301  5451  5499 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-18 14:31:18.302  5451  5499 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-18 14:31:18.304  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-18 14:31:18.305  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-18 14:31:18.306  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-18 14:31:18.306  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-18 14:31:18.307  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-18 14:31:18.309  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-18 14:31:18.309  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e8b86f4 Bundle[{}]
11-18 14:31:18.310  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-18 14:31:18.310  5451  5499 I io.jxcore.node.LifeCycleMonitor: start: OK
11-18 14:31:18.310  5451  5499 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-18 14:31:18.311  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 14:31:18.311  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 14:31:18.311  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-18 14:31:18.311  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-18 14:31:18.312  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-18 14:31:18.312  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-18 14:31:18.312  5451  5499 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 14:31:18.313  5451  5499 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-18 14:31:18.314  5451  5499 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-18 14:31:18.316  5451  5499 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 14:31:18.317  5451  5499 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-18 14:31:18.318  5451  5499 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-18 14:31:18.318  5451  5499 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-18 14:31:18.319  5451  5499 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-18 14:31:18.320  5451  5499 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-18 14:31:18.321  5451  5499 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-18 14:31:18.321  5451  5499 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
11-18 14:31:18.322  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-18 14:31:18.323  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-18 14:31:18.323  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-18 14:31:18.323  5451  5499 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 138)
11-18 14:31:18.323  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-18 14:31:18.323  5451  5499 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-18 14:31:18.323  5451  5499 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 139)
11-18 14:31:18.324  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-18 14:31:18.324  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-18 14:31:18.324  5451  5499 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-18 14:31:18.325  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 14:31:18.325  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26d0b07 added. We now have 3 listener(s)
,11-18 14:31:18.326  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:18.326  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 14:31:18.327  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 14:31:18.327  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 14:31:18.327  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340434 added. We now have 3 listener(s)
11-18 14:31:18.327  5451  5499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 14:31:18.327  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 14:31:18.331  5451  5499 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-18 14:31:18.332  5451  5499 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 14:31:18.332  5451  5499 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-18 14:31:18.332  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-18 14:31:18.333  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.333  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.333  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.333  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:18.333  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-18 14:31:18.333  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 14:31:18.333  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:18.334  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 14:31:18.336  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 14:31:18.336  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 14:31:18.336  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 14:31:18.337  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 14:31:18.337  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 14:31:18.337  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 14:31:18.337  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 14:31:18.337  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:18.337  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 14:31:18.337  5451  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 14:31:18.338  5451  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 14:31:18.340  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 14:31:18.340  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 14:31:18.340  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 14:31:18.337  5563  5563 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32691]" dev="sockfs" ino=32691 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:18.341  5451  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 14:31:18.337  5563  5563 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32691]" dev="sockfs" ino=32691 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 14:31:18.345  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:18.345  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 14:31:18.345  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:18.346  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:18.346  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 14:31:18.348  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:18.348  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.348  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 14:31:18.348  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 14:31:18.348  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 14:31:18.348  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
,11-18 14:31:18.349  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:18.349  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:18.349  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.349  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 14:31:18.349  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:18.349  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:18.349  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.350  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.350  5451  5499 D BluetoothAdapter: STATE_ON
,11-18 14:31:18.353  5553  5581 D BtGatt.GattService: registerClient() - UUID=a8027e7b-1229-4136-92d2-5043364d4d2a
,11-18 14:31:18.354  5553  5569 D BtGatt.GattService: onClientRegistered() - UUID=a8027e7b-1229-4136-92d2-5043364d4d2a, clientIf=5
,11-18 14:31:18.354  5451  5462 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 14:31:18.356  5553  5571 D BtGatt.AdvertiseManager: message : 0
,11-18 14:31:18.358  5553  5571 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 14:31:18.367  5553  5569 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 14:31:18.372  5553  5569 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 14:31:18.373  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.373  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.373  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 14:31:18.374  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 14:31:18.374  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:18.376  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.376  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.376  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:18.376  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-18 14:31:18.377  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 14:31:18.377  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.380  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.380  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 14:31:18.380  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.380  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.380  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:18.380  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 14:31:18.880  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 14:31:18.880  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 14:31:18.880  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 14:31:21.263  5645  5645 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 14:31:21.269  5645  5645 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 14:31:21.276  5645  5645 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 14:31:21.352   930  2896 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-18 14:31:21.354   930  2896 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-18 14:31:21.354   930  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 14:31:21.368   930  2896 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 14:31:21.405   930  2896 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 14:31:21.411  5645  5645 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 14:31:21.838  5645  5645 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 14:31:21.872  5645  5645 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-18 14:31:21.873  5645  5645 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-18 14:31:21.879  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 14:31:21.879  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 14:31:21.879  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 14:31:21.879  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 14:31:21.879  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 14:31:21.880  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 14:31:21.880  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 14:31:21.880  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 14:31:21.880  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 14:31:21.880  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 14:31:21.880  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 14:31:21.880  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 14:31:21.880  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 14:31:21.880  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.881  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.881  5451  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 14:31:21.881  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.881  5451  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 14:31:21.881  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.881  5451  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 14:31:21.882  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:21.882  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 14:31:21.883   930  2896 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-18 14:31:21.883   930  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 14:31:21.883   930  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
11-18 14:31:21.884  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:21.884  5451  5499 D BluetoothLeScanner: could not find callback wrapper
11-18 14:31:21.884  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 14:31:21.884  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.884  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.884  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.884  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 14:31:21.885  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.886  5553  5571 D BtGatt.AdvertiseManager: message : 1
11-18 14:31:21.887  5553  5571 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 14:31:21.897  5553  5569 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 14:31:21.897  5553  5569 D BtGatt.GattService: Client app is not null!
11-18 14:31:21.898  5553  5564 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.899   930  2896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.899  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 14:31:21.899  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 14:31:21.901  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 14:31:21.902  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.904  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.904  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:21.904  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.904  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.904  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 14:31:21.904  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 14:31:21.905  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:21.905  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 14:31:21.905  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 14:31:21.905  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:21.905  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:21.906  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.906  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 14:31:21.906  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 14:31:21.906  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 14:31:21.906  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-18 14:31:21.906  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 14:31:21.906  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.907  5451  5499 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-18 14:31:21.907  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 14:31:21.908  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.908  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 14:31:21.908  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-18 14:31:21.908  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 14:31:21.909  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.909  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.909  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-18 14:31:21.909  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:21.909  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:21.909  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 14:31:21.911  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 14:31:21.912   508   923 D CommandListener: Setting iface cfg
11-18 14:31:21.915  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 14:31:21.915  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 14:31:21.915  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 14:31:21.918   930  2896 D WifiStateMachine: Start Dhcp Watchdog 2
,11-18 14:31:21.920  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:21.920  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 14:31:21.921  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:21.921  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:21.921  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 14:31:21.924  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-18 14:31:21.927  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-18 14:31:21.927  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.927  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 14:31:21.927  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 14:31:21.928  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 14:31:21.928   930  2896 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-18 14:31:21.928   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 14:31:21.928   930  2898 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-18 14:31:21.928  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 14:31:21.928  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:21.929  5451  5499 D BluetoothAdapter: STATE_ON
,11-18 14:31:21.932  5553  5564 D BtGatt.GattService: registerClient() - UUID=c556e7c9-3b1e-44b6-a687-f5dd81d83b55
11-18 14:31:21.932  5553  5569 D BtGatt.GattService: onClientRegistered() - UUID=c556e7c9-3b1e-44b6-a687-f5dd81d83b55, clientIf=5
,11-18 14:31:21.933  5451  5462 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-18 14:31:21.933  5553  5582 D BtGatt.GattService: start scan with filters
,11-18 14:31:21.937  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-18 14:31:21.937  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.937  5553  5572 D BtGatt.ScanManager: handling starting scan
11-18 14:31:21.937  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 14:31:21.937  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.938   930  5654 D DhcpClient: Receive thread started
11-18 14:31:21.938  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 14:31:21.938  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:21.938  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 14:31:21.938  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 14:31:21.938  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 14:31:21.938  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.938  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.938  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 14:31:21.939  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 14:31:21.939  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:21.940  5553  5572 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d88f4e1
,11-18 14:31:21.942  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.942  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 14:31:21.942  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:21.942  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:21.943  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 14:31:21.946  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 14:31:21.946  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.946  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.946  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:21.946  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 14:31:21.947  5553  5569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 14:31:21.947  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:21.948  5553  5572 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 14:31:21.953  5553  5569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 14:31:21.953  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:21.953  5553  5572 D BtGatt.ScanManager: Starting BLE batch scan
11-18 14:31:21.953  5553  5572 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 14:31:21.961  5553  5569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 14:31:21.961  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:21.966  5553  5569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 14:31:21.966  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:22.022   930  2896 E native  : do suspend false
,11-18 14:31:22.029   930  5653 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 14:31:22.448  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 14:31:22.448  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 14:31:22.448  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 14:31:24.937   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 14:31:24.944  5451  5499 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 14:31:24.945  5451  5499 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-18 14:31:24.945  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-18 14:31:24.946  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:24.946  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:24.946  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 14:31:24.946  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.946  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-18 14:31:24.947  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.947  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.947  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 14:31:24.947  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 14:31:24.947  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.948  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.948  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.951  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:24.951  5553  5582 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 14:31:24.952  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 14:31:24.954  5553  5572 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 14:31:24.955  5451  5499 D BluetoothAdapter: STATE_ON
,11-18 14:31:24.957  5553  5563 D BtGatt.GattService: stopScan() - queue size =1
11-18 14:31:24.958  5553  5564 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 14:31:24.959  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 14:31:24.959  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.959  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 14:31:24.959  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.960  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 14:31:24.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.960  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 14:31:24.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 14:31:24.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 14:31:24.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 14:31:24.960  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.963  5553  5553 D BtGatt.ScanManager: awakened up at time 104662
11-18 14:31:24.964  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:24.965   930  5653 D DhcpClient: Broadcasting DHCPDISCOVER
11-18 14:31:24.968  5553  5563 D BtGatt.GattService: registerClient() - UUID=cd800ecf-3dbd-47aa-a45d-63b96454460d
11-18 14:31:24.969  5553  5569 D BtGatt.GattService: onClientRegistered() - UUID=cd800ecf-3dbd-47aa-a45d-63b96454460d, clientIf=5
,11-18 14:31:24.969  5451  5461 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 14:31:24.970  5553  5581 D BtGatt.GattService: start scan with filters
,11-18 14:31:24.976  5553  5569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-18 14:31:24.976  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:24.977  5553  5569 D BtGatt.GattService: current time is 104675382494
,11-18 14:31:24.977  5553  5569 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -84, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,11-18 14:31:24.979  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,11-18 14:31:24.980  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-18 14:31:24.980  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-18 14:31:24.980  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-18 14:31:24.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-18 14:31:24.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:24.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-18 14:31:24.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:24.982  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.982  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:24.983  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-18 14:31:24.983  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:24.983  5451  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 14:31:24.983  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 14:31:24.983  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-18 14:31:24.983  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 14:31:24.983  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 14:31:24.983  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:24.983  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:24.984  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 14:31:24.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 14:31:24.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-18 14:31:24.984  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 14:31:24.985  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 14:31:24.985  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-18 14:31:24.985  5451  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 14:31:24.990  5563  5563 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33992]" dev="sockfs" ino=33992 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 14:31:24.990  5563  5563 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33992]" dev="sockfs" ino=33992 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 14:31:24.986  5451  5657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 14:31:24.986  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 14:31:24.987  5451  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 14:31:24.987  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 14:31:24.987  5553  5569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 14:31:24.987  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:24.988  5553  5572 D BtGatt.ScanManager: stopping BLe Batch
,11-18 14:31:24.995  5451  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 14:31:24.995  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.995  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:24.995  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.995  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 14:31:24.995  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 14:31:24.995  5553  5569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 14:31:24.995  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 14:31:24.995  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:24.995  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-18 14:31:24.996  5451  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:24.996  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:24.996  5553  5572 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 14:31:24.996  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.996  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 14:31:24.996  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 14:31:24.996  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.996  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.996  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:24.997  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:25.001  5553  5582 D BtGatt.GattService: registerClient() - UUID=aa1c450f-16f7-4c46-a619-7020347ccfda
11-18 14:31:25.001  5553  5569 D BtGatt.GattService: onClientRegistered() - UUID=aa1c450f-16f7-4c46-a619-7020347ccfda, clientIf=6
,11-18 14:31:25.002  5451  5462 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-18 14:31:25.003  5553  5569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 14:31:25.003  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:25.003  5553  5571 D BtGatt.AdvertiseManager: message : 0
11-18 14:31:25.005  5553  5572 D BtGatt.ScanManager: handling starting scan
,11-18 14:31:25.006  5553  5571 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 14:31:25.012  5553  5569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 14:31:25.012  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:25.013  5553  5572 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 14:31:25.023  5553  5569 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 14:31:25.028  5553  5569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 14:31:25.028  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:25.028  5553  5572 D BtGatt.ScanManager: Starting BLE batch scan
11-18 14:31:25.029  5553  5572 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 14:31:25.034  5553  5569 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 14:31:25.035  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:25.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 14:31:25.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:25.035  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.035  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-18 14:31:25.036  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-18 14:31:25.036  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 14:31:25.038  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 14:31:25.038  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.041  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.041  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.041  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:25.041  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:25.041  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.042  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:25.042  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-18 14:31:25.043  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-18 14:31:25.043  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.043  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:25.043  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.043  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 14:31:25.043  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 14:31:25.043  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 14:31:25.044  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.044  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-18 14:31:25.044  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.047  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.047  5553  5569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-18 14:31:25.047  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 14:31:25.047  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:25.047  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-18 14:31:25.048  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.048  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:25.048  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-18 14:31:25.054  5553  5569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-18 14:31:25.054  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:25.549  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-18 14:31:25.549  5451  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 14:31:25.549  5451  5451 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 14:31:28.047  5451  5499 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 14:31:28.047  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 14:31:28.047  5451  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 14:31:28.048  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 14:31:28.048  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 14:31:28.048  5451  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 14:31:28.048  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 14:31:28.049  5451  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 14:31:28.049  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 14:31:28.049  5451  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 14:31:28.049  5451  5499 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 14:31:28.049  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 14:31:28.049  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 14:31:28.049  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 14:31:28.050  5451  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26d0b07 removed from the list
11-18 14:31:28.050  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 14:31:28.050  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 14:31:28.050  5451  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 14:31:28.050  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 14:31:28.050  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 14:31:28.050  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.051  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.051  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.051  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 14:31:28.052  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.053  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:28.054  5553  5581 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 14:31:28.055  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 14:31:28.055  5553  5572 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 14:31:28.057  5451  5499 D BluetoothAdapter: STATE_ON
11-18 14:31:28.059  5553  5563 D BtGatt.GattService: stopScan() - queue size =1
11-18 14:31:28.061  5553  5581 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 14:31:28.062  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 14:31:28.062  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:28.062  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 14:31:28.062  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.063  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.063  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.063  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 14:31:28.063  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.064  5553  5553 D BtGatt.ScanManager: awakened up at time 107763
,11-18 14:31:28.064  5553  5571 D BtGatt.AdvertiseManager: message : 1
11-18 14:31:28.066  5553  5571 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 14:31:28.077  5553  5569 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-18 14:31:28.078  5553  5569 D BtGatt.GattService: Client app is not null!
,11-18 14:31:28.080  5553  5581 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 14:31:28.080  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 14:31:28.080  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:28.080  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 14:31:28.080  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
,11-18 14:31:28.081  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.081  5451  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.081  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 14:31:28.081  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 14:31:28.082  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 14:31:28.082  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.083  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.083  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 14:31:28.084  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.084  5451  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-18 14:31:28.084  5451  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340434 removed from the list
11-18 14:31:28.084  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:28.084  5451  5499 D io.jxcore.node.ConnectivityMonitor: stop
11-18 14:31:28.084  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 14:31:28.084  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:28.084  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 14:31:28.084  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 14:31:28.084  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-18 14:31:28.084  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.084  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.084  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 14:31:28.084  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.085  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 14:31:28.085  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-18 14:31:28.085  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 14:31:28.085  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 14:31:28.086  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 14:31:28.086  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 14:31:28.086  5451  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 14:31:28.086  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-18 14:31:28.087  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 14:31:28.087  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 14:31:28.088  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-18 14:31:28.089  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 14:31:28.089  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 14:31:28.090  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 14:31:28.091  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-18 14:31:28.091  5451  5499 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-18 14:31:28.100  5553  5569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-18 14:31:28.100  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:28.100  5553  5569 D BtGatt.GattService: current time is 107798371531
11-18 14:31:28.100  5553  5569 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -85, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -90, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-18 14:31:28.100  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-18 14:31:28.100  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 14:31:28.101  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-18 14:31:28.101  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 14:31:28.101  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-18 14:31:28.101  5553  5569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-18 14:31:28.106  5553  5569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-18 14:31:28.106  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:28.106  5553  5572 D BtGatt.ScanManager: stopping BLe Batch
,11-18 14:31:28.112  5553  5569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 14:31:28.112  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 14:31:28.112  5553  5572 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 14:31:28.116  5553  5569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 14:31:28.116  5553  5569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 14:31:28.588  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 14:31:28.632   930  5653 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 14:31:28.666   930  5654 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,11-18 14:31:28.666   930  5653 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-18 14:31:28.667   930  5653 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-18 14:31:28.678   930  5654 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-18 14:31:28.679   930  5653 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-18 14:31:28.680   508   923 D CommandListener: Setting iface cfg
,11-18 14:31:28.681   930  2896 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-18 14:31:28.683   930  5653 D DhcpClient: Scheduling renewal in 86399s
,11-18 14:31:28.693   930  2896 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-18 14:31:28.694   930  2896 D WifiConfigStore: No blacklist allowed without epno enabled
,11-18 14:31:28.695   930  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-18 14:31:28.698   930  2898 D ConnectivityService: Adding iface wlan0 to network 101
,11-18 14:31:28.701   930  2896 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-18 14:31:28.735   930  2898 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-18 14:31:28.735   930  2898 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-18 14:31:28.737   930  2898 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 14:31:28.739   930  2898 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-18 14:31:28.740   930  2898 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-18 14:31:28.746   930  2898 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 14:31:28.751   930  2898 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-18 14:31:28.751   930  2898 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-18 14:31:28.751   930  2898 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 14:31:28.751   930  2896 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-18 14:31:28.751   930  2898 D ConnectivityService:    accepting network in place of null
11-18 14:31:28.751   930  2896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 14:31:28.752   930  2898 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -57]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 14:31:28.761   930  5651 D NetlinkSocketObserver: NeighborEvent{elapsedMs=108459, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 14:31:28.772   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 14:31:28.792   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 14:31:28.795   930  2898 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-18 14:31:28.795   930  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 14:31:28.795  3680  3793 W QCNEJ   : |CORE| network available: 101
11-18 14:31:28.796   930  2898 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-18 14:31:28.797   930   947 D Tethering: MasterInitialState.processMessage what=3
11-18 14:31:28.798  3680  3793 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-18 14:31:28.800  3680  3793 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-18 14:31:28.800  3680  3793 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-18 14:31:28.810  4774  4793 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 14:31:28.810  4774  4793 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 14:31:28.810  4774  4793 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 14:31:28.811  4774  4793 E SarControlService: no key has been found,reset the power
11-18 14:31:28.811  4774  4820 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 14:31:28.811  4774  4820 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 14:31:28.811  4774  4820 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 14:31:28.811  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 14:31:28.812  4808  4808 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-18 14:31:28.813  4774  4820 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-18 14:31:28.813  4774  4820 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 14:31:28.813  4774  4820 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 14:31:28.814  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 14:31:28.814  4808  4808 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 14:31:28.815  3872  3872 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-18 14:31:28.817  3886  3886 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-18 14:31:28.818  4808  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6d40930 HexData = [00000000ec03000000000000ffffffff]
11-18 14:31:28.819  4808  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 14:31:28.819  4808  4826 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-18 14:31:28.821  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 14:31:28.821  4774  4787 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-18 14:31:28.822  3886  3886 D SystemUpdateService: onCreate
,11-18 14:31:28.827  3886  3886 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 14:31:28.829  4808  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6d40930 HexData = [00000000ed03000000000000ffffffff]
11-18 14:31:28.829  4808  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 14:31:28.829  4808  4826 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 14:31:28.830  4808  4808 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 14:31:28.830  4774  4788 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-18 14:31:28.839  3886  3886 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 14:31:28.843  3886  5255 I iu.UploadsManager: num queued entries: 0
,11-18 14:31:28.844  3886  5255 I iu.UploadsManager: num updated entries: 0
11-18 14:31:28.844  3886  5255 I iu.SyncManager: NEXT; no task
,11-18 14:31:28.848  3886  5672 I SystemUpdateService: active receiver: enabled
,11-18 14:31:28.849  3886  3886 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 14:31:28.850  3886  3886 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-18 14:31:28.852  5258  5258 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-18 14:31:28.855  5258  5258 D SprintDMHelper: simOperator: 
,11-18 14:31:28.855  5258  5258 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 14:31:28.876   930  5650 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-18 14:31:28.882  3886  5672 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 14:31:28.894  3886  5672 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 14:31:28.894  3886  5672 I SystemUpdateService: now status is 0 (complete)
11-18 14:31:28.894  3886  5672 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 14:31:28.894  3886  5672 I SystemUpdateService: file has been verified
11-18 14:31:28.894  3886  5672 I SystemUpdateService: OTA package size = 21989297
,11-18 14:31:28.898   930  3665 D AlarmManagerService: Setting time of day to sec=1479475889
,11-18 14:31:29.305   930  3665 W AlarmManagerService: Unable to set rtc to 1479475889: Invalid argument
,11-18 14:31:29.311  3886  5672 I SystemUpdateService: showing system update notification
,11-18 14:31:29.319   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 14:31:29.320  3886  3886 D SystemUpdateService: onDestroy
,11-18 14:31:29.406   930  5650 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 13:31:29 GMT], X-Android-Received-Millis=[1479475889406], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479475889357]}
,11-18 14:31:29.407   930  2898 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 14:31:29.407   930  2898 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-18 14:31:29.407   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 14:31:29.409   930  2898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 14:31:29.458  4376  5677 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 14:31:30.202   930  2898 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 14:31:30.502  5451  5499 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 14:31:30.654  5451  5684 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 14:31:30.654  5451  5684 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 14:31:31.364   930  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 14:31:31.447  5451  5684 W !!      : call onHalfStreamCopied
,11-18 14:31:31.447  5451  5684 I testCopyDataAndClose: closing input stream
,11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 152, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 152, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 14:31:32.223  5451  5684 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 14:31:32.833   930  2896 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 8 -> obsolete
,11-18 14:31:33.628   930  2896 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-18 14:31:34.926   550   550 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 14:31:34.927   550   550 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 14:31:36.373  5451  5499 I StreamCopyingThreadTest: Starting test: testRun
,11-18 14:31:36.377  5451  5685 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:36.377  5451  5685 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 14:31:37.163   930  2898 D ConnectivityService: handlePromptUnvalidated 101
,11-18 14:31:39.928   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:40.930   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:41.384  5451  5686 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 14:31:41.387  5451  5499 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 14:31:41.570  5451  5687 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 14:31:41.570  5451  5687 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 14:31:41.931   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:42.932   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 14:31:43.196  5451  5687 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 14:31:43.934   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:44.935   550   550 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 14:31:45.979  3582  3780 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-18 14:31:45.979  3582  3780 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-18 14:31:46.011  3504  3504 I ConfigService: onCreate
,11-18 14:31:47.338  5451  5499 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 14:31:47.341  5451  5689 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:47.341  5451  5689 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 14:31:47.341  5451  5689 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:47.341  5451  5689 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 14:31:47.342  5451  5689 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 14:31:47.343  5451  5689 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:47.343  5451  5689 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-18 14:31:47.344  5451  5499 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-18 14:31:47.344  5451  5499 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-18 14:31:47.345  5451  5499 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-18 14:31:47.347  5451  5690 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:47.347  5451  5690 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 14:31:47.348  5451  5690 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 164, thread name: My test thread name): Test exception.
,11-18 14:31:47.348  5451  5690 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:47.348  5451  5690 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 14:31:47.349  5451  5690 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-18 14:31:47.349  5451  5690 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-18 14:31:47.349  5451  5690 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 14:31:47.351  5451  5499 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-18 14:31:47.351  5451  5499 E com.test.thalitest.ThaliTestRunner: 
11-18 14:31:47.351  5451  5499 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 14:31:47.351  5451  5499 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 14:31:47.352  5451,  5499 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 14:31:47.352  5451  5499 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 14:31:47.353  5451  5499 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 14:31:47.354  5451  5499 E com.test.,thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57),
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:31:47.354  5451  5499 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 14:31:47.359  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG UnitTest_app: 'Running unit tests'
11-18 14:31:47.359  5451  5499 I jxcore-log: 
11-18 14:31:47.359  5451  5499 I jxcore-log: *Native tests were executed*
11-18 14:31:47.359  5451  5499 I jxcore-log: 
11-18 14:31:47.359  5451  5499 I jxcore-log: Total number of executed tests:  82
11-18 14:31:47.359  5451  5499 I jxcore-log: 
11-18 14:31:47.359  5451  5499 I jxcore-log: Number of passed tests:  79
11-18 14:31:47.359  5451  5499 I jxcore-log: 
11-18 14:31:47.359  5451  5499 I jxcore-log: Number of failed tests:  3
11-18 14:31:47.359  5451  5499 I jxcore-log: 
11-18 14:31:47.360  5451  5499 I jxcore-log: Number of ignored tests:  0
11-18 14:31:47.360  5451  5499 I jxcore-log: 
11-18 14:31:47.360  5451  5499 I jxcore-log: Total duration:  40555
11-18 14:31:47.360  5451  5499 I jxcore-log: 
11-18 14:31:47.360  54,51  5499 I jxcore-log: Failed to execute UT.
11-18 14:31:47.360  5451  5499 I jxcore-log: 
11-18 14:31:47.360  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 14:31:47.360  5451  5499 I jxcore-log: 
11-18 14:31:47.363  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 14:31:47.363  5451  5499 I jxcore-log: 
11-18 14:31:47.367  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 14:31:47.367  5451  5499 I jxcore-log: 
11-18 14:31:47.368  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.368  5451  5499 I jxcore-log: 
11-18 14:31:47.370  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 14:31:47.370  5451  5499 I jxcore-log: 
11-18 14:31:47.370  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.370  5451  5499 I jxcore-log: 
11-18 14:31:47.371  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 14:31:47.371  5451  5499 I jxcore-log: 
11-18 14:31:47.371  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 14:31:47.371  5451  5499 I jxcore-log: 
11-18 14:31:47.371  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.371  5451  5499 I jxcore-log: 
11-18 14:31:47.371  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 14:31:47.371  5451  5499 I jxcore-log: 
11-18 14:31:47.372  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 14:31:47.372  5451  5499 I jxcore-log: 
11-18 14:31:47.372  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.372  5451  5499 I jxcore-log: 
11-18 14:31:47.372  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 14:31:47.372  5451  5499 I jxcore-log: 
11-18 14:31:47.373  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 14:31:47.373  5451  5499 I jxcore-log: 
11-18 14:31:47.373  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.373  5451  5499 I jxcore-log: 
11-18 14:31:47.373  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 14:31:47.373  5451  5499 I jxcore-log: 
11-18 14:31:47.373  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.373  5451  5499 I jxcore-log: 
,11-18 14:31:47.373  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 14:31:47.373  5451  5499 I jxcore-log: 
11-18 14:31:47.373  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.373  5451  5499 I jxcore-log: 
11-18 14:31:47.374  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 14:31:47.374  5451  5499 I jxcore-log: 
11-18 14:31:47.374  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.374  5451  5499 I jxcore-log: 
11-18 14:31:47.374  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 14:31:47.374  5451  5499 I jxcore-log: 
11-18 14:31:47.374  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.374  5451  5499 I jxcore-log: 
11-18 14:31:47.375  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 14:31:47.375  5451  5499 I jxcore-log: 
11-18 14:31:47.375  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.375  5451  5499 I jxcore-log: 
11-18 14:31:47.375  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 14:31:47.375  5451  5499 I jxcore-log: 
11-18 14:31:47.375  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.375  5451  5499 I jxcore-log: 
11-18 14:31:47.376  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 14:31:47.376  5451  5499 I jxcore-log: 
11-18 14:31:47.376  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 14:31:47.376  5451  5499 I jxcore-log: 
11-18 14:31:47.377  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 14:31:47.377  5451  5499 I jxcore-log: 
11-18 14:31:47.377  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 14:31:47.377  5451  5499 I jxcore-log: 
11-18 14:31:47.378  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.378  5451  5499 I jxcore-log: 
11-18 14:31:47.378  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 14:31:47.378  5451  5499 I jxcore-log: 
11-18 14:31:47.378  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 14:31:47.378  5451  5499 I jxcore-log,: 
11-18 14:31:47.378  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.378  5451  5499 I jxcore-log: 
11-18 14:31:47.378  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 14:31:47.378  5451  5499 I jxcore-log: 
11-18 14:31:47.379  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 14:31:47.379  5451  5499 I jxcore-log: 
11-18 14:31:47.379  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.379  5451  5499 I jxcore-log: 
11-18 14:31:47.379  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 14:31:47.379  5451  5499 I jxcore-log: 
11-18 14:31:47.379  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 14:31:47.379  5451  5499 I jxcore-log: 
11-18 14:31:47.384  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 14:31:47.384  5451  5499 I jxcore-log: 
11-18 14:31:47.384  5451  5499 I jxcore-log: 2016-11-18 13:31:47 - WARN testUtils: 'myNameCallback not set!'
11-18 14:31:47.384  5451  5499 I jxcore-log: 
11-18 14:31:47.385  5451  5451 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-18 14:31:47.872   930  5651 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127163, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 14:31:49.506  5451  5499 I jxcore-log: 2016-11-18 13:31:49 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 14:31:49.506  5451  5499 I jxcore-log: 
,11-18 14:31:49.508  5451  5499 I jxcore-log: 2016-11-18 13:31:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 14:31:49.508  5451  5499 I jxcore-log: 
,11-18 14:31:49.857  5451  5499 I jxcore-log: 2016-11-18 13:31:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 14:31:49.857  5451  5499 I jxcore-log: 
,11-18 14:31:49.871  5451  5499 I jxcore-log: 2016-11-18 13:31:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 14:31:49.871  5451  5499 I jxcore-log: 
,11-18 14:31:49.936   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:50.938   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:51.010  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 14:31:51.010  5451  5499 I jxcore-log: 
,11-18 14:31:51.045  3504  3504 I ConfigService: onDestroy
,11-18 14:31:51.181  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 14:31:51.181  5451  5499 I jxcore-log: 
,11-18 14:31:51.186  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 14:31:51.186  5451  5499 I jxcore-log: 
,11-18 14:31:51.198  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 14:31:51.198  5451  5499 I jxcore-log: 
,11-18 14:31:51.699  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 14:31:51.699  5451  5499 I jxcore-log: 
,11-18 14:31:51.746  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 14:31:51.746  5451  5499 I jxcore-log: 
,11-18 14:31:51.760  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 14:31:51.760  5451  5499 I jxcore-log: 
,11-18 14:31:51.764  5451  5499 I jxcore-log: 2016-11-18 13:31:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 14:31:51.764  5451  5499 I jxcore-log: 
,11-18 14:31:51.939   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:52.055  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 14:31:52.055  5451  5499 I jxcore-log: 
,11-18 14:31:52.187  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 14:31:52.187  5451  5499 I jxcore-log: 
,11-18 14:31:52.563  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 14:31:52.563  5451  5499 I jxcore-log: 
,11-18 14:31:52.570  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 14:31:52.570  5451  5499 I jxcore-log: 
,11-18 14:31:52.574  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 14:31:52.574  5451  5499 I jxcore-log: 
,11-18 14:31:52.578  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 14:31:52.578  5451  5499 I jxcore-log: 
,11-18 14:31:52.583  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 14:31:52.583  5451  5499 I jxcore-log: 
,11-18 14:31:52.622  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 14:31:52.622  5451  5499 I jxcore-log: 
,11-18 14:31:52.628  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 14:31:52.628  5451  5499 I jxcore-log: 
,11-18 14:31:52.658  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 14:31:52.658  5451  5499 I jxcore-log: 
,11-18 14:31:52.696  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 14:31:52.696  5451  5499 I jxcore-log: 
,11-18 14:31:52.704  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 14:31:52.704  5451  5499 I jxcore-log: 
,11-18 14:31:52.710  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 14:31:52.710  5451  5499 I jxcore-log: 
,11-18 14:31:52.727  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 14:31:52.727  5451  5499 I jxcore-log: 
,11-18 14:31:52.742  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 14:31:52.742  5451  5499 I jxcore-log: 
,11-18 14:31:52.748  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 14:31:52.748  5451  5499 I jxcore-log: 
,11-18 14:31:52.753  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 14:31:52.753  5451  5499 I jxcore-log: 
,11-18 14:31:52.767  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 14:31:52.767  5451  5499 I jxcore-log: 
,11-18 14:31:52.785  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 14:31:52.785  5451  5499 I jxcore-log: 
,11-18 14:31:52.799  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 14:31:52.799  5451  5499 I jxcore-log: 
,11-18 14:31:52.810  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 14:31:52.810  5451  5499 I jxcore-log: 
,11-18 14:31:52.823  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 14:31:52.823  5451  5499 I jxcore-log: 
,11-18 14:31:52.833  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 14:31:52.833  5451  5499 I jxcore-log: 
,11-18 14:31:52.847  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 14:31:52.847  5451  5499 I jxcore-log: 
,11-18 14:31:52.857  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 14:31:52.857  5451  5499 I jxcore-log: 
,11-18 14:31:52.864  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 14:31:52.864  5451  5499 I jxcore-log: 
,11-18 14:31:52.884  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 14:31:52.884  5451  5499 I jxcore-log: 
,11-18 14:31:52.889  5451  5499 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 14:31:52.890  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 14:31:52.890  5451  5499 I jxcore-log: 
,11-18 14:31:52.940   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:52.958  5451  5499 I jxcore-log: 2016-11-18 13:31:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:52.958  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:52.958  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:52.958  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:52.958  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:52.958  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:52.958  5451  5499 I jxcore-log: 
,11-18 14:31:53.280  5451  5499 I jxcore-log: 2016-11-18 13:31:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:53.280  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:53.280  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:53.280  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:53.280  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:53.280  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:53.280  5451  5499 I jxcore-log: 
,11-18 14:31:53.283  5451  5499 I jxcore-log: 2016-11-18 13:31:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:53.283  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:53.283  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:53.283  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:53.283  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:53.283  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:53.283  5451  5499 I jxcore-log: 
,11-18 14:31:53.687  5451  5499 I jxcore-log: 2016-11-18 13:31:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:53.687  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:53.687  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:53.687  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:53.687  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:53.687  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:53.687  5451  5499 I jxcore-log: 
,11-18 14:31:53.692  5451  5499 I jxcore-log: 2016-11-18 13:31:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:53.692  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:53.692  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:53.692  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:53.692  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:53.692  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:53.692  5451  5499 I jxcore-log: 
,11-18 14:31:53.940   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:31:54.281  5451  5499 I jxcore-log: 2016-11-18 13:31:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:54.281  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:54.281  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:54.281  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:54.281  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:54.281  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:54.281  5451  5499 I jxcore-log: 
,11-18 14:31:54.285  5451  5499 I jxcore-log: 2016-11-18 13:31:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:54.285  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:54.285  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:54.285  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:54.285  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:54.285  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:54.285  5451  5499 I jxcore-log: 
,11-18 14:31:54.941   550   550 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 14:31:55.336  5451  5499 I jxcore-log: 2016-11-18 13:31:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:55.336  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:55.336  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:55.336  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:55.336  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:55.336  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:55.336  5451  5499 I jxcore-log: 
,11-18 14:31:55.344  5451  5499 I jxcore-log: 2016-11-18 13:31:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:55.344  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:55.344  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:55.344  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:55.344  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:55.344  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:55.344  5451  5499 I jxcore-log: 
,11-18 14:31:56.381  5451  5499 I jxcore-log: 2016-11-18 13:31:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:56.381  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:56.381  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:56.381  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:56.381  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:56.381  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:56.381  5451  5499 I jxcore-log: 
,11-18 14:31:56.383  5451  5499 I jxcore-log: 2016-11-18 13:31:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:56.383  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:56.383  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:56.383  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:56.383  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:56.383  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:56.383  5451  5499 I jxcore-log: 
,11-18 14:31:57.416  5451  5499 I jxcore-log: 2016-11-18 13:31:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:57.416  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:57.416  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:57.416  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:57.416  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:57.416  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:57.416  5451  5499 I jxcore-log: 
,11-18 14:31:57.421  5451  5499 I jxcore-log: 2016-11-18 13:31:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:57.421  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:57.421  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:57.421  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:57.421  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:57.421  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:57.421  5451  5499 I jxcore-log: 
,11-18 14:31:57.958   930  5651 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-18 14:31:58.445  5451  5499 I jxcore-log: 2016-11-18 13:31:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:58.445  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:58.445  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:58.445  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:58.445  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:58.445  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:58.445  5451  5499 I jxcore-log: 
,11-18 14:31:58.449  5451  5499 I jxcore-log: 2016-11-18 13:31:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:58.449  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:58.449  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:58.449  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:58.449  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:58.449  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:58.449  5451  5499 I jxcore-log: 
,11-18 14:31:59.487  5451  5499 I jxcore-log: 2016-11-18 13:31:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:59.487  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:59.487  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:59.487  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:59.487  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:59.487  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:59.487  5451  5499 I jxcore-log: 
,11-18 14:31:59.493  5451  5499 I jxcore-log: 2016-11-18 13:31:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:31:59.493  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:31:59.493  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:31:59.493  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:31:59.493  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:31:59.493  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:31:59.493  5451  5499 I jxcore-log: 
,11-18 14:32:00.509  5451  5499 I jxcore-log: 2016-11-18 13:32:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:00.509  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:00.509  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:00.509  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:00.509  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:00.509  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:00.509  5451  5499 I jxcore-log: 
,11-18 14:32:00.512  5451  5499 I jxcore-log: 2016-11-18 13:32:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:00.512  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:00.512  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:00.512  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:00.512  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:00.512  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:00.512  5451  5499 I jxcore-log: 
,11-18 14:32:01.579  5451  5499 I jxcore-log: 2016-11-18 13:32:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:01.579  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:01.579  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:01.579  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:01.579  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:01.579  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:01.579  5451  5499 I jxcore-log: 
,11-18 14:32:01.583  5451  5499 I jxcore-log: 2016-11-18 13:32:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:01.583  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:01.583  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:01.583  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:01.583  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:01.583  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:01.583  5451  5499 I jxcore-log: 
,11-18 14:32:02.620  5451  5499 I jxcore-log: 2016-11-18 13:32:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:02.620  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:02.620  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:02.620  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:02.620  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:02.620  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:02.620  5451  5499 I jxcore-log: 
,11-18 14:32:02.627  5451  5499 I jxcore-log: 2016-11-18 13:32:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:02.627  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:02.627  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:02.627  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:02.627  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:02.627  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:02.627  5451  5499 I jxcore-log: 
,11-18 14:32:03.669  5451  5499 I jxcore-log: 2016-11-18 13:32:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:03.669  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:03.669  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:03.669  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:03.669  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:03.669  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:03.669  5451  5499 I jxcore-log: 
,11-18 14:32:03.676  5451  5499 I jxcore-log: 2016-11-18 13:32:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:03.676  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:03.676  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:03.676  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:03.676  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:03.676  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:03.676  5451  5499 I jxcore-log: 
,11-18 14:32:04.705  5451  5499 I jxcore-log: 2016-11-18 13:32:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:04.705  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:04.705  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:04.705  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:04.705  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:04.705  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:04.705  5451  5499 I jxcore-log: 
,11-18 14:32:04.708  5451  5499 I jxcore-log: 2016-11-18 13:32:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:04.708  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:04.708  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:04.708  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:04.708  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:04.708  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:04.708  5451  5499 I jxcore-log: 
,11-18 14:32:04.943   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:32:05.742  5451  5499 I jxcore-log: 2016-11-18 13:32:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:05.742  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:05.742  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:05.742  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:05.742  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:05.742  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:05.742  5451  5499 I jxcore-log: 
,11-18 14:32:05.746  5451  5499 I jxcore-log: 2016-11-18 13:32:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:05.746  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:05.746  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:05.746  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:05.746  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:05.746  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:05.746  5451  5499 I jxcore-log: 
,11-18 14:32:05.944   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:32:06.777  5451  5499 I jxcore-log: 2016-11-18 13:32:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 14:32:06.777  5451  5499 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 14:32:06.777  5451  5499 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 14:32:06.777  5451  5499 I jxcore-log: emit@events.js:82:1
11-18 14:32:06.777  5451  5499 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 14:32:06.777  5451  5499 I jxcore-log: emit@events.js:82:1'
11-18 14:32:06.777  5451  5499 I jxcore-log: 
,11-18 14:32:06.786  5451  5499 E jxcore  : Error!: error is undefined
11-18 14:32:06.786  5451  5499 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-18 14:32:06.790  5451  5499 I jxcore-log: 2016-11-18 13:32:06 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-18 14:32:06.790  5451  5499 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-18 14:32:06.790  5451  5499 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-18 14:32:06.790  5451  5499 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-18 14:32:06.790  5451  5499 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-18 14:32:06.790  5451  5499 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-18 14:32:06.790  5451  5499 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-18 14:32:06.790  5451  5499 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-18 14:32:06.792  5451  5499 I jxcore-log: 2016-11-18 13:32:06 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 14:32:06.792  5451  5499 I jxcore-log: 
,11-18 14:32:06.795  5451  5499 E jxcore-log: TypeError: 
11-18 14:32:06.796  5451  5499 E jxcore-log: error is undefined
11-18 14:32:06.796  5451  5499 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-18 14:32:06.796  5451  5499 E jxcore-log: 
,11-18 14:32:06.910   930  2897 D WifiService: Client connection lost with reason: 4
,11-18 14:32:06.910   930  5337 I WindowState: WIN DEATH: Window{623d27a u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-18 14:32:06.910   930  3758 D GraphicsStats: Buffer count: 2
,11-18 14:32:06.925   528   528 I Zygote  : Process 5451 exited cleanly (139)
,11-18 14:32:06.926   930   940 I ActivityManager: Process com.test.thalitest (pid 5451) has died
,11-18 14:32:06.927   930   940 W ActivityManager: Force removing ActivityRecord{816c45b u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-18 14:32:06.945   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:32:06.975   941   941 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[26915]" dev="sockfs" ino=26915 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 14:32:06.975   941   941 W Binder_2: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[26915]" dev="sockfs" ino=26915 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 14:32:06.980   930   941 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5451 uid 10077
11-18 14:32:06.985  3582  3582 I Keyboard.Facilitator: onFinishInput()
,11-18 14:32:07.058  3872  5696 I MicroRecognitionRnrImpl: Starting detection.
,11-18 14:32:07.059  3872  5697 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a5e80fb
,11-18 14:32:07.060   513  5699 I AudioFlinger: AudioFlinger's thread 0xf1e80000 ready to run
,11-18 14:32:07.067   513  2928 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-18 14:32:07.068  3872  5697 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a5e80fb
,11-18 14:32:07.079   513  5699 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-18 14:32:07.079   513  5699 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-18 14:32:07.079   513  5699 I ACDB-LOADER: ACDB AFE returned = -19
,11-18 14:32:07.079   513  5699 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-18 14:32:07.079   513  5699 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-18 14:32:07.079   513  5699 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-18 14:32:07.086   513  5699 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-18 14:32:07.160  3872  3872 I HotwordWorkerImpl: onReady
,11-18 14:32:07.291  5691  5691 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 14:32:07.295  5691  5691 D AndroidRuntime: CheckJNI is OFF
,11-18 14:32:07.319  5691  5691 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 14:32:07.348  5691  5691 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 14:32:07.364  5691  5691 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 14:32:07.373   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 14:32:07.527   930   953 I art     : Starting a blocking GC Explicit
11-18 14:32:07.531  3749  3927 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-18 14:32:07.604   930   953 I art     : Explicit concurrent mark sweep GC freed 15235(937KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.392ms total 76.363ms
,11-18 14:32:07.628   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 14:32:07.631  5691  5691 I art     : System.exit called, status: 0
,11-18 14:32:07.631  5691  5691 I AndroidRuntime: VM exiting with result code 0.
,11-18 14:32:07.645   930   953 I ActivityManager: Start proc 5710:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-18 14:32:07.646   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 14:32:07.657  5553  5553 D BluetoothMapAppObserver: onReceive
,11-18 14:32:07.657  5553  5553 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-18 14:32:07.666  3582  3582 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-18 14:32:07.669   930  2857 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-18 14:32:07.672  4033  4107 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-18 14:32:07.680  3582  5722 I Keyboard.Facilitator.DecoderInitializer: run()
,11-18 14:32:07.686  3582  5722 I Decoder : createOrResetDecoder
,11-18 14:32:07.706  3325  5724 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 14:32:07.718  3717  3717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-18 14:32:07.731    13    13 W kworker/1:0: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 14:32:07.741  3504  3504 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-18 14:32:07.741  3504  3504 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-18 14:32:07.738    13    13 W kworker/1:0: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 14:32:07.756   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 14:32:07.757  3749  3834 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-18 14:32:07.765    13    13 W kworker/1:0: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 14:32:07.774   930  5337 I ActivityManager: Start proc 5729:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-18 14:32:07.774  3749  3834 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 14:32:07.774  3749  3834 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3749
11-18 14:32:07.774  3749  3834 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.774  3749  3834 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 14:32:07.780   930  5737 E DropBoxManagerService: Can't write: system_app_crash
11-18 14:32:07.780   930  5737 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 14:32:07.780   930  5737 E DropBoxManagerService: 	... 5 more
11-18 14:32:07.781   930   940 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-18 14:32:07.781  3886  5740 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-18 14:32:07.781  3886  5740 D AccountUtils: Clearing selected account for com.test.thalitest
11-18 14:32:07.782  3504  3504 I ConfigService: onCreate
11-18 14:32:07.785  3872  3884 W SearchService: Abort, client detached.
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 14:32:07.785  3504  5743 E ,SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 14:32:07.785  3504  5743 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 14:32:07.786  3504  5743 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-18 14:32:07.787  3872  3872 I HotwordDetector: Closing mic
11-18 14:32:07.787  3872  4108 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a5e80fb
11-18 14:32:07.788  3872  5697 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 14:32:07.788  3325  5724 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-18 14:32:07.789  3325  5724 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-18 14:32:07.789  3325  5724 E AndroidRuntime: Process: android.process.acore, PID: 3325
11-18 14:32:07.789  3325  5724 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.789  3325  5724 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 14:32:07.795  3504  5743 W SQLiteOpenHelper: Opened config.db in read-only mode
11-18 14:32:07.803   930  5745 E DropBoxManagerService: Can't write: system_app_crash
11-18 14:32:07.803   930  5745 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 14:32:07.803   930  5745 E DropBoxManagerService: 	... 5 more
11-18 14:32:07.809  3886  5740 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-18 14:32:07.818  3582  5722 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.822  3886  5747 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.822  3886  5747 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 14:32:07.824  3886  5747 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-18 14:32:07.824  3886  5747 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-18 14:32:07.824  3886  5747 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-18 14:32:07.826  3886  5747 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-18 14:32:07.826  3886  5747 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-18 14:32:07.827  3886  5747 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-18 14:32:07.827  3886  5747 E AndroidRuntime: Process: com.google.android.gms, PID: 3886
11-18 14:32:07.827  3886  5747 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.827  3886  5747 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.836  3886  5740 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-18 14:32:07.836  3886  5740 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 14:32:07.838  3886  5740 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-18 14:32:07.855   930  5751 E DropBoxManagerService: Can't write: system_app_crash
11-18 14:32:07.855   930  5751 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 14:32:07.855   930  5751 E DropBoxManagerService: 	... 5 more
11-18 14:32:07.859   513  5699 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-18 14:32:07.860   513  5699 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-18 14:32:07.865   513  5699 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 14:32:07.866   513  5699 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 14:32:07.866   513  2928 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 14:32:07.869  3872  5696 I MicroRecognitionRnrImpl: Detection finished
11-18 14:32:07.870  3872  4109 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 14:32:07.885   930   941 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-18 14:32:07.923  3886  5750 W BaseAppContext: Using Auth Proxy for data requests.
,11-18 14:32:07.926  3886  5750 W BaseAppContext: Using Auth Proxy for data requests.
,11-18 14:32:07.939  3886  5740 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-18 14:32:07.945   550   550 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 14:32:07.956  3886  5756 I GMPM-SVC: App measurement is starting up
,11-18 14:32:07.964  3886  5756 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-18 14:32:07.964  3886  5756 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-18 14:32:07.967  3886  5756 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-18 14:32:07.967  3886  5756 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-18 14:32:07.968  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-18 14:32:07.968  3886  5756 E GMPM-SVC: Opening the database failed, dropping and recreating it
,11-18 14:32:07.975  3886  5756 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-18 14:32:07.975  3886  5756 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-18 14:32:07.976  3886  5756 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-18 14:32:07.976  3886  5756 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-18 14:32:07.977  3886  5756 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-18 14:32:07.978  3886  5756 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-18 14:32:07.994   930   943 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{33989bf u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{5b78719 3886 com.google.android.gms/10012/u0 remote:5f4e660}: process crashing
,11-18 14:32:08.001   930  3332 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3886 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-18 14:32:08.058  3886  5746 W DriveInitializer: Awaiting to be initialized
,11-18 14:32:08.058  3886  5761 W DriveInitializer: Background init thread started
,11-18 14:32:08.150   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
