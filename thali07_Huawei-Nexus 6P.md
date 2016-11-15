#### Test 93765317fadb314_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-15 15:52:00.300  3879  4273 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-15 15:52:00.377  3879  4273 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-15 15:52:00.785  5609  5609 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-15 15:52:00.790  5609  5609 D AndroidRuntime: CheckJNI is OFF
11-15 15:52:00.814  5609  5609 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-15 15:52:00.854  5609  5609 I Radio-JNI: register_android_hardware_Radio DONE
11-15 15:52:00.869  5609  5609 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-15 15:52:00.888   930  3232 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-15 15:52:00.905  5609  5609 D AndroidRuntime: Shutting down VM
11-15 15:52:00.920  4013  4028 W SearchService: Abort, client detached.
11-15 15:52:00.926  4013  4013 I HotwordDetector: Closing mic
11-15 15:52:00.926  4013  4247 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@56ad67e
11-15 15:52:00.927  4013  4269 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 15:52:00.947   930  3871 I ActivityManager: Start proc 5618:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-15 15:52:01.002   513  4271 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 15:52:01.003   513  4271 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-15 15:52:01.007   513  4271 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-15 15:52:01.007   513  4271 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 15:52:01.008   513  3033 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-15 15:52:01.010  4013  4254 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-15 15:52:01.010  4013  4267 I MicroRecognitionRnrImpl: Detection finished
11-15 15:52:01.039  5618  5618 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-15 15:52:01.061  5618  5618 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-15 15:52:01.122  5618  5618 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 5176-5233)
11-15 15:52:01.122  5618  5618 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 15:52:01.163  5618  5618 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {60495ef}
,11-15 15:52:01.163  5618  5618 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-15 15:52:01.163  5618  5618 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-15 15:52:01.167  5618  5618 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-15 15:52:01.167  5618  5618 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-15 15:52:01.217  5618  5618 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-15 15:52:01.231  5618  5618 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-15 15:52:01.232  5618  5618 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-15 15:52:01.232  5618  5618 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 15:52:01.232  5618  5618 I Adreno  : Build Date                       : 12/06/15
11-15 15:52:01.232  5618  5618 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 15:52:01.232  5618  5618 I Adreno  : Local Branch                     : mybranch17112971
11-15 15:52:01.232  5618  5618 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 15:52:01.232  5618  5618 I Adreno  : Remote Branch                    : NONE
11-15 15:52:01.232  5618  5618 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 15:52:01.277   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bc191f8:true
,11-15 15:52:01.304   409   409 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[27188]" dev="sockfs" ino=27188 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.304   409   409 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27188]" dev="sockfs" ino=27188 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.317  5618  5618 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-15 15:52:01.325  5618  5618 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-15 15:52:01.351   758   758 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34926]" dev="sockfs" ino=34926 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.351   758   758 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34926]" dev="sockfs" ino=34926 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:01.352  5618  5655 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 15:52:01.354  3190  3190 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[27198]" dev="sockfs" ino=27198 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.354  3190  3190 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27198]" dev="sockfs" ino=27198 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:01.359  5618  5642 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-15 15:52:01.393  5618  5655 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 15:52:01.478   941   941 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33011]" dev="sockfs" ino=33011 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.481   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +555ms
11-15 15:52:01.483  3691  3691 I Keyboard.Facilitator: onFinishInput()
11-15 15:52:01.478   941   941 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33011]" dev="sockfs" ino=33011 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.481  3447  3447 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33010]" dev="sockfs" ino=33010 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.481  3447  3447 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33010]" dev="sockfs" ino=33010 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:01.510  5618  5618 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5618
,11-15 15:52:01.604  5618  5618 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-15 15:52:01.748  5618  5658 D jxcore_app_log: JniHelper::setJavaVM(0xf503c000), pthread_self() = -584578768
,11-15 15:52:01.752  5618  5658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
11-15 15:52:01.752  5618  5658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-15 15:52:01.752  5618  5658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-15 15:52:01.752  5618  5658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-15 15:52:01.752  5618  5658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-15 15:52:01.752  5618  5658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73527fd added. We now have 1 listener(s)
,11-15 15:52:01.754  5618  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-15 15:52:01.754  5618  5658 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:01.754  5618  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 15:52:01.754  5618  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-15 15:52:01.757  5618  5658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8039c0 added. We now have 1 listener(s)
11-15 15:52:01.757  5618  5658 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 15:52:01.763   930  2986 D WifiService: New client listening to asynchronous messages
,11-15 15:52:01.764  5618  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 15:52:01.764  5618  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-15 15:52:01.764  5618  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-15 15:52:01.764  5618  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-15 15:52:01.764  5618  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-15 15:52:01.766  5618  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:01.766  5618  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 15:52:01.769  5618  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:01.769  5618  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 15:52:01.769  5618  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-15 15:52:01.769  5618  5658 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 15:52:01.770  5618  5658 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 15:52:01.772  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:01.774  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:01.787  5618  5618 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-15 15:52:02.155  5618  5665 W jxcore-log: Initializing JXcore engine
,11-15 15:52:02.155  5618  5665 W jxcore-log: JXcore engine is ready
,11-15 15:52:02.184  5665  5665 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11758 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-15 15:52:02.184  5665  5665 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13343]" dev="sockfs" ino=13343 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-15 15:52:02.184  5665  5665 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-15 15:52:02.184  5665  5665 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34905]" dev="sockfs" ino=34905 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-15 15:52:02.193  5618  5665 W jxcore-log: Starting JXcore engine
,11-15 15:52:02.243  5618  5665 W jxcore-log: Platform android
11-15 15:52:02.243  5618  5665 W jxcore-log: 
11-15 15:52:02.243  5618  5665 W jxcore-log: Process ARCH arm
11-15 15:52:02.243  5618  5665 W jxcore-log: 
,11-15 15:52:02.380  5618  5665 I jxcore-log: JXcore Cordova bridge is ready!
11-15 15:52:02.380  5618  5665 I jxcore-log: 
,11-15 15:52:02.381  5618  5665 W jxcore-log: JXcore engine is started
,11-15 15:52:02.388  5618  5658 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-15 15:52:02.394  5618  5618 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-15 15:52:04.572  3613  3613 I ConfigService: onDestroy
,11-15 15:52:05.849   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 15:52:05.932   930  3871 I ActivityManager: Killing 5182:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-15 15:52:06.829   930  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 15:52:08.879   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 15:52:09.556   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:10.557   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:11.558   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:12.268  5618  5665 I jxcore-log: 2016-11-15 14:52:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-15 15:52:12.268  5618  5665 I jxcore-log: 
,11-15 15:52:12.269  5618  5665 I jxcore-log: 2016-11-15 14:52:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-15 15:52:12.269  5618  5665 I jxcore-log: 
,11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:12.273  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 15:52:12.275  5618  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-15 15:52:12.277  5618  5665 I jxcore-log: 2016-11-15 14:52:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-15 15:52:12.277  5618  5665 I jxcore-log: 
,11-15 15:52:12.278  5618  5665 I jxcore-log: 2016-11-15 14:52:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-15 15:52:12.278  5618  5665 I jxcore-log: 
,11-15 15:52:12.543  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 15:52:12.543  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6785ac added. We now have 2 listener(s)
,11-15 15:52:12.544  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 15:52:12.544  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 15:52:12.544  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 15:52:12.544  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 15:52:12.544  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d68275 added. We now have 2 listener(s)
,11-15 15:52:12.544  5618  5665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 15:52:12.545  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 15:52:12.547  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:12.550  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 15:52:12.551  5618  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:12.551  5618  5665 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 15:52:12.552  5618  5665 D ExecuteNativeTests: Running unit tests
11-15 15:52:12.553  5618  5665 D BluetoothAdapter: enable(): BT is already enabled..!
11-15 15:52:12.553   930  3190 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,11-15 15:52:12.553   930  3190 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 15:52:12.558  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:12.559   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:12.564  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:13.560   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:14.094   930  2986 D WifiService: New client listening to asynchronous messages
,11-15 15:52:14.097  4013  5668 W CronetSyncConnectionRcs: Upload content type not set.
,11-15 15:52:14.296  4869  4927 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-15 15:52:14.308  4869  4869 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-15 15:52:14.311   930  3878 I ActivityManager: Killing 5259:org.codeaurora.ims/1001 (adj 15): empty #17
,11-15 15:52:14.561   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 15:52:22.558  5618  5665 I com.test.thalitest.ThaliTestRunner: Running UT
,11-15 15:52:22.626  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 15:52:22.626  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344e13f added. We now have 3 listener(s)
11-15 15:52:22.627  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:22.627  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 15:52:22.627  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 15:52:22.627  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 15:52:22.627  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6af4a0c added. We now have 3 listener(s)
11-15 15:52:22.627  5618  5665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 15:52:22.628  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 15:52:22.630  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:22.633  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 15:52:22.634  5618  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-15 15:52:22.635  5618  5665 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-15 15:52:22.638  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-15 15:52:22.638  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 15:52:22.639  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:22.639  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:22.639  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:22.640  5618  5665 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-15 15:52:22.640  5618  5665 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 15:52:22.640  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 15:52:22.640  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:22.640  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:22.640  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:22.641  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-15 15:52:22.642  5618  5665 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-15 15:52:22.642  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:22.643  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-15 15:52:22.645  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-15 15:52:22.645  5618  5665 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-15 15:52:22.657  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:22.658  5618  5665 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 15:52:22.658  5618  5665 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-15 15:52:22.658  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-15 15:52:22.658  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:22.658  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-15 15:52:22.658  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 15:52:22.658  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:22.659  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 15:52:22.660  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 15:52:22.660  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 15:52:22.660  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 15:52:22.660  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 15:52:22.661  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 15:52:22.662  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 15:52:22.662  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:22.662  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 15:52:22.663  5618  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-15 15:52:22.664  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 15:52:22.664  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 15:52:22.665  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 15:52:22.666  5618  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 15:52:22.664  4896  4896 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[27205]" dev="sockfs" ino=27205 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:22.668  5618  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 15:52:22.664  4896  4896 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[27205]" dev="sockfs" ino=27205 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:22.668  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 15:52:22.669  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 15:52:22.670  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 15:52:22.671  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.671  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 15:52:22.671  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:22.671  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-15 15:52:22.671  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 15:52:22.671  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.671  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.672  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.672  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.672  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:22.675  4684  4906 D BtGatt.GattService: registerClient() - UUID=917894be-f256-43e5-9e1d-5d06b2a74a94
,11-15 15:52:22.676  4684  4747 D BtGatt.GattService: onClientRegistered() - UUID=917894be-f256-43e5-9e1d-5d06b2a74a94, clientIf=5
,11-15 15:52:22.676  5618  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 15:52:22.679  4684  4749 D BtGatt.AdvertiseManager: message : 0
,11-15 15:52:22.683  4684  4749 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 15:52:22.702  4684  4747 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 15:52:22.711  4684  4747 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 15:52:22.713  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.713  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.713  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 15:52:22.714  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 15:52:22.714  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.714  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.714  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:22.715  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:22.715  5618  5665 I io.jxcore.node.ConnectionHelper: start: OK
11-15 15:52:22.715  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:22.716  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.716  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:22.716  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-15 15:52:22.716  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.716  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:22.716  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.717  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 15:52:22.717  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 15:52:22.717  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.717  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.717  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 15:52:22.717  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.721  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-15 15:52:22.721  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 15:52:22.722  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.722  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.722  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 15:52:22.723  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:22.723  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 15:52:23.218  5618  5665 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-15 15:52:23.219  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-15 15:52:23.220  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 15:52:23.221  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 15:52:23.222  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-15 15:52:23.222  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 15:52:23.222  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 15:52:23.222  5618  5665 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 15:52:23.222  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 15:52:23.222  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 15:52:23.222  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 15:52:23.222  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 15:52:23.223  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 15:52:23.223  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-15 15:52:23.223  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 15:52:23.223  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 15:52:23.223  5618  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 15:52:23.224  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 15:52:23.224  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 15:52:23.224  5618  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 15:52:23.224  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 15:52:23.224  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 15:52:23.224  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 15:52:23.224  5618  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 15:52:23.225  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.225  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.227  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:23.227  5618  5665 D BluetoothLeScanner: could not find callback wrapper
11-15 15:52:23.227  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 15:52:23.227  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.227  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.228  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 15:52:23.228  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.229  4684  4749 D BtGatt.AdvertiseManager: message : 1
11-15 15:52:23.230  4684  4749 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 15:52:23.245  4684  4747 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 15:52:23.246  4684  4747 D BtGatt.GattService: Client app is not null!
11-15 15:52:23.247  4684  4896 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.249  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 15:52:23.249  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 15:52:23.250  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.250  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.250  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 15:52:23.250  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.251  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.251  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:23.252  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.252  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.252  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.252  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.252  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.252  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 15:52:23.252  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-15 15:52:23.255  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-15 15:52:23.255  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.256  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.256  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.256  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.257  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 15:52:23.257  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 15:52:23.259  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 15:52:23.259  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:23.260  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:23.260  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 15:52:23.260  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 15:52:23.260  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:23.260  5618  5665 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 15:52:23.260  5618  5665 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 15:52:23.260  5618  5665 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-15 15:52:23.260  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-15 15:52:23.261  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:23.261  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 15:52:23.261  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 15:52:23.261  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:23.262  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 15:52:23.262  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 15:52:23.262  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 15:52:23.262  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 15:52:23.262  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 15:52:23.262  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 15:52:23.263  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:23.263  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 15:52:23.263  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-15 15:52:23.263  5618  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 15:52:23.264  5618  5683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:23.269  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 15:52:23.269  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 15:52:23.269  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 15:52:23.268  4896  4896 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33024]" dev="sockfs" ino=33024 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:23.268  4896  4896 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33024]" dev="sockfs" ino=33024 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:23.271  5618  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 15:52:23.277  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 15:52:23.279  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-15 15:52:23.279  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-15 15:52:23.283  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.283  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-15 15:52:23.283  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:23.283  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-15 15:52:23.283  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 15:52:23.283  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.284  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.284  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.284  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.285  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:23.288  4684  4696 D BtGatt.GattService: registerClient() - UUID=9b84a2c2-73c5-4f19-84fd-a5e703b41f73
11-15 15:52:23.289  4684  4747 D BtGatt.GattService: onClientRegistered() - UUID=9b84a2c2-73c5-4f19-84fd-a5e703b41f73, clientIf=5
,11-15 15:52:23.290  5618  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 15:52:23.291  4684  4749 D BtGatt.AdvertiseManager: message : 0
,11-15 15:52:23.295  4684  4749 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 15:52:23.310  4684  4747 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 15:52:23.317  4684  4747 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 15:52:23.317  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.318  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.318  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 15:52:23.318  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.318  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.318  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.318  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.318  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.319  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 15:52:23.321  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 15:52:23.321  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.323  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.323  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.323  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.323  5618  5665 I io.jxcore.node.ConnectionHelper: start: OK
11-15 15:52:23.323  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:23.324  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-15 15:52:23.324  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.325  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.325  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 15:52:23.325  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 15:52:23.328  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.329  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 15:52:23.329  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.329  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.329  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.329  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.329  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 15:52:23.829  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-15 15:52:23.829  5618  5665 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 15:52:23.829  5618  5665 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-15 15:52:23.829  5618  5665 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 15:52:23.829  5618  5665 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 15:52:23.830  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 15:52:23.830  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 15:52:23.830  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.833  4684  4749 D BtGatt.AdvertiseManager: message : 1
,11-15 15:52:23.835  4684  4749 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 15:52:23.848  4684  4747 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 15:52:23.849  4684  4747 D BtGatt.GattService: Client app is not null!
,11-15 15:52:23.850  4684  4896 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 15:52:23.852  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 15:52:23.852  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.852  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 15:52:23.853  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.853  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.853  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 15:52:23.853  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.853  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-15 15:52:23.854  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:23.854  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-15 15:52:23.854  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 15:52:23.854  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.854  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.855  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.855  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.856  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:23.862  4684  4896 D BtGatt.GattService: registerClient() - UUID=9381d6fe-279c-414a-8da3-5eaa41ae4ec0
11-15 15:52:23.863  4684  4747 D BtGatt.GattService: onClientRegistered() - UUID=9381d6fe-279c-414a-8da3-5eaa41ae4ec0, clientIf=5,
11-15 15:52:23.864  5618  5629 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 15:52:23.866  4684  4749 D BtGatt.AdvertiseManager: message : 0
,11-15 15:52:23.870  4684  4749 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 15:52:23.885  4684  4747 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 15:52:23.893  4684  4747 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 15:52:23.894  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.894  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.895  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 15:52:23.895  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.895  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.895  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.895  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.895  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.895  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 15:52:23.895  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 15:52:23.895  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 15:52:23.896  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-15 15:52:23.896  5618  5665 I io.jxcore.node.ConnectionHelper: start: OK
11-15 15:52:23.896  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.896  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-15 15:52:23.896  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.897  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.897  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.897  5618  5665 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 15:52:23.898  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-15 15:52:23.898  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 15:52:23.898  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 15:52:23.898  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 15:52:23.898  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-15 15:52:23.899  5618  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-15 15:52:23.899  5618  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 15:52:23.899  5618  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 15:52:23.899  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 15:52:23.899  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 15:52:23.899  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 15:52:23.899  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 15:52:23.899  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.899  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.901  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:23.901  5618  5665 D BluetoothLeScanner: could not find callback wrapper
11-15 15:52:23.902  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 15:52:23.902  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.902  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.902  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 15:52:23.902  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.904  4684  4749 D BtGatt.AdvertiseManager: message : 1
11-15 15:52:23.905  4684  4749 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 15:52:23.913  4684  4747 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 15:52:23.913  4684  4747 D BtGatt.GattService: Client app is not null!
11-15 15:52:23.914  4684  4896 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 15:52:23.915  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 15:52:23.915  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.915  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 15:52:23.915  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.915  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.915  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.916  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 15:52:23.916  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 15:52:23.916  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.916  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.916  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 15:52:23.916  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:23.917  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.917  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:23.917  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.917  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.918  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.918  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.918  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.918  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 15:52:23.918  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 15:52:23.919  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-15 15:52:23.919  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.920  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.920  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.920  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.920  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 15:52:23.920  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 15:52:23.921  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:23.921  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:23.921  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:23.923  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-15 15:52:23.923  5618  5665 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-15 15:52:23.924  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-15 15:52:23.925  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-15 15:52:23.926  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-15 15:52:23.926  5618  5665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-15 15:52:23.927  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-15 15:52:23.927  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-15 15:52:23.928  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-15 15:52:23.928  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:23.929  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:23.929  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 15:52:23.929  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:23.930  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:23.930  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 15:52:23.931  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-15 15:52:23.931  5618  5665 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 15:52:23.931  5618  5665 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 15:52:23.936  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-15 15:52:23.936  5618  5665 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-15 15:52:23.937  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-15 15:52:23.938  5618  5665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-15 15:52:23.939  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-15 15:52:23.939  5618  5665 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-15 15:52:23.940  5618  5665 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-15 15:52:23.940  5618  5665 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-15 15:52:23.940  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 15:52:23.940  5618  5665 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-15 15:52:23.940  5618  5665 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 15:52:23.940  5618  5665 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-15 15:52:23.940  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 15:52:23.940  5618  5665 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-15 15:52:23.940  5618  5665 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 15:52:23.940  5618  5665 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 15:52:23.940  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 15:52:23.941  5618  5665 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-15 15:52:23.942  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-15 15:52:23.942  5618  5665 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 15:52:23.942  5618  5665 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 15:52:23.942  5618  5665 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-15 15:52:23.943  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-15 15:52:23.943  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:23.943  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 15:52:23.943  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 15:52:23.943  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:23.944  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 15:52:23.945  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 15:52:23.945  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 15:52:23.945  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 15:52:23.945  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 15:52:23.945  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 15:52:23.945  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 15:52:23.945  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:23.945  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 15:52:23.945  5618  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 15:52:23.946  5618  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:23.948  4896  4896 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[35175]" dev="sockfs" ino=35175 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:23.948  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 15:52:23.949  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 15:52:23.949  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 15:52:23.948  4896  4896 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[35175]" dev="sockfs" ino=35175 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:23.951  5618  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 15:52:23.952  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 15:52:23.953  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 15:52:23.953  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 15:52:23.955  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.955  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 15:52:23.955  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:23.955  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-15 15:52:23.956  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 15:52:23.956  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.956  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.956  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.956  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.957  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:23.960  4684  4906 D BtGatt.GattService: registerClient() - UUID=efcd90db-e102-4267-84d5-f13bd8386f13
11-15 15:52:23.962  4684  4747 D BtGatt.GattService: onClientRegistered() - UUID=efcd90db-e102-4267-84d5-f13bd8386f13, clientIf=5
11-15 15:52:23.963  5618  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 15:52:23.964  4684  4749 D BtGatt.AdvertiseManager: message : 0
,11-15 15:52:23.968  4684  4749 D BtGatt.AdvertiseManager: starting multi advertising
11-15 15:52:23.977  4684  4747 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-15 15:52:23.982  4684  4747 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-15 15:52:23.983  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.983  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 15:52:23.985  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 15:52:23.985  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.986  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.986  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.986  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:23.986  5618  5665 I io.jxcore.node.ConnectionHelper: start: OK
11-15 15:52:23.987  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.987  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 15:52:23.988  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.990  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.990  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 15:52:23.990  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.990  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.990  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 15:52:23.990  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:23.990  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 15:52:24.488  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 15:52:24.488  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 15:52:24.488  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 15:52:24.489  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 15:52:24.489  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-15 15:52:24.489  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 15:52:24.489  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 15:52:24.489  5618  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 15:52:24.490  5618  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 15:52:24.490  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 15:52:24.490  5618  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 15:52:24.490  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344e13f removed from the list
,11-15 15:52:24.490  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 15:52:24.490  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 15:52:24.490  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 15:52:24.490  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 15:52:24.490  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-15 15:52:24.491  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 15:52:24.491  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 15:52:24.491  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.491  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 15:52:24.491  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:24.495  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:24.495  5618  5665 D BluetoothLeScanner: could not find callback wrapper
11-15 15:52:24.496  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 15:52:24.496  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:24.496  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.496  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 15:52:24.496  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.498  4684  4749 D BtGatt.AdvertiseManager: message : 1
11-15 15:52:24.499  4684  4749 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 15:52:24.511  4684  4747 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 15:52:24.511  4684  4747 D BtGatt.GattService: Client app is not null!
,11-15 15:52:24.513  4684  4696 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 15:52:24.513  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 15:52:24.513  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:24.514  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-15 15:52:24.514  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.514  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.514  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.514  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-15 15:52:24.514  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 15:52:24.515  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.515  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.515  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 15:52:24.515  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.517  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.517  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:24.518  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.518  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.518  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.519  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.519  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.519  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 15:52:24.519  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-15 15:52:24.520  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-15 15:52:24.521  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:24.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:24.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:24.525  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6af4a0c removed from the list
11-15 15:52:24.525  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:24.526  5618  5665 D io.jxcore.node.ConnectivityMonitor: stop
11-15 15:52:24.526  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:24.526  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-15 15:52:24.526  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 15:52:25.027  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 15:52:29.530  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-15 15:52:29.532  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-15 15:52:29.533  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:29.541  4696  4696 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[35179]" dev="sockfs" ino=35179 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:29.541  4696  4696 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35179]" dev="sockfs" ino=35179 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:29.535  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 15:52:29.537  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 15:52:29.537  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 15:52:29.537  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 15:52:29.537  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 15:52:29.537  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-15 15:52:29.537  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-15 15:52:29.537  5618  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 15:52:29.539  5618  5688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:29.540  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-15 15:52:29.541  5618  5665 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-15 15:52:29.541  5618  5665 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-15 15:52:29.542  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 15:52:29.542  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:29.542  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 15:52:29.544  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-15 15:52:29.547  5618  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 15:52:29.552  5618  5665 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-15 15:52:29.553  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 15:52:29.553  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 15:52:29.553  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-15 15:52:29.553  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-15 15:52:29.553  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 15:52:29.553  5618  5688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 15:52:29.553  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 15:52:29.553  5618  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 15:52:29.554  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 15:52:29.554  5618  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-15 15:52:29.554  5618  5665 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344e13f not in the list
11-15 15:52:29.554  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 15:52:29.554  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 15:52:29.554  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 15:52:29.554  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 15:52:29.554  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 15:52:29.554  5618  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-15 15:52:29.554  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 15:52:29.555  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:29.555  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 15:52:29.555  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 15:52:29.556  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:29.557  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:29.557  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:29.557  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:29.557  5618  5665 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6af4a0c not in the list
11-15 15:52:29.557  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:29.557  5618  5665 D io.jxcore.node.ConnectivityMonitor: stop
11-15 15:52:29.557  5618  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-15 15:52:29.557  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:29.557  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 15:52:29.557  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:29.559  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-15 15:52:29.560  5618  5665 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-15 15:52:29.560  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 15:52:29.560  5618  5665 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-15 15:52:29.560  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 15:52:29.560  5618  5665 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-15 15:52:29.560  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 15:52:29.561  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-15 15:52:29.562  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-15 15:52:29.564  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-15 15:52:29.565  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 15:52:29.565  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-15 15:52:29.566  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-15 15:52:29.566  5618  5665 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-15 15:52:29.567  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 15:52:29.568  5618  5665 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-15 15:52:29.568  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 15:52:29.569  5618  5665 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-15 15:52:29.569  5618  5665 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-15 15:52:29.570  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-15 15:52:29.570  5618  5665 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-15 15:52:29.570  5618  5665 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-15 15:52:29.571  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-15 15:52:29.572  5618  5665 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-15 15:52:29.572  5618  5665 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-15 15:52:29.572  5618  5665 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-15 15:52:29.572  5618  5665 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-15 15:52:29.573  5618  5665 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-15 15:52:29.573  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 15:52:29.574  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9f4e3c added. We now have 3 listener(s)
11-15 15:52:29.575  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:29.576  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 15:52:29.576  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 15:52:29.576  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 15:52:29.576  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@812c7c5 added. We now have 3 listener(s)
11-15 15:52:29.576  5618  5665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 15:52:29.577  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 15:52:29.580  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:29.584  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 15:52:29.586  5618  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:29.587  5618  5665 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-15 15:52:29.589  5618  5665 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 15:52:29.589   930  3841 D WifiService: setWifiEnabled: true pid=5618, uid=10077
11-15 15:52:29.589   930  3841 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 15:52:29.589  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:29.591  5618  5665 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-15 15:52:29.594  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:29.594  5618  5665 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-15 15:52:29.595  5618  5665 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-15 15:52:29.598   930  3871 D WifiService: setWifiEnabled: false pid=5618, uid=10077
,11-15 15:52:29.598   930  3871 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 15:52:29.601   930  2985 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-15 15:52:29.601   930  2985 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 15:52:29.601   930  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 15:52:29.601   930  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 15:52:29.609   930  5393 D DhcpClient: Clearing IP address
,11-15 15:52:29.609   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 15:52:29.612   508   924 D CommandListener: Setting iface cfg
,11-15 15:52:29.614  3613  5444 V NativeCrypto: Read error: ssl=0x7f858c9a80: I/O error during system call, Connection timed out
,11-15 15:52:29.616  3613  5444 V NativeCrypto: SSL shutdown failed: ssl=0x7f858c9a80: I/O error during system call, Broken pipe
11-15 15:52:29.618   930  3190 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-15 15:52:29.619   930  5391 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-15 15:52:29.621   930  5391 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-15 15:52:29.621   930  2988 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-15 15:52:29.622   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-15 15:52:29.624   930  2988 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 15:52:29.627   930  2988 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-15 15:52:29.627   930  2988 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-15 15:52:29.629   930  3232 I ActivityManager: Killing 5300:com.android.settings/1000 (adj 15): empty #17
11-15 15:52:29.630   537   537 E Parcel  : Reading a NULL string not supported here.
,11-15 15:52:29.638   930  5394 D DhcpClient: Receive thread stopped
,11-15 15:52:29.652   930  2988 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-15 15:52:29.655  3766  3917 W QCNEJ   : |CORE| network lost: 100
,11-15 15:52:29.656  3766  3917 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-15 15:52:29.658   930   930 D RttService: SCAN_AVAILABLE : 1
11-15 15:52:29.659   930  3099 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 15:52:29.663   930  2985 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-15 15:52:29.668   930  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-15 15:52:29.679   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 15:52:29.697   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 15:52:29.697   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 15:52:29.697   508   924 D TetherController: Setting IP forward enable = 0
11-15 15:52:29.699   930  2988 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-15 15:52:29.699   930  2988 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 15:52:29.702   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-15 15:52:29.703   930  2985 D DhcpClient: doQuit
,11-15 15:52:29.703   930  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-15 15:52:29.704   930  5393 D DhcpClient: onQuitting
11-15 15:52:29.705  3479  3479 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:29.711  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:29.713  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:29.717  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:29.718  5275  5275 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@45ad1cb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-15 15:52:29.719  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:29.720  4013  4013 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:29.722  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:29.724  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:29.727  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:29.729  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:29.729  5064  5088 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-15 15:52:29.729  5064  5088 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-15 15:52:29.730  5064  5088 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-15 15:52:29.732  5064  5088 E SarControlService: no key has been found,reset the power
,11-15 15:52:29.732  5064  5100 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-15 15:52:29.732  5064  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 15:52:29.732  5064  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 15:52:29.733  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 15:52:29.733  5089  5089 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 15:52:29.731  3879  3879 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-15 15:52:29.731  3479  3479 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-15 15:52:29.731  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:29.735  5064  5100 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 15:52:29.735  5064  5100 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 15:52:29.735  5064  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 15:52:29.736  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:29.736  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-15 15:52:29.736  5089  5089 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-15 15:52:29.739  3479  3479 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-15 15:52:29.740  5089  5103 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@62ccbc9 HexData = [00000000ea03000000000000ffffffff]
11-15 15:52:29.740  5089  5103 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 15:52:29.740  5089  5103 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-15 15:52:29.740  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 15:52:29.741  5064  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 15:52:29.741   508   917 W SocketClient: write error (Broken pipe)
,11-15 15:52:29.741   508   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-15 15:52:29.741   508   917 W SocketListener: Error sending broadcast (Broken pipe)
11-15 15:52:29.741  3879  3879 D SystemUpdateService: onCreate
11-15 15:52:29.746  3879  3879 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-15 15:52:29.746  5089  5103 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@62ccbc9 HexData = [00000000eb03000000000000ffffffff]
11-15 15:52:29.747  5089  5103 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 15:52:29.747  5089  5103 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-15 15:52:29.747  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 15:52:29.747  5064  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-15 15:52:29.754  3879  5705 I SystemUpdateService: active receiver: enabled
11-15 15:52:29.756  3879  3879 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-15 15:52:29.761   508   924 E Netd    : netlink response contains error (No such file or directory)
11-15 15:52:29.762  3879  5417 I iu.UploadsManager: num queued entries: 0
11-15 15:52:29.762  3879  5417 I iu.UploadsManager: num updated entries: 0
11-15 15:52:29.762   930  2988 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-15 15:52:29.763  3879  5417 I iu.SyncManager: NEXT; no task
,11-15 15:52:29.764  3879  3879 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 15:52:29.765  3879  3879 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-15 15:52:29.767  5419  5419 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 15:52:29.771  5419  5419 D SprintDMHelper: simOperator: 
11-15 15:52:29.771  5419  5419 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 15:52:29.776  3479  3479 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 15:52:29.778  3879  5705 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 15:52:29.782  5036  5708 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-15 15:52:29.783  3879  5705 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-15 15:52:29.784  3879  5705 I SystemUpdateService: now status is 0 (complete)
,11-15 15:52:29.784  3879  5705 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 15:52:29.784  3879  5705 I SystemUpdateService: file has been verified
11-15 15:52:29.784  3879  5705 I SystemUpdateService: OTA package size = 21989297
,11-15 15:52:29.789  3479  3479 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 15:52:29.790  3879  5705 I SystemUpdateService: showing system update notification
,11-15 15:52:29.796   930  3850 I ActivityManager: Start proc 5709:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-15 15:52:29.807   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 15:52:29.809  3879  3879 D SystemUpdateService: onDestroy
,11-15 15:52:29.831  5709  5709 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-15 15:52:29.838   930   941 I ActivityManager: Killing 5076:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-15 15:52:29.892   930  2985 D wifi    : In wifi stop Hal
,11-15 15:52:29.892   930  2985 D wifi    : halHandle = 0x7f73156680, mVM = 0x7f8f74d140, mCls = 0x100a02
11-15 15:52:29.892   930  3478 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 15:52:29.892   930  3478 D WifiHAL : Got a signal to exit!!!
11-15 15:52:29.892   930  3478 I WifiHAL : Exit wifi_event_loop
11-15 15:52:29.893   930  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-15 15:52:29.894   930  2985 E WifiHAL : Event processing terminated
11-15 15:52:29.894   930  2985 D wifi    : In wifi cleaned up handler
11-15 15:52:29.894   930  2985 I WifiHAL : Internal cleanup completed
,11-15 15:52:29.894  5036  5036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 15:52:29.896  4058  4245 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 15:52:29.896  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:29.897  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:29.899  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:29.914   930  3478 D wifi    : set interface wlan0 flags (DOWN)
,11-15 15:52:29.914   930  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 15:52:30.057  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 15:52:30.104  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:30.108   930  3841 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,11-15 15:52:30.108   930  3841 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 15:52:30.119   508   924 D SoftapController: Softap fwReload - Ok
,11-15 15:52:30.119   930   947 D Tethering: InitialState.processMessage what=4
11-15 15:52:30.122   508   924 D CommandListener: Setting iface cfg
,11-15 15:52:30.123   508   924 D CommandListener: Trying to bring down wlan0
11-15 15:52:30.124   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-15 15:52:30.126   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 15:52:30.130   930  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 15:52:30.612   930  3828 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,11-15 15:52:30.615   930  3828 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 15:52:30.741   930  2985 D wifi    : set interface wlan0 flags (UP)
,11-15 15:52:30.742   930  2985 I WifiHAL : Initializing wifi
,11-15 15:52:30.742   930  2985 I WifiHAL : Creating socket
,11-15 15:52:30.743   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-15 15:52:30.752   930  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 15:52:30.752   930  2985 D wifi    : Did set static halHandle = 0x7f73156680
11-15 15:52:30.752   930  2985 D wifi    : halHandle = 0x7f73156680, mVM = 0x7f8f74d140, mCls = 0x20172a
,11-15 15:52:30.752   930  2985 D wifi    : array field set
11-15 15:52:30.753   930  2985 I WifiNative-HAL: interface[0] = wlan0
11-15 15:52:30.755   930  5729 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547391628928
,11-15 15:52:30.755   930  5729 D wifi    : waitForHalEvents called, vm = 0x7f8f74d140, obj = 0x20172a, env = 0x7f70872c80
,11-15 15:52:30.777   508   924 D TetherController: Setting IP forward enable = 0
,11-15 15:52:30.814  5730  5730 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 15:52:30.855   930  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 15:52:30.862  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:30.864  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:30.866  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:30.876  5730  5730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 15:52:30.903  5730  5730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 15:52:30.903  5730  5730 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 15:52:30.915   930  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:30.921  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:30.924  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:30.928  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:30.930  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:30.932   930  2985 D WifiConfigStore: loaded 0 passpoint configs
11-15 15:52:30.932   930  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 15:52:30.932   930  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-15 15:52:30.933   930  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-15 15:52:30.933   930  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-15 15:52:30.933   930  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:30.933  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:30.934   930  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-15 15:52:30.934   930  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-15 15:52:30.934   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 15:52:30.934   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-15 15:52:30.934   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 15:52:30.934   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 15:52:30.934   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-15 15:52:30.935  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:30.936   930  2985 D WifiNative-HAL: Setting external_sim to 1
11-15 15:52:30.936   930  2985 D wifi    : setting dfs flag to true, 0x7f79591bc0
11-15 15:52:30.936   930  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 15:52:30.936  5036  5036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 15:52:30.936   930  2985 D wifi    : setting scan oui 0x7f79591bc0
11-15 15:52:30.936   930  2985 D WifiHAL : Sending mac address OUI
,11-15 15:52:30.939   930  2985 E native  : do suspend false
,11-15 15:52:30.945   930  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-15 15:52:30.945   930   930 D RttService: SCAN_AVAILABLE : 3
11-15 15:52:30.946   930  3099 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 15:52:30.949   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-15 15:52:30.951   508   924 D CommandListener: Setting iface cfg
11-15 15:52:30.953   930  2984 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-15 15:52:30.953   930  2984 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 15:52:30.959   930  2984 D WifiNative-HAL: p2pGetDeviceAddress
,11-15 15:52:30.959   930  2984 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 15:52:30.965   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=105076 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-15 15:52:31.118  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:31.130  4684  4742 D BluetoothAdapterState: Current state: ON, message: 23
,11-15 15:52:31.130  4684  4742 D BluetoothAdapterProperties: Setting state to 13
,11-15 15:52:31.131  4684  4742 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-15 15:52:31.132  4684  4742 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 15:52:31.133  4684  4742 I BluetoothAdapterState: Entering PendingCommandState
,11-15 15:52:31.140  4684  4684 D BluetoothMapService: onReceive
,11-15 15:52:31.140  4684  4684 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 15:52:31.140  4684  4684 D BluetoothMapService: STATE_TURNING_OFF
,11-15 15:52:31.141  4684  4684 D BluetoothMapService: MAP Service closeService in
11-15 15:52:31.141  4684  4684 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 15:52:31.141  4684  4684 D ObexServerSockets0: shutdown(block = true)
,11-15 15:52:31.142  4684  4684 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-15 15:52:31.142  4684  4909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-15 15:52:31.142  4684  4684 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 15:52:31.142  4684  4893 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 15:52:31.142  4684  4910 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-15 15:52:31.144  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:31.144  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:31.145  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:31.145  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:31.148  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:31.148  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:31.150  4684  4684 I BtOppRfcommListener: stopping Accept Thread
11-15 15:52:31.150  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:31.150  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:31.150  4684  5320 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-15 15:52:31.150  4684  5320 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-15 15:52:31.153  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMo,nitor:     - is Bluetooth enabled: false
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:31.153  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:31.154  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:31.154  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:31.161   930   943 I ActivityManager: Start proc 5736:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-15 15:52:31.162  4684  4747 D BluetoothAdapterProperties: Scan Mode:20
11-15 15:52:31.163  4684  4742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-15 15:52:31.167  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:31.168  4684  4684 D HeadsetService: Received stop request...Stopping profile...
11-15 15:52:31.168  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:31.170  3815  4027 D BluetoothHeadset: Proxy object disconnected
11-15 15:52:31.170   930   930 D BluetoothHeadset: Proxy object disconnected
11-15 15:52:31.170  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:31.170   930   930 D BluetoothHeadset: Proxy object disconnected
,11-15 15:52:31.170   930   930 D BluetoothHeadset: Proxy object disconnected
11-15 15:52:31.170  4684  4684 D A2dpService: Received stop request...Stopping profile...
11-15 15:52:31.170  3154  3165 D BluetoothHeadset: Proxy object disconnected
11-15 15:52:31.171  4684  4898 D A2dpStateMachine: Exit Disconnected: -1
11-15 15:52:31.171  3154  3154 D HeadsetProfile: Bluetooth service disconnected
11-15 15:52:31.172   930   930 D BluetoothA2dp: Proxy object disconnected
,11-15 15:52:31.172  3154  3154 D BluetoothA2dp: Proxy object disconnected
11-15 15:52:31.173  4684  4684 D HidService: Received stop request...Stopping profile...
11-15 15:52:31.173  4684  4684 D HidService: Stopping Bluetooth HidService
11-15 15:52:31.174  3154  3154 D BluetoothInputDevice: Proxy object disconnected
11-15 15:52:31.174  3154  3154 D HidProfile: Bluetooth service disconnected
,11-15 15:52:31.176  4684  4684 D HealthService: Received stop request...Stopping profile...
11-15 15:52:31.177  4684  4684 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:31.177  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.177  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.177  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:31.178  4684  4684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-15 15:52:31.178  4684  4684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-15 15:52:31.179  4684  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 15:52:31.179  4684  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:31.179  4684  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:31.179  4684  4684 D PanService: Received stop request...Stopping profile...
11-15 15:52:31.179  4684  4747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 15:52:31.180  4684  4747 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 15:52:31.180  3154  3154 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 15:52:31.180  3154  3154 D PanProfile: Bluetooth service disconnected
11-15 15:52:31.181  4684  4684 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:31.181  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.181  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 15:52:31.181  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:31.182  4684  4684 D BluetoothMapService: Received stop request...Stopping profile...
11-15 15:52:31.182  4684  4684 D BluetoothMapService: stop()
11-15 15:52:31.182  4684  4684 D BluetoothMapAppObserver: deinitObservers()
11-15 15:52:31.182  4684  4684 D BluetoothMapAppObserver: removeReceiver()
11-15 15:52:31.185  3154  3154 D BluetoothMap: Proxy object disconnected
11-15 15:52:31.185  3154  3154 D MapProfile: Bluetooth service disconnected
,11-15 15:52:31.188  4684  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 15:52:31.188  4684  4684 V BluetoothAdapterState: isTurningOff()=true
,11-15 15:52:31.188  4684  4747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 15:52:31.189  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.189  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.189  4684  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:31.189  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:31.189  4684  4891 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-15 15:52:31.189  4684  4891 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-15 15:52:31.189  4684  4891 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 15:52:31.189  4684  4891 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 15:52:31.190  4684  4684 D SapService: Received stop request...Stopping profile...
11-15 15:52:31.190  4684  4684 V SapService: stop()
11-15 15:52:31.191  4684  4684 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-15 15:52:31.192  4684  4684 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 15:52:31.192  4684  4684 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:31.192  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.192  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.192  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:31.192  4684  4684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 15:52:31.192  4684  4747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 15:52:31.193  4684  4684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-15 15:52:31.193  4684  4747 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 15:52:31.193  4684  4684 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:31.194  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.194  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.194  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:31.194  4684  4684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 15:52:31.194  4684  4684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 15:52:31.195  4684  4684 D BluetoothMapService: MAP Service closeService in
11-15 15:52:31.195  4684  4684 V BluetoothAdapterState: isTurningOff()=true
,11-15 15:52:31.195  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.195  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.195  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:31.195  4684  4684 D BluetoothMapService: cleanup()
11-15 15:52:31.195  4684  4684 D BluetoothMapService: MAP Service closeService in
11-15 15:52:31.196  4684  4684 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:31.196  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.196  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.196  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:31.196  4684  4742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 15:52:31.197  4684  4742 D BluetoothAdapterProperties: Setting state to 15
11-15 15:52:31.197  4684  4742 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 15:52:31.197  4684  4742 I BluetoothAdapterState: Entering BleOnState
11-15 15:52:31.197   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 15:52:31.197  3154  3367 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:31.198  3815  3839 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:31.198  3154  3169 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 15:52:31.198   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:31.199  3154  3165 D BluetoothMap: onBluetoothStateChange: up=false
11-15 15:52:31.199  3154  3367 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 15:52:31.200  3154  3169 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 15:52:31.200   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:31.200  3154  3165 D BluetoothPan: onBluetoothStateChange on: false
11-15 15:52:31.201   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:31.201  4684  4742 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 15:52:31.201  4684  4742 D BluetoothAdapterProperties: Setting state to 16
11-15 15:52:31.201  4684  4742 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 15:52:31.202  4684  4742 D BluetoothAdapterProperties: onBleDisable
11-15 15:52:31.202  4684  4742 I BluetoothAdapterState: Entering PendingCommandState
11-15 15:52:31.202  4684  4743 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 15:52:31.203  4684  4747 D BluetoothAdapterProperties: Scan Mode:20
11-15 15:52:31.203  4684  4891 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-15 15:52:31.203  4684  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:31.205  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:31.207  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:31.209  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:31.211  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:31.212  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:31.213  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:31.225  5736  5736 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-15 15:52:31.237  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 15:52:31.242   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8545ada:true
,11-15 15:52:31.242  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 15:52:31.255   930  3449 I ActivityManager: Start proc 5748:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-15 15:52:31.267  5736  5736 D LocalBluetoothProfileManager: Adding local MAP profile
,11-15 15:52:31.270  5736  5736 D BluetoothMap: Create BluetoothMap proxy object
,11-15 15:52:31.288  5736  5736 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-15 15:52:31.294  5748  5748 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-15 15:52:31.304  5736  5736 D DockEventReceiver: finishStartingService: stopping service
,11-15 15:52:31.309   930  3850 I ActivityManager: Killing 5275:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-15 15:52:31.412  4684  4747 I bt_hci  : shut_down
,11-15 15:52:31.417  4684  4751 D bt_hwcfg: hw_epilog_process
,11-15 15:52:31.417  4684  4751 I bt_vendor: low_power_mode_cb
,11-15 15:52:31.419  4684  4751 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-15 15:52:31.419  4684  4751 I bt_vendor: epilog_cb
11-15 15:52:31.419  4684  4751 I bt_hci  : epilog_finished_callback
,11-15 15:52:31.421  4684  4747 I bt_hci_h4: hal_close
,11-15 15:52:31.422  4684  4747 I bt_userial_vendor: device fd = 54 close
,11-15 15:52:31.506  5748  5748 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.506  5748  5748 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.506  5748  5748 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.506  5748  5748 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.506  5748  5748 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:583)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.506  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.507  5748  5748 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.507  5748  5748 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.507  5748  5748 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:52:31.507  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:52:31.510  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 15:52:31.515  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 15:52:31.522  5736  5736 D DockEventReceiver: finishStartingService: stopping service
11-15 15:52:31.526   930  3232 I ActivityManager: Killing 3931:com.android.providers.calendar/u0a1 (adj 15): empty #17
11-15 15:52:31.526  4684  4743 D bt_stack_manager: event_shut_down_stack finished.
11-15 15:52:31.527  4684  4742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 15:52:31.554  4684  4684 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 15:52:31.554  4684  4742 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-15 15:52:31.555  4684  4684 D BtGatt.GattService: Received stop request...Stopping profile...
11-15 15:52:31.555  4684  4684 D BtGatt.GattService: stop()
11-15 15:52:31.555  4684  4684 D BtGatt.AdvertiseManager: advertise clients cleared
11-15 15:52:31.557  4684  4684 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:31.557  4684  4684 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.557  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:31.557  4684  4684 V BluetoothAdapterState: isBleTurningOff()=true
11-15 15:52:31.557  4684  4742 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 15:52:31.557  4684  4742 D BluetoothAdapterProperties: Setting state to 10
11-15 15:52:31.557  4684  4742 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 15:52:31.558  4684  4742 I BluetoothAdapterState: Entering OffState
11-15 15:52:31.558   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-15 15:52:31.565  4684  4684 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-15 15:52:31.565  4684  4684 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 15:52:31.565  4684  4684 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 15:52:31.567  4684  4743 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-15 15:52:31.570  4684  4684 I art     : System.exit called, status: 0
11-15 15:52:31.570  4684  4684 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 15:52:31.623   930  3841 I ActivityManager: Process com.android.bluetooth (pid 4684) has died
,11-15 15:52:31.629  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:31.642   930   947 I ActivityManager: Start proc 5781:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 15:52:31.702  5781  5781 D AdapterServiceConfig: Adding HeadsetService
,11-15 15:52:31.702  5781  5781 D AdapterServiceConfig: Adding A2dpService
11-15 15:52:31.703  5781  5781 D AdapterServiceConfig: Adding HidService
11-15 15:52:31.703  5781  5781 D AdapterServiceConfig: Adding HealthService
11-15 15:52:31.703  5781  5781 D AdapterServiceConfig: Adding PanService
11-15 15:52:31.703  5781  5781 D AdapterServiceConfig: Adding GattService
11-15 15:52:31.703  5781  5781 D AdapterServiceConfig: Adding BluetoothMapService
,11-15 15:52:31.703  5781  5781 D AdapterServiceConfig: Adding SapService
,11-15 15:52:31.714   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c302073:true
,11-15 15:52:31.714  5781  5781 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 15:52:31.717  5781  5781 I bt_bluedroid: init
,11-15 15:52:31.717  5781  5793 I BluetoothAdapterState: Entering OffState
,11-15 15:52:31.719  5781  5794 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 15:52:31.719  5781  5794 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 15:52:31.719  5781  5794 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 15:52:31.719  5781  5794 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 15:52:31.719  5781  5781 I bt_bluedroid: get_profile_interface socket
,11-15 15:52:31.721  5781  5781 I bt_bluedroid: get_profile_interface sdp
,11-15 15:52:31.721  5781  5797 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 15:52:31.723  5781  5797 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 15:52:31.726  5781  5792 I bt_bluedroid: config_hci_snoop_log
,11-15 15:52:31.726   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-15 15:52:31.730  5781  5793 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 15:52:31.730  5781  5793 D BluetoothAdapterProperties: Setting state to 14
,11-15 15:52:31.730  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-15 15:52:31.731  5781  5793 D BluetoothBondStateMachine: make
11-15 15:52:31.732  5781  5798 I BluetoothBondStateMachine: StableState(): Entering Off State
11-15 15:52:31.735  5781  5793 I BluetoothAdapterState: Entering PendingCommandState
,11-15 15:52:31.735  5748  5767 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-15 15:52:31.736  5781  5781 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-15 15:52:31.738  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:31.739  5781  5781 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 15:52:31.739  5781  5781 D BtGatt.GattService: Received start request. Starting profile...
11-15 15:52:31.740  5781  5781 D BtGatt.GattService: start()
11-15 15:52:31.740  5781  5781 I bt_bluedroid: get_profile_interface gatt
,11-15 15:52:31.740  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:31.741  5781  5781 D BtGatt.AdvertiseManager: advertise manager created
,11-15 15:52:31.745  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:31.745  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:31.745  5781  5781 V BluetoothAdapterState: isBleTurningOn()=true
11-15 15:52:31.746  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:31.746  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 15:52:31.747  5781  5793 I bt_bluedroid: bt_bluedroid
11-15 15:52:31.747  5781  5794 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-15 15:52:31.748  5781  5794 I bt_hci  : start_up
,11-15 15:52:31.748   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d011048:true
,11-15 15:52:31.752  5781  5794 I bt_vendor: alloc value 0xf3d0d871
,11-15 15:52:31.752  5781  5794 I bt_vendor: init
11-15 15:52:31.752  5781  5794 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 15:52:31.752  5781  5794 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 15:52:31.861  5781  5794 D bt_hci  : start_up starting async portion
,11-15 15:52:31.862  5781  5802 I bt_hci  : event_finish_startup
11-15 15:52:31.862  5781  5802 I bt_hci_h4: hal_open
11-15 15:52:31.862  5781  5802 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 15:52:31.861  5804  5804 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 15:52:31.865  5781  5802 I bt_userial_vendor: device fd = 54 open
,11-15 15:52:31.877  5781  5802 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 15:52:31.879  5781  5802 D bt_hwcfg: Chipset BCM4358A3
,11-15 15:52:31.879  5781  5802 D bt_hwcfg: Target name = [BCM4358A3]
11-15 15:52:31.879  5781  5802 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 15:52:32.137  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-15 15:52:32.258  5781  5802 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-15 15:52:32.258  5781  5802 D bt_hwcfg: Settlement delay -- 100 ms
11-15 15:52:32.258  5781  5802 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 15:52:32.381  5781  5802 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 15:52:32.381  5781  5802 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 15:52:32.383  5781  5802 I bt_hwcfg: vendor lib fwcfg completed
,11-15 15:52:32.383  5781  5802 I bt_vendor: firmware callback
,11-15 15:52:32.383  5781  5802 I bt_hci  : firmware_config_callback
,11-15 15:52:32.391  5781  5806 I bt_btu  : btu_task pending for preload complete event
11-15 15:52:32.391  5781  5806 I bt_btu_task: Bluetooth chip preload is complete
,11-15 15:52:32.391  5781  5806 I bt_btu  : btu_task received preload complete event
,11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_AVRC
11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_A2D
,11-15 15:52:32.399  5781  5806 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_PAN
,11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_GATT
11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-15 15:52:32.400  5781  5806 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 15:52:32.487  5781  5806 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c8b549
,11-15 15:52:32.488  5781  5806 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c8b549 
,11-15 15:52:32.503  5781  5797 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 15:52:32.505  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 15:52:32.505  5781  5797 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 15:52:32.507  5781  5797 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 15:52:32.510  5781  5797 D BluetoothAdapterProperties: Scan Mode:20
,11-15 15:52:32.511  5781  5797 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 15:52:32.511  5781  5797 D bt_hci  : do_postload posting postload work item
11-15 15:52:32.511  5781  5802 I bt_hci  : event_postload
11-15 15:52:32.511  5781  5802 I bt_vendor: sco_config_cb
,11-15 15:52:32.511  5781  5802 I bt_hci  : sco_config_callback postload finished.
,11-15 15:52:32.516  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.517  5781  5797 D bt_bte_conf: Device ID record 1 : primary
11-15 15:52:32.517  5781  5797 D bt_bte_conf:   vendorId            = 000f
,11-15 15:52:32.517  5781  5797 D bt_bte_conf:   vendorIdSource      = 0001
11-15 15:52:32.517  5781  5797 D bt_bte_conf:   product             = 1200
11-15 15:52:32.517  5781  5797 D bt_bte_conf:   version             = 1436
11-15 15:52:32.517  5781  5797 D bt_bte_conf:   clientExecutableURL = 
11-15 15:52:32.518  5781  5797 D bt_bte_conf:   serviceDescription  = 
11-15 15:52:32.518  5781  5797 D bt_bte_conf:   documentationURL    = 
11-15 15:52:32.518  5781  5797 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 15:52:32.519  5781  5794 D bt_stack_manager: event_start_up_stack finished
11-15 15:52:32.520  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 15:52:32.521  5781  5793 D BluetoothAdapterProperties: Setting state to 15
,11-15 15:52:32.521  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 15:52:32.521  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.521  5781  5793 I BluetoothAdapterState: Entering BleOnState
11-15 15:52:32.523  5781  5802 I bt_vendor: low_power_mode_cb
,11-15 15:52:32.527  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.528  5781  5793 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 15:52:32.528  5781  5793 D BluetoothAdapterProperties: Setting state to 11
11-15 15:52:32.528  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-15 15:52:32.532  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:32.533  5781  5781 D HeadsetService: Received start request. Starting profile...
,11-15 15:52:32.536  5781  5781 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-15 15:52:32.536  5781  5781 D HeadsetStateMachine: make
,11-15 15:52:32.541  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.543  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.545  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.551  5781  5781 D HeadsetStateMachine: max_hf_connections = 1
11-15 15:52:32.551  5781  5781 I bt_bluedroid: get_profile_interface handsfree
11-15 15:52:32.552  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-15 15:52:32.553  5781  5797 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 15:52:32.553  5781  5793 I BluetoothAdapterState: Entering PendingCommandState
,11-15 15:52:32.555  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:32.556  5781  5781 D A2dpService: Received start request. Starting profile...
11-15 15:52:32.557  5781  5781 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-15 15:52:32.557  5781  5781 I bt_bluedroid: get_profile_interface avrcp
,11-15 15:52:32.562  5781  5781 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 15:52:32.562  5781  5781 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 15:52:32.562  5781  5781 D A2dpStateMachine: make
,11-15 15:52:32.563  5781  5781 I bt_bluedroid: get_profile_interface a2dp
,11-15 15:52:32.564  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-15 15:52:32.566  5781  5815 D A2dpStateMachine: Enter Disconnected: -2
11-15 15:52:32.566  5781  5781 I BluetoothHidServiceJni: classInitNative: succeeds
11-15 15:52:32.567  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:32.569  5781  5781 D HidService: Received start request. Starting profile...
,11-15 15:52:32.569  5781  5781 I bt_bluedroid: get_profile_interface hidhost
11-15 15:52:32.569  5781  5797 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c6c56d
11-15 15:52:32.569  5781  5781 D HidService: setHidService(): set to: null
11-15 15:52:32.570  5736  5736 D BluetoothInputDevice: Proxy object connected
11-15 15:52:32.570  5781  5781 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 15:52:32.570  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 15:52:32.570  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:32.570  5736  5736 D HidProfile: Bluetooth service connected
11-15 15:52:32.572  5781  5781 D HealthService: Received start request. Starting profile...
,11-15 15:52:32.573  5781  5781 I bt_bluedroid: get_profile_interface health
,11-15 15:52:32.575  5781  5781 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-15 15:52:32.575  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:32.576  5736  5736 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 15:52:32.576  5781  5781 D PanService: Received start request. Starting profile...
11-15 15:52:32.577  5736  5736 D PanProfile: Bluetooth service connected
11-15 15:52:32.577  5781  5781 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 15:52:32.577  5781  5781 I bt_bluedroid: get_profile_interface pan
11-15 15:52:32.577  5781  5797 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-15 15:52:32.580  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:32.581  5781  5781 D BluetoothMapService: Received start request. Starting profile...
11-15 15:52:32.581  5781  5781 D BluetoothMapService: start()
11-15 15:52:32.581  5736  5736 D BluetoothMap: Proxy object connected
11-15 15:52:32.581  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 15:52:32.582  5736  5736 D MapProfile: Bluetooth service connected
11-15 15:52:32.582  5736  5736 D BluetoothMap: getConnectedDevices()
,11-15 15:52:32.583  5736  5736 D BluetoothMap: Bluetooth is Not enabled
,11-15 15:52:32.585  5781  5781 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-15 15:52:32.586  5781  5781 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-15 15:52:32.586  5781  5781 D BluetoothMapAppObserver: createReceiver()
,11-15 15:52:32.587  5781  5781 D BluetoothMapAppObserver: initObservers()
,11-15 15:52:32.587  5781  5781 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-15 15:52:32.594  5781  5781 V SapService: SapBinder()
,11-15 15:52:32.595  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:32.595  5781  5781 D SapService: Received start request. Starting profile...
11-15 15:52:32.595  5781  5781 V SapService: start()
,11-15 15:52:32.596  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.596  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 15:52:32.597  5781  5812 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isTurningOn()=true
,11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.597  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.598  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.599  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.599  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:32.599  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.599  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:32.600  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:32.600  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:32.600  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.600  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:32.600  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-15 15:52:32.600  5781  5793 D BluetoothAdapterProperties: ScanMode =  20
11-15 15:52:32.600  5781  5793 D BluetoothAdapterProperties: State =  11
11-15 15:52:32.601  5781  5797 D BluetoothAdapterProperties: Scan Mode:21
11-15 15:52:32.601  5781  5797 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 15:52:32.602  5781  5793 D BluetoothAdapterProperties: Setting state to 12
11-15 15:52:32.602  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 15:52:32.602  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 15:52:32.602   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 15:52:32.603  5781  5793 I BluetoothAdapterState: Entering OnState
11-15 15:52:32.604  3154  3169 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:32.604  3815  3838 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:32.605  5618  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-15 15:52:32.605  3154  3165 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 15:52:32.606   930   930 D BluetoothA2dp: Proxy object connected
,11-15 15:52:32.607  5618  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:32.611  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:32.611  3154  3154 D BluetoothA2dp: Proxy object connected
,11-15 15:52:32.612  5736  5746 D BluetoothMap: onBluetoothStateChange: up=true
11-15 15:52:32.612   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 15:52:32.613  3154  3367 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 15:52:32.614  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:32.615  3154  3154 D BluetoothMap: Proxy object connected
11-15 15:52:32.615  5781  5781 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 15:52:32.615  3154  3154 D MapProfile: Bluetooth service connected
11-15 15:52:32.615  3154  3154 D BluetoothMap: getConnectedDevices()
11-15 15:52:32.615  5736  5747 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 15:52:32.615  5781  5781 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 15:52:32.616  3154  3169 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 15:52:32.617  5781  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:32.617  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:32.618  3154  3165 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-15 15:52:32.620  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:32.620   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:32.620  5781  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:32.621  3154  3154 D BluetoothInputDevice: Proxy object connected
11-15 15:52:32.621  3154  3154 D HidProfile: Bluetooth service connected
11-15 15:52:32.621  3154  3165 D BluetoothPan: onBluetoothStateChange on: true
11-15 15:52:32.622  3154  3154 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 15:52:32.622  5736  5746 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 15:52:32.622  3154  3154 D PanProfile: Bluetooth service connected
11-15 15:52:32.622   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:32.622  5736  5747 D BluetoothPan: onBluetoothStateChange on: true
11-15 15:52:32.622  5781  5781 D ObexServerSockets: Succeed to create listening sockets 
11-15 15:52:32.623  5781  5781 D ObexServerSockets0: startAccept()
11-15 15:52:32.623  5781  5781 D ObexServerSockets0: prepareForNewConnect()
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:32.623  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:32.625  5781  5781 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 15:52:32.625  5781  5781 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-15 15:52:32.625   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 15:52:32.625  5781  5781 D BluetoothMapService: onReceive
11-15 15:52:32.625  5781  5781 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-15 15:52:32.625  5781  5781 D BluetoothMapService: STATE_ON
11-15 15:52:32.626  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:32.626  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 15:52:32.627  5781  5821 D ObexServerSockets0: Accepting socket connection...
,11-15 15:52:32.627  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.628  5736  5736 D LocalBluetoothProfileManager: Adding local A2DP profile
11-15 15:52:32.629  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.629  5781  5820 D ObexServerSockets0: Accepting socket connection...
11-15 15:52:32.632  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.633  5781  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:32.633  5736  5736 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-15 15:52:32.634  5781  5823 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-15 15:52:32.634  5781  5823 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-15 15:52:32.638  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.639  5618  5665 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 15:52:32.639  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-15 15:52:32.639  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 15:52:32.641  5618  5665 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-15 15:52:32.641  5618  5665 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-15 15:52:32.641  5736  5736 D BluetoothA2dp: Proxy object connected
,11-15 15:52:32.643  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.645  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 15:52:32.645  5781  5793 D BluetoothAdapterState: Current state: ON, message: 23
11-15 15:52:32.645  5781  5793 D BluetoothAdapterProperties: Setting state to 13
11-15 15:52:32.645  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-15 15:52:32.646  5781  5793 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 15:52:32.646  5781  5793 I BluetoothAdapterState: Entering PendingCommandState
,11-15 15:52:32.649  5781  5797 D BluetoothAdapterProperties: Scan Mode:20
,11-15 15:52:32.650  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-15 15:52:32.650  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:32.650  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:32.651  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 15:52:32.651  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:32.653  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:32.653  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:32.654  5736  5736 D DockEventReceiver: finishStartingService: stopping service
11-15 15:52:32.654  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 15:52:32.654  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:32.656  5781  5781 D BluetoothMapService: onReceive
11-15 15:52:32.656  3154  3154 D BluetoothPbap: Proxy object connected
11-15 15:52:32.656  5781  5781 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 15:52:32.656  3154  3154 D PbapServerProfile: Bluetooth service connected
11-15 15:52:32.656  5781  5781 D BluetoothMapService: STATE_TURNING_OFF
11-15 15:52:32.657  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.657  5736  5736 D BluetoothPbap: Proxy object connected
11-15 15:52:32.658  5736  5736 D PbapServerProfile: Bluetooth service connected
11-15 15:52:32.659  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.662  5781  5781 D HeadsetService: Received stop request...Stopping profile...
,11-15 15:52:32.666  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 15:52:32.666  5781  5781 D A2dpService: Received stop request...Stopping profile...
11-15 15:52:32.666  5781  5815 D A2dpStateMachine: Exit Disconnected: -1
,11-15 15:52:32.669   930   930 D BluetoothA2dp: Proxy object disconnected
11-15 15:52:32.670  5781  5781 D HidService: Received stop request...Stopping profile...
11-15 15:52:32.670  5781  5781 D HidService: Stopping Bluetooth HidService
,11-15 15:52:32.670  5736  5736 D BluetoothA2dp: Proxy object disconnected
11-15 15:52:32.672  3154  3154 D BluetoothA2dp: Proxy object disconnected
11-15 15:52:32.672  3154  3154 D BluetoothInputDevice: Proxy object disconnected
,11-15 15:52:32.672  3154  3154 D HidProfile: Bluetooth service disconnected
11-15 15:52:32.673  5781  5781 D HealthService: Received stop request...Stopping profile...
,11-15 15:52:32.675  5781  5781 D PanService: Received stop request...Stopping profile...
,11-15 15:52:32.675  5736  5736 D DockEventReceiver: finishStartingService: stopping service
11-15 15:52:32.676  3154  3154 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 15:52:32.676  3154  3154 D PanProfile: Bluetooth service disconnected
11-15 15:52:32.676  5736  5736 D BluetoothInputDevice: Proxy object disconnected
11-15 15:52:32.676  5736  5736 D HidProfile: Bluetooth service disconnected
11-15 15:52:32.676  5736  5736 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 15:52:32.676  5736  5736 D PanProfile: Bluetooth service disconnected
11-15 15:52:32.677  5781  5781 D BluetoothMapService: Received stop request...Stopping profile...
11-15 15:52:32.677  5781  5781 D BluetoothMapService: stop()
,11-15 15:52:32.678  5781  5781 D BluetoothMapAppObserver: deinitObservers()
,11-15 15:52:32.678  5781  5781 D BluetoothMapAppObserver: removeReceiver()
11-15 15:52:32.679  3154  3154 D BluetoothMap: Proxy object disconnected
11-15 15:52:32.679  3154  3154 D MapProfile: Bluetooth service disconnected
11-15 15:52:32.679  5736  5736 D BluetoothMap: Proxy object disconnected
11-15 15:52:32.679  5736  5736 D MapProfile: Bluetooth service disconnected
11-15 15:52:32.679  5781  5781 D SapService: Received stop request...Stopping profile...
11-15 15:52:32.679  5781  5781 V SapService: stop()
,11-15 15:52:32.691  5781  5781 V BluetoothAdapterState: isTurningOff()=true
,11-15 15:52:32.691  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.691  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.691  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:32.692  5781  5781 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-15 15:52:32.692  5781  5781 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-15 15:52:32.693  5781  5806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:32.693  5781  5781 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:32.693  5781  5806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:32.693  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.693  5781  5806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:32.693  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.693  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.693  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 15:52:32.693  5781  5797 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,11-15 15:52:32.697  5781  5781 V BluetoothAdapterState: isTurningOff()=true
,11-15 15:52:32.697  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.697  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.697  5781  5806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:32.697  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.697  5781  5806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:32.697  5781  5806 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 15:52:32.697  5781  5806 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 15:52:32.697  5781  5806 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 15:52:32.697  5781  5806 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 15:52:32.697  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 15:52:32.698  5781  5781 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 15:52:32.698  5781  5781 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 15:52:32.698  5781  5781 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:32.698  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.698  5781  5797 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 15:52:32.698  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 15:52:32.698  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.698  5781  5781 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 15:52:32.699  5781  5797 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 15:52:32.699  5781  5781 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 15:52:32.699  5781  5781 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:32.699  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.699  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.699  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.700  5781  5781 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 15:52:32.700  5781  5781 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 15:52:32.701  5781  5781 D BluetoothMapService: MAP Service closeService in
11-15 15:52:32.701  5781  5781 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 15:52:32.701  5781  5781 D ObexServerSockets0: shutdown(block = true)
11-15 15:52:32.701  5781  5820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-15 15:52:32.701  5781  5781 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 15:52:32.702  5781  5808 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 15:52:32.702  5781  5781 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 15:52:32.702  5781  5821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 15:52:32.702  5781  5781 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:32.702  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.702  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 15:52:32.702  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 15:52:32.703  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:32.704  5781  5781 D BluetoothMapService: cleanup()
11-15 15:52:32.704  5781  5781 D BluetoothMapService: MAP Service closeService in
,11-15 15:52:32.705  5781  5781 V BluetoothAdapterState: isTurningOff()=true
11-15 15:52:32.705  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:32.705  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:32.705  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:32.705  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 15:52:32.705  5781  5793 D BluetoothAdapterProperties: Setting state to 15
,11-15 15:52:32.705  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 15:52:32.706  5781  5793 I BluetoothAdapterState: Entering BleOnState
11-15 15:52:32.707  3154  3154 D BluetoothPbap: Proxy object disconnected
11-15 15:52:32.707  3154  3154 D PbapServerProfile: Bluetooth service disconnected
,11-15 15:52:32.709  5736  5736 D BluetoothPbap: Proxy object disconnected
,11-15 15:52:32.709  5736  5736 D PbapServerProfile: Bluetooth service disconnected
11-15 15:52:32.710   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 15:52:32.710  3154  3367 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:32.711  3815  4027 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 15:52:32.715  5736  5747 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:32.715  3154  3165 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 15:52:32.716  5736  5828 D BluetoothMap: onBluetoothStateChange: up=false
11-15 15:52:32.716   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:32.717  3154  3169 D BluetoothMap: onBluetoothStateChange: up=false
11-15 15:52:32.717  5736  5746 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 15:52:32.718  3154  3367 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 15:52:32.718  3154  3165 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 15:52:32.719   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 15:52:32.720  3154  3169 D BluetoothPan: onBluetoothStateChange on: false
11-15 15:52:32.720  5736  5747 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 15:52:32.720   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 15:52:32.720  5736  5828 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 15:52:32.721  5736  5746 D BluetoothPan: onBluetoothStateChange on: false
11-15 15:52:32.721  5781  5793 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 15:52:32.721  5781  5793 D BluetoothAdapterProperties: Setting state to 16
,11-15 15:52:32.721  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 15:52:32.722  5781  5793 D BluetoothAdapterProperties: onBleDisable
11-15 15:52:32.722  5781  5793 I BluetoothAdapterState: Entering PendingCommandState
11-15 15:52:32.722  5781  5794 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 15:52:32.724  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 15:52:32.724  5781  5806 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 15:52:32.725  5781  5806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 15:52:32.725  5781  5797 D BluetoothAdapterProperties: Scan Mode:20
11-15 15:52:32.726  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.728  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:32.729  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 15:52:32.730  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.732  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:32.735  5736  5736 D DockEventReceiver: finishStartingService: stopping service
,11-15 15:52:32.925  5781  5797 I bt_hci  : shut_down
,11-15 15:52:32.926  5781  5802 D bt_hwcfg: hw_epilog_process
11-15 15:52:32.927  5781  5802 I bt_vendor: low_power_mode_cb
,11-15 15:52:32.930  5781  5802 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-15 15:52:32.930  5781  5802 I bt_vendor: epilog_cb
11-15 15:52:32.931  5781  5802 I bt_hci  : epilog_finished_callback
,11-15 15:52:32.932  5781  5797 I bt_hci_h4: hal_close
11-15 15:52:32.933  5781  5797 I bt_userial_vendor: device fd = 54 close
,11-15 15:52:33.055  5781  5794 D bt_stack_manager: event_shut_down_stack finished.
,11-15 15:52:33.056  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-15 15:52:33.060  5781  5793 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-15 15:52:33.060  5781  5781 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 15:52:33.061  5781  5781 D BtGatt.GattService: Received stop request...Stopping profile...
11-15 15:52:33.061  5781  5781 D BtGatt.GattService: stop()
11-15 15:52:33.062  5781  5781 D BtGatt.AdvertiseManager: advertise clients cleared
,11-15 15:52:33.065  5781  5781 V BluetoothAdapterState: isTurningOff()=false
,11-15 15:52:33.066  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:33.066  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:33.066  5781  5781 V BluetoothAdapterState: isBleTurningOff()=true
,11-15 15:52:33.066  5781  5793 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 15:52:33.067  5781  5793 D BluetoothAdapterProperties: Setting state to 10
,11-15 15:52:33.067  5781  5793 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 15:52:33.069  5781  5793 I BluetoothAdapterState: Entering OffState
11-15 15:52:33.070   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-15 15:52:33.085  5781  5781 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-15 15:52:33.085  5781  5781 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 15:52:33.086  5781  5781 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 15:52:33.089  5781  5794 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 15:52:33.098  5781  5781 I art     : System.exit called, status: 0
,11-15 15:52:33.098  5781  5781 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 15:52:33.138   930  3190 I ActivityManager: Process com.android.bluetooth (pid 5781) has died
,11-15 15:52:33.144  5618  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:33.144  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:33.144  5618  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 15:52:33.144  5618  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:33.145  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:33.158   930   947 I ActivityManager: Start proc 5836:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 15:52:33.217  5836  5836 D AdapterServiceConfig: Adding HeadsetService
,11-15 15:52:33.217  5836  5836 D AdapterServiceConfig: Adding A2dpService
11-15 15:52:33.217  5836  5836 D AdapterServiceConfig: Adding HidService
11-15 15:52:33.218  5836  5836 D AdapterServiceConfig: Adding HealthService
11-15 15:52:33.218  5836  5836 D AdapterServiceConfig: Adding PanService
,11-15 15:52:33.218  5836  5836 D AdapterServiceConfig: Adding GattService
11-15 15:52:33.218  5836  5836 D AdapterServiceConfig: Adding BluetoothMapService
11-15 15:52:33.219  5836  5836 D AdapterServiceConfig: Adding SapService
,11-15 15:52:33.230   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e44508:true
,11-15 15:52:33.231  5836  5836 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 15:52:33.233  5836  5836 I bt_bluedroid: init
11-15 15:52:33.233  5836  5848 I BluetoothAdapterState: Entering OffState
,11-15 15:52:33.235  5836  5849 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 15:52:33.235  5836  5849 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 15:52:33.235  5836  5849 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 15:52:33.235  5836  5849 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 15:52:33.235  5836  5836 I bt_bluedroid: get_profile_interface socket
,11-15 15:52:33.237  5836  5836 I bt_bluedroid: get_profile_interface sdp
,11-15 15:52:33.237  5836  5852 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 15:52:33.238  5836  5852 D BluetoothAdapterProperties: Name is: Nexus 6P
11-15 15:52:33.241  5836  5847 I bt_bluedroid: config_hci_snoop_log
,11-15 15:52:33.242   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 15:52:33.245  5836  5848 D BluetoothAdapterState: Current state: OFF, message: 0
11-15 15:52:33.245  5836  5848 D BluetoothAdapterProperties: Setting state to 14
11-15 15:52:33.245  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-15 15:52:33.247  5836  5848 D BluetoothBondStateMachine: make
,11-15 15:52:33.248  5836  5853 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 15:52:33.251  5836  5848 I BluetoothAdapterState: Entering PendingCommandState
,11-15 15:52:33.252  5836  5836 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 15:52:33.254  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:33.254  5836  5836 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 15:52:33.255  5836  5836 D BtGatt.GattService: Received start request. Starting profile...
11-15 15:52:33.255  5836  5836 D BtGatt.GattService: start()
11-15 15:52:33.255  5836  5836 I bt_bluedroid: get_profile_interface gatt
,11-15 15:52:33.256  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:33.256  5836  5836 D BtGatt.AdvertiseManager: advertise manager created
,11-15 15:52:33.260  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:33.260  5836  5836 V BluetoothAdapterState: isTurningOn()=false
11-15 15:52:33.260  5836  5836 V BluetoothAdapterState: isBleTurningOn()=true
11-15 15:52:33.260  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:33.260  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 15:52:33.261  5836  5848 I bt_bluedroid: bt_bluedroid
,11-15 15:52:33.261  5836  5849 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-15 15:52:33.262  5836  5849 I bt_hci  : start_up
,11-15 15:52:33.266  5836  5849 I bt_vendor: alloc value 0xf3d0d871
11-15 15:52:33.266  5836  5849 I bt_vendor: init
11-15 15:52:33.266  5836  5849 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 15:52:33.267  5836  5849 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 15:52:33.377  5836  5849 D bt_hci  : start_up starting async portion
,11-15 15:52:33.377  5836  5856 I bt_hci  : event_finish_startup
11-15 15:52:33.377  5836  5856 I bt_hci_h4: hal_open
11-15 15:52:33.377  5836  5856 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 15:52:33.374  5857  5857 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 15:52:33.382  5836  5856 I bt_userial_vendor: device fd = 54 open
,11-15 15:52:33.396  5836  5856 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 15:52:33.399  5836  5856 D bt_hwcfg: Chipset BCM4358A3
,11-15 15:52:33.399  5836  5856 D bt_hwcfg: Target name = [BCM4358A3]
,11-15 15:52:33.399  5836  5856 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 15:52:33.652  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-15 15:52:33.782  5836  5856 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-15 15:52:33.783  5836  5856 D bt_hwcfg: Settlement delay -- 100 ms
11-15 15:52:33.783  5836  5856 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 15:52:33.906  5836  5856 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 15:52:33.906  5836  5856 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 15:52:33.908  5836  5856 I bt_hwcfg: vendor lib fwcfg completed
,11-15 15:52:33.908  5836  5856 I bt_vendor: firmware callback
11-15 15:52:33.908  5836  5856 I bt_hci  : firmware_config_callback
11-15 15:52:33.916  5836  5859 I bt_btu  : btu_task pending for preload complete event
,11-15 15:52:33.916  5836  5859 I bt_btu_task: Bluetooth chip preload is complete
,11-15 15:52:33.916  5836  5859 I bt_btu  : btu_task received preload complete event
,11-15 15:52:33.924  5836  5859 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 15:52:33.924  5836  5859 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 15:52:33.924  5836  5859 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-15 15:52:33.924  5836  5859 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_A2D
11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_PAN
11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 15:52:33.925  5836  5859 I         : BTE_InitTraceLevels -- TRC_GATT
,11-15 15:52:33.926  5836  5859 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 15:52:33.926  5836  5859 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-15 15:52:33.926  5836  5859 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 15:52:34.008  5836  5859 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c8b549
11-15 15:52:34.008  5836  5859 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c8b549 
,11-15 15:52:34.028  5836  5852 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 15:52:34.029  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 15:52:34.030  5836  5852 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 15:52:34.032  5836  5852 D BluetoothAdapterProperties: Name is: Nexus 6P
11-15 15:52:34.034  5836  5852 D BluetoothAdapterProperties: Scan Mode:20
11-15 15:52:34.035  5836  5852 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 15:52:34.035  5836  5852 D bt_hci  : do_postload posting postload work item
11-15 15:52:34.035  5836  5856 I bt_hci  : event_postload
,11-15 15:52:34.035  5836  5856 I bt_vendor: sco_config_cb
11-15 15:52:34.035  5836  5856 I bt_hci  : sco_config_callback postload finished.
11-15 15:52:34.037  5836  5852 D bt_bte_conf: Device ID record 1 : primary
11-15 15:52:34.037  5836  5852 D bt_bte_conf:   vendorId            = 000f
11-15 15:52:34.037  5836  5852 D bt_bte_conf:   vendorIdSource      = 0001
11-15 15:52:34.037  5836  5852 D bt_bte_conf:   product             = 1200
11-15 15:52:34.037  5836  5852 D bt_bte_conf:   version             = 1436
11-15 15:52:34.038  5836  5852 D bt_bte_conf:   clientExecutableURL = 
11-15 15:52:34.038  5836  5852 D bt_bte_conf:   serviceDescription  = 
11-15 15:52:34.038  5836  5852 D bt_bte_conf:   documentationURL    = 
11-15 15:52:34.038  5836  5852 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 15:52:34.038  5836  5849 D bt_stack_manager: event_start_up_stack finished
11-15 15:52:34.039  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 15:52:34.039  5836  5848 D BluetoothAdapterProperties: Setting state to 15
11-15 15:52:34.040  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 15:52:34.040  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:34.040  5836  5848 I BluetoothAdapterState: Entering BleOnState
11-15 15:52:34.043  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:34.047  5836  5856 I bt_vendor: low_power_mode_cb
11-15 15:52:34.047  5836  5848 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 15:52:34.047  5836  5848 D BluetoothAdapterProperties: Setting state to 11
11-15 15:52:34.047  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-15 15:52:34.049  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 15:52:34.052  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 15:52:34.054  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:34.056  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-15 15:52:34.058  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:34.060  3815  4027 D BluetoothHeadset: Proxy object connected
11-15 15:52:34.060  5836  5836 D HeadsetService: Received start request. Starting profile...
11-15 15:52:34.061   930   930 D BluetoothHeadset: Proxy object connected
,11-15 15:52:34.062  5736  5746 D BluetoothHeadset: Proxy object connected
,11-15 15:52:34.062  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:34.063   930   930 D BluetoothHeadset: Proxy object connected
11-15 15:52:34.063   930   930 D BluetoothHeadset: Proxy object connected
11-15 15:52:34.064  3154  3367 D BluetoothHeadset: Proxy object connected
,11-15 15:52:34.066  5736  5736 D HeadsetProfile: Bluetooth service connected
11-15 15:52:34.066  5836  5836 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 15:52:34.066  5836  5836 D HeadsetStateMachine: make
11-15 15:52:34.066  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-15 15:52:34.069  5836  5848 I BluetoothAdapterState: Entering PendingCommandState
,11-15 15:52:34.073  3154  3154 D HeadsetProfile: Bluetooth service connected
,11-15 15:52:34.075  5836  5836 D HeadsetStateMachine: max_hf_connections = 1
11-15 15:52:34.075  5836  5836 I bt_bluedroid: get_profile_interface handsfree
11-15 15:52:34.075  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-15 15:52:34.078  5836  5852 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 15:52:34.080  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:34.081  5836  5836 D A2dpService: Received start request. Starting profile...
11-15 15:52:34.081  5836  5836 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-15 15:52:34.081  5836  5836 I bt_bluedroid: get_profile_interface avrcp
11-15 15:52:34.087  5836  5836 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-15 15:52:34.087  5836  5836 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 15:52:34.087  5836  5836 D A2dpStateMachine: make
11-15 15:52:34.088  5836  5836 I bt_bluedroid: get_profile_interface a2dp
11-15 15:52:34.089  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-15 15:52:34.091  5836  5868 D A2dpStateMachine: Enter Disconnected: -2
,11-15 15:52:34.091  5836  5836 I BluetoothHidServiceJni: classInitNative: succeeds
11-15 15:52:34.092  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:34.093  5836  5836 D HidService: Received start request. Starting profile...
11-15 15:52:34.093  5836  5836 I bt_bluedroid: get_profile_interface hidhost
11-15 15:52:34.093  5836  5836 D HidService: setHidService(): set to: null
11-15 15:52:34.093  5836  5852 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c6c56d
11-15 15:52:34.093  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 15:52:34.094  5836  5836 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 15:52:34.094  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:34.095  5836  5836 D HealthService: Received start request. Starting profile...
11-15 15:52:34.096  5836  5836 I bt_bluedroid: get_profile_interface health
11-15 15:52:34.098  5836  5836 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-15 15:52:34.099  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
11-15 15:52:34.099  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 15:52:34.099  5836  5836 D PanService: Received start request. Starting profile...
11-15 15:52:34.099  5836  5836 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 15:52:34.099  5836  5836 I bt_bluedroid: get_profile_interface pan
11-15 15:52:34.100  5836  5852 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-15 15:52:34.100   930  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-15 15:52:34.101   930  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-15 15:52:34.101   930  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-15 15:52:34.102  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:34.103  5836  5836 D BluetoothMapService: Received start request. Starting profile...
11-15 15:52:34.103  5836  5836 D BluetoothMapService: start()
,11-15 15:52:34.105  5836  5836 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-15 15:52:34.106  5836  5836 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 15:52:34.106  5836  5836 D BluetoothMapAppObserver: createReceiver()
,11-15 15:52:34.108  5836  5836 D BluetoothMapAppObserver: initObservers()
,11-15 15:52:34.108  5836  5836 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-15 15:52:34.110   930  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 15:52:34.115  5836  5836 V SapService: SapBinder()
11-15 15:52:34.115  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:34.115  5836  5836 D SapService: Received start request. Starting profile...
11-15 15:52:34.116  5836  5836 V SapService: start()
,11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isTurningOff()=false
,11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:34.118  5836  5866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:34.118  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isTurningOn()=true
,11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:34.119  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isTurningOff()=false
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isTurningOn()=true
11-15 15:52:34.120  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
11-15 15:52:34.121  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 15:52:34.121  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 15:52:34.121  5836  5848 D BluetoothAdapterProperties: ScanMode =  20
11-15 15:52:34.121  5836  5848 D BluetoothAdapterProperties: State =  11
11-15 15:52:34.122  5836  5852 D BluetoothAdapterProperties: Scan Mode:21
11-15 15:52:34.122  5836  5852 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 15:52:34.122  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 15:52:34.124  5836  5848 D BluetoothAdapterProperties: Setting state to 12
11-15 15:52:34.124  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:34.124  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 15:52:34.124   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-15 15:52:34.125  3154  3367 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 15:52:34.125  3815  3838 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:34.125   930   930 D BluetoothA2dp: Proxy object connected
11-15 15:52:34.125  5836  5848 I BluetoothAdapterState: Entering OnState
11-15 15:52:34.126  5736  5747 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:34.126  3154  3169 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:34.127  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:34.128  3154  3154 D BluetoothA2dp: Proxy object connected
,11-15 15:52:34.128  5736  5828 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 15:52:34.130  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:34.132   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 15:52:34.132  3154  3367 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 15:52:34.133  3154  3154 D BluetoothMap: Proxy object connected
,11-15 15:52:34.134  5736  5747 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 15:52:34.134  3154  3154 D MapProfile: Bluetooth service connected
11-15 15:52:34.134  3154  3154 D BluetoothMap: getConnectedDevices()
11-15 15:52:34.134  5836  5836 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 15:52:34.134  5836  5836 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 15:52:34.135  5836  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 15:52:34.136  3154  3165 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 15:52:34.137  5836  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:34.138  3154  3367 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-15 15:52:34.139  5836  5836 D ObexServerSockets: Succeed to create listening sockets 
11-15 15:52:34.139  5836  5836 D ObexServerSockets0: startAccept()
11-15 15:52:34.139  5836  5836 D ObexServerSockets0: prepareForNewConnect()
11-15 15:52:34.140   930  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-15 15:52:34.141   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 15:52:34.141  5836  5836 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 15:52:34.141  5836  5836 D BluetoothSdpJni: SDP Create record success - handle: 0
11-15 15:52:34.141  3154  3169 D BluetoothPan: onBluetoothStateChange on: true
11-15 15:52:34.142  5836  5873 D ObexServerSockets0: Accepting socket connection...
11-15 15:52:34.142  5836  5874 D ObexServerSockets0: Accepting socket connection...
11-15 15:52:34.142  5736  5736 D BluetoothMap: Proxy object connected
11-15 15:52:34.142  5736  5736 D MapProfile: Bluetooth service connected
,11-15 15:52:34.142  5736  5736 D BluetoothMap: getConnectedDevices()
11-15 15:52:34.142  3154  3154 D BluetoothInputDevice: Proxy object connected
11-15 15:52:34.142  3154  3154 D HidProfile: Bluetooth service connected
11-15 15:52:34.143  5736  5828 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 15:52:34.144  5730  5730 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-15 15:52:34.144  3154  3154 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 15:52:34.144  3154  3154 D PanProfile: Bluetooth service connected
,11-15 15:52:34.145   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 15:52:34.145  5736  5747 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 15:52:34.147  5736  5828 D BluetoothPan: onBluetoothStateChange on: true
,11-15 15:52:34.149  5736  5736 D BluetoothInputDevice: Proxy object connected
,11-15 15:52:34.150  5736  5736 D HidProfile: Bluetooth service connected
11-15 15:52:34.150   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 15:52:34.150   930   930 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-15 15:52:34.150  5836  5836 D BluetoothMapService: onReceive
,11-15 15:52:34.150  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 15:52:34.150  5836  5836 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 15:52:34.150  5836  5836 D BluetoothMapService: STATE_ON
11-15 15:52:34.152  5736  5736 D BluetoothA2dp: Proxy object connected
11-15 15:52:34.153  5736  5736 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 15:52:34.153  5836  5876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:34.153  5736  5736 D PanProfile: Bluetooth service connected
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:34.156  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:34.156  5836  5876 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-15 15:52:34.156  5836  5876 D BluetoothSdpJni: SDP Create record success - handle: 1
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:34.158  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:34.158  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 15:52:34.160  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:34.162  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:34.162  5618  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:34.163  5618  5665 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-15 15:52:34.164   930  3850 D WifiService: setWifiEnabled: false pid=5618, uid=10077
11-15 15:52:34.164  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 15:52:34.164   930  3850 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 15:52:34.166   930   930 D RttService: SCAN_AVAILABLE : 1
,11-15 15:52:34.166   930  3099 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-15 15:52:34.166  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:34.167  5736  5736 D DockEventReceiver: finishStartingService: stopping service
,11-15 15:52:34.172  5736  5736 D BluetoothPbap: Proxy object connected
,11-15 15:52:34.172  5736  5736 D PbapServerProfile: Bluetooth service connected
,11-15 15:52:34.175   930  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-15 15:52:34.176   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 15:52:34.177  5836  5836 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 15:52:34.177  5836  5836 D ObexServerSockets0: prepareForNewConnect()
,11-15 15:52:34.180  3154  3154 D BluetoothPbap: Proxy object connected
,11-15 15:52:34.180  3154  3154 D PbapServerProfile: Bluetooth service connected
,11-15 15:52:34.185   930  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 15:52:34.185  5836  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:34.185  5730  5730 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:34.192  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:34.194  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:34.198  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:34.198  5836  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:34.199  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-15 15:52:34.200  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:34.202  5730  5730 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-15 15:52:34.203  5836  5886 I BtOppRfcommListener: Accept thread started.
,11-15 15:52:34.220  5730  5730 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 15:52:34.228  5730  5730 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 15:52:34.233  5036  5036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 15:52:34.233   930  2985 D wifi    : In wifi stop Hal
11-15 15:52:34.233   930  2985 D wifi    : halHandle = 0x7f73156680, mVM = 0x7f8f74d140, mCls = 0x20172a
11-15 15:52:34.233   930  5729 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 15:52:34.233   930  5729 D WifiHAL : Got a signal to exit!!!
11-15 15:52:34.233   930  5729 I WifiHAL : Exit wifi_event_loop
11-15 15:52:34.234   930  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-15 15:52:34.234   930  2985 E WifiHAL : Event processing terminated
11-15 15:52:34.234   930  2985 D wifi    : In wifi cleaned up handler
,11-15 15:52:34.234   930  2985 I WifiHAL : Internal cleanup completed
11-15 15:52:34.235  4058  4245 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 15:52:34.237  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:34.238  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:34.256   930  5729 D wifi    : set interface wlan0 flags (DOWN)
,11-15 15:52:34.256   930  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 15:52:34.463   930   947 D Tethering: InitialState.processMessage what=4
,11-15 15:52:34.469   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:34.675  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:34.680  5618  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:34.685   930   940 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,11-15 15:52:34.685   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 15:52:34.687  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:34.695   508   924 D SoftapController: Softap fwReload - Ok
,11-15 15:52:34.699   508   924 D CommandListener: Setting iface cfg
11-15 15:52:34.700   508   924 D CommandListener: Trying to bring down wlan0
,11-15 15:52:34.702   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 15:52:34.705   930  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 15:52:35.194   930  3447 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,11-15 15:52:35.199   930  3447 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 15:52:35.311   930  2985 D wifi    : set interface wlan0 flags (UP)
,11-15 15:52:35.311   930  2985 I WifiHAL : Initializing wifi
,11-15 15:52:35.311   930  2985 I WifiHAL : Creating socket
,11-15 15:52:35.317   930  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 15:52:35.317   930  2985 D wifi    : Did set static halHandle = 0x7f73156680
11-15 15:52:35.317   930  2985 D wifi    : halHandle = 0x7f73156680, mVM = 0x7f8f74d140, mCls = 0x1012a2
11-15 15:52:35.317   930  2985 D wifi    : array field set
11-15 15:52:35.318   930  2985 I WifiNative-HAL: interface[0] = wlan0
11-15 15:52:35.320   930  5889 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547391628928
,11-15 15:52:35.320   930  5889 D wifi    : waitForHalEvents called, vm = 0x7f8f74d140, obj = 0x1012a2, env = 0x7f70872f80
11-15 15:52:35.323   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-15 15:52:35.383  5890  5890 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 15:52:35.421   930  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 15:52:35.431  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:35.433  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:35.457  5890  5890 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 15:52:35.462  5890  5890 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-15 15:52:35.462  5890  5890 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 15:52:35.472   930  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:35.476  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:35.478  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:35.481  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 15:52:35.483  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:35.489   930  2985 D WifiConfigStore: loaded 0 passpoint configs
,11-15 15:52:35.489   930  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 15:52:35.489   930  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-15 15:52:35.490   930  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-15 15:52:35.490   930  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-15 15:52:35.490   930  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-15 15:52:35.491   930  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-15 15:52:35.491   930  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-15 15:52:35.491   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 15:52:35.491   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-15 15:52:35.491   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 15:52:35.491   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 15:52:35.491   930  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 15:52:35.493   930  2985 D WifiNative-HAL: Setting external_sim to 1
11-15 15:52:35.493   930  2985 D wifi    : setting dfs flag to true, 0x7f77edb300
,11-15 15:52:35.493   930  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 15:52:35.493  5036  5036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 15:52:35.493   930  2985 D wifi    : setting scan oui 0x7f77edb300
,11-15 15:52:35.493   930  2985 D WifiHAL : Sending mac address OUI
,11-15 15:52:35.496   930  2985 E native  : do suspend false
,11-15 15:52:35.502   930  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-15 15:52:35.502   930   930 D RttService: SCAN_AVAILABLE : 3
11-15 15:52:35.502   930  3099 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 15:52:35.505   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-15 15:52:35.507   508   924 D CommandListener: Setting iface cfg
,11-15 15:52:35.511   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=109623 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=4 mControllerEnergyUsed=15 }
,11-15 15:52:35.511   930  2984 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
11-15 15:52:35.511   930  2984 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 15:52:35.513   930  2984 D WifiNative-HAL: p2pGetDeviceAddress
11-15 15:52:35.514   930  2984 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:35.714  5618  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:35.720  5618  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-15 15:52:35.723  5618  5665 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 15:52:35.724   930  3850 D WifiService: setWifiEnabled: true pid=5618, uid=10077
11-15 15:52:35.724   930  3850 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 15:52:35.725  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 15:52:35.725  5618  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 15:52:35.725  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 15:52:35.725  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 15:52:35.726  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 15:52:35.726  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9f4e3c removed from the list
11-15 15:52:35.726  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 15:52:35.726  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@812c7c5 removed from the list
11-15 15:52:35.726  5618  5665 D io.jxcore.node.ConnectivityMonitor: stop
11-15 15:52:35.726  5618  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 15:52:35.726  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-15 15:52:35.730  5618  5665 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-15 15:52:35.734  5618  5665 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-15 15:52:35.735  5618  5665 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-15 15:52:35.737  5618  5665 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-15 15:52:35.739  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-15 15:52:35.740  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-15 15:52:35.741  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-15 15:52:35.741  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-15 15:52:35.741  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-15 15:52:35.744  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-15 15:52:35.744  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f80763d Bundle[{}]
11-15 15:52:35.745  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-15 15:52:35.745  5618  5665 I io.jxcore.node.LifeCycleMonitor: start: OK
11-15 15:52:35.745  5618  5665 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-15 15:52:35.746  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-15 15:52:35.746  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-15 15:52:35.747  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-15 15:52:35.747  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-15 15:52:35.748  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-15 15:52:35.748  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-15 15:52:35.748  5618  5665 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-15 15:52:35.749  5618  5665 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-15 15:52:35.751  5618  5665 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-15 15:52:35.752  5618  5665 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-15 15:52:35.753  5618  5665 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-15 15:52:35.754  5618  5665 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-15 15:52:35.754  5618  5665 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-15 15:52:35.754  5618  5665 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-15 15:52:35.756  5618  5665 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-15 15:52:35.757  5618  5665 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-15 15:52:35.758  5618  5665 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-15 15:52:35.760  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-15 15:52:35.761  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-15 15:52:35.761  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-15 15:52:35.761  5618  5665 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-15 15:52:35.763  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-15 15:52:35.763  5618  5665 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-15 15:52:35.763  5618  5665 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
,11-15 15:52:35.764  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-15 15:52:35.765  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-15 15:52:35.766  5618  5665 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-15 15:52:35.766  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 15:52:35.766  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2311228 added. We now have 3 listener(s)
11-15 15:52:35.767  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:35.768  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 15:52:35.768  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 15:52:35.768  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 15:52:35.768  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d1b41 added. We now have 3 listener(s)
11-15 15:52:35.768  5618  5665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 15:52:35.769  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 15:52:35.772  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 15:52:35.775  5618  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 15:52:35.777  5618  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-15 15:52:35.777  5618  5665 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-15 15:52:35.779  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 15:52:35.780  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 15:52:35.780  5618  5665 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-15 15:52:35.781  5618  5665 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-15 15:52:35.781  5618  5665 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-15 15:52:35.781  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-15 15:52:35.782  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:35.782  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 15:52:35.782  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 15:52:35.782  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 15:52:35.783  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 15:52:35.783  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 15:52:35.784  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 15:52:35.784  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-15 15:52:35.784  5618  5892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 15:52:35.784  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 15:52:35.784  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-15 15:52:35.784  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:35.784  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 15:52:35.784  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 15:52:35.785  5618  5892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 15:52:35.788  5618  5892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 15:52:35.784  5846  5846 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33209]" dev="sockfs" ino=33209 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:35.788  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 15:52:35.788  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 15:52:35.788  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 15:52:35.784  5846  5846 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33209]" dev="sockfs" ino=33209 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 15:52:35.792  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 15:52:35.792  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 15:52:35.793  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-15 15:52:35.794  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:35.794  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 15:52:35.794  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:35.794  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-15 15:52:35.795  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 15:52:35.795  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.795  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:35.795  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.795  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.795  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:35.798  5836  5875 D BtGatt.GattService: registerClient() - UUID=5dbd7173-5615-46ab-852c-c273f3cbb223
,11-15 15:52:35.799  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=5dbd7173-5615-46ab-852c-c273f3cbb223, clientIf=5
11-15 15:52:35.799  5618  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 15:52:35.801  5836  5854 D BtGatt.AdvertiseManager: message : 0
,11-15 15:52:35.803  5836  5854 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 15:52:35.806  5836  5852 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 15:52:35.809  5836  5852 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 15:52:35.809  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.809  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.809  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 15:52:35.809  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:35.809  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:35.809  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.809  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.810  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.810  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 15:52:35.811  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 15:52:35.811  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.812  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.812  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.812  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:35.812  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 15:52:35.812  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-15 15:52:35.812  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:35.812  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 15:52:35.812  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.812  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:35.812  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.812  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 15:52:35.813  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 15:52:35.813  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.813  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-15 15:52:35.813  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 15:52:35.813  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.815  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.815  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 15:52:35.815  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.815  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.815  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 15:52:35.815  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:35.815  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 15:52:36.316  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-15 15:52:36.316  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 15:52:36.316  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 15:52:39.314  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 15:52:39.314  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 15:52:39.314  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 15:52:39.315  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-15 15:52:39.315  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 15:52:39.316  5618  5892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 15:52:39.316  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-15 15:52:39.316  5618  5892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 15:52:39.316  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 15:52:39.316  5618  5892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 15:52:39.316  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 15:52:39.316  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 15:52:39.316  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 15:52:39.317  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 15:52:39.317  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 15:52:39.317  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 15:52:39.317  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 15:52:39.317  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 15:52:39.319  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.320  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.321  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:39.322  5618  5665 D BluetoothLeScanner: could not find callback wrapper
11-15 15:52:39.322  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 15:52:39.322  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.322  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.322  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 15:52:39.323  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.324  5836  5854 D BtGatt.AdvertiseManager: message : 1
11-15 15:52:39.325  5836  5854 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 15:52:39.338  5836  5852 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 15:52:39.339  5836  5852 D BtGatt.GattService: Client app is not null!
,11-15 15:52:39.340  5836  5875 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 15:52:39.342  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 15:52:39.342  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.342  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-15 15:52:39.342  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.342  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.343  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.343  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 15:52:39.343  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 15:52:39.343  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.343  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.343  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 15:52:39.344  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.346  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.346  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:39.347  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.347  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.347  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.347  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.347  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.347  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 15:52:39.348  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 15:52:39.349  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-15 15:52:39.349  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.351  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.352  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.352  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.352  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 15:52:39.352  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 15:52:39.352  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:39.352  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:39.353  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:39.355  5618  5665 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-15 15:52:39.356  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-15 15:52:39.356  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 15:52:39.357  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 15:52:39.357  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 15:52:39.357  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:39.357  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 15:52:39.360  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-15 15:52:39.360  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 15:52:39.360  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 15:52:39.364  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 15:52:39.365  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-15 15:52:39.365  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-15 15:52:39.370  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.370  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 15:52:39.370  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 15:52:39.370  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 15:52:39.371  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 15:52:39.371  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.372  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:39.375  5836  5847 D BtGatt.GattService: registerClient() - UUID=1b51f34a-d4ee-4b29-81ad-81472da3a679
11-15 15:52:39.375  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=1b51f34a-d4ee-4b29-81ad-81472da3a679, clientIf=5
,11-15 15:52:39.376  5618  5763 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 15:52:39.377  5836  5875 D BtGatt.GattService: start scan with filters
,11-15 15:52:39.381  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-15 15:52:39.381  5836  5855 D BtGatt.ScanManager: handling starting scan
11-15 15:52:39.381  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.381  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-15 15:52:39.382  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.382  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.382  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 15:52:39.382  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 15:52:39.382  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.382  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.383  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 15:52:39.383  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.383  5836  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8dbcda6
,11-15 15:52:39.386  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.386  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 15:52:39.386  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.386  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.386  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.386  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 15:52:39.386  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 15:52:39.388  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 15:52:39.388  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.390  5836  5852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 15:52:39.390  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 15:52:39.391  5836  5855 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 15:52:39.391  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.392  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:39.392  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:39.399  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-15 15:52:39.399  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:39.400  5836  5855 D BtGatt.ScanManager: Starting BLE batch scan
11-15 15:52:39.400  5836  5855 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 15:52:39.411  5836  5852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 15:52:39.412  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 15:52:39.417  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 15:52:39.418  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 15:52:39.561   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 15:52:39.562   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 15:52:39.887  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 15:52:39.888  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 15:52:39.888  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 15:52:42.394  5618  5665 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-15 15:52:42.395  5618  5665 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 15:52:42.395  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 15:52:42.396  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 15:52:42.396  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-15 15:52:42.398  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:42.400  5836  5877 D BtGatt.GattService: stopScan() - queue size =1
11-15 15:52:42.402  5836  5847 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 15:52:42.403  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-15 15:52:42.403  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.403  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 15:52:42.404  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 15:52:42.404  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.404  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 15:52:42.404  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 15:52:42.404  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 15:52:42.404  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 15:52:42.405  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.407  5618  5665 D BluetoothAdapter: STATE_ON
,11-15 15:52:42.413  5836  5863 D BtGatt.GattService: registerClient() - UUID=9902e2be-c892-41a5-99fd-0f68442a80b1
,11-15 15:52:42.414  5836  5836 D BtGatt.ScanManager: awakened up at time 116525
11-15 15:52:42.414  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=9902e2be-c892-41a5-99fd-0f68442a80b1, clientIf=5
,11-15 15:52:42.414  5618  5629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 15:52:42.415  5836  5875 D BtGatt.GattService: start scan with filters
11-15 15:52:42.417  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 15:52:42.417  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:42.418  5836  5855 D BtGatt.ScanManager: stopping BLe Batch
,11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 15:52:42.419  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 15:52:42.419  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.420  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.420  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:42.420  5618  5665 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 15:52:42.420  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 15:52:42.420  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 15:52:42.421  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 15:52:42.421  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 15:52:42.421  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 15:52:42.422  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-15 15:52:42.422  5618  5895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 15:52:42.422  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 15:52:42.422  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-15 15:52:42.422  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-15 15:52:42.422  5618  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 15:52:42.425  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 15:52:42.425  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 15:52:42.421  5865  5865 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35856]" dev="sockfs" ino=35856 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:42.421  5865  5865 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35856]" dev="sockfs" ino=35856 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 15:52:42.425  5836  5855 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 15:52:42.425  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 15:52:42.425  5618  5665 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-15 15:52:42.436  5618  5895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 15:52:42.436  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.436  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.436  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 15:52:42.436  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 15:52:42.436  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
,11-15 15:52:42.437  5618  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 15:52:42.437  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.437  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.437  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.437  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.439  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:42.441  5836  5877 D BtGatt.GattService: registerClient() - UUID=bf068cc1-e56b-4b31-8f51-e6f82b966aae
,11-15 15:52:42.442  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=bf068cc1-e56b-4b31-8f51-e6f82b966aae, clientIf=6
,11-15 15:52:42.442  5836  5852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-15 15:52:42.442  5618  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-15 15:52:42.442  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:42.442  5836  5852 D BtGatt.GattService: current time is 116554783090
11-15 15:52:42.443  5836  5852 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -84, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 15:52:42.443  5836  5854 D BtGatt.AdvertiseManager: message : 0
,11-15 15:52:42.444  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 15:52:42.445  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 15:52:42.445  5836  5855 D BtGatt.ScanManager: handling starting scan
11-15 15:52:42.445  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 15:52:42.446  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 15:52:42.447  5836  5854 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 15:52:42.451  5836  5852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 15:52:42.451  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 15:52:42.452  5836  5855 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 15:52:42.460  5836  5852 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-15 15:52:42.464  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-15 15:52:42.464  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:42.464  5836  5855 D BtGatt.ScanManager: Starting BLE batch scan
11-15 15:52:42.465  5836  5855 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 15:52:42.468  5836  5852 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-15 15:52:42.469  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.469  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.470  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.470  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-15 15:52:42.470  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-15 15:52:42.470  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 15:52:42.471  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 15:52:42.471  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.476  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:42.476  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.476  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:42.476  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.477  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-15 15:52:42.477  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-15 15:52:42.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.479  5836  5852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 15:52:42.479  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:42.480  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.480  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-15 15:52:42.480  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.480  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-15 15:52:42.480  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 15:52:42.480  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-15 15:52:42.480  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-15 15:52:42.484  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 15:52:42.484  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 15:52:42.981  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-15 15:52:42.981  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-15 15:52:42.982  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 15:52:44.563   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:45.479  5618  5665 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-15 15:52:45.480  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 15:52:45.480  5618  5665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 15:52:45.481  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-15 15:52:45.481  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 15:52:45.482  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-15 15:52:45.482  5618  5895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 15:52:45.482  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 15:52:45.482  5618  5895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 15:52:45.482  5618  5665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 15:52:45.482  5618  5895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-15 15:52:45.482  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 15:52:45.483  5618  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2311228 removed from the list
11-15 15:52:45.483  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-15 15:52:45.483  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 15:52:45.483  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 15:52:45.483  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 15:52:45.483  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-15 15:52:45.483  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 15:52:45.483  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 15:52:45.484  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:45.484  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.484  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 15:52:45.486  5618  5665 D BluetoothAdapter: STATE_ON
11-15 15:52:45.489  5836  5877 D BtGatt.GattService: stopScan() - queue size =1
11-15 15:52:45.493  5836  5863 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 15:52:45.493  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 15:52:45.494  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.494  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 15:52:45.494  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.494  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.494  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 15:52:45.494  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-15 15:52:45.495  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.495  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.495  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-15 15:52:45.495  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:45.500  5836  5836 D BtGatt.ScanManager: awakened up at time 119612
,11-15 15:52:45.502  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:45.502  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 15:52:45.502  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.502  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.502  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.502  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:45.502  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 15:52:45.503  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.503  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 15:52:45.503  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:45.503  5836  5855 D BtGatt.ScanManager: stopping BLe Batch
,11-15 15:52:45.504  5836  5854 D BtGatt.AdvertiseManager: message : 1
11-15 15:52:45.505  5836  5854 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-15 15:52:45.512  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 15:52:45.512  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:45.512  5836  5855 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 15:52:45.519  5836  5852 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-15 15:52:45.520  5836  5852 D BtGatt.GattService: Client app is not null!
11-15 15:52:45.520  5836  5877 D BtGatt.GattService: unregisterClient() - clientIf=6
11-15 15:52:45.521  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 15:52:45.521  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:45.522  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 15:52:45.522  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.523  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.523  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.523  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 15:52:45.523  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 15:52:45.523  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.523  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.523  5618  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 15:52:45.523  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.525  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 15:52:45.526  5618  5665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-15 15:52:45.526  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-15 15:52:45.526  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.528  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.528  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 15:52:45.528  5618  5665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 15:52:45.528  5618  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d1b41 removed from the list
11-15 15:52:45.528  5618  5665 D io.jxcore.node.ConnectivityMonitor: stop
11-15 15:52:45.528  5618  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 15:52:45.528  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 15:52:45.528  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 15:52:45.528  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 15:52:45.529  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 15:52:45.533  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-15 15:52:45.533  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-15 15:52:45.533  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 15:52:45.533  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 15:52:45.533  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 15:52:45.533  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-15 15:52:45.533  5618  5665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 15:52:45.534  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-15 15:52:45.535  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-15 15:52:45.536  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-15 15:52:45.537  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-15 15:52:45.538  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-15 15:52:45.539  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-15 15:52:45.539  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-15 15:52:45.540  5618  5665 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-15 15:52:45.547  5836  5852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 15:52:45.548  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 15:52:45.548  5836  5852 D BtGatt.GattService: current time is 119660024829
11-15 15:52:45.548  5836  5852 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -87, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 15:52:45.548  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 15:52:45.548  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 15:52:45.549  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 15:52:45.549  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 15:52:45.549  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 15:52:45.549  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 15:52:45.563   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:45.966   930  2985 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-15 15:52:46.029  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 15:52:46.564   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:46.833   930  2985 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-15 15:52:47.544  5618  5665 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-15 15:52:47.565   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:47.682  5618  5897 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 15:52:47.682  5618  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 15:52:48.379   930  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-15 15:52:48.380   930  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-15 15:52:48.380   930  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 15:52:48.388   930  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 15:52:48.420   930  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 15:52:48.426  5890  5890 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 15:52:48.482  5618  5897 W !!      : call onHalfStreamCopied
,11-15 15:52:48.482  5618  5897 I testCopyDataAndClose: closing input stream
,11-15 15:52:48.565   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:48.885  5890  5890 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 15:52:48.928  5890  5890 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 15:52:48.930  5890  5890 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 15:52:48.940   930  2985 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-15 15:52:48.941   930  2988 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 15:52:48.941   930  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 15:52:48.960   930  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 15:52:48.972   508   924 D CommandListener: Setting iface cfg
,11-15 15:52:48.978   930  2985 D WifiStateMachine: Start Dhcp Watchdog 2
,11-15 15:52:48.984   930  5901 D DhcpClient: Receive thread started
,11-15 15:52:48.989   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 15:52:48.989   930  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-15 15:52:48.989   930  2988 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-15 15:52:49.070   930  2985 E native  : do suspend false
,11-15 15:52:49.080   930  5900 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 15:52:49.093   930  5901 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172717, domain null
,11-15 15:52:49.094   930  5900 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172717 seconds
,11-15 15:52:49.095   930  5900 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 15:52:49.106   930  5901 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-15 15:52:49.107   930  5900 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-15 15:52:49.109   508   924 D CommandListener: Setting iface cfg
,11-15 15:52:49.113   930  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 15:52:49.116   930  5900 D DhcpClient: Scheduling renewal in 86399s
,11-15 15:52:49.124   930  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-15 15:52:49.125   930  2985 D WifiConfigStore: No blacklist allowed without epno enabled
,11-15 15:52:49.126   930  2988 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-15 15:52:49.128   930  2985 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-15 15:52:49.134   930  2988 D ConnectivityService: Adding iface wlan0 to network 101
,11-15 15:52:49.172   930  2988 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-15 15:52:49.172   930  2988 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-15 15:52:49.174   930  2988 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-15 15:52:49.176   930  2988 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-15 15:52:49.178   930  2988 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-15 15:52:49.185   930  2988 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 15:52:49.190   930  2988 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-15 15:52:49.190   930  2988 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-15 15:52:49.191   930  2988 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-15 15:52:49.191   930  2985 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-15 15:52:49.191   930  2988 D ConnectivityService:    accepting network in place of null
11-15 15:52:49.191   930  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 15:52:49.191   930  2988 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 15:52:49.199   930  5899 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123310, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 15:52:49.214   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 15:52:49.236   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 15:52:49.240   930  2988 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-15 15:52:49.240   930  2988 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 15:52:49.240  3766  3917 W QCNEJ   : |CORE| network available: 101
11-15 15:52:49.242   930  2988 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-15 15:52:49.247  3766  3917 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 15:52:49.247  5618  5897 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 15:52:49.248  5618  5897 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 15:52:49.248  5618  5897 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 15:52:49.248  5618  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
11-15 15:52:49.248  3766  3917 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-15 15:52:49.248   930   947 D Tethering: MasterInitialState.processMessage what=3
11-15 15:52:49.248  3766  3917 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:49.252  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 15:52:49.258  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 15:52:49.262  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 15:52:49.263  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-15 15:52:49.269  4013  4013 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 15:52:49.271  5064  5088 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-15 15:52:49.271  5064  5088 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 15:52:49.271  5064  5088 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-15 15:52:49.271  5064  5088 E SarControlService: no key has been found,reset the power
11-15 15:52:49.271  5064  5100 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 15:52:49.271  5064  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 15:52:49.271  5064  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-15 15:52:49.272  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 15:52:49.272  5089  5089 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 15:52:49.273  5064  5100 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 15:52:49.273  5064  5100 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 15:52:49.273  5064  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 15:52:49.274  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 15:52:49.274  5089  5089 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-15 15:52:49.274   930  5898 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
,11-15 15:52:49.276  3879  3879 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 15:52:49.279  5089  5103 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@62ccbc9 HexData = [00000000ec03000000000000ffffffff]
11-15 15:52:49.279  5089  5103 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 15:52:49.279  5089  5103 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-15 15:52:49.280  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 15:52:49.280  5064  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 15:52:49.280  3879  3879 D SystemUpdateService: onCreate
11-15 15:52:49.285  3879  3879 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-15 15:52:49.286  5089  5103 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@62ccbc9 HexData = [00000000ed03000000000000ffffffff]
,11-15 15:52:49.286  5089  5103 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 15:52:49.295  5089  5103 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-15 15:52:49.296  5089  5089 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-15 15:52:49.296  5064  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 15:52:49.307  3879  3879 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 15:52:49.316  3879  5417 I iu.UploadsManager: num queued entries: 0
,11-15 15:52:49.316  3879  5417 I iu.UploadsManager: num updated entries: 0
11-15 15:52:49.317  3879  5417 I iu.SyncManager: NEXT; no task
,11-15 15:52:49.318  3879  5911 I SystemUpdateService: active receiver: enabled
,11-15 15:52:49.320  3879  3879 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 15:52:49.321  3879  3879 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 15:52:49.323  5419  5419 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 15:52:49.326  5419  5419 D SprintDMHelper: simOperator: 
11-15 15:52:49.327  5419  5419 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 15:52:49.335   930  5898 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 14:52:49 GMT], X-Android-Received-Millis=[1479221569334], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479221569312]}
,11-15 15:52:49.335   930  2988 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-15 15:52:49.335   930  2988 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-15 15:52:49.336   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-15 15:52:49.337   930  2988 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 15:52:49.359  3879  5911 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 15:52:49.364  3879  5911 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-15 15:52:49.365  3879  5911 I SystemUpdateService: now status is 0 (complete)
11-15 15:52:49.365  3879  5911 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 15:52:49.365  3879  5911 I SystemUpdateService: file has been verified
11-15 15:52:49.365  3879  5911 I SystemUpdateService: OTA package size = 21989297
,11-15 15:52:49.369  3879  5911 I SystemUpdateService: showing system update notification
,11-15 15:52:49.382   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 15:52:49.384  3879  3879 D SystemUpdateService: onDestroy
,11-15 15:52:49.432  5036  5915 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-15 15:52:49.566   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 15:52:50.241   930  2988 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-15 15:52:50.513   930  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-15 15:52:52.011   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 15:52:53.477  5618  5665 I StreamCopyingThreadTest: Starting test: testRun
,11-15 15:52:53.481  5618  5923 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:52:53.481  5618  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 15:52:54.567   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:55.042   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 15:52:55.568   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:56.570   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:57.193   930  2988 D ConnectivityService: handlePromptUnvalidated 101
,11-15 15:52:57.572   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:58.487  5618  5924 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-15 15:52:58.490  5618  5665 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-15 15:52:58.572   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:52:58.630  5618  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 15:52:58.630  5618  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 15:52:59.573   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 15:53:00.265  5618  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 15:53:01.484  3691  3855 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 15:53:01.484  3691  3855 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 15:53:01.516  3613  3613 I ConfigService: onCreate
,11-15 15:53:04.113   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 15:53:04.526  5618  5665 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-15 15:53:04.529  5618  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 15:53:04.530  5618  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 15:53:04.530  5618  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-15 15:53:04.530  5618  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 15:53:04.530  5618  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:53:04.530  5618  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-15 15:53:04.531  5618  5665 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-15 15:53:04.532  5618  5665 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-15 15:53:04.533  5618  5665 I StreamCopyingThreadTest: Starting test: testRunWithException
11-15 15:53:04.535  5618  5928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:53:04.535  5618  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 15:53:04.536  5618  5928 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,11-15 15:53:04.536  5618  5928 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:53:04.536  5618  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 15:53:04.536  5618  5928 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-15 15:53:04.536  5618  5928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-15 15:53:04.536  5618  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 15:53:04.537  5618  5665 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-15 15:53:04.537  5618  5665 E com.test.thalitest.ThaliTestRunner: 
11-15 15:53:04.537  5618  5665 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 15:53:04.537  5618  5665 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 15:53:04.538  5618,  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 15:53:04.538  5618  5665 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-15 15:53:04.539  5618  5665 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363,)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:53:04.539  5618  5665 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 15:53:04.540  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG UnitTest_app: 'Running unit tests'
11-15 15:53:04.540  5618  5665 I jxcore-log: 
11-15 15:53:04.540  5618  5665 I jxcore-log: *Native tests were executed*
11-15 15:53:04.540  5618  5665 I jxcore-log: 
11-15 15:53:04.540  5618  5665 I jxcore-log: Total number of executed tests:  82
11-15 15:53:04.540  5618  5665 I jxcore-log: 
11-15 15:53:04.540  5618  5665 I jxcore-log: Number of passed tests:  80
11-15 15:53:04.540  5618  5665 I jxcore-log: 
11-15 15:53:04.541  5618  5665 I jxcore-log: Number of failed tests:  2
11-15 15:53:04.541  5618  5665 I jxcore-log: 
11-15 15:53:04.541  5618  5665 I jxcore-log: Number of ignored tests:  0
11-15 15:53:04.541  5618  5665 I jxcore-log: 
11-15 15:53:04.541  5618  5665 I jxcore-log: Total duration:  41913
11-15 15:53:04.541  5618  5665 I jxcore-log: 
11-15 15:53:04.541  5618  5665 I jxcore-log: Failed to execute UT.
11-15 15:53:04.541  5618  5665 I jxcore-log: 
11-15 15:53:04.542  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-15 15:53:04.542  5618  5665 I jxcore-log: 
11-15 15:53:04.543  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG UnitTest_ap,p: 'Unit Test app is loaded'
11-15 15:53:04.543  5618  5665 I jxcore-log: 
11-15 15:53:04.546  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-15 15:53:04.546  5618  5665 I jxcore-log: 
11-15 15:53:04.546  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.546  5618  5665 I jxcore-log: 
11-15 15:53:04.547  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-15 15:53:04.547  5618  5665 I jxcore-log: 
11-15 15:53:04.548  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.548  5618  5665 I jxcore-log: 
11-15 15:53:04.549  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-15 15:53:04.549  5618  5665 I jxcore-log: 
11-15 15:53:04.549  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.549  5618  5665 I jxcore-log: 
11-15 15:53:04.549  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 15:53:04.549  5618  5665 I jxcore-log: 
11-15 15:53:04.549  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 15:53:04.549  5618  5665 I jxcore-log: 
11-15 15:53:04.550  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 15:53:04.550  5618  5665 I jxcore-log: 
11-15 15:53:04.550  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 15:53:04.550  5618  5665 I jxcore-log: 
11-15 15:53:04.550  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-15 15:53:04.550  5618  5665 I jxcore-log: 
11-15 15:53:04.550  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.550  5618  5665 I jxcore-log: 
11-15 15:53:04.551  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.551  5618  5665 I jxcore-log: 
11-15 15:53:04.551  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.551  5618  5665 I jxcore-log: 
11-15 15:53:04.551  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 15:53:04.551  5618  5665 I jxcore-log: 
11-15 15:53:04.551  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.551  5618  5665 I jxcore-log: 
11-15 15:53:04.551  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 15:53:04.551  5618  5665 I jxcore-log: 
11-15 15:53:04.552  5618  5665 I jxcore-log: 2016-11-15 14:,53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.552  5618  5665 I jxcore-log: 
11-15 15:53:04.552  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 15:53:04.552  5618  5665 I jxcore-log: 
11-15 15:53:04.552  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.552  5618  5665 I jxcore-log: 
11-15 15:53:04.552  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 15:53:04.552  5618  5665 I jxcore-log: 
11-15 15:53:04.553  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.553  5618  5665 I jxcore-log: 
11-15 15:53:04.553  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.553  5618  5665 I jxcore-log: 
11-15 15:53:04.553  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.553  5618  5665 I jxcore-log: 
11-15 15:53:04.553  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.553  5618  5665 I jxcore-log: 
11-15 15:53:04.553  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.553  5618  5665 I jxcore-log: 
11-15 15:53:04.554  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.554  5618  5665 I jxcore-log: 
11-15 15:53:04.554  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.554  5618  5665 I jxcore-log: 
11-15 15:53:04.554  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.554  5618  5665 I jxcore-log: 
11-15 15:53:04.555  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.555  5618  5665 I jxcore-log: 
11-15 15:53:04.556  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.556  5618  5665 I jxcore-log: 
11-15 15:53:04.556  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.556  5618  5665 I jxcore-log: 
11-15 15:53:04.556  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.556  5618  5665 I jxcore-log: 
11-15 15:53:04.556  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.556  5618  5665 I jxcore-log: 
11-15 15:53:04.557  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.557  5618  5665 I jxcore-log: 
11-15 15:53:04.557  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:0,4.557  5618  5665 I jxcore-log: 
11-15 15:53:04.557  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.557  5618  5665 I jxcore-log: 
11-15 15:53:04.557  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.557  5618  5665 I jxcore-log: 
11-15 15:53:04.557  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.557  5618  5665 I jxcore-log: 
11-15 15:53:04.558  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.558  5618  5665 I jxcore-log: 
11-15 15:53:04.558  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.558  5618  5665 I jxcore-log: 
11-15 15:53:04.558  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.558  5618  5665 I jxcore-log: 
11-15 15:53:04.558  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.558  5618  5665 I jxcore-log: 
11-15 15:53:04.558  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.558  5618  5665 I jxcore-log: 
11-15 15:53:04.558  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.558  5618  5665 I jxcore-log: 
11-15 15:53:04.559  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.559  5618  5665 I jxcore-log: 
11-15 15:53:04.559  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.559  5618  5665 I jxcore-log: 
11-15 15:53:04.559  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.559  5618  5665 I jxcore-log: 
11-15 15:53:04.559  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.559  5618  5665 I jxcore-log: 
11-15 15:53:04.559  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.559  5618  5665 I jxcore-log: 
,11-15 15:53:04.560  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.560  5618  5665 I jxcore-log: 
11-15 15:53:04.560  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 15:53:04.560  5618  5665 I jxcore-log: 
11-15 15:53:04.560  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.560  5618  5665 I jxcore-log: 
11-15 15:53:04.560  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 15:53:04.560  5618  5665 I jxcore-log: 
11-15 15:53:04.560  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.560  5618  5665 I jxcore-log: 
11-15 15:53:04.561  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 15:53:04.561  5618  5665 I jxcore-log: 
11-15 15:53:04.561  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.561  5618  5665 I jxcore-log: 
11-15 15:53:04.561  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.561  5618  5665 I jxcore-log: 
11-15 15:53:04.561  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.561  5618  5665 I jxcore-log: 
,11-15 15:53:04.561  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.561  5618  5665 I jxcore-log: 
11-15 15:53:04.561  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.561  5618  5665 I jxcore-log: 
11-15 15:53:04.562  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.562  5618  5665 I jxcore-log: 
11-15 15:53:04.562  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.562  5618  5665 I jxcore-log: 
11-15 15:53:04.562  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 15:53:04.562  5618  5665 I jxcore-log: 
11-15 15:53:04.562  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.562  5618  5665 I jxcore-log: 
,11-15 15:53:04.562  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 15:53:04.562  5618  5665 I jxcore-log: 
11-15 15:53:04.562  5618  5618 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-15 15:53:04.563  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-15 15:53:04.563  5618  5665 I jxcore-log: 
11-15 15:53:04.563  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-15 15:53:04.563  5618  5665 I jxcore-log: 
11-15 15:53:04.563  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 15:53:04.563  5618  5665 I jxcore-log: 
11-15 15:53:04.564  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-15 15:53:04.564  5618  5665 I jxcore-log: 
11-15 15:53:04.564  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.564  5618  5665 I jxcore-log: 
,11-15 15:53:04.564  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-15 15:53:04.564  5618  5665 I jxcore-log: 
11-15 15:53:04.564  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 15:53:04.564  5618  5665 I jxcore-log: 
,11-15 15:53:04.569  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-15 15:53:04.569  5618  5665 I jxcore-log: 
11-15 15:53:04.569  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - WARN testUtils: 'myNameCallback not set!'
11-15 15:53:04.569  5618  5665 I jxcore-log: 
,11-15 15:53:04.570  5618  5665 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-15 15:53:04.571  5618  5665 I jxcore-log: 2016-11-15 14:53:04 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-15 15:53:04.571  5618  5665 I jxcore-log: 
,11-15 15:53:06.550  3613  3613 I ConfigService: onDestroy
,11-15 15:53:06.659  5618  5665 I jxcore-log: 2016-11-15 14:53:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-15 15:53:06.659  5618  5665 I jxcore-log: 
,11-15 15:53:07.004  5618  5665 I jxcore-log: 2016-11-15 14:53:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-15 15:53:07.004  5618  5665 I jxcore-log: 
,11-15 15:53:07.018  5618  5665 I jxcore-log: 2016-11-15 14:53:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-15 15:53:07.018  5618  5665 I jxcore-log: 
,11-15 15:53:07.147   930  2988 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 15:53:08.136  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-15 15:53:08.136  5618  5665 I jxcore-log: 
,11-15 15:53:08.309  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-15 15:53:08.309  5618  5665 I jxcore-log: 
,11-15 15:53:08.314  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-15 15:53:08.314  5618  5665 I jxcore-log: 
,11-15 15:53:08.319  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-15 15:53:08.319  5618  5665 I jxcore-log: 
,11-15 15:53:08.806  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-15 15:53:08.806  5618  5665 I jxcore-log: 
,11-15 15:53:08.851  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-15 15:53:08.851  5618  5665 I jxcore-log: 
,11-15 15:53:08.865  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-15 15:53:08.865  5618  5665 I jxcore-log: 
,11-15 15:53:08.869  5618  5665 I jxcore-log: 2016-11-15 14:53:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-15 15:53:08.869  5618  5665 I jxcore-log: 
,11-15 15:53:09.167  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-15 15:53:09.167  5618  5665 I jxcore-log: 
,11-15 15:53:09.314  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-15 15:53:09.314  5618  5665 I jxcore-log: 
,11-15 15:53:09.574   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:53:09.683  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-15 15:53:09.683  5618  5665 I jxcore-log: 
,11-15 15:53:09.718  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-15 15:53:09.718  5618  5665 I jxcore-log: 
,11-15 15:53:09.724  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-15 15:53:09.724  5618  5665 I jxcore-log: 
,11-15 15:53:09.729  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-15 15:53:09.729  5618  5665 I jxcore-log: 
,11-15 15:53:09.736  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-15 15:53:09.736  5618  5665 I jxcore-log: 
,11-15 15:53:09.750  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-15 15:53:09.750  5618  5665 I jxcore-log: 
,11-15 15:53:09.754  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-15 15:53:09.754  5618  5665 I jxcore-log: 
,11-15 15:53:09.782  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-15 15:53:09.782  5618  5665 I jxcore-log: 
,11-15 15:53:09.819  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-15 15:53:09.819  5618  5665 I jxcore-log: 
,11-15 15:53:09.826  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-15 15:53:09.826  5618  5665 I jxcore-log: 
,11-15 15:53:09.832  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-15 15:53:09.832  5618  5665 I jxcore-log: 
,11-15 15:53:09.848  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-15 15:53:09.848  5618  5665 I jxcore-log: 
,11-15 15:53:09.852  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-15 15:53:09.852  5618  5665 I jxcore-log: 
,11-15 15:53:09.858  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-15 15:53:09.858  5618  5665 I jxcore-log: 
,11-15 15:53:09.863  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-15 15:53:09.863  5618  5665 I jxcore-log: 
,11-15 15:53:09.876  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-15 15:53:09.876  5618  5665 I jxcore-log: 
,11-15 15:53:09.883  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-15 15:53:09.883  5618  5665 I jxcore-log: 
,11-15 15:53:09.905  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-15 15:53:09.905  5618  5665 I jxcore-log: 
,11-15 15:53:09.916  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-15 15:53:09.916  5618  5665 I jxcore-log: 
,11-15 15:53:09.928  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-15 15:53:09.928  5618  5665 I jxcore-log: 
,11-15 15:53:09.938  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-15 15:53:09.938  5618  5665 I jxcore-log: 
,11-15 15:53:09.951  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-15 15:53:09.951  5618  5665 I jxcore-log: 
,11-15 15:53:09.960  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-15 15:53:09.960  5618  5665 I jxcore-log: 
,11-15 15:53:09.967  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-15 15:53:09.967  5618  5665 I jxcore-log: 
,11-15 15:53:09.973  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-15 15:53:09.973  5618  5665 I jxcore-log: 
,11-15 15:53:09.979  5618  5665 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-15 15:53:09.980  5618  5665 I jxcore-log: 2016-11-15 14:53:09 - INFO testUtils: 'BLE multiple advertisement supported'
11-15 15:53:09.980  5618  5665 I jxcore-log: 
,11-15 15:53:10.136  5618  5665 I jxcore-log: 2016-11-15 14:53:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:10.136  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:10.136  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:10.136  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:10.136  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:10.136  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:10.136  5618  5665 I jxcore-log: 
,11-15 15:53:10.462  5618  5665 I jxcore-log: 2016-11-15 14:53:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:10.462  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:10.462  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:10.462  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:10.462  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:10.462  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:10.462  5618  5665 I jxcore-log: 
,11-15 15:53:10.467  5618  5665 I jxcore-log: 2016-11-15 14:53:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:10.467  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:10.467  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:10.467  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:10.467  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:10.467  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:10.467  5618  5665 I jxcore-log: 
,11-15 15:53:10.575   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:53:10.785  5618  5665 I jxcore-log: 2016-11-15 14:53:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:10.785  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:10.785  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:10.785  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:10.785  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:10.785  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:10.785  5618  5665 I jxcore-log: 
,11-15 15:53:10.790  5618  5665 I jxcore-log: 2016-11-15 14:53:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:10.790  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:10.790  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:10.790  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:10.790  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:10.790  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:10.790  5618  5665 I jxcore-log: 
,11-15 15:53:11.576   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:53:11.899  5618  5665 I jxcore-log: 2016-11-15 14:53:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:11.899  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:11.899  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:11.899  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:11.899  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:11.899  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:11.899  5618  5665 I jxcore-log: 
,11-15 15:53:11.903  5618  5665 I jxcore-log: 2016-11-15 14:53:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:11.903  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:11.903  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:11.903  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:11.903  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:11.903  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:11.903  5618  5665 I jxcore-log: 
,11-15 15:53:12.577   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:53:12.931  5618  5665 I jxcore-log: 2016-11-15 14:53:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:12.931  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:12.931  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:12.931  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:12.931  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:12.931  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:12.931  5618  5665 I jxcore-log: 
,11-15 15:53:12.937  5618  5665 I jxcore-log: 2016-11-15 14:53:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:12.937  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:12.937  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:12.937  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:12.937  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:12.937  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:12.937  5618  5665 I jxcore-log: 
,11-15 15:53:13.578   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 15:53:13.978  5618  5665 I jxcore-log: 2016-11-15 14:53:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:13.978  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:13.978  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:13.978  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:13.978  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:13.978  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:13.978  5618  5665 I jxcore-log: 
,11-15 15:53:13.982  5618  5665 I jxcore-log: 2016-11-15 14:53:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:13.982  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:13.982  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:13.982  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:13.982  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:13.982  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:13.982  5618  5665 I jxcore-log: 
,11-15 15:53:14.579   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 15:53:15.012  5618  5665 I jxcore-log: 2016-11-15 14:53:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:15.012  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:15.012  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:15.012  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:15.012  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:15.012  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:15.012  5618  5665 I jxcore-log: 
,11-15 15:53:15.016  5618  5665 I jxcore-log: 2016-11-15 14:53:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:15.016  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:15.016  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:15.016  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:15.016  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:15.016  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:15.016  5618  5665 I jxcore-log: 
,11-15 15:53:16.046  5618  5665 I jxcore-log: 2016-11-15 14:53:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:16.046  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:16.046  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:16.046  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:16.046  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:16.046  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:16.046  5618  5665 I jxcore-log: 
,11-15 15:53:16.049  5618  5665 I jxcore-log: 2016-11-15 14:53:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:16.049  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:16.049  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:16.049  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:16.049  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:16.049  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:16.049  5618  5665 I jxcore-log: 
,11-15 15:53:17.083  5618  5665 I jxcore-log: 2016-11-15 14:53:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:17.083  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:17.083  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:17.083  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:17.083  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:17.083  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:17.083  5618  5665 I jxcore-log: 
,11-15 15:53:17.089  5618  5665 I jxcore-log: 2016-11-15 14:53:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:17.089  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:17.089  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:17.089  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:17.089  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:17.089  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:17.089  5618  5665 I jxcore-log: 
,11-15 15:53:18.120  5618  5665 I jxcore-log: 2016-11-15 14:53:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:18.120  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:18.120  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:18.120  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:18.120  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:18.120  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:18.120  5618  5665 I jxcore-log: 
,11-15 15:53:18.126  5618  5665 I jxcore-log: 2016-11-15 14:53:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:18.126  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:18.126  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:18.126  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:18.126  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:18.126  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:18.126  5618  5665 I jxcore-log: 
,11-15 15:53:19.185  5618  5665 I jxcore-log: 2016-11-15 14:53:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:19.185  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:19.185  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:19.185  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:19.185  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:19.185  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:19.185  5618  5665 I jxcore-log: 
,11-15 15:53:19.189  5618  5665 I jxcore-log: 2016-11-15 14:53:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:19.189  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:19.189  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:19.189  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:19.189  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:19.189  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:19.189  5618  5665 I jxcore-log: 
,11-15 15:53:20.220  5618  5665 I jxcore-log: 2016-11-15 14:53:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:20.220  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:20.220  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:20.220  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:20.220  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:20.220  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:20.220  5618  5665 I jxcore-log: 
,11-15 15:53:20.226  5618  5665 I jxcore-log: 2016-11-15 14:53:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:20.226  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:20.226  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:20.226  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:20.226  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:20.226  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:20.226  5618  5665 I jxcore-log: 
,11-15 15:53:21.259  5618  5665 I jxcore-log: 2016-11-15 14:53:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:21.259  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:21.259  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:21.259  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:21.259  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:21.259  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:21.259  5618  5665 I jxcore-log: 
,11-15 15:53:21.263  5618  5665 I jxcore-log: 2016-11-15 14:53:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:21.263  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:21.263  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:21.263  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:21.263  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:21.263  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:21.263  5618  5665 I jxcore-log: 
,11-15 15:53:22.294  5618  5665 I jxcore-log: 2016-11-15 14:53:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:22.294  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:22.294  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:22.294  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:22.294  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:22.294  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:22.294  5618  5665 I jxcore-log: 
,11-15 15:53:22.298  5618  5665 I jxcore-log: 2016-11-15 14:53:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:22.298  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:22.298  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:22.298  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:22.298  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:22.298  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:22.298  5618  5665 I jxcore-log: 
,11-15 15:53:22.402  4058  4506 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-15 15:53:23.315  5618  5665 I jxcore-log: 2016-11-15 14:53:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:23.315  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:23.315  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:23.315  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:23.315  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:23.315  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:23.315  5618  5665 I jxcore-log: 
,11-15 15:53:23.316  5618  5665 I jxcore-log: 2016-11-15 14:53:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:23.316  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:23.316  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:23.316  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:23.316  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:23.316  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:23.316  5618  5665 I jxcore-log: 
,11-15 15:53:23.337  3613  5932 I VacuumService: Vacuum at: now=1479221603337 tag=VacuumService,
,11-15 15:53:23.463  3613  5935 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-15 15:53:23.497  3613  5933 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-15 15:53:23.499  3613  5933 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-15 15:53:23.523  3613  5933 W Uploader:  no longer exists, so no auth token.
,11-15 15:53:23.530  3613  5935 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 15:53:23.828  3613  5937 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 15:53:24.109  3613  5935 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 15:53:24.172  3613  5933 W Uploader:  no longer exists, so no auth token.
,11-15 15:53:24.183  3613  5937 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 15:53:24.260  3613  5935 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 15:53:24.336  3613  5937 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 15:53:24.338  5618  5665 I jxcore-log: 2016-11-15 14:53:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 15:53:24.338  5618  5665 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 15:53:24.338  5618  5665 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 15:53:24.338  5618  5665 I jxcore-log: emit@events.js:82:1
11-15 15:53:24.338  5618  5665 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 15:53:24.338  5618  5665 I jxcore-log: emit@events.js:82:1'
11-15 15:53:24.338  5618  5665 I jxcore-log: 
,11-15 15:53:24.345  5618  5665 E jxcore  : Error!: error is undefined
11-15 15:53:24.345  5618  5665 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-15 15:53:24.347  5618  5665 I jxcore-log: 2016-11-15 14:53:24 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-15 15:53:24.347  5618  5665 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-15 15:53:24.347  5618  5665 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-15 15:53:24.347  5618  5665 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-15 15:53:24.347  5618  5665 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-15 15:53:24.347  5618  5665 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-15 15:53:24.347  5618  5665 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-15 15:53:24.347  5618  5665 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-15 15:53:24.348  5618  5665 I jxcore-log: 2016-11-15 14:53:24 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-15 15:53:24.348  5618  5665 I jxcore-log: 
11-15 15:53:24.348  5618  5665 E jxcore-log: TypeError: 
11-15 15:53:24.349  5618  5665 E jxcore-log: error is undefined
11-15 15:53:24.349  5618  5665 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-15 15:53:24.349  5618  5665 E jxcore-log: 
,11-15 15:53:24.434   930  3850 D GraphicsStats: Buffer count: 2
,11-15 15:53:24.434   930  2986 D WifiService: Client connection lost with reason: 4
,11-15 15:53:24.434   930  3871 I WindowState: WIN DEATH: Window{eec2641 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-15 15:53:24.450   528   528 I Zygote  : Process 5618 exited cleanly (139)
,11-15 15:53:24.451   930  3850 I ActivityManager: Process com.test.thalitest (pid 5618) has died
,11-15 15:53:24.452   930  3850 W ActivityManager: Force removing ActivityRecord{985b7ae u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-15 15:53:24.497   930  3871 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5618 uid 10077
,11-15 15:53:24.502  3691  3691 I Keyboard.Facilitator: onFinishInput()
,11-15 15:53:24.498  3871  3871 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[29783]" dev="sockfs" ino=29783 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 15:53:24.498  3871  3871 W Binder_A: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[29783]" dev="sockfs" ino=29783 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 15:53:24.559  4013  5945 I MicroRecognitionRnrImpl: Starting detection.
,11-15 15:53:24.560  4013  5946 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d4fb621
,11-15 15:53:24.562   513  5948 I AudioFlinger: AudioFlinger's thread 0xf1ec0000 ready to run
,11-15 15:53:24.565   513  3033 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-15 15:53:24.567  4013  5946 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d4fb621
,11-15 15:53:24.577   513  5948 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-15 15:53:24.577   513  5948 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-15 15:53:24.577   513  5948 I ACDB-LOADER: ACDB AFE returned = -19
11-15 15:53:24.577   513  5948 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-15 15:53:24.577   513  5948 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-15 15:53:24.577   513  5948 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-15 15:53:24.584   513  5948 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-15 15:53:24.662  4013  4013 I HotwordWorkerImpl: onReady
,11-15 15:53:24.816  5941  5941 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-15 15:53:24.821  5941  5941 D AndroidRuntime: CheckJNI is OFF
,11-15 15:53:24.846  5941  5941 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-15 15:53:24.876  5941  5941 I Radio-JNI: register_android_hardware_Radio DONE
,11-15 15:53:24.891  5941  5941 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-15 15:53:24.898   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-15 15:53:25.028  3840  4047 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-15 15:53:25.056   930   953 I art     : Starting a blocking GC Explicit
,11-15 15:53:25.140   930   953 I art     : Explicit concurrent mark sweep GC freed 37278(2MB) AllocSpace objects, 8(260KB) LOS objects, 33% free, 28MB/43MB, paused 1.536ms total 83.437ms
,11-15 15:53:25.159   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-15 15:53:25.162  5941  5941 I art     : System.exit called, status: 0
,11-15 15:53:25.162  5941  5941 I AndroidRuntime: VM exiting with result code 0.
,11-15 15:53:25.166   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-15 15:53:25.180  3691  3691 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-15 15:53:25.181  5836  5836 D BluetoothMapAppObserver: onReceive
11-15 15:53:25.182  5836  5836 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-15 15:53:25.184  4058  4187 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-15 15:53:25.199   930  2976 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-15 15:53:25.200  3691  5959 I Keyboard.Facilitator.DecoderInitializer: run()
,11-15 15:53:25.211  3691  5959 I Decoder : createOrResetDecoder
,11-15 15:53:25.213  3434  5960 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-15 15:53:25.246   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-15 15:53:25.248  3815  3815 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-15 15:53:25.248    28    28 W kworker/1:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 15:53:25.251    28    28 W kworker/1:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 15:53:25.259  3840  3981 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-15 15:53:25.262  3613  3613 I ConfigService: onCreate
,11-15 15:53:25.268    28    28 W kworker/1:1: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 15:53:25.274  3434  5960 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-15 15:53:25.276   930   940 I ActivityManager: Start proc 5965:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-15 15:53:25.277  3840  3981 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-15 15:53:25.277  3840  3981 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3840
11-15 15:53:25.277  3840  3981 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:53:25.277  3840  3981 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-15 15:53:25.282   930  5976 E DropBoxManagerService: Can't write: system_app_crash
11-15 15:53:25.282   930  5976 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 15:53:25.282   930  5976 E DropBoxManagerService: 	... 5 more
11-15 15:53:25.282  3613  3613 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-15 15:53:25.282  3434  5960 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-15 15:53:25.282  3434  5960 E AndroidRuntime: Process: android.process.acore, PID: 3434
11-15 15:53:25.282  3434  5960 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:53:25.282  3434  5960 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-15 15:53:25.283  3613  3613 D AndroidRuntime: Shutting down VM
11-15 15:53:25.283  3613  3613 E AndroidRuntime: FATAL EXCEPTION: main
11-15 15:53:25.283  3613  3613 E AndroidRuntime: Process: com.google.process.gapps, PID: 3613
11-15 15:53:25.283  3613  3613 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-15 15:53:25.283  3613  3613 E AndroidRuntime: 	... 8 more
11-15 15:53:25.283   930  3190 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-15 15:53:25.288  4013  4029 W SearchService: Abort, client detached.
11-15 15:53:25.289  3691  5959 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-15 15:53:25.293  4013  4013 I HotwordDetector: Closing mic
11-15 15:53:25.293  4013  4247 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d4fb621
11-15 15:53:25.293  4013  5946 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 15:53:25.294  2977  2977 W Binder_4: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[27424]" dev="sockfs" ino=27424 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 15:53:25.294  2977  2977 W Binder_4: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[27424]" dev="sockfs" ino=27424 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 15:53:25.298   758   758 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33326]" dev="sockfs" ino=33326 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 15:53:25.299   930  5979 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-15 15:53:25.298   758   758 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[33326]" dev="sockfs" ino=33326 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 15:53:25.308   930  5980 E DropBoxManagerService: Can't write: system_app_crash
11-15 15:53:25.308   930  5980 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 15:53:25.308   930  5980 E DropBoxManagerService: 	... 5 more
11-15 15:53:25.319   930  5981 E DropBoxManagerService: Can't write: system_app_crash
11-15 15:53:25.319   930  5981 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 15:53:25.319   930  5981 E DropBoxManagerService: 	... 5 more
,11-15 15:53:25.342   930  5979 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 15:53:25.342   930  5979 I Adreno  : Build Date                       : 12/06/15
11-15 15:53:25.342   930  5979 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 15:53:25.342   930  5979 I Adreno  : Local Branch                     : mybranch17112971
11-15 15:53:25.342   930  5979 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 15:53:25.342   930  5979 I Adreno  : Remote Branch                    : NONE
11-15 15:53:25.342   930  5979 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 15:53:25.347   930  3871 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
11-15 15:53:25.350  3691  5959 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-15 15:53:25.351   930  5979 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 15:53:25.353  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-15 15:53:25.353  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-15 15:53:25.355  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-15 15:53:25.355  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-15 15:53:25.356  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-15 15:53:25.356  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-15 15:53:25.358  3691  5959 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-15 15:53:25.358  3691  5959 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-15 15:53:25.358  3691  5959 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-15 15:53:25.358  3691  5959 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-15 15:53:25.358  3691  5959 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-15 15:53:25.358  3691  5959 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-15 15:53:25.360   513  5948 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 15:53:25.361   513  5948 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-15 15:53:25.366   513  5948 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-15 15:53:25.367   513  5948 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 15:53:25.368   513  3033 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-15 15:53:25.371  4013  5945 I MicroRecognitionRnrImpl: Detection finished
,11-15 15:53:25.371  4013  4254 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-15 15:53:25.653   385   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
