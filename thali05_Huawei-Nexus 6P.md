#### Test 855940258c32634_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 04:37:27.043   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-21 04:37:27.043   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-21 04:37:27.518  5613  5613 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 04:37:27.524  5613  5613 D AndroidRuntime: CheckJNI is OFF
09-21 04:37:27.553  5613  5613 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 04:37:27.588  5613  5613 I Radio-JNI: register_android_hardware_Radio DONE
09-21 04:37:27.603  5613  5613 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 04:37:27.607   928  3404 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 04:37:27.622  5613  5613 D AndroidRuntime: Shutting down VM
09-21 04:37:27.623  4812  4822 W SearchService: Abort, client detached.
09-21 04:37:27.634  4812  4812 I HotwordDetector: Closing mic
09-21 04:37:27.635  4812  5469 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5715c63
09-21 04:37:27.654   928  3422 I ActivityManager: Start proc 5622:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 04:37:27.713   514  5601 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-21 04:37:27.714   514  5601 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
09-21 04:37:27.719   514  5601 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
09-21 04:37:27.720   514  5601 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-21 04:37:27.721   514  3000 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-21 04:37:27.723  4812  5470 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-21 04:37:27.723  4812  5597 I MicroRecognitionRnrImpl: Detection finished
09-21 04:37:27.751  5622  5622 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-21 04:37:27.773  5622  5622 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 04:37:27.793  5622  5622 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 9650-9667)
09-21 04:37:27.794  5622  5622 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 04:37:27.810  5622  5622 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {42548d6}
09-21 04:37:27.810  5622  5622 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 04:37:27.810  5622  5622 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-21 04:37:27.813  5622  5622 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-21 04:37:27.814  5622  5622 E SysUtils: ApplicationContext is null in ApplicationStatus
09-21 04:37:27.843  5622  5622 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 04:37:27.852  5622  5622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 04:37:27.852  5622  5622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 04:37:27.852  5622  5622 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 04:37:27.852  5622  5622 I Adreno  : Build Date                       : 12/06/15
09-21 04:37:27.852  5622  5622 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 04:37:27.852  5622  5622 I Adreno  : Local Branch                     : mybranch17112971
09-21 04:37:27.852  5622  5622 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 04:37:27.852  5622  5622 I Adreno  : Remote Branch                    : NONE
09-21 04:37:27.852  5622  5622 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 04:37:27.889   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b6ec775:true
,09-21 04:37:27.922  2938  2938 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32880]" dev="sockfs" ino=32880 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:27.922  2938  2938 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32880]" dev="sockfs" ino=32880 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:27.934  5622  5622 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 04:37:27.943  5622  5622 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 04:37:27.965  2938  2938 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[29609]" dev="sockfs" ino=29609 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:27.968  5622  5660 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-21 04:37:27.965  2938  2938 W Binder_5: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[29609]" dev="sockfs" ino=29609 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:27.969  3149  3149 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[17837]" dev="sockfs" ino=17837 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:27.969  3149  3149 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[17837]" dev="sockfs" ino=17837 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:37:27.972  5622  5647 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 04:37:27.995  5622  5660 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 04:37:28.055  3553  3553 W Binder_9: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[27637]" dev="sockfs" ino=27637 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:28.059   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +433ms
09-21 04:37:28.061  3420  3420 I Keyboard.Facilitator: onFinishInput()
09-21 04:37:28.055  3553  3553 W Binder_9: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[27637]" dev="sockfs" ino=27637 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:28.059  3553  3553 W Binder_9: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[27636]" dev="sockfs" ino=27636 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 04:37:28.059  3553  3553 W Binder_9: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[27636]" dev="sockfs" ino=27636 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 04:37:28.114  5622  5622 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5622
,09-21 04:37:28.202  5622  5622 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 04:37:28.338  5622  5662 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -583534288
,09-21 04:37:28.342  5622  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 04:37:28.342  5622  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 04:37:28.342  5622  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 04:37:28.342  5622  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 04:37:28.342  5622  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 04:37:28.342  5622  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91ee9c added. We now have 1 listener(s)
,09-21 04:37:28.345  5622  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-21 04:37:28.346  5622  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 04:37:28.346  5622  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 04:37:28.346  5622  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-21 04:37:28.348  5622  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2986c2b added. We now have 1 listener(s)
,09-21 04:37:28.349  5622  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 04:37:28.353   928  2973 D WifiService: New client listening to asynchronous messages
,09-21 04:37:28.354  5622  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 04:37:28.354  5622  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 04:37:28.354  5622  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 04:37:28.354  5622  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 04:37:28.354  5622  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 04:37:28.356  5622  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 04:37:28.357  5622  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 04:37:28.363  5622  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 04:37:28.364  5622  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 04:37:28.364  5622  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 04:37:28.364  5622  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 04:37:28.365  5622  5662 I io.jxcore.node.LifeCycleMonitor: start: OK
09-21 04:37:28.367  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 04:37:28.369  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 04:37:28.386  5622  5622 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 04:37:28.447   928  3149 I ActivityManager: Killing 4858:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-21 04:37:28.680  5622  5670 W jxcore-log: Initializing JXcore engine
,09-21 04:37:28.680  5622  5670 W jxcore-log: JXcore engine is ready
,09-21 04:37:28.702  5670  5670 W Thread-58: type=1400 audit(0.0:116): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1462 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-21 04:37:28.702  5670  5670 W Thread-58: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[15451]" dev="sockfs" ino=15451 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 04:37:28.702  5670  5670 W Thread-58: type=1400 audit(0.0:118): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 04:37:28.702  5670  5670 W Thread-58: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32022]" dev="sockfs" ino=32022 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 04:37:28.711  5622  5670 W jxcore-log: Starting JXcore engine
,09-21 04:37:28.762  5622  5670 W jxcore-log: Platform android
09-21 04:37:28.762  5622  5670 W jxcore-log: 
,09-21 04:37:28.762  5622  5670 W jxcore-log: Process ARCH arm
09-21 04:37:28.762  5622  5670 W jxcore-log: 
,09-21 04:37:28.848   928  2972 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-21 04:37:28.861  5622  5670 I jxcore-log: JXcore Cordova bridge is ready!
09-21 04:37:28.861  5622  5670 I jxcore-log: 
,09-21 04:37:28.862  5622  5670 W jxcore-log: JXcore engine is started
,09-21 04:37:28.871  5622  5662 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 04:37:28.876  5622  5622 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 04:37:37.044   540   540 I ServiceManager: Waiting for service AtCmdFwd...

```
