#### Test 93371269d9d2d87_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-15 16:39:08.204  3940  4301 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-15 16:39:08.274  3940  4301 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
--------- beginning of system
11-15 16:39:08.618   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-15 16:39:08.634  5686  5686 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-15 16:39:08.638  5686  5686 D AndroidRuntime: CheckJNI is OFF
11-15 16:39:08.662  5686  5686 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-15 16:39:08.694  5686  5686 I Radio-JNI: register_android_hardware_Radio DONE
11-15 16:39:08.709  5686  5686 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-15 16:39:08.728   930  3915 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-15 16:39:08.748  5686  5686 D AndroidRuntime: Shutting down VM
11-15 16:39:08.755  4049  4063 W SearchService: Abort, client detached.
11-15 16:39:08.767  4049  4049 I HotwordDetector: Closing mic
11-15 16:39:08.768  4049  4275 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a381a5e
11-15 16:39:08.768  4049  4289 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 16:39:08.779   930   940 I ActivityManager: Start proc 5695:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-15 16:39:08.848   512  4291 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 16:39:08.849   512  4291 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-15 16:39:08.854   512  4291 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-15 16:39:08.854   512  4291 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 16:39:08.855   512  3076 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-15 16:39:08.856  4049  4280 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-15 16:39:08.856  4049  4288 I MicroRecognitionRnrImpl: Detection finished
11-15 16:39:08.871  5695  5695 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-15 16:39:08.899  5695  5695 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-15 16:39:08.960  5695  5695 I LibraryLoader: Time to load native libraries: 58 ms (timestamps 4950-5008)
11-15 16:39:08.960  5695  5695 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 16:39:08.994  5695  5695 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {58c97ba}
11-15 16:39:08.995  5695  5695 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-15 16:39:08.995  5695  5695 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-15 16:39:09.001  5695  5695 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-15 16:39:09.002  5695  5695 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-15 16:39:09.052  5695  5695 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-15 16:39:09.066  5695  5695 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-15 16:39:09.066  5695  5695 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-15 16:39:09.066  5695  5695 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 16:39:09.066  5695  5695 I Adreno  : Build Date                       : 12/06/15
11-15 16:39:09.066  5695  5695 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 16:39:09.066  5695  5695 I Adreno  : Local Branch                     : mybranch17112971
11-15 16:39:09.066  5695  5695 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 16:39:09.066  5695  5695 I Adreno  : Remote Branch                    : NONE
11-15 16:39:09.066  5695  5695 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 16:39:09.131   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33ab516:true
,11-15 16:39:09.169   758   758 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[34928]" dev="sockfs" ino=34928 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.169   758   758 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34928]" dev="sockfs" ino=34928 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.184  5695  5695 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-15 16:39:09.193  5695  5695 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-15 16:39:09.222   758   758 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[35931]" dev="sockfs" ino=35931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.222   758   758 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[35931]" dev="sockfs" ino=35931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:09.226  5695  5732 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 16:39:09.226  3223  3223 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[15045]" dev="sockfs" ino=15045 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.231  5695  5719 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-15 16:39:09.226  3223  3223 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15045]" dev="sockfs" ino=15045 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.251  5695  5732 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 16:39:09.336  3221  3221 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32977]" dev="sockfs" ino=32977 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.336  3221  3221 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32977]" dev="sockfs" ino=32977 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:09.340   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +583ms
11-15 16:39:09.339  3658  3658 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32976]" dev="sockfs" ino=32976 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:09.339  3658  3658 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32976]" dev="sockfs" ino=32976 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:09.344  3756  3756 I Keyboard.Facilitator: onFinishInput()
,11-15 16:39:09.397  5695  5695 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5695
,11-15 16:39:09.500  5695  5695 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-15 16:39:09.698  5695  5734 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -576718544
,11-15 16:39:09.702  5695  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-15 16:39:09.702  5695  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-15 16:39:09.702  5695  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-15 16:39:09.702  5695  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-15 16:39:09.702  5695  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-15 16:39:09.702  5695  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23482a0 added. We now have 1 listener(s)
,11-15 16:39:09.704  5695  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-15 16:39:09.705  5695  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 16:39:09.705  5695  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 16:39:09.705  5695  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-15 16:39:09.707  5695  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3202ff added. We now have 1 listener(s)
11-15 16:39:09.708  5695  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 16:39:09.712   930  3055 D WifiService: New client listening to asynchronous messages
,11-15 16:39:09.712  5695  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 16:39:09.712  5695  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-15 16:39:09.713  5695  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-15 16:39:09.713  5695  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-15 16:39:09.713  5695  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-15 16:39:09.713  5695  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-15 16:39:09.713  5695  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-15 16:39:09.715  5695  5734 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 16:39:09.934  5695  5695 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-15 16:39:10.140  5695  5704 I art     : Background sticky concurrent mark sweep GC freed 87739(8MB) AllocSpace objects, 16(1476KB) LOS objects, 21% free, 25MB/32MB, paused 2.076ms total 116.759ms
,11-15 16:39:10.301  5695  5742 W jxcore-log: Initializing JXcore engine
11-15 16:39:10.301  5695  5742 W jxcore-log: JXcore engine is ready
,11-15 16:39:10.322  5742  5742 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13013 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-15 16:39:10.322  5742  5742 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14390]" dev="sockfs" ino=14390 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-15 16:39:10.322  5742  5742 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-15 16:39:10.322  5742  5742 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34061]" dev="sockfs" ino=34061 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-15 16:39:10.332  5695  5742 W jxcore-log: Starting JXcore engine
,11-15 16:39:10.382  5695  5742 W jxcore-log: Platform android
11-15 16:39:10.382  5695  5742 W jxcore-log: 
11-15 16:39:10.382  5695  5742 W jxcore-log: Process ARCH arm
11-15 16:39:10.382  5695  5742 W jxcore-log: 
,11-15 16:39:10.526  5695  5742 I jxcore-log: JXcore Cordova bridge is ready!
11-15 16:39:10.526  5695  5742 I jxcore-log: 
,11-15 16:39:10.526  5695  5742 W jxcore-log: JXcore engine is started
,11-15 16:39:10.543  5695  5734 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-15 16:39:10.550  5695  5695 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-15 16:39:12.360  3643  3643 I ConfigService: onDestroy
,11-15 16:39:13.775   930  3862 I ActivityManager: Killing 5135:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-15 16:39:14.661   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 16:39:14.752  4049  4049 I art     : Waiting for a blocking GC DisableMovingGc
,11-15 16:39:14.763  4049  4049 I art     : WaitForGcToComplete blocked for 10.471ms for cause DisableMovingGc
,11-15 16:39:14.763  4049  4049 I art     : Starting a blocking GC DisableMovingGc
,11-15 16:39:16.909   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:17.910   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:18.802   930  3018 I ActivityManager: Killing 5477:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-15 16:39:18.885  4049  5744 W CronetSyncConnectionRcs: Upload content type not set.
,11-15 16:39:18.911   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:19.912   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:20.207  5695  5742 I jxcore-log: 2016-11-15 15:39:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-15 16:39:20.207  5695  5742 I jxcore-log: 
,11-15 16:39:20.209  5695  5742 I jxcore-log: 2016-11-15 15:39:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-15 16:39:20.209  5695  5742 I jxcore-log: 
,11-15 16:39:20.214  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 16:39:20.214  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 16:39:20.216  5695  5742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 16:39:20.218  5695  5742 I jxcore-log: 2016-11-15 15:39:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-15 16:39:20.218  5695  5742 I jxcore-log: 
11-15 16:39:20.220  5695  5742 I jxcore-log: 2016-11-15 15:39:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-15 16:39:20.220  5695  5742 I jxcore-log: 
,11-15 16:39:20.472  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 16:39:20.472  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6c3ea added. We now have 2 listener(s)
11-15 16:39:20.473  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:20.473  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 16:39:20.473  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 16:39:20.473  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 16:39:20.473  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ee6db added. We now have 2 listener(s)
11-15 16:39:20.473  5695  5742 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 16:39:20.474  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 16:39:20.475  5695  5742 D ExecuteNativeTests: Running unit tests
,11-15 16:39:20.476  5695  5742 D BluetoothAdapter: enable(): BT is already enabled..!
11-15 16:39:20.476   930  3658 D WifiService: setWifiEnabled: true pid=5695, uid=10077
11-15 16:39:20.476   930  3658 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 16:39:20.718   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 16:39:20.914   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:21.914   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 16:39:22.091  4909  4971 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-15 16:39:22.092  4909  4909 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-15 16:39:23.744   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 16:39:30.482  5695  5742 I com.test.thalitest.ThaliTestRunner: Running UT
,11-15 16:39:30.570  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,11-15 16:39:30.570  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f990ec added. We now have 3 listener(s)
11-15 16:39:30.572  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:30.572  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 16:39:30.572  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 16:39:30.572  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 16:39:30.572  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef2ccb5 added. We now have 3 listener(s)
11-15 16:39:30.572  5695  5742 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 16:39:30.574  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 16:39:30.578  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-15 16:39:30.578  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 16:39:30.578  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:30.578  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:30.578  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:30.579  5695  5742 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-15 16:39:30.579  5695  5742 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 16:39:30.579  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 16:39:30.579  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:30.579  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:30.580  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:30.580  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-15 16:39:30.580  5695  5742 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-15 16:39:30.584  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-15 16:39:30.585  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-15 16:39:30.586  5695  5742 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-15 16:39:30.587  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 16:39:30.587  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 16:39:30.590  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 16:39:30.591  5695  5742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 16:39:30.592  5695  5742 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-15 16:39:30.592  5695  5742 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-15 16:39:30.592  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-15 16:39:30.592  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.592  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.592  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.592  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:30.592  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 16:39:30.592  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 16:39:30.593  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:30.594  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 16:39:30.594  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 16:39:30.594  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 16:39:30.594  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 16:39:30.594  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 16:39:30.595  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-15 16:39:30.596  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 16:39:30.596  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:30.596  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 16:39:30.596  5695  5749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-15 16:39:30.598  5695  5749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:30.598  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 16:39:30.598  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 16:39:30.598  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 16:39:30.599  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 16:39:30.599  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 16:39:30.599  5695  5749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 16:39:30.600  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.600  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 16:39:30.596  4941  4941 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32077]" dev="sockfs" ino=32077 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:30.596  4941  4941 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32077]" dev="sockfs" ino=32077 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:30.601  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 16:39:30.601  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:30.601  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-15 16:39:30.602  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:30.602  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.602  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 16:39:30.602  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 16:39:30.603  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:30.603  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-15 16:39:30.603  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 16:39:30.603  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:30.603  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.603  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 16:39:30.603  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:30.603  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.603  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:30.604  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.604  5695  5742 D BluetoothAdapter: STATE_ON
,11-15 16:39:30.606  4731  4743 D BtGatt.GattService: registerClient() - UUID=e6125412-32a4-4ebd-8024-5bba7aee71fb
,11-15 16:39:30.607  4731  4793 D BtGatt.GattService: onClientRegistered() - UUID=e6125412-32a4-4ebd-8024-5bba7aee71fb, clientIf=5
,11-15 16:39:30.608  5695  5706 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 16:39:30.609  4731  4795 D BtGatt.AdvertiseManager: message : 0
11-15 16:39:30.611  4731  4795 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 16:39:30.624  4731  4793 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 16:39:30.630  4731  4793 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 16:39:30.631  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.631  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.631  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 16:39:30.632  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 16:39:30.632  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.633  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.633  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.633  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:30.633  5695  5742 I io.jxcore.node.ConnectionHelper: start: OK
,11-15 16:39:30.633  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.634  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 16:39:30.634  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 16:39:30.635  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.635  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.635  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 16:39:30.635  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.637  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.637  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 16:39:30.637  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.637  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.637  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:30.637  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 16:39:31.136  5695  5742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 16:39:31.136  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-15 16:39:31.136  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 16:39:31.137  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-15 16:39:31.138  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 16:39:31.139  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 16:39:31.139  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 16:39:31.139  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 16:39:31.139  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-15 16:39:31.139  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 16:39:31.139  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 16:39:31.139  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 16:39:31.139  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 16:39:31.139  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 16:39:31.140  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 16:39:31.140  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 16:39:31.140  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-15 16:39:31.140  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 16:39:31.140  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 16:39:31.141  5695  5742 ,V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 16:39:31.141  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 16:39:31.141  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 16:39:31.142  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 16:39:31.142  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 16:39:31.142  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 16:39:31.143  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 16:39:31.143  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 16:39:31.143  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 16:39:31.143  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 16:39:31.143  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 16:39:31.143  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 16:39:31.143  5695  5749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 16:39:31.144  5695  5749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 16:39:31.144  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 16:39:31.144  5695  5749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 16:39:31.144  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.144  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.144  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.145  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.146  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:31.146  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 16:39:31.147  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:31.147  5695  5742 D BluetoothLeScanner: could not find callback wrapper
11-15 16:39:31.147  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 16:39:31.147  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.147  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.147  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.148  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 16:39:31.148  5695  5742 D org.thaliproject.p2p.btcon,nectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.149  4731  4795 D BtGatt.AdvertiseManager: message : 1
11-15 16:39:31.150  4731  4795 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 16:39:31.162  4731  4793 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 16:39:31.163  4731  4793 D BtGatt.GattService: Client app is not null!
,11-15 16:39:31.164  4731  4941 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 16:39:31.165  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 16:39:31.165  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.165  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 16:39:31.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 16:39:31.166  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 16:39:31.167  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 16:39:31.167  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.168  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.168  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:31.168  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.169  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.169  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 16:39:31.169  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 16:39:31.169  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:31.170  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:31.170  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 16:39:31.170  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:31.170  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-15 16:39:31.170  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.170  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 16:39:31.170  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 16:39:31.170  5695  5742 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 16:39:31.170  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.171  5695  5742 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 16:39:31.171  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.171  5695  5742 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-15 16:39:31.171  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-15 16:39:31.171  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 16:39:31.171  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.171  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.171  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.171  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.171  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:31.172  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 16:39:31.172  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 16:39:31.172  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:31.173  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.173  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.173  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.174  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.174  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:31.175  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 16:39:31.175  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 16:39:31.175  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 16:39:31.176  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 16:39:31.176  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 16:39:31.176  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 16:39:31.176  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:31.176  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 16:39:31.176  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 16:39:31.179  5695  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 16:39:31.179  4949  4949 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32083]" dev="sockfs" ino=32083 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:31.179  4949  4949 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32083]" dev="sockfs" ino=32083 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:31.181  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 16:39:31.181  5695  5752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:31.181  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-15 16:39:31.181  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 16:39:31.185  5695  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 16:39:31.188  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.188  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 16:39:31.189  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 16:39:31.189  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:31.189  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-15 16:39:31.191  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.192  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.192  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 16:39:31.192  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 16:39:31.192  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:31.192  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-15 16:39:31.192  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.193  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.193  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.193  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 16:39:31.193  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.193  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.193  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.193  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.195  5695  5742 D BluetoothAdapter: STATE_ON
,11-15 16:39:31.198  4731  4941 D BtGatt.GattService: registerClient() - UUID=9c4aa692-99a4-433f-92cd-a0f5c4f1b753
11-15 16:39:31.199  4731  4793 D BtGatt.GattService: onClientRegistered() - UUID=9c4aa692-99a4-433f-92cd-a0f5c4f1b753, clientIf=5
,11-15 16:39:31.199  5695  5705 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 16:39:31.200  4731  4795 D BtGatt.AdvertiseManager: message : 0
,11-15 16:39:31.204  4731  4795 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 16:39:31.215  4731  4793 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 16:39:31.223  4731  4793 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 16:39:31.224  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.224  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.224  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-15 16:39:31.224  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.224  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.225  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.225  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.225  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.225  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 16:39:31.227  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 16:39:31.228  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.229  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.229  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.229  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.229  5695  5742 I io.jxcore.node.ConnectionHelper: start: OK
11-15 16:39:31.229  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-15 16:39:31.230  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 16:39:31.230  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.231  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.231  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-15 16:39:31.231  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.234  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.234  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 16:39:31.234  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.234  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.234  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-15 16:39:31.234  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 16:39:31.734  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-15 16:39:31.734  5695  5742 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 16:39:31.734  5695  5742 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-15 16:39:31.735  5695  5742 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 16:39:31.735  5695  5742 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-15 16:39:31.735  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-15 16:39:31.736  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.736  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 16:39:31.736  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.736  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 16:39:31.737  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.738  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-15 16:39:31.740  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.740  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.741  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.743  4731  4795 D BtGatt.AdvertiseManager: message : 1
11-15 16:39:31.745  4731  4795 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 16:39:31.757  4731  4793 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 16:39:31.757  4731  4793 D BtGatt.GattService: Client app is not null!
,11-15 16:39:31.758  4731  4949 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 16:39:31.759  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 16:39:31.760  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.760  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 16:39:31.760  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.760  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.760  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.761  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 16:39:31.761  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.761  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.761  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.761  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-15 16:39:31.761  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 16:39:31.761  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:31.761  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-15 16:39:31.762  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.762  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.762  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.762  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 16:39:31.762  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.762  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.762  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.762  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.764  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:31.768  4731  4949 D BtGatt.GattService: registerClient() - UUID=8641c012-928c-49db-be5c-32437111c4f9
11-15 16:39:31.768  4731  4793 D BtGatt.GattService: onClientRegistered() - UUID=8641c012-928c-49db-be5c-32437111c4f9, clientIf=5
,11-15 16:39:31.769  5695  5706 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 16:39:31.770  4731  4795 D BtGatt.AdvertiseManager: message : 0
,11-15 16:39:31.772  4731  4795 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 16:39:31.782  4731  4793 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 16:39:31.788  4731  4793 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 16:39:31.790  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 16:39:31.790  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.790  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:31.791  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-15 16:39:31.791  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 16:39:31.791  5695  5742 I io.jxcore.node.ConnectionHelper: start: OK
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.791  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 16:39:31.791  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 16:39:31.792  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.792  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.792  5695  5742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 16:39:31.792  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 16:39:31.792  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-15 16:39:31.792  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 16:39:31.792  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 16:39:31.792  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 16:39:31.793  5695  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 16:39:31.793  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 16:39:31.793  5695  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 16:39:31.793  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 16:39:31.793  5695  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-15 16:39:31.793  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 16:39:31.793  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 16:39:31.793  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:31.793  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 16:39:31.793  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 16:39:31.793  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 16:39:31.794  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 16:39:31.794  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 16:39:31.794  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.794  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.794  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.794  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.795  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:31.796  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-15 16:39:31.796  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:31.797  5695  5742 D BluetoothLeScanner: could not find callback wrapper
11-15 16:39:31.797  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 16:39:31.797  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.797  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.797  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.797  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 16:39:31.797  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.798  4731  4795 D BtGatt.AdvertiseManager: message : 1
,11-15 16:39:31.799  4731  4795 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 16:39:31.805  4731  4793 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 16:39:31.805  4731  4793 D BtGatt.GattService: Client app is not null!
,11-15 16:39:31.806  4731  4745 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 16:39:31.806  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 16:39:31.807  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.807  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-15 16:39:31.807  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.807  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.807  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.807  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 16:39:31.807  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 16:39:31.808  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 16:39:31.808  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.809  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.809  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:31.809  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.810  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.810  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 16:39:31.810  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 16:39:31.810  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:31.810  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:31.810  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:31.810  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.810  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-15 16:39:31.811  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 16:39:31.811  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.811  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.811  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 16:39:31.811  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.812  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-15 16:39:31.812  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.812  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.812  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.812  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:31.813  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,11-15 16:39:31.813  5695  5742 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-15 16:39:31.814  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-15 16:39:31.815  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 16:39:31.815  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-15 16:39:31.816  5695  5742 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-15 16:39:31.816  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-15 16:39:31.817  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-15 16:39:31.817  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-15 16:39:31.817  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 16:39:31.817  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:31.817  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:31.817  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:31.818  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 16:39:31.818  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:31.818  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:31.818  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:31.818  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 16:39:31.818  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:31.818  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:31.818  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 16:39:31.819  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-15 16:39:31.819  5695  5742 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 16:39:31.819  5695  5742 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 16:39:31.822  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-15 16:39:31.823  5695  5742 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-15 16:39:31.824  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-15 16:39:31.824  5695  5742 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-15 16:39:31.825  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-15 16:39:31.825  5695  5742 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-15 16:39:31.825  5695  5742 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-15 16:39:31.825  5695  5742 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-15 16:39:31.825  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 16:39:31.825  5695  5742 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-15 16:39:31.826  5695  5742 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 16:39:31.826  5695  5742 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-15 16:39:31.826  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 16:39:31.826  5695  5742 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-15 16:39:31.826  5695  5742 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 16:39:31.826  5695  5742 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 16:39:31.826  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 16:39:31.826  5695  5742 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-15 16:39:31.827  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-15 16:39:31.827  5695  5742 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 16:39:31.827  5695  5742 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 16:39:31.827  5695  5742 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-15 16:39:31.827  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-15 16:39:31.827  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.827  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.827  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.827  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:31.827  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 16:39:31.827  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 16:39:31.828  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:31.829  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 16:39:31.829  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 16:39:31.829  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 16:39:31.829  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 16:39:31.829  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-15 16:39:31.829  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 16:39:31.829  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 16:39:31.829  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:31.829  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 16:39:31.830  5695  5756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 16:39:31.831  5695  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:31.829  4745  4745 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33008]" dev="sockfs" ino=33008 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:31.829  4745  4745 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33008]" dev="sockfs" ino=33008 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:31.833  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 16:39:31.833  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 16:39:31.833  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 16:39:31.833  5695  5756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 16:39:31.837  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.837  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 16:39:31.837  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 16:39:31.837  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:31.837  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-15 16:39:31.839  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.839  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.840  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 16:39:31.840  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 16:39:31.840  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:31.840  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-15 16:39:31.840  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 16:39:31.840  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.840  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.840  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 16:39:31.840  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:31.840  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.840  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.840  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.841  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:31.843  4731  4743 D BtGatt.GattService: registerClient() - UUID=6e27dcb8-43d4-406d-930f-7d3c16cd883a
11-15 16:39:31.843  4731  4793 D BtGatt.GattService: onClientRegistered() - UUID=6e27dcb8-43d4-406d-930f-7d3c16cd883a, clientIf=5
11-15 16:39:31.844  5695  5705 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 16:39:31.845  4731  4795 D BtGatt.AdvertiseManager: message : 0
,11-15 16:39:31.847  4731  4795 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 16:39:31.854  4731  4793 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 16:39:31.859  4731  4793 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 16:39:31.860  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.860  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.860  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 16:39:31.862  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 16:39:31.862  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.863  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.863  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:31.864  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:31.864  5695  5742 I io.jxcore.node.ConnectionHelper: start: OK
11-15 16:39:31.864  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.864  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.864  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-15 16:39:31.864  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.867  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.867  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 16:39:31.867  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.867  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.867  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:31.867  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 16:39:32.365  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 16:39:32.366  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 16:39:32.366  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 16:39:32.366  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-15 16:39:32.366  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 16:39:32.367  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 16:39:32.367  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 16:39:32.367  5695  5756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 16:39:32.367  5695  5756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 16:39:32.367  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 16:39:32.367  5695  5756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-15 16:39:32.368  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f990ec removed from the list
11-15 16:39:32.368  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 16:39:32.368  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 16:39:32.368  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 16:39:32.368  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 16:39:32.368  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 16:39:32.368  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 16:39:32.369  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:32.369  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 16:39:32.369  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:32.369  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.369  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.369  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.372  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:32.372  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 16:39:32.374  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:32.375  5695  5742 D BluetoothLeScanner: could not find callback wrapper
11-15 16:39:32.375  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-15 16:39:32.375  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.375  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.376  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.376  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 16:39:32.376  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.378  4731  4795 D BtGatt.AdvertiseManager: message : 1
11-15 16:39:32.379  4731  4795 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 16:39:32.396  4731  4793 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 16:39:32.396  4731  4793 D BtGatt.GattService: Client app is not null!
,11-15 16:39:32.398  4731  4949 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 16:39:32.399  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 16:39:32.399  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.399  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 16:39:32.399  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.399  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.400  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:32.400  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 16:39:32.400  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 16:39:32.401  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 16:39:32.401  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.403  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:32.403  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:32.403  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.403  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:32.403  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef2ccb5 removed from the list
,11-15 16:39:32.403  5695  5742 D io.jxcore.node.ConnectivityMonitor: stop
11-15 16:39:32.404  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 16:39:32.404  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:32.404  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 16:39:32.404  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:32.404  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:32.404  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 16:39:32.404  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 16:39:32.404  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-15 16:39:32.405  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 16:39:32.405  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 16:39:32.405  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:32.407  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:32.407  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 16:39:32.408  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:32.408  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:32.408  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 16:39:32.910  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 16:39:35.543   930  3054 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 16:39:37.408  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-15 16:39:37.410  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-15 16:39:37.411  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:37.411  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 16:39:37.420  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 16:39:37.421  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 16:39:37.421  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 16:39:37.421  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 16:39:37.421  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 16:39:37.422  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 16:39:37.422  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 16:39:37.422  5695  5757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 16:39:37.423  5695  5757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 16:39:37.425  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-15 16:39:37.427  5695  5742 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-15 16:39:37.428  5695  5742 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 16:39:37.428  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 16:39:37.428  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:37.428  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 16:39:37.430  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-15 16:39:37.430  5695  5757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 16:39:37.426  4949  4949 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[36180]" dev="sockfs" ino=36180 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:37.426  4949  4949 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[36180]" dev="sockfs" ino=36180 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:37.436  5695  5742 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-15 16:39:37.437  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 16:39:37.437  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 16:39:37.437  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 16:39:37.437  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 16:39:37.437  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 16:39:37.437  5695  5757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 16:39:37.438  5695  5757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 16:39:37.438  5695  5757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 16:39:37.438  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 16:39:37.438  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:37.438  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 16:39:37.438  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:37.438  5695  5742 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f990ec not in the list
11-15 16:39:37.438  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 16:39:37.439  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 16:39:37.439  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 16:39:37.439  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 16:39:37.439  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 16:39:37.439  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:37.440  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:37.440  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:37.441  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:37.441  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:37.441  5695  5742 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef2ccb5 not in the list
11-15 16:39:37.441  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:37.441  5695  5742 D io.jxcore.node.ConnectivityMonitor: stop
11-15 16:39:37.441  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:37.441  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:37.443  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-15 16:39:37.443  5695  5742 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-15 16:39:37.443  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 16:39:37.445  5695  5742 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-15 16:39:37.445  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 16:39:37.445  5695  5742 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-15 16:39:37.445  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 16:39:37.446  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-15 16:39:37.446  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-15 16:39:37.448  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-15 16:39:37.448  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 16:39:37.448  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-15 16:39:37.449  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-15 16:39:37.449  5695  5742 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-15 16:39:37.449  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 16:39:37.449  5695  5742 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-15 16:39:37.449  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-15 16:39:37.449  5695  5742 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-15 16:39:37.449  5695  5742 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-15 16:39:37.450  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-15 16:39:37.450  5695  5742 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-15 16:39:37.450  5695  5742 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-15 16:39:37.451  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-15 16:39:37.451  5695  5742 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-15 16:39:37.451  5695  5742 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-15 16:39:37.451  5695  5742 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-15 16:39:37.451  5695  5742 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-15 16:39:37.451  5695  5742 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-15 16:39:37.452  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 16:39:37.452  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166fcab added. We now have 3 listener(s)
11-15 16:39:37.453  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:37.454  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 16:39:37.454  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 16:39:37.454  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 16:39:37.454  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@117df08 added. We now have 3 listener(s)
,11-15 16:39:37.454  5695  5742 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 16:39:37.454  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 16:39:37.457  5695  5742 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 16:39:37.457   930  3906 D WifiService: setWifiEnabled: true pid=5695, uid=10077
11-15 16:39:37.457   930  3906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 16:39:37.459  5695  5742 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-15 16:39:37.462  5695  5742 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-15 16:39:37.463  5695  5742 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-15 16:39:37.466  5695  5742 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-15 16:39:37.466  5695  5742 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-15 16:39:37.472  4731  4789 D BluetoothAdapterState: Current state: ON, message: 23
11-15 16:39:37.472  4731  4789 D BluetoothAdapterProperties: Setting state to 13
11-15 16:39:37.472  4731  4789 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 16:39:37.473  5695  5742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 16:39:37.473  4731  4789 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 16:39:37.474  4731  4789 I BluetoothAdapterState: Entering PendingCommandState
11-15 16:39:37.474  5695  5742 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 16:39:37.474  5695  5742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 16:39:37.476  4731  4731 D BluetoothMapService: onReceive
,11-15 16:39:37.476  4731  4731 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 16:39:37.476  4731  4731 D BluetoothMapService: STATE_TURNING_OFF
11-15 16:39:37.476  4731  4731 D BluetoothMapService: MAP Service closeService in
11-15 16:39:37.476  4731  4731 D BluetoothMapMasInstance0: MAP Service shutdown
,11-15 16:39:37.476  4731  4731 D ObexServerSockets0: shutdown(block = true)
11-15 16:39:37.477  4731  4951 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-15 16:39:37.477  4731  4731 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 16:39:37.477  4731  4731 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-15 16:39:37.477  4731  4952 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 16:39:37.477  4731  4939 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 16:39:37.479  4731  4731 I BtOppRfcommListener: stopping Accept Thread
11-15 16:39:37.480  4731  5382 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-15 16:39:37.480  4731  5382 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-15 16:39:37.491   930   943 I ActivityManager: Start proc 5760:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-15 16:39:37.492  4731  4793 D BluetoothAdapterProperties: Scan Mode:20
,11-15 16:39:37.493  4731  4789 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-15 16:39:37.495  4731  4731 D HeadsetService: Received stop request...Stopping profile...
11-15 16:39:37.496  3225  4060 D BluetoothHeadset: Proxy object disconnected
11-15 16:39:37.497  4731  4731 V BluetoothAdapterState: isTurningOff()=true
,11-15 16:39:37.497  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.497  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.497  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:37.497  3866  4098 D BluetoothHeadset: Proxy object disconnected
11-15 16:39:37.497   930   930 D BluetoothHeadset: Proxy object disconnected
11-15 16:39:37.497   930   930 D BluetoothHeadset: Proxy object disconnected
11-15 16:39:37.498   930   930 D BluetoothHeadset: Proxy object disconnected
,11-15 16:39:37.500  4731  4731 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-15 16:39:37.500  4731  4731 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-15 16:39:37.500  4731  4793 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-15 16:39:37.500  4731  4902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 16:39:37.500  4731  4902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 16:39:37.500  4731  4902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 16:39:37.500  4731  4731 D A2dpService: Received stop request...Stopping profile...
11-15 16:39:37.500  4731  4793 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 16:39:37.501  4731  4944 D A2dpStateMachine: Exit Disconnected: -1
,11-15 16:39:37.502   930   930 D BluetoothA2dp: Proxy object disconnected
,11-15 16:39:37.503  4731  4731 D HidService: Received stop request...Stopping profile...
11-15 16:39:37.503  4731  4731 D HidService: Stopping Bluetooth HidService
11-15 16:39:37.504  3225  3225 D HeadsetProfile: Bluetooth service disconnected
11-15 16:39:37.504  3225  3225 D BluetoothA2dp: Proxy object disconnected
,11-15 16:39:37.504  3225  3225 D BluetoothInputDevice: Proxy object disconnected
11-15 16:39:37.504  3225  3225 D HidProfile: Bluetooth service disconnected
11-15 16:39:37.504  4731  4731 D HealthService: Received stop request...Stopping profile...
,11-15 16:39:37.505  4731  4731 D PanService: Received stop request...Stopping profile...
11-15 16:39:37.509  4731  4731 D BluetoothMapService: Received stop request...Stopping profile...
11-15 16:39:37.509  4731  4731 D BluetoothMapService: stop()
11-15 16:39:37.509  3225  3225 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 16:39:37.509  3225  3225 D PanProfile: Bluetooth service disconnected
,11-15 16:39:37.509  4731  4731 D BluetoothMapAppObserver: deinitObservers()
,11-15 16:39:37.509  4731  4731 D BluetoothMapAppObserver: removeReceiver()
11-15 16:39:37.511  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-15 16:39:37.511  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.511  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.511  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:37.511  3225  3225 D BluetoothMap: Proxy object disconnected
11-15 16:39:37.513  4731  4793 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-15 16:39:37.513  4731  4902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 16:39:37.513  3225  3225 D MapProfile: Bluetooth service disconnected
11-15 16:39:37.513  4731  4902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 16:39:37.513  4731  4731 D SapService: Received stop request...Stopping profile...
11-15 16:39:37.513  4731  4731 V SapService: stop()
11-15 16:39:37.513  4731  4902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 16:39:37.514  4731  4902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 16:39:37.514  4731  4902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 16:39:37.514  4731  4902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 16:39:37.515  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-15 16:39:37.515  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.515  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.515  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:37.516  4731  4731 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 16:39:37.516  4731  4731 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-15 16:39:37.516  4731  4793 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 16:39:37.516  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-15 16:39:37.516  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.516  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.516  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:37.517  4731  4731 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 16:39:37.517  4731  4793 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 16:39:37.517  4731  4731 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 16:39:37.518  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-15 16:39:37.518  4731  4731 V BluetoothAdapterState: isTurningOn()=false
,11-15 16:39:37.518  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.518  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:37.518  4731  4731 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 16:39:37.518  4731  4731 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 16:39:37.519  4731  4731 D BluetoothMapService: MAP Service closeService in
11-15 16:39:37.519  4731  4731 V BluetoothAdapterState: isTurningOff()=true
11-15 16:39:37.519  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.519  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.519  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:37.520  4731  4731 D BluetoothMapService: cleanup()
11-15 16:39:37.520  4731  4731 D BluetoothMapService: MAP Service closeService in
11-15 16:39:37.520  4731  4731 V BluetoothAdapterState: isTurningOff()=true
,11-15 16:39:37.520  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.520  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.520  4731  4731 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 16:39:37.530  4731  4789 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-15 16:39:37.530  4731  4789 D BluetoothAdapterProperties: Setting state to 15
11-15 16:39:37.531  4731  4789 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 16:39:37.531  4731  4789 I BluetoothAdapterState: Entering BleOnState
,11-15 16:39:37.532   930  3223 I ActivityManager: Killing 5490:com.android.chrome/u0a39 (adj 15): empty #17
,11-15 16:39:37.544   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 16:39:37.544  3225  3236 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 16:39:37.545  3225  3237 D BluetoothPan: onBluetoothStateChange on: false
,11-15 16:39:37.546   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 16:39:37.546  3225  4060 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 16:39:37.547  3225  3236 D BluetoothPbap: onBluetoothStateChange: up=false
,11-15 16:39:37.548  3866  3886 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 16:39:37.548   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 16:39:37.548   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 16:39:37.548  3225  3237 D BluetoothMap: onBluetoothStateChange: up=false
11-15 16:39:37.549  3225  4060 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 16:39:37.549  4731  4789 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 16:39:37.549  4731  4789 D BluetoothAdapterProperties: Setting state to 16
11-15 16:39:37.550  4731  4789 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 16:39:37.550  4731  4789 D BluetoothAdapterProperties: onBleDisable
11-15 16:39:37.550  4731  4789 I BluetoothAdapterState: Entering PendingCommandState
11-15 16:39:37.551  4731  4790 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 16:39:37.552  4731  4902 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 16:39:37.552  4731  4902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 16:39:37.552  4731  4793 D BluetoothAdapterProperties: Scan Mode:20
,11-15 16:39:37.560  5760  5760 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-15 16:39:37.575  5760  5760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 16:39:37.582   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7bc2b9:true
,11-15 16:39:37.583  3643  3643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 16:39:37.595   930  3829 I ActivityManager: Start proc 5772:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-15 16:39:37.602  5760  5760 D LocalBluetoothProfileManager: Adding local MAP profile
,11-15 16:39:37.604  5760  5760 D BluetoothMap: Create BluetoothMap proxy object
,11-15 16:39:37.613  5760  5760 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-15 16:39:37.619  5760  5760 D DockEventReceiver: finishStartingService: stopping service
,11-15 16:39:37.628   930  3658 I ActivityManager: Killing 4556:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-15 16:39:37.645  5772  5772 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-15 16:39:37.757  4731  4793 I bt_hci  : shut_down
,11-15 16:39:37.762  4731  4797 I bt_vendor: low_power_mode_cb
,11-15 16:39:37.763  4731  4797 D bt_hwcfg: hw_epilog_process
,11-15 16:39:37.765  4731  4797 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-15 16:39:37.765  4731  4797 I bt_vendor: epilog_cb
11-15 16:39:37.765  4731  4797 I bt_hci  : epilog_finished_callback
,11-15 16:39:37.767  4731  4793 I bt_hci_h4: hal_close
11-15 16:39:37.768  4731  4793 I bt_userial_vendor: device fd = 54 close
,11-15 16:39:37.828  5772  5772 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-15 16:39:37.828  5772  5772 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.828  5772  5772 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.828  5772  5772 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.828  5772  5772 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.k.d(PG:583)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.828  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.829  5772  5772 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.829  5772  5772 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.829  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.834  5772  5772 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 16:39:37.834  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 16:39:37.837  5760  5760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 16:39:37.842  3643  3643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 16:39:37.847  5760  5760 D DockEventReceiver: finishStartingService: stopping service
11-15 16:39:37.848   930   940 I ActivityManager: Killing 5198:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-15 16:39:37.883  4731  4790 D bt_stack_manager: event_shut_down_stack finished.
11-15 16:39:37.883  4731  4789 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-15 16:39:37.885  4731  4789 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-15 16:39:37.885  4731  4731 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 16:39:37.885  4731  4731 D BtGatt.GattService: Received stop request...Stopping profile...
11-15 16:39:37.886  4731  4731 D BtGatt.GattService: stop()
11-15 16:39:37.886  4731  4731 D BtGatt.AdvertiseManager: advertise clients cleared
11-15 16:39:37.887  4731  4731 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:37.887  4731  4731 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:37.887  4731  4731 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:37.887  4731  4731 V BluetoothAdapterState: isBleTurningOff()=true
11-15 16:39:37.887  4731  4789 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 16:39:37.887  4731  4789 D BluetoothAdapterProperties: Setting state to 10
11-15 16:39:37.888  4731  4789 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 16:39:37.888  4731  4789 I BluetoothAdapterState: Entering OffState
11-15 16:39:37.889   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-15 16:39:37.894  4731  4731 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-15 16:39:37.894  4731  4731 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 16:39:37.894  4731  4731 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 16:39:37.896  4731  4790 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-15 16:39:37.903  4731  4731 I art     : System.exit called, status: 0
11-15 16:39:37.903  4731  4731 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 16:39:37.942  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 16:39:37.943   930  3221 I ActivityManager: Process com.android.bluetooth (pid 4731) has died
,11-15 16:39:37.974  5695  5758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 16:39:37.974  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 16:39:37.974  5695  5758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 16:39:37.974  5695  5758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 16:39:37.979  5695  5742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 16:39:37.988   930   947 I ActivityManager: Start proc 5804:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 16:39:38.043  5772  5789 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-15 16:39:38.048  5804  5804 D AdapterServiceConfig: Adding HeadsetService
,11-15 16:39:38.049  5804  5804 D AdapterServiceConfig: Adding A2dpService
11-15 16:39:38.049  5804  5804 D AdapterServiceConfig: Adding HidService
11-15 16:39:38.049  5804  5804 D AdapterServiceConfig: Adding HealthService
,11-15 16:39:38.049  5804  5804 D AdapterServiceConfig: Adding PanService
11-15 16:39:38.050  5804  5804 D AdapterServiceConfig: Adding GattService
11-15 16:39:38.050  5804  5804 D AdapterServiceConfig: Adding BluetoothMapService
,11-15 16:39:38.050  5804  5804 D AdapterServiceConfig: Adding SapService
,11-15 16:39:38.056   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f167286:true
,11-15 16:39:38.062   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7f90e3:true
,11-15 16:39:38.062  5804  5804 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 16:39:38.064  5804  5804 I bt_bluedroid: init
,11-15 16:39:38.064  5804  5817 I BluetoothAdapterState: Entering OffState
,11-15 16:39:38.066  5804  5818 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 16:39:38.066  5804  5818 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 16:39:38.066  5804  5818 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 16:39:38.066  5804  5818 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-15 16:39:38.066  5804  5804 I bt_bluedroid: get_profile_interface socket
11-15 16:39:38.068  5804  5821 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 16:39:38.068  5804  5804 I bt_bluedroid: get_profile_interface sdp
11-15 16:39:38.069  5804  5821 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 16:39:38.072  5804  5815 I bt_bluedroid: config_hci_snoop_log
,11-15 16:39:38.073   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 16:39:38.076  5804  5817 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 16:39:38.077  5804  5817 D BluetoothAdapterProperties: Setting state to 14
11-15 16:39:38.077  5804  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-15 16:39:38.078  5804  5817 D BluetoothBondStateMachine: make
11-15 16:39:38.079  5804  5823 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 16:39:38.081  5804  5817 I BluetoothAdapterState: Entering PendingCommandState
,11-15 16:39:38.082  5804  5804 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 16:39:38.084  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
11-15 16:39:38.084  5804  5804 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 16:39:38.085  5804  5804 D BtGatt.GattService: Received start request. Starting profile...
11-15 16:39:38.085  5804  5804 D BtGatt.GattService: start()
11-15 16:39:38.085  5804  5804 I bt_bluedroid: get_profile_interface gatt
,11-15 16:39:38.086  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
,11-15 16:39:38.086  5804  5804 D BtGatt.AdvertiseManager: advertise manager created
,11-15 16:39:38.089  5804  5804 V BluetoothAdapterState: isTurningOff()=false
,11-15 16:39:38.090  5804  5804 V BluetoothAdapterState: isTurningOn()=false
11-15 16:39:38.090  5804  5804 V BluetoothAdapterState: isBleTurningOn()=true
11-15 16:39:38.090  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.090  5804  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 16:39:38.091  5804  5817 I bt_bluedroid: bt_bluedroid
11-15 16:39:38.091  5804  5818 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-15 16:39:38.091  5804  5818 I bt_hci  : start_up
,11-15 16:39:38.098  5804  5818 I bt_vendor: alloc value 0xf4253871
,11-15 16:39:38.098  5804  5818 I bt_vendor: init
11-15 16:39:38.098  5804  5818 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 16:39:38.098  5804  5818 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 16:39:38.209  5804  5818 D bt_hci  : start_up starting async portion
,11-15 16:39:38.209  5804  5826 I bt_hci  : event_finish_startup
11-15 16:39:38.209  5804  5826 I bt_hci_h4: hal_open
11-15 16:39:38.209  5804  5826 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 16:39:38.211  5804  5826 I bt_userial_vendor: device fd = 54 open
,11-15 16:39:38.206  5827  5827 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 16:39:38.224  5804  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 16:39:38.227  5804  5826 D bt_hwcfg: Chipset BCM4358A3
,11-15 16:39:38.227  5804  5826 D bt_hwcfg: Target name = [BCM4358A3]
11-15 16:39:38.227  5804  5826 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 16:39:38.483  5804  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-15 16:39:38.619  5804  5826 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-15 16:39:38.620  5804  5826 D bt_hwcfg: Settlement delay -- 100 ms
11-15 16:39:38.620  5804  5826 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 16:39:38.742  5804  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-15 16:39:38.743  5804  5826 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 16:39:38.744  5804  5826 I bt_hwcfg: vendor lib fwcfg completed
11-15 16:39:38.744  5804  5826 I bt_vendor: firmware callback
11-15 16:39:38.745  5804  5826 I bt_hci  : firmware_config_callback
,11-15 16:39:38.755  5804  5829 I bt_btu  : btu_task pending for preload complete event
,11-15 16:39:38.755  5804  5829 I bt_btu_task: Bluetooth chip preload is complete
11-15 16:39:38.755  5804  5829 I bt_btu  : btu_task received preload complete event
,11-15 16:39:38.763  5804  5829 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 16:39:38.763  5804  5829 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_AVRC
11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_A2D
11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_BTM
,11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 16:39:38.764  5804  5829 I         : BTE_InitTraceLevels -- TRC_PAN
11-15 16:39:38.765  5804  5829 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 16:39:38.765  5804  5829 I         : BTE_InitTraceLevels -- TRC_GATT
,11-15 16:39:38.765  5804  5829 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 16:39:38.765  5804  5829 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-15 16:39:38.765  5804  5829 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 16:39:38.851  5804  5829 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41d1549
,11-15 16:39:38.851  5804  5829 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41d1549 
,11-15 16:39:38.868  5804  5821 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
11-15 16:39:38.869  5804  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 16:39:38.870  5804  5821 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 16:39:38.872  5804  5821 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 16:39:38.875  5804  5821 D BluetoothAdapterProperties: Scan Mode:20
,11-15 16:39:38.876  5804  5821 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 16:39:38.876  5804  5821 D bt_hci  : do_postload posting postload work item
11-15 16:39:38.876  5804  5826 I bt_hci  : event_postload
,11-15 16:39:38.876  5804  5826 I bt_vendor: sco_config_cb
11-15 16:39:38.876  5804  5826 I bt_hci  : sco_config_callback postload finished.
,11-15 16:39:38.880  5804  5821 D bt_bte_conf: Device ID record 1 : primary
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   vendorId            = 000f
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   vendorIdSource      = 0001
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   product             = 1200
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   version             = 1436
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   clientExecutableURL = 
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   serviceDescription  = 
11-15 16:39:38.880  5804  5821 D bt_bte_conf:   documentationURL    = 
11-15 16:39:38.881  5804  5821 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 16:39:38.881  5804  5818 D bt_stack_manager: event_start_up_stack finished
11-15 16:39:38.882  5804  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 16:39:38.882  5804  5817 D BluetoothAdapterProperties: Setting state to 15
11-15 16:39:38.882  5804  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 16:39:38.882  5804  5826 I bt_vendor: low_power_mode_cb
11-15 16:39:38.883  5804  5817 I BluetoothAdapterState: Entering BleOnState
,11-15 16:39:38.887  5804  5817 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-15 16:39:38.887  5804  5817 D BluetoothAdapterProperties: Setting state to 11
11-15 16:39:38.888  5804  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-15 16:39:38.904  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
11-15 16:39:38.904  5804  5804 D HeadsetService: Received start request. Starting profile...
,11-15 16:39:38.907  5804  5804 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 16:39:38.907  5804  5804 D HeadsetStateMachine: make
,11-15 16:39:38.913  5804  5817 I BluetoothAdapterState: Entering PendingCommandState
,11-15 16:39:38.917  5804  5804 D HeadsetStateMachine: max_hf_connections = 1
,11-15 16:39:38.917  5804  5804 I bt_bluedroid: get_profile_interface handsfree
11-15 16:39:38.917  5804  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-15 16:39:38.918  5804  5821 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 16:39:38.922  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
,11-15 16:39:38.923  5804  5804 D A2dpService: Received start request. Starting profile...
,11-15 16:39:38.923  3643  3643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 16:39:38.923  5804  5804 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-15 16:39:38.924  5804  5804 I bt_bluedroid: get_profile_interface avrcp
,11-15 16:39:38.930  5804  5804 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 16:39:38.930  5804  5804 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 16:39:38.930  5804  5804 D A2dpStateMachine: make
,11-15 16:39:38.932  5804  5804 I bt_bluedroid: get_profile_interface a2dp
,11-15 16:39:38.933  5804  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-15 16:39:38.934  5804  5804 I BluetoothHidServiceJni: classInitNative: succeeds
11-15 16:39:38.936  5804  5837 D A2dpStateMachine: Enter Disconnected: -2
11-15 16:39:38.936  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
,11-15 16:39:38.937  5760  5760 D BluetoothInputDevice: Proxy object connected
,11-15 16:39:38.937  5804  5804 D HidService: Received start request. Starting profile...
11-15 16:39:38.938  5804  5804 I bt_bluedroid: get_profile_interface hidhost
11-15 16:39:38.938  5804  5804 D HidService: setHidService(): set to: null
11-15 16:39:38.938  5804  5821 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41b256d
11-15 16:39:38.938  5760  5760 D HidProfile: Bluetooth service connected
11-15 16:39:38.938  5804  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 16:39:38.938  5804  5804 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 16:39:38.939  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
11-15 16:39:38.939  5804  5804 D HealthService: Received start request. Starting profile...
11-15 16:39:38.940  5804  5804 I bt_bluedroid: get_profile_interface health
,11-15 16:39:38.941  5804  5804 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-15 16:39:38.942  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
11-15 16:39:38.943  5804  5804 D PanService: Received start request. Starting profile...
11-15 16:39:38.943  5804  5804 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 16:39:38.943  5804  5804 I bt_bluedroid: get_profile_interface pan
11-15 16:39:38.943  5804  5821 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-15 16:39:38.945  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
11-15 16:39:38.946  5804  5804 D BluetoothMapService: Received start request. Starting profile...
11-15 16:39:38.946  5804  5804 D BluetoothMapService: start()
11-15 16:39:38.948  5804  5804 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-15 16:39:38.946  5760  5760 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 16:39:38.949  5760  5760 D PanProfile: Bluetooth service connected
11-15 16:39:38.950  5760  5760 D BluetoothMap: Proxy object connected
11-15 16:39:38.950  5760  5760 D MapProfile: Bluetooth service connected
11-15 16:39:38.950  5760  5760 D BluetoothMap: getConnectedDevices()
11-15 16:39:38.951  5804  5804 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 16:39:38.951  5804  5804 D BluetoothMapAppObserver: createReceiver()
11-15 16:39:38.952  5804  5804 D BluetoothMapAppObserver: initObservers()
11-15 16:39:38.952  5804  5804 D BluetoothMapAppObserver: getEnabledAccountItems()
11-15 16:39:38.958  5804  5804 V SapService: SapBinder()
11-15 16:39:38.958  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
11-15 16:39:38.958  5804  5804 D SapService: Received start request. Starting profile...
11-15 16:39:38.958  5804  5804 V SapService: start()
,11-15 16:39:38.961  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.961  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.961  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.961  5804  5835 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-15 16:39:38.961  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.961  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.961  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.962  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.963  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.964  5804  5804 V BluetoothAdapterState: isTurningOff()=false
11-15 16:39:38.964  5804  5804 V BluetoothAdapterState: isTurningOn()=true
11-15 16:39:38.964  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
11-15 16:39:38.964  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
11-15 16:39:38.964  5804  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 16:39:38.964  5804  5817 D BluetoothAdapterProperties: ScanMode =  20
11-15 16:39:38.964  5804  5817 D BluetoothAdapterProperties: State =  11
11-15 16:39:38.967  5760  5760 D BluetoothMap: Bluetooth is Not enabled
11-15 16:39:38.967  5804  5821 D BluetoothAdapterProperties: Scan Mode:21
11-15 16:39:38.967  5804  5817 D BluetoothAdapterProperties: Setting state to 12
11-15 16:39:38.968  5804  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 16:39:38.968  5804  5821 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 16:39:38.968   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 16:39:38.968  5804  5817 I BluetoothAdapterState: Entering OnState
11-15 16:39:38.968  3225  3236 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 16:39:38.969  3225  3237 D BluetoothPan: onBluetoothStateChange on: true
11-15 16:39:38.970  3225  3225 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 16:39:38.970  3225  3225 D PanProfile: Bluetooth service connected
11-15 16:39:38.970   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 16:39:38.971  3225  3236 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 16:39:38.972   930   930 D BluetoothA2dp: Proxy object connected
11-15 16:39:38.973  3225  3225 D BluetoothInputDevice: Proxy object connected
11-15 16:39:38.973  3225  3225 D HidProfile: Bluetooth service connected
11-15 16:39:38.973  5760  5771 D BluetoothPan: onBluetoothStateChange on: true
11-15 16:39:38.973  3225  3237 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 16:39:38.975  3866  4098 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 16:39:38.975  5760  5770 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 16:39:38.976   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 16:39:38.976  5760  5771 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 16:39:38.977   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 16:39:38.977  3225  3236 D BluetoothMap: onBluetoothStateChange: up=true
11-15 16:39:38.977  5804  5804 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 16:39:38.978  5804  5804 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 16:39:38.978  3225  3225 D BluetoothMap: Proxy object connected
11-15 16:39:38.978  3225  4060 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 16:39:38.978  3225  3225 D MapProfile: Bluetooth service connected
11-15 16:39:38.978  3225  3225 D BluetoothMap: getConnectedDevices()
11-15 16:39:38.979  5804  5804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:38.980  5760  5770 D BluetoothMap: onBluetoothStateChange: up=true
11-15 16:39:38.980  3225  3225 D BluetoothA2dp: Proxy object connected
11-15 16:39:38.981   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 16:39:38.982  5804  5804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:38.984  5804  5804 D ObexServerSockets: Succeed to create listening sockets 
11-15 16:39:38.984  5804  5804 D ObexServerSockets0: startAccept()
11-15 16:39:38.984  5804  5804 D ObexServerSockets0: prepareForNewConnect()
11-15 16:39:38.984  5760  5760 D LocalBluetoothProfileManager: Adding local A2DP profile
11-15 16:39:38.986  5804  5804 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 16:39:38.986  5804  5843 D ObexServerSockets0: Accepting socket connection...
11-15 16:39:38.987  5804  5804 D BluetoothSdpJni: SDP Create record success - handle: 0
11-15 16:39:38.987  5804  5804 D BluetoothMapService: onReceive
11-15 16:39:38.987  5804  5804 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 16:39:38.987  5804  5804 D BluetoothMapService: STATE_ON
11-15 16:39:38.987  5804  5844 D ObexServerSockets0: Accepting socket connection...
11-15 16:39:38.988  5760  5760 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 16:39:38.988  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 16:39:38.990  5695  5758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 16:39:38.991  5695  5742 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-15 16:39:38.992   930   941 D WifiService: setWifiEnabled: false pid=5695, uid=10077
11-15 16:39:38.992   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 16:39:38.994   930  3054 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-15 16:39:38.994   930  3054 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 16:39:38.994   930  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 16:39:38.994  5804  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:38.994   930  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-15 16:39:38.995  5804  5845 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-15 16:39:38.995  5804  5845 D BluetoothSdpJni: SDP Create record success - handle: 1
11-15 16:39:38.996  5760  5760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 16:39:38.997  5695  5742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 16:39:38.999  5760  5760 D BluetoothA2dp: Proxy object connected
,11-15 16:39:39.004  3643  3643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 16:39:39.008  5760  5760 D DockEventReceiver: finishStartingService: stopping service
,11-15 16:39:39.009   930  5453 D DhcpClient: Clearing IP address
11-15 16:39:39.009   507   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 16:39:39.012  3225  3225 D BluetoothPbap: Proxy object connected
,11-15 16:39:39.012  3225  3225 D PbapServerProfile: Bluetooth service connected
11-15 16:39:39.012  5760  5760 D BluetoothPbap: Proxy object connected
11-15 16:39:39.012  5804  5804 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 16:39:39.012  5804  5804 D ObexServerSockets0: prepareForNewConnect()
11-15 16:39:39.012  5760  5760 D PbapServerProfile: Bluetooth service connected
,11-15 16:39:39.017   507   924 D CommandListener: Setting iface cfg
,11-15 16:39:39.018   930  5454 D DhcpClient: Receive thread stopped
11-15 16:39:39.020  5804  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 16:39:39.022  3643  5504 V NativeCrypto: Read error: ssl=0x7f8f88c000: I/O error during system call, Connection timed out
,11-15 16:39:39.023  3643  5504 V NativeCrypto: SSL shutdown failed: ssl=0x7f8f88c000: I/O error during system call, Broken pipe
11-15 16:39:39.027   930  3891 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-15 16:39:39.027   930  5451 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-15 16:39:39.031   930  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-15 16:39:39.031   930  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-15 16:39:39.034   533   533 E Parcel  : Reading a NULL string not supported here.
11-15 16:39:39.034   930  5451 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-15 16:39:39.037   930   930 D RttService: SCAN_AVAILABLE : 1
11-15 16:39:39.037   930  3164 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 16:39:39.038   930  3056 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-15 16:39:39.039  3832  3961 W QCNEJ   : |CORE| network lost: 100
11-15 16:39:39.040  3832  3961 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-15 16:39:39.043  5804  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:39.044  5804  5856 I BtOppRfcommListener: Accept thread started.
,11-15 16:39:39.056   930  3054 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-15 16:39:39.061   930  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-15 16:39:39.066   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 16:39:39.070  3225  3237 D BluetoothHeadset: Proxy object connected
,11-15 16:39:39.071  3225  3225 D HeadsetProfile: Bluetooth service connected
11-15 16:39:39.071  3866  4098 D BluetoothHeadset: Proxy object connected
11-15 16:39:39.071   930   930 D BluetoothHeadset: Proxy object connected
11-15 16:39:39.071   930   930 D BluetoothHeadset: Proxy object connected
11-15 16:39:39.071   930   930 D BluetoothHeadset: Proxy object connected
,11-15 16:39:39.076  3866  3886 D BluetoothHeadset: Proxy object connected
,11-15 16:39:39.076   930   947 D BluetoothHeadset: Proxy object connected
11-15 16:39:39.076   930   947 D BluetoothHeadset: Proxy object connected
,11-15 16:39:39.082   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 16:39:39.083   507   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 16:39:39.083   507   924 D TetherController: Setting IP forward enable = 0
11-15 16:39:39.084   930  3056 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-15 16:39:39.084   930  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 16:39:39.085   930  3054 D DhcpClient: doQuit
,11-15 16:39:39.085   930  3054 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 16:39:39.086   930  5453 D DhcpClient: onQuitting
,11-15 16:39:39.087  3532  3532 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-15 16:39:39.089   930   947 D Tethering: MasterInitialState.processMessage what=3
11-15 16:39:39.090  5760  5770 D BluetoothHeadset: Proxy object connected
11-15 16:39:39.093  5760  5760 D HeadsetProfile: Bluetooth service connected
,11-15 16:39:39.095  4049  4049 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-15 16:39:39.097  5333  5333 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7c61846 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-15 16:39:39.099  3940  3940 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-15 16:39:39.101  5123  5141 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-15 16:39:39.101  5123  5141 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 16:39:39.101  5123  5141 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-15 16:39:39.101  5123  5141 E SarControlService: no key has been found,reset the power
11-15 16:39:39.101  5123  5160 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 16:39:39.101  5123  5160 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 16:39:39.101  5123  5160 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 16:39:39.102  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 16:39:39.102  5148  5148 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 16:39:39.105  5123  5160 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 16:39:39.105  5123  5160 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 16:39:39.105  3532  3532 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-15 16:39:39.105  5123  5160 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-15 16:39:39.105  5148  5162 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f2577dc HexData = [00000000ea03000000000000ffffffff]
11-15 16:39:39.106  5148  5162 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 16:39:39.106  5148  5162 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-15 16:39:39.106  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 16:39:39.106  5148  5148 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-15 16:39:39.110  3532  3532 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-15 16:39:39.111  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 16:39:39.111  5123  5134 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 16:39:39.112   507   917 W SocketClient: write error (Broken pipe)
11-15 16:39:39.112   507   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-15 16:39:39.112   507   917 W SocketListener: Error sending broadcast (Broken pipe)
11-15 16:39:39.113  3940  3940 D SystemUpdateService: onCreate
11-15 16:39:39.114  5148  5162 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f2577dc HexData = [00000000eb03000000000000ffffffff]
,11-15 16:39:39.114  5148  5162 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 16:39:39.114  5148  5162 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-15 16:39:39.115  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 16:39:39.115  5123  5133 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 16:39:39.119  3940  3940 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 16:39:39.126  3940  5872 I SystemUpdateService: active receiver: enabled
,11-15 16:39:39.128  3940  3940 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-15 16:39:39.133  3940  5475 I iu.UploadsManager: num queued entries: 0
,11-15 16:39:39.133  3940  5475 I iu.UploadsManager: num updated entries: 0
11-15 16:39:39.134  3940  5475 I iu.SyncManager: NEXT; no task
,11-15 16:39:39.135   507   924 E Netd    : netlink response contains error (No such file or directory)
,11-15 16:39:39.136   507   924 D TetherController: Setting IP forward enable = 0
11-15 16:39:39.137   930  3056 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-15 16:39:39.137   930  3056 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-15 16:39:39.138  3940  3940 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 16:39:39.139  3940  3940 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-15 16:39:39.141  3532  3532 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-15 16:39:39.141  3940  5872 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-15 16:39:39.143  3940  5872 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-15 16:39:39.143  3940  5872 I SystemUpdateService: now status is 0 (complete)
11-15 16:39:39.143  3940  5872 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 16:39:39.143  3940  5872 I SystemUpdateService: file has been verified
11-15 16:39:39.143  3940  5872 I SystemUpdateService: OTA package size = 21989297
,11-15 16:39:39.148  3940  5872 I SystemUpdateService: showing system update notification
,11-15 16:39:39.153   930  3658 I ActivityManager: Start proc 5877:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-15 16:39:39.156  3532  3532 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 16:39:39.165   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 16:39:39.167  3940  3940 D SystemUpdateService: onDestroy
,11-15 16:39:39.186  5877  5877 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-15 16:39:39.189  5877  5877 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 16:39:39.195  5877  5877 D SprintDMHelper: simOperator: 
,11-15 16:39:39.195  5877  5877 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 16:39:39.207   930  3862 I ActivityManager: Start proc 5889:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-15 16:39:39.208   930  3862 I ActivityManager: Killing 5524:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-15 16:39:39.259  5064  5064 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 16:39:39.259   930  3054 D wifi    : In wifi stop Hal
,11-15 16:39:39.259   930  3054 D wifi    : halHandle = 0x7f79536680, mVM = 0x7f95b0d140, mCls = 0x100a02
11-15 16:39:39.259   930  3531 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 16:39:39.259   930  3531 D WifiHAL : Got a signal to exit!!!
,11-15 16:39:39.259   930  3531 I WifiHAL : Exit wifi_event_loop
11-15 16:39:39.260   930  3054 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-15 16:39:39.260   930  3054 E WifiHAL : Event processing terminated
11-15 16:39:39.260   930  3054 D wifi    : In wifi cleaned up handler
,11-15 16:39:39.260   930  3054 I WifiHAL : Internal cleanup completed
11-15 16:39:39.261  4135  4302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 16:39:39.282   930  3531 D wifi    : set interface wlan0 flags (DOWN)
11-15 16:39:39.282   930  3054 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 16:39:39.294  5064  5903 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-15 16:39:39.307   930  3658 I ActivityManager: Start proc 5904:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-15 16:39:39.309   930  3915 I ActivityManager: Killing 5333:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-15 16:39:39.348  5904  5904 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-15 16:39:39.356   930  3846 I ActivityManager: Killing 3976:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-15 16:39:39.490   930   947 D Tethering: InitialState.processMessage what=4
,11-15 16:39:39.498   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 16:39:39.504  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 16:39:39.509  5695  5758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 16:39:39.512   930  3221 D WifiService: setWifiEnabled: true pid=5695, uid=10077
,11-15 16:39:39.513   930  3221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 16:39:39.514  5695  5742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 16:39:39.519   507   924 D SoftapController: Softap fwReload - Ok
,11-15 16:39:39.522   507   924 D CommandListener: Setting iface cfg
,11-15 16:39:39.522   507   924 D CommandListener: Trying to bring down wlan0
,11-15 16:39:39.523   507   924 D CommandListener: Clearing all IP addresses on wlan0
,11-15 16:39:39.527   930  3054 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 16:39:40.018   930   941 D WifiService: setWifiEnabled: true pid=5695, uid=10077
,11-15 16:39:40.018   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 16:39:40.139   930  3054 D wifi    : set interface wlan0 flags (UP)
11-15 16:39:40.139   930  3054 I WifiHAL : Initializing wifi
11-15 16:39:40.140   930  3054 I WifiHAL : Creating socket
,11-15 16:39:40.146   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-15 16:39:40.148   930  3054 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 16:39:40.148   930  3054 D wifi    : Did set static halHandle = 0x7f79536680
11-15 16:39:40.149   930  3054 D wifi    : halHandle = 0x7f79536680, mVM = 0x7f95b0d140, mCls = 0x101876
11-15 16:39:40.149   930  3054 D wifi    : array field set
11-15 16:39:40.149   930  3054 I WifiNative-HAL: interface[0] = wlan0
11-15 16:39:40.151   930  5920 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547496355456
11-15 16:39:40.151   930  5920 D wifi    : waitForHalEvents called, vm = 0x7f95b0d140, obj = 0x101876, env = 0x7f7aa7df00
,11-15 16:39:40.155   930  3054 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 16:39:40.157   930  3054 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-15 16:39:40.208  5921  5921 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 16:39:40.270  5921  5921 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 16:39:40.325  5921  5921 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-15 16:39:40.325  5921  5921 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 16:39:40.522   930  3906 D WifiService: setWifiEnabled: true pid=5695, uid=10077
,11-15 16:39:40.522   930  3906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 16:39:41.025   930  3846 D WifiService: setWifiEnabled: true pid=5695, uid=10077
,11-15 16:39:41.026   930  3846 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 16:39:41.167   930  3054 D WifiConfigStore: Loading config and enabling all networks 
,11-15 16:39:41.203   930  3054 D WifiConfigStore: loaded 0 passpoint configs
,11-15 16:39:41.204   930  3054 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 16:39:41.205   930  3054 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-15 16:39:41.206   930  3054 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-15 16:39:41.206   930  3054 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-15 16:39:41.207   930  3054 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-15 16:39:41.208   930  3054 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-15 16:39:41.209   930  3054 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-15 16:39:41.209   930  3054 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 16:39:41.209   930  3054 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-15 16:39:41.210   930  3054 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 16:39:41.210   930  3054 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-15 16:39:41.210   930  3054 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 16:39:41.213   930  3054 D WifiNative-HAL: Setting external_sim to 1
11-15 16:39:41.214   930  3054 D wifi    : setting dfs flag to true, 0x7f7f13c140
11-15 16:39:41.214  5064  5064 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 16:39:41.214   930  3054 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 16:39:41.215   930  3054 D wifi    : setting scan oui 0x7f7f13c140
11-15 16:39:41.215   930  3054 D WifiHAL : Sending mac address OUI
,11-15 16:39:41.219   930  3054 E native  : do suspend false
,11-15 16:39:41.225   930  3054 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-15 16:39:41.225   507   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-15 16:39:41.225   930   930 D RttService: SCAN_AVAILABLE : 3
11-15 16:39:41.226   930  3164 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-15 16:39:41.227   507   924 D CommandListener: Setting iface cfg
,11-15 16:39:41.231   930  3053 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-15 16:39:41.231   930  3053 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 16:39:41.241   930  3053 D WifiNative-HAL: p2pGetDeviceAddress
,11-15 16:39:41.241   930  3053 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 16:39:41.246   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=107294 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 16:39:41.536  5695  5758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 16:39:41.544  5695  5758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 16:39:41.547  5695  5742 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 16:39:41.548   930  3658 D WifiService: setWifiEnabled: true pid=5695, uid=10077
11-15 16:39:41.548   930  3658 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 16:39:41.549  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 16:39:41.549  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:41.549  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-15 16:39:41.550  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166fcab removed from the list
11-15 16:39:41.550  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 16:39:41.550  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@117df08 removed from the list
11-15 16:39:41.550  5695  5742 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 16:39:41.554  5695  5742 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-15 16:39:41.557  5695  5742 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-15 16:39:41.559  5695  5742 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-15 16:39:41.562  5695  5742 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-15 16:39:41.565  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-15 16:39:41.567  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-15 16:39:41.568  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-15 16:39:41.568  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-15 16:39:41.570  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-15 16:39:41.573  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-15 16:39:41.574  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@725f5e0 Bundle[{}]
,11-15 16:39:41.575  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-15 16:39:41.575  5695  5742 I io.jxcore.node.LifeCycleMonitor: start: OK
11-15 16:39:41.576  5695  5742 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-15 16:39:41.577  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-15 16:39:41.578  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-15 16:39:41.579  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-15 16:39:41.579  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-15 16:39:41.580  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-15 16:39:41.581  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-15 16:39:41.582  5695  5742 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-15 16:39:41.583  5695  5742 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-15 16:39:41.586  5695  5742 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-15 16:39:41.588  5695  5742 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-15 16:39:41.590  5695  5742 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-15 16:39:41.591  5695  5742 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-15 16:39:41.592  5695  5742 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-15 16:39:41.592  5695  5742 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-15 16:39:41.595  5695  5742 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-15 16:39:41.597  5695  5742 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-15 16:39:41.598  5695  5742 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-15 16:39:41.600  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-15 16:39:41.602  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-15 16:39:41.603  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-15 16:39:41.603  5695  5742 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-15 16:39:41.604  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-15 16:39:41.604  5695  5742 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-15 16:39:41.604  5695  5742 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-15 16:39:41.604  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-15 16:39:41.605  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-15 16:39:41.606  5695  5742 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-15 16:39:41.606  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 16:39:41.607  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e160c6 added. We now have 3 listener(s)
,11-15 16:39:41.609  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 16:39:41.609  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 16:39:41.609  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 16:39:41.610  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 16:39:41.610  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b96b887 added. We now have 3 listener(s)
11-15 16:39:41.610  5695  5742 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 16:39:41.611  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 16:39:41.617  5695  5742 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-15 16:39:41.617  5695  5742 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-15 16:39:41.618  5695  5742 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-15 16:39:41.618  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-15 16:39:41.618  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.618  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.618  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.618  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 16:39:41.618  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 16:39:41.619  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 16:39:41.619  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:41.619  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 16:39:41.622  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 16:39:41.623  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 16:39:41.623  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 16:39:41.623  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 16:39:41.623  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 16:39:41.623  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 16:39:41.623  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:41.623  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-15 16:39:41.623  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 16:39:41.623  5695  5924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 16:39:41.625  5695  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:41.622  5834  5834 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32243]" dev="sockfs" ino=32243 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:41.622  5834  5834 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32243]" dev="sockfs" ino=32243 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 16:39:41.628  5695  5924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 16:39:41.628  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 16:39:41.628  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 16:39:41.628  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 16:39:41.632  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:41.632  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 16:39:41.633  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-15 16:39:41.633  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:41.633  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-15 16:39:41.635  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.635  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.635  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 16:39:41.635  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 16:39:41.635  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:41.635  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-15 16:39:41.635  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:41.635  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:41.635  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.635  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 16:39:41.636  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:41.636  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.636  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:41.636  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.636  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:41.639  5804  5834 D BtGatt.GattService: registerClient() - UUID=f7bb37b0-91a3-4f29-aa52-ed0e1eeb51fe
11-15 16:39:41.640  5804  5821 D BtGatt.GattService: onClientRegistered() - UUID=f7bb37b0-91a3-4f29-aa52-ed0e1eeb51fe, clientIf=5
11-15 16:39:41.641  5695  5706 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 16:39:41.643  5804  5824 D BtGatt.AdvertiseManager: message : 0
,11-15 16:39:41.645  5804  5824 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 16:39:41.654  5804  5821 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 16:39:41.660  5804  5821 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 16:39:41.660  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.660  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:41.660  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 16:39:41.660  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.661  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.661  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.661  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.661  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.661  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 16:39:41.662  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 16:39:41.662  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.663  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.663  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:41.663  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:41.663  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:41.663  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.663  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:41.663  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.664  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.664  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 16:39:41.664  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 16:39:41.667  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.667  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 16:39:41.667  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 16:39:41.667  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.667  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:41.667  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 16:39:42.168  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-15 16:39:42.168  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 16:39:42.168  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 16:39:43.657  3940  5928 I EventLogService: Aggregate from 1479222551539 (log), 1479222551539 (data)
,11-15 16:39:44.338  5921  5921 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 16:39:44.342  5921  5921 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 16:39:44.349  5921  5921 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 16:39:44.355  5921  5921 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 16:39:44.393   930  3054 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-15 16:39:44.394   930  3054 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-15 16:39:44.394   930  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 16:39:44.404   930  3054 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 16:39:44.436   930  3054 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 16:39:44.441  5921  5921 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 16:39:44.881  5921  5921 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 16:39:44.933  5921  5921 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 16:39:44.933  5921  5921 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 16:39:44.943   930  3054 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 16:39:44.944   930  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-15 16:39:44.944   930  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 16:39:44.961   930  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 16:39:44.974   507   924 D CommandListener: Setting iface cfg
,11-15 16:39:44.979   930  3054 D WifiStateMachine: Start Dhcp Watchdog 2
,11-15 16:39:44.985   930  5933 D DhcpClient: Receive thread started
,11-15 16:39:44.990   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 16:39:44.990   930  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-15 16:39:44.990   930  3056 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-15 16:39:45.070   930  3054 E native  : do suspend false
,11-15 16:39:45.084   930  5932 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 16:39:45.099   930  5933 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172730, domain null
,11-15 16:39:45.100   930  5932 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172730 seconds
,11-15 16:39:45.102   930  5932 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 16:39:45.118   930  5933 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-15 16:39:45.119   930  5932 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-15 16:39:45.121   507   924 D CommandListener: Setting iface cfg
,11-15 16:39:45.126   930  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 16:39:45.132   930  5932 D DhcpClient: Scheduling renewal in 86399s
,11-15 16:39:45.140   930  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-15 16:39:45.142   930  3054 D WifiConfigStore: No blacklist allowed without epno enabled
11-15 16:39:45.143   930  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-15 16:39:45.145   930  3056 D ConnectivityService: Adding iface wlan0 to network 101
,11-15 16:39:45.161   930  3054 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-15 16:39:45.165  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-15 16:39:45.165  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 16:39:45.165  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 16:39:45.165  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 16:39:45.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 16:39:45.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 16:39:45.166  5695  5924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 16:39:45.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 16:39:45.166  5695  5924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 16:39:45.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 16:39:45.166  5695  5924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 16:39:45.166  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 16:39:45.166  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-15 16:39:45.166  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 16:39:45.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 16:39:45.166  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 16:39:45.167  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:45.167  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.167  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.167  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.168  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:45.168  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 16:39:45.169  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:45.169  5695  5742 D BluetoothLeScanner: could not find callback wrapper
,11-15 16:39:45.169  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 16:39:45.170  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:45.170  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.170  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.170  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 16:39:45.170  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.171  5804  5824 D BtGatt.AdvertiseManager: message : 1
11-15 16:39:45.172  5804  5824 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 16:39:45.183  5804  5821 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 16:39:45.183  5804  5821 D BtGatt.GattService: Client app is not null!
,11-15 16:39:45.184  5804  5814 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 16:39:45.185  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 16:39:45.185  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.186  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 16:39:45.186  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.186  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.186  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.186  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-15 16:39:45.186  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 16:39:45.187  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 16:39:45.187  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.189  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.189  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:45.189  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:45.189  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.190  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 16:39:45.190  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 16:39:45.190  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-15 16:39:45.190  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 16:39:45.190  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:45.190  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:45.190  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-15 16:39:45.191  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.191  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 16:39:45.191  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 16:39:45.191  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.191  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.191  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 16:39:45.191  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 16:39:45.193  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.193  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.193  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.193  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.193  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 16:39:45.195  5695  5742 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-15 16:39:45.195  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 16:39:45.196  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 16:39:45.196  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 16:39:45.196  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 16:39:45.196  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:45.197  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 16:39:45.198   930  3056 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-15 16:39:45.198   930  3056 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-15 16:39:45.198  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 16:39:45.202   930  3056 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-15 16:39:45.203  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 16:39:45.203  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 16:39:45.203   930  3056 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-15 16:39:45.203  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 16:39:45.206   930  3056 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-15 16:39:45.208  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.208  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 16:39:45.209  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 16:39:45.209  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:45.209  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-15 16:39:45.213  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-15 16:39:45.214   930  3056 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-15 16:39:45.216  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-15 16:39:45.216  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.217  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 16:39:45.217  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-15 16:39:45.217  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-15 16:39:45.217  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 16:39:45.218  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.218  5695  5742 D BluetoothAdapter: STATE_ON
,11-15 16:39:45.218   930  3056 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-15 16:39:45.219   930  3056 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-15 16:39:45.219   930  3056 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-15 16:39:45.219   930  3056 D ConnectivityService:    accepting network in place of null
11-15 16:39:45.219   930  3054 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-15 16:39:45.219   930  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 16:39:45.219   930  3056 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-15 16:39:45.221  5804  5834 D BtGatt.GattService: registerClient() - UUID=2ddfd52b-a807-4ac2-af13-f98ba2f3a32e
,11-15 16:39:45.223  5804  5821 D BtGatt.GattService: onClientRegistered() - UUID=2ddfd52b-a807-4ac2-af13-f98ba2f3a32e, clientIf=5
11-15 16:39:45.223  5695  5706 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 16:39:45.224  5804  5814 D BtGatt.GattService: start scan with filters
,11-15 16:39:45.228  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-15 16:39:45.228  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.228  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 16:39:45.228  5804  5825 D BtGatt.ScanManager: handling starting scan
11-15 16:39:45.228  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.228  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 16:39:45.228  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:45.229  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.229  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 16:39:45.229  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-15 16:39:45.229  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.229  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.229  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 16:39:45.229  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 16:39:45.230  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.230  5804  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@71fa79d
,11-15 16:39:45.234  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:45.234  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 16:39:45.235  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.235  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:45.235  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.235  5804  5821 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 16:39:45.235  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:45.236  5804  5825 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 16:39:45.237  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.237  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 16:39:45.237  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.237  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:45.237  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 16:39:45.238   930  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=111285, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 16:39:45.240  5804  5821 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 16:39:45.240  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:45.241  5804  5825 D BtGatt.ScanManager: Starting BLE batch scan
11-15 16:39:45.241  5804  5825 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-15 16:39:45.243   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 16:39:45.249  5804  5821 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 16:39:45.249  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:45.254  5804  5821 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 16:39:45.254  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:45.263   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 16:39:45.266   930  3056 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-15 16:39:45.266   930  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-15 16:39:45.266  3832  3961 W QCNEJ   : |CORE| network available: 101
11-15 16:39:45.267   930  3056 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-15 16:39:45.269   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-15 16:39:45.274  3832  3961 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-15 16:39:45.275  3832  3961 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-15 16:39:45.275  3832  3961 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-15 16:39:45.276  4049  4049 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 16:39:45.280  3940  3940 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 16:39:45.283  3940  3940 D SystemUpdateService: onCreate
,11-15 16:39:45.286  3940  3940 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-15 16:39:45.288  5123  5141 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-15 16:39:45.288  5123  5141 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 16:39:45.288  5123  5141 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-15 16:39:45.288  5123  5141 E SarControlService: no key has been found,reset the power
11-15 16:39:45.288  5123  5160 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 16:39:45.289  5123  5160 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-15 16:39:45.289  5123  5160 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 16:39:45.289  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 16:39:45.289  5148  5148 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-15 16:39:45.290  5123  5160 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-15 16:39:45.290  5123  5160 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 16:39:45.291  5123  5160 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 16:39:45.291  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 16:39:45.291  5148  5148 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-15 16:39:45.295  5148  5162 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f2577dc HexData = [00000000ec03000000000000ffffffff]
11-15 16:39:45.296  5148  5162 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-15 16:39:45.296  5148  5162 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-15 16:39:45.296  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 16:39:45.296  5123  5134 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 16:39:45.297  5148  5162 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f2577dc HexData = [00000000ed03000000000000ffffffff]
11-15 16:39:45.297  5148  5162 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 16:39:45.297  5148  5162 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-15 16:39:45.297  5148  5148 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 16:39:45.297  5123  5133 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 16:39:45.303  3940  3940 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 16:39:45.309  3940  5475 I iu.UploadsManager: num queued entries: 0
,11-15 16:39:45.309  3940  5475 I iu.UploadsManager: num updated entries: 0
,11-15 16:39:45.310  3940  5475 I iu.SyncManager: NEXT; no task
,11-15 16:39:45.311  3940  3940 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 16:39:45.313  3940  3940 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 16:39:45.315  5877  5877 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 16:39:45.318  5877  5877 D SprintDMHelper: simOperator: 
11-15 16:39:45.319  5877  5877 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 16:39:45.329  3940  5944 I SystemUpdateService: active receiver: enabled
,11-15 16:39:45.350  3940  5944 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 16:39:45.358   930  5930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
,11-15 16:39:45.362  3940  5944 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-15 16:39:45.362  3940  5944 I SystemUpdateService: now status is 0 (complete)
11-15 16:39:45.362  3940  5944 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 16:39:45.362  3940  5944 I SystemUpdateService: file has been verified
11-15 16:39:45.363  3940  5944 I SystemUpdateService: OTA package size = 21989297
,11-15 16:39:45.369  3940  5944 I SystemUpdateService: showing system update notification
,11-15 16:39:45.379   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 16:39:45.380  3940  3940 D SystemUpdateService: onDestroy
,11-15 16:39:45.407   930  5930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 15:39:45 GMT], X-Android-Received-Millis=[1479224385406], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479224385381]}
,11-15 16:39:45.407   930  3056 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-15 16:39:45.408   930  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-15 16:39:45.408   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-15 16:39:45.409   930  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 16:39:45.450  5064  5948 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-15 16:39:45.738  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 16:39:45.738  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 16:39:45.738  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 16:39:45.758  5804  5804 D BtGatt.ScanManager: awakened up at time 111805
,11-15 16:39:45.760  5804  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 16:39:45.776  5804  5821 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-15 16:39:45.776  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:45.778  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-15 16:39:46.267   930  3056 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-15 16:39:46.915   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 16:39:46.916   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 16:39:48.237  5695  5742 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-15 16:39:48.237  5695  5742 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-15 16:39:48.237  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-15 16:39:48.238  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.238  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.239  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 16:39:48.239  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.240  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-15 16:39:48.241  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.241  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.242  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 16:39:48.242  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 16:39:48.243  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.243  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.243  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.244  5695  5742 D BluetoothAdapter: STATE_ON
,11-15 16:39:48.245  5804  5815 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 16:39:48.246  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-15 16:39:48.248  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:48.249  5804  5834 D BtGatt.GattService: stopScan() - queue size =1
,11-15 16:39:48.251  5804  5814 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 16:39:48.252  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 16:39:48.252  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.252  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 16:39:48.252  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.253  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 16:39:48.253  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.253  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.253  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 16:39:48.253  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 16:39:48.253  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 16:39:48.253  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 16:39:48.254  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.251  5804  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 16:39:48.255  5695  5742 D BluetoothAdapter: STATE_ON
,11-15 16:39:48.258  5804  5814 D BtGatt.GattService: registerClient() - UUID=e2196091-5e00-4879-b0a1-db136967a010
,11-15 16:39:48.260  5804  5821 D BtGatt.GattService: onClientRegistered() - UUID=e2196091-5e00-4879-b0a1-db136967a010, clientIf=5
11-15 16:39:48.260  5804  5804 D BtGatt.ScanManager: awakened up at time 114308
,11-15 16:39:48.260  5695  5706 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 16:39:48.261  5804  5842 D BtGatt.GattService: start scan with filters
,11-15 16:39:48.264  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 16:39:48.264  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.265  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 16:39:48.265  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.265  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.265  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:48.265  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:48.265  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.265  5695  5742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-15 16:39:48.265  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 16:39:48.265  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 16:39:48.265  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 16:39:48.265  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 16:39:48.266  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.266  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.267  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 16:39:48.267  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 16:39:48.267  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 16:39:48.267  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 16:39:48.267  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 16:39:48.267  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 16:39:48.267  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-15 16:39:48.267  5695  5956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 16:39:48.268  5695  5956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 16:39:48.269  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 16:39:48.269  5695  5742 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 16:39:48.272  5695  5956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 16:39:48.266  5815  5815 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33184]" dev="sockfs" ino=33184 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:48.272  5804  5821 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-15 16:39:48.272  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:48.266  5815  5815 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33184]" dev="sockfs" ino=33184 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 16:39:48.272  5804  5821 D BtGatt.GattService: current time is 114320074251
11-15 16:39:48.272  5804  5821 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -77, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 16:39:48.274  5804  5821 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 16:39:48.274  5804  5821 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 16:39:48.278  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.279  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.279  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.279  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 16:39:48.279  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 16:39:48.279  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 16:39:48.279  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-15 16:39:48.279  5695  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:48.279  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 16:39:48.279  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.279  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-15 16:39:48.279  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 16:39:48.280  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.280  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.280  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.280  5804  5821 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 16:39:48.280  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:48.280  5804  5825 D BtGatt.ScanManager: stopping BLe Batch
11-15 16:39:48.281  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:48.284  5804  5834 D BtGatt.GattService: registerClient() - UUID=21e83bb7-dbac-430a-b4d7-70bd74d032cd
,11-15 16:39:48.284  5804  5821 D BtGatt.GattService: onClientRegistered() - UUID=21e83bb7-dbac-430a-b4d7-70bd74d032cd, clientIf=6
11-15 16:39:48.285  5695  5705 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-15 16:39:48.286  5804  5824 D BtGatt.AdvertiseManager: message : 0
,11-15 16:39:48.287  5804  5821 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 16:39:48.287  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:48.287  5804  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 16:39:48.289  5804  5824 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 16:39:48.293  5804  5821 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-15 16:39:48.293  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:48.295  5804  5825 D BtGatt.ScanManager: handling starting scan
,11-15 16:39:48.302  5804  5821 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-15 16:39:48.306  5804  5821 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-15 16:39:48.306  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:48.307  5804  5825 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 16:39:48.311  5804  5821 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-15 16:39:48.312  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.312  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.313  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-15 16:39:48.313  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-15 16:39:48.313  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 16:39:48.314  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 16:39:48.314  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.316  5804  5821 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 16:39:48.316  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:48.316  5804  5825 D BtGatt.ScanManager: Starting BLE batch scan
11-15 16:39:48.317  5804  5825 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-15 16:39:48.317  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.317  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:48.317  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:48.317  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.317  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-15 16:39:48.317  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 16:39:48.318  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.318  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.318  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-15 16:39:48.318  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.320  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.320  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-15 16:39:48.320  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.320  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.320  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:48.320  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-15 16:39:48.326  5804  5821 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 16:39:48.326  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:48.330  5804  5821 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 16:39:48.330  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:48.821  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-15 16:39:48.821  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-15 16:39:48.822  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 16:39:51.320  5695  5742 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-15 16:39:51.321  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 16:39:51.321  5695  5742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 16:39:51.321  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 16:39:51.321  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 16:39:51.322  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-15 16:39:51.322  5695  5956 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 16:39:51.322  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 16:39:51.322  5695  5956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 16:39:51.322  5695  5742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 16:39:51.323  5695  5956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 16:39:51.323  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 16:39:51.323  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 16:39:51.323  5695  5742 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e160c6 removed from the list
,11-15 16:39:51.323  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 16:39:51.323  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 16:39:51.323  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 16:39:51.323  5695  5742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 16:39:51.323  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 16:39:51.324  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 16:39:51.326  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.326  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:51.326  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.326  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 16:39:51.327  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.329  5695  5742 D BluetoothAdapter: STATE_ON
11-15 16:39:51.330  5804  5815 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 16:39:51.330  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 16:39:51.332  5804  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 16:39:51.332  5695  5742 D BluetoothAdapter: STATE_ON
,11-15 16:39:51.334  5804  5842 D BtGatt.GattService: stopScan() - queue size =1
11-15 16:39:51.336  5804  5834 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 16:39:51.336  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-15 16:39:51.337  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.337  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-15 16:39:51.337  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:51.337  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.337  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.337  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 16:39:51.337  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:51.339  5804  5824 D BtGatt.AdvertiseManager: message : 1
11-15 16:39:51.340  5804  5804 D BtGatt.ScanManager: awakened up at time 117388
11-15 16:39:51.343  5804  5824 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-15 16:39:51.353  5804  5821 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-15 16:39:51.353  5804  5821 D BtGatt.GattService: Client app is not null!
,11-15 16:39:51.354  5804  5842 D BtGatt.GattService: unregisterClient() - clientIf=6
11-15 16:39:51.355  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 16:39:51.355  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.356  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 16:39:51.356  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.356  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.356  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:51.356  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 16:39:51.356  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-15 16:39:51.357  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 16:39:51.358  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:51.360  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 16:39:51.360  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:51.360  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.360  5695  5742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 16:39:51.360  5695  5742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b96b887 removed from the list
11-15 16:39:51.360  5695  5742 D io.jxcore.node.ConnectivityMonitor: stop
11-15 16:39:51.361  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:51.361  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 16:39:51.361  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:51.361  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.361  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-15 16:39:51.361  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-15 16:39:51.361  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.361  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.361  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-15 16:39:51.362  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.362  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-15 16:39:51.362  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-15 16:39:51.362  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 16:39:51.362  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 16:39:51.363  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 16:39:51.363  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-15 16:39:51.363  5695  5742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 16:39:51.363  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.363  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.363  5695  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.363  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-15 16:39:51.364  5695  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 16:39:51.364  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-15 16:39:51.364  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.364  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 16:39:51.364  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 16:39:51.364  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.364  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 16:39:51.364  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 16:39:51.365  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-15 16:39:51.366  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-15 16:39:51.366  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-15 16:39:51.367  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-15 16:39:51.368  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-15 16:39:51.369  5804  5821 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-15 16:39:51.369  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:51.369  5804  5821 D BtGatt.GattService: current time is 117417419677
11-15 16:39:51.369  5804  5821 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -87, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 16:39:51.370  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-15 16:39:51.370  5804  5821 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 16:39:51.370  5804  5821 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 16:39:51.370  5804  5821 E BtGatt.ContextMap: Context not found for ID 5
,11-15 16:39:51.371  5695  5742 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-15 16:39:51.381  5804  5821 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-15 16:39:51.381  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:51.381  5804  5825 D BtGatt.ScanManager: stopping BLe Batch
,11-15 16:39:51.386  5804  5821 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-15 16:39:51.386  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 16:39:51.386  5804  5825 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 16:39:51.391  5804  5821 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 16:39:51.391  5804  5821 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 16:39:51.865  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 16:39:51.916   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:52.917   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:53.223   930  3056 D ConnectivityService: handlePromptUnvalidated 101
,11-15 16:39:53.375  5695  5742 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-15 16:39:53.528  5695  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 16:39:53.528  5695  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:39:53.918   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:54.046   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 16:39:54.341  5695  5958 W !!      : call onHalfStreamCopied
,11-15 16:39:54.341  5695  5958 I testCopyDataAndClose: closing input stream
,11-15 16:39:54.918   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 16:39:55.119  5695  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 16:39:55.544   930  3054 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-15 16:39:55.920   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:39:56.240   930  3054 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-15 16:39:56.920   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 16:39:57.071   930  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 16:39:59.280  5695  5742 I StreamCopyingThreadTest: Starting test: testRun
,11-15 16:39:59.287  5695  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:39:59.287  5695  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:40:01.922   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:02.923   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:03.925   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:04.294  5695  5960 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-15 16:40:04.297  5695  5742 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-15 16:40:04.428  5695  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 16:40:04.428  5695  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:40:04.926   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:05.927   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:06.033  5695  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 16:40:06.033  5695  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:40:06.033  5695  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 16:40:06.033  5695  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 16:40:06.033  5695  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 16:40:06.034  5695  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 16:40:06.034  5695  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 16:40:06.034  5695  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 16:40:06.034  5695  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 16:40:06.034  5695  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 16:40:06.034  5695  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 16:40:06.928   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 16:40:07.836   930  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133884, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 16:40:09.345  3756  3945 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 16:40:09.346  3756  3945 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 16:40:09.379  3643  3643 I ConfigService: onCreate
,11-15 16:40:10.112  5695  5742 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-15 16:40:10.114  5695  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:40:10.114  5695  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 16:40:10.115  5695  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 16:40:10.116  5695  5963 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-15 16:40:10.116  5695  5963 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 16:40:10.116  5695  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:40:10.116  5695  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-15 16:40:10.117  5695  5742 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-15 16:40:10.118  5695  5742 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-15 16:40:10.119  5695  5742 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-15 16:40:10.121  5695  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:40:10.121  5695  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 16:40:10.122  5695  5964 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-15 16:40:10.122  5695  5964 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:40:10.122  5695  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-15 16:40:10.122  5695  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-15 16:40:10.122  5695  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-15 16:40:10.122  5695  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 16:40:10.124  5695  5742 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-15 16:40:10.124  5695  5742 E com.test.thalitest.ThaliTestRunner: 
11-15 16:40:10.124  5695  5742 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 16:40:10.124  5695  5742 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.125  5695  5742 E com.,test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 16:4,0:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 16:40:10.125  5695  5742 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRu,nner.java:363)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-15 16:40:10.126  5695  5742 E com.test.thal,itest.ThaliTestRunner: StreamCopyingThread should be closed
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 16:40:10.126  5695  5742 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
,11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunn,er.java:325)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 16:40:10.127  5695  5742 E com.,test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:10.127  5695  5742 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 16:40:10.129  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG UnitTest_app: 'Running unit tests'
11-15 16:40:10.129  5695  5742 I jxcore-log: 
11-15 16:40:10.129  5695  5742 I jxcore-log: *Native tests were executed*
11-15 16:40:10.129  5695  5742 I jxcore-log: 
11-15 16:40:10.129  5695  5742 I jxcore-log: Total number of executed tests:  82
11-15 16:40:10.129  5695  5742 I jxcore-log: 
11-15 16:40:10.129  5695  5742 I jxcore-log: Number of passed tests:  79
11-15 16:40:10.129  5695  5742 I jxcore-log: 
11-15 16:40:10.129  5695  5742 I jxcore-log: Number of failed tests:  3
11-15 16:40:10.129  5695  5742 I jxcore-log: 
11-15 16:40:10.130  5695  5742 I jxcore-log: Number of ignored tests:  0
11-15 16:40:10.130  5695  5742 I jxcore-log: 
11-15 16:40:10.130  5695  5742 I jxcore-log: Total duration:  39557
11-15 16:40:10.130  5695  5742 I jxcore-log: 
11-15 16:40:10.130  5695  5742 I jxcore-log: Failed to execute UT.
11-15 16:40:10.130  5695  5742 I jxcore-log: 
11-15 16:40:10.131  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-15 16:40:10.131  5695  5742 I jxcore-log: 
11-15 16:40:10.132  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-15 16:40:10.132  5695  5742 I jxcore-log: 
11-15 16:40:10.135  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 16:40:10.135  5695  5742 I jxcore-log: 
11-15 16:40:10.135  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.135  5695  5742 I jxcore-log: 
11-15 16:40:10.136  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 16:40:10.136  5695  5742 I jxcore-log: 
11-15 16:40:10.137  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.137  5695  5742 I jxcore-log: 
11-15 16:40:10.138  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 16:40:10.138  5695  5742 I jxcore-log: 
11-15 16:40:10.138  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 16:40:10.138  5695  5742 I jxcore-log: 
11-15 16:40:10.138  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.138  5695  5742 I jxcore-log: 
11-15 16:40:10.139  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 16:40:10.139  5695  5742 I jxcore-log: 
11-15 16:40:10.139  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 16:40:10.139  5695  5742 I jxcore-log: 
11-15 16:40:10.139  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.139  5695  5742 I jxcore-log: 
11-15 16:40:10.139  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 16:40:10.139  5695  5742 I jxcore-log: 
11-15 16:40:10.139  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 16:40:10.139  5695  5742 I jxcore-log: 
11-15 16:40:10.140  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.140  5695  5742 I jxcore-log: 
11-15 16:40:10.140  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 16:40:10.140  5695  5742 I jxcore-log: 
11-15 16:40:10.140  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.140  5695  5742 I jxcore-log: 
11-15 16:40:10.140  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 16:40:10.140  5695  5742 I jxcore-log: 
11-15 16:40:10.141  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.141  5695  5742 I jxcore-log: 
11-15 16:40:10.141  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 16:40:10.141  5695  5742 I jxcore-log: 
11-15 16:40:10.141  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.141  5695  5742 I jxcore-log: 
11-15 16:40:10.141  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 16:40:10.141  5695  5742 I jxcore-log: 
11-15 16:40:10.141  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.141  5695  5742 I jxcore-log: 
11-15 16:40:10.142  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 16:40:10.142  5695  5742 I jxcore-log: 
11-15 16:40:10.142  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.142  5695  5742 I jxcore-log: 
11-15 16:40:10.142  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 16:40:10.142  5695  5742 I jxcore-log: 
11-15 16:40:10.142  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.142  5695  5742 I jxcore-log: 
11-15 16:40:10.143  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 16:40:10.143  5695  5742 I jxcore-log: 
11-15 16:40:10.143  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 16:40:10.143  5695  5742 I jxcore-log: 
11-15 16:40:10.143  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 16:40:10.143  5695  5742 I jxcore-log: 
11-15 16:40:10.144  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 16:40:10.144  5695  5742 I jxcore-log: 
11-15 16:40:10.144  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.144  5695  5742 I jxcore-log: 
11-15 16:40:10.145  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-15 16:40:10.145  5695  5742 I jxcore-log: 
11-15 16:40:10.145  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 16:40:10.145  5695  5742 I jxcore-log: 
11-15 16:40:10.145  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.145  5695  5742 I jxcore-log: 
11-15 16:40:10.146  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-15 16:40:10.146  5695  5742 I jxcore-log: 
11-15 16:40:10.146  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 16:40:10.146  5695  5742 I jxcore-log: 
11-15 16:40:10.146  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.146  5695  5742 I jxcore-log: 
11-15 16:40:10.146  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 16:40:10.146  5695  5742 I jxcore-log: 
11-15 16:40:10.146  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 16:40:10.146  5695  5742 I jxcore-log: 
11-15 16:40:10.151  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-15 16:40:10.151  5695  5742 I jxcore-log: 
11-15 16:40:10.151  5695  5742 I jxcore-log: 2016-11-15 15:40:10 - WARN testUtils: 'myNameCallback not set!'
11-15 16:40:10.151  5695  5742 I jxcore-log: 
11-15 16:40:10.153  5695  5695 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-15 16:40:12.247  5695  5742 I jxcore-log: 2016-11-15 15:40:12 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-15 16:40:12.247  5695  5742 I jxcore-log: 
,11-15 16:40:12.249  5695  5742 I jxcore-log: 2016-11-15 15:40:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-15 16:40:12.249  5695  5742 I jxcore-log: 
,11-15 16:40:12.590  5695  5742 I jxcore-log: 2016-11-15 15:40:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-15 16:40:12.590  5695  5742 I jxcore-log: 
,11-15 16:40:12.604  5695  5742 I jxcore-log: 2016-11-15 15:40:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-15 16:40:12.604  5695  5742 I jxcore-log: 
,11-15 16:40:13.719  5695  5742 I jxcore-log: 2016-11-15 15:40:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-15 16:40:13.719  5695  5742 I jxcore-log: 
,11-15 16:40:13.888  5695  5742 I jxcore-log: 2016-11-15 15:40:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-15 16:40:13.888  5695  5742 I jxcore-log: 
,11-15 16:40:13.893  5695  5742 I jxcore-log: 2016-11-15 15:40:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-15 16:40:13.893  5695  5742 I jxcore-log: 
,11-15 16:40:13.905  5695  5742 I jxcore-log: 2016-11-15 15:40:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-15 16:40:13.905  5695  5742 I jxcore-log: 
,11-15 16:40:14.398  5695  5742 I jxcore-log: 2016-11-15 15:40:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-15 16:40:14.398  5695  5742 I jxcore-log: 
,11-15 16:40:14.421  3643  3643 I ConfigService: onDestroy
,11-15 16:40:14.443  5695  5742 I jxcore-log: 2016-11-15 15:40:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-15 16:40:14.443  5695  5742 I jxcore-log: 
,11-15 16:40:14.456  5695  5742 I jxcore-log: 2016-11-15 15:40:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-15 16:40:14.456  5695  5742 I jxcore-log: 
,11-15 16:40:14.461  5695  5742 I jxcore-log: 2016-11-15 15:40:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-15 16:40:14.461  5695  5742 I jxcore-log: 
,11-15 16:40:14.737  5695  5742 I jxcore-log: 2016-11-15 15:40:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-15 16:40:14.737  5695  5742 I jxcore-log: 
,11-15 16:40:14.865  5695  5742 I jxcore-log: 2016-11-15 15:40:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-15 16:40:14.865  5695  5742 I jxcore-log: 
,11-15 16:40:15.248  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-15 16:40:15.248  5695  5742 I jxcore-log: 
,11-15 16:40:15.255  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-15 16:40:15.255  5695  5742 I jxcore-log: 
,11-15 16:40:15.259  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-15 16:40:15.259  5695  5742 I jxcore-log: 
,11-15 16:40:15.263  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-15 16:40:15.263  5695  5742 I jxcore-log: 
,11-15 16:40:15.268  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-15 16:40:15.268  5695  5742 I jxcore-log: 
,11-15 16:40:15.308  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-15 16:40:15.308  5695  5742 I jxcore-log: 
,11-15 16:40:15.314  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-15 16:40:15.314  5695  5742 I jxcore-log: 
,11-15 16:40:15.335  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-15 16:40:15.335  5695  5742 I jxcore-log: 
,11-15 16:40:15.372  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-15 16:40:15.372  5695  5742 I jxcore-log: 
,11-15 16:40:15.387  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-15 16:40:15.387  5695  5742 I jxcore-log: 
,11-15 16:40:15.394  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-15 16:40:15.394  5695  5742 I jxcore-log: 
,11-15 16:40:15.409  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-15 16:40:15.409  5695  5742 I jxcore-log: 
,11-15 16:40:15.424  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-15 16:40:15.424  5695  5742 I jxcore-log: 
,11-15 16:40:15.430  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-15 16:40:15.430  5695  5742 I jxcore-log: 
,11-15 16:40:15.437  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-15 16:40:15.437  5695  5742 I jxcore-log: 
,11-15 16:40:15.450  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-15 16:40:15.450  5695  5742 I jxcore-log: 
,11-15 16:40:15.467  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-15 16:40:15.467  5695  5742 I jxcore-log: 
,11-15 16:40:15.482  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-15 16:40:15.482  5695  5742 I jxcore-log: 
,11-15 16:40:15.494  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-15 16:40:15.494  5695  5742 I jxcore-log: 
,11-15 16:40:15.507  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-15 16:40:15.507  5695  5742 I jxcore-log: 
,11-15 16:40:15.517  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-15 16:40:15.517  5695  5742 I jxcore-log: 
,11-15 16:40:15.531  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-15 16:40:15.531  5695  5742 I jxcore-log: 
,11-15 16:40:15.540  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-15 16:40:15.540  5695  5742 I jxcore-log: 
,11-15 16:40:15.547  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-15 16:40:15.547  5695  5742 I jxcore-log: 
,11-15 16:40:15.568  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-15 16:40:15.568  5695  5742 I jxcore-log: 
,11-15 16:40:15.574  5695  5742 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-15 16:40:15.575  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - INFO testUtils: 'BLE multiple advertisement supported'
11-15 16:40:15.575  5695  5742 I jxcore-log: 
,11-15 16:40:15.646  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:15.646  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:15.646  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:15.646  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:15.646  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:15.646  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:15.646  5695  5742 I jxcore-log: 
,11-15 16:40:15.885  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:15.885  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:15.885  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:15.885  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:15.885  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:15.885  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:15.885  5695  5742 I jxcore-log: 
,11-15 16:40:15.888  5695  5742 I jxcore-log: 2016-11-15 15:40:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:15.888  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:15.888  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:15.888  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:15.888  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:15.888  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:15.888  5695  5742 I jxcore-log: 
,11-15 16:40:16.178  5695  5742 I jxcore-log: 2016-11-15 15:40:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:16.178  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:16.178  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:16.178  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:16.178  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:16.178  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:16.178  5695  5742 I jxcore-log: 
,11-15 16:40:16.181  5695  5742 I jxcore-log: 2016-11-15 15:40:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:16.181  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:16.181  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:16.181  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:16.181  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:16.181  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:16.181  5695  5742 I jxcore-log: 
,11-15 16:40:16.929   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:17.930   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:18.211  5695  5742 I jxcore-log: 2016-11-15 15:40:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:18.211  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:18.211  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:18.211  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:18.211  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:18.211  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:18.211  5695  5742 I jxcore-log: 
,11-15 16:40:18.215  5695  5742 I jxcore-log: 2016-11-15 15:40:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:18.215  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:18.215  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:18.215  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:18.215  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:18.215  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:18.215  5695  5742 I jxcore-log: 
,11-15 16:40:18.931   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:19.248  5695  5742 I jxcore-log: 2016-11-15 15:40:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:19.248  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:19.248  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:19.248  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:19.248  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:19.248  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:19.248  5695  5742 I jxcore-log: 
,11-15 16:40:19.255  5695  5742 I jxcore-log: 2016-11-15 15:40:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:19.255  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:19.255  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:19.255  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:19.255  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:19.255  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:19.255  5695  5742 I jxcore-log: 
,11-15 16:40:19.932   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:20.291  5695  5742 I jxcore-log: 2016-11-15 15:40:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:20.291  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:20.291  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:20.291  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:20.291  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:20.291  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:20.291  5695  5742 I jxcore-log: 
,11-15 16:40:20.295  5695  5742 I jxcore-log: 2016-11-15 15:40:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:20.295  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:20.295  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:20.295  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:20.295  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:20.295  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:20.295  5695  5742 I jxcore-log: 
,11-15 16:40:20.643   930  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 16:40:20.933   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 16:40:21.326  5695  5742 I jxcore-log: 2016-11-15 15:40:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:21.326  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:21.326  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:21.326  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:21.326  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:21.326  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:21.326  5695  5742 I jxcore-log: 
,11-15 16:40:21.330  5695  5742 I jxcore-log: 2016-11-15 15:40:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:21.330  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:21.330  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:21.330  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:21.330  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:21.330  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:21.330  5695  5742 I jxcore-log: 
,11-15 16:40:21.934   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 16:40:23.227  5695  5742 I jxcore-log: 2016-11-15 15:40:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:23.227  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:23.227  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:23.227  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:23.227  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:23.227  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:23.227  5695  5742 I jxcore-log: 
,11-15 16:40:23.231  5695  5742 I jxcore-log: 2016-11-15 15:40:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:23.231  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:23.231  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:23.231  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:23.231  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:23.231  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:23.231  5695  5742 I jxcore-log: 
,11-15 16:40:24.265  5695  5742 I jxcore-log: 2016-11-15 15:40:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:24.265  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:24.265  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:24.265  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:24.265  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:24.265  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:24.265  5695  5742 I jxcore-log: 
,11-15 16:40:24.269  5695  5742 I jxcore-log: 2016-11-15 15:40:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:24.269  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:24.269  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:24.269  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:24.269  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:24.269  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:24.269  5695  5742 I jxcore-log: 
,11-15 16:40:25.201   930  3054 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 16:40:25.296  5695  5742 I jxcore-log: 2016-11-15 15:40:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:25.296  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:25.296  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:25.296  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:25.296  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:25.296  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:25.296  5695  5742 I jxcore-log: 
,11-15 16:40:25.299  5695  5742 I jxcore-log: 2016-11-15 15:40:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:25.299  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:25.299  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:25.299  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:25.299  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:25.299  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:25.299  5695  5742 I jxcore-log: 
,11-15 16:40:26.384  5695  5742 I jxcore-log: 2016-11-15 15:40:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:26.384  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:26.384  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:26.384  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:26.384  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:26.384  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:26.384  5695  5742 I jxcore-log: 
,11-15 16:40:26.390  5695  5742 I jxcore-log: 2016-11-15 15:40:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:26.390  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:26.390  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:26.390  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:26.390  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:26.390  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:26.390  5695  5742 I jxcore-log: 
,11-15 16:40:27.421  5695  5742 I jxcore-log: 2016-11-15 15:40:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:27.421  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:27.421  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:27.421  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:27.421  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:27.421  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:27.421  5695  5742 I jxcore-log: 
,11-15 16:40:27.427  5695  5742 I jxcore-log: 2016-11-15 15:40:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:27.427  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:27.427  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:27.427  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:27.427  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:27.427  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:27.427  5695  5742 I jxcore-log: 
,11-15 16:40:28.464  5695  5742 I jxcore-log: 2016-11-15 15:40:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:28.464  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:28.464  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:28.464  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:28.464  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:28.464  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:28.464  5695  5742 I jxcore-log: 
,11-15 16:40:28.469  5695  5742 I jxcore-log: 2016-11-15 15:40:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:28.469  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:28.469  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:28.469  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:28.469  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:28.469  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:28.469  5695  5742 I jxcore-log: 
,11-15 16:40:29.499  5695  5742 I jxcore-log: 2016-11-15 15:40:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:29.499  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:29.499  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:29.499  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:29.499  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:29.499  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:29.499  5695  5742 I jxcore-log: 
,11-15 16:40:29.503  5695  5742 I jxcore-log: 2016-11-15 15:40:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:29.503  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:29.503  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:29.503  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:29.503  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:29.503  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:29.503  5695  5742 I jxcore-log: 
,11-15 16:40:30.531  5695  5742 I jxcore-log: 2016-11-15 15:40:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:30.531  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:30.531  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:30.531  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:30.531  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:30.531  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:30.531  5695  5742 I jxcore-log: 
,11-15 16:40:30.535  5695  5742 I jxcore-log: 2016-11-15 15:40:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:30.535  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:30.535  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:30.535  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:30.535  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:30.535  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:30.535  5695  5742 I jxcore-log: 
,11-15 16:40:30.683  4135  4554 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-15 16:40:31.550  5695  5742 I jxcore-log: 2016-11-15 15:40:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 16:40:31.550  5695  5742 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 16:40:31.550  5695  5742 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 16:40:31.550  5695  5742 I jxcore-log: emit@events.js:82:1
11-15 16:40:31.550  5695  5742 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 16:40:31.550  5695  5742 I jxcore-log: emit@events.js:82:1'
11-15 16:40:31.550  5695  5742 I jxcore-log: 
,11-15 16:40:31.554  5695  5742 E jxcore  : Error!: error is undefined
11-15 16:40:31.554  5695  5742 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-15 16:40:31.555  5695  5742 I jxcore-log: 2016-11-15 15:40:31 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-15 16:40:31.555  5695  5742 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-15 16:40:31.555  5695  5742 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-15 16:40:31.555  5695  5742 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-15 16:40:31.555  5695  5742 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-15 16:40:31.555  5695  5742 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-15 16:40:31.555  5695  5742 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-15 16:40:31.555  5695  5742 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-15 16:40:31.556  5695  5742 I jxcore-log: 2016-11-15 15:40:31 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-15 16:40:31.556  5695  5742 I jxcore-log: 
,11-15 16:40:31.556  5695  5742 E jxcore-log: TypeError: 
11-15 16:40:31.557  5695  5742 E jxcore-log: error is undefined
11-15 16:40:31.557  5695  5742 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-15 16:40:31.557  5695  5742 E jxcore-log: 
,11-15 16:40:31.574  3643  5966 I VacuumService: Vacuum at: now=1479224431574 tag=VacuumService
,11-15 16:40:31.610  3643  5969 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-15 16:40:31.640   930  3846 D GraphicsStats: Buffer count: 2
,11-15 16:40:31.640   930  3055 D WifiService: Client connection lost with reason: 4
11-15 16:40:31.640   930  3221 I WindowState: WIN DEATH: Window{eb536dd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-15 16:40:31.661   527   527 I Zygote  : Process 5695 exited cleanly (139)
,11-15 16:40:31.664   930  3846 I ActivityManager: Process com.test.thalitest (pid 5695) has died
11-15 16:40:31.668   930  3846 W ActivityManager: Force removing ActivityRecord{176ba9a u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-15 16:40:31.701  3643  5967 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-15 16:40:31.704  3643  5967 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-15 16:40:31.712   930   940 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5695 uid 10077
11-15 16:40:31.709   940   940 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[29133]" dev="sockfs" ino=29133 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 16:40:31.709   940   940 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[29133]" dev="sockfs" ino=29133 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 16:40:31.714  3756  3756 I Keyboard.Facilitator: onFinishInput()
,11-15 16:40:31.740  3643  5967 W Uploader:  no longer exists, so no auth token.
,11-15 16:40:31.748  3643  5969 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 16:40:31.778  4049  5977 I MicroRecognitionRnrImpl: Starting detection.
,11-15 16:40:31.779  4049  5978 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@29cbfb9
,11-15 16:40:31.781   512  5980 I AudioFlinger: AudioFlinger's thread 0xf1c80000 ready to run
,11-15 16:40:31.784   512  3076 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-15 16:40:31.786  4049  5978 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@29cbfb9
,11-15 16:40:31.796   512  5980 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-15 16:40:31.797   512  5980 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-15 16:40:31.797   512  5980 I ACDB-LOADER: ACDB AFE returned = -19
11-15 16:40:31.797   512  5980 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-15 16:40:31.797   512  5980 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-15 16:40:31.797   512  5980 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-15 16:40:31.804   512  5980 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-15 16:40:31.887  4049  4049 I HotwordWorkerImpl: onReady
,11-15 16:40:32.008  3643  5973 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 16:40:32.024  5970  5970 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-15 16:40:32.027  5970  5970 D AndroidRuntime: CheckJNI is OFF
,11-15 16:40:32.047  5970  5970 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-15 16:40:32.074  5970  5970 I Radio-JNI: register_android_hardware_Radio DONE
,11-15 16:40:32.077  3643  5969 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 16:40:32.088  5970  5970 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-15 16:40:32.096   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-15 16:40:32.255  3909  4094 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-15 16:40:32.262   930   953 I art     : Starting a blocking GC Explicit
,11-15 16:40:32.334   930   953 I art     : Explicit concurrent mark sweep GC freed 16814(1032KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.486ms total 72.052ms
,11-15 16:40:32.339  3643  5973 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 16:40:32.351   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-15 16:40:32.354  5970  5970 I art     : System.exit called, status: 0
,11-15 16:40:32.354  5970  5970 I AndroidRuntime: VM exiting with result code 0.
,11-15 16:40:32.361   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-15 16:40:32.368  5804  5804 D BluetoothMapAppObserver: onReceive
,11-15 16:40:32.368  5804  5804 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-15 16:40:32.376  3756  3756 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-15 16:40:32.376  4135  4262 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-15 16:40:32.380   930  3020 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-15 16:40:32.392  3756  5994 I Keyboard.Facilitator.DecoderInitializer: run()
,11-15 16:40:32.394  3756  5994 I Decoder : createOrResetDecoder
,11-15 16:40:32.424  3866  3866 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-15 16:40:32.437  3643  3643 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-15 16:40:32.438  3643  3643 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-15 16:40:32.440   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-15 16:40:32.446  3477  5996 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-15 16:40:32.455  3643  5967 W Uploader:  no longer exists, so no auth token.
,11-15 16:40:32.464  3643  3643 I ConfigService: onCreate
,11-15 16:40:32.466  3940  6000 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-15 16:40:32.467  3940  6000 D AccountUtils: Clearing selected account for com.test.thalitest
,11-15 16:40:32.476   315   315 W kworker/1:2: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 16:40:32.482   315   315 W kworker/1:2: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-15 16:40:32.485  3643  5969 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 16:40:32.485  3940  6000 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-15 16:40:32.489  3940  3940 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-15 16:40:32.490  3940  3940 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-15 16:40:32.493  3756  5994 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-15 16:40:32.498  3940  3940 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-15 16:40:32.498  3940  3940 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-15 16:40:32.502   315   315 W kworker/1:2: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 16:40:32.511  3940  6006 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,11-15 16:40:32.511  4049  6010 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-15 16:40:32.511  3940  6006 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,11-15 16:40:32.511  3940  6006 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,11-15 16:40:32.512  3940  6006 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,11-15 16:40:32.518  3940  6006 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/help_responses.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
11-15 16:40:32.518  3940  6006 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-15 16:40:32.518  3940  6006 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
11-15 16:40:32.519  3940  6006 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db'.
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:32.521  3940  6006 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: Couldn't open auto_complete_suggestions.db for writing (will try read-only):
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLi,teConnectionPool.java:463)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:32.522  3940  6006 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 16:40:32.523  3940  6006 W SQLiteOpenHelper: Opened auto_complete_suggestions.db in read-only mode
11-15 16:40:32.523  3940  6006 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-15 16:40:32.523  3940  6006 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-15 16:40:32.524  3940  6006 E SQLiteLog: (8) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-15 16:40:32.524  3940  6006 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
--------- beginning of crash
11-15 16:40:32.525  3940  6006 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-15 16:40:32.525  3940  6006 E AndroidRuntime: Process: com.google.android.gms, PID: 3940
11-15 16:40:32.525  3940  6006 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:32.525  3940  6006 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: Failed to save models
11-15 16:40:32.528  3909  4090 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.528  3909  4090 E ReflectionEngine: 	... 16 more
11-15 16:40:32.532  4049  6010 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-15 16:40:32.539   930  3658 I ActivityManager: Start proc 6012:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
11-15 16:40:32.543  3477  5996 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-15 16:40:32.548   930  6021 E DropBoxManagerService: Can't write: system_app_crash
11-15 16:40:32.548   930  6021 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.548   930  6021 E DropBoxManagerService: 	... 5 more
11-15 16:40:32.553  3477  5996 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-15 16:40:32.553  3477  5996 E AndroidRuntime: Process: android.process.acore, PID: 3477
11-15 16:40:32.553  3477  5996 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:32.553  3477  5996 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: Failed to write the stream file
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2439: open failed: EROFS (Read-only file system)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.553  3909  4090 E ObservedEventLogger: 	... 16 more
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: Failed to write the stream file
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2440: open failed: EROFS (Read-only file system)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.554  3909  4090 E ObservedEventLogger: 	... 16 more
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: Failed to write the stream file
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2441: open failed: EROFS (Read-only file system)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.555  3909  4090 E ObservedEventLogger: 	... 16 more
11-15 16:40:32.552   408   408 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[35294]" dev="sockfs" ino=35294 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 16:40:32.552   408   408 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[35294]" dev="sockfs" ino=35294 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: Failed to write the stream file
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2442: open failed: EROFS (Read-only file system)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.556  3909  4090 E ObservedEventLogger: 	... 16 more
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: Failed to write the stream file
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2443: open failed: EROFS (Read-only file system)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.557  3909  4090 E ObservedEventLogger: 	... 16 more
11-15 16:40:32.561   930  6025 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-15 16:40:32.556   410   410 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32329]" dev="sockfs" ino=32329 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 16:40:32.556   410   410 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32329]" dev="sockfs" ino=32329 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 16:40:32.576   930  3221 I ActivityManager: Start proc 6026:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-15 16:40:32.577  4049  6010 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
11-15 16:40:32.577  4049  6010 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
11-15 16:40:32.577  4049  6010 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4049
11-15 16:40:32.577  4049  6010 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 16:40:32.577  4049  6010 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: Can't write: system_app_crash
11-15 16:40:32.579   930  6034 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.579   930  6034 E DropBoxManagerService: 	... 5 more
11-15 16:40:32.589   930  6038 E DropBoxManagerService: Can't write: system_app_crash
11-15 16:40:32.589   930  6038 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 16:40:32.589   930  6038 E DropBoxManagerService: 	... 5 more
,11-15 16:40:32.598  3756  5994 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-15 16:40:32.601  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-15 16:40:32.601  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-15 16:40:32.601  3940  6008 W BaseAppContext: Using Auth Proxy for data requests.
,11-15 16:40:32.603  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-15 16:40:32.604  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-15 16:40:32.604  3940  6000 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
11-15 16:40:32.605  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-15 16:40:32.605  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-15 16:40:32.607  3940  6008 W BaseAppContext: Using Auth Proxy for data requests.
11-15 16:40:32.615  3940  6043 I GMPM-SVC: App measurement is starting up
11-15 16:40:32.616  3756  5994 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-15 16:40:32.617  3756  5994 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-15 16:40:32.617  3756  5994 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-15 16:40:32.617  3756  5994 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-15 16:40:32.617  3756  5994 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-15 16:40:32.617  3756  5994 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-15 16:40:32.620  3940  3940 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-15 16:40:32.623  3940  6043 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-15 16:40:32.623  3940  6043 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-15 16:40:32.632   930   943 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{b2fa427 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{82e0028 3940 com.google.android.gms/10012/u0 remote:daa6e4b}: process crashing
,11-15 16:40:32.640   930  3638 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3940 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-15 16:40:32.684  3940  6005 W DriveInitializer: Awaiting to be initialized
,11-15 16:40:32.685  3940  6047 W DriveInitializer: Background init thread started
,11-15 16:40:32.902   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
