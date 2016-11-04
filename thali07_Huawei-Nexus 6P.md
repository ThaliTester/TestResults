#### Test 92005191e79faae_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 11:20:53.375  3926  4186 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-04 11:20:53.446  3926  4186 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-04 11:20:53.935  5570  5570 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 11:20:53.940  5570  5570 D AndroidRuntime: CheckJNI is OFF
11-04 11:20:53.966  5570  5570 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 11:20:53.999  5570  5570 I Radio-JNI: register_android_hardware_Radio DONE
11-04 11:20:54.014  5570  5570 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 11:20:54.027   928  3754 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 11:20:54.066  3908  3921 W SearchService: Abort, client detached.
11-04 11:20:54.067  5570  5570 D AndroidRuntime: Shutting down VM
11-04 11:20:54.074  3908  4176 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a68eaa9
11-04 11:20:54.074  3908  4183 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 11:20:54.074  3908  3908 I HotwordDetector: Closing mic
11-04 11:20:54.100   928  3563 I ActivityManager: Start proc 5579:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 11:20:54.154   513  4185 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 11:20:54.155   513  4185 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 11:20:54.158   513  4185 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 11:20:54.158   513  4185 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 11:20:54.159   513  2939 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 11:20:54.161  3908  4182 I MicroRecognitionRnrImpl: Detection finished
11-04 11:20:54.161  3908  4179 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 11:20:54.189  5579  5579 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 11:20:54.207  5579  5579 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-04 11:20:54.263  5579  5579 I LibraryLoader: Time to load native libraries: 52 ms (timestamps 9532-9584)
11-04 11:20:54.263  5579  5579 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 11:20:54.296  5579  5579 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3342e20}
,11-04 11:20:54.296  5579  5579 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 11:20:54.296  5579  5579 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 11:20:54.299  5579  5579 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 11:20:54.300  5579  5579 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 11:20:54.354  5579  5579 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 11:20:54.363  5579  5579 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 11:20:54.363  5579  5579 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 11:20:54.363  5579  5579 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 11:20:54.363  5579  5579 I Adreno  : Build Date                       : 12/06/15
11-04 11:20:54.363  5579  5579 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 11:20:54.363  5579  5579 I Adreno  : Local Branch                     : mybranch17112971
11-04 11:20:54.363  5579  5579 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 11:20:54.363  5579  5579 I Adreno  : Remote Branch                    : NONE
11-04 11:20:54.363  5579  5579 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 11:20:54.401   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bee7f6e:true
,11-04 11:20:54.441   951   951 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[15843]" dev="sockfs" ino=15843 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.441   951   951 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15843]" dev="sockfs" ino=15843 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.450  5579  5579 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 11:20:54.457  5579  5579 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 11:20:54.484   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33863]" dev="sockfs" ino=33863 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.484   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33863]" dev="sockfs" ino=33863 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 11:20:54.486  5579  5616 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 11:20:54.487  3759  3759 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30865]" dev="sockfs" ino=30865 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.487  3759  3759 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30865]" dev="sockfs" ino=30865 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.490  5579  5603 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 11:20:54.517  5579  5616 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 11:20:54.587  3358  3358 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33867]" dev="sockfs" ino=33867 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.587  3358  3358 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33867]" dev="sockfs" ino=33867 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 11:20:54.591   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +520ms
,11-04 11:20:54.591  3096  3096 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33866]" dev="sockfs" ino=33866 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:20:54.591  3096  3096 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33866]" dev="sockfs" ino=33866 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 11:20:54.595  3588  3588 I Keyboard.Facilitator: onFinishInput()
,11-04 11:20:54.636  5579  5579 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5579
,11-04 11:20:54.744  5579  5579 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 11:20:54.979  5579  5618 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -562038480
,11-04 11:20:54.984  5579  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 11:20:54.984  5579  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 11:20:54.984  5579  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 11:20:54.984  5579  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 11:20:54.984  5579  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 11:20:54.984  5579  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e26c037 added. We now have 1 listener(s)
,11-04 11:20:54.990  5579  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 11:20:54.990  5579  5618 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:20:54.991  5579  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:20:54.991  5579  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 11:20:54.993  5579  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86d72c2 added. We now have 1 listener(s)
11-04 11:20:54.993  5579  5618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:20:55.000   928  2890 D WifiService: New client listening to asynchronous messages
,11-04 11:20:55.001  5579  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:20:55.001  5579  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 11:20:55.001  5579  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-04 11:20:55.001  5579  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 11:20:55.001  5579  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 11:20:55.001  5579  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-04 11:20:55.001  5579  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-04 11:20:55.002  5579  5618 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 11:20:55.132   928  2889 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 11:20:55.132  5579  5579 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 11:20:55.448  5579  5588 I art     : Background sticky concurrent mark sweep GC freed 75488(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.417ms total 256.433ms
,11-04 11:20:56.207  5579  5588 I art     : Background partial concurrent mark sweep GC freed 59564(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.373ms total 121.426ms
,11-04 11:20:56.330  5579  5626 W jxcore-log: Initializing JXcore engine
,11-04 11:20:56.330  5579  5626 W jxcore-log: JXcore engine is ready
,11-04 11:20:56.354  5626  5626 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12309 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-04 11:20:56.354  5626  5626 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15491]" dev="sockfs" ino=15491 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-04 11:20:56.354  5626  5626 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-04 11:20:56.354  5626  5626 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33844]" dev="sockfs" ino=33844 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 11:20:56.365  5579  5626 W jxcore-log: Starting JXcore engine
,11-04 11:20:56.413  5579  5626 W jxcore-log: Platform android
11-04 11:20:56.413  5579  5626 W jxcore-log: 
,11-04 11:20:56.413  5579  5626 W jxcore-log: Process ARCH arm
11-04 11:20:56.413  5579  5626 W jxcore-log: 
,11-04 11:20:56.592  5579  5626 I jxcore-log: JXcore Cordova bridge is ready!
11-04 11:20:56.592  5579  5626 I jxcore-log: 
,11-04 11:20:56.592  5579  5626 W jxcore-log: JXcore engine is started
,11-04 11:20:56.602  5579  5618 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 11:20:56.608  5579  5579 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 11:20:57.502  3528  3528 I ConfigService: onDestroy
,11-04 11:20:58.428   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:20:59.091   928  3754 I ActivityManager: Killing 5366:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-04 11:20:59.123   928  3754 I ActivityManager: Killing 5021:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,11-04 11:20:59.429   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:00.430   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:01.431   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:02.432   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:03.433   547   547 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 11:21:06.300  5579  5626 I jxcore-log: 2016-11-04 10:21:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 11:21:06.300  5579  5626 I jxcore-log: 
,11-04 11:21:06.301  5579  5626 I jxcore-log: 2016-11-04 10:21:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 11:21:06.301  5579  5626 I jxcore-log: 
,11-04 11:21:06.306  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 11:21:06.306  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 11:21:06.308  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 11:21:06.310  5579  5626 I jxcore-log: 2016-11-04 10:21:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native',
11-04 11:21:06.310  5579  5626 I jxcore-log: 
11-04 11:21:06.312  5579  5626 I jxcore-log: 2016-11-04 10:21:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 11:21:06.312  5579  5626 I jxcore-log: 
,11-04 11:21:06.560  5579  5626 I jxcore-log: 2016-11-04 10:21:06 - DEBUG UnitTest_app: 'Running unit tests'
11-04 11:21:06.560  5579  5626 I jxcore-log: 
,11-04 11:21:06.561  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:21:06.561  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c302bc0 added. We now have 2 listener(s)
,11-04 11:21:06.561  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:21:06.562  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:21:06.562  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 11:21:06.562  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:21:06.562  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45750f9 added. We now have 2 listener(s)
11-04 11:21:06.562  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:21:06.562  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:21:06.563  5579  5626 D executeNativeTests: Running unit tests
,11-04 11:21:06.604  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 11:21:06.604  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee added. We now have 3 listener(s)
11-04 11:21:06.605  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:21:06.605  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:21:06.605  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 11:21:06.605  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:21:06.605  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f added. We now have 3 listener(s)
11-04 11:21:06.605  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:21:06.606  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:21:06.608  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-04 11:21:06.608  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 11:21:06.608  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 11:21:06.608  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 11:21:06.609  5579  5626 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 11:21:06.609  5579  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 11:21:06.609  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 11:21:06.609  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 11:21:06.609  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 11:21:06.609  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 11:21:06.610  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:06.610  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:06.610  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:06.610  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:06.611  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:06.611  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:21:06.611  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee removed from the list
11-04 11:21:06.611  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:06.611  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f removed from the list
11-04 11:21:06.611  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:06.611  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.612  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.612  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.612  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.612  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:06.612  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:06.612  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:06.612  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:06.613  5579  5626 D io.jxcore.node.ConnectionHelper: onBluetoothM,acAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 11:21:06.613  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:06.614  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:06.614  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:06.614  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:06.614  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:06.614  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:06.614  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:06.614  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:06.614  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:06.614  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.615  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:06.615  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.615  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.615  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:06.615  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 11:21:06.615  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:06.615  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-04 11:21:06.618  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 11:21:06.619  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:06.619  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:06.619  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:06.619  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:06.619  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:06.619  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:06.619  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:06.619  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:06.619  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:21:06.619  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.620  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.620  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.620  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.620  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:06.620  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:06.620  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:06.620  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:06.620  5579  5626 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 11:21:06.622  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:21:06.622  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 11:21:06.630  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 11:21:06.632  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:06.632  5579  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 11:21:06.632  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:21:06.632  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 11:21:06.632  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 11:21:06.632  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:21:06.632  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 11:21:06.634  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 11:21:06.634  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 11:21:06.634  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 11:21:06.636  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:06.638  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:06.638  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 11:21:06.638  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:06.639  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 11:21:06.639  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 11:21:06.639  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 11:21:06.640  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-04 11:21:06.641  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 11:21:06.641  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.641  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 11:21:06.641  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 11:21:06.641  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 11:21:06.642  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-04 11:21:06.642  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.642  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:21:06.644  4618  4849 D BtGatt.GattService: registerClient() - UUID=460e8455-32d4-4ceb-9e0e-a44a2f8b87db
,11-04 11:21:06.645  4618  4690 D BtGatt.GattService: onClientRegistered() - UUID=460e8455-32d4-4ceb-9e0e-a44a2f8b87db, clientIf=5
11-04 11:21:06.646  5579  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 11:21:06.648  4618  4829 D BtGatt.GattService: start scan with filters
,11-04 11:21:06.654  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 11:21:06.654  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:06.654  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 11:21:06.654  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.654  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 11:21:06.654  4618  4693 D BtGatt.ScanManager: handling starting scan
11-04 11:21:06.655  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 11:21:06.655  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 11:21:06.655  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 11:21:06.655  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 11:21:06.655  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 11:21:06.655  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.655  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.656  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.656  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:06.656  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:06.656  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.656  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 11:21:06.656  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.656  5579  5626 I io.jxcore.node.ConnectionHelper: start: OK
11-04 11:21:06.657  4618  4693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:21:06.659  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.659  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:21:06.659  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.659  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.659  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:21:06.660  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 11:21:06.668  4618  4690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 11:21:06.668  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:06.668  4618  4693 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 11:21:06.675  4618  4690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 11:21:06.675  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:06.675  4618  4693 D BtGatt.ScanManager: Starting BLE batch scan
11-04 11:21:06.676  4618  4693 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 11:21:06.687  4618  4690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 11:21:06.687  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:06.694  4618  4690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 11:21:06.694  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:07.088  3908  5627 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 11:21:07.157  4832  4872 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 11:21:07.157  4832  4832 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 11:21:07.161  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 11:21:07.161  5579  5579 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:21:07.161  5579  5579 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 11:21:11.660  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:11.660  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-04 11:21:11.660  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 11:21:11.661  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:21:11.661  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 11:21:11.661  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:11.661  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 11:21:11.661  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 11:21:11.661  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:21:11.661  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 11:21:11.662  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.662  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.662  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.662  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 11:21:11.663  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.664  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:21:11.664  4618  4630 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 11:21:11.664  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 11:21:11.665  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:21:11.666  4618  4693 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:21:11.666  4618  4849 D BtGatt.GattService: stopScan() - queue size =1
11-04 11:21:11.667  4618  4829 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 11:21:11.667  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 11:21:11.667  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:11.667  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-04 11:21:11.668  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:11.668  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.668  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:11.668  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.668  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 11:21:11.669  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.669  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.669  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.669  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 11:21:11.669  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 11:21:11.670  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:21:11.670  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.671  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.672  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:21:11.672  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.672  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:11.672  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:11.672  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:21:11.672  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:21:11.672  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:11.672  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:11.672  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:11.672  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:11.673  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:11.673  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:11.673  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 11:21:11.673  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:11.673  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 11:21:11.673  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.674  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 11:21:11.674  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 11:21:11.674  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.674  4618  4618 D BtGatt.ScanManager: awakened up at time 96996
11-04 11:21:11.674  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-04 11:21:11.676  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 11:21:11.676  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.679  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.679  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.679  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.679  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:21:11.679  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 11:21:11.703  4618  4690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-04 11:21:11.703  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:11.704  4618  4690 D BtGatt.GattService: current time is 97026114313
11-04 11:21:11.704  4618  4690 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -87, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -84, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -96, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-04 11:21:11.706  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 11:21:11.707  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 11:21:11.707  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 11:21:11.707  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 11:21:11.708  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 11:21:11.708  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-04 11:21:11.714  4618  4690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 11:21:11.714  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:11.714  4618  4693 D BtGatt.ScanManager: stopping BLe Batch
,11-04 11:21:11.721  4618  4690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 11:21:11.721  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:11.721  4618  4693 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:21:11.726  4618  4690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 11:21:11.726  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:12.180  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 11:21:16.682  5579  5626 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 11:21:16.687  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 11:21:16.688  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 11:21:16.701  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 11:21:16.704  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:16.704  5579  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 11:21:16.704  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:21:16.704  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 11:21:16.705  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-04 11:21:16.705  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:21:16.705  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 11:21:16.707  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:16.709  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 11:21:16.709  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 11:21:16.709  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 11:21:16.711  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:16.713  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:16.713  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 11:21:16.714  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 11:21:16.714  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 11:21:16.714  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 11:21:16.718  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:16.719  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 11:21:16.719  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 11:21:16.719  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 11:21:16.719  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 11:21:16.719  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.719  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:21:16.722  4618  4631 D BtGatt.GattService: registerClient() - UUID=eaa0410d-2c08-4c96-b97a-34cdefd6f4ba
11-04 11:21:16.722  4618  4690 D BtGatt.GattService: onClientRegistered() - UUID=eaa0410d-2c08-4c96-b97a-34cdefd6f4ba, clientIf=5
,11-04 11:21:16.722  5579  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 11:21:16.723  4618  4850 D BtGatt.GattService: start scan with filters
,11-04 11:21:16.727  4618  4693 D BtGatt.ScanManager: handling starting scan
11-04 11:21:16.728  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 11:21:16.728  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.728  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 11:21:16.728  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.728  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 11:21:16.729  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 11:21:16.729  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.729  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 11:21:16.729  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 11:21:16.729  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-04 11:21:16.729  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.729  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 11:21:16.730  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 11:21:16.730  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.733  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.733  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:21:16.733  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.733  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.733  5579  5626 I io.jxcore.node.ConnectionHelper: start: OK
11-04 11:21:16.733  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.736  4618  4690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 11:21:16.736  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.736  4618  4693 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 11:21:16.736  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.736  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.736  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.737  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.737  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 11:21:16.738  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:21:16.738  5579  5626 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 11:21:16.739  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:16.739  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 11:21:16.739  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:16.739  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 11:21:16.739  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:16.739  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 11:21:16.739  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.740  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:21:16.741  4618  4829 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 11:21:16.741  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 11:21:16.742  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:21:16.742  4618  4850 D BtGatt.GattService: stopScan() - queue size =1
11-04 11:21:16.743  4618  4690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 11:21:16.743  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.743  4618  4849 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 11:21:16.743  4618  4693 D BtGatt.ScanManager: Starting BLE batch scan
11-04 11:21:16.743  4618  4693 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 11:21:16.743  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 11:21:16.743  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.743  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.744  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 11:21:16.744  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 11:21:16.745  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:21:16.745  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.746  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.746  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:21:16.746  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04, 11:21:16.746  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.747  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:16.747  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:21:16.747  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:21:16.747  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:16.747  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:16.747  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:16.747  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:16.747  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 11:21:16.747  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:16.747  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.747  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:16.747  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 11:21:16.747  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:16.747  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 11:21:16.747  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 11:21:16.747  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.747  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.747  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 11:21:16.748  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.749  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.749  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.749  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.749  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.750  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:21:16.750  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.751  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.751  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.751  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.751  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:16.751  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:16.752  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:16.752  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:16.752  5579  5626 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 11:21:16.755  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:21:16.755  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 11:21:16.757  4618  4690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 11:21:16.757  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.764  4618  4690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 11:21:16.764  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 11:21:16.764  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.765  4618  4693 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 11:21:16.766  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:16.766  5579  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 11:21:16.766  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:21:16.766  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 11:21:16.766  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 11:21:16.766  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:21:16.766  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 11:21:16.771  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:16.772  4618  4690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:21:16.772  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.772  4618  4690 E BtGatt.ContextMap: Context not found for ID 5
11-04 11:21:16.773  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:16.773  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 11:21:16.773  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 11:21:16.774  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 11:21:16.777  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.778  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 11:21:16.778  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 11:21:16.778  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 11:21:16.778  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 11:21:16.779  4618  4690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 11:21:16.779  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.779  4618  4693 D BtGatt.ScanManager: stopping BLe Batch
11-04 11:21:16.782  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.782  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 11:21:16.782  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 11:21:16.782  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 11:21:16.783  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 11:21:16.783  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.783  4618  4690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 11:21:16.783  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.783  4618  4693 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 11:21:16.783  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:21:16.786  4618  4631 D BtGatt.GattService: registerClient() - UUID=9faaf20d-a5b3-4bbe-9f0c-887880e33e4b
11-04 11:21:16.787  4618  4690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:21:16.787  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.787  4618  4690 D BtGatt.GattService: onClientRegistered() - UUID=9faaf20d-a5b3-4bbe-9f0c-887880e33e4b, clientIf=5
11-04 11:21:16.788  5579  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 11:21:16.788  4618  4630 D BtGatt.GattService: start scan with filters
11-04 11:21:16.790  4618  4693 D BtGatt.ScanManager: handling starting scan
,11-04 11:21:16.790  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 11:21:16.790  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.790  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 11:21:16.790  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.791  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 11:21:16.791  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 11:21:16.791  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.791  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 11:21:16.791  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 11:21:16.791  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.791  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.791  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 11:21:16.792  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 11:21:16.792  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.794  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.794  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:21:16.794  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.794  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:16.794  4618  4690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 11:21:16.794  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.795  5579  5626 I io.jxcore.node.ConnectionHelper: start: OK
11-04 11:21:16.795  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.795  4618  4693 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 11:21:16.799  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.799  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.799  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.799  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:21:16.799  4618  4690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 11:21:16.799  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.799  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:21:16.799  4618  4693 D BtGatt.ScanManager: Starting BLE batch scan
11-04 11:21:16.799  4618  4693 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 11:21:16.806  4618  4690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 11:21:16.806  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:16.811  4618  4690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 11:21:16.811  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:17.300  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-04 11:21:17.301  5579  5579 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 11:21:17.301  5579  5579 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 11:21:21.795  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:21:21.795  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:21.796  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-04 11:21:21.796  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:21:21.796  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 11:21:21.796  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:21.796  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 11:21:21.796  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 11:21:21.796  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:21:21.797  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 11:21:21.797  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.797  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.797  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.798  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-04 11:21:21.798  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.802  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:21:21.803  4618  4630 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 11:21:21.804  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 11:21:21.805  4618  4693 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:21:21.806  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:21:21.808  4618  4829 D BtGatt.GattService: stopScan() - queue size =1
,11-04 11:21:21.810  4618  4849 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 11:21:21.811  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 11:21:21.811  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:21.811  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 11:21:21.811  4618  4618 D BtGatt.ScanManager: awakened up at time 107133
11-04 11:21:21.812  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.812  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.812  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.812  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:21.812  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 11:21:21.813  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.813  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.813  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.813  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 11:21:21.813  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 11:21:21.813   928  3754 I ActivityManager: Killing 5378:com.android.chrome/u0a39 (adj 15): empty #17
,11-04 11:21:21.837  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 11:21:21.837  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:21.839  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.840  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:21:21.840  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.840  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:21.840  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:21.840  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:21.840  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 11:21:21.840  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 11:21:21.840  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 11:21:21.841  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 11:21:21.841  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:21:21.841  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-04 11:21:21.841  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 11:21:21.841  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:21:21.842  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 11:21:21.843  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:21.843  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:21:21.843  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:21:21.843  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 11:21:21.851  4618  4690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-04 11:21:21.851  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:21.851  4618  4690 D BtGatt.GattService: current time is 107173473584
11-04 11:21:21.851  4618  4690 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -87, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -76, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 11:21:21.852  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 11:21:21.852  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 11:21:21.852  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-04 11:21:21.852  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-04 11:21:21.852  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 11:21:21.853  4618  4690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-04 11:21:21.858  4618  4690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 11:21:21.858  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:21.858  4618  4693 D BtGatt.ScanManager: stopping BLe Batch
,11-04 11:21:21.863  4618  4690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 11:21:21.863  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:21:21.863  4618  4693 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 11:21:21.868  4618  4690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:21:21.868  4618  4690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:21:22.344  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 11:21:22.344  5579  5579 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:22.345  5579  5579 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 11:21:26.842  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:21:26.842  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 11:21:26.842  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 11:21:26.842  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 11:21:26.843  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:21:26.843  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:21:26.843  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 11:21:26.843  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
,11-04 11:21:26.843  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:26.843  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.844  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:21:26.844  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 11:21:26.848  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.852  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.853  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.853  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.853  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 11:21:26.854  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.854  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.854  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.857  5579  5626 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-04 11:21:26.860  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:21:26.860  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.860  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.860  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.860  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.860  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.860  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.860  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.860  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.861  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.862  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.862  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.862  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.862  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.862  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.862  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.863  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.864  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 11:21:26.864  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.864  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.864  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 11:21:26.864  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.864  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.864  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.864  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.864  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.865  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.865  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.866  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.866  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.866  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.866  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.866  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.866  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.866  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.867  5579  5626 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 11:21:26.868  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.868  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.868  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.868  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.868  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.868  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
,11-04 11:21:26.868  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.868  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.868  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.868  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.870  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.870  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.870  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.870  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.870  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.870  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.870  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.871  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-04 11:21:26.871  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:21:26.872  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.872  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.872  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.872  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.872  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.872  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.872  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.872  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:21:26.872  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.873  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.874  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.874  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.874  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.874  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.874  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.874  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.875  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-04 11:21:26.875  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 11:21:26.875  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 11:21:26.875  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 11:21:26.875  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 11:21:26.875  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 11:21:26.875  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 11:21:26.876  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 11:21:26.876  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 11:21:26.876  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.876  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.876  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.876  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.876  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.876  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.876  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.876  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.876  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.877  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:26.879  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.879  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.879  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.879  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.879  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.879  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.880  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.881  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 11:21:26.882  5579  5626 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 11:21:26.882  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 11:21:26.887  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 11:21:26.887  5579  5626 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-04 11:21:26.887  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 11:21:26.887  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 11:21:26.887  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 11:21:26.887  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 11:21:26.887  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-04 11:21:26.888  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 11:21:26.889  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 11:21:26.890  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 11:21:26.890  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-04 11:21:26.890  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 11:21:26.890  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 11:21:26.890  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-04 11:21:26.891  5579  5626 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 11:21:26.891  5579  5626 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-04 11:21:26.891  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 11:21:26.891  5579  5626 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 11:21:26.891  5579  5626 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-04 11:21:26.891  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 11:21:26.891  5579  5626 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 11:21:26.892  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-04 11:21:26.899  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-04 11:21:26.900  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-04 11:21:26.900  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-04 11:21:26.900  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-04 11:21:26.900  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-04 11:21:26.900  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-04 11:21:26.901  5579  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 11:21:26.901  5579  5626 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-04 11:21:26.901  5579  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-04 11:21:26.901  5579  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-04 11:21:26.901  5579  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-04 11:21:26.901  5579  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-04 11:21:26.902  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.902  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.902  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.902  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.902  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.902  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-04 11:21:26.904  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.904  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.904  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.904  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.904  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.904  5579  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-04 11:21:26.904  5579  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-04 11:21:26.905  5579  5630 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-04 11:21:26.905  5579  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 11:21:26.904  4849  4849 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30589]" dev="sockfs" ino=30589 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 11:21:26.904  4849  4849 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30589]" dev="sockfs" ino=30589 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 11:21:26.905  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.906  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.906  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.906  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.906  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.906  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:26.906  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.907  5579  5626 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 11:21:26.907  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.907  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.908  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.908  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.908  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.908  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.908  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.908  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.908  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.908  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.909  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.909  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.909  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.909  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.909  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 11:21:26.909  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.910  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.910  5579  5626 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-04 11:21:26.910  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.911  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.911  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.911  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.911  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.911  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.911  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.911  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.911  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.911  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.912  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.912  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.913  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.913  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.913  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.913  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.913  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.914  5579  5626 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 11:21:26.914  5579  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-04 11:21:26.914  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 11:21:26.914  5579  5626 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 11:21:26.914  5579  5626 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 11:21:26.915  5579  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 11:21:26.915  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 11:21:26.915  5579  5626 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-04 11:21:26.915  5579  5626 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 11:21:26.915  5579  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 11:21:26.915  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 11:21:26.915  5579  5626 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 11:21:26.915  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:26.915  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:26.915  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:26.915  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.915  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.915  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.915  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:26.915  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.915  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:26.916  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.917  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.917  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.917  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:26.917  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:26.917  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:26.918  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.918  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:26.918  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:26.918  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:26.918  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:26.918  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:26.918  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:26.919  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:21:28.434   547   547 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-04 11:21:28.435   547   547 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 11:21:31.919  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:31.920  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:31.920  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.920  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:31.920  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
,11-04 11:21:31.920  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:31.921  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:31.921  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:31.921  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.921  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 11:21:31.922  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:31.922  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.922  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:31.922  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:31.922  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.927  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.928  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.929  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.929  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:31.929  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:31.929  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:31.930  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:31.936  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 11:21:31.938  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:21:31.939  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 11:21:31.945  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 11:21:31.946  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-04 11:21:31.946  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 11:21:31.947  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-04 11:21:31.947  5579  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-04 11:21:31.947  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 11:21:31.948  5579  5579 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 11:21:31.948  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 11:21:31.949  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.949  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 11:21:31.949  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-04 11:21:31.950  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 11:21:31.950  5579  5632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:21:31.950  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 11:21:31.950  4630  4630 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33921]" dev="sockfs" ino=33921 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 11:21:31.951  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 11:21:31.952  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-04 11:21:31.952  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:31.952  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:31.952  5579  5579 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 11:21:31.952  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 11:21:31.952  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:21:31.952  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 11:21:31.950  4630  4630 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33921]" dev="sockfs" ino=33921 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 11:21:31.953  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.955  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.955  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:21:31.955  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.955  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.955  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:31.955  5579  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 11:21:31.956  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:31.956  5579  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 11:21:31.956  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 11:21:31.956  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:31.956  5579  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 11:21:31.956  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:21:31.956  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:31.956  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:21:31.956  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.956  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 11:21:31.956  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:31.956  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.956  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:31.956  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:31.956  5579  5579 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 11:21:31.957  5579  5579 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:31.957  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.959  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.959  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.959  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.959  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:31.959  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:31.959  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.960  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:31.962  5579  5626 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-04 11:21:31.962  5579  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 11:21:31.962  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 11:21:31.963  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 11:21:31.963  5579  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 11:21:31.963  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:31.963  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:31.963  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:31.963  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.963  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:31.964  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:31.964  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.964  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:31.964  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:31.964  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.966  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.966  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.967  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.967  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:31.967  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:31.967  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.967  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:31.972  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:21:31.973  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:31.973  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:31.973  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.973  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 11:21:31.973  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:31.973  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.973  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:31.973  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:31.973  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.975  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.975  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.975  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.975  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:31.976  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:31.976  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.976  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
11-04 11:21:31.977  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:21:31.977  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:21:31.977  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:21:31.977  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:21:31.977  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:21:31.977  5579  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac7cee not in the list
11-04 11:21:31.978  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.978  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:31.978  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:31.978  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.979  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:21:31.980  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.980  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:21:31.980  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:21:31.980  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:21:31.980  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:21:31.980  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895e58f not in the list
,11-04 11:21:31.983  5579  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-04 11:21:31.983  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 11:21:31.983  5579  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 11:21:31.983  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 11:21:31.983  5579  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 11:21:31.983  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 11:21:31.986  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 11:21:31.986  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 11:21:31.986  5579  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-04 11:21:31.987  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 11:21:31.987  5579  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 11:21:31.987  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 11:21:31.987  5579  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-04 11:21:31.987  5579  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-04 11:21:31.987  5579  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 11:21:31.988  5579  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-04 11:21:31.988  5579  5626 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 11:21:31.988  5579  5626 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 11:21:31.988  5579  5626 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-04 11:21:31.989  5579  5626 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 11:21:31.989  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:21:31.990  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d0284c added. We now have 3 listener(s)
11-04 11:21:31.990  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:21:31.992  5579  5626 D BluetoothAdapter: enable(): BT is already enabled..!
11-04 11:21:31.993   928  3542 D WifiService: setWifiEnabled: true pid=5579, uid=10077
11-04 11:21:31.993   928  3542 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 11:21:32.033  4618  4822 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-04 11:21:32.033  4618  4827 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-04 11:21:32.033  5579  5630 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-04 11:21:32.034  5579  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-04 11:21:32.034  5579  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-04 11:21:32.457  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 11:21:33.436   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:34.437   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:35.137   928  2889 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 11:21:35.437   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:36.438   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:36.999  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:21:36.999  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b08095 added. We now have 4 listener(s)
,11-04 11:21:36.999  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:21:37.013  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:37.014  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b08095 removed from the list
,11-04 11:21:37.014  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:21:37.017  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:21:37.017  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9255aa added. We now have 4 listener(s)
,11-04 11:21:37.017  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:21:37.021  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:21:37.021  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9255aa removed from the list
,11-04 11:21:37.021  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:21:37.024  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:21:37.025  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e4759b added. We now have 4 listener(s)
11-04 11:21:37.026  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:21:37.032   928  3140 D WifiService: setWifiEnabled: false pid=5579, uid=10077
,11-04 11:21:37.032   928  3140 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 11:21:37.038   928  2889 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 11:21:37.039   928  2889 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 11:21:37.039   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 11:21:37.039   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 11:21:37.045  4618  4686 D BluetoothAdapterState: Current state: ON, message: 23
,11-04 11:21:37.045  4618  4686 D BluetoothAdapterProperties: Setting state to 13
11-04 11:21:37.045  4618  4686 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 11:21:37.045  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 11:21:37.045  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 11:21:37.046  4618  4686 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 11:21:37.048  4618  4686 I BluetoothAdapterState: Entering PendingCommandState
11-04 11:21:37.050  4618  4690 D BluetoothAdapterProperties: Scan Mode:20
11-04 11:21:37.050  4618  4686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 11:21:37.052  4618  4618 D BluetoothMapService: onReceive
11-04 11:21:37.052  4618  4618 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 11:21:37.052  4618  4618 D BluetoothMapService: STATE_TURNING_OFF
11-04 11:21:37.053  4618  4618 D BluetoothMapService: MAP Service closeService in
,11-04 11:21:37.053  4618  4618 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 11:21:37.053  4618  4618 D ObexServerSockets0: shutdown(block = true)
11-04 11:21:37.053   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-04 11:21:37.053  4618  4618 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 11:21:37.054  4618  4852 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-04 11:21:37.054  4618  4618 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 11:21:37.054  4618  4853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 11:21:37.054  4618  4827 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 11:21:37.055   928  5339 D DhcpClient: Clearing IP address
11-04 11:21:37.057  4618  4618 I BtOppRfcommListener: stopping Accept Thread
11-04 11:21:37.057  4618  5267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 11:21:37.058  4618  5267 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-04 11:21:37.059  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 11:21:37.059  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 11:21:37.060  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:37.060  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 11:21:37.061  5579  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 11:21:37.062   508   922 D CommandListener: Setting iface cfg
,11-04 11:21:37.064  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:37.066  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:37.069  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:37.071  3528  5392 V NativeCrypto: Read error: ssl=0x7f8bd36e00: I/O error during system call, Connection timed out
,11-04 11:21:37.072  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:37.073  3528  5392 V NativeCrypto: SSL shutdown failed: ssl=0x7f8bd36e00: I/O error during system call, Broken pipe
,11-04 11:21:37.075   928  3542 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-04 11:21:37.075   928  5335 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-04 11:21:37.076   928  5340 D DhcpClient: Receive thread stopped
,11-04 11:21:37.077   928  5335 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-04 11:21:37.077   928  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-04 11:21:37.078   928  2891 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 11:21:37.079   928  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 11:21:37.087   928   941 I ActivityManager: Start proc 5636:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-04 11:21:37.091   928  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 11:21:37.091   928  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-04 11:21:37.091  4618  4618 D HeadsetService: Received stop request...Stopping profile...
,11-04 11:21:37.093   542   542 E Parcel  : Reading a NULL string not supported here.
,11-04 11:21:37.096   928   928 D BluetoothHeadset: Proxy object disconnected
,11-04 11:21:37.096   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:37.096   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:37.097  3072  3084 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:37.097  3724  3745 D BluetoothHeadset: Proxy object disconnected
,11-04 11:21:37.098   928   928 D RttService: SCAN_AVAILABLE : 1
11-04 11:21:37.098  3072  3072 D HeadsetProfile: Bluetooth service disconnected
11-04 11:21:37.098   928  2999 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-04 11:21:37.098  4618  4618 D A2dpService: Received stop request...Stopping profile...
11-04 11:21:37.099  4618  4834 D A2dpStateMachine: Exit Disconnected: -1
11-04 11:21:37.099   928   928 D BluetoothA2dp: Proxy object disconnected
,11-04 11:21:37.100   928  2891 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-04 11:21:37.100  4618  4618 D HidService: Received stop request...Stopping profile...
11-04 11:21:37.100  4618  4618 D HidService: Stopping Bluetooth HidService
11-04 11:21:37.102  3680  3797 W QCNEJ   : |CORE| network lost: 100
,11-04 11:21:37.103  3680  3797 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 11:21:37.106  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.106  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.106  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.106  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:37.107  4618  4618 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 11:21:37.107  4618  4618 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 11:21:37.108  4618  4822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:37.108  4618  4822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:37.108  4618  4822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:37.108  4618  4690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 11:21:37.108  4618  4690 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 11:21:37.108  4618  4618 D HealthService: Received stop request...Stopping profile...
,11-04 11:21:37.110  4618  4618 D PanService: Received stop request...Stopping profile...
,11-04 11:21:37.112  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.112  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.112  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.112  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:37.112   928  2889 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 11:21:37.113  4618  4822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 11:21:37.114  4618  4822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 11:21:37.115  4618  4822 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 11:21:37.115  4618  4822 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-04 11:21:37.115  4618  4822 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 11:21:37.115  4618  4822 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 11:21:37.115  4618  4690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 11:21:37.117  4618  4618 D BluetoothMapService: Received stop request...Stopping profile...
11-04 11:21:37.117  4618  4618 D BluetoothMapService: stop()
11-04 11:21:37.117  4618  4618 D BluetoothMapAppObserver: deinitObservers()
11-04 11:21:37.117  4618  4618 D BluetoothMapAppObserver: removeReceiver()
11-04 11:21:37.118  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.118  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.119  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.119  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:37.119  4618  4618 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 11:21:37.119  4618  4618 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 11:21:37.119  4618  4690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 11:21:37.120  4618  4618 D SapService: Received stop request...Stopping profile...
11-04 11:21:37.120  4618  4618 V SapService: stop()
11-04 11:21:37.121  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.121  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.121  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.121  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:37.121  4618  4618 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-04 11:21:37.121  4618  4690 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 11:21:37.122   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 11:21:37.124  4618  4618 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 11:21:37.125  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.125  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.125  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.125  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:37.125  4618  4618 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 11:21:37.126  4618  4618 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 11:21:37.127  4618  4618 D BluetoothMapService: MAP Service closeService in
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 11:21:37.127  4618  4618 D BluetoothMapService: cleanup()
11-04 11:21:37.127  4618  4618 D BluetoothMapService: MAP Service closeService in
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:37.127  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.128  4618  4618 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:37.128  4618  4686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 11:21:37.128  4618  4686 D BluetoothAdapterProperties: Setting state to 15
11-04 11:21:37.128  4618  4686 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 11:21:37.129  3072  3083 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 11:21:37.128  4618  4686 I BluetoothAdapterState: Entering BleOnState
,11-04 11:21:37.129   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 11:21:37.129  3072  3084 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:37.130  3072  3275 D BluetoothMap: onBluetoothStateChange: up=false
11-04 11:21:37.131  3072  3072 D BluetoothA2dp: Proxy object disconnected
11-04 11:21:37.132  3072  3084 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 11:21:37.132  3072  3072 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 11:21:37.132  3072  3072 D PanProfile: Bluetooth service disconnected
11-04 11:21:37.132   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:37.132  3072  3083 D BluetoothPan: onBluetoothStateChange on: false
11-04 11:21:37.133  3724  3751 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:37.133   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:37.133  3072  3275 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 11:21:37.134   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:37.135  4618  4686 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-04 11:21:37.135  4618  4686 D BluetoothAdapterProperties: Setting state to 16
11-04 11:21:37.135  4618  4686 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 11:21:37.135  4618  4686 D BluetoothAdapterProperties: onBleDisable
11-04 11:21:37.136  4618  4686 I BluetoothAdapterState: Entering PendingCommandState
11-04 11:21:37.136  4618  4687 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 11:21:37.137  4618  4690 D BluetoothAdapterProperties: Scan Mode:20
11-04 11:21:37.138  4618  4822 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 11:21:37.138  4618  4822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 11:21:37.139  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:21:37.139  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 11:21:37.139  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:37.139  5579  5579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 11:21:37.141  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:37.141  5636  5636 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-04 11:21:37.151   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 11:21:37.159  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 11:21:37.164   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2eb23c7:true
,11-04 11:21:37.165  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 11:21:37.171   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 11:21:37.171   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-04 11:21:37.172   508   922 D TetherController: Setting IP forward enable = 0
,11-04 11:21:37.173   928  2891 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-04 11:21:37.173   928  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 11:21:37.180   928   939 I ActivityManager: Start proc 5660:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-04 11:21:37.182   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-04 11:21:37.185   928  2889 D DhcpClient: doQuit
,11-04 11:21:37.185   928  2889 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 11:21:37.186   928  5339 D DhcpClient: onQuitting
11-04 11:21:37.187  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:37.189  3390  3390 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 11:21:37.190  5240  5240 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@86a8cbb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-04 11:21:37.192  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:21:37.192  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 11:21:37.193  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:37.193  5579  5579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 11:21:37.193  3908  3908 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 11:21:37.204  5636  5636 D LocalBluetoothProfileManager: Adding local MAP profile
,11-04 11:21:37.207  5636  5636 D BluetoothMap: Create BluetoothMap proxy object
,11-04 11:21:37.226  3390  3390 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 11:21:37.229  5636  5636 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-04 11:21:37.230  3390  3390 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 11:21:37.234   508   922 E Netd    : netlink response contains error (No such file or directory)
,11-04 11:21:37.234   508   922 D TetherController: Setting IP forward enable = 0
11-04 11:21:37.235   928  2891 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 11:21:37.235   928  2891 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 11:21:37.246  5660  5660 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 11:21:37.249  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-04 11:21:37.256  3390  3390 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 11:21:37.259   928  3759 I ActivityManager: Killing 4397:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-04 11:21:37.268  3390  3390 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 11:21:37.345  4618  4690 I bt_hci  : shut_down
,11-04 11:21:37.349  4618  4694 D bt_hwcfg: hw_epilog_process
,11-04 11:21:37.349  4618  4694 I bt_vendor: low_power_mode_cb
,11-04 11:21:37.352  4618  4694 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 11:21:37.352  4618  4694 I bt_vendor: epilog_cb
11-04 11:21:37.352  4618  4694 I bt_hci  : epilog_finished_callback
11-04 11:21:37.355  4618  4690 I bt_hci_h4: hal_close
,11-04 11:21:37.355  4618  4690 I bt_userial_vendor: device fd = 54 close
,11-04 11:21:37.373   928  2889 D wifi    : In wifi stop Hal
,11-04 11:21:37.373   928  2889 D wifi    : halHandle = 0x7f89eaa180, mVM = 0x7fa650d140, mCls = 0x100a02
11-04 11:21:37.373  4444  4444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 11:21:37.373   928  3389 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 11:21:37.373   928  3389 D WifiHAL : Got a signal to exit!!!
11-04 11:21:37.373   928  3389 I WifiHAL : Exit wifi_event_loop
11-04 11:21:37.374   928  2889 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-04 11:21:37.374   928  2889 E WifiHAL : Event processing terminated
11-04 11:21:37.374   928  2889 D wifi    : In wifi cleaned up handler
11-04 11:21:37.374   928  2889 I WifiHAL : Internal cleanup completed
11-04 11:21:37.375  3657  4125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 11:21:37.376  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:37.396   928  3389 D wifi    : set interface wlan0 flags (DOWN)
,11-04 11:21:37.397   928  2889 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 11:21:37.439   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:37.464  4618  4687 D bt_stack_manager: event_shut_down_stack finished.
,11-04 11:21:37.464  4618  4686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-04 11:21:37.466  4618  4618 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 11:21:37.466  4618  4686 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 11:21:37.467  4618  4618 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 11:21:37.467  4618  4618 D BtGatt.GattService: stop()
11-04 11:21:37.467  4618  4618 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 11:21:37.468  4618  4618 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:37.468  4618  4618 V BluetoothAdapterState: isTurningOn()=false
,11-04 11:21:37.468  4618  4618 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:37.468  4618  4618 V BluetoothAdapterState: isBleTurningOff()=true
11-04 11:21:37.469  4618  4686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 11:21:37.469  4618  4686 D BluetoothAdapterProperties: Setting state to 10
11-04 11:21:37.469  4618  4686 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 11:21:37.469  4618  4686 I BluetoothAdapterState: Entering OffState
11-04 11:21:37.470   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-04 11:21:37.478  4618  4618 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-04 11:21:37.478  4618  4618 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 11:21:37.478  4618  4618 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 11:21:37.480  4618  4687 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-04 11:21:37.487  4618  4618 I art     : System.exit called, status: 0
11-04 11:21:37.487  4618  4618 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.521  5660  5660 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.521  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.522  5660  5660 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 11:21:37.522  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 11:21:37.526  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 11:21:37.529   928  3358 I ActivityManager: Process com.android.bluetooth (pid 4618) has died
11-04 11:21:37.542   928  3754 I ActivityManager: Start proc 5702:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-04 11:21:37.544  5636  5636 D DockEventReceiver: finishStartingService: stopping service
11-04 11:21:37.546   928   939 I ActivityManager: Killing 5085:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-04 11:21:37.599   928   945 D Tethering: InitialState.processMessage what=4
11-04 11:21:37.601   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 11:21:37.629  5702  5702 D AdapterServiceConfig: Adding HeadsetService
,11-04 11:21:37.629  5702  5702 D AdapterServiceConfig: Adding A2dpService
11-04 11:21:37.629  5702  5702 D AdapterServiceConfig: Adding HidService
11-04 11:21:37.630  5702  5702 D AdapterServiceConfig: Adding HealthService
11-04 11:21:37.630  5702  5702 D AdapterServiceConfig: Adding PanService
11-04 11:21:37.630  5702  5702 D AdapterServiceConfig: Adding GattService
,11-04 11:21:37.630  5702  5702 D AdapterServiceConfig: Adding BluetoothMapService
11-04 11:21:37.630  5702  5702 D AdapterServiceConfig: Adding SapService
11-04 11:21:37.632   928  3563 I ActivityManager: Killing 5410:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-04 11:21:37.676  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 11:21:37.687  3926  3926 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 11:21:37.692  3926  3926 D SystemUpdateService: onCreate
,11-04 11:21:37.695  3926  3926 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 11:21:37.703  3926  3926 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 11:21:37.708  3926  4214 I iu.UploadsManager: num queued entries: 0
,11-04 11:21:37.708  3926  4214 I iu.UploadsManager: num updated entries: 0
11-04 11:21:37.709  3926  4214 I iu.SyncManager: NEXT; no task
,11-04 11:21:37.711  3926  3926 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 11:21:37.713  3926  3926 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 11:21:37.714  3926  5714 I SystemUpdateService: active receiver: enabled
,11-04 11:21:37.725   928  3754 I ActivityManager: Start proc 5716:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-04 11:21:37.728  3926  5714 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 11:21:37.730  3926  5714 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-04 11:21:37.730  3926  5714 I SystemUpdateService: now status is 0 (complete)
,11-04 11:21:37.730  3926  5714 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-04 11:21:37.732  3926  5714 I SystemUpdateService: file has been verified
11-04 11:21:37.732  3926  5714 I SystemUpdateService: OTA package size = 21989297
,11-04 11:21:37.762  5716  5716 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-04 11:21:37.765  3926  5714 I SystemUpdateService: showing system update notification
,11-04 11:21:37.767  5716  5716 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 11:21:37.773  5716  5716 D SprintDMHelper: simOperator: 
11-04 11:21:37.773  5716  5716 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 11:21:37.785   928  3358 I ActivityManager: Start proc 5728:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-04 11:21:37.800   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 11:21:37.805  3926  3926 D SystemUpdateService: onDestroy
,11-04 11:21:37.807   928  3358 I ActivityManager: Killing 5397:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-04 11:21:37.893   928  3564 I ActivityManager: Start proc 5744:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-04 11:21:37.896   928  3542 I ActivityManager: Killing 5240:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 11:21:37.932  5660  5689 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 11:21:37.956  5744  5744 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-04 11:21:38.012   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5afea66:true
,11-04 11:21:38.148   928   938 I ActivityManager: Killing 3825:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-04 11:21:38.196   928  3140 I ActivityManager: Start proc 5758:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 11:21:38.228  5758  5758 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 11:21:38.236   928  4228 I ActivityManager: Killing 5455:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-04 11:21:38.439   547   547 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 11:21:42.064   928  3779 D WifiService: setWifiEnabled: true pid=5579, uid=10077
,11-04 11:21:42.064   928  3779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 11:21:42.073   508   922 D SoftapController: Softap fwReload - Ok
,11-04 11:21:42.080   508   922 D CommandListener: Setting iface cfg
,11-04 11:21:42.080   508   922 D CommandListener: Trying to bring down wlan0
,11-04 11:21:42.082   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-04 11:21:42.090   928  2889 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 11:21:42.662   928  2889 D wifi    : set interface wlan0 flags (UP)
,11-04 11:21:42.664   928  2889 I WifiHAL : Initializing wifi
11-04 11:21:42.664   928  2889 I WifiHAL : Creating socket
11-04 11:21:42.666   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 11:21:42.669   928  2889 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 11:21:42.669   928  2889 D wifi    : Did set static halHandle = 0x7f89eaa180
11-04 11:21:42.669   928  2889 D wifi    : halHandle = 0x7f89eaa180, mVM = 0x7fa650d140, mCls = 0x1912
11-04 11:21:42.669   928  2889 D wifi    : array field set
11-04 11:21:42.670   928  2889 I WifiNative-HAL: interface[0] = wlan0
11-04 11:21:42.671   928  5778 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547774701952
11-04 11:21:42.671   928  5778 D wifi    : waitForHalEvents called, vm = 0x7fa650d140, obj = 0x1912, env = 0x7f875e32c0
,11-04 11:21:42.674   928  2889 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 11:21:42.677   928  2889 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,11-04 11:21:42.681  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:42.734  5779  5779 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 11:21:42.791  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 11:21:42.853  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-04 11:21:42.854  5779  5779 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 11:21:43.440   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:43.688   928  2889 D WifiConfigStore: Loading config and enabling all networks 
,11-04 11:21:43.692  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:21:43.692  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 11:21:43.692  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:43.693  5579  5579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 11:21:43.723   928  2889 D WifiConfigStore: loaded 0 passpoint configs
,11-04 11:21:43.724   928  2889 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 11:21:43.725   928  2889 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 11:21:43.726   928  2889 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 11:21:43.726   928  2889 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 11:21:43.727   928  2889 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 11:21:43.728   928  2889 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-04 11:21:43.728   928  2889 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 11:21:43.728   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 11:21:43.729   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 11:21:43.729   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 11:21:43.729   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-04 11:21:43.729   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 11:21:43.732   928  2889 D WifiNative-HAL: Setting external_sim to 1
,11-04 11:21:43.732  4444  4444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 11:21:43.733   928  2889 D wifi    : setting dfs flag to true, 0x7f8b122320
,11-04 11:21:43.734   928  2889 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 11:21:43.734   928  2889 D wifi    : setting scan oui 0x7f8b122320
11-04 11:21:43.734   928  2889 D WifiHAL : Sending mac address OUI
,11-04 11:21:43.738   928  2889 E native  : do suspend false
,11-04 11:21:43.746   928  2889 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 11:21:43.746   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 11:21:43.746   928   928 D RttService: SCAN_AVAILABLE : 3
,11-04 11:21:43.746   928  2999 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 11:21:43.747   508   922 D CommandListener: Setting iface cfg
,11-04 11:21:43.751   928  2888 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-04 11:21:43.751   928  2888 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 11:21:43.761   928  2888 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 11:21:43.766   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129088 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
11-04 11:21:43.766   928  2888 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 11:21:44.442   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:45.442   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:46.443   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:46.850  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 11:21:46.855  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 11:21:46.859  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 11:21:46.864  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 11:21:46.909   928  2889 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 11:21:46.911   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 11:21:46.911   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 11:21:46.924   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 11:21:46.958   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 11:21:46.964  5779  5779 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 11:21:47.070   928  3754 D WifiService: setWifiEnabled: false pid=5579, uid=10077
,11-04 11:21:47.070   928  3754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 11:21:47.075   928   928 D RttService: SCAN_AVAILABLE : 1
,11-04 11:21:47.076   928  2999 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 11:21:47.088   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 11:21:47.089   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-04 11:21:47.096   928  2889 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 11:21:47.097  5779  5779 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 11:21:47.103  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:21:47.103  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 11:21:47.103  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:47.103  5579  5579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 11:21:47.114  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 11:21:47.121  5779  5779 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-04 11:21:47.150  5779  5779 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 11:21:47.157  5779  5779 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 11:21:47.261  4444  4444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 11:21:47.261   928  2889 D wifi    : In wifi stop Hal
11-04 11:21:47.265  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:47.264   928  2889 D wifi    : halHandle = 0x7f89eaa180, mVM = 0x7fa650d140, mCls = 0x1912
11-04 11:21:47.266   928  5778 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 11:21:47.266   928  5778 D WifiHAL : Got a signal to exit!!!
11-04 11:21:47.267   928  5778 I WifiHAL : Exit wifi_event_loop
11-04 11:21:47.268   928  2889 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-04 11:21:47.268   928  2889 E WifiHAL : Event processing terminated
11-04 11:21:47.269   928  2889 D wifi    : In wifi cleaned up handler
,11-04 11:21:47.269   928  2889 I WifiHAL : Internal cleanup completed
11-04 11:21:47.276  3657  4125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 11:21:47.306   928  5778 D wifi    : set interface wlan0 flags (DOWN)
,11-04 11:21:47.307   928  2889 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 11:21:47.444   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:47.512   928   945 D Tethering: InitialState.processMessage what=4
,11-04 11:21:47.519   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 11:21:48.445   547   547 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 11:21:52.107   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c303c84:true
,11-04 11:21:52.108  5702  5702 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 11:21:52.113  5702  5783 I BluetoothAdapterState: Entering OffState
,11-04 11:21:52.114  5702  5702 I bt_bluedroid: init
,11-04 11:21:52.117  5702  5784 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 11:21:52.117  5702  5784 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 11:21:52.117  5702  5784 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-04 11:21:52.117  5702  5784 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-04 11:21:52.119  5702  5702 I bt_bluedroid: get_profile_interface socket
,11-04 11:21:52.121  5702  5787 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 11:21:52.121  5702  5702 I bt_bluedroid: get_profile_interface sdp
11-04 11:21:52.122  5702  5787 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 11:21:52.127  5702  5712 I bt_bluedroid: config_hci_snoop_log
,11-04 11:21:52.129   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 11:21:52.134  5702  5783 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 11:21:52.134  5702  5783 D BluetoothAdapterProperties: Setting state to 14
11-04 11:21:52.134  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 11:21:52.135  5702  5783 D BluetoothBondStateMachine: make
,11-04 11:21:52.137  5702  5788 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 11:21:52.141  5702  5783 I BluetoothAdapterState: Entering PendingCommandState
,11-04 11:21:52.142  5702  5702 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 11:21:52.144  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:52.145  5702  5702 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 11:21:52.145  5702  5702 D BtGatt.GattService: Received start request. Starting profile...
11-04 11:21:52.145  5702  5702 D BtGatt.GattService: start()
11-04 11:21:52.146  5702  5702 I bt_bluedroid: get_profile_interface gatt
11-04 11:21:52.146  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:52.146  5702  5702 D BtGatt.AdvertiseManager: advertise manager created
,11-04 11:21:52.151  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,11-04 11:21:52.152  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:52.152  5702  5702 V BluetoothAdapterState: isBleTurningOn()=true
11-04 11:21:52.152  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:52.152  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 11:21:52.154  5702  5783 I bt_bluedroid: bt_bluedroid
,11-04 11:21:52.154  5702  5784 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 11:21:52.154  5702  5784 I bt_hci  : start_up
,11-04 11:21:52.159  5702  5784 I bt_vendor: alloc value 0xf4103871
11-04 11:21:52.159  5702  5784 I bt_vendor: init
,11-04 11:21:52.159  5702  5784 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 11:21:52.160  5702  5784 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 11:21:52.271  5702  5784 D bt_hci  : start_up starting async portion
,11-04 11:21:52.272  5702  5791 I bt_hci  : event_finish_startup
11-04 11:21:52.272  5702  5791 I bt_hci_h4: hal_open
11-04 11:21:52.272  5702  5791 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 11:21:52.271  5792  5792 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 11:21:52.276  5702  5791 I bt_userial_vendor: device fd = 54 open
,11-04 11:21:52.290  5702  5791 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 11:21:52.294  5702  5791 D bt_hwcfg: Chipset BCM4358A3
,11-04 11:21:52.294  5702  5791 D bt_hwcfg: Target name = [BCM4358A3]
11-04 11:21:52.294  5702  5791 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 11:21:52.681  5702  5791 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 11:21:52.681  5702  5791 D bt_hwcfg: Settlement delay -- 100 ms
11-04 11:21:52.681  5702  5791 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 11:21:52.815  5702  5791 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-04 11:21:52.816  5702  5791 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 11:21:52.817  5702  5791 I bt_hwcfg: vendor lib fwcfg completed
11-04 11:21:52.817  5702  5791 I bt_vendor: firmware callback
11-04 11:21:52.817  5702  5791 I bt_hci  : firmware_config_callback
,11-04 11:21:52.827  5702  5794 I bt_btu  : btu_task pending for preload complete event
,11-04 11:21:52.827  5702  5794 I bt_btu_task: Bluetooth chip preload is complete
11-04 11:21:52.827  5702  5794 I bt_btu  : btu_task received preload complete event
,11-04 11:21:52.833  5702  5794 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 11:21:52.833  5702  5794 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_A2D
,11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 11:21:52.834  5702  5794 I         : BTE_InitTraceLevels -- TRC_GAP
,11-04 11:21:52.835  5702  5794 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 11:21:52.835  5702  5794 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 11:21:52.835  5702  5794 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 11:21:52.835  5702  5794 I         : BTE_InitTraceLevels -- TRC_SMP
,11-04 11:21:52.835  5702  5794 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 11:21:52.835  5702  5794 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 11:21:52.921  5702  5794 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4081549
11-04 11:21:52.921  5702  5794 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4081549 
,11-04 11:21:52.936  5702  5787 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 11:21:52.937  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 11:21:52.938  5702  5787 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 11:21:52.940  5702  5787 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 11:21:52.944  5702  5787 D BluetoothAdapterProperties: Scan Mode:20
,11-04 11:21:52.945  5702  5787 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 11:21:52.945  5702  5787 D bt_hci  : do_postload posting postload work item
11-04 11:21:52.945  5702  5791 I bt_hci  : event_postload
11-04 11:21:52.946  5702  5791 I bt_vendor: sco_config_cb
11-04 11:21:52.946  5702  5791 I bt_hci  : sco_config_callback postload finished.
,11-04 11:21:52.949  5702  5787 D bt_bte_conf: Device ID record 1 : primary
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   vendorId            = 000f
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   vendorIdSource      = 0001
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   product             = 1200
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   version             = 1436
11-04 11:21:52.949  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   clientExecutableURL = 
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   serviceDescription  = 
11-04 11:21:52.949  5702  5787 D bt_bte_conf:   documentationURL    = 
11-04 11:21:52.949  5702  5787 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 11:21:52.950  5702  5784 D bt_stack_manager: event_start_up_stack finished
11-04 11:21:52.950  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-04 11:21:52.951  5702  5783 D BluetoothAdapterProperties: Setting state to 15
,11-04 11:21:52.951  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 11:21:52.953  5702  5783 I BluetoothAdapterState: Entering BleOnState
,11-04 11:21:52.958  5702  5791 I bt_vendor: low_power_mode_cb
11-04 11:21:52.958  5702  5783 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 11:21:52.958  5702  5783 D BluetoothAdapterProperties: Setting state to 11
,11-04 11:21:52.958  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 11:21:52.967  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:52.971  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:21:52.978  5702  5702 D HeadsetService: Received start request. Starting profile...
,11-04 11:21:52.980  5702  5783 I BluetoothAdapterState: Entering PendingCommandState
11-04 11:21:52.980  5702  5702 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 11:21:52.981  5702  5702 D HeadsetStateMachine: make
,11-04 11:21:52.990  5702  5702 D HeadsetStateMachine: max_hf_connections = 1
11-04 11:21:52.990  5702  5702 I bt_bluedroid: get_profile_interface handsfree
11-04 11:21:52.992  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-04 11:21:52.992  5702  5787 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 11:21:52.993  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:52.994  5702  5702 D A2dpService: Received start request. Starting profile...
11-04 11:21:52.994  5702  5702 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-04 11:21:52.995  5702  5702 I bt_bluedroid: get_profile_interface avrcp
,11-04 11:21:53.000  5702  5702 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 11:21:53.001  5702  5702 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 11:21:53.001  5702  5702 D A2dpStateMachine: make
11-04 11:21:53.002  5702  5702 I bt_bluedroid: get_profile_interface a2dp
,11-04 11:21:53.002  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 11:21:53.004  5702  5802 D A2dpStateMachine: Enter Disconnected: -2
,11-04 11:21:53.005  5702  5702 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 11:21:53.005  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:53.005  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 11:21:53.008  5702  5702 D HidService: Received start request. Starting profile...
11-04 11:21:53.008  5702  5702 I bt_bluedroid: get_profile_interface hidhost
11-04 11:21:53.008  5702  5702 D HidService: setHidService(): set to: null
11-04 11:21:53.008  5702  5702 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 11:21:53.009  5702  5787 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406256d
11-04 11:21:53.009  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 11:21:53.009  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:53.010  5702  5702 D HealthService: Received start request. Starting profile...
11-04 11:21:53.011  5702  5702 I bt_bluedroid: get_profile_interface health
11-04 11:21:53.011  5702  5702 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 11:21:53.012  5636  5636 D BluetoothInputDevice: Proxy object connected
11-04 11:21:53.012  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:53.013  5636  5636 D HidProfile: Bluetooth service connected
11-04 11:21:53.013  5702  5702 D PanService: Received start request. Starting profile...
11-04 11:21:53.013  5702  5702 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 11:21:53.013  5702  5702 I bt_bluedroid: get_profile_interface pan
11-04 11:21:53.014  5702  5787 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 11:21:53.015  5636  5636 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 11:21:53.015  5636  5636 D PanProfile: Bluetooth service connected
11-04 11:21:53.016  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:21:53.017  5702  5702 D BluetoothMapService: Received start request. Starting profile...
11-04 11:21:53.017  5636  5636 D BluetoothMap: Proxy object connected
11-04 11:21:53.017  5702  5702 D BluetoothMapService: start()
11-04 11:21:53.017  5636  5636 D MapProfile: Bluetooth service connected
11-04 11:21:53.018  5636  5636 D BluetoothMap: getConnectedDevices()
11-04 11:21:53.018  5636  5636 D BluetoothMap: Bluetooth is Not enabled
11-04 11:21:53.019  5702  5702 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 11:21:53.020  5702  5702 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 11:21:53.020  5702  5702 D BluetoothMapAppObserver: createReceiver()
11-04 11:21:53.022  5702  5702 D BluetoothMapAppObserver: initObservers()
11-04 11:21:53.022  5702  5702 D BluetoothMapAppObserver: getEnabledAccountItems()
11-04 11:21:53.028  5702  5702 V SapService: SapBinder()
11-04 11:21:53.028  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:21:53.029  5702  5702 D SapService: Received start request. Starting profile...
11-04 11:21:53.029  5702  5702 V SapService: start()
,11-04 11:21:53.032  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,11-04 11:21:53.032  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.032  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:53.032  5702  5800 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 11:21:53.032  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:53.033  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:53.034  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 11:21:53.035  5702  5702 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:53.035  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.035  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:53.035  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 11:21:53.036  5702  5702 V BluetoothAdapterState: isTurningOff()=false
11-04 11:21:53.036  5702  5702 V BluetoothAdapterState: isTurningOn()=true
11-04 11:21:53.036  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 11:21:53.036  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:53.036  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 11:21:53.036  5702  5783 D BluetoothAdapterProperties: ScanMode =  20
11-04 11:21:53.036  5702  5783 D BluetoothAdapterProperties: State =  11
11-04 11:21:53.037  5702  5783 D BluetoothAdapterProperties: Setting state to 12
11-04 11:21:53.037  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-04 11:21:53.037  3072  3084 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 11:21:53.038  5702  5787 D BluetoothAdapterProperties: Scan Mode:21
11-04 11:21:53.039  5702  5787 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 11:21:53.039  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 11:21:53.039  5702  5783 I BluetoothAdapterState: Entering OnState
11-04 11:21:53.040   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 11:21:53.040  3072  3072 D BluetoothInputDevice: Proxy object connected
11-04 11:21:53.040  3072  3072 D HidProfile: Bluetooth service connected
11-04 11:21:53.040  3072  3083 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:21:53.042   928   928 D BluetoothA2dp: Proxy object connected
,11-04 11:21:53.043  3072  3084 D BluetoothMap: onBluetoothStateChange: up=true
11-04 11:21:53.045  3072  3072 D BluetoothMap: Proxy object connected
11-04 11:21:53.045  3072  3083 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 11:21:53.045  3072  3072 D MapProfile: Bluetooth service connected
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:21:53.045  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 11:21:53.045  3072  3072 D BluetoothMap: getConnectedDevices()
,11-04 11:21:53.046  5636  5645 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 11:21:53.047  5636  5648 D BluetoothMap: onBluetoothStateChange: up=true
11-04 11:21:53.047  3072  3072 D BluetoothA2dp: Proxy object connected
11-04 11:21:53.047  5636  5645 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 11:21:53.047  5702  5702 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 11:21:53.048  5702  5702 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-04 11:21:53.048  5579  5579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 11:21:53.049   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 11:21:53.049  3072  3275 D BluetoothPan: onBluetoothStateChange on: true
,11-04 11:21:53.050  5702  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:21:53.051  3072  3072 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 11:21:53.051  3724  3979 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:21:53.051  3072  3072 D PanProfile: Bluetooth service connected
11-04 11:21:53.051  5702  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:21:53.052  5636  5648 D BluetoothPan: onBluetoothStateChange on: true
11-04 11:21:53.052   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:21:53.052  3072  3084 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 11:21:53.052  5702  5702 D ObexServerSockets: Succeed to create listening sockets 
11-04 11:21:53.052  5702  5702 D ObexServerSockets0: startAccept()
11-04 11:21:53.052  5702  5702 D ObexServerSockets0: prepareForNewConnect()
11-04 11:21:53.053   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:21:53.054  5702  5702 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 11:21:53.054  5702  5702 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 11:21:53.054  5702  5808 D ObexServerSockets0: Accepting socket connection...
,11-04 11:21:53.055  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 11:21:53.055  5702  5702 D BluetoothMapService: onReceive
11-04 11:21:53.055  5702  5702 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 11:21:53.055  5702  5702 D BluetoothMapService: STATE_ON
11-04 11:21:53.055   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 11:21:53.056  5702  5809 D ObexServerSockets0: Accepting socket connection...
,11-04 11:21:53.058  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:53.058  5636  5636 D LocalBluetoothProfileManager: Adding local A2DP profile
11-04 11:21:53.059  5702  5810 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:21:53.060  5702  5810 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 11:21:53.060  5702  5810 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 11:21:53.063  5636  5636 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-04 11:21:53.068  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 11:21:53.071  5636  5636 D BluetoothA2dp: Proxy object connected
,11-04 11:21:53.075  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 11:21:53.077  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-04 11:21:53.083  3072  3072 D BluetoothPbap: Proxy object connected
,11-04 11:21:53.083  5636  5636 D BluetoothPbap: Proxy object connected
11-04 11:21:53.083  3072  3072 D PbapServerProfile: Bluetooth service connected
,11-04 11:21:53.083  5636  5636 D PbapServerProfile: Bluetooth service connected
11-04 11:21:53.084  5702  5702 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 11:21:53.084  5702  5702 D ObexServerSockets0: prepareForNewConnect()
,11-04 11:21:53.091  5702  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 11:21:53.104  5702  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 11:21:53.105  5702  5819 I BtOppRfcommListener: Accept thread started.
,11-04 11:21:53.145   928   928 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.145   928   928 D BluetoothHeadset: Proxy object connected
11-04 11:21:53.145   928   928 D BluetoothHeadset: Proxy object connected
11-04 11:21:53.145  3072  3083 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.145  3072  3072 D HeadsetProfile: Bluetooth service connected
11-04 11:21:53.146  3724  3745 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.149   928   945 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.152  3724  3949 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.152   928   945 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.153   928   945 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.166  5636  5648 D BluetoothHeadset: Proxy object connected
,11-04 11:21:53.167  5636  5636 D HeadsetProfile: Bluetooth service connected
,11-04 11:21:54.595  3588  3678 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 11:21:54.596  3588  3678 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 11:21:54.625  3528  3528 I ConfigService: onCreate
,11-04 11:21:57.088  5702  5783 D BluetoothAdapterState: Current state: ON, message: 23
11-04 11:21:57.088  5702  5783 D BluetoothAdapterProperties: Setting state to 13
11-04 11:21:57.088  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 11:21:57.089  5702  5783 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 11:21:57.091  5702  5783 I BluetoothAdapterState: Entering PendingCommandState
,11-04 11:21:57.096  5702  5702 D BluetoothMapService: onReceive
11-04 11:21:57.097  5702  5702 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 11:21:57.097  5702  5702 D BluetoothMapService: STATE_TURNING_OFF
11-04 11:21:57.097  5702  5702 D BluetoothMapService: MAP Service closeService in
11-04 11:21:57.097  5702  5702 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 11:21:57.097  5702  5702 D ObexServerSockets0: shutdown(block = true)
11-04 11:21:57.101  5702  5702 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 11:21:57.102  5702  5702 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 11:21:57.102  5702  5808 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 11:21:57.102  5702  5796 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-04 11:21:57.102  5702  5809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-04 11:21:57.102  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:21:57.102  5579  5579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 11:21:57.104  5702  5787 D BluetoothAdapterProperties: Scan Mode:20
11-04 11:21:57.104  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 11:21:57.106  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 11:21:57.107  5579  5579 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 11:21:57.108  5579  5579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 11:21:57.109  5702  5702 I BtOppRfcommListener: stopping Accept Thread
,11-04 11:21:57.110  5702  5819 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 11:21:57.111  5702  5819 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 11:21:57.111  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:21:57.113  5702  5702 D HeadsetService: Received stop request...Stopping profile...
11-04 11:21:57.115   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:57.116  5636  5648 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:57.116   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:57.116   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:57.116  3072  3084 D BluetoothHeadset: Proxy object disconnected
11-04 11:21:57.117  3072  3072 D HeadsetProfile: Bluetooth service disconnected
11-04 11:21:57.117  3724  3751 D BluetoothHeadset: Proxy object disconnected
,11-04 11:21:57.121  5702  5702 D A2dpService: Received stop request...Stopping profile...
,11-04 11:21:57.121  5702  5802 D A2dpStateMachine: Exit Disconnected: -1
,11-04 11:21:57.123   928   928 D BluetoothA2dp: Proxy object disconnected
11-04 11:21:57.123  3072  3072 D BluetoothA2dp: Proxy object disconnected
11-04 11:21:57.123  5636  5636 D DockEventReceiver: finishStartingService: stopping service
11-04 11:21:57.124  5702  5702 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:57.124  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.124  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 11:21:57.124  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 11:21:57.125  5636  5636 D HeadsetProfile: Bluetooth service disconnected
,11-04 11:21:57.125  5636  5636 D BluetoothA2dp: Proxy object disconnected
11-04 11:21:57.126  5702  5702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 11:21:57.126  5702  5702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 11:21:57.126  5702  5794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 11:21:57.126  5702  5794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 11:21:57.126  5702  5794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:57.126  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 11:21:57.126  5702  5787 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 11:21:57.127  5702  5702 D HidService: Received stop request...Stopping profile...
11-04 11:21:57.127  5702  5702 D HidService: Stopping Bluetooth HidService
11-04 11:21:57.128  3072  3072 D BluetoothInputDevice: Proxy object disconnected
11-04 11:21:57.129  3072  3072 D HidProfile: Bluetooth service disconnected
11-04 11:21:57.129  5636  5636 D BluetoothInputDevice: Proxy object disconnected
11-04 11:21:57.129  5636  5636 D HidProfile: Bluetooth service disconnected
11-04 11:21:57.129  5702  5702 D HealthService: Received stop request...Stopping profile...
11-04 11:21:57.131  5702  5702 D PanService: Received stop request...Stopping profile...
11-04 11:21:57.132  3072  3072 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 11:21:57.132  3072  3072 D PanProfile: Bluetooth service disconnected
11-04 11:21:57.133  5702  5702 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:57.133  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.133  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 11:21:57.133  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:57.135  5702  5794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:57.135  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 11:21:57.135  5702  5794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:57.135  5636  5636 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 11:21:57.135  5702  5794 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 11:21:57.135  5636  5636 D PanProfile: Bluetooth service disconnected
11-04 11:21:57.135  5702  5794 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 11:21:57.135  5702  5794 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 11:21:57.135  5702  5794 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 11:21:57.135  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 11:21:57.136  5702  5702 D BluetoothMapService: Received stop request...Stopping profile...
11-04 11:21:57.136  5702  5702 D BluetoothMapService: stop()
11-04 11:21:57.136  5702  5702 D BluetoothMapAppObserver: deinitObservers()
11-04 11:21:57.136  5702  5702 D BluetoothMapAppObserver: removeReceiver()
,11-04 11:21:57.138  3072  3072 D BluetoothMap: Proxy object disconnected
11-04 11:21:57.138  3072  3072 D MapProfile: Bluetooth service disconnected
11-04 11:21:57.138  5702  5702 D SapService: Received stop request...Stopping profile...
11-04 11:21:57.138  5636  5636 D BluetoothMap: Proxy object disconnected
11-04 11:21:57.138  5702  5702 V SapService: stop()
11-04 11:21:57.138  5636  5636 D MapProfile: Bluetooth service disconnected
,11-04 11:21:57.139  5702  5702 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:57.139  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.139  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:57.139  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:57.140  5702  5702 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 11:21:57.140  5702  5702 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 11:21:57.140  5702  5702 V BluetoothAdapterState: isTurningOff()=true
,11-04 11:21:57.140  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.140  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:57.140  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:57.140  5702  5702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 11:21:57.140  5702  5702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 11:21:57.140  5702  5702 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:57.141  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.141  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:57.141  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:57.141  5702  5702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 11:21:57.141  5702  5702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 11:21:57.143  3072  3072 D BluetoothPbap: Proxy object disconnected
11-04 11:21:57.143  3072  3072 D PbapServerProfile: Bluetooth service disconnected
,11-04 11:21:57.143  5702  5702 D BluetoothMapService: MAP Service closeService in
11-04 11:21:57.143  5702  5702 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:57.143  5702  5702 V BluetoothAdapterState: isTurningOn()=false
,11-04 11:21:57.143  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:57.144  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:57.144  5702  5702 D BluetoothMapService: cleanup()
11-04 11:21:57.144  5702  5702 D BluetoothMapService: MAP Service closeService in
11-04 11:21:57.144  5702  5702 V BluetoothAdapterState: isTurningOff()=true
11-04 11:21:57.144  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.144  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:57.144  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:21:57.145  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 11:21:57.145  5702  5783 D BluetoothAdapterProperties: Setting state to 15
,11-04 11:21:57.145  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-04 11:21:57.145  3072  3084 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 11:21:57.145  5702  5787 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 11:21:57.146  5702  5783 I BluetoothAdapterState: Entering BleOnState
11-04 11:21:57.146   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 11:21:57.146  3072  3275 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 11:21:57.146  5702  5787 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 11:21:57.147  3072  3083 D BluetoothMap: onBluetoothStateChange: up=false
11-04 11:21:57.147  3072  3084 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 11:21:57.148  5636  5645 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:57.148  5636  5648 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 11:21:57.149  5636  5645 D BluetoothMap: onBluetoothStateChange: up=false
11-04 11:21:57.149  5636  5648 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 11:21:57.150   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 11:21:57.150  3072  3275 D BluetoothPan: onBluetoothStateChange on: false
11-04 11:21:57.150  3724  3979 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:57.151  5636  5645 D BluetoothPan: onBluetoothStateChange on: false
11-04 11:21:57.151  5636  5648 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 11:21:57.152   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:57.152  3072  3083 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 11:21:57.152   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 11:21:57.152  5702  5783 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 11:21:57.153  5702  5783 D BluetoothAdapterProperties: Setting state to 16
11-04 11:21:57.153  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-04 11:21:57.147  5636  5636 D BluetoothPbap: Proxy object disconnected
11-04 11:21:57.153  5636  5636 D PbapServerProfile: Bluetooth service disconnected
11-04 11:21:57.153  5702  5783 D BluetoothAdapterProperties: onBleDisable
11-04 11:21:57.153  5702  5783 I BluetoothAdapterState: Entering PendingCommandState
11-04 11:21:57.154  5702  5784 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 11:21:57.155  5702  5794 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 11:21:57.155  5702  5794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 11:21:57.156  5702  5787 D BluetoothAdapterProperties: Scan Mode:20
,11-04 11:21:57.156  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 11:21:57.157  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:57.158  5579  5579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:21:57.161  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 11:21:57.173  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-04 11:21:57.361  5702  5787 I bt_hci  : shut_down
,11-04 11:21:57.364  5702  5791 D bt_hwcfg: hw_epilog_process
,11-04 11:21:57.364  5702  5791 I bt_vendor: low_power_mode_cb
,11-04 11:21:57.367  5702  5791 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 11:21:57.367  5702  5791 I bt_vendor: epilog_cb
11-04 11:21:57.367  5702  5791 I bt_hci  : epilog_finished_callback
,11-04 11:21:57.369  5702  5787 I bt_hci_h4: hal_close
,11-04 11:21:57.370  5702  5787 I bt_userial_vendor: device fd = 54 close
,11-04 11:21:57.479  5702  5784 D bt_stack_manager: event_shut_down_stack finished.
,11-04 11:21:57.479  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-04 11:21:57.483  5702  5783 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 11:21:57.484  5702  5702 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 11:21:57.485  5702  5702 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 11:21:57.485  5702  5702 D BtGatt.GattService: stop()
11-04 11:21:57.485  5702  5702 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 11:21:57.489  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,11-04 11:21:57.490  5702  5702 V BluetoothAdapterState: isTurningOn()=false
11-04 11:21:57.490  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:21:57.490  5702  5702 V BluetoothAdapterState: isBleTurningOff()=true
11-04 11:21:57.490  5702  5783 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 11:21:57.491  5702  5783 D BluetoothAdapterProperties: Setting state to 10
,11-04 11:21:57.491  5702  5783 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-04 11:21:57.492  5702  5783 I BluetoothAdapterState: Entering OffState
,11-04 11:21:57.495   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 11:21:57.508  5702  5702 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 11:21:57.508  5702  5702 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 11:21:57.508  5702  5702 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 11:21:57.509  5702  5784 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 11:21:57.514  5702  5702 I art     : System.exit called, status: 0
11-04 11:21:57.515  5702  5702 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 11:21:57.540   928  3564 I ActivityManager: Process com.android.bluetooth (pid 5702) has died
,11-04 11:21:58.446   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:59.447   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:21:59.656  3528  3528 I ConfigService: onDestroy
,11-04 11:22:00.448   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:01.449   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:02.085  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:22:02.086  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 11:22:02.091  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:22:02.091  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e4759b removed from the list
,11-04 11:22:02.092  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:22:02.094  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:02.094  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@982276 added. We now have 4 listener(s)
11-04 11:22:02.094  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:22:02.096  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:02.096  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@982276 removed from the list
,11-04 11:22:02.096  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:22:02.099  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:22:02.099  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88ad077 added. We now have 4 listener(s)
,11-04 11:22:02.099  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:22:02.450   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:03.450   547   547 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 11:22:06.778   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 11:22:06.787  3588  3588 I Keyboard.Facilitator: onFinishInput()
,11-04 11:22:06.784  3759  3759 W Binder_A: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33866]" dev="sockfs" ino=33866 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:06.787  3759  3759 W Binder_A: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33866]" dev="sockfs" ino=33866 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:06.811   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 11:22:06.811   928   948 I Adreno  : Build Date                       : 12/06/15
11-04 11:22:06.811   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 11:22:06.811   928   948 I Adreno  : Local Branch                     : mybranch17112971
11-04 11:22:06.811   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 11:22:06.811   928   948 I Adreno  : Remote Branch                    : NONE
11-04 11:22:06.811   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 11:22:06.851   383   951 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (192 us)
,11-04 11:22:07.106  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 11:22:07.120   928   945 I ActivityManager: Start proc 5829:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 11:22:07.174  5829  5829 D AdapterServiceConfig: Adding HeadsetService
,11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding A2dpService
11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding HidService
11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding HealthService
11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding PanService
,11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding GattService
11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding BluetoothMapService
11-04 11:22:07.175  5829  5829 D AdapterServiceConfig: Adding SapService
,11-04 11:22:07.188   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d99c0dc:true
11-04 11:22:07.188  5829  5829 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 11:22:07.192  5829  5829 I bt_bluedroid: init
11-04 11:22:07.192  5829  5841 I BluetoothAdapterState: Entering OffState
,11-04 11:22:07.195  5829  5842 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-04 11:22:07.195  5829  5842 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 11:22:07.195  5829  5842 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 11:22:07.195  5829  5842 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-04 11:22:07.196  5829  5829 I bt_bluedroid: get_profile_interface socket
,11-04 11:22:07.197  5829  5845 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 11:22:07.198  5829  5829 I bt_bluedroid: get_profile_interface sdp
11-04 11:22:07.199  5829  5845 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 11:22:07.203  5829  5840 I bt_bluedroid: config_hci_snoop_log
11-04 11:22:07.204   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 11:22:07.209  5829  5841 D BluetoothAdapterState: Current state: OFF, message: 0
11-04 11:22:07.210  5829  5841 D BluetoothAdapterProperties: Setting state to 14
11-04 11:22:07.210  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 11:22:07.211  5829  5841 D BluetoothBondStateMachine: make
,11-04 11:22:07.212  5829  5846 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 11:22:07.215  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,11-04 11:22:07.216  5829  5829 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-04 11:22:07.218  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:22:07.219  5829  5829 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 11:22:07.220  5829  5829 D BtGatt.GattService: Received start request. Starting profile...
11-04 11:22:07.220  5829  5829 D BtGatt.GattService: start()
11-04 11:22:07.220  5829  5829 I bt_bluedroid: get_profile_interface gatt
,11-04 11:22:07.221  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:22:07.221  5829  5829 D BtGatt.AdvertiseManager: advertise manager created
,11-04 11:22:07.227  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:07.227  5829  5829 V BluetoothAdapterState: isTurningOn()=false
11-04 11:22:07.227  5829  5829 V BluetoothAdapterState: isBleTurningOn()=true
11-04 11:22:07.227  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:07.227  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 11:22:07.228  5829  5841 I bt_bluedroid: bt_bluedroid
,11-04 11:22:07.228  5829  5842 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 11:22:07.229  5829  5842 I bt_hci  : start_up
,11-04 11:22:07.233  5829  5842 I bt_vendor: alloc value 0xf410f871
11-04 11:22:07.233  5829  5842 I bt_vendor: init
,11-04 11:22:07.233  5829  5842 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 11:22:07.233  5829  5842 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 11:22:07.342  5829  5842 D bt_hci  : start_up starting async portion
11-04 11:22:07.343  5829  5849 I bt_hci  : event_finish_startup
,11-04 11:22:07.343  5829  5849 I bt_hci_h4: hal_open
11-04 11:22:07.343  5829  5849 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 11:22:07.347  5829  5849 I bt_userial_vendor: device fd = 54 open
,11-04 11:22:07.344  5850  5850 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 11:22:07.363  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 11:22:07.366  5829  5849 D bt_hwcfg: Chipset BCM4358A3
,11-04 11:22:07.366  5829  5849 D bt_hwcfg: Target name = [BCM4358A3]
11-04 11:22:07.367  5829  5849 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 11:22:07.524  5579  5579 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 11:22:07.524  5579  5579 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 11:22:07.555   928   948 I sensors : batch
,11-04 11:22:07.556   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 11:22:07.557  5579  5579 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c36e676 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1a934e4, 16908290=android.view.AbsSavedState$1@1a934e4}, android:focusedViewId=100}]}]
11-04 11:22:07.558  5579  5579 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 11:22:07.558  5579  5579 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 11:22:07.558  5579  5579 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-04 11:22:07.560   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 11:22:07.560   928   948 I sensors : activate
11-04 11:22:07.561   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f78583c00
11-04 11:22:07.561   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-04 11:22:07.561   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-04 11:22:07.568   928  2676 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-04 11:22:07.572   928  2676 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 11:22:07.836  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 11:22:07.836  5829  5849 D bt_hwcfg: Settlement delay -- 100 ms
11-04 11:22:07.836  5829  5849 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 11:22:07.868   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 11:22:07.871   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 11:22:07.875   928  3007 D SurfaceControl: Excessive delay in setPowerMode(): 313ms
,11-04 11:22:07.895   928   948 I DreamManagerService: Entering dreamland.
,11-04 11:22:07.897   928   948 I PowerManagerService: Dozing...
,11-04 11:22:07.901   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 11:22:07.931  3564  3564 W Binder_8: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35989]" dev="sockfs" ino=35989 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 11:22:07.932   928  3563 I sensors : batch
11-04 11:22:07.933   928  3563 I sensors : activate
11-04 11:22:07.931  3564  3564 W Binder_8: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35989]" dev="sockfs" ino=35989 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:07.937   928  2676 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 11:22:07.937   928  2676 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 11:22:07.941   513  2940 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 11:22:07.970  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 11:22:07.970  5829  5849 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 11:22:07.971  5829  5849 I bt_hwcfg: vendor lib fwcfg completed
11-04 11:22:07.971  5829  5849 I bt_vendor: firmware callback
,11-04 11:22:07.971  5829  5849 I bt_hci  : firmware_config_callback
,11-04 11:22:07.975  5829  5854 I bt_btu  : btu_task pending for preload complete event
,11-04 11:22:07.975  5829  5854 I bt_btu_task: Bluetooth chip preload is complete
11-04 11:22:07.975  5829  5854 I bt_btu  : btu_task received preload complete event
,11-04 11:22:07.977  5829  5854 I         : BTE_InitTraceLevels -- TRC_HCI
11-04 11:22:07.977  5829  5854 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-04 11:22:07.977  5829  5854 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 11:22:07.977  5829  5854 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 11:22:07.977  5829  5854 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 11:22:07.977  5829  5854 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-04 11:22:07.978  5829  5854 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 11:22:08.050  3724  4702 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 11:22:08.050  3724  4702 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 11:22:08.051  3724  4702 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 11:22:08.051   526  1250 D         : oem-qmi: Connection accepted
,11-04 11:22:08.051   526  1250 D         : oem-qmi: Waiting to accept connection
11-04 11:22:08.053   928   928 I sensors : activate
11-04 11:22:08.053   513  2942 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-04 11:22:08.054  5829  5854 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf408d549
11-04 11:22:08.054  5829  5854 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf408d549 
11-04 11:22:08.056   928  2676 I hubconnection: sensorhub said: 'activate 31 enable:0'
11-04 11:22:08.057  3724  4702 D         : oem_qmi_lib:output 0
11-04 11:22:08.057  3724  4702 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 11:22:08.064  5829  5845 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 11:22:08.066  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 11:22:08.066  5829  5845 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 11:22:08.069  5829  5845 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 11:22:08.070  5829  5845 D BluetoothAdapterProperties: Scan Mode:20
11-04 11:22:08.070  5829  5845 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 11:22:08.070  5829  5845 D bt_hci  : do_postload posting postload work item
11-04 11:22:08.070  5829  5849 I bt_hci  : event_postload
11-04 11:22:08.070  5829  5849 I bt_vendor: sco_config_cb
11-04 11:22:08.070  5829  5849 I bt_hci  : sco_config_callback postload finished.
,11-04 11:22:08.071  5829  5845 D bt_bte_conf: Device ID record 1 : primary
11-04 11:22:08.071  5829  5845 D bt_bte_conf:   vendorId            = 000f
11-04 11:22:08.071  5829  5845 D bt_bte_conf:   vendorIdSource      = 0001
11-04 11:22:08.071  5829  5845 D bt_bte_conf:   product             = 1200
11-04 11:22:08.071  5829  5845 D bt_bte_conf:   version             = 1436
,11-04 11:22:08.071  5829  5845 D bt_bte_conf:   clientExecutableURL = 
11-04 11:22:08.071  5829  5845 D bt_bte_conf:   serviceDescription  = 
11-04 11:22:08.071  5829  5845 D bt_bte_conf:   documentationURL    = 
11-04 11:22:08.071  5829  5845 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 11:22:08.072  5829  5842 D bt_stack_manager: event_start_up_stack finished
11-04 11:22:08.072  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 11:22:08.072  5829  5841 D BluetoothAdapterProperties: Setting state to 15
11-04 11:22:08.072  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 11:22:08.072  5829  5841 I BluetoothAdapterState: Entering BleOnState
,11-04 11:22:08.075  5829  5841 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 11:22:08.075  5829  5841 D BluetoothAdapterProperties: Setting state to 11
11-04 11:22:08.076  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 11:22:08.077  5829  5849 I bt_vendor: low_power_mode_cb
,11-04 11:22:08.080  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:22:08.083  5829  5829 D HeadsetService: Received start request. Starting profile...
11-04 11:22:08.086  5829  5829 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 11:22:08.086  5829  5829 D HeadsetStateMachine: make
,11-04 11:22:08.092  3724  4702 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
11-04 11:22:08.092  3724  4702 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-04 11:22:08.092  3724  4702 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 11:22:08.092   526  1250 D         : oem-qmi: Connection accepted
11-04 11:22:08.093   526  1250 D         : oem-qmi: Waiting to accept connection
11-04 11:22:08.093  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,11-04 11:22:08.096  5829  5829 D HeadsetStateMachine: max_hf_connections = 1
,11-04 11:22:08.096  5829  5829 I bt_bluedroid: get_profile_interface handsfree
11-04 11:22:08.096  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 11:22:08.096  5829  5845 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-04 11:22:08.099  3724  4702 D         : oem_qmi_lib:output 0
11-04 11:22:08.099  3724  4702 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-04 11:22:08.100  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:22:08.100  5829  5829 D A2dpService: Received start request. Starting profile...
11-04 11:22:08.101  5829  5829 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 11:22:08.101  5829  5829 I bt_bluedroid: get_profile_interface avrcp
,11-04 11:22:08.106  5829  5829 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-04 11:22:08.106  5829  5829 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 11:22:08.106  5829  5829 D A2dpStateMachine: make
,11-04 11:22:08.107  5829  5829 I bt_bluedroid: get_profile_interface a2dp
,11-04 11:22:08.109  5829  5865 D A2dpStateMachine: Enter Disconnected: -2
,11-04 11:22:08.110  5829  5829 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 11:22:08.111  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:22:08.111  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-04 11:22:08.112  5829  5829 D HidService: Received start request. Starting profile...
11-04 11:22:08.112  5829  5829 I bt_bluedroid: get_profile_interface hidhost
11-04 11:22:08.112  5829  5829 D HidService: setHidService(): set to: null
11-04 11:22:08.112  5829  5845 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406e56d
11-04 11:22:08.112  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 11:22:08.112  5829  5829 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-04 11:22:08.113  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:22:08.114  5829  5829 D HealthService: Received start request. Starting profile...
,11-04 11:22:08.115  5829  5829 I bt_bluedroid: get_profile_interface health
11-04 11:22:08.116  5829  5829 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 11:22:08.116  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:22:08.117  5829  5829 D PanService: Received start request. Starting profile...
,11-04 11:22:08.117  5829  5829 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 11:22:08.117  5829  5829 I bt_bluedroid: get_profile_interface pan
11-04 11:22:08.118  5829  5845 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 11:22:08.121  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 11:22:08.121  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
11-04 11:22:08.121  5829  5829 D BluetoothMapService: Received start request. Starting profile...
11-04 11:22:08.121  5829  5829 D BluetoothMapService: start()
11-04 11:22:08.123  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 11:22:08.124  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 11:22:08.124  5829  5829 D BluetoothMapAppObserver: createReceiver()
,11-04 11:22:08.125  5829  5829 D BluetoothMapAppObserver: initObservers()
11-04 11:22:08.125  5829  5829 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 11:22:08.133  5829  5829 V SapService: SapBinder()
11-04 11:22:08.133  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:22:08.133  5829  5829 D SapService: Received start request. Starting profile...
11-04 11:22:08.134  5829  5829 V SapService: start()
,11-04 11:22:08.136  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.136  5829  5829 V BluetoothAdapterState: isTurningOn()=true
,11-04 11:22:08.136  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.136  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:08.137  5829  5862 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.137  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:08.138  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.138  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-04 11:22:08.138  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.138  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-04 11:22:08.139  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-04 11:22:08.139  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-04 11:22:08.139  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-04 11:22:08.139  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 11:22:08.140  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-04 11:22:08.140  5829  5841 D BluetoothAdapterProperties: ScanMode =  20
11-04 11:22:08.140  5829  5841 D BluetoothAdapterProperties: State =  11
11-04 11:22:08.140  5829  5841 D BluetoothAdapterProperties: Setting state to 12
11-04 11:22:08.140  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 11:22:08.141  5829  5841 I BluetoothAdapterState: Entering OnState
11-04 11:22:08.141  3072  3275 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 11:22:08.142  5829  5845 D BluetoothAdapterProperties: Scan Mode:21
11-04 11:22:08.142  5829  5845 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 11:22:08.143   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 11:22:08.144  3072  3084 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:22:08.144  3072  3072 D BluetoothInputDevice: Proxy object connected
11-04 11:22:08.144  3072  3072 D HidProfile: Bluetooth service connected
11-04 11:22:08.145   928   928 D BluetoothA2dp: Proxy object connected
11-04 11:22:08.145  3072  3275 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 11:22:08.147  3072  3083 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 11:22:08.149  5636  5648 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:22:08.149  3072  3072 D BluetoothMap: Proxy object connected
11-04 11:22:08.149  3072  3072 D MapProfile: Bluetooth service connected
,11-04 11:22:08.149  3072  3072 D BluetoothMap: getConnectedDevices()
11-04 11:22:08.149  5636  5645 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 11:22:08.151  3072  3072 D BluetoothA2dp: Proxy object connected
11-04 11:22:08.151  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 11:22:08.151  5636  5648 D BluetoothMap: onBluetoothStateChange: up=true
11-04 11:22:08.152  5829  5829 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-04 11:22:08.153  5636  5636 D BluetoothInputDevice: Proxy object connected
,11-04 11:22:08.153  5636  5636 D HidProfile: Bluetooth service connected
11-04 11:22:08.154  5636  5645 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 11:22:08.154  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:22:08.156  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:22:08.156   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:22:08.156  3072  3275 D BluetoothPan: onBluetoothStateChange on: true
11-04 11:22:08.157  5829  5829 D ObexServerSockets: Succeed to create listening sockets 
11-04 11:22:08.157  5829  5829 D ObexServerSockets0: startAccept()
11-04 11:22:08.157  5829  5829 D ObexServerSockets0: prepareForNewConnect()
11-04 11:22:08.158  3724  3745 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 11:22:08.159  5636  5648 D BluetoothPan: onBluetoothStateChange on: true
11-04 11:22:08.159  5829  5829 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 11:22:08.159  5829  5829 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-04 11:22:08.159  5829  5872 D ObexServerSockets0: Accepting socket connection...
11-04 11:22:08.160  5829  5873 D ObexServerSockets0: Accepting socket connection...
11-04 11:22:08.160  3072  3072 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 11:22:08.160  3072  3072 D PanProfile: Bluetooth service connected
11-04 11:22:08.162  5636  5645 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 11:22:08.163   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 11:22:08.163  3072  3083 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 11:22:08.164   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 11:22:08.166   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-04 11:22:08.166  5829  5829 D BluetoothMapService: onReceive
11-04 11:22:08.166  5829  5829 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 11:22:08.166  5829  5829 D BluetoothMapService: STATE_ON
,11-04 11:22:08.168  5636  5636 D BluetoothMap: Proxy object connected
,11-04 11:22:08.168  5636  5636 D MapProfile: Bluetooth service connected
11-04 11:22:08.168  5636  5636 D BluetoothMap: getConnectedDevices()
11-04 11:22:08.168  5829  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 11:22:08.170  5829  5874 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 11:22:08.170  5829  5874 D BluetoothSdpJni: SDP Create record success - handle: 1
11-04 11:22:08.170  5636  5636 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 11:22:08.170  5636  5636 D PanProfile: Bluetooth service connected
,11-04 11:22:08.171  5636  5636 D BluetoothA2dp: Proxy object connected
,11-04 11:22:08.176  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 11:22:08.182  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 11:22:08.184  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-04 11:22:08.189  5636  5636 D BluetoothPbap: Proxy object connected
,11-04 11:22:08.189  5636  5636 D PbapServerProfile: Bluetooth service connected
,11-04 11:22:08.194  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 11:22:08.194  5829  5829 D ObexServerSockets0: prepareForNewConnect()
11-04 11:22:08.195  3072  3072 D BluetoothPbap: Proxy object connected
11-04 11:22:08.195  3072  3072 D PbapServerProfile: Bluetooth service connected
,11-04 11:22:08.197  5829  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 11:22:08.213  5829  5883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 11:22:08.214  5829  5883 I BtOppRfcommListener: Accept thread started.
,11-04 11:22:08.246   928   928 D BluetoothHeadset: Proxy object connected
11-04 11:22:08.247  5636  5648 D BluetoothHeadset: Proxy object connected
11-04 11:22:08.247   928   928 D BluetoothHeadset: Proxy object connected
11-04 11:22:08.247   928   928 D BluetoothHeadset: Proxy object connected
,11-04 11:22:08.247  3072  3083 D BluetoothHeadset: Proxy object connected
11-04 11:22:08.247  3072  3072 D HeadsetProfile: Bluetooth service connected
,11-04 11:22:08.249  3724  3949 D BluetoothHeadset: Proxy object connected
,11-04 11:22:08.250  5636  5645 D BluetoothHeadset: Proxy object connected
11-04 11:22:08.251  5636  5636 D HeadsetProfile: Bluetooth service connected
11-04 11:22:08.253  5636  5636 D HeadsetProfile: Bluetooth service connected
,11-04 11:22:08.256   928   945 D BluetoothHeadset: Proxy object connected
,11-04 11:22:08.259  3724  3751 D BluetoothHeadset: Proxy object connected
,11-04 11:22:08.263   928   945 D BluetoothHeadset: Proxy object connected
,11-04 11:22:08.265   928   945 D BluetoothHeadset: Proxy object connected
,11-04 11:22:11.537  3657  4396 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:22:12.118  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 11:22:12.123  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 11:22:12.125  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:12.125  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88ad077 removed from the list
11-04 11:22:12.125  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:22:12.129  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:22:12.129  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f812d4d added. We now have 4 listener(s)
11-04 11:22:12.129  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 11:22:12.136   928  3140 D WifiService: setWifiEnabled: false pid=5579, uid=10077
,11-04 11:22:12.136   928  3140 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 11:22:17.147  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 11:22:17.149   928  4228 D WifiService: setWifiEnabled: true pid=5579, uid=10077
11-04 11:22:17.149   928  4228 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 11:22:17.156   508   922 D SoftapController: Softap fwReload - Ok
,11-04 11:22:17.161   508   922 D CommandListener: Setting iface cfg
,11-04 11:22:17.162   508   922 D CommandListener: Trying to bring down wlan0
,11-04 11:22:17.164   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-04 11:22:17.171   928  2889 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 11:22:17.840   928  2889 D wifi    : set interface wlan0 flags (UP)
,11-04 11:22:17.842   928  2889 I WifiHAL : Initializing wifi
,11-04 11:22:17.842   928  2889 I WifiHAL : Creating socket
,11-04 11:22:17.849   928  2889 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 11:22:17.849   928  2889 D wifi    : Did set static halHandle = 0x7f89eaa180
11-04 11:22:17.849   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 11:22:17.849   928  2889 D wifi    : halHandle = 0x7f89eaa180, mVM = 0x7fa650d140, mCls = 0x20166a
11-04 11:22:17.850   928  2889 D wifi    : array field set
11-04 11:22:17.850   928  2889 I WifiNative-HAL: interface[0] = wlan0
11-04 11:22:17.852   928  5888 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547774701952
11-04 11:22:17.853   928  5888 D wifi    : waitForHalEvents called, vm = 0x7fa650d140, obj = 0x20166a, env = 0x7f875e3680
,11-04 11:22:17.914  5889  5889 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 11:22:17.954   928  2889 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 11:22:17.955   928  2889 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-04 11:22:17.986  5889  5889 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 11:22:18.028  5889  5889 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-04 11:22:18.029  5889  5889 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 11:22:18.452   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:18.971   928  2889 D WifiConfigStore: Loading config and enabling all networks 
,11-04 11:22:19.006   928  2889 D WifiConfigStore: loaded 0 passpoint configs
11-04 11:22:19.007   928  2889 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 11:22:19.008   928  2889 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 11:22:19.009   928  2889 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 11:22:19.010   928  2889 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 11:22:19.010   928  2889 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 11:22:19.012   928  2889 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 11:22:19.013   928  2889 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 11:22:19.013   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 11:22:19.013   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-04 11:22:19.013   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 11:22:19.013   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 11:22:19.013   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 11:22:19.017   928  2889 D WifiNative-HAL: Setting external_sim to 1
,11-04 11:22:19.018  4444  4444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 11:22:19.018   928  2889 D wifi    : setting dfs flag to true, 0x7f8d43f300
,11-04 11:22:19.019   928  2889 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 11:22:19.019   928  2889 D wifi    : setting scan oui 0x7f8d43f300
,11-04 11:22:19.019   928  2889 D WifiHAL : Sending mac address OUI
,11-04 11:22:19.024   928  2889 E native  : do suspend true
,11-04 11:22:19.032   928  2889 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 11:22:19.033   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 11:22:19.033   928   928 D RttService: SCAN_AVAILABLE : 3
11-04 11:22:19.033   928  2999 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 11:22:19.034   508   922 D CommandListener: Setting iface cfg
,11-04 11:22:19.044   928  2888 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
11-04 11:22:19.044   928  2888 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 11:22:19.058   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164380 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,11-04 11:22:19.059   928  2888 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 11:22:19.060   928  2888 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 11:22:19.453   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:20.455   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:21.456   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 11:22:22.168  5579  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 11:22:22.174  5579  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 11:22:22.174  5889  5889 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-04 11:22:22.175  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:22:22.175  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f812d4d removed from the list
,11-04 11:22:22.176  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 11:22:22.183  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-04 11:22:22.184  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-04 11:22:22.187  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c36e676 Bundle[{}]
11-04 11:22:22.188  5579  5626 I io.jxcore.node.LifeCycleMonitor: start: OK
11-04 11:22:22.188  5579  5626 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-04 11:22:22.189  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-04 11:22:22.189  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 11:22:22.190  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-04 11:22:22.190  5579  5626 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 11:22:22.197  5579  5626 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-04 11:22:22.198  5579  5626 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-04 11:22:22.198  5579  5626 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-04 11:22:22.200  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.201  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5bf002 added. We now have 3 listener(s)
11-04 11:22:22.201   928  2889 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-04 11:22:22.202  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.202  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 11:22:22.202  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.202   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-04 11:22:22.202  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.202   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 11:22:22.203  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1fd13 added. We now have 4 listener(s)
11-04 11:22:22.203  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.203  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:22:22.205  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.205  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@936bb50 added. We now have 4 listener(s)
11-04 11:22:22.206  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.207  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 11:22:22.207  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.207  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.207  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9405149 added. We now have 5 listener(s)
11-04 11:22:22.207  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.207  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:22:22.207  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.207  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:22:22.207  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 11:22:22.207  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.207  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.208  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5bf002 removed from the list
11-04 11:22:22.208  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.208  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1fd13 removed from the list
11-04 11:22:22.208  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:22:22.208  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.210   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 11:22:22.210  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.210  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.210  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.210  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.210  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 11:22:22.210  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 11:22:22.211  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1fd13 not in the list
11-04 11:22:22.211  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.214  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.214  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.214  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.215  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.215  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 11:22:22.215  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.216  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9405149 removed from the list
11-04 11:22:22.216  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.217  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.217  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.217  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@936bb50 removed from the list
11-04 11:22:22.219  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.219  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d0a4e added. We now have 3 listener(s)
11-04 11:22:22.220  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.220  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.220  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 11:22:22.220  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.221  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@255576f added. We now have 4 listener(s)
11-04 11:22:22.221  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.222  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:22:22.223  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 11:22:22.223  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd43c7c added. We now have 4 listener(s)
11-04 11:22:22.225  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.225  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.225  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.225  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.225  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3b905 added. We now have 5 listener(s)
11-04 11:22:22.225  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.225  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:22.225  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 11:22:22.226  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 11:22:22.226  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:22:22.226  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 11:22:22.227  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 11:22:22.230  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 11:22:22.231  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 11:22:22.231  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 11:22:22.235  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.235  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 11:22:22.236  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 11:22:22.236  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 11:22:22.236  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 11:22:22.240  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.240  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 11:22:22.240  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-04 11:22:22.240  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 11:22:22.240  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 11:22:22.240  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.241  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:22:22.244  5829  5840 D BtGatt.GattService: registerClient() - UUID=f9e80698-5f77-442b-ae32-bd00740bc2ec
11-04 11:22:22.244   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 11:22:22.245  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=f9e80698-5f77-442b-ae32-bd00740bc2ec, clientIf=5
,11-04 11:22:22.245  5579  5589 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 11:22:22.246  5829  5870 D BtGatt.GattService: start scan with filters
,11-04 11:22:22.249  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 11:22:22.249  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.249  5829  5848 D BtGatt.ScanManager: handling starting scan
11-04 11:22:22.249  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 11:22:22.250  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.250  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 11:22:22.250  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 11:22:22.250  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.250  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 11:22:22.250  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 11:22:22.250  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.250  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.250  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 11:22:22.251  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 11:22:22.251  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.252  5829  5848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@646a99b
,11-04 11:22:22.254  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.254  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:22:22.254  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.254  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.254  5579  5626 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 11:22:22.254  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.254  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.254  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 11:22:22.254  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.254  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:22:22.254  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.254  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 11:22:22.257  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.257  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.257  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.257  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.257  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 11:22:22.257  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:22:22.257  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 11:22:22.257  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:22:22.258  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.258  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.258  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.258  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 11:22:22.258  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.259  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:22:22.259  5829  5870 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 11:22:22.259  5829  5845 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 11:22:22.259  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.259  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-04 11:22:22.260  5829  5848 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 11:22:22.260  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:22:22.261  5829  5875 D BtGatt.GattService: stopScan() - queue size =1
11-04 11:22:22.262  5829  5840 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.262  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.263  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.263  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 11:22:22.263  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 11:22:22.263  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 11:22:22.264  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.265  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.266  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:22:22.266  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.266  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.266  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:22:22.266  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:22:22.266  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-04 11:22:22.266  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.266  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 11:22:22.266  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 11:22:22.266  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.266  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.266  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 11:22:22.267  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 11:22:22.267  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.267  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.267  5829  5848 D BtGatt.ScanManager: Starting BLE batch scan
11-04 11:22:22.267  5829  5848 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 11:22:22.268  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.268  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.268  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.268  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.268  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:22:22.268  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:22:22.268  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.269  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:22:22.269  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.269  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 11:22:22.269  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.269  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d0a4e removed from the list
11-04 11:22:22.269  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.269  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@255576f removed from the list
11-04 11:22:22.269  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:22:22.269  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.270  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.270  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.270  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.271  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.271  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.271  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.271  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@255576f not in the list
11-04 11:22:22.271  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.272  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.272  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.272  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.272  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.272  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.272  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.272  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3b905 removed from the list
,11-04 11:22:22.272  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.272  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.272  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.272  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd43c7c removed from the list
11-04 11:22:22.273  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.273  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ac1526 added. We now have 3 listener(s)
11-04 11:22:22.274  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.274  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.274  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.274  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:22:22.274  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1ac567 added. We now have 4 listener(s)
11-04 11:22:22.274  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.275  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:22:22.276  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.276  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1359f14 added. We now have 4 listener(s)
11-04 11:22:22.277  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 11:22:22.277  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.277  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.277  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.277  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c503bd added. We now have 5 listener(s)
11-04 11:22:22.277  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.278  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:22.278  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:22.278  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-04 11:22:22.278  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 11:22:22.278  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:22:22.278  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 11:22:22.279  5829  5845 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 11:22:22.279  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.280  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 11:22:22.283  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 11:22:22.283  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 11:22:22.283  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 11:22:22.284  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 11:22:22.284  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:22:22.286  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:22:22.286  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.286  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 11:22:22.287  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 11:22:22.287  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 11:22:22.287  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 11:22:22.290  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.290  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 11:22:22.290  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 11:22:22.290  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 11:22:22.290  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 11:22:22.290  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.290  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 11:22:22.290  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.291  5829  5845 E BtGatt.ContextMap: Context not found for ID 5
11-04 11:22:22.291  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:22:22.294  5829  5840 D BtGatt.GattService: registerClient() - UUID=9fe98040-363f-4954-a492-a0c15387f86d
,11-04 11:22:22.294  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=9fe98040-363f-4954-a492-a0c15387f86d, clientIf=5
,11-04 11:22:22.294  5579  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 11:22:22.295  5829  5870 D BtGatt.GattService: start scan with filters
,11-04 11:22:22.297  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 11:22:22.297  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.297  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 11:22:22.297  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.297  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 11:22:22.298  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 11:22:22.298  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.298  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 11:22:22.298  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 11:22:22.298  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.298  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 11:22:22.298  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.298  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.298  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 11:22:22.298  5829  5848 D BtGatt.ScanManager: stopping BLe Batch
,11-04 11:22:22.299  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 11:22:22.299  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.301  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.302  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:22:22.302  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.302  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.302  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.302  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:22.302  5579  5626 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 11:22:22.302  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:22:22.302  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.302  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:22:22.302  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.302  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.302  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 11:22:22.303  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.303  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.303  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ac1526 removed from the list
11-04 11:22:22.303  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.303  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1ac567 removed from the list
11-04 11:22:22.303  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:22:22.303  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.303  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:22:22.303  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-04 11:22:22.303  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 11:22:22.303  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.303  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:22:22.303  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.303  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 11:22:22.303  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.303  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 11:22:22.304  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.304  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.304  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.304  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.304  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.304  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.304  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.304  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.304  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.304  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.304  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:22:22.304  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1ac567 not in the list
11-04 11:22:22.305  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 11:22:22.305  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:22:22.305  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 11:22:22.306  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.306  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.306  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.306  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 11:22:22.306  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.306  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:22:22.307  5829  5840 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 11:22:22.307  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 11:22:22.307  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:22:22.308  5829  5839 D BtGatt.GattService: stopScan() - queue size =0
11-04 11:22:22.308  5829  5875 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 11:22:22.309  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 11:22:22.309  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.309  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:22:22.310  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.310  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 11:22:22.310  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 11:22:22.311  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 11:22:22.311  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.312  5829  5848 D BtGatt.ScanManager: handling starting scan
11-04 11:22:22.312  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.312  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 11:22:22.312  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.312  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.312  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.312  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.312  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.313  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c503bd removed from the list
11-04 11:22:22.313  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:22:22.313  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.313  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:22:22.313  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.313  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 11:22:22.313  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 11:22:22.313  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1359f14 removed from the list
11-04 11:22:22.313  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.313  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 11:22:22.313  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 11:22:22.313  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.313  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.313  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 11:22:22.313  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.313  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.313  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@986a2fe added. We now have 3 listener(s)
11-04 11:22:22.314  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.314  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.314  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.314  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.314  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:22:22.314  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.314  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.315  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.315  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 11:22:22.315  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270fa5f added. We now have 4 listener(s)
11-04 11:22:22.315  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.316  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 11:22:22.317  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.317  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@addbcac added. We now have 4 listener(s)
11-04 11:22:22.317  5829  5845 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 11:22:22.317  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.317  5829  5848 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 11:22:22.319  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.319  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 11:22:22.319  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.319  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.319  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eded75 added. We now have 5 listener(s)
11-04 11:22:22.319  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.319  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:22.319  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 11:22:22.320  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-04 11:22:22.320  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 11:22:22.320  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 11:22:22.321  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 11:22:22.322  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 11:22:22.322  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.322  5829  5848 D BtGatt.ScanManager: Starting BLE batch scan
,11-04 11:22:22.322  5829  5848 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 11:22:22.324  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 11:22:22.324  5579  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 11:22:22.324  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 11:22:22.328  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.328  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 11:22:22.329  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 11:22:22.329  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 11:22:22.329  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 11:22:22.332  5829  5845 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 11:22:22.332  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:22:22.333  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.333  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 11:22:22.333  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 11:22:22.333  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 11:22:22.333  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 11:22:22.333  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.333  5579  5626 D BluetoothAdapter: STATE_ON
,11-04 11:22:22.337  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 11:22:22.337  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.337  5829  5839 D BtGatt.GattService: registerClient() - UUID=ff0fd41c-a043-44a1-9a12-c8372943bf75
11-04 11:22:22.337  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=ff0fd41c-a043-44a1-9a12-c8372943bf75, clientIf=5
,11-04 11:22:22.338  5579  5740 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 11:22:22.338  5829  5875 D BtGatt.GattService: start scan with filters
11-04 11:22:22.339  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:22:22.340  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 11:22:22.340  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.340  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 11:22:22.340  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.340  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 11:22:22.341  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 11:22:22.341  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.341  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 11:22:22.341  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 11:22:22.341  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.341  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.341  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-04 11:22:22.341  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 11:22:22.342  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.344  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.344  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:22:22.344  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:22:22.344  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.344  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.344  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.344  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.346  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 11:22:22.346  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.346  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:22:22.346  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.346  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.346  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:22:22.346  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.346  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.346  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@986a2fe removed from the list
11-04 11:22:22.346  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.346  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270fa5f removed from the list
,11-04 11:22:22.346  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:22:22.346  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.347  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:22:22.347  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.347  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 11:22:22.347  5579  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 11:22:22.347  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 11:22:22.347  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.347  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.347  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.347  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.347  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.347  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.348  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 11:22:22.348  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.348  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.348  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.348  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.348  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270fa5f not in the list
11-04 11:22:22.348  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.348  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 11:22:22.348  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.349  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:22:22.349  5829  5875 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 11:22:22.349  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 11:22:22.350  5579  5626 D BluetoothAdapter: STATE_ON
11-04 11:22:22.350  5829  5840 D BtGatt.GattService: stopScan() - queue size =0
11-04 11:22:22.350  5829  5839 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.351  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-04 11:22:22.351  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 11:22:22.352  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 11:22:22.352  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.352  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 11:22:22.352  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.353  5829  5848 D BtGatt.ScanManager: stopping BLe Batch
11-04 11:22:22.353  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.353  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 11:22:22.353  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.353  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.353  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.353  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.353  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.353  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:22:22.353  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eded75 removed from the list
11-04 11:22:22.353  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.353  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 11:22:22.353  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.353  5579  5579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 11:22:22.353  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 11:22:22.353  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.353  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@addbcac removed from the list
11-04 11:22:22.353  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 11:22:22.353  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 11:22:22.353  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.353  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.353  5579  5579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 11:22:22.353  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.354  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 11:22:22.354  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ba13d6 added. We now have 3 listener(s)
11-04 11:22:22.355  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.355  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.355  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.355  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.355  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9d657 added. We now have 4 listener(s)
11-04 11:22:22.355  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.355  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.356  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.356  5579  5579 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 11:22:22.356  5579  5579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-04 11:22:22.356  5579  5579 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 11:22:22.357  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 11:22:22.357  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 11:22:22.357  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.358  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 11:22:22.358  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 11:22:22.358  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f88f544 added. We now have 4 listener(s)
,11-04 11:22:22.359  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 11:22:22.359  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 11:22:22.359  5579  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 11:22:22.359  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 11:22:22.359  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea3562d added. We now have 5 listener(s)
11-04 11:22:22.359  5579  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 11:22:22.359  5579  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 11:22:22.360  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.360  5579  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 11:22:22.360  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 11:22:22.360  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.360  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.360  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ba13d6 removed from the list
11-04 11:22:22.360  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.360  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9d657 removed from the list
11-04 11:22:22.360  5579  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-04 11:22:22.360  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.361  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.361  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-04 11:22:22.361  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.361  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.361  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 11:22:22.361  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.361  5579  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9d657 not in the list
11-04 11:22:22.361  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.362  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.362  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.362  5579  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-04 11:22:22.362  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 11:22:22.362  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 11:22:22.362  5579  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 11:22:22.362  5579  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea3562d removed from the list
11-04 11:22:22.362  5579  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 11:22:22.362  5579  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 11:22:22.363  5579  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 11:22:22.363  5579  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f88f544 removed from the list
11-04 11:22:22.363  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 11:22:22.363  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 11:22:22.363  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-04 11:22:22.363  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:22.363  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-04 11:22:22.364  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:22.364  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:22:22.364  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.366  5829  5848 D BtGatt.ScanManager: handling starting scan
11-04 11:22:22.371  5829  5845 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 11:22:22.371  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.371  5829  5848 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 11:22:22.376  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 11:22:22.376  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.376  5829  5848 D BtGatt.ScanManager: Starting BLE batch scan
11-04 11:22:22.376  5829  5848 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 11:22:22.385  5829  5845 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 11:22:22.385  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:22:22.390  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 11:22:22.390  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:22:22.391  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:22:22.396  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:22:22.396  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.396  5829  5845 E BtGatt.ContextMap: Context not found for ID 5
,11-04 11:22:22.402  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 11:22:22.402  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.402  5829  5848 D BtGatt.ScanManager: stopping BLe Batch
,11-04 11:22:22.407  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 11:22:22.407  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 11:22:22.407  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 11:22:22.412  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 11:22:22.413  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 11:22:22.457   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:22.641  5889  5889 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 11:22:22.680  5889  5889 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 11:22:22.682  5889  5889 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 11:22:22.694   928  2889 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 11:22:22.695   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 11:22:22.695   928  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 11:22:22.716   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 11:22:22.734   508   922 D CommandListener: Setting iface cfg
,11-04 11:22:22.741   928  2889 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 11:22:22.747   928  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 11:22:22.755   928  5894 D DhcpClient: Receive thread started
,11-04 11:22:22.769  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 11:22:22.814  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 11:22:22.849   928  2889 E native  : do suspend false
,11-04 11:22:22.857  5579  5579 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 11:22:22.868   928  5893 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 11:22:22.884   928  5894 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172673, domain null
11-04 11:22:22.885   928  5893 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172673 seconds
,11-04 11:22:22.887   928  5893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 11:22:22.902   928  5894 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 11:22:22.903   928  5893 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 11:22:22.907   508   922 D CommandListener: Setting iface cfg
11-04 11:22:22.913   928  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 11:22:22.917   928  2889 E native  : do suspend true
11-04 11:22:22.918   928  5893 D DhcpClient: Scheduling renewal in 86399s
,11-04 11:22:22.944   928  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 11:22:22.946   928  2889 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 11:22:22.947   928  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 11:22:22.949   928  2891 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 11:22:22.955   928  2889 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 11:22:23.003   928  2891 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-04 11:22:23.003   928  2891 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 11:22:23.005   928  2891 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 11:22:23.006   928  2891 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 11:22:23.008   928  2891 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 11:22:23.016   928  2891 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 11:22:23.021   928  2891 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 11:22:23.021   928  2891 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-04 11:22:23.022   928  2891 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 11:22:23.022   928  2891 D ConnectivityService:    accepting network in place of null
11-04 11:22:23.022   928  2889 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 11:22:23.022   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 11:22:23.022   928  2891 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 11:22:23.046   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 11:22:23.068   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 11:22:23.072   928  2891 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 11:22:23.072   928  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 11:22:23.072  3680  3797 W QCNEJ   : |CORE| network available: 101
,11-04 11:22:23.073   928  2891 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-04 11:22:23.074  3680  3797 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 11:22:23.075  3680  3797 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 11:22:23.075  3680  3797 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 11:22:23.076   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-04 11:22:23.090  3926  3926 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 11:22:23.093  3926  3926 D SystemUpdateService: onCreate
,11-04 11:22:23.095  3908  3908 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 11:22:23.099  3926  3926 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 11:22:23.110  3926  3926 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 11:22:23.117  3926  4214 I iu.UploadsManager: num queued entries: 0
,11-04 11:22:23.117  3926  4214 I iu.UploadsManager: num updated entries: 0
11-04 11:22:23.117  3926  4214 I iu.SyncManager: NEXT; no task
,11-04 11:22:23.118  3926  5905 I SystemUpdateService: active receiver: enabled
,11-04 11:22:23.122  3926  3926 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 11:22:23.123  3926  3926 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 11:22:23.125  5716  5716 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 11:22:23.129  5716  5716 D SprintDMHelper: simOperator: 
11-04 11:22:23.130  5716  5716 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 11:22:23.155  3926  5905 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 11:22:23.159  3926  5905 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 11:22:23.159  3926  5905 I SystemUpdateService: now status is 0 (complete)
11-04 11:22:23.159  3926  5905 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 11:22:23.160  3926  5905 I SystemUpdateService: file has been verified
11-04 11:22:23.160  3926  5905 I SystemUpdateService: OTA package size = 21989297
,11-04 11:22:23.166  3926  5905 I SystemUpdateService: showing system update notification
,11-04 11:22:23.175   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 11:22:23.176  3926  3926 D SystemUpdateService: onDestroy
,11-04 11:22:23.458   547   547 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-04 11:22:23.744   928  5892 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169066, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 11:22:23.837   928  5891 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 11:22:23.892   928  5891 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 10:22:23 GMT], X-Android-Received-Millis=[1478254943890], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478254943866]}
,11-04 11:22:23.894   928  2891 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 11:22:23.895   928  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-04 11:22:23.895   928  2891 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 11:22:23.899   928  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 11:22:24.072   928  2891 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 11:22:24.539  5579  5913 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 11:22:24.539  5579  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:25.335  5579  5913 W !!      : call onHalfStreamCopied
,11-04 11:22:25.335  5579  5913 I testCopyDataAndClose: closing input stream
,11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 11:22:26.113  5579  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 11:22:26.471  3528  5915 I VacuumService: Vacuum at: now=1478254946471 tag=VacuumService
,11-04 11:22:26.516  3528  5918 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-04 11:22:26.547  3528  5916 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-04 11:22:26.551  3528  5916 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-04 11:22:26.574  3528  5918 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 11:22:26.867  3528  5916 W Uploader:  no longer exists, so no auth token.
,11-04 11:22:26.871  3528  5920 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 11:22:26.973  3528  5916 W Uploader:  no longer exists, so no auth token.
,11-04 11:22:26.984  3528  5918 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 11:22:27.074  3528  5920 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 11:22:27.170  3528  5918 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 11:22:27.285  3528  5920 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 11:22:30.575  5579  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:30.575  5579  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:31.028   928  2891 D ConnectivityService: handlePromptUnvalidated 101
,11-04 11:22:32.575  5579  5626 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-04 11:22:32.575  5579  5626 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:32.575  5579  5626 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-04 11:22:32.581  5579  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-04 11:22:32.581  5579  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:32.581  5579  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-04 11:22:32.744  5579  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 11:22:32.744  5579  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:34.364  5579  5926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 11:22:34.364  5579  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 11:22:34.364  5579  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 11:22:34.364  5579  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 11:22:34.365  5579  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 11:22:38.717  5579  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:38.717  5579  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:38.718  5579  5927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:38.718  5579  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:38.718  5579  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 11:22:38.718  5579  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 11:22:38.718  5579  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 11:22:38.719  5579  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 11:22:38.719  5579  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 11:22:38.719  5579  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 11:22:38.719  5579  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-04 11:22:38.719  5579  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:38.719  5579  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-04 11:22:38.721  5579  5626 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-04 11:22:38.724  5579  5928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:38.724  5579  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 11:22:38.724  5579  5928 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-04 11:22:38.725  5579  5928 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:38.725  5579  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 11:22:38.725  5579  5928 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 11:22:38.725  5579  5928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 11:22:38.725  5579  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 11:22:38.730  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-04 11:22:38.730  5579  5626 I jxcore-log: 
11-04 11:22:38.730  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-04 11:22:38.730  5579  5626 I jxcore-log: 
11-04 11:22:38.731  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-04 11:22:38.731  5579  5626 I jxcore-log: 
,11-04 11:22:38.731  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-04 11:22:38.731  5579  5626 I jxcore-log: 
11-04 11:22:38.731  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'Total duration:  92123'
11-04 11:22:38.731  5579  5626 I jxcore-log: 
,11-04 11:22:38.734  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 11:22:38.734  5579  5626 I jxcore-log: 
,11-04 11:22:38.737  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 11:22:38.737  5579  5626 I jxcore-log: 
11-04 11:22:38.738  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 11:22:38.738  5579  5626 I jxcore-log: 
11-04 11:22:38.738  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 11:22:38.738  5579  5626 I jxcore-log: 
11-04 11:22:38.739  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 11:22:38.739  5579  5626 I jxcore-log: 
11-04 11:22:38.739  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.739  5579  5626 I jxcore-log: 
11-04 11:22:38.739  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 11:22:38.739  5579  5626 I jxcore-log: 
11-04 11:22:38.739  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.739  5579  5626 I jxcore-log: 
11-04 11:22:38.740  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 11:22:38.740  5579  5626 I jxcore-log: 
11-04 11:22:38.740  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 11:22:38.740  5579  5626 I jxcore-log: 
11-04 11:22:38.740  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 11:22:38.740  5579  5626 I jxcore-log: 
,11-04 11:22:38.741  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 11:22:38.741  5579  5626 I jxcore-log: 
11-04 11:22:38.741  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.741  5579  5626 I jxcore-log: 
11-04 11:22:38.741  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 11:22:38.741  5579  5626 I jxcore-log: 
,11-04 11:22:38.741  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.741  5579  5626 I jxcore-log: 
11-04 11:22:38.741  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 11:22:38.741  5579  5626 I jxcore-log: 
11-04 11:22:38.742  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.742  5579  5626 I jxcore-log: 
11-04 11:22:38.742  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 11:22:38.742  5579  5626 I jxcore-log: 
11-04 11:22:38.742  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 11:22:38.742  5579  5626 I jxcore-log: 
11-04 11:22:38.742  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 11:22:38.742  5579  5626 I jxcore-log: 
11-04 11:22:38.743  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 11:22:38.743  5579  5626 I jxcore-log: 
,11-04 11:22:38.743  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 11:22:38.743  5579  5626 I jxcore-log: 
11-04 11:22:38.743  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 11:22:38.743  5579  5626 I jxcore-log: 
11-04 11:22:38.743  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 11:22:38.743  5579  5626 I jxcore-log: 
11-04 11:22:38.744  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 11:22:38.744  5579  5626 I jxcore-log: 
11-04 11:22:38.745  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 11:22:38.745  5579  5626 I jxcore-log: 
11-04 11:22:38.745  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 11:22:38.745  5579  5626 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-04 11:22:38.746  5579  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 11:22:38.746  5579  5626 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-04 11:22:38.746  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 11:22:38.746  5579  5626 I jxcore-log: 
11-04 11:22:38.746  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.746  5579  5626 I jxcore-log: 
11-04 11:22:38.746  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 11:22:38.746  5579  5626 I jxcore-log: 
,11-04 11:22:38.747  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.747  5579  5626 I jxcore-log: 
11-04 11:22:38.747  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 11:22:38.747  5579  5626 I jxcore-log: 
11-04 11:22:38.747  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 11:22:38.747  5579  5626 I jxcore-log: 
,11-04 11:22:38.750  5579  5579 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-04 11:22:38.752  5579  5626 I jxcore-log: 2016-11-04 10:22:38 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 11:22:38.752  5579  5626 I jxcore-log: 
,11-04 11:22:40.825  5579  5626 I jxcore-log: 2016-11-04 10:22:40 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-04 11:22:40.825  5579  5626 I jxcore-log: 
,11-04 11:22:40.826  5579  5626 I jxcore-log: 2016-11-04 10:22:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 11:22:40.826  5579  5626 I jxcore-log: 
,11-04 11:22:41.167  5579  5626 I jxcore-log: 2016-11-04 10:22:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 11:22:41.167  5579  5626 I jxcore-log: 
,11-04 11:22:41.180  5579  5626 I jxcore-log: 2016-11-04 10:22:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 11:22:41.180  5579  5626 I jxcore-log: 
,11-04 11:22:42.304  5579  5626 I jxcore-log: 2016-11-04 10:22:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 11:22:42.304  5579  5626 I jxcore-log: 
,11-04 11:22:42.496  5579  5626 I jxcore-log: 2016-11-04 10:22:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 11:22:42.496  5579  5626 I jxcore-log: 
,11-04 11:22:42.502  5579  5626 I jxcore-log: 2016-11-04 10:22:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 11:22:42.502  5579  5626 I jxcore-log: 
,11-04 11:22:42.506  5579  5626 I jxcore-log: 2016-11-04 10:22:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 11:22:42.506  5579  5626 I jxcore-log: 
,11-04 11:22:42.994  5579  5626 I jxcore-log: 2016-11-04 10:22:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 11:22:42.994  5579  5626 I jxcore-log: 
,11-04 11:22:43.039  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 11:22:43.039  5579  5626 I jxcore-log: 
,11-04 11:22:43.053  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 11:22:43.053  5579  5626 I jxcore-log: 
,11-04 11:22:43.057  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 11:22:43.057  5579  5626 I jxcore-log: 
,11-04 11:22:43.346  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 11:22:43.346  5579  5626 I jxcore-log: 
,11-04 11:22:43.459   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:43.473  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 11:22:43.473  5579  5626 I jxcore-log: 
,11-04 11:22:43.833  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 11:22:43.833  5579  5626 I jxcore-log: 
,11-04 11:22:43.841  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 11:22:43.841  5579  5626 I jxcore-log: 
,11-04 11:22:43.845  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 11:22:43.845  5579  5626 I jxcore-log: 
,11-04 11:22:43.850  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 11:22:43.850  5579  5626 I jxcore-log: 
,11-04 11:22:43.855  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 11:22:43.855  5579  5626 I jxcore-log: 
,11-04 11:22:43.883  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 11:22:43.883  5579  5626 I jxcore-log: 
,11-04 11:22:43.919  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 11:22:43.919  5579  5626 I jxcore-log: 
,11-04 11:22:43.926  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 11:22:43.926  5579  5626 I jxcore-log: 
,11-04 11:22:43.932  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 11:22:43.932  5579  5626 I jxcore-log: 
,11-04 11:22:43.948  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 11:22:43.948  5579  5626 I jxcore-log: 
,11-04 11:22:43.952  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 11:22:43.952  5579  5626 I jxcore-log: 
,11-04 11:22:43.958  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 11:22:43.958  5579  5626 I jxcore-log: 
,11-04 11:22:43.963  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 11:22:43.963  5579  5626 I jxcore-log: 
,11-04 11:22:43.976  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 11:22:43.976  5579  5626 I jxcore-log: 
,11-04 11:22:43.982  5579  5626 I jxcore-log: 2016-11-04 10:22:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 11:22:43.982  5579  5626 I jxcore-log: 
,11-04 11:22:44.004  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 11:22:44.004  5579  5626 I jxcore-log: 
,11-04 11:22:44.015  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 11:22:44.015  5579  5626 I jxcore-log: 
,11-04 11:22:44.038  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 11:22:44.038  5579  5626 I jxcore-log: 
,11-04 11:22:44.048  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 11:22:44.048  5579  5626 I jxcore-log: 
,11-04 11:22:44.061  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 11:22:44.061  5579  5626 I jxcore-log: 
,11-04 11:22:44.072  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 11:22:44.072  5579  5626 I jxcore-log: 
,11-04 11:22:44.079  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 11:22:44.079  5579  5626 I jxcore-log: 
,11-04 11:22:44.101  5579  5626 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 11:22:44.102  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 11:22:44.102  5579  5626 I jxcore-log: 
,11-04 11:22:44.191  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:44.191  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:44.191  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:44.191  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:44.191  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:44.191  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:44.191  5579  5626 I jxcore-log: 
,11-04 11:22:44.396  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:44.396  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:44.396  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:44.396  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:44.396  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:44.396  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:44.396  5579  5626 I jxcore-log: 
,11-04 11:22:44.399  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:44.399  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:44.399  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:44.399  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:44.399  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:44.399  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:44.399  5579  5626 I jxcore-log: 
,11-04 11:22:44.460   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:44.796  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:44.796  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:44.796  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:44.796  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:44.796  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:44.796  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:44.796  5579  5626 I jxcore-log: 
,11-04 11:22:44.800  5579  5626 I jxcore-log: 2016-11-04 10:22:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:44.800  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:44.800  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:44.800  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:44.800  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:44.800  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:44.800  5579  5626 I jxcore-log: 
,11-04 11:22:45.437  5579  5626 I jxcore-log: 2016-11-04 10:22:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:45.437  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:45.437  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:45.437  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:45.437  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:45.437  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:45.437  5579  5626 I jxcore-log: 
,11-04 11:22:45.441  5579  5626 I jxcore-log: 2016-11-04 10:22:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:45.441  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:45.441  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:45.441  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:45.441  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:45.441  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:45.441  5579  5626 I jxcore-log: 
,11-04 11:22:45.461   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:46.461   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:46.487  5579  5626 I jxcore-log: 2016-11-04 10:22:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:46.487  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:46.487  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:46.487  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:46.487  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:46.487  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:46.487  5579  5626 I jxcore-log: 
,11-04 11:22:46.494  5579  5626 I jxcore-log: 2016-11-04 10:22:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:46.494  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:46.494  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:46.494  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:46.494  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:46.494  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:46.494  5579  5626 I jxcore-log: 
,11-04 11:22:47.463   547   547 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 11:22:47.534  5579  5626 I jxcore-log: 2016-11-04 10:22:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:47.534  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:47.534  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:47.534  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:47.534  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:47.534  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:47.534  5579  5626 I jxcore-log: 
,11-04 11:22:47.537  5579  5626 I jxcore-log: 2016-11-04 10:22:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:47.537  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:47.537  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:47.537  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:47.537  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:47.537  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:47.537  5579  5626 I jxcore-log: 
,11-04 11:22:48.463   547   547 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 11:22:48.567  5579  5626 I jxcore-log: 2016-11-04 10:22:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:48.567  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:48.567  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:48.567  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:48.567  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:48.567  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:48.567  5579  5626 I jxcore-log: 
,11-04 11:22:48.573  5579  5626 I jxcore-log: 2016-11-04 10:22:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:48.573  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:48.573  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:48.573  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:48.573  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:48.573  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:48.573  5579  5626 I jxcore-log: 
,11-04 11:22:49.600  5579  5626 I jxcore-log: 2016-11-04 10:22:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:49.600  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:49.600  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:49.600  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:49.600  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:49.600  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:49.600  5579  5626 I jxcore-log: 
,11-04 11:22:49.603  5579  5626 I jxcore-log: 2016-11-04 10:22:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:49.603  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:49.603  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:49.603  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:49.603  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:49.603  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:49.603  5579  5626 I jxcore-log: 
,11-04 11:22:50.639  5579  5626 I jxcore-log: 2016-11-04 10:22:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:50.639  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:50.639  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:50.639  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:50.639  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:50.639  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:50.639  5579  5626 I jxcore-log: 
,11-04 11:22:50.642  5579  5626 I jxcore-log: 2016-11-04 10:22:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:50.642  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:50.642  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:50.642  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:50.642  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:50.642  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:50.642  5579  5626 I jxcore-log: 
,11-04 11:22:51.672  5579  5626 I jxcore-log: 2016-11-04 10:22:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:51.672  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:51.672  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:51.672  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:51.672  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:51.672  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:51.672  5579  5626 I jxcore-log: 
,11-04 11:22:51.676  5579  5626 I jxcore-log: 2016-11-04 10:22:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:51.676  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:51.676  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:51.676  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:51.676  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:51.676  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:51.676  5579  5626 I jxcore-log: 
,11-04 11:22:52.746  5579  5626 I jxcore-log: 2016-11-04 10:22:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:52.746  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:52.746  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:52.746  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:52.746  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:52.746  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:52.746  5579  5626 I jxcore-log: 
,11-04 11:22:52.750  5579  5626 I jxcore-log: 2016-11-04 10:22:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:52.750  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:52.750  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:52.750  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:52.750  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:52.750  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:52.750  5579  5626 I jxcore-log: 
,11-04 11:22:53.786  5579  5626 I jxcore-log: 2016-11-04 10:22:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:53.786  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:53.786  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:53.786  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:53.786  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:53.786  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:53.786  5579  5626 I jxcore-log: 
,11-04 11:22:53.790  5579  5626 I jxcore-log: 2016-11-04 10:22:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:53.790  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:53.790  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:53.790  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:53.790  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:53.790  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:53.790  5579  5626 I jxcore-log: 
,11-04 11:22:54.818  5579  5626 I jxcore-log: 2016-11-04 10:22:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:54.818  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:54.818  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:54.818  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:54.818  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:54.818  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:54.818  5579  5626 I jxcore-log: 
,11-04 11:22:54.821  5579  5626 I jxcore-log: 2016-11-04 10:22:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:54.821  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:54.821  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:54.821  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:54.821  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:54.821  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:54.821  5579  5626 I jxcore-log: 
,11-04 11:22:55.852  5579  5626 I jxcore-log: 2016-11-04 10:22:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:55.852  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:55.852  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:55.852  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:55.852  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:55.852  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:55.852  5579  5626 I jxcore-log: 
,11-04 11:22:55.855  5579  5626 I jxcore-log: 2016-11-04 10:22:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:55.855  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:55.855  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:55.855  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:55.855  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:55.855  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:55.855  5579  5626 I jxcore-log: 
,11-04 11:22:57.019  5579  5626 I jxcore-log: 2016-11-04 10:22:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:57.019  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:57.019  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:57.019  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:57.019  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:57.019  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:57.019  5579  5626 I jxcore-log: 
,11-04 11:22:57.023  5579  5626 I jxcore-log: 2016-11-04 10:22:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:57.023  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:57.023  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:57.023  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:57.023  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:57.023  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:57.023  5579  5626 I jxcore-log: 
,11-04 11:22:58.062  5579  5626 I jxcore-log: 2016-11-04 10:22:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 11:22:58.062  5579  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 11:22:58.062  5579  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 11:22:58.062  5579  5626 I jxcore-log: emit@events.js:82:1
11-04 11:22:58.062  5579  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 11:22:58.062  5579  5626 I jxcore-log: emit@events.js:82:1'
11-04 11:22:58.062  5579  5626 I jxcore-log: 
,11-04 11:22:58.072  5579  5626 E jxcore  : Error!: error is undefined
11-04 11:22:58.072  5579  5626 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 11:22:58.077  5579  5626 I jxcore-log: 2016-11-04 10:22:58 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 11:22:58.077  5579  5626 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-04 11:22:58.077  5579  5626 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 11:22:58.077  5579  5626 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 11:22:58.077  5579  5626 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 11:22:58.077  5579  5626 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 11:22:58.077  5579  5626 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 11:22:58.077  5579  5626 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 11:22:58.083  5579  5626 I jxcore-log: 2016-11-04 10:22:58 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 11:22:58.083  5579  5626 I jxcore-log: 
,11-04 11:22:58.086  5579  5626 E jxcore-log: TypeError: 
11-04 11:22:58.086  5579  5626 E jxcore-log: error is undefined
11-04 11:22:58.086  5579  5626 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-04 11:22:58.086  5579  5626 E jxcore-log: 
,11-04 11:22:58.170   928  4228 D GraphicsStats: Buffer count: 2
,11-04 11:22:58.171   928  3358 I WindowState: WIN DEATH: Window{7b1a02a u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-04 11:22:58.171   928  2890 D WifiService: Client connection lost with reason: 4
,11-04 11:22:58.187   528   528 I Zygote  : Process 5579 exited cleanly (139)
,11-04 11:22:58.192   928  3542 I ActivityManager: Process com.test.thalitest (pid 5579) has died
,11-04 11:22:58.210   928  3542 I ActivityManager: Start proc 5931:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 11:22:58.291  5931  5931 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 11:22:58.312  5931  5931 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 11:22:58.317  5931  5931 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3637-3639)
,11-04 11:22:58.317  5931  5931 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 11:22:58.327  5931  5931 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b853923}
11-04 11:22:58.327  5931  5931 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 11:22:58.327  5931  5931 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 11:22:58.330  5931  5931 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 11:22:58.331  5931  5931 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 11:22:58.341  5931  5931 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 11:22:58.349  5931  5931 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 11:22:58.349  5931  5931 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 11:22:58.349  5931  5931 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 11:22:58.349  5931  5931 I Adreno  : Build Date                       : 12/06/15
11-04 11:22:58.349  5931  5931 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 11:22:58.349  5931  5931 I Adreno  : Local Branch                     : mybranch17112971
11-04 11:22:58.349  5931  5931 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 11:22:58.349  5931  5931 I Adreno  : Remote Branch                    : NONE
11-04 11:22:58.349  5931  5931 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 11:22:58.383   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42299c1:true
,11-04 11:22:58.394  4139  4139 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[30920]" dev="sockfs" ino=30920 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.397  4139  4139 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[30920]" dev="sockfs" ino=30920 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.407  5931  5931 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 11:22:58.414  5931  5931 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 11:22:58.444  4139  4139 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34443]" dev="sockfs" ino=34443 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.445  5931  5967 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-04 11:22:58.444  4139  4139 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34443]" dev="sockfs" ino=34443 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.447  3754  3754 W Binder_9: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[15862]" dev="sockfs" ino=15862 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.447  3754  3754 W Binder_9: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[15862]" dev="sockfs" ino=15862 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.449  5931  5954 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 11:22:58.479  5931  5967 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 11:22:58.495   928  3563 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5579 uid 10077
,11-04 11:22:58.498  3588  3588 I Keyboard.Facilitator: onFinishInput()
11-04 11:22:58.494  3563  3563 W Binder_7: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[33548]" dev="sockfs" ino=33548 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.494  3563  3563 W Binder_7: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[33548]" dev="sockfs" ino=33548 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.494  4228  4228 W Binder_C: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[33547]" dev="sockfs" ino=33547 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.494  4228  4228 W Binder_C: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[33547]" dev="sockfs" ino=33547 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:58.517   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +286ms (total +319ms)
,11-04 11:22:58.519  5931  5931 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5931
,11-04 11:22:58.573  5931  5931 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 11:22:58.599  5929  5929 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 11:22:58.616  5929  5929 D AndroidRuntime: CheckJNI is OFF
,11-04 11:22:58.639  5929  5929 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 11:22:58.662  5929  5929 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 11:22:58.676  5929  5929 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 11:22:58.686   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-04 11:22:58.686   928   941 I ActivityManager: Killing 5931:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 11:22:58.716   928  3564 D GraphicsStats: Buffer count: 2
,11-04 11:22:58.716   928  3140 I WindowState: WIN DEATH: Window{307ff84 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 11:22:58.789   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-04 11:22:58.790   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-04 11:22:58.791   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-04 11:22:58.791   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 11:22:58.791   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 11:22:58.791   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:22:58.791   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 11:22:58.791   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 11:22:58.791   928   941 I ActivityManager:   Force finishing activity ActivityRecord{ee8a972 u0 com.test.thalitest/.MainActivity t68}
11-04 11:22:58.793   928   952 I art     : Starting a blocking GC Explicit
,11-04 11:22:58.800   928  3779 W ActivityManager: Spurious death for ProcessRecord{b614ba2 0:com.test.thalitest/u0a77}, curProc for 5931: null
,11-04 11:22:58.889   928   952 I art     : Explicit concurrent mark sweep GC freed 53933(3MB) AllocSpace objects, 20(400KB) LOS objects, 33% free, 29MB/43MB, paused 1.923ms total 95.510ms
,11-04 11:22:58.911   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 11:22:58.915  5929  5929 I art     : System.exit called, status: 0
,11-04 11:22:58.915  5929  5929 I AndroidRuntime: VM exiting with result code 0.
,11-04 11:22:58.935   928   952 I ActivityManager: Start proc 5981:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-04 11:22:58.935   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 11:22:58.940   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-04 11:22:58.943  5829  5829 D BluetoothMapAppObserver: onReceive
,11-04 11:22:58.943  5829  5829 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 11:22:58.951  3588  3588 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 11:22:58.958   928  2880 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-04 11:22:58.959  3657  4054 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-04 11:22:58.981  3588  5993 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 11:22:58.981  3724  3724 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-04 11:22:58.985  3344  5996 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 11:22:58.998  3588  5993 I Decoder : createOrResetDecoder
,11-04 11:22:59.027   314   314 W kworker/1:2: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 11:22:59.034   314   314 W kworker/1:2: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 11:22:59.042   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 11:22:59.045  3528  3528 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-04 11:22:59.045  3528  3528 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-04 11:22:59.046   928  3564 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5931 uid 10077
,11-04 11:22:59.044  3564  3564 W Binder_8: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[28783]" dev="sockfs" ino=28783 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 11:22:59.044  3564  3564 W Binder_8: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[28783]" dev="sockfs" ino=28783 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 11:22:59.049  3588  3588 I Keyboard.Facilitator: onFinishInput()
11-04 11:22:59.052  3752  3873 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-04 11:22:59.054   314   314 W kworker/1:2: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 11:22:59.068   928  3759 I ActivityManager: Start proc 6000:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-04 11:22:59.068  3752  3873 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-04 11:22:59.068  3752  3873 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3752
11-04 11:22:59.068  3752  3873 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 11:22:59.068  3752  3873 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-04 11:22:59.074  3344  3369 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj1E9E3C91C) - 
,11-04 11:22:59.076   928  6006 E DropBoxManagerService: Can't write: system_app_crash
11-04 11:22:59.076   928  6006 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 11:22:59.076   928  6006 E DropBoxManagerService: 	... 5 more
,11-04 11:22:59.077   928   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-04 11:22:59.086  3528  3528 I ConfigService: onCreate
,11-04 11:22:59.089  3528  6014 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-04 11:22:59.089  3528  6014 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-04 11:22:59.089  3528  6014 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-04 11:22:59.090  3752  3873 I Process : Sending signal. PID: 3752 SIG: 9
,11-04 11:22:59.091  3528  6014 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-04 11:22:59.107  3926  6013 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-04 11:22:59.107  3926  6013 D AccountUtils: Clearing selected account for com.test.thalitest
,11-04 11:22:59.121  3588  5993 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-04 11:22:59.129   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
