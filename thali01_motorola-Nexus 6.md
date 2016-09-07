#### Test 834440500e39eda_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,09-07 10:31:53.875   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-07 10:31:54.554  3754  3754 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 10:31:54.559  3754  3754 D AndroidRuntime: CheckJNI is OFF
09-07 10:31:54.594  3754  3754 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 10:31:54.636  3754  3754 I Radio-JNI: register_android_hardware_Radio DONE
09-07 10:31:54.656  3754  3754 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 10:31:54.660   874  1958 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 10:31:54.699  2013  2023 W SearchService: Abort, client detached.
09-07 10:31:54.703  3754  3754 D AndroidRuntime: Shutting down VM
09-07 10:31:54.706  2013  2013 I HotwordDetector: Closing mic
09-07 10:31:54.706  2013  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@537d6b3
09-07 10:31:54.707  2013  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 10:31:54.729   874  1928 I ActivityManager: Start proc 3763:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 10:31:54.765   377  2343 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 10:31:54.767   377  2343 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 10:31:54.774   377  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 10:31:54.776  2013  2337 I MicroRecognitionRnrImpl: Detection finished
09-07 10:31:54.777  2013  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 10:31:54.800  3763  3763 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 10:31:54.821  3763  3763 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 10:31:54.829  3763  3763 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3508-3512)
09-07 10:31:54.829  3763  3763 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 10:31:54.847  3763  3763 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f55ce9}
09-07 10:31:54.847  3763  3763 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 10:31:54.847  3763  3763 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 10:31:54.853  3763  3763 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 10:31:54.854  3763  3763 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 10:31:54.869  3763  3763 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 10:31:54.878  3763  3763 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 10:31:54.878  3763  3763 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 10:31:54.878  3763  3763 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 10:31:54.878  3763  3763 I Adreno  : Build Date                       : 10/20/15
09-07 10:31:54.878  3763  3763 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 10:31:54.878  3763  3763 I Adreno  : Local Branch                     : M14
09-07 10:31:54.878  3763  3763 I Adreno  : Remote Branch                    : 
09-07 10:31:54.878  3763  3763 I Adreno  : Remote Branch                    : 
09-07 10:31:54.878  3763  3763 I Adreno  : Reconstruct Branch               : 
,09-07 10:31:54.937   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2475a2d:true
,09-07 10:31:54.982  3763  3763 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 10:31:54.994  3763  3763 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 10:31:55.044  3763  3801 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 10:31:55.053  3763  3788 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 10:31:55.086  3763  3801 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 10:31:55.140  1880  1880 I Keyboard.Facilitator: onFinishInput()
,09-07 10:31:55.140   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +439ms
,09-07 10:31:55.230  3763  3763 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3763
,09-07 10:31:55.445  3763  3763 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 10:31:55.539   874  3066 I ActivityManager: Killing 2968:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 10:31:55.574  3763  3803 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1712916176
,09-07 10:31:55.582   874  3066 I ActivityManager: Killing 3187:com.google.android.gm/u0a78 (adj 15): empty #18
,09-07 10:31:55.596  3763  3803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 10:31:55.596  3763  3803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 10:31:55.596  3763  3803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 10:31:55.596  3763  3803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 10:31:55.596  3763  3803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 10:31:55.596  3763  3803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db0f1d added. We now have 1 listener(s)
,09-07 10:31:55.604  3763  3803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 10:31:55.606  3763  3803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:31:55.606  3763  3803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:31:55.606  3763  3803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 10:31:55.609  3763  3803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7282360 added. We now have 1 listener(s)
,09-07 10:31:55.609  3763  3803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:31:55.611   874  1310 D WifiService: New client listening to asynchronous messages
09-07 10:31:55.612  3763  3803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:31:55.612  3763  3803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 10:31:55.612  3763  3803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 10:31:55.612  3763  3803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-07 10:31:55.612  3763  3803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 10:31:55.647  3763  3803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:31:55.647  3763  3803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 10:31:55.656  3763  3803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:31:55.656  3763  3803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:31:55.656  3763  3803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 10:31:55.657  3763  3803 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:31:55.657  3763  3803 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 10:31:55.792  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:31:55.796  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:31:55.798  3763  3763 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 10:31:56.900   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 10:31:57.021  3763  3814 W jxcore-log: Initializing JXcore engine
09-07 10:31:57.021  3763  3814 W jxcore-log: JXcore engine is ready
,09-07 10:31:57.061  3814  3814 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 10:31:57.061  3814  3814 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11666]" dev="sockfs" ino=11666 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 10:31:57.061  3814  3814 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 10:31:57.061  3814  3814 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26718]" dev="sockfs" ino=26718 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 10:31:57.075  3763  3814 W jxcore-log: Starting JXcore engine
,09-07 10:31:57.154  3763  3814 W jxcore-log: Platform android
09-07 10:31:57.154  3763  3814 W jxcore-log: 
,09-07 10:31:57.154  3763  3814 W jxcore-log: Process ARCH arm
09-07 10:31:57.154  3763  3814 W jxcore-log: 
,09-07 10:31:57.344  3763  3814 I jxcore-log: JXcore Cordova bridge is ready!
09-07 10:31:57.344  3763  3814 I jxcore-log: 
,09-07 10:31:57.344  3763  3814 W jxcore-log: JXcore engine is started
,09-07 10:31:57.354  3763  3803 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 10:31:57.360  3763  3763 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 10:32:02.541   874  1871 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 10:32:03.313   874  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 10:32:04.993  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 10:32:05.003  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 10:32:05.007  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 10:32:05.046  1506  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 10:32:05.046  1506  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 10:32:05.046  1506  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:05.046  1506  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:05.089  3502  3502 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 10:32:05.090  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 10:32:05.090  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 10:32:07.066  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 10:32:07.066  3763  3814 I jxcore-log: 
,09-07 10:32:07.069  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 10:32:07.069  3763  3814 I jxcore-log: 
,09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.083  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:07.089  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:07.091  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 10:32:07.091  3763  3814 I jxcore-log: 
,09-07 10:32:07.093  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 10:32:07.093  3763  3814 I jxcore-log: 
,09-07 10:32:07.589  3763  3814 D executeNativeTests: Running unit tests
,09-07 10:32:07.648  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:07.648  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad added. We now have 2 listener(s)
,09-07 10:32:07.649  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:07.649  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:07.649  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:32:07.649  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:07.649  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 added. We now have 2 listener(s)
,09-07 10:32:07.649  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:07.650  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:07.655  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.667  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:07.672  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.672  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:07.675  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 10:32:07.676  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 10:32:07.676  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 10:32:07.678  3763  3814 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 10:32:07.678  3763  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 10:32:07.678  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 10:32:07.678  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 10:32:07.679  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 10:32:07.679  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:07.679  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:07.679  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:07.679  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:07.680  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.680  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:07.680  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 10:32:07.680  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad removed from the list
09-07 10:32:07.680  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.680  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 removed from the list
,09-07 10:32:07.683  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:07.695  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:07.696  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.696  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.696  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.696  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.697  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.697  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.697  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.697  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.705  3763  3814 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 10:32:07.706  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.706  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:07.707  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:07.707  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.707  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.707  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:07.707  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.707  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.708  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.708  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:07.708  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.708  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.708  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.708  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:07.709  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.710  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.710  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.711  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.718  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 10:32:07.719  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 10:32:07.720  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 10:32:07.721  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 10:32:07.721  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 10:32:07.721  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 10:32:07.721  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 10:32:07.721  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 10:32:07.721  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 10:32:07.721  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.721  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.721  3763  3814 V io.jxcore.node.,StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.721  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.721  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.721  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.721  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.722  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.722  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.722  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.722  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.722  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.722  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.722  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.723  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.723  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.723  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.723  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.724  3763  3814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 10:32:07.725  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.728  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:07.727  3571  3825 I BooksSync: Starting books sync for 61035162, extras: ade
09-07 10:32:07.729  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.730  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:07.730  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:07.730  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:07.730  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:07.730  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.730  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:32:07.732  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.733  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.734  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 10:32:07.734  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:32:07.738  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:07.740  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 10:32:07.740  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:32:07.742  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 10:32:07.744  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 10:32:07.744  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 10:32:07.744  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:07.745  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 10:32:07.746  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:07.750  2685  2698 D BtGatt.GattService: registerClient() - UUID=715b0af4-be95-4f50-8b7d-79a1e7c2abf0
09-07 10:32:07.751  2685  2705 D BtGatt.GattService: onClientRegistered() - UUID=715b0af4-be95-4f50-8b7d-79a1e7c2abf0, clientIf=5
09-07 10:32:07.751  3763  3775 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 10:32:07.752  2685  2834 D BtGatt.GattService: start scan with filters
09-07 10:32:07.755  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:07.755  2685  2708 D BtGatt.ScanManager: handling starting scan
09-07 10:32:07.755  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:07.755  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:07.756  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 10:32:07.757  2685  2708 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
09-07 10:32:07.758  3571  3826 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
09-07 10:32:07.758  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:07.759  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:07.759  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:07.761  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 10:32:07.764  3763  3814 I io.jxcore.node.ConnectionHelper: start: OK
09-07 10:32:07.764  2685  2705 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 10:32:07.764  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.764  2685  2708 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 10:32:07.768  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.768  3763  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 10:32:07.768  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.769  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 10:32:07.769  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.769  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:07.769  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:07.769  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 10:32:07.770  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.770  2685  2708 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:07.770  2685  2708 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 10:32:07.771  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:07.771  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:07.771  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:07.771  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:07.771  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 10:32:07.772  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:07.772  2685  2698 D BtGatt.GattService: stopScan() - queue size =1
09-07 10:32:07.773  2685  2834 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 10:32:07.773  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:07.773  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:07.773  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:07.773  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:07.773  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 10:32:07.775  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.775  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:07.775  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:07.775  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:07.777  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:07.779  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:07.779  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.779  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:07.779  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.779  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.780  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:07.780  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.780  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.780  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.780  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.780  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.780  3763  3814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 10:32:07.783  2685  2705 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 10:32:07.783  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.783  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.786  1506  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 10:32:07.786  1506  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 10:32:07.786  1506  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:07.786  1506  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 10:32:07.787  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 10:32:07.787  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.788  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:07.790  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.790  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:07.790  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:07.790  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:07.790  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:07.790  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.790  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:32:07.793  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.793  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 10:32:07.793  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.793  2685  2708 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:07.796  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.797  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 10:32:07.797  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:32:07.799  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 10:32:07.799  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.799  2685  2708 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 10:32:07.801  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:07.801  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 10:32:07.801  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:32:07.804  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 10:32:07.804  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:07.804  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 10:32:07.805  2685  2705 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 10:32:07.805  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.805  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:07.806  2685  2698 D BtGatt.GattService: registerClient() - UUID=aa6795b4-7668-43e4-98db-4246dcca118d
09-07 10:32:07.807  2685  2705 D BtGatt.GattService: onClientRegistered() - UUID=aa6795b4-7668-43e4-98db-4246dcca118d, clientIf=5
09-07 10:32:07.807  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 10:32:07.807  2685  2832 D BtGatt.GattService: start scan with filters
09-07 10:32:07.809  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:07.809  2685  2708 D BtGatt.ScanManager: handling starting scan
09-07 10:32:07.809  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:07.809  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:07.810  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 10:32:07.812  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:07.812  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:07.812  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:07.813  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 10:32:07.814  2685  2705 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 10:32:07.814  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.815  2685  2708 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 10:32:07.816  3763  3814 I io.jxcore.node.ConnectionHelper: start: OK
09-07 10:32:07.818  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.818  3763  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 10:32:07.818  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.819  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 10:32:07.819  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.819  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:07.819  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:07.819  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:07.819  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:07.819  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:07.819  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:07.819  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 10:32:07.820  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:07.820  2685  2698 D BtGatt.GattService: stopScan() - queue size =1
09-07 10:32:07.821  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 10:32:07.821  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.821  2685  2708 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:07.821  2685  2708 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 10:32:07.821  2685  2832 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 10:32:07.821  1506  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 10:32:07.821  1506  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 10:32:07.821  1506  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:07.821  1506  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 10:32:07.822  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:07.822  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:07.822  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:07.822  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:07.822  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 10:32:07.824  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.824  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:07.824  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:07.824  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:07.825  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:07.826  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.826  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.826  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:07.826  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:07.826  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.826  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:07.826  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.826  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.826  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.826  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:07.826  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.826  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:07.826  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.827  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.827  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.827  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.827  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.828  3763  3814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 10:32:07.829  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.831  2685  2705 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 10:32:07.831  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.834  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:07.834  3571  3826 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 10:32:07.835  3571  3825 E BooksSync: Soft error
09-07 10:32:07.835  3571  3825 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 10:32:07.835  3571  3825 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 10:32:07.835  3571  3825 E BooksSync: Sync error
09-07 10:32:07.835  3571  3825 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 10:32:07.835  3571  3825 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 10:32:07.835  3571  3825 I BooksSync: Finished books sync
,09-07 10:32:07.835  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.835  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 10:32:07.835  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.836  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:07.836  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:07.836  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 10:32:07.836  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:07.836  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.836  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:07.838  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 10:32:07.839  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:07.839  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.841  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.841   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126380, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
09-07 10:32:07.841  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 10:32:07.841  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:07.841  2685  2708 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:07.843  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:07.844  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 10:32:07.844  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:32:07.847  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 10:32:07.847  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:07.847  2685  2708 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 10:32:07.847  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 10:32:07.847  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
09-07 10:32:07.847  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 10:32:07.848  3763  3814 D BluetoothAdapter: STATE_ON
,09-07 10:32:07.849  2685  2832 D BtGatt.GattService: registerClient() - UUID=7b6d5489-a060-45fd-a205-b4706a61748b
09-07 10:32:07.849  2685  2705 D BtGatt.GattService: onClientRegistered() - UUID=7b6d5489-a060-45fd-a205-b4706a61748b, clientIf=5
09-07 10:32:07.850  3763  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 10:32:07.850  2685  2696 D BtGatt.GattService: start scan with filters
,09-07 10:32:07.852  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:07.852  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:07.852  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:07.852  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:07.854  2685  2705 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-07 10:32:07.855  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:07.855  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.855  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-07 10:32:07.855  2685  2705 D BtGatt.GattService: current time is 126538209749
09-07 10:32:07.855  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:07.855  2685  2705 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-07 10:32:07.856  2685  2705 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 10:32:07.856  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 10:32:07.857  2685  2708 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:07.859  3763  3814 I io.jxcore.node.ConnectionHelper: start: OK
09-07 10:32:07.859  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.859  3763  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 10:32:07.859  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.859  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 10:32:07.859  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.859  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:07.859  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:07.859  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 10:32:07.859  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:07.859  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:07.860  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:07.860  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 10:32:07.860  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:07.861  2685  2698 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:07.861  2685  2834 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 10:32:07.861  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:07.862  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:07.862  2685  2705 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 10:32:07.862  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:07.862  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.862  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:07.862  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 10:32:07.862  2685  2708 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 10:32:07.863  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.863  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:07.863  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 10:32:07.863  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:07.863  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:07.864  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:07.864  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:07.864  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.864  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.864  3763  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 10:32:07.865  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.865  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.865  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.865  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.865  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:07.865  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.865  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.865  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.865  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.865  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:07.866  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 10:32:07.866  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.866  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.866  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.866  2685  2708 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:07.866  2685  2708 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 10:32:07.867  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.867  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.867  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.867  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.868  3763  3814 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 10:32:07.868  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.868  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.868  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.868  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:07.868  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.869  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.869  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.869  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.869  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.869  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.869  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:07.869  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.869  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.869  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.870  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.870  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.870  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.870  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.871  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 10:32:07.871  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.871  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:07.871  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.871  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.872  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.872  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.872  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.872  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.872  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.872  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.872  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:07.872  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.872  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.872  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.873  2685  2705 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 10:32:07.873  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:07.873  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.873  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.873  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.873  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.876  3763  3814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 10:32:07.876  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.876  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.876  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.876  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.876  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.876  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.877  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
,09-07 10:32:07.877  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.877  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.877  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.877  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.877  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.877  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.877  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.878  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.878  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 10:32:07.878  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.878  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.878  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.878  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.879  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 10:32:07.879  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:07.879  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.879  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.879  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.879  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:07.879  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:07.879  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.879  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.880  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.880  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.880  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.880  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.880  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 10:32:07.880  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.881  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:07.881  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.881  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.881  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.881  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 10:32:07.882  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 10:32:07.882  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.882  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:32:07.882  2685  2708 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:07.883  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:32:07.883  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 10:32:07.883  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 10:32:07.883  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 10:32:07.883  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.883  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.883  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:07.884  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.884  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.884  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:07.884  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.884  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.884  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.884  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.884  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.884  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.884  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:07.884  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.885  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.885  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.886  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.886  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.886  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:07.886  3763  3814 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 10:32:07.887  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 10:32:07.888  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 10:32:07.888  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.888  2685  2708 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 10:32:07.890  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:07.890  3763  3814 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 10:32:07.890  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 10:32:07.891  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 10:32:07.892  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 10:32:07.893  2685  2705 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 10:32:07.893  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610],
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 10:32:07.893  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 10:32:07.893  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd,
09-07 10:32:07.893  3763  3814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:32:07.893  3763  3814 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 10:32:07.894  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:07.894  3763  3814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:32:07.894  3763  3814 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 10:32:07.894  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:07.894  3763  3814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:32:07.894  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 10:32:07.896  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 10:32:07.897  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 10:32:07.897  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 10:32:07.897  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 10:32:07.897  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 10:32:07.897  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 10:32:07.898  3763  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 10:32:07.898  3763  3814 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 10:32:07.898  3763  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
09-07 10:32:07.898  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.898  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.898  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.899  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:07.899  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.899  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.899  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 10:32:07.899  3763  3827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:32:07.899  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list,
09-07 10:32:07.899  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.899  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.899  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.900  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 10:32:07.900  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.900  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.900  3763  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
09-07 10:32:07.900  3763  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 390),
09-07 10:32:07.900  3763  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 390)
09-07 10:32:07.900  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:07.902  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:07.902  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.902  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.902  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.902  3763  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
09-07 10:32:07.902  3763  3814 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 10:32:07.903  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.903  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:07.903  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.903  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:07.903  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.903  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.903  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.903  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.903  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.903  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:07.903  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.903  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.903  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.904  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.904  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.904  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.904  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.904  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.905  3763  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 10:32:07.905  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.905  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.905  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:07.905  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.905  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.905  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.905  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.905  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.905  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.905  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.905  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.906  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.906  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.906  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.906  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.906  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.906  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.906  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.907  3763  3814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 10:32:07.907  3763  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 10:32:07.907  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:32:07.907  3763  3814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-07 10:32:07.907  3763  3814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 10:32:07.907  3763  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 10:32:07.907  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:32:07.907  3763  3814 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 10:32:07.907  3763  3814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 10:32:07.907  3763  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-07 10:32:07.907  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:32:07.907  3763  3814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 10:32:07.907  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.908  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.908  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.908  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:07.908  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.908  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.908  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.908  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.908  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.908  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:07.908  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.908  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.908  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.908  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.909  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.909  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.909  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.909  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.909  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.910  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.910  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.910  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
,09-07 10:32:07.910  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.910  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.910  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.910  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.910  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.910  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:07.910  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.910  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.910  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.910  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.910  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.910  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:07.910  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.911  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.911  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.911  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.911  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.911  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
,09-07 10:32:07.911  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.911  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.911  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.911  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.911  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.911  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.911  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.912  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:07.912  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.912  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.912  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.913  3763  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 10:32:07.913  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:07.914  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 10:32:07.914  3763  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 10:32:07.914  3763  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 10:32:07.915  3763  3763 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 10:32:07.915  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 10:32:07.915  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:07.915  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:07.915  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 10:32:07.915  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 10:32:07.915  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 10:32:07.915  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.915  3763  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 10:32:07.915  3763  3763 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 10:32:07.915  3763  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:32:07.915  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.915  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.916  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:07.916  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:07.916  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 10:32:07.916  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.916  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.917  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.917  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:07.917  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:07.917  3763  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 10:32:07.917  3763  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 10:32:07.917  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:07.917  3763  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 10:32:07.917  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.917  3763  3763 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 10:32:07.917  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:07.917  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.917  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.918  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.918  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.918  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.918  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.918  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.918  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.918  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.918  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.918  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 10:32:07.918  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.918  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.919  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.919  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.919  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.919  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.920  3763  3814 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 10:32:07.920  3763  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 10:32:07.920  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 10:32:07.920  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:32:07.920  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.920  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.920  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:07.921  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.921  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.921  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.921  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.921  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 10:32:07.921  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.921  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.921  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.921  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 10:32:07.921  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.921  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.922  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.922  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.922  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.922  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.924  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.925  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:07.925  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:07.925  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.925  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.925  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.925  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
09-07 10:32:07.925  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.925  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.925  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.925  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 10:32:07.925  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.925  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.925  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.926  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.926  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:07.926  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.926  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.926  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:07.926  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:07.927  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:07.927  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:07.927  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.927  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.927  3763  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61864ad not in the list
,09-07 10:32:07.927  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.927  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
09-07 10:32:07.927  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:07.927  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:07.927  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.927  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:07.927  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:07.928  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:07.928  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:07.928  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:07.928  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ddc3e2 not in the list
,09-07 10:32:07.928  3763  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 10:32:07.928  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:32:07.929  3763  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 10:32:07.929  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:32:07.929  3763  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2,
09-07 10:32:07.929  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:32:07.930  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 10:32:07.930  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 10:32:07.930  3763  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 10:32:07.931  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 10:32:07.931  3763  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 10:32:07.931  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 10:32:07.931  3763  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 10:32:07.931  3763  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 10:32:07.931  3763  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 10:32:07.931  3763  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-07 10:32:07.932  3763  3814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 10:32:07.932  3763  3814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 10:32:07.932  3763  3814 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 10:32:07.932  3763  3814 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 10:32:07.932  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:07.932  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4738ff4 added. We now have 2 listener(s)
09-07 10:32:07.932  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:07.933  3763  3814 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 10:32:07.934   874  1932 D WifiService: setWifiEnabled: true pid=3763, uid=10000
09-07 10:32:07.934   874  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 10:32:07.934  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:07.934  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c8d31d added. We now have 3 listener(s)
09-07 10:32:07.934  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:07.937  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:07.937  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c42e992 added. We now have 4 listener(s)
09-07 10:32:07.937  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:07.938  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:07.938  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4941f63 added. We now have 5 listener(s)
09-07 10:32:07.938  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:07.939   874   884 D WifiService: setWifiEnabled: false pid=3763, uid=10000
09-07 10:32:07.939   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:32:07.943  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:07.943  2685  2701 D BluetoothAdapterState: Current state: ON, message: 23
09-07 10:32:07.943  2685  2701 D BluetoothAdapterProperties: Setting state to 13
09-07 10:32:07.943  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
09-07 10:32:07.948  2685  2701 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 10:32:07.948  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.948  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:07.949  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:07.949  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.949  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK,
,09-07 10:32:07.950  2685  2701 I BluetoothAdapterState: Entering PendingCommandState
,09-07 10:32:07.951  2685  2705 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:32:07.951  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.951  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 10:32:07.952  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.953  2685  2685 D HeadsetService: Received stop request...Stopping profile...
09-07 10:32:07.953  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 10:32:07.955  1364  1384 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:07.955   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 10:32:07.955   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 10:32:07.955   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 10:32:07.955  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-07 10:32:07.955  1951  1968 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:07.956   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:32:07.956   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:07.957   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:07.957  2685  2685 D A2dpService: Received stop request...Stopping profile...
09-07 10:32:07.957   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:07.957  2685  2837 D A2dpStateMachine: Exit Disconnected: -1
09-07 10:32:07.959  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:07.959  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:07.959   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.959  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:07.959  2685  2685 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:07.959  2685  2685 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:07.959  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:07.959  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:07.960  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:07.960  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.961   874  1876 D DhcpClient: Clearing IP address
09-07 10:32:07.961   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 10:32:07.961  2685  2685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 10:32:07.961  2685  2685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:32:07.961  2685  2685 V BluetoothAdapterState: isTurningOff,()=true
09-07 10:32:07.961  2685  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:07.961  2685  2685 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:07.961  2685  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:07.961  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:07.961  2685  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:07.961  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:07.962  2685  2705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 10:32:07.962  2685  2705 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 10:32:07.962  2685  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:07.962  2685  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:07.962  2685  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:32:07.962  2685  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:32:07.962  2685  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:32:07.962  2685  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:32:07.963  2685  2705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 10:32:07.963  2685  2685 D HidService: Received stop request...Stopping profile...
09-07 10:32:07.963  2685  2685 D HidService: Stopping Bluetooth HidService
09-07 10:32:07.964  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-07 10:32:07.964  1364  1364 D HidProfile: Bluetooth service disconnected
09-07 10:32:07.964  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:07.965  2685  2685 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:07.965  2685  2685 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:07.965  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:07.965  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:07.966  2685  2685 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 10:32:07.966  1506  2475 V NativeCrypto: Read error: ssl=0x9b37c200: I/O error during system call, Connection timed out
09-07 10:32:07.966  2685  2705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 10:32:07.966  2685  2685 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 10:32:07.967  2685  2685 D HealthService: Received stop request...Stopping profile...
09-07 10:32:07.967   373   872 D CommandListener: Setting iface cfg
09-07 10:32:07.968  1506  2475 V NativeCrypto: SSL shutdown failed: ssl=0x9b37c200: I/O error during system call, Broken pipe
,09-07 10:32:07.969   874   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-07 10:32:07.969   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 10:32:07.970   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 10:32:07.970   874  1866 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-07 10:32:07.971   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 10:32:07.972   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 10:32:07.972   396   396 E Parcel  : Reading a NULL string not supported here.
,09-07 10:32:07.977  2685  2685 D PanService: Received stop request...Stopping profile...
09-07 10:32:07.977   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:07.978   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-07 10:32:07.979   874  1866 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-07 10:32:07.981  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 10:32:07.981  1364  1364 D PanProfile: Bluetooth service disconnected
09-07 10:32:07.983  2685  2685 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:07.983  2685  2685 V BluetoothAdapterState: isTurningOn()=false,
09-07 10:32:07.983  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:07.983  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:07.983  2685  2685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 10:32:07.983  2685  2705 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 10:32:07.983  2685  2685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-07 10:32:07.984  2685  2685 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 10:32:07.984  2685  2685 D BluetoothMapService: stop()
,09-07 10:32:07.985   874  1892 D DhcpClient: Receive thread stopped
,09-07 10:32:07.989  2685  2685 D BluetoothMapAppObserver: deinitObservers()
,09-07 10:32:07.989  2685  2685 D BluetoothMapAppObserver: removeReceiver()
09-07 10:32:07.990   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 10:32:07.992   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 10:32:07.993  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:07.993  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:07.994  2685  2685 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:07.995  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:07.995  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:07.995  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:07.995  2685  2685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 10:32:07.996  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:07.996  2685  2685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 10:32:07.996  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:07.997  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:07.997  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:07.998  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:07.998  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:07.998  2685  2685 D BluetoothMapService: MAP Service closeService in
,09-07 10:32:07.998  2685  2685 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 10:32:07.998  2685  2685 D ObexServerSockets0: shutdown(block = true)
09-07 10:32:07.999  2685  2866 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 10:32:07.999  1364  1364 D BluetoothMap: Proxy object disconnected
,09-07 10:32:07.999  1364  1364 D MapProfile: Bluetooth service disconnected
09-07 10:32:07.999  2685  2685 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 10:32:07.999  2685  2829 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 10:32:07.999  2685  2867 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 10:32:07.999  2685  2685 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 10:32:07.999  2685  2685 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:07.999  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:07.999  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:07.999  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:07.999  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 10:32:08.000  2685  2685 D BluetoothMapService: cleanup()
,09-07 10:32:08.000  2685  2701 D BluetoothAdapterProperties: Setting state to 15
,09-07 10:32:08.000  2685  2685 D BluetoothMapService: MAP Service closeService in
,09-07 10:32:08.000  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 10:32:08.000  2685  2701 I BluetoothAdapterState: Entering BleOnState
09-07 10:32:08.001  2027  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:32:08.004   874   887 I ActivityManager: Start proc 3835:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-07 10:32:08.007   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:08.007   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:08.007   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:32:08.007  2685  2685 I BtOppRfcommListener: stopping Accept Thread
09-07 10:32:08.007  2685  3417 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:32:08.007  2685  3417 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 10:32:08.009  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.010  1364  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-07 10:32:08.011  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.011  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 10:32:08.012  1364  2050 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 10:32:08.012  1364  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:08.012  1364  1377 D BluetoothPan: onBluetoothStateChange on: false
09-07 10:32:08.013  1364  2050 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:32:08.013   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 10:32:08.013   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:08.013  1951  2111 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:08.014  2685  2701 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 10:32:08.014  2685  2701 D BluetoothAdapterProperties: Setting state to 16
09-07 10:32:08.014  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 10:32:08.015  2685  2701 D BluetoothAdapterProperties: onBleDisable
09-07 10:32:08.015  2685  2701 I BluetoothAdapterState: Entering PendingCommandState
09-07 10:32:08.015  2685  2702 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 10:32:08.016  2685  2800 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 10:32:08.016  2685  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:08.016  2685  2705 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:32:08.017  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.018  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.020  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.021  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.047   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 10:32:08.048   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-07 10:32:08.048   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:32:08.048  3835  3835 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 10:32:08.049   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 10:32:08.052  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.052  3367  3367 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1db0f1d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-07 10:32:08.053  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.086  3835  3835 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 10:32:08.093   373   872 E Netd    : netlink response contains error (No such file or directory)
09-07 10:32:08.093   874  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 10:32:08.093   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 10:32:08.107   874  3066 I ActivityManager: Start proc 3865:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 10:32:08.110   874  1952 I ActivityManager: Killing 3367:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 10:32:08.166  3865  3865 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 10:32:08.180  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:08.185  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:08.186   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa774cd:true
,09-07 10:32:08.216   874  1952 I ActivityManager: Start proc 3877:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-07 10:32:08.218  2685  2705 I bt_hci  : shut_down
,09-07 10:32:08.224  2685  2709 I bt_vendor: low_power_mode_cb
,09-07 10:32:08.225  2685  2709 D bt_hwcfg: hw_epilog_process
,09-07 10:32:08.229  3865  3865 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 10:32:08.232  3865  3865 D BluetoothMap: Create BluetoothMap proxy object
,09-07 10:32:08.237  3865  3865 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 10:32:08.245  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:08.252  2685  2709 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 10:32:08.252  2685  2709 I bt_vendor: epilog_cb
09-07 10:32:08.252  2685  2709 I bt_hci  : epilog_finished_callback
,09-07 10:32:08.253   874   884 I ActivityManager: Killing 3544:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-07 10:32:08.276  3877  3877 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 10:32:08.308  2685  2705 I bt_hci_h4: hal_close
,09-07 10:32:08.308  2685  2705 I bt_userial_vendor: device fd = 51 close
,09-07 10:32:08.418  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:08.439  2685  2702 D bt_stack_manager: event_shut_down_stack finished.
,09-07 10:32:08.440  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 10:32:08.443  2685  2701 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 10:32:08.443  2685  2685 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 10:32:08.445  2685  2685 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 10:32:08.445  2685  2685 D BtGatt.GattService: stop()
,09-07 10:32:08.445  2685  2685 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 10:32:08.446  2685  2685 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:08.446  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:08.446  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:08.446  2685  2685 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 10:32:08.447  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 10:32:08.447  2685  2701 D BluetoothAdapterProperties: Setting state to 10
09-07 10:32:08.447  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 10:32:08.448  2685  2701 I BluetoothAdapterState: Entering OffState
09-07 10:32:08.448   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 10:32:08.456  2685  2685 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 10:32:08.456  2685  2685 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 10:32:08.456  2685  2702 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 10:32:08.456  2685  2685 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 10:32:08.460  2685  2702 D bt_stack_manager: event_clean_up_stack finished.
,09-07 10:32:08.478  2685  2685 I art     : System.exit called, status: 0
,09-07 10:32:08.478  2685  2685 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 10:32:08.488  3877  3877 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.488  3877  3877 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.488  3877  3877 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.488  3877  3877 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.488  3877  3877 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.488  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.489  3877  3877 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.489  3877  3877 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.489  3877  3877 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.489  3877  3877 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:08.489  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 10:32:08.494  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:08.517  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:08.519   874  1958 I ActivityManager: Killing 3434:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 10:32:08.568   874   885 I ActivityManager: Process com.android.bluetooth (pid 2685) has died
,09-07 10:32:08.573  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:08.596   874  1701 I ActivityManager: Start proc 3909:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-07 10:32:08.721  3909  3909 D AdapterServiceConfig: Adding HeadsetService
,09-07 10:32:08.721  3909  3909 D AdapterServiceConfig: Adding A2dpService
09-07 10:32:08.721  3909  3909 D AdapterServiceConfig: Adding HidService
09-07 10:32:08.721  3909  3909 D AdapterServiceConfig: Adding HealthService
,09-07 10:32:08.721  3909  3909 D AdapterServiceConfig: Adding PanService
09-07 10:32:08.721  3909  3909 D AdapterServiceConfig: Adding GattService
09-07 10:32:08.722  3909  3909 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 10:32:08.740  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 10:32:08.743  1705  1705 D SystemUpdateService: onCreate
,09-07 10:32:08.745  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 10:32:08.752  1705  3923 I SystemUpdateService: active receiver: enabled
,09-07 10:32:08.774  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 10:32:08.774  1705  3923 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 10:32:08.778  1705  3923 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 10:32:08.778  1705  3923 I SystemUpdateService: now status is 0 (complete)
09-07 10:32:08.778  1705  3923 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 10:32:08.778  1705  3923 I SystemUpdateService: file has been verified
,09-07 10:32:08.778  1705  3923 I SystemUpdateService: OTA package size = 12249756
09-07 10:32:08.779  1705  2439 I iu.UploadsManager: num queued entries: 0
09-07 10:32:08.779  1705  2439 I iu.UploadsManager: num updated entries: 0
,09-07 10:32:08.780  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 10:32:08.781  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 10:32:08.787  1705  2439 I iu.SyncManager: NEXT; no task
,09-07 10:32:08.787  1705  3923 I SystemUpdateService: showing system update notification
,09-07 10:32:08.806   874   884 I ActivityManager: Start proc 3925:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 10:32:08.808  1705  1705 D SystemUpdateService: onDestroy
,09-07 10:32:08.842  3877  3894 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 10:32:08.850  3925  3925 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 10:32:08.852  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:08.858  3925  3925 D SprintDMHelper: simOperator: 
09-07 10:32:08.858  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 10:32:08.865   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aa527a9:true
,09-07 10:32:08.871   874  1928 I ActivityManager: Start proc 3937:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 10:32:08.873   874  1928 I ActivityManager: Killing 3485:android.process.acore/u0a5 (adj 15): empty #17
,09-07 10:32:09.027   874  1952 I ActivityManager: Start proc 3952:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 10:32:09.037   874  1700 I ActivityManager: Killing 3649:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 10:32:09.105  3952  3952 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 10:32:09.165  3952  3952 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 10:32:09.165  3952  3952 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 10:32:09.165  3952  3952 I GAv4    :   adb logcat -s GAv4
,09-07 10:32:09.181  3952  3952 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:32:09.188  3952  3952 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:32:09.224  3952  3969 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:32:09.329  3952  3952 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 10:32:09.371  3952  3952 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 10:32:09.379  3952  3952 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8059-8062)
09-07 10:32:09.380  3952  3952 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 10:32:09.396  3952  3952 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {782f98d}
,09-07 10:32:09.397  3952  3952 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 10:32:09.399  3952  3952 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 10:32:09.411  3952  3952 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 10:32:09.413  3952  3952 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 10:32:09.427  3952  3952 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 10:32:09.441  3952  3952 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 10:32:09.441  3952  3952 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 10:32:09.441  3952  3952 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 10:32:09.441  3952  3952 I Adreno  : Build Date                       : 10/20/15
09-07 10:32:09.441  3952  3952 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 10:32:09.441  3952  3952 I Adreno  : Local Branch                     : M14
09-07 10:32:09.441  3952  3952 I Adreno  : Remote Branch                    : 
09-07 10:32:09.441  3952  3952 I Adreno  : Remote Branch                    : 
09-07 10:32:09.441  3952  3952 I Adreno  : Reconstruct Branch               : 
,09-07 10:32:09.508  3952  3952 I NSApplication: Starting up...
,09-07 10:32:09.517  3952  3998 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 10:32:09.550   874   884 I ActivityManager: Start proc 4003:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 10:32:09.553   874   884 I ActivityManager: Killing 3666:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 10:32:09.622  4003  4003 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 10:32:09.805   874  1701 I ActivityManager: Killing 2192:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 10:32:10.952   874  1932 D WifiService: setWifiEnabled: true pid=3763, uid=10000
,09-07 10:32:10.952   874  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:32:10.967   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-07 10:32:10.974  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:10.974  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:10.974  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:10.975  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:10.978  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:10.978  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:10.979  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:10.979  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:11.012   874  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-07 10:32:11.013   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 10:32:11.014   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 10:32:11.015   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 10:32:11.016   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 10:32:11.016   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 10:32:11.016   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 10:32:11.033   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 10:32:11.033   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.25 rxSuccessRate=8.75 delta 1000 -> 994
,09-07 10:32:11.035   373   872 D CommandListener: Setting iface cfg
,09-07 10:32:11.036   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 10:32:11.036   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 10:32:11.042   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 10:32:11.042   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:11.051   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 10:32:11.051   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 10:32:11.081   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 10:32:11.102   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 10:32:11.105  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 10:32:11.529  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 10:32:11.581  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 10:32:11.582  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 10:32:11.587   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 10:32:11.603   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 10:32:11.604   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 10:32:11.605   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:11.631   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-07 10:32:11.642   373   872 D CommandListener: Setting iface cfg
,09-07 10:32:11.644   874  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 10:32:11.666   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 10:32:11.666   874  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-07 10:32:11.672   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 10:32:11.691   874  4029 D DhcpClient: Receive thread started
,09-07 10:32:11.778   874  1309 E native  : do suspend false
,09-07 10:32:11.801   874  1876 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 10:32:11.911   874  4029 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172692, domain null
,09-07 10:32:11.912   874  1876 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172692 seconds
,09-07 10:32:11.916   874  1876 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 10:32:12.021   874  4029 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 10:32:12.023   874  1876 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 10:32:12.027   373   872 D CommandListener: Setting iface cfg
,09-07 10:32:12.040   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 10:32:12.040   874  1876 D DhcpClient: Scheduling renewal in 86399s
,09-07 10:32:12.054   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 10:32:12.057   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 10:32:12.060   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 10:32:12.063   874  1311 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 10:32:12.079   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 10:32:12.118   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 10:32:12.118   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 10:32:12.120   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 10:32:12.121   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 10:32:12.122   874  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 10:32:12.136   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 10:32:12.142   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 10:32:12.142   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 10:32:12.143   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 10:32:12.143   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 10:32:12.143   874  1311 D ConnectivityService:    accepting network in place of null
,09-07 10:32:12.144   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 10:32:12.144   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 10:32:12.172   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 10:32:12.189   874  4028 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130871, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 10:32:12.204   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 10:32:12.212   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 10:32:12.212   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:12.234   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 10:32:12.235   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 10:32:12.246  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:12.246  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:12.246  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:12.246  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:12.248  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:12.248  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:12.248  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:12.248  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:12.256  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 10:32:12.259  1705  1705 D SystemUpdateService: onCreate
,09-07 10:32:12.262  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 10:32:12.265  1705  4039 I SystemUpdateService: active receiver: enabled
,09-07 10:32:12.269  1705  4039 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 10:32:12.271  1705  4039 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 10:32:12.271  1705  4039 I SystemUpdateService: now status is 0 (complete)
09-07 10:32:12.272  1705  4039 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 10:32:12.272  1705  4039 I SystemUpdateService: file has been verified
09-07 10:32:12.272  1705  4039 I SystemUpdateService: OTA package size = 12249756
,09-07 10:32:12.280   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 10:32:12.282  1705  4039 I SystemUpdateService: showing system update notification
,09-07 10:32:12.283  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 10:32:12.288  1705  2439 I iu.UploadsManager: num queued entries: 0
,09-07 10:32:12.288  1705  2439 I iu.UploadsManager: num updated entries: 0
09-07 10:32:12.289  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 10:32:12.289  1705  2439 I iu.SyncManager: NEXT; no task
09-07 10:32:12.289  1705  4043 I MDM     : [171] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 10:32:12.289  1705  4043 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 10:32:12.290  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 10:32:12.291  1705  4043 V GoogleAuthProtoRequest: [171] a.<init>: mAccountName set to: thalitester@gmail.com
09-07 10:32:12.293  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:12.296  1705  1705 D SystemUpdateService: onDestroy
,09-07 10:32:12.298  3925  3925 D SprintDMHelper: simOperator: 
,09-07 10:32:12.298  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 10:32:12.299  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 10:32:12.300  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 10:32:12.334  1506  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 10:32:12.334  1506  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 10:32:12.334  1506  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:12.334  1506  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:12.347  1705  4043 E MDM     : [171] SitrepService.a: Error sending sitrep.
,09-07 10:32:12.358   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 08:32:12 GMT], X-Android-Received-Millis=[1473237132358], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473237132324]}
,09-07 10:32:12.359   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 10:32:12.359   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-07 10:32:12.359   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 10:32:12.361   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 10:32:12.373  3007  4049 V KeepSync: Connecting to GoogleApiClient
,09-07 10:32:12.373   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 10:32:12.408  1506  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 10:32:12.408  1506  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 10:32:12.408  1506  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:12.408  1506  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:12.426  1705  4053 V BaseAuthAsyncOperation: access token request failed
,09-07 10:32:12.430  3007  4049 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 10:32:12.435  2284  4045 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 10:32:12.462  1506  2383 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 10:32:12.462  1506  2383 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 10:32:12.462  1506  2383 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 10:32:12.462  1506  2383 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:12.478  2985  4048 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 10:32:12.478  2985  4048 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jdm.a(PG:82)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jcs.o(PG:406)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jcn.a(PG:1379)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jcs.i(PG:143)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at blb.a(PG:3937)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at czp.a(PG:18188)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at czp.a(PG:9081)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at czq.run(PG:1686)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 10:32:12.478  2985  4048 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jdj.a(PG:4091)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jdj.a(PG:1125)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jdm.a(PG:77)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	... 12 more
09-07 10:32:12.478  2985  4048 E HttpOperation: Caused by: faj: BadAuthentication
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at fal.a(PG:38)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	at jdj.a(PG:4089)
09-07 10:32:12.478  2985  4048 E HttpOperation: 	... 14 more
,09-07 10:32:12.506  1506  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 10:32:12.506  1506  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 10:32:12.506  1506  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:12.506  1506  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:12.517  1506  2383 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 10:32:12.517  1506  2383 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 10:32:12.518  1506  2383 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:12.518  1506  2383 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:12.535  2985  4048 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 10:32:12.535  2985  4048 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jdm.a(PG:82)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jcs.o(PG:406)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jcn.a(PG:1379)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jcs.i(PG:143)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at hec.a(PG:42)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at hee.a(PG:102)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at czr.a(PG:65)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at kka.a(PG:108)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at czp.a(PG:19176)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at czp.a(PG:9081)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at czq.run(PG:1686)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 10:32:12.535  2985  4048 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jdj.a(PG:4091)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jdj.a(PG:1125)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jdm.a(PG:77)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	... 15 more
09-07 10:32:12.535  2985  4048 E HttpOperation: Caused by: faj: BadAuthentication
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at fal.a(PG:38)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	at jdj.a(PG:4089)
09-07 10:32:12.535  2985  4048 E HttpOperation: 	... 17 more
,09-07 10:32:12.536  2985  4048 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 10:32:12.536  2985  4048 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at hec.a(PG:42)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at hee.a(PG:102)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at czr.a(PG:65)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at kka.a(PG:108)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	... 15 more
09-07 10:32:12.536  2985  4048 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at fal.a(PG:38)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 10:32:12.536  2985  4048 E ExperimentLoader: 	... 17 more
,09-07 10:32:12.548  3007  4049 E KeepSync: IOException
09-07 10:32:12.548  3007  4049 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 10:32:12.548  3007  4049 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 10:32:12.548  3007  4049 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 10:32:12.548  3007  4049 E KeepSync: 	... 10 more
09-07 10:32:12.548  3007  4049 W KeepSync: Sync result 2
,09-07 10:32:12.554   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127554, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 10:32:12.673   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 127097, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 10:32:13.212   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 10:32:13.856   874  1952 I ActivityManager: Killing 3687:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 10:32:13.963   874  1700 D WifiService: setWifiEnabled: false pid=3763, uid=10000
,09-07 10:32:13.963   874  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:32:13.993  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 10:32:13.997   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 10:32:13.997   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 10:32:13.997   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 10:32:13.998   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:14.013   874  1876 D DhcpClient: Clearing IP address
,09-07 10:32:14.015   373   872 D CommandListener: Setting iface cfg
,09-07 10:32:14.018   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:14.020   874  4029 D DhcpClient: Receive thread stopped
,09-07 10:32:14.022  1506  4055 V NativeCrypto: Read error: ssl=0x9b37c200: I/O error during system call, Connection timed out
,09-07 10:32:14.025  1506  4055 V NativeCrypto: SSL shutdown failed: ssl=0x9b37c200: I/O error during system call, Broken pipe
09-07 10:32:14.025   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 10:32:14.025   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-07 10:32:14.037   396   396 E Parcel  : Reading a NULL string not supported here.
,09-07 10:32:14.044   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 10:32:14.045   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 10:32:14.048   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-07 10:32:14.049   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:14.061   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 10:32:14.063  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:14.063  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:14.063  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:14.063  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:14.064  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:14.064  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:14.064  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:14.064  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:14.065   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 10:32:14.070  2027  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:14.086   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 10:32:14.105   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 10:32:14.106   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 10:32:14.106   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:14.109   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 10:32:14.112  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:14.113  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:14.120  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 10:32:14.124  1705  1705 D SystemUpdateService: onCreate
,09-07 10:32:14.126  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 10:32:14.140  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 10:32:14.150  1705  2439 I iu.UploadsManager: num queued entries: 0
,09-07 10:32:14.151  1705  2439 I iu.UploadsManager: num updated entries: 0
,09-07 10:32:14.153  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 10:32:14.154  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 10:32:14.156  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:14.162  3925  3925 D SprintDMHelper: simOperator: 
,09-07 10:32:14.162  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 10:32:14.177  1705  4066 I SystemUpdateService: active receiver: enabled
,09-07 10:32:14.179  2284  4071 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 10:32:14.184   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 10:32:14.185   874  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 10:32:14.190  1705  2439 I iu.SyncManager: NEXT; no task
,09-07 10:32:14.195  1705  4066 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 10:32:14.201  1705  4066 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-07 10:32:14.202  1705  4066 I SystemUpdateService: now status is 0 (complete)
09-07 10:32:14.202  1705  4066 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 10:32:14.202  1705  4066 I SystemUpdateService: file has been verified
09-07 10:32:14.202  1705  4066 I SystemUpdateService: OTA package size = 12249756
,09-07 10:32:14.204  3952  3952 I art     : Waiting for a blocking GC DisableMovingGc
,09-07 10:32:14.208  3952  3952 I art     : Starting a blocking GC DisableMovingGc
,09-07 10:32:14.236  1705  4066 I SystemUpdateService: showing system update notification
,09-07 10:32:14.246  1705  1705 D SystemUpdateService: onDestroy
,09-07 10:32:17.019   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e4e74:true
09-07 10:32:17.019  3909  3909 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 10:32:17.024  3909  3909 I bt_bluedroid: init
,09-07 10:32:17.025  3909  4075 I BluetoothAdapterState: Entering OffState
,09-07 10:32:17.030  3909  4076 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 10:32:17.031  3909  4076 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 10:32:17.031  3909  4076 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 10:32:17.031  3909  4076 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 10:32:17.033  3909  3909 I bt_bluedroid: get_profile_interface socket
,09-07 10:32:17.035  3909  3909 I bt_bluedroid: get_profile_interface sdp
,09-07 10:32:17.038  3909  4079 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 10:32:17.040  3909  4079 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 10:32:17.042  3909  3920 I bt_bluedroid: config_hci_snoop_log
,09-07 10:32:17.045   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 10:32:17.057  3909  4075 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 10:32:17.058  3909  4075 D BluetoothAdapterProperties: Setting state to 14
09-07 10:32:17.058  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 10:32:17.062  3909  4075 D BluetoothBondStateMachine: make
,09-07 10:32:17.067  3909  4080 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 10:32:17.078  3909  4075 I BluetoothAdapterState: Entering PendingCommandState
,09-07 10:32:17.079  3909  3909 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 10:32:17.086  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:17.088  3909  3909 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 10:32:17.090  3909  3909 D BtGatt.GattService: Received start request. Starting profile...
,09-07 10:32:17.090  3909  3909 D BtGatt.GattService: start()
,09-07 10:32:17.090  3909  3909 I bt_bluedroid: get_profile_interface gatt
09-07 10:32:17.092  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:17.093  3909  3909 D BtGatt.AdvertiseManager: advertise manager created
,09-07 10:32:17.111  3909  3909 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:17.111  3909  3909 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:17.111  3909  3909 V BluetoothAdapterState: isBleTurningOn()=true
09-07 10:32:17.112  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:17.114  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 10:32:17.115  3909  4075 I bt_bluedroid: enable
09-07 10:32:17.116  3909  4076 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 10:32:17.117  3909  4076 I bt_hci  : start_up
,09-07 10:32:17.141  3909  4076 I bt_vendor: alloc value 0xb3939189
,09-07 10:32:17.141  3909  4076 I bt_vendor: init
09-07 10:32:17.142  3909  4076 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 10:32:17.142  3909  4076 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 10:32:17.252  3909  4076 D bt_hci  : start_up starting async portion
,09-07 10:32:17.252  3909  4083 I bt_hci  : event_finish_startup
,09-07 10:32:17.253  3909  4083 I bt_hci_h4: hal_open
09-07 10:32:17.253  3909  4083 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 10:32:17.263  3909  4083 I bt_userial_vendor: device fd = 51 open
,09-07 10:32:17.294  3909  4083 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 10:32:17.326  3909  4083 D bt_hwcfg: Chipset BCM4354A2
,09-07 10:32:17.326  3909  4083 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 10:32:17.327  3909  4083 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 10:32:17.932  3909  4083 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 10:32:17.934  3909  4083 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 10:32:17.935  3909  4083 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 10:32:18.052  3909  4083 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 10:32:18.054  3909  4083 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 10:32:18.081  3909  4083 I bt_hwcfg: vendor lib fwcfg completed
,09-07 10:32:18.081  3909  4083 I bt_vendor: firmware callback
09-07 10:32:18.082  3909  4083 I bt_hci  : firmware_config_callback
,09-07 10:32:18.095  3909  4085 I bt_btu  : btu_task pending for preload complete event
,09-07 10:32:18.095  3909  4085 I bt_btu_task: Bluetooth chip preload is complete
09-07 10:32:18.095  3909  4085 I bt_btu  : btu_task received preload complete event
,09-07 10:32:18.107  3909  4085 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 10:32:18.107  3909  4085 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 10:32:18.108  3909  4085 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 10:32:18.108  3909  4085 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 10:32:18.108  3909  4085 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 10:32:18.108  3909  4085 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 10:32:18.109  3909  4085 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-07 10:32:18.109  3909  4085 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 10:32:18.109  3909  4085 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 10:32:18.110  3909  4085 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 10:32:18.110  3909  4085 I         : BTE_InitTraceLevels -- TRC_SDP
,09-07 10:32:18.110  3909  4085 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 10:32:18.110  3909  4085 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 10:32:18.111  3909  4085 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-07 10:32:18.111  3909  4085 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 10:32:18.247  3909  4085 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,09-07 10:32:18.248  3909  4085 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,09-07 10:32:18.259  3909  4079 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 10:32:18.260  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 10:32:18.261  3909  4079 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 10:32:18.266  3909  4079 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 10:32:18.271  3909  4079 D BluetoothAdapterProperties: Scan Mode:20
,09-07 10:32:18.273  3909  4079 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 10:32:18.273  3909  4079 D bt_hci  : do_postload posting postload work item
,09-07 10:32:18.274  3909  4083 I bt_hci  : event_postload
09-07 10:32:18.274  3909  4083 I bt_vendor: sco_config_cb
,09-07 10:32:18.274  3909  4083 I bt_hci  : sco_config_callback postload finished.
,09-07 10:32:18.277  3909  4079 D bt_bte_conf: Device ID record 1 : primary
,09-07 10:32:18.278  3909  4079 D bt_bte_conf:   vendorId            = 000f
,09-07 10:32:18.278  3909  4079 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 10:32:18.278  3909  4079 D bt_bte_conf:   product             = 1200
,09-07 10:32:18.278  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.278  3909  4079 D bt_bte_conf:   version             = 1436
,09-07 10:32:18.278  3909  4079 D bt_bte_conf:   clientExecutableURL = 
,09-07 10:32:18.279  3909  4079 D bt_bte_conf:   serviceDescription  = 
09-07 10:32:18.279  3909  4079 D bt_bte_conf:   documentationURL    = 
,09-07 10:32:18.280  3909  4079 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 10:32:18.280  3909  4076 D bt_stack_manager: event_start_up_stack finished
09-07 10:32:18.283  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 10:32:18.283  3909  4075 D BluetoothAdapterProperties: Setting state to 15
,09-07 10:32:18.284  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 10:32:18.287  3909  4075 I BluetoothAdapterState: Entering BleOnState
09-07 10:32:18.288  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:18.289  3909  4083 I bt_vendor: low_power_mode_cb
,09-07 10:32:18.293  3909  4075 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 10:32:18.293  3909  4075 D BluetoothAdapterProperties: Setting state to 11
09-07 10:32:18.293  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 10:32:18.305  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:18.306  3909  3909 D HeadsetService: Received start request. Starting profile...
,09-07 10:32:18.310  3909  3909 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 10:32:18.311  3909  3909 D HeadsetStateMachine: make
09-07 10:32:18.311  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.313  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.322  3909  4075 I BluetoothAdapterState: Entering PendingCommandState
,09-07 10:32:18.322  3909  3909 D HeadsetStateMachine: max_hf_connections = 1
,09-07 10:32:18.322  3909  3909 I bt_bluedroid: get_profile_interface handsfree
09-07 10:32:18.323  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 10:32:18.323  3909  4079 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 10:32:18.327  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:18.331  3909  3909 D A2dpService: Received start request. Starting profile...
,09-07 10:32:18.332  3909  3909 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 10:32:18.332  3909  3909 I bt_bluedroid: get_profile_interface avrcp
,09-07 10:32:18.339  3909  3909 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 10:32:18.339  3909  3909 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 10:32:18.339  3909  3909 D A2dpStateMachine: make
,09-07 10:32:18.341  3909  3909 I bt_bluedroid: get_profile_interface a2dp
09-07 10:32:18.342  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 10:32:18.342  3909  4094 D A2dpStateMachine: Enter Disconnected: -2
,09-07 10:32:18.345  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:18.345  3909  3909 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 10:32:18.346  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:18.347  3909  3909 D HidService: Received start request. Starting profile...
,09-07 10:32:18.347  3909  3909 I bt_bluedroid: get_profile_interface hidhost
,09-07 10:32:18.347  3909  3909 D HidService: setHidService(): set to: null
09-07 10:32:18.347  3909  4079 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
09-07 10:32:18.348  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-07 10:32:18.348  3909  3909 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 10:32:18.349  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
09-07 10:32:18.349  3865  3865 D BluetoothInputDevice: Proxy object connected
,09-07 10:32:18.349  3909  3909 D HealthService: Received start request. Starting profile...
09-07 10:32:18.350  3865  3865 D HidProfile: Bluetooth service connected
,09-07 10:32:18.351  3909  3909 I bt_bluedroid: get_profile_interface health
,09-07 10:32:18.353  3909  3909 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 10:32:18.354  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:18.355  3865  3865 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 10:32:18.355  3909  3909 D PanService: Received start request. Starting profile...
09-07 10:32:18.356  3909  3909 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 10:32:18.356  3909  3909 I bt_bluedroid: get_profile_interface pan
09-07 10:32:18.356  3865  3865 D PanProfile: Bluetooth service connected
09-07 10:32:18.356  3909  4079 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 10:32:18.358  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:18.359  3909  3909 D BluetoothMapService: Received start request. Starting profile...
09-07 10:32:18.359  3909  3909 D BluetoothMapService: start()
,09-07 10:32:18.362  3909  3909 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 10:32:18.362  3909  3909 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 10:32:18.362  3909  3909 D BluetoothMapAppObserver: createReceiver()
,09-07 10:32:18.363  3909  3909 D BluetoothMapAppObserver: initObservers()
09-07 10:32:18.363  3909  3909 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 10:32:18.365  3865  3865 D BluetoothMap: Proxy object connected
,09-07 10:32:18.366  3865  3865 D MapProfile: Bluetooth service connected
09-07 10:32:18.366  3865  3865 D BluetoothMap: getConnectedDevices()
09-07 10:32:18.367  3865  3865 D BluetoothMap: Bluetooth is Not enabled
,09-07 10:32:18.371  3909  4092 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 10:32:18.371  3909  3909 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:18.371  3909  3909 V BluetoothAdapterState: isTurningOn()=true
,09-07 10:32:18.371  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:18.371  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:18.373  3909  3909 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:18.373  3909  3909 V BluetoothAdapterState: isTurningOn()=true
,09-07 10:32:18.373  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:18.373  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:18.375  3909  3909 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:18.375  3909  3909 V BluetoothAdapterState: isTurningOn()=true
,09-07 10:32:18.375  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:18.375  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isTurningOn()=true
,09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:18.376  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:18.377  3909  3909 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:18.377  3909  3909 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:18.377  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:18.377  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:18.377  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 10:32:18.377  3909  4075 D BluetoothAdapterProperties: ScanMode =  20
09-07 10:32:18.377  3909  4075 D BluetoothAdapterProperties: State =  11
09-07 10:32:18.378  3909  4075 D BluetoothAdapterProperties: Setting state to 12
,09-07 10:32:18.378  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 10:32:18.379  3909  4075 I BluetoothAdapterState: Entering OnState
09-07 10:32:18.379   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:18.379   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 10:32:18.379   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:32:18.380  3909  4079 D BluetoothAdapterProperties: Scan Mode:21
09-07 10:32:18.381  3909  4079 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:32:18.382  3865  3876 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 10:32:18.383  1364  1377 D BluetoothMap: onBluetoothStateChange: up=true
09-07 10:32:18.383   874   874 D BluetoothA2dp: Proxy object connected
09-07 10:32:18.385  1364  1364 D BluetoothMap: Proxy object connected
09-07 10:32:18.385  1364  1364 D MapProfile: Bluetooth service connected
09-07 10:32:18.385  1364  1364 D BluetoothMap: getConnectedDevices()
,09-07 10:32:18.385  3865  3875 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 10:32:18.385  1364  2050 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:18.387  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:18.392  3865  3876 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 10:32:18.392  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:18.393  3909  3909 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 10:32:18.395  3909  3909 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 10:32:18.395  1364  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:18.397  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:18.397  1364  1364 D BluetoothInputDevice: Proxy object connected
09-07 10:32:18.398  1364  2050 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 10:32:18.398  1364  1364 D HidProfile: Bluetooth service connected
,09-07 10:32:18.398  3865  3875 D BluetoothPan: onBluetoothStateChange on: true
09-07 10:32:18.398  1364  1384 D BluetoothPan: onBluetoothStateChange on: true
,09-07 10:32:18.399  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 10:32:18.400  1364  1364 D PanProfile: Bluetooth service connected
,09-07 10:32:18.400  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:32:18.400  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:18.401  1364  1364 D BluetoothA2dp: Proxy object connected
09-07 10:32:18.401   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:18.402  1951  2254 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 10:32:18.402  3909  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:32:18.403   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 10:32:18.405  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:18.406  3865  3865 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 10:32:18.406  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:18.407  3909  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:32:18.409  3909  3909 D ObexServerSockets: Succeed to create listening sockets 
09-07 10:32:18.409  3909  3909 D ObexServerSockets0: startAccept()
09-07 10:32:18.409  3909  3909 D ObexServerSockets0: prepareForNewConnect()
09-07 10:32:18.409  3865  3865 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 10:32:18.411  3909  3909 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 10:32:18.411  3909  3909 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 10:32:18.411  3909  4100 D ObexServerSockets0: Accepting socket connection...
09-07 10:32:18.411  3909  3909 D BluetoothMapService: onReceive
09-07 10:32:18.411  3909  3909 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:18.412  3909  3909 D BluetoothMapService: STATE_ON
09-07 10:32:18.412  3909  4101 D ObexServerSockets0: Accepting socket connection...
,09-07 10:32:18.417  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:18.420  3865  3865 D BluetoothA2dp: Proxy object connected
09-07 10:32:18.423  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:18.429  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:18.435  1364  1364 D BluetoothPbap: Proxy object connected
,09-07 10:32:18.435  1364  1364 D PbapServerProfile: Bluetooth service connected
09-07 10:32:18.435  3865  3865 D BluetoothPbap: Proxy object connected
,09-07 10:32:18.436  3865  3865 D PbapServerProfile: Bluetooth service connected
,09-07 10:32:18.442  3909  3909 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 10:32:18.442  3909  3909 D ObexServerSockets0: prepareForNewConnect()
,09-07 10:32:18.446  3909  4105 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:18.459  3909  4109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:18.460  3909  4109 I BtOppRfcommListener: Accept thread started.
,09-07 10:32:18.480  1364  2050 D BluetoothHeadset: Proxy object connected
,09-07 10:32:18.480  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:18.481  1951  1968 D BluetoothHeadset: Proxy object connected
09-07 10:32:18.481   874   874 D BluetoothHeadset: Proxy object connected
09-07 10:32:18.481   874   874 D BluetoothHeadset: Proxy object connected
09-07 10:32:18.481   874   874 D BluetoothHeadset: Proxy object connected
,09-07 10:32:18.498  1364  1384 D BluetoothHeadset: Proxy object connected
09-07 10:32:18.499  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:18.501   874   891 D BluetoothHeadset: Proxy object connected
,09-07 10:32:18.502  1951  1969 D BluetoothHeadset: Proxy object connected
,09-07 10:32:18.513  3865  3876 D BluetoothHeadset: Proxy object connected
,09-07 10:32:18.513  3865  3865 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:19.982  3909  4075 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 10:32:19.983  3909  4075 D BluetoothAdapterProperties: Setting state to 13
,09-07 10:32:19.983  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 10:32:19.985  3909  4075 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 10:32:19.996  3909  3909 D BluetoothMapService: onReceive
09-07 10:32:19.997  3909  3909 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:19.997  3909  3909 D BluetoothMapService: STATE_TURNING_OFF
09-07 10:32:19.999  3909  3909 D BluetoothMapService: MAP Service closeService in
,09-07 10:32:19.999  3909  3909 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 10:32:19.999  3909  3909 D ObexServerSockets0: shutdown(block = true)
,09-07 10:32:20.000  3909  4100 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 10:32:20.001  3909  4075 I BluetoothAdapterState: Entering PendingCommandState
,09-07 10:32:20.001  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:20.002  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:20.003  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:20.003  3909  3909 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 10:32:20.004  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:20.004  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:20.004  3909  4101 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 10:32:20.005  3909  4079 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:32:20.006  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 10:32:20.007  3909  4087 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 10:32:20.008  3909  3909 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 10:32:20.009  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:20.010  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:20.011  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:20.011  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:20.013  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:20.014  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:20.018  3909  3909 D HeadsetService: Received stop request...Stopping profile...
09-07 10:32:20.022  3865  3876 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:20.022  1364  1384 D BluetoothHeadset: Proxy object disconnected
,09-07 10:32:20.023  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-07 10:32:20.023  1951  2111 D BluetoothHeadset: Proxy object disconnected
09-07 10:32:20.023   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 10:32:20.023  3909  3909 I BtOppRfcommListener: stopping Accept Thread
,09-07 10:32:20.023   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 10:32:20.023   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 10:32:20.023  3909  4109 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 10:32:20.024  3909  4109 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 10:32:20.026  3909  3909 D A2dpService: Received stop request...Stopping profile...
,09-07 10:32:20.026  3909  4094 D A2dpStateMachine: Exit Disconnected: -1
09-07 10:32:20.027  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:20.028   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:20.028  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:20.030  3865  3865 D HeadsetProfile: Bluetooth service disconnected
,09-07 10:32:20.030  3865  3865 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:20.031  3909  3909 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:20.031  3909  3909 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:20.031  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:32:20.031  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:20.031  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:20.034  3909  3909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 10:32:20.034  3909  3909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 10:32:20.035  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 10:32:20.035  3909  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:20.035  3909  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:20.035  3909  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 10:32:20.035  3909  3909 D HidService: Received stop request...Stopping profile...
09-07 10:32:20.035  3909  4079 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,09-07 10:32:20.035  3909  3909 D HidService: Stopping Bluetooth HidService
,09-07 10:32:20.036  3865  3865 D BluetoothInputDevice: Proxy object disconnected
,09-07 10:32:20.036  3865  3865 D HidProfile: Bluetooth service disconnected
09-07 10:32:20.036  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-07 10:32:20.036  1364  1364 D HidProfile: Bluetooth service disconnected
,09-07 10:32:20.037  3909  3909 D HealthService: Received stop request...Stopping profile...
09-07 10:32:20.038  3909  3909 D PanService: Received stop request...Stopping profile...
,09-07 10:32:20.039  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 10:32:20.039  1364  1364 D PanProfile: Bluetooth service disconnected
,09-07 10:32:20.039  3865  3865 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 10:32:20.039  3909  3909 D BluetoothMapService: Received stop request...Stopping profile...
09-07 10:32:20.039  3865  3865 D PanProfile: Bluetooth service disconnected
09-07 10:32:20.039  3909  3909 D BluetoothMapService: stop()
,09-07 10:32:20.040  3909  3909 D BluetoothMapAppObserver: deinitObservers()
09-07 10:32:20.040  3909  3909 D BluetoothMapAppObserver: removeReceiver()
09-07 10:32:20.041  3865  3865 D BluetoothMap: Proxy object disconnected
,09-07 10:32:20.041  3865  3865 D MapProfile: Bluetooth service disconnected
,09-07 10:32:20.041  1364  1364 D BluetoothMap: Proxy object disconnected
09-07 10:32:20.041  1364  1364 D MapProfile: Bluetooth service disconnected
,09-07 10:32:20.042  3909  3909 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:20.042  3909  3909 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:20.042  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:20.042  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:20.043  3909  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:20.043  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-07 10:32:20.043  3909  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 10:32:20.043  3909  4085 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:32:20.043  3909  4085 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 10:32:20.043  3909  4085 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 10:32:20.043  3909  4085 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 10:32:20.046  3865  3865 D BluetoothPbap: Proxy object disconnected
,09-07 10:32:20.046  3865  3865 D PbapServerProfile: Bluetooth service disconnected
09-07 10:32:20.046  1364  1364 D BluetoothPbap: Proxy object disconnected
,09-07 10:32:20.046  1364  1364 D PbapServerProfile: Bluetooth service disconnected
09-07 10:32:20.049  3909  3909 V BluetoothAdapterState: isTurningOff()=true,
09-07 10:32:20.049  3909  3909 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:20.049  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:20.049  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:20.050  3909  3909 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 10:32:20.050  3909  3909 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 10:32:20.050  3909  3909 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:20.051  3909  3909 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:20.050  3909  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 10:32:20.051  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:20.051  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:20.051  3909  3909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 10:32:20.051  3909  4079 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 10:32:20.051  3909  3909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:32:20.052  3909  3909 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:20.052  3909  3909 V BluetoothAdapterState: isTurningOn()=false
,09-07 10:32:20.052  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:20.052  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:20.053  3909  3909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 10:32:20.053  3909  3909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 10:32:20.054  3909  3909 D BluetoothMapService: MAP Service closeService in
09-07 10:32:20.054  3909  3909 V BluetoothAdapterState: isTurningOff()=true
09-07 10:32:20.054  3909  3909 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:20.054  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:20.054  3909  3909 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:20.054  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-07 10:32:20.054  3909  3909 D BluetoothMapService: cleanup()
,09-07 10:32:20.054  3909  3909 D BluetoothMapService: MAP Service closeService in
,09-07 10:32:20.054  3909  4075 D BluetoothAdapterProperties: Setting state to 15
,09-07 10:32:20.054  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-07 10:32:20.054  3909  4075 I BluetoothAdapterState: Entering BleOnState
,09-07 10:32:20.055   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 10:32:20.055   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 10:32:20.055  3865  3875 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 10:32:20.055  3865  3876 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:20.056   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 10:32:20.056  3865  3875 D BluetoothMap: onBluetoothStateChange: up=false
09-07 10:32:20.057  1364  1384 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 10:32:20.057  3865  3876 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 10:32:20.058  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false,
09-07 10:32:20.058  3865  3875 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 10:32:20.058  1364  2050 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 10:32:20.059  1364  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 10:32:20.060  3865  3876 D BluetoothPan: onBluetoothStateChange on: false
,09-07 10:32:20.061  1364  1377 D BluetoothPan: onBluetoothStateChange on: false,
09-07 10:32:20.061  1364  2050 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:32:20.061   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 10:32:20.062  1951  2254 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:32:20.062  3909  4075 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 10:32:20.062  3909  4075 D BluetoothAdapterProperties: Setting state to 16
09-07 10:32:20.062  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 10:32:20.063  3909  4075 D BluetoothAdapterProperties: onBleDisable
,09-07 10:32:20.064  3909  4075 I BluetoothAdapterState: Entering PendingCommandState
09-07 10:32:20.065  3909  4076 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 10:32:20.065  3909  4085 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 10:32:20.066  3909  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 10:32:20.066  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:20.066  3909  4079 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:32:20.067  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:20.067  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:20.067  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:20.068  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:20.072  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:32:20.074  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:20.148   874  1311 D ConnectivityService: handlePromptUnvalidated 101
,09-07 10:32:20.267  3909  4079 I bt_hci  : shut_down
,09-07 10:32:20.284  3909  4083 D bt_hwcfg: hw_epilog_process
,09-07 10:32:20.284  3909  4083 I bt_vendor: low_power_mode_cb
,09-07 10:32:20.300  3909  4083 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 10:32:20.300  3909  4083 I bt_vendor: epilog_cb
09-07 10:32:20.300  3909  4083 I bt_hci  : epilog_finished_callback
,09-07 10:32:20.308  3909  4079 I bt_hci_h4: hal_close
,09-07 10:32:20.309  3909  4079 I bt_userial_vendor: device fd = 51 close
,09-07 10:32:20.423  3909  4076 D bt_stack_manager: event_shut_down_stack finished.
,09-07 10:32:20.424  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 10:32:20.432  3909  4075 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 10:32:20.432  3909  3909 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 10:32:20.434  3909  3909 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 10:32:20.434  3909  3909 D BtGatt.GattService: stop()
09-07 10:32:20.434  3909  3909 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 10:32:20.439  3909  3909 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:20.440  3909  3909 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:20.440  3909  3909 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:20.441  3909  3909 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 10:32:20.441  3909  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 10:32:20.442  3909  4075 D BluetoothAdapterProperties: Setting state to 10
09-07 10:32:20.442  3909  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 10:32:20.444  3909  4075 I BluetoothAdapterState: Entering OffState
,09-07 10:32:20.445   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 10:32:20.475  3909  3909 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 10:32:20.475  3909  3909 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 10:32:20.476  3909  4076 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 10:32:20.486  3909  4076 D bt_stack_manager: event_clean_up_stack finished.
,09-07 10:32:20.488  3909  3909 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 10:32:20.490  3909  3909 I art     : System.exit called, status: 0
,09-07 10:32:20.491  3909  3909 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 10:32:20.563   874  3066 I ActivityManager: Process com.android.bluetooth (pid 3909) has died
,09-07 10:32:22.980  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:22.980  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:25.988  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:25.989  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2248419 added. We now have 6 listener(s)
09-07 10:32:25.989  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:25.993  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:25.993  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e220cde added. We now have 7 listener(s)
09-07 10:32:25.993  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:25.995  3763  3814 I System.out: IsBluetoothEnabled
,09-07 10:32:26.006  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:26.043   874   891 I ActivityManager: Start proc 4122:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 10:32:26.151  4122  4122 D AdapterServiceConfig: Adding HeadsetService
09-07 10:32:26.152  4122  4122 D AdapterServiceConfig: Adding A2dpService
,09-07 10:32:26.153  4122  4122 D AdapterServiceConfig: Adding HidService
09-07 10:32:26.154  4122  4122 D AdapterServiceConfig: Adding HealthService
09-07 10:32:26.154  4122  4122 D AdapterServiceConfig: Adding PanService
09-07 10:32:26.155  4122  4122 D AdapterServiceConfig: Adding GattService
09-07 10:32:26.155  4122  4122 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 10:32:26.170   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a884421:true
,09-07 10:32:26.171  4122  4122 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 10:32:26.175  4122  4122 I bt_bluedroid: init
,09-07 10:32:26.177  4122  4134 I BluetoothAdapterState: Entering OffState
,09-07 10:32:26.179  4122  4135 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 10:32:26.179  4122  4135 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 10:32:26.179  4122  4135 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 10:32:26.179  4122  4135 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 10:32:26.180  4122  4122 I bt_bluedroid: get_profile_interface socket
,09-07 10:32:26.182  4122  4122 I bt_bluedroid: get_profile_interface sdp
,09-07 10:32:26.182  4122  4138 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 10:32:26.184  4122  4138 D BluetoothAdapterProperties: Name is: Nexus 6
09-07 10:32:26.184  4122  4133 I bt_bluedroid: config_hci_snoop_log
09-07 10:32:26.185   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 10:32:26.193  4122  4134 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 10:32:26.195  4122  4134 D BluetoothAdapterProperties: Setting state to 14
,09-07 10:32:26.196  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 10:32:26.199  4122  4134 D BluetoothBondStateMachine: make
,09-07 10:32:26.200  4122  4139 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 10:32:26.204  4122  4134 I BluetoothAdapterState: Entering PendingCommandState
,09-07 10:32:26.206  4122  4122 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 10:32:26.210  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:26.211  4122  4122 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 10:32:26.212  4122  4122 D BtGatt.GattService: Received start request. Starting profile...
09-07 10:32:26.212  4122  4122 D BtGatt.GattService: start()
,09-07 10:32:26.212  4122  4122 I bt_bluedroid: get_profile_interface gatt
,09-07 10:32:26.213  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
09-07 10:32:26.213  4122  4122 D BtGatt.AdvertiseManager: advertise manager created
,09-07 10:32:26.220  4122  4122 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:26.220  4122  4122 V BluetoothAdapterState: isTurningOn()=false
09-07 10:32:26.220  4122  4122 V BluetoothAdapterState: isBleTurningOn()=true
09-07 10:32:26.220  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:26.221  4122  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 10:32:26.222  4122  4134 I bt_bluedroid: enable
,09-07 10:32:26.222  4122  4135 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 10:32:26.223  4122  4135 I bt_hci  : start_up
,09-07 10:32:26.228  4122  4135 I bt_vendor: alloc value 0xb39a2189
,09-07 10:32:26.229  4122  4135 I bt_vendor: init
09-07 10:32:26.229  4122  4135 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 10:32:26.229  4122  4135 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 10:32:26.336  4122  4135 D bt_hci  : start_up starting async portion
,09-07 10:32:26.336  4122  4142 I bt_hci  : event_finish_startup
,09-07 10:32:26.337  4122  4142 I bt_hci_h4: hal_open
09-07 10:32:26.337  4122  4142 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 10:32:26.348  4122  4142 I bt_userial_vendor: device fd = 51 open
,09-07 10:32:26.377  4122  4142 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 10:32:26.410  4122  4142 D bt_hwcfg: Chipset BCM4354A2
,09-07 10:32:26.410  4122  4142 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 10:32:26.411  4122  4142 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 10:32:27.077  4122  4142 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-07 10:32:27.079  4122  4142 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 10:32:27.079  4122  4142 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 10:32:27.195  4122  4142 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 10:32:27.197  4122  4142 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 10:32:27.227  4122  4142 I bt_hwcfg: vendor lib fwcfg completed
,09-07 10:32:27.227  4122  4142 I bt_vendor: firmware callback
09-07 10:32:27.227  4122  4142 I bt_hci  : firmware_config_callback
,09-07 10:32:27.240  4122  4144 I bt_btu  : btu_task pending for preload complete event
,09-07 10:32:27.240  4122  4144 I bt_btu_task: Bluetooth chip preload is complete
,09-07 10:32:27.241  4122  4144 I bt_btu  : btu_task received preload complete event
,09-07 10:32:27.254  4122  4144 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 10:32:27.254  4122  4144 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 10:32:27.255  4122  4144 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 10:32:27.255  4122  4144 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 10:32:27.255  4122  4144 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 10:32:27.255  4122  4144 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 10:32:27.256  4122  4144 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 10:32:27.256  4122  4144 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 10:32:27.256  4122  4144 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 10:32:27.256  4122  4144 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 10:32:27.257  4122  4144 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 10:32:27.257  4122  4144 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 10:32:27.257  4122  4144 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 10:32:27.258  4122  4144 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 10:32:27.258  4122  4144 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 10:32:27.391  4122  4144 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391fd9d
,09-07 10:32:27.391  4122  4144 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391fd9d 
,09-07 10:32:27.403  4122  4138 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 10:32:27.405  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 10:32:27.407  4122  4138 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 10:32:27.411  4122  4138 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 10:32:27.418  4122  4138 D BluetoothAdapterProperties: Scan Mode:20
,09-07 10:32:27.419  4122  4138 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:32:27.419  4122  4138 D bt_hci  : do_postload posting postload work item
,09-07 10:32:27.421  4122  4142 I bt_hci  : event_postload
09-07 10:32:27.421  4122  4142 I bt_vendor: sco_config_cb
,09-07 10:32:27.421  4122  4142 I bt_hci  : sco_config_callback postload finished.
09-07 10:32:27.422  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:27.425  4122  4138 D bt_bte_conf: Device ID record 1 : primary
,09-07 10:32:27.425  4122  4138 D bt_bte_conf:   vendorId            = 000f
,09-07 10:32:27.425  4122  4142 I bt_vendor: low_power_mode_cb
09-07 10:32:27.425  4122  4138 D bt_bte_conf:   vendorIdSource      = 0001
09-07 10:32:27.426  4122  4138 D bt_bte_conf:   product             = 1200
09-07 10:32:27.426  4122  4138 D bt_bte_conf:   version             = 1436
09-07 10:32:27.426  4122  4138 D bt_bte_conf:   clientExecutableURL = 
09-07 10:32:27.426  4122  4138 D bt_bte_conf:   serviceDescription  = 
09-07 10:32:27.426  4122  4138 D bt_bte_conf:   documentationURL    = 
09-07 10:32:27.427  4122  4138 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 10:32:27.427  4122  4135 D bt_stack_manager: event_start_up_stack finished
09-07 10:32:27.429  4122  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 10:32:27.430  4122  4134 D BluetoothAdapterProperties: Setting state to 15
09-07 10:32:27.430  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-07 10:32:27.431  4122  4134 I BluetoothAdapterState: Entering BleOnState
,09-07 10:32:27.435  4122  4134 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 10:32:27.435  4122  4134 D BluetoothAdapterProperties: Setting state to 11
,09-07 10:32:27.435  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 10:32:27.440  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:27.443  4122  4122 D HeadsetService: Received start request. Starting profile...
,09-07 10:32:27.446  4122  4122 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 10:32:27.447  4122  4122 D HeadsetStateMachine: make
,09-07 10:32:27.454  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:27.465  4122  4122 D HeadsetStateMachine: max_hf_connections = 1
,09-07 10:32:27.466  4122  4122 I bt_bluedroid: get_profile_interface handsfree
,09-07 10:32:27.466  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-07 10:32:27.470  4122  4134 I BluetoothAdapterState: Entering PendingCommandState
,09-07 10:32:27.470  4122  4138 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 10:32:27.472  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:27.472  4122  4122 D A2dpService: Received start request. Starting profile...
,09-07 10:32:27.473  4122  4122 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 10:32:27.473  4122  4122 I bt_bluedroid: get_profile_interface avrcp
,09-07 10:32:27.480  4122  4122 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 10:32:27.480  4122  4122 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-07 10:32:27.480  4122  4122 D A2dpStateMachine: make
,09-07 10:32:27.482  4122  4122 I bt_bluedroid: get_profile_interface a2dp
,09-07 10:32:27.483  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 10:32:27.484  4122  4153 D A2dpStateMachine: Enter Disconnected: -2
09-07 10:32:27.485  4122  4122 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 10:32:27.486  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:27.488  4122  4122 D HidService: Received start request. Starting profile...
,09-07 10:32:27.488  4122  4122 I bt_bluedroid: get_profile_interface hidhost
09-07 10:32:27.488  4122  4138 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39013e5
,09-07 10:32:27.488  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 10:32:27.489  4122  4122 D HidService: setHidService(): set to: null
09-07 10:32:27.491  4122  4122 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 10:32:27.492  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:27.494  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:27.495  4122  4122 D HealthService: Received start request. Starting profile...
,09-07 10:32:27.498  4122  4122 I bt_bluedroid: get_profile_interface health
,09-07 10:32:27.499  4122  4122 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 10:32:27.500  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:27.501  4122  4122 D PanService: Received start request. Starting profile...
,09-07 10:32:27.501  4122  4122 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 10:32:27.501  4122  4122 I bt_bluedroid: get_profile_interface pan
,09-07 10:32:27.503  4122  4138 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 10:32:27.506  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
,09-07 10:32:27.507  4122  4122 D BluetoothMapService: Received start request. Starting profile...
,09-07 10:32:27.507  4122  4122 D BluetoothMapService: start()
,09-07 10:32:27.509  4122  4122 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 10:32:27.510  4122  4122 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 10:32:27.510  4122  4122 D BluetoothMapAppObserver: createReceiver()
,09-07 10:32:27.511  4122  4122 D BluetoothMapAppObserver: initObservers()
09-07 10:32:27.511  4122  4122 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 10:32:27.518  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:27.518  4122  4122 V BluetoothAdapterState: isTurningOn()=true
,09-07 10:32:27.518  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:27.518  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:27.520  4122  4150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:27.520  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:27.523  4122  4122 V BluetoothAdapterState: isTurningOff()=false
,09-07 10:32:27.523  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:27.523  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:27.523  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:27.523  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-07 10:32:27.524  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-07 10:32:27.524  4122  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-07 10:32:27.524  4122  4134 D BluetoothAdapterProperties: ScanMode =  20
09-07 10:32:27.525  4122  4134 D BluetoothAdapterProperties: State =  11
09-07 10:32:27.525  4122  4134 D BluetoothAdapterProperties: Setting state to 12
09-07 10:32:27.525  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 10:32:27.526   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 10:32:27.526   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:27.526  4122  4134 I BluetoothAdapterState: Entering OnState
09-07 10:32:27.526  3865  3875 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:32:27.528  4122  4138 D BluetoothAdapterProperties: Scan Mode:21
09-07 10:32:27.528  4122  4138 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:32:27.530  3865  3875 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:27.531   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:32:27.531   874   874 D BluetoothA2dp: Proxy object connected
09-07 10:32:27.531  3865  3876 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 10:32:27.534  1364  1377 D BluetoothMap: onBluetoothStateChange: up=true
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:27.534  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:27.536  1364  1364 D BluetoothMap: Proxy object connected
09-07 10:32:27.536  1364  1364 D MapProfile: Bluetooth service connected
09-07 10:32:27.537  1364  1364 D BluetoothMap: getConnectedDevices()
09-07 10:32:27.537  3865  3876 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 10:32:27.537  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:27.538  4122  4122 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 10:32:27.539  4122  4122 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 10:32:27.540  1364  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 10:32:27.541  4122  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.543  3865  3875 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 10:32:27.545  4122  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.545  3865  3865 D BluetoothA2dp: Proxy object connected
09-07 10:32:27.545  1364  2050 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 10:32:27.547  4122  4122 D ObexServerSockets: Succeed to create listening sockets 
09-07 10:32:27.547  4122  4122 D ObexServerSockets0: startAccept()
09-07 10:32:27.547  4122  4122 D ObexServerSockets0: prepareForNewConnect()
,09-07 10:32:27.547  3865  3865 D BluetoothMap: Proxy object connected
09-07 10:32:27.547  3865  3865 D MapProfile: Bluetooth service connected
09-07 10:32:27.547  3865  3865 D BluetoothMap: getConnectedDevices()
09-07 10:32:27.547  1364  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:27.548  3865  3876 D BluetoothPan: onBluetoothStateChange on: true
09-07 10:32:27.550  1364  1384 D BluetoothPan: onBluetoothStateChange on: true
,09-07 10:32:27.552  1364  2050 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:32:27.554  4122  4122 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-07 10:32:27.554  1364  1364 D BluetoothA2dp: Proxy object connected
,09-07 10:32:27.554  4122  4122 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 10:32:27.554   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:27.555  1951  2254 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:32:27.555  4122  4160 D ObexServerSockets0: Accepting socket connection...
09-07 10:32:27.557  3865  3865 D BluetoothInputDevice: Proxy object connected
09-07 10:32:27.557  3865  3865 D HidProfile: Bluetooth service connected
,09-07 10:32:27.557  1364  1364 D BluetoothInputDevice: Proxy object connected
09-07 10:32:27.558  1364  1364 D HidProfile: Bluetooth service connected
09-07 10:32:27.558  4122  4161 D ObexServerSockets0: Accepting socket connection...
09-07 10:32:27.559   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 10:32:27.560  4122  4122 D BluetoothMapService: onReceive
09-07 10:32:27.561  4122  4122 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.561  4122  4122 D BluetoothMapService: STATE_ON
09-07 10:32:27.561  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:27.562  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 10:32:27.562  1364  1364 D PanProfile: Bluetooth service connected
09-07 10:32:27.563  3865  3865 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 10:32:27.563  3865  3865 D PanProfile: Bluetooth service connected
09-07 10:32:27.567  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 10:32:27.573  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:32:27.580  3865  3865 D DockEventReceiver: finishStartingService: stopping service
09-07 10:32:27.584  1364  1364 D BluetoothPbap: Proxy object connected
09-07 10:32:27.584  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-07 10:32:27.585  3865  3865 D BluetoothPbap: Proxy object connected
09-07 10:32:27.585  3865  3865 D PbapServerProfile: Bluetooth service connected
,09-07 10:32:27.590  4122  4122 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 10:32:27.591  4122  4122 D ObexServerSockets0: prepareForNewConnect()
,09-07 10:32:27.595  4122  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.609  4122  4170 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.610  4122  4170 I BtOppRfcommListener: Accept thread started.
,09-07 10:32:27.627  3865  4158 D BluetoothHeadset: Proxy object connected
,09-07 10:32:27.627  3865  3865 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:27.628  1364  1377 D BluetoothHeadset: Proxy object connected
09-07 10:32:27.628  1364  1364 D HeadsetProfile: Bluetooth service connected
09-07 10:32:27.628  1951  1968 D BluetoothHeadset: Proxy object connected
09-07 10:32:27.629   874   874 D BluetoothHeadset: Proxy object connected
09-07 10:32:27.629   874   874 D BluetoothHeadset: Proxy object connected
,09-07 10:32:27.629   874   874 D BluetoothHeadset: Proxy object connected
,09-07 10:32:27.631  3865  3876 D BluetoothHeadset: Proxy object connected
,09-07 10:32:27.631  3865  3865 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:27.648  1364  2050 D BluetoothHeadset: Proxy object connected
,09-07 10:32:27.649  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:27.655   874   891 D BluetoothHeadset: Proxy object connected
,09-07 10:32:27.655  1951  1969 D BluetoothHeadset: Proxy object connected
,09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:28.027  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:28.034  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:28.037  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:28.038  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61f4ebf added. We now have 8 listener(s)
09-07 10:32:28.038  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:28.043   874  1932 D WifiService: setWifiEnabled: false pid=3763, uid=10000
,09-07 10:32:28.044   874  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:32:28.056  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:28.057   874  1928 D WifiService: setWifiEnabled: true pid=3763, uid=10000
,09-07 10:32:28.057   874  1928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:32:28.070   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:28.087  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:28.091  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:28.093  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:28.095  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:28.099  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 10:32:28.100  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 10:32:28.102   874  1309 D WifiConfigStore: loaded 0 passpoint configs
09-07 10:32:28.103   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 10:32:28.103   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 10:32:28.104   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 10:32:28.105   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 10:32:28.105  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7c2be07 Bundle[{}]
09-07 10:32:28.105   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 10:32:28.105   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-07 10:32:28.105  3763  3814 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 10:32:28.106  3763  3814 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 10:32:28.106  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 10:32:28.107  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 10:32:28.108  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 10:32:28.110  3763  3814 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 10:32:28.115  3763  3814 I System.out: Running OutgoingSocketThread
,09-07 10:32:28.119   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 10:32:28.119  3763  4175 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
09-07 10:32:28.119   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.62 rxSuccessRate=0.73 delta 1000 -> 1000
09-07 10:32:28.120   373   872 D CommandListener: Setting iface cfg
,09-07 10:32:28.120   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-07 10:32:28.121   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 10:32:28.121  3763  4175 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39090
09-07 10:32:28.121  3763  4175 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 10:32:28.129   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 10:32:28.129   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
09-07 10:32:28.129   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:32:28.129   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 10:32:28.137   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 10:32:28.213   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 10:32:28.218  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 10:32:28.699  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 10:32:28.743  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 10:32:28.744  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 10:32:28.746   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 10:32:28.756   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 10:32:28.756   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:28.757   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 10:32:28.774   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:28.788   373   872 D CommandListener: Setting iface cfg
09-07 10:32:28.788   874  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 10:32:28.815   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 10:32:28.816   874  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-07 10:32:28.821   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 10:32:28.825   874  4179 D DhcpClient: Receive thread started
,09-07 10:32:28.913   874  1309 E native  : do suspend false
,09-07 10:32:28.934   874  1876 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 10:32:28.947   874  4179 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-07 10:32:28.949   874  1876 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-07 10:32:28.952   874  1876 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 10:32:28.971   874  4179 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 10:32:28.972   874  1876 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 10:32:28.977   373   872 D CommandListener: Setting iface cfg
,09-07 10:32:28.990   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 10:32:28.990   874  1876 D DhcpClient: Scheduling renewal in 86399s
,09-07 10:32:29.006   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 10:32:29.011   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 10:32:29.013   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 10:32:29.015   874  1311 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 10:32:29.029   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 10:32:29.060   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 10:32:29.060   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-07 10:32:29.062   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 10:32:29.063   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 10:32:29.064   874  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 10:32:29.070   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 10:32:29.076   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-07 10:32:29.076   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 10:32:29.076   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 10:32:29.076   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 10:32:29.076   874  1311 D ConnectivityService:    accepting network in place of null
09-07 10:32:29.077   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 10:32:29.078   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 10:32:29.103   874  4178 D NetlinkSocketObserver: NeighborEvent{elapsedMs=147785, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 10:32:29.103   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 10:32:29.116  3763  3814 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,09-07 10:32:29.116  3763  3814 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,09-07 10:32:29.118  3763  3814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,09-07 10:32:29.119  3763  3814 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 10:32:29.119  3763  3814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,09-07 10:32:29.121  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 10:32:29.121  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0ce98c added. We now have 2 listener(s)
,09-07 10:32:29.122  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.122  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:29.122  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:32:29.122  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:29.122  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef048d5 added. We now have 9 listener(s)
,09-07 10:32:29.123  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:29.123  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:29.125  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:29.129  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:29.130  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.131  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:29.131  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.131  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10417db added. We now have 3 listener(s)
09-07 10:32:29.132  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.133  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:29.133  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:29.133  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.133  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c651278 added. We now have 10 listener(s)
09-07 10:32:29.133  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:29.133  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:29.133  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:29.133  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:29.133  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.133  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.133  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:29.133  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.134  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0ce98c removed from the list
09-07 10:32:29.134  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:29.134  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef048d5 removed from the list
09-07 10:32:29.134  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.135  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:29.135  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:29.135  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.135   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 10:32:29.136  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.138  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:29.138  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:29.138  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.138  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.138  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef048d5 not in the list
09-07 10:32:29.139  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.139  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.140  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:29.140  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.141  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.141  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c651278 removed from the list
,09-07 10:32:29.141   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 10:32:29.141   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:32:29.141  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.142  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.142  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.142  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 10:32:29.142  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10417db removed from the list
09-07 10:32:29.144  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.144  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3799d51 added. We now have 2 listener(s)
09-07 10:32:29.146   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 10:32:29.150   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:29.155  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:29.157  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.157  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.157  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:29.158  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:29.158  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.158  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65cd9b6 added. We now have 9 listener(s)
,09-07 10:32:29.158  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:29.158  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:32:29.160  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:29.164  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:29.165  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 10:32:29.166  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:29.166  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:29.166  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.166  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14de24 added. We now have 3 listener(s)
,09-07 10:32:29.168  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.168  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.168  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:29.168  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:29.169  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:29.169  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469bd8d added. We now have 10 listener(s)
,09-07 10:32:29.169  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:29.169  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 10:32:29.169  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:29.169  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:29.169  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.169  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:32:29.170  1705  1705 D SystemUpdateService: onCreate
09-07 10:32:29.170  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.172  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 10:32:29.172  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:32:29.172  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 10:32:29.175  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 10:32:29.175   874  4177 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 10:32:29.176  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 10:32:29.176  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:29.180  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 10:32:29.180  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:29.180  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 10:32:29.181  3763  3814 D BluetoothAdapter: STATE_ON
,09-07 10:32:29.183  4122  4159 D BtGatt.GattService: registerClient() - UUID=4fe8b101-4ed9-4871-b9ca-379da1b25702
,09-07 10:32:29.184  4122  4138 D BtGatt.GattService: onClientRegistered() - UUID=4fe8b101-4ed9-4871-b9ca-379da1b25702, clientIf=5
09-07 10:32:29.185  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 10:32:29.185  4122  4132 D BtGatt.GattService: start scan with filters
,09-07 10:32:29.188  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 10:32:29.188  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:29.188  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:29.188  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:29.188  4122  4141 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:29.191  4122  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@195aa2b
09-07 10:32:29.191  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:29.191  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:29.191  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:29.193  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:29.193  4122  4138 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 10:32:29.194  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.194  4122  4141 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 10:32:29.195  3763  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 10:32:29.195  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:29.195  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 10:32:29.195  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.195  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:29.195  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:29.195  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:29.195  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 10:32:29.195  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 10:32:29.195  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.195  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:29.195  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:29.195  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:29.196  4122  4141 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:29.196  4122  4141 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 10:32:29.197  3763  3814 D BluetoothAdapter: STATE_ON
,09-07 10:32:29.197  4122  4138 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 10:32:29.197  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.197  4122  4159 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:29.198  4122  4132 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 10:32:29.198  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:29.198  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:29.198  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 10:32:29.198  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 10:32:29.198  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.198  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 10:32:29.198  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 10:32:29.199  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:29.199  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:29.199  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 10:32:29.199  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 10:32:29.200  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:29.201  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:29.201  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-07 10:32:29.201  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:29.201  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 10:32:29.201  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.201  4122  4141 D BtGatt.ScanManager: stopping BLe Batch
,09-07 10:32:29.202  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:29.202  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:29.202  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:29.202  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.202  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.202  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:29.203  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.203  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3799d51 removed from the list
09-07 10:32:29.203  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.203  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65cd9b6 removed from the list
09-07 10:32:29.203  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:29.203  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.203  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 10:32:29.203  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.203  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.203  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.204  4122  4141 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 10:32:29.204  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.204  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.204  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.204  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65cd9b6 not in the list
09-07 10:32:29.204  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.204  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.205  4122  4138 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 10:32:29.205  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.205  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.205  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.205  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.205  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469bd8d removed from the list
,09-07 10:32:29.205  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.205  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.205  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.205  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.205  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14de24 removed from the list
09-07 10:32:29.206  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.206  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1a589 added. We now have 2 listener(s)
,09-07 10:32:29.208  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 10:32:29.208  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:29.208  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:29.208  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.208  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd9698e added. We now have 9 listener(s)
09-07 10:32:29.208  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:29.208  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:32:29.211  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:29.217  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:29.217  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 10:32:29.218  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:29.218  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:29.218  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.218  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a63cdbc added. We now have 3 listener(s)
09-07 10:32:29.220  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.220  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:29.220  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:29.220  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.220  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@961145 added. We now have 10 listener(s)
09-07 10:32:29.220  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.220  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:29.221  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:29.221  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:29.221  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:29.221  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:29.221  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.221  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:29.222  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.208  1705  4188 I SystemUpdateService: active receiver: enabled
09-07 10:32:29.224  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 10:32:29.224  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:29.232  1705  2439 I iu.UploadsManager: num queued entries: 0
,09-07 10:32:29.232  1705  2439 I iu.UploadsManager: num updated entries: 0
09-07 10:32:29.233  1705  2439 I iu.SyncManager: NEXT; no task
,09-07 10:32:29.235  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 10:32:29.235  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 10:32:29.235  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:29.238  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 10:32:29.238  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 10:32:29.239  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 10:32:29.239  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 10:32:29.240  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:29.240  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 10:32:29.242  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:29.242  4122  4151 D BtGatt.GattService: registerClient() - UUID=11cec636-a27c-4629-9673-d1d6823cc746
09-07 10:32:29.243  4122  4138 D BtGatt.GattService: onClientRegistered() - UUID=11cec636-a27c-4629-9673-d1d6823cc746, clientIf=5
09-07 10:32:29.243  3763  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 10:32:29.243   874  4177 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 08:32:29 GMT], X-Android-Received-Millis=[1473237149242], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473237149214]}
,09-07 10:32:29.244  4122  4162 D BtGatt.GattService: start scan with filters
09-07 10:32:29.245   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 10:32:29.245   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-07 10:32:29.245   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 10:32:29.246   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 10:32:29.248  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:29.248  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:29.248  4122  4141 D BtGatt.ScanManager: handling starting scan
09-07 10:32:29.248  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 10:32:29.248  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:29.250  1705  4191 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 10:32:29.250  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:29.251  1705  4191 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 10:32:29.251  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:29.251  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:29.252  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 10:32:29.253  3925  3925 D SprintDMHelper: simOperator: 
09-07 10:32:29.253  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 10:32:29.254  1705  4191 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 10:32:29.255  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:29.255  3763  3814 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 10:32:29.256  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:29.256  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:29.256  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:29.256  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.256  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.256  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-07 10:32:29.256  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.256  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1a589 removed from the list
09-07 10:32:29.256  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.256  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd9698e removed from the list
09-07 10:32:29.257  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:29.257  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:29.257  4122  4138 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 10:32:29.257  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.257  4122  4141 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 10:32:29.260  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.260  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 10:32:29.260  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.260  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:29.261  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:29.261  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.261  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.261  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd9698e not in the list
09-07 10:32:29.261  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 10:32:29.261  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:29.261  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:29.261  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:29.261  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 10:32:29.262  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:29.262  1705  4188 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-07 10:32:29.263  4122  4162 D BtGatt.GattService: stopScan() - queue size =1
09-07 10:32:29.264  4122  4159 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 10:32:29.264  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:29.264  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 10:32:29.265  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:29.265  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:29.265  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 10:32:29.266  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:29.266  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:29.266  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:29.266  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 10:32:29.267  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.268  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:29.268  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:29.268  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:29.268  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.268  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.269  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:29.269  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@961145 removed from the list
09-07 10:32:29.269  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.269  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.269  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.269  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.269  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 10:32:29.269  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a63cdbc removed from the list
09-07 10:32:29.270  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 10:32:29.270  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 10:32:29.271  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.271  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b7cc1 added. We now have 2 listener(s)
09-07 10:32:29.271  4122  4141 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:29.271  4122  4141 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 10:32:29.273  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 10:32:29.274  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.274  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:29.274  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:32:29.274  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.275  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad1c66 added. We now have 9 listener(s)
,09-07 10:32:29.275  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:29.278  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:32:29.283  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.284  4122  4138 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 10:32:29.284  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:29.287  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:29.294  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.294  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:29.294  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 10:32:29.294  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37e1854 added. We now have 3 listener(s)
,09-07 10:32:29.295  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 10:32:29.296  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:29.296  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 10:32:29.296  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:32:29.296  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.296  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.296  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1223fd added. We now have 10 listener(s)
09-07 10:32:29.296  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:29.296  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:29.296  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:29.296  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 10:32:29.296  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.296  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:29.297  1705  4188 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 10:32:29.298  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.299  3763  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 10:32:29.299  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:32:29.301  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.302  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 10:32:29.302  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.302  4122  4141 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:29.302  1705  4188 I SystemUpdateService: now status is 0 (complete)
,09-07 10:32:29.303  1705  4188 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 10:32:29.303  1705  4188 I SystemUpdateService: file has been verified
09-07 10:32:29.308  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 10:32:29.310  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.305  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:29.310  4122  4141 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 10:32:29.311  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 10:32:29.311  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:29.304  1705  4188 I SystemUpdateService: OTA package size = 12249756
,09-07 10:32:29.316  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 10:32:29.316  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 10:32:29.316  3763  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 10:32:29.316  3763  3814 D BluetoothAdapter: STATE_ON
,09-07 10:32:29.318  4122  4138 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 10:32:29.318  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.319  4122  4162 D BtGatt.GattService: registerClient() - UUID=8cce5c65-869b-4dcc-9c7e-ca21655a71b6
,09-07 10:32:29.319  4122  4138 D BtGatt.GattService: onClientRegistered() - UUID=8cce5c65-869b-4dcc-9c7e-ca21655a71b6, clientIf=5
09-07 10:32:29.320  3763  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 10:32:29.320  4122  4159 D BtGatt.GattService: start scan with filters
,09-07 10:32:29.324  4122  4141 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:29.324  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:29.324  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 10:32:29.324  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-07 10:32:29.324  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:29.328  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:29.328  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 10:32:29.328  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:29.330  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 10:32:29.330  4122  4138 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 10:32:29.330  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.331  4122  4141 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 10:32:29.335  1705  4188 I SystemUpdateService: showing system update notification
,09-07 10:32:29.335  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:29.335  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:29.335  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:29.335  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 10:32:29.335  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.335  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:29.335  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.336  4122  4141 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 10:32:29.336  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:29.336  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.336  4122  4141 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 10:32:29.336  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b7cc1 removed from the list
09-07 10:32:29.336  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.336  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad1c66 removed from the list
09-07 10:32:29.336  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:29.336  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:29.336  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.336  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 10:32:29.336  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.337  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:29.337  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.337  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.337  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.337  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad1c66 not in the list
09-07 10:32:29.337  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 10:32:29.338  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:29.338  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 10:32:29.338  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:29.338  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 10:32:29.338  3763  3814 D BluetoothAdapter: STATE_ON
09-07 10:32:29.339  4122  4133 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:29.339  4122  4162 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 10:32:29.339  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:29.339  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 10:32:29.339  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 10:32:29.339  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:29.339  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 10:32:29.340  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:29.340  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:29.340  3763  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:29.341  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:29.341  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.342  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.342  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.342  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.342  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:29.342  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1223fd removed from the list
09-07 10:32:29.342  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:29.342  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:29.342  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.342  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.342  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:29.342  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 10:32:29.342  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37e1854 removed from the list
09-07 10:32:29.343  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.343  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26202f9 added. We now have 2 listener(s)
09-07 10:32:29.344  1506  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 10:32:29.344  1506  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 10:32:29.344  1506  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 10:32:29.344  1506  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 10:32:29.344  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 10:32:29.344  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:29.345  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:32:29.345  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:29.345  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@639523e added. We now have 9 listener(s)
,09-07 10:32:29.345  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:29.345  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:29.347  4122  4138 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 10:32:29.348  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.350  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:29.354  3763  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:29.355  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 10:32:29.355  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.357  3763  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:29.357  3763  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:29.357  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:29.357  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4141dec added. We now have 3 listener(s)
,09-07 10:32:29.358  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 10:32:29.358  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:29.358  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:29.358  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:29.358  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e36d5b5 added. We now have 10 listener(s)
,09-07 10:32:29.358  3763  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:29.358  3763  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:29.359  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:29.359  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 10:32:29.359  3763  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:29.359  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:29.359  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.359  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:29.359  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.359  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26202f9 removed from the list,
09-07 10:32:29.359  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:29.359  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@639523e removed from the list
,09-07 10:32:29.361  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:29.361  3763  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:29.361  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.362  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.362  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:29.362  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 10:32:29.362  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.363  4122  4141 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:29.363  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:29.363  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:29.363  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:29.363  3763  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@639523e not in the list
09-07 10:32:29.363  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:29.363  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:29.364  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:29.364  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 10:32:29.364  3763  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:29.364  3763  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e36d5b5 removed from the list
,09-07 10:32:29.364  3763  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:29.364  3763  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:29.364  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:29.364  3763  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:29.364  3763  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4141dec removed from the list
,09-07 10:32:29.365  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 10:32:29.365  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-07 10:32:29.365  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 10:32:29.365  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:29.365  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 10:32:29.365  3763  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:29.368  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 10:32:29.368  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 10:32:29.368  4122  4141 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 10:32:29.371  3763  4198 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
,09-07 10:32:29.372  3763  4198 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
09-07 10:32:29.372  3763  4198 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 10:32:29.373  4122  4138 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 10:32:29.373  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 10:32:29.374  3763  4199 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
,09-07 10:32:29.374  3763  4199 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
09-07 10:32:29.374  3763  4199 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 10:32:29.375  3763  3814 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 10:32:29.375  3763  3814 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 10:32:29.375  3763  3814 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 10:32:29.375  3763  3814 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-07 10:32:29.376  3763  3814 D com.test.thalitest.ThaliTestRunner: Total duration: 21729 ms
09-07 10:32:29.377  3763  3814 I jxcore-log: *Native tests were executed*
09-07 10:32:29.377  3763  3814 I jxcore-log: 
,09-07 10:32:29.377  1705  4191 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-07 10:32:29.377  3763  3814 I jxcore-log: Total number of executed tests:  80
09-07 10:32:29.377  3763  3814 I jxcore-log: 
,09-07 10:32:29.377  3763  3814 I jxcore-log: Number of passed tests:  80
09-07 10:32:29.377  3763  3814 I jxcore-log: 
,09-07 10:32:29.377  3763  3814 I jxcore-log: Number of failed tests:  0
09-07 10:32:29.377  3763  3814 I jxcore-log: 
,09-07 10:32:29.378  3763  3814 I jxcore-log: Number of ignored tests:  0
09-07 10:32:29.378  3763  3814 I jxcore-log: 
,09-07 10:32:29.378  3763  3814 I jxcore-log: Total duration:  21729
09-07 10:32:29.378  3763  3814 I jxcore-log: 
09-07 10:32:29.378  3763  3814 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 10:32:29.378  3763  3814 I jxcore-log: ,
09-07 10:32:29.387  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.387  3763  3814 I jxcore-log: 
09-07 10:32:29.387  3763  3763 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 10:32:29.389  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.389  3763  3814 I jxcore-log: 
09-07 10:32:29.390  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.390  3763  3814 I jxcore-log: 
09-07 10:32:29.391  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.391  3763  3814 I jxcore-log: 
09-07 10:32:29.392  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.392  3763  3814 I jxcore-log: 
09-07 10:32:29.394  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.394  3763  3814 I jxcore-log: 
09-07 10:32:29.400  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.400  3763  3814 I jxcore-log: 
09-07 10:32:29.402  1705  1705 D SystemUpdateService: onDestroy
,09-07 10:32:29.404  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.404  3763  3814 I jxcore-log: 
,09-07 10:32:29.405  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.405  3763  3814 I jxcore-log: 
09-07 10:32:29.405  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:29.405  3763  3814 I jxcore-log: 
09-07 10:32:29.406  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:32:29.406  3763  3814 I jxcore-log: 
09-07 10:32:29.407  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:32:29.407  3763  3814 I jxcore-log: 
09-07 10:32:29.407  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.407  3763  3814 I jxcore-log: 
09-07 10:32:29.408  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.408  3763  3814 I jxcore-log: 
09-07 10:32:29.409  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.409  3763  3814 I jxcore-log: 
09-07 10:32:29.409  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.409  3763  3814 I jxcore-log: 
09-07 10:32:29.410  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.410  3763  3814 I jxcore-log: 
09-07 10:32:29.411  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.411  3763  3814 I jxcore-log: 
09-07 10:32:29.411  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.411  3763  3814 I jxcore-log: 
09-07 10:32:29.412  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.412  3763  3814 I jxcore-log: 
,09-07 10:32:29.412  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.412  3763  3814 I jxcore-log: 
09-07 10:32:29.413  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:29.413  3763  3814 I jxcore-log: 
09-07 10:32:29.413  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:29.413  3763  3814 I jxcore-log: 
,09-07 10:32:29.414  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:29.414  3763  3814 I jxcore-log: 
09-07 10:32:29.414  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.414  3763  3814 I jxcore-log: 
09-07 10:32:29.414  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.414  3763  3814 I jxcore-log: 
09-07 10:32:29.415  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.415  3763  3814 I jxcore-log: 
09-07 10:32:29.415  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.415  3763  3814 I jxcore-log: 
09-07 10:32:29.416  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.416  3763  3814 I jxcore-log: 
09-07 10:32:29.417  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:29.417  3763  3814 I jxcore-log: 
,09-07 10:32:29.464  2284  4194 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 10:32:29.702  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:29.703  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:29.703  3763  3814 I jxcore-log: 
,09-07 10:32:29.769  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:29.770  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:29.770  3763  3814 I jxcore-log: 
,09-07 10:32:29.842  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:29.846  3763  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:29.846  3763  3814 I jxcore-log: 
,09-07 10:32:30.050  4201  4201 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-07 10:32:30.055  4201  4201 D AndroidRuntime: CheckJNI is OFF
,09-07 10:32:30.099  4201  4201 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-07 10:32:30.142   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-07 10:32:30.148  4201  4201 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 10:32:30.171  4201  4201 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 10:32:30.180   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-07 10:32:30.181   874   887 I ActivityManager: Killing 3763:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-07 10:32:30.295   874   897 W PackageSettings: Skipping PackageSetting{96450ec com.example.hello/10273} due to missing metadata
,09-07 10:32:30.312   874   885 D GraphicsStats: Buffer count: 2
,09-07 10:32:30.312   874  3066 I WindowState: WIN DEATH: Window{460289d u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 10:32:30.313   874  1310 D WifiService: Client connection lost with reason: 4
,09-07 10:32:30.338   874   887 W ActivityManager: Force removing ActivityRecord{729b15a u0 com.test.thalitest/.MainActivity t4}: app died, no saved state
,09-07 10:32:30.344   874   897 I art     : Starting a blocking GC Explicit
,09-07 10:32:30.359   874   885 W ActivityManager: Spurious death for ProcessRecord{c6b22a2 0:com.test.thalitest/u0a0}, curProc for 3763: null
,09-07 10:32:30.384   874  3066 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3763 uid 10000
,09-07 10:32:30.386  1880  1880 I Keyboard.Facilitator: onFinishInput()
,09-07 10:32:30.411   874   897 I art     : Explicit concurrent mark sweep GC freed 16284(1050KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.007ms total 63.425ms
,09-07 10:32:30.433   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 10:32:30.442  4201  4201 I art     : System.exit called, status: 0
,09-07 10:32:30.442  4201  4201 I AndroidRuntime: VM exiting with result code 0.
,09-07 10:32:30.448   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-07 10:32:30.450  2013  4217 I MicroRecognitionRnrImpl: Starting detection.
09-07 10:32:30.451  2013  4219 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@25bd1d3
09-07 10:32:30.452   377  4221 I AudioFlinger: AudioFlinger's thread 0xb1d40000 ready to run
09-07 10:32:30.460   377  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 10:32:30.461  2013  4219 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@25bd1d3
,09-07 10:32:30.471   377  4221 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,09-07 10:32:30.471   377  4221 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
09-07 10:32:30.471   377  4221 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,09-07 10:32:30.476  4122  4122 D BluetoothMapAppObserver: onReceive
,09-07 10:32:30.476  4122  4122 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-07 10:32:30.478   377  4221 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-07 10:32:30.481  2027  2298 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 10:32:30.485  1880  1880 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-07 10:32:30.487  1880  4222 I Keyboard.Facilitator.DecoderInitializer: run()
,09-07 10:32:30.488   874  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 10:32:30.492  1880  4222 I Decoder : createOrResetDecoder
,09-07 10:32:30.524  1951  1951 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-07 10:32:30.544  3635  3635 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 10:32:30.545  1506  1506 I ConfigService: onCreate
,09-07 10:32:30.558  2013  2013 I HotwordWorkerImpl: onReady
,09-07 10:32:30.581   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 10:32:30.588   874   884 I ActivityManager: Start proc 4227:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 10:32:30.603  1880  4222 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-07 10:32:30.621  1963  2049 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-07 10:32:30.624   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-07 10:32:30.624   874   886 E PackageManager: Failed to write settings, restoring backup
09-07 10:32:30.624   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 10:32:30.624   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 10:32:30.624   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 10:32:30.624   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 10:32:30.624   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 10:32:30.624   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:30.624   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.624   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 10:32:30.628   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-07 10:32:30.628   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 10:32:30.628   874   8,87 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 10:32:30.628   874   887 E DropBoxManagerService: 	... 13 more
,09-07 10:32:30.632  4227  4227 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 10:32:30.635  1880  4222 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-07 10:32:30.635   874  1950 I ActivityManager: Start proc 4240:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-07 10:32:30.635  1963  2049 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 10:32:30.635  1963  2049 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1963
09-07 10:32:30.635  1963  2049 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.635  1963  2049 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 10:32:30.637   874  1958 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 10:32:30.640  2013  2026 W SearchService: Abort, client detached.
09-07 10:32:30.641   874  4248 E DropBoxManagerService: Can't write: system_app_crash
09-07 10:32:30.641   874  4248 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 10:32:30.641   874  4248 E DropBoxManagerService: 	... 5 more
09-07 10:32:30.642  2013  2013 I HotwordDetector: Closing mic
09-07 10:32:30.642  2013  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@25bd1d3
09-07 10:32:30.643  2013  4219 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-07 10:32:30.644  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 10:32:30.644  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 10:32:30.645  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 10:32:30.645  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 10:32:30.646  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 10:32:30.646  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 10:32:30.647  1880  4222 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 10:32:30.647  1880  4222 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 10:32:30.647  1880  4222 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 10:32:30.647  1880  4222 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 10:32:30.647  1880  4222 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 10:32:30.647  1880  4222 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-07 10:32:30.654   874  4253 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 10:32:30.662  2013  4254 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,09-07 10:32:30.691   874  4253 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 10:32:30.691   874  4253 I Adreno  : Build Date                       : 10/20/15
09-07 10:32:30.691   874  4253 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 10:32:30.691   874  4253 I Adreno  : Local Branch                     : M14
09-07 10:32:30.691   874  4253 I Adreno  : Remote Branch                    : 
09-07 10:32:30.691   874  4253 I Adreno  : Remote Branch                    : 
09-07 10:32:30.691   874  4253 I Adreno  : Reconstruct Branch               : 
,09-07 10:32:30.696   874  4253 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 10:32:30.700  4227  4227 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 10:32:30.702   377  4221 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-07 10:32:30.702   377  4221 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 10:32:30.709   377  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-07 10:32:30.711  2013  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-07 10:32:30.712  2013  4217 I MicroRecognitionRnrImpl: Detection finished
,09-07 10:32:30.729  4227  4263 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 10:32:30.736   874   885 I ActivityManager: Start proc 4264:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.752  4227  4256 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.752  4227  4256 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 10:32:30.783  4264  4264 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-07 10:32:30.789  1705  4277 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 10:32:30.790  1705  4277 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 10:32:30.799  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-07 10:32:30.800  1506  1506 D AndroidRuntime: Shutting down VM
09-07 10:32:30.801  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
09-07 10:32:30.801  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
09-07 10:32:30.801  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 10:32:30.801  1506  1506 E AndroidRuntime: 	... 8 more
,09-07 10:32:30.805   874  4281 E DropBoxManagerService: Can't write: system_app_crash
09-07 10:32:30.805   874  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 10:32:30.805   874  4281 E DropBoxManagerService: 	... 5 more
,09-07 10:32:30.828  4227  4256 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-07 10:32:30.832  4227  4263 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.832  4227  4263 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 10:32:30.833  4227  4263 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 10:32:30.833  4227  4263 E AndroidRuntime: Process: android.process.acore, PID: 4227
09-07 10:32:30.833  4227  4263 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 10:32:30.833  4227  4263 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 10:32:30.834  4227  4256 I Process : Sending signal. PID: 4227 SIG: 9
,09-07 10:32:30.835   874  4282 E DropBoxManagerService: Can't write: system_app_crash
09-07 10:32:30.835   874  4282 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 10:32:30.835   874  4282 E DropBoxManagerService: 	... 5 more
,09-07 10:32:30.873   874  1701 I ActivityManager: Process android.process.acore (pid 4227) has died
,09-07 10:32:30.875   874  1701 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-07 10:32:30.989   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
09-07 10:32:30.989   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
09-07 10:32:30.989   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
09-07 10:32:30.989   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,09-07 10:32:30.989   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
09-07 10:32:30.989   281   281 E qdoverlay: MdpCtrl close error in unset

```
