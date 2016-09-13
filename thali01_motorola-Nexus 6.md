#### Test 846186378976bee_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,09-13 13:49:54.077   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-13 13:49:54.767  3788  3788 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 13:49:54.772  3788  3788 D AndroidRuntime: CheckJNI is OFF
09-13 13:49:54.815  3788  3788 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 13:49:54.866  3788  3788 I Radio-JNI: register_android_hardware_Radio DONE
09-13 13:49:54.888  3788  3788 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 13:49:54.892   874  1961 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 13:49:54.916  2019  2032 W SearchService: Abort, client detached.
09-13 13:49:54.927  2019  2341 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5c8a393
09-13 13:49:54.928  2019  2349 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 13:49:54.926  2019  2019 I HotwordDetector: Closing mic
09-13 13:49:54.935  3788  3788 D AndroidRuntime: Shutting down VM
09-13 13:49:54.968   874  1383 I ActivityManager: Start proc 3797:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 13:49:54.978   378  2351 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 13:49:54.982   378  2351 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 13:49:54.993   378  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 13:49:54.994  2019  2347 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 13:49:54.995  2019  2348 I MicroRecognitionRnrImpl: Detection finished
09-13 13:49:55.042  3797  3797 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 13:49:55.076  3797  3797 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 13:49:55.083  3797  3797 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4997-4999)
09-13 13:49:55.083  3797  3797 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:49:55.095  3797  3797 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2bb3946}
09-13 13:49:55.095  3797  3797 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:49:55.096  3797  3797 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 13:49:55.113  3797  3797 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 13:49:55.117  3797  3797 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 13:49:55.141  3797  3797 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 13:49:55.156  3797  3797 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 13:49:55.156  3797  3797 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 13:49:55.156  3797  3797 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 13:49:55.156  3797  3797 I Adreno  : Build Date                       : 10/20/15
09-13 13:49:55.156  3797  3797 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 13:49:55.156  3797  3797 I Adreno  : Local Branch                     : M14
09-13 13:49:55.156  3797  3797 I Adreno  : Remote Branch                    : 
09-13 13:49:55.156  3797  3797 I Adreno  : Remote Branch                    : 
09-13 13:49:55.156  3797  3797 I Adreno  : Reconstruct Branch               : 
,09-13 13:49:55.229   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36491dc:true
09-13 13:49:55.265  3797  3797 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 13:49:55.280  3797  3797 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-13 13:49:55.347  3797  3837 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-13 13:49:55.355  3797  3823 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-13 13:49:55.385  3797  3837 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 13:49:55.407  1882  1882 I Keyboard.Facilitator: onFinishInput()
09-13 13:49:55.465   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +516ms
09-13 13:49:55.560  3797  3797 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3797
09-13 13:49:55.706  3797  3797 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-13 13:49:55.779   874  1527 I ActivityManager: Killing 2983:com.google.android.calendar/u0a37 (adj 15): empty #17
09-13 13:49:55.821   874  1527 I ActivityManager: Killing 3199:com.google.android.gm/u0a78 (adj 15): empty #18
09-13 13:49:55.901  3797  3840 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1680148176
09-13 13:49:55.906  3797  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 13:49:55.906  3797  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 13:49:55.906  3797  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 13:49:55.906  3797  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 13:49:55.906  3797  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 13:49:55.906  3797  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4bc1ea added. We now have 1 listener(s)
09-13 13:49:55.909  3797  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-13 13:49:55.910  3797  3840 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:49:55.911  3797  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:49:55.911  3797  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 13:49:55.916  3797  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53e1a51 added. We now have 1 listener(s)
09-13 13:49:55.916  3797  3840 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:49:55.919   874  1314 D WifiService: New client listening to asynchronous messages
09-13 13:49:55.921  3797  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:49:55.921  3797  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 13:49:55.921  3797  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 13:49:55.921  3797  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 13:49:55.921  3797  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 13:49:55.925  3797  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:49:55.925  3797  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-13 13:49:55.929  3797  3840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:49:55.929  3797  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:49:55.929  3797  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 13:49:55.929  3797  3840 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:49:55.930  3797  3840 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 13:49:56.060  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:49:56.063  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:49:56.066  3797  3797 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 13:49:56.248  3516  3526 D Finsky  : [268] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
09-13 13:49:56.262  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:49:56.293  1513  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 13:49:56.294  1513  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 13:49:56.294  1513  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:49:56.294  1513  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 13:49:56.319  3516  3526 D Finsky  : [268] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
09-13 13:49:56.916  3797  3849 W jxcore-log: Initializing JXcore engine
09-13 13:49:56.917  3797  3849 W jxcore-log: JXcore engine is ready
09-13 13:49:56.956  3849  3849 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8798 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-13 13:49:56.956  3849  3849 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11615]" dev="sockfs" ino=11615 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 13:49:56.956  3849  3849 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 13:49:56.956  3849  3849 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25366]" dev="sockfs" ino=25366 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 13:49:56.968  3797  3849 W jxcore-log: Starting JXcore engine
09-13 13:49:57.062  3797  3849 W jxcore-log: Platform android
09-13 13:49:57.062  3797  3849 W jxcore-log: 
09-13 13:49:57.062  3797  3849 W jxcore-log: Process ARCH arm
09-13 13:49:57.062  3797  3849 W jxcore-log: 
09-13 13:49:57.317  3797  3849 I jxcore-log: JXcore Cordova bridge is ready!
09-13 13:49:57.317  3797  3849 I jxcore-log: 
09-13 13:49:57.317  3797  3849 W jxcore-log: JXcore engine is started
09-13 13:49:57.323  3797  3840 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 13:49:57.326  3797  3797 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-13 13:49:57.379  1513  1513 I ConfigService: onDestroy
,09-13 13:50:00.120   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:06.123   874   887 I ActivityManager: Waited long enough for: ServiceRecord{ecf44c0 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-13 13:50:06.155   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:06.575  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:06.580  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:06.583  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:06.607  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:50:06.607  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 13:50:06.607  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:50:06.607  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:50:06.640  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:50:06.640  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 13:50:06.640  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-13 13:50:11.268  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 13:50:11.268  3797  3849 I jxcore-log: 
,09-13 13:50:11.271  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 13:50:11.271  3797  3849 I jxcore-log: 
,09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:11.279  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:11.282  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:11.284  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 13:50:11.284  3797  3849 I jxcore-log: 
,09-13 13:50:11.286  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 13:50:11.286  3797  3849 I jxcore-log: 
,09-13 13:50:11.637  3797  3849 I jxcore-log: Running unit tests
09-13 13:50:11.637  3797  3849 I jxcore-log: 
,09-13 13:50:11.638  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:50:11.638  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae1de6a added. We now have 2 listener(s)
,09-13 13:50:11.639  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:50:11.640  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 13:50:11.640  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:50:11.640  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:50:11.640  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ec2f5b added. We now have 2 listener(s)
09-13 13:50:11.640  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:50:11.646  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:50:11.655  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:11.674  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:11.678  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:11.679  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:50:11.680  3797  3849 D executeNativeTests: Running unit tests
,09-13 13:50:11.684  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:11.688  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:11.770  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:50:11.770  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 added. We now have 3 listener(s)
,09-13 13:50:11.771  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:50:11.771  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 13:50:11.771  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:50:11.771  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:50:11.771  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 added. We now have 3 listener(s)
,09-13 13:50:11.771  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:50:11.772  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:50:11.777  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:11.788  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:11.794  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:11.794  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:50:11.797  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:50:11.797  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:50:11.797  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 13:50:11.797  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:50:11.798  3797  3849 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 13:50:11.799  3797  3849 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 13:50:11.799  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 13:50:11.799  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:50:11.799  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:50:11.799  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:50:11.800  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:11.800  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:11.800  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:11.801  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:11.803  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:11.803  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.804  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:50:11.804  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 13:50:11.804  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 removed from the list
09-13 13:50:11.804  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:11.804  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 removed from the list
,09-13 13:50:11.808  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:11.808  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:11.808  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.810  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.810  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:11.812  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:11.812  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:11.812  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:11.812  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:11.815  3797  3849 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 13:50:11.818  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:11.818  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:11.818  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:11.818  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:11.819  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.819  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.823  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:11.824  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:11.824  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:11.824  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:11.824  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.825  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.825  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.825  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.828  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:11.828  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:11.828  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:11.829  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:11.835  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 13:50:11.835  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 13:50:11.835  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 13:50:11.836  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 13:50:11.837  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 13:50:11.838  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 13:50:11.838  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 13:50:11.838  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:11.838  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:11.838  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:11.838  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:11.838  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.838  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.838  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:11.838  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:11.838  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:11.838  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:11.838  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.839  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.839  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:11.839  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:11.841  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:11.841  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:11.841  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:11.842  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:11.844  3797  3849 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 13:50:11.848  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:11.860  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:50:11.865  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:11.865  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:50:11.865  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:50:11.865  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:50:11.866  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:50:11.866  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:50:11.866  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:50:11.870  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 13:50:11.870  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:50:11.871  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:11.888  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:11.889  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 13:50:11.891  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:50:11.892  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:50:11.894  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-13 13:50:11.899  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 13:50:11.899  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 13:50:11.899  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:50:11.900  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 13:50:11.901  3797  3849 D BluetoothAdapter: STATE_ON
09-13 13:50:11.905  2671  2806 D BtGatt.GattService: registerClient() - UUID=0935f3e1-fcbf-4e5e-9d5b-e4e9f96ee3f0
09-13 13:50:11.906  2671  2691 D BtGatt.GattService: onClientRegistered() - UUID=0935f3e1-fcbf-4e5e-9d5b-e4e9f96ee3f0, clientIf=5
09-13 13:50:11.907  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 13:50:11.908  2671  2829 D BtGatt.GattService: start scan with filters
09-13 13:50:11.911  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 13:50:11.911  2671  2696 D BtGatt.ScanManager: handling starting scan
09-13 13:50:11.911  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:50:11.912  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:50:11.912  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 13:50:11.913  2671  2696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
09-13 13:50:11.914  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:50:11.915  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 13:50:11.915  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:50:11.916  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 13:50:11.919  3797  3849 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 13:50:11.920  2671  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 13:50:11.920  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:11.921  2671  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 13:50:11.926  2671  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 13:50:11.926  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:11.927  2671  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:50:11.927  2671  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:50:11.937  2671  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:50:11.937  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:11.943  2671  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 13:50:11.943  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:12.219   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:12.417  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 13:50:12.417  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:50:12.418  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:50:12.541   874  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 13:50:13.452  2671  2671 D BtGatt.ScanManager: awakened up at time 123369
,09-13 13:50:13.457  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:13.504  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-13 13:50:13.505  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:13.505  2671  2691 D BtGatt.GattService: current time is 123422669647
,09-13 13:50:13.508  2671  2691 D BtGatt.GattService: Batch record : [19, 45, -92, 93, -2, 95, 1, -128, -88, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -81, 45, -78, -102, 125, -33, -22, 96, -47, -76, 108, 34, 58, 0, 71, -122, -77, 84, 69, -12, 1, -128, -101, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -93, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -106, -15, -31, -128, 20, -7, 1, -128, -107, 3, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -50, -6, 0, 3, 2, -25, 21, 62, 61, -123, -61, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:50:13.513  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -81, 45, -78, -102, 125, -33, -22, 96, -47, -76, 108, 34, 58]
,09-13 13:50:13.516  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:50:13.517  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 13:50:13.519  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 13:50:13.521  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:50:13.521  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -50, -6, 0, 3, 2, -25, 21, 62, 61, -123, -61]
09-13 13:50:13.521  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:50:15.009  2671  2671 D BtGatt.ScanManager: awakened up at time 124926
,09-13 13:50:15.012  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:15.041  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-13 13:50:15.041  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:15.042  2671  2691 D BtGatt.GattService: current time is 124958929018,
09-13 13:50:15.042  2671  2691 D BtGatt.GattService: Batch record : [19, 45, -92, 93, -2, 95, 1, -128, -95, 2, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -81, 45, -78, -102, 125, -33, -22, 96, -47, -76, 108, 34, 58, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:50:15.042  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -81, 45, -78, -102, 125, -33, -22, 96, -47, -76, 108, 34, 58]
09-13 13:50:15.042  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:50:16.545  2671  2671 D BtGatt.ScanManager: awakened up at time 126462
,09-13 13:50:16.548  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:16.596  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-13 13:50:16.596  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:16.596  2671  2691 D BtGatt.GattService: current time is 126513733861
,09-13 13:50:16.597  2671  2691 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -93, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 19, 45, -92, 93, -2, 95, 1, -128, -94, 15, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -81, 45, -78, -102, 125, -33, -22, 96, -47, -76, 108, 34, 58, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -87, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -87, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:50:16.598  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:50:16.599  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -81, 45, -78, -102, 125, -33, -22, 96, -47, -76, 108, 34, 58]
,09-13 13:50:16.600  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:50:16.601  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91],
,09-13 13:50:16.601  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 13:50:16.602  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 13:50:16.603  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:50:16.929  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:50:16.930  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:16.930  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:50:16.930  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:16.931  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:50:16.931  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:50:16.932  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:50:16.932  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:50:16.932  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:50:16.934  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:50:16.934  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 13:50:16.937  3797  3849 D BluetoothAdapter: STATE_ON
,09-13 13:50:16.940  2671  2829 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:50:16.943  2671  2806 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:50:16.945  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:50:16.945  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:50:16.946  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 13:50:16.947  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:50:16.947  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 13:50:16.951  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:50:16.953  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 13:50:16.954  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:50:16.954  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:50:16.956  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:50:16.960  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:50:16.960  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:16.960  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:16.961  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:50:16.961  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:50:16.961  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:50:16.961  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
,09-13 13:50:16.961  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:16.962  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:16.962  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:16.962  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:16.964  2671  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 13:50:16.965  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:16.965  2671  2696 D BtGatt.ScanManager: stopping BLe Batch
,09-13 13:50:16.981  2671  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:50:16.982  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:16.982  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:17.001  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:50:17.001  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:17.462  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:50:18.285   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:20.896  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:20.901  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:20.983  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:50:20.984  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:50:20.984  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:50:20.985  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:50:21.048  3553  3864 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:50:21.048  3553  3864 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:50:21.048  3553  3864 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	... 12 more
09-13 13:50:21.048  3553  3864 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at fal.a(PG:38)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:50:21.048  3553  3864 E HttpOperation: 	... 14 more
,09-13 13:50:21.121  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:50:21.121  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 13:50:21.121  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:50:21.121  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:50:21.145  3553  3864 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:50:21.145  3553  3864 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at hec.a(PG:42)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at hee.a(PG:102)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at czr.a(PG:65)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at kka.a(PG:108)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:50:21.145  3553  3864 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	... 15 more
09-13 13:50:21.145  3553  3864 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at fal.a(PG:38)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:50:21.145  3553  3864 E HttpOperation: 	... 17 more
,09-13 13:50:21.146  3553  3864 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:50:21.146  3553  3864 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	... 15 more
09-13 13:50:21.146  3553  3864 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:50:21.146  3553  3864 E ExperimentLoader: 	... 17 more
,09-13 13:50:21.275   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130538, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:50:21.308   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:21.964  3797  3849 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 13:50:21.971  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:21.985  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:21.991  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:21.992  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:50:21.993  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:50:21.993  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 13:50:21.993  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 13:50:21.994  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:50:21.994  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 13:50:22.005  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:50:22.005  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:50:22.005  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:22.014  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:22.021  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:50:22.024  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 13:50:22.024  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:50:22.037  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 13:50:22.037  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 13:50:22.038  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 13:50:22.040  3797  3849 D BluetoothAdapter: STATE_ON
,09-13 13:50:22.048  2671  2683 D BtGatt.GattService: registerClient() - UUID=25d402e3-a363-4eff-832f-11ef00371c91
,09-13 13:50:22.049  2671  2691 D BtGatt.GattService: onClientRegistered() - UUID=25d402e3-a363-4eff-832f-11ef00371c91, clientIf=5
,09-13 13:50:22.051  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 13:50:22.053  2671  2682 D BtGatt.GattService: start scan with filters
,09-13 13:50:22.062  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:50:22.062  2671  2696 D BtGatt.ScanManager: handling starting scan
09-13 13:50:22.063  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 13:50:22.063  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:50:22.064  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:50:22.074  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:50:22.074  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:50:22.074  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:50:22.080  2671  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 13:50:22.081  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:22.081  2671  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 13:50:22.082  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:50:22.092  3797  3849 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 13:50:22.096  2671  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 13:50:22.096  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:22.096  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:22.096  3797  3849 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 13:50:22.096  2671  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:50:22.097  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:22.097  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:50:22.099  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:22.097  2671  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 13:50:22.099  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:50:22.099  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 13:50:22.099  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:50:22.099  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 13:50:22.100  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:50:22.103  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:50:22.103  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 13:50:22.104  3797  3849 D BluetoothAdapter: STATE_ON
09-13 13:50:22.105  2671  2806 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:50:22.105  2671  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:50:22.106  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 13:50:22.106  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:50:22.106  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 13:50:22.106  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:50:22.106  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 13:50:22.107  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:50:22.107  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 13:50:22.108  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:50:22.108  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 13:50:22.109  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:50:22.110  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:50:22.110  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:22.110  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:50:22.110  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:50:22.110  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:22.110  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:22.110  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:22.110  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:22.110  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 13:50:22.110  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:22.110  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:50:22.111  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:22.111  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:22.113  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:22.113  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 13:50:22.113  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:22.113  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:22.114  3797  3849 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 13:50:22.115  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:22.127  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:22.128  2671  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 13:50:22.128  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:22.129  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:22.129  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:50:22.130  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 13:50:22.130  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 13:50:22.130  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 13:50:22.130  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:50:22.130  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:50:22.134  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 13:50:22.134  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:50:22.135  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:22.135  2671  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 13:50:22.136  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:22.138  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:22.138  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 13:50:22.139  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:50:22.139  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:50:22.143  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 13:50:22.143  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:50:22.143  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 13:50:22.144  3797  3849 D BluetoothAdapter: STATE_ON
09-13 13:50:22.146  2671  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:50:22.146  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:22.146  2671  2683 D BtGatt.GattService: registerClient() - UUID=4ca0ce8f-ccd0-48c2-8c29-f7e804e808f9
09-13 13:50:22.146  2671  2696 D BtGatt.ScanManager: stopping BLe Batch
09-13 13:50:22.147  2671  2691 D BtGatt.GattService: onClientRegistered() - UUID=4ca0ce8f-ccd0-48c2-8c29-f7e804e808f9, clientIf=5
09-13 13:50:22.147  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 13:50:22.148  2671  2682 D BtGatt.GattService: start scan with filters
,09-13 13:50:22.151  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:50:22.151  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:50:22.151  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:50:22.151  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:50:22.153  2671  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:50:22.153  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:22.153  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 13:50:22.154  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:50:22.154  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:50:22.155  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:50:22.156  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:50:22.159  3797  3849 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 13:50:22.159  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 13:50:22.159  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:22.161  2671  2696 D BtGatt.ScanManager: handling starting scan
,09-13 13:50:22.167  2671  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 13:50:22.167  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:22.167  2671  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 13:50:22.172  2671  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 13:50:22.172  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:22.172  2671  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:50:22.173  2671  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:50:22.182  2671  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:50:22.183  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:22.188  2671  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 13:50:22.188  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:22.655  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 13:50:22.656  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 13:50:22.656  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:50:23.695  2671  2671 D BtGatt.ScanManager: awakened up at time 133612
,09-13 13:50:23.697  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:23.760  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-13 13:50:23.760  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:23.761  2671  2691 D BtGatt.GattService: current time is 133677994054
09-13 13:50:23.762  2671  2691 D BtGatt.GattService: Batch record : [19, 45, -92, 93, -2, 95, 1, -128, -96, 3, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -80, 45, -95, 17, 20, -13, -2, 42, -101, 18, -18, 9, -30, 0, 116, -43, -111, -91, -20, -29, 1, -128, -101, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -94, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -100, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 19, 45, -92, 93, -2, 95, 1, -128, -97, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -80, 45, -95, 17, 20, -13, -2, 42, -101, 18, -18, 9, -30, 0]
09-13 13:50:23.763  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -80, 45, -95, 17, 20, -13, -2, 42, -101, 18, -18, 9, -30]
,09-13 13:50:23.763  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 13:50:23.768  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 13:50:23.769  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 13:50:23.770  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 13:50:23.770  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 13:50:23.771  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:50:23.772  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -80, 45, -95, 17, 20, -13, -2, 42, -101, 18, -18, 9, -30]
,09-13 13:50:25.264  2671  2671 D BtGatt.ScanManager: awakened up at time 135181
,09-13 13:50:25.267  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:25.297  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-13 13:50:25.297  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:25.298  2671  2691 D BtGatt.GattService: current time is 135215153218
09-13 13:50:25.299  2671  2691 D BtGatt.GattService: Batch record : [19, 45, -92, 93, -2, 95, 1, -128, -108, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -79, 45, -123, -96, 33, -116, -71, 95, -96, 60, -122, 61, 48, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 13:50:25.300  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -79, 45, -123, -96, 33, -116, -71, 95, -96, 60, -122, 61, 48]
,09-13 13:50:25.300  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 13:50:25.301  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 13:50:26.801  2671  2671 D BtGatt.ScanManager: awakened up at time 136717
,09-13 13:50:26.803  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:26.891  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-13 13:50:26.891  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:26.891  2671  2691 D BtGatt.GattService: current time is 136808634626
09-13 13:50:26.892  2671  2691 D BtGatt.GattService: Batch record : [19, 45, -92, 93, -2, 95, 1, -128, -104, 10, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -79, 45, -123, -96, 33, -116, -71, 95, -96, 60, -122, 61, 48, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -88, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -86, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -93, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 13:50:26.893  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -79, 45, -123, -96, 33, -116, -71, 95, -96, 60, -122, 61, 48]
09-13 13:50:26.893  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 13:50:26.894  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 13:50:26.895  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 13:50:26.895  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 13:50:26.896  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:50:26.897  2671  2691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:50:27.160  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:50:27.160  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:27.161  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 13:50:27.161  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:27.161  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 13:50:27.161  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:50:27.162  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 13:50:27.162  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:50:27.162  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 13:50:27.163  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 13:50:27.163  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 13:50:27.167  3797  3849 D BluetoothAdapter: STATE_ON
,09-13 13:50:27.169  2671  2683 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:50:27.174  2671  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 13:50:27.175  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:27.178  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 13:50:27.178  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:50:27.178  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 13:50:27.179  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 13:50:27.179  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 13:50:27.185  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:50:27.186  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:50:27.186  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 13:50:27.187  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 13:50:27.190  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:50:27.191  2671  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:50:27.191  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:27.191  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:50:27.192  2671  2696 D BtGatt.ScanManager: stopping BLe Batch
09-13 13:50:27.194  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:50:27.195  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:50:27.195  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:50:27.196  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:50:27.203  2671  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:50:27.203  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:50:27.203  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:50:27.211  2671  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:50:27.211  2671  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:50:27.228  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:50:27.228  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 13:50:27.229  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:50:27.229  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:50:27.247  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:50:27.247  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 13:50:27.248  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-13 13:50:27.361   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:27.697  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:50:27.698  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:27.698  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:50:29.214   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:50:30.392   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:32.198  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:50:32.199  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:50:32.199  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:32.199  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.200  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.200  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:50:32.200  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.201  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:32.201  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.201  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:32.203  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.205  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:32.205  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.209  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:32.210  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:50:32.210  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.210  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.212  3797  3849 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 13:50:32.215  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.216  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:50:32.216  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.216  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:50:32.217  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.217  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.217  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.218  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.218  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.218  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:32.218  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.218  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.219  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.219  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:32.221  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:32.221  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.222  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.222  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:32.225  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 13:50:32.225  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.226  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.226  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:32.226  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.226  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.226  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:32.227  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.227  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.227  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.227  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:32.227  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.228  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.228  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.228  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:32.230  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:50:32.230  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.230  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.231  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:32.232  3797  3849 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 13:50:32.232  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:50:32.233  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.233  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.233  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.234  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:32.234  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.234  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.234  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.234  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:32.234  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.235  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.235  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.235  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:32.235  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:32.237  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:50:32.237  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.238  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.238  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:32.239  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 13:50:32.239  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.240  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.240  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:32.240  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.240  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.240  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.241  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
,09-13 13:50:32.241  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.241  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.241  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:32.241  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.242  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.242  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.242  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:32.244  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:50:32.244  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.244  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:32.244  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.245  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:50:32.245  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:50:32.245  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:50:32.245  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 13:50:32.246  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:50:32.246  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:50:32.246  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:50:32.246  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:50:32.246  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:50:32.247  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.247  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:50:32.247  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.247  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.247  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.247  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.247  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.247  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.247  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.247  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.248  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.248  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.248  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.248  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.249  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:32.249  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.249  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.249  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.250  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:50:32.251  3797  3849 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 13:50:32.251  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 13:50:32.258  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:50:32.258  3797  3849 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 13:50:32.258  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 13:50:32.258  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 13:50:32.258  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 13:50:32.258  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 13:50:32.258  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 13:50:32.259  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 13:50:32.260  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 13:50:32.261  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 13:50:32.261  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 13:50:32.261  3797  3849 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:50:32.262  3797  3849 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 13:50:32.262  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:50:32.262  3797  3849 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:50:32.262  3797  3849 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 13:50:32.263  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:50:32.263  3797  3849 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:50:32.263  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 13:50:32.265  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 13:50:32.267  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 13:50:32.267  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 13:50:32.268  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 13:50:32.268  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 13:50:32.268  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 13:50:32.268  3797  3849 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:50:32.268  3797  3849 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 13:50:32.269  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.269  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.269  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.270  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.270  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.270  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.270  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 13:50:32.272  3797  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
09-13 13:50:32.273  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.273  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.273  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.273  3797  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
09-13 13:50:32.274  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.274  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.274  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.274  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.274  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.277  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:32.277  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.277  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.277  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.278  3797  3849 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 13:50:32.279  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.279  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.279  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.279  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.279  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.279  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.279  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.279  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.279  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.279  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.280  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.280  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.280  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.280  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.280  3797  3867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:50:32.281  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:32.281  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.281  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.282  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.283  3797  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 13:50:32.283  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.283  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.283  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.283  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.284  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.284  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.284  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.284  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.284  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.284  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.284  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.284  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.284  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.284  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.286  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:32.286  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.286  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.286  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.287  3797  3849 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 13:50:32.287  3797  3849 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 13:50:32.287  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:50:32.287  3797  3849 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 13:50:32.287  3797  3849 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 13:50:32.287  3797  3849 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 13:50:32.288  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:50:32.288  3797  3849 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 13:50:32.288  3797  3849 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 13:50:32.288  3797  3849 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 13:50:32.288  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:50:32.288  3797  3849 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 13:50:32.290  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:32.290  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:32.290  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:32.291  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.291  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.291  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.291  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.291  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.291  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.291  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.291  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.291  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.291  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.292  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.293  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-13 13:50:32.293  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:32.293  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.293  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.294  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:32.294  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.294  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:32.295  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:32.295  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:32.295  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:32.295  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:32.295  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:32.295  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:36.431   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:37.296  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:37.296  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.297  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:50:37.297  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.297  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.298  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:37.298  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:37.299  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:50:37.299  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:37.299  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:50:37.300  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.300  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:37.300  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
,09-13 13:50:37.300  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.301  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:37.301  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:37.301  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.302  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:37.302  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.302  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.306  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:37.307  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:37.307  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.307  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.312  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 13:50:37.314  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:50:37.315  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 13:50:37.316  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 13:50:37.316  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 13:50:37.316  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 13:50:37.316  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:50:37.316  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 13:50:37.317  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:37.317  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 13:50:37.317  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 13:50:37.317  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 13:50:37.317  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.317  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 13:50:37.317  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:37.317  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.318  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:50:37.317  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 13:50:37.318  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:50:37.318  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 13:50:37.318  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.319  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:37.320  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:50:37.320  3797  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 13:50:37.320  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:37.321  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:37.321  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-13 13:50:37.322  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-13 13:50:37.321  3797  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 13:50:37.322  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:50:37.322  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:37.322  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:50:37.322  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.326  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.326  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:50:37.326  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:37.326  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:37.326  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.326  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:37.326  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 13:50:37.326  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.326  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.326  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.326  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:37.328  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:37.328  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:37.328  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:37.328  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.330  3797  3849 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 13:50:37.330  3797  3849 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 13:50:37.330  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 13:50:37.330  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 13:50:37.331  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 13:50:37.331  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:50:37.331  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:50:37.331  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:37.331  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:37.331  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-13 13:50:37.331  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:37.331  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:37.331  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:37.331  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.331  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:37.332  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:37.332  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.332  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.332  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.333  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:50:37.333  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:37.333  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.333  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:37.340  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:37.340  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:37.340  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:37.341  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:37.341  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.341  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.341  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
,09-13 13:50:37.341  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.341  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.341  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:37.341  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.341  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.341  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:50:37.341  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.342  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:50:37.343  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:37.343  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.343  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:37.344  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:50:37.344  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:50:37.344  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:50:37.344  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:50:37.344  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.344  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:37.344  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5100041 not in the list
09-13 13:50:37.345  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.345  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
09-13 13:50:37.345  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:37.345  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.345  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.345  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:37.345  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:50:37.346  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:50:37.346  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:50:37.346  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:50:37.346  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2a19e6 not in the list
,09-13 13:50:37.348  3797  3849 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 13:50:37.348  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:50:37.348  3797  3849 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-13 13:50:37.348  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 13:50:37.348  3797  3849 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 13:50:37.348  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:50:37.351  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 13:50:37.351  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 13:50:37.351  3797  3849 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 13:50:37.352  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 13:50:37.352  3797  3849 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 13:50:37.352  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 13:50:37.352  3797  3849 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 13:50:37.352  3797  3849 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 13:50:37.353  3797  3849 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 13:50:37.353  3797  3849 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 13:50:37.354  3797  3849 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 13:50:37.354  3797  3849 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 13:50:37.354  3797  3849 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 13:50:37.354  3797  3849 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 13:50:37.356  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:50:37.356  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b4ee58 added. We now have 3 listener(s)
09-13 13:50:37.356  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:50:37.358  3797  3849 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 13:50:37.359   874   885 D WifiService: setWifiEnabled: true pid=3797, uid=10000
,09-13 13:50:37.359   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:50:37.413  2671  2772 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-13 13:50:37.414  2671  2803 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-13 13:50:37.415  3797  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
,09-13 13:50:37.828  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:50:39.458   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:40.053   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 13:50:40.064  1882  1882 I Keyboard.Facilitator: onFinishInput()
,09-13 13:50:40.077   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 13:50:40.077   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 13:50:40.077   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 13:50:40.077   874   894 I Adreno  : Local Branch                     : M14
09-13 13:50:40.077   874   894 I Adreno  : Remote Branch                    : 
09-13 13:50:40.077   874   894 I Adreno  : Remote Branch                    : 
09-13 13:50:40.077   874   894 I Adreno  : Reconstruct Branch               : 
,09-13 13:50:40.100   282   361 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
,09-13 13:50:40.704  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 13:50:40.704  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 13:50:40.741   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 13:50:40.742  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bbd1cc Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ab87bb1, 16908290=android.view.AbsSavedState$1@ab87bb1}, android:focusedViewId=100}]}]
09-13 13:50:40.742  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-13 13:50:40.743  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 13:50:40.743  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 13:50:40.757   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 13:50:40.762   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-13 13:50:40.762   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-13 13:50:40.762   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 13:50:40.790   874   883 I art     : Background partial concurrent mark sweep GC freed 34923(2MB) AllocSpace objects, 11(308KB) LOS objects, 33% free, 29MB/43MB, paused 995us total 108.748ms
,09-13 13:50:40.989   282   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-13 13:50:40.991   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 13:50:40.996   874  1340 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,09-13 13:50:41.002   874   894 I DreamManagerService: Entering dreamland.
,09-13 13:50:41.003   874   894 I PowerManagerService: Dozing...
,09-13 13:50:41.004   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 13:50:41.064   378  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 13:50:41.065   378  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 13:50:41.073   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:50:41.082   874  1313 E native  : do suspend false
,09-13 13:50:41.086  1930  3875 D NfcService: Discovery configuration equal, not updating.
,09-13 13:50:41.097   874  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 13:50:41.116   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:50:41.121   874  1313 E native  : do suspend true
,09-13 13:50:41.201   378  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 13:50:41.202   378  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 13:50:41.577   874  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 13:50:42.367  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:50:42.368  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@222c896 added. We now have 4 listener(s)
09-13 13:50:42.368  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:50:42.385  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:42.385  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@222c896 removed from the list
,09-13 13:50:42.385  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:50:42.386  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:42.386  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:42.389  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:50:42.390  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf14c17 added. We now have 4 listener(s)
,09-13 13:50:42.390  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:50:42.396  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:50:42.396  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf14c17 removed from the list
09-13 13:50:42.397  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:50:42.397  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:50:42.397  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:50:42.399  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:50:42.400  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb69804 added. We now have 4 listener(s)
09-13 13:50:42.400  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:50:42.407   874   884 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,09-13 13:50:42.407   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:50:42.421  2671  2687 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 13:50:42.421  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:50:42.421  2671  2687 D BluetoothAdapterProperties: Setting state to 13
,09-13 13:50:42.422  2671  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 13:50:42.423  2671  2687 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 13:50:42.428  2671  2687 I BluetoothAdapterState: Entering PendingCommandState
09-13 13:50:42.437  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.439  2671  2671 D BluetoothMapService: onReceive
09-13 13:50:42.440  2671  2671 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 13:50:42.440  2671  2671 D BluetoothMapService: STATE_TURNING_OFF
09-13 13:50:42.440  2671  2671 D BluetoothMapService: MAP Service closeService in
09-13 13:50:42.440  2671  2671 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 13:50:42.440  2671  2671 D ObexServerSockets0: shutdown(block = true)
09-13 13:50:42.441  2671  2671 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 13:50:42.441  2671  2671 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 13:50:42.441  2671  2803 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 13:50:42.442  2671  2830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 13:50:42.442  2671  2831 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 13:50:42.443  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:42.443  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:42.444  2671  2671 I BtOppRfcommListener: stopping Accept Thread
09-13 13:50:42.444  2671  3427 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:50:42.445  2671  3427 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 13:50:42.447  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.447  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:42.448  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:50:42.450   874  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 13:50:42.450   874  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{3}, ntable=[]
,09-13 13:50:42.451   874  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 13:50:42.451   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:50:42.452  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:42.457  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:42.462  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.462   874  1313 E native  : do suspend true
,09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:42.462  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:42.464  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.464  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:42.468  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:42.469  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:42.469   874   887 I ActivityManager: Start proc 3881:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-13 13:50:42.469  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.470  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:42.472  2671  2691 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:50:42.472  2671  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 13:50:42.472   874  1879 D DhcpClient: Clearing IP address
09-13 13:50:42.473   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-13 13:50:42.474  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:42.475   374   873 D CommandListener: Setting iface cfg
,09-13 13:50:42.476  2671  2671 D HeadsetService: Received stop request...Stopping profile...
,09-13 13:50:42.476  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:42.477   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 13:50:42.477   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 13:50:42.478  1371  1384 D BluetoothHeadset: Proxy object disconnected
09-13 13:50:42.478  1371  1371 D HeadsetProfile: Bluetooth service disconnected
09-13 13:50:42.478  1513  2488 V NativeCrypto: Read error: ssl=0x9b1fc000: I/O error during system call, Connection timed out
09-13 13:50:42.479  1945  1958 D BluetoothHeadset: Proxy object disconnected
09-13 13:50:42.479   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 13:50:42.480  1513  2488 V NativeCrypto: SSL shutdown failed: ssl=0x9b1fc000: I/O error during system call, Broken pipe
09-13 13:50:42.480  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:42.481   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 13:50:42.482   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 13:50:42.482   874  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
09-13 13:50:42.482   874  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 13:50:42.482   874  1313 E native  : do suspend true
,09-13 13:50:42.483  2671  2671 D A2dpService: Received stop request...Stopping profile...
09-13 13:50:42.484  2671  2809 D A2dpStateMachine: Exit Disconnected: -1
09-13 13:50:42.486  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:42.486  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:50:42.487  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.487  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:42.488   460   460 E Parcel  : Reading a NULL string not supported here.
09-13 13:50:42.490   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 13:50:42.490  1371  1371 D BluetoothA2dp: Proxy object disconnected
,09-13 13:50:42.492   874  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 13:50:42.493  2671  2671 V BluetoothAdapterState: isTurningOff()=true
,09-13 13:50:42.493  2671  2671 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:50:42.493  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:50:42.493  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:50:42.497  2671  2671 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 13:50:42.497  2671  2671 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 13:50:42.498  2671  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 13:50:42.498  2671  2772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 13:50:42.498  2671  2772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:50:42.498  2671  2772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:50:42.498  2671  2691 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 13:50:42.499  2671  2671 D HidService: Received stop request...Stopping profile...
,09-13 13:50:42.499  2671  2671 D HidService: Stopping Bluetooth HidService
09-13 13:50:42.500  2671  2671 D HealthService: Received stop request...Stopping profile...
09-13 13:50:42.502  2671  2671 V BluetoothAdapterState: isTurningOff()=true
,09-13 13:50:42.502  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 13:50:42.502  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:42.502  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:42.503  2671  2671 D PanService: Received stop request...Stopping profile...
,09-13 13:50:42.504   874  1890 D DhcpClient: Receive thread stopped
,09-13 13:50:42.505  2671  2772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:50:42.505  2671  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 13:50:42.505  2671  2772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:50:42.505  2671  2772 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:50:42.505  2671  2772 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:50:42.505  2671  2772 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:50:42.505  2671  2772 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:50:42.506  2671  2671 D BluetoothMapService: Received stop request...Stopping profile...
09-13 13:50:42.506  2671  2671 D BluetoothMapService: stop()
09-13 13:50:42.507  2671  2671 D BluetoothMapAppObserver: deinitObservers()
09-13 13:50:42.507  2671  2671 D BluetoothMapAppObserver: removeReceiver()
09-13 13:50:42.508  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 13:50:42.508  2671  2671 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:50:42.508  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:42.508  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:42.509  2671  2671 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 13:50:42.509  2671  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 13:50:42.509  2671  2671 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 13:50:42.509  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 13:50:42.509  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 13:50:42.509  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:50:42.510  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:42.512  1371  1371 D BluetoothInputDevice: Proxy object disconnected
,09-13 13:50:42.512  1371  1371 D HidProfile: Bluetooth service disconnected
09-13 13:50:42.512  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:50:42.512  1371  1371 D PanProfile: Bluetooth service disconnected
09-13 13:50:42.512  1371  1371 D BluetoothMap: Proxy object disconnected
09-13 13:50:42.512  1371  1371 D MapProfile: Bluetooth service disconnected
09-13 13:50:42.512  2671  2671 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 13:50:42.513  2671  2691 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 13:50:42.513  2671  2671 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:50:42.514  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 13:50:42.514  2671  2671 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:50:42.514  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:42.514  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:50:42.514  2671  2671 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 13:50:42.514  2671  2671 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 13:50:42.515  2671  2671 D BluetoothMapService: MAP Service closeService in
09-13 13:50:42.515  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 13:50:42.515  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 13:50:42.515  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:42.515  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:50:42.516  2671  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 13:50:42.516  2671  2687 D BluetoothAdapterProperties: Setting state to 15
09-13 13:50:42.516  2671  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 13:50:42.516  1371  1385 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 13:50:42.517  2671  2687 I BluetoothAdapterState: Entering BleOnState
09-13 13:50:42.517  1371  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:50:42.517   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:50:42.517  1945  1958 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:50:42.518  1371  2198 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:50:42.518   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:50:42.518  1371  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:50:42.518  1371  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 13:50:42.519  1371  2198 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:50:42.519   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:50:42.519   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:50:42.520  2671  2687 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 13:50:42.520  2671  2687 D BluetoothAdapterProperties: Setting state to 16
09-13 13:50:42.520  2671  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 13:50:42.521  2671  2687 D BluetoothAdapterProperties: onBleDisable
09-13 13:50:42.521  2671  2687 I BluetoothAdapterState: Entering PendingCommandState
09-13 13:50:42.521  2671  2688 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 13:50:42.522  2671  2772 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-13 13:50:42.522  2671  2772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:50:42.522  2671  2691 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:50:42.523  2671  2671 D BluetoothMapService: cleanup()
09-13 13:50:42.523  2671  2671 D BluetoothMapService: MAP Service closeService in
09-13 13:50:42.525  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:42.525  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:42.525  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.525  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:42.527  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:42.527  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:42.528  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.528  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:42.529  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:42.529  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:42.530  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:42.532  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:42.532   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 13:50:42.534  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:42.538  3881  3881 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-13 13:50:42.549  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 13:50:42.553   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:50:42.554  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:50:42.554   874  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
09-13 13:50:42.554   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:50:42.555   374   873 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:50:42.558  3393  3393 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b4bc1ea and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-13 13:50:42.558   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 13:50:42.560  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:42.561  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:42.562  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:42.566   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7de08bf:true
09-13 13:50:42.569   874  1961 I ActivityManager: Start proc 3898:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 13:50:42.570   874  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:50:42.588   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:50:42.590  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:42.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:50:42.591  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.591  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:50:42.592   874  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 13:50:42.593  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:42.593  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:42.594  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.594  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:50:42.594  2043  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:50:42.595  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:42.595  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:50:42.595  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:42.596  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:42.603  3881  3881 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 13:50:42.605  3881  3881 D BluetoothMap: Create BluetoothMap proxy object
,09-13 13:50:42.612  3898  3898 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 13:50:42.614  3881  3881 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 13:50:42.617   374   873 E Netd    : netlink response contains error (No such file or directory)
,09-13 13:50:42.624  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:50:42.634   874  2127 I ActivityManager: Killing 3393:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 13:50:42.726  2671  2691 I bt_hci  : shut_down
,09-13 13:50:42.759  2671  2697 I bt_vendor: low_power_mode_cb
,09-13 13:50:42.770  2671  2697 D bt_hwcfg: hw_epilog_process
,09-13 13:50:42.782  2671  2697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 13:50:42.782  2671  2697 I bt_vendor: epilog_cb
09-13 13:50:42.783  2671  2697 I bt_hci  : epilog_finished_callback
,09-13 13:50:42.788  2671  2691 I bt_hci_h4: hal_close
,09-13 13:50:42.789  2671  2691 I bt_userial_vendor: device fd = 51 close
,09-13 13:50:42.844  3898  3898 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.844  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
,09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845,  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 13:50:42.845  3898  3898 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:50:42.845  3898  3898 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:50:42.870  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:50:42.878  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:50:42.880  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:50:42.888   874  2214 I ActivityManager: Killing 3569:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-13 13:50:42.892  1513  2119 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 13:50:42.970  2671  2688 D bt_stack_manager: event_shut_down_stack finished.
,09-13 13:50:42.971  2671  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 13:50:42.976  2671  2687 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 13:50:42.977  2671  2671 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:50:42.979  2671  2671 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 13:50:42.979  2671  2671 D BtGatt.GattService: stop()
09-13 13:50:42.980  2671  2671 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 13:50:42.980  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:50:42.986  1722  1722 D SystemUpdateService: onCreate
,09-13 13:50:43.000  2671  2671 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:50:43.000  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 13:50:43.000  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:50:43.000  2671  2671 V BluetoothAdapterState: isBleTurningOff()=true
09-13 13:50:43.001  2671  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 13:50:43.001  2671  2687 D BluetoothAdapterProperties: Setting state to 10
09-13 13:50:43.001  2671  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 13:50:43.001  2671  2687 I BluetoothAdapterState: Entering OffState
,09-13 13:50:43.002   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-13 13:50:43.010  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:50:43.012  1722  3934 I SystemUpdateService: active receiver: enabled
,09-13 13:50:43.019  2671  2671 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 13:50:43.019  2671  2671 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 13:50:43.019  2671  2671 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 13:50:43.019  2671  2688 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 13:50:43.021  1722  3934 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:50:43.023  2671  2688 D bt_stack_manager: event_clean_up_stack finished.
09-13 13:50:43.023  1722  3934 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 13:50:43.023  1722  3934 I SystemUpdateService: now status is 0 (complete),
09-13 13:50:43.024  1722  3934 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:50:43.024  1722  3934 I SystemUpdateService: file has been verified
09-13 13:50:43.024  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 13:50:43.024  1722  3934 I SystemUpdateService: OTA package size = 12249756
,09-13 13:50:43.028  1722  2465 I iu.UploadsManager: num queued entries: 0
,09-13 13:50:43.029  1722  2465 I iu.UploadsManager: num updated entries: 0
,09-13 13:50:43.030  1722  2465 I iu.SyncManager: NEXT; no task
,09-13 13:50:43.032  2671  2671 I art     : System.exit called, status: 0
,09-13 13:50:43.032  2671  2671 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 13:50:43.032  1722  3934 I SystemUpdateService: showing system update notification
,09-13 13:50:43.040  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:50:43.041  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:50:43.047  3898  3927 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 13:50:43.053   874  2214 I ActivityManager: Start proc 3937:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 13:50:43.056  1722  1722 D SystemUpdateService: onDestroy
,09-13 13:50:43.080   874  1962 I ActivityManager: Process com.android.bluetooth (pid 2671) has died
,09-13 13:50:43.087  3937  3937 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 13:50:43.089  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:50:43.091   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e97f9bb:true
,09-13 13:50:43.098  3937  3937 D SprintDMHelper: simOperator: 
,09-13 13:50:43.098  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:50:43.112   874  1528 I ActivityManager: Start proc 3949:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 13:50:43.225   874  2127 I ActivityManager: Start proc 3964:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 13:50:43.228   874   884 I ActivityManager: Killing 3451:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 13:50:43.312  3964  3964 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 13:50:43.386  3964  3964 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 13:50:43.386  3964  3964 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 13:50:43.386  3964  3964 I GAv4    :   adb logcat -s GAv4
,09-13 13:50:43.403  3964  3964 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:50:43.410  3964  3964 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:50:43.440  3964  3981 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:50:43.552  3964  3964 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 13:50:43.597  3964  3964 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 13:50:43.606  3964  3964 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3519-3522)
,09-13 13:50:43.606  3964  3964 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 13:50:43.625  3964  3964 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fd0799a}
,09-13 13:50:43.625  3964  3964 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 13:50:43.625  3964  3964 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 13:50:43.635  3964  3964 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 13:50:43.637  3964  3964 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 13:50:43.652  3964  3964 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 13:50:43.665  3964  3964 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 13:50:43.665  3964  3964 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 13:50:43.665  3964  3964 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 13:50:43.665  3964  3964 I Adreno  : Build Date                       : 10/20/15
09-13 13:50:43.665  3964  3964 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 13:50:43.665  3964  3964 I Adreno  : Local Branch                     : M14
09-13 13:50:43.665  3964  3964 I Adreno  : Remote Branch                    : 
09-13 13:50:43.665  3964  3964 I Adreno  : Remote Branch                    : 
09-13 13:50:43.665  3964  3964 I Adreno  : Reconstruct Branch               : 
,09-13 13:50:43.729  3964  3964 I NSApplication: Starting up...
,09-13 13:50:43.739  3964  4010 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 13:50:43.774   874  2215 I ActivityManager: Start proc 4015:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 13:50:43.775   874  2215 I ActivityManager: Killing 3039:com.google.android.keep/u0a79 (adj 15): empty #17
,09-13 13:50:43.864  4015  4015 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 13:50:44.041   874  1959 I ActivityManager: Killing 3638:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-13 13:50:44.154   874  1701 I ActivityManager: Start proc 4029:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 13:50:44.246  4029  4029 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 13:50:44.307  4029  4029 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 13:50:44.342   874  2215 I ActivityManager: Start proc 4052:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
09-13 13:50:44.343   874  2215 I ActivityManager: Killing 3497:android.process.acore/u0a5 (adj 15): empty #17
,09-13 13:50:44.432  4052  4052 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-13 13:50:44.693   874  1701 I ActivityManager: Killing 3685:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 13:50:46.043  2043  2655 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 13:50:47.450   874  1528 D WifiService: setWifiEnabled: true pid=3797, uid=10000
,09-13 13:50:47.450   874  1528 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:50:47.465   874  1313 D WifiConfigStore: Loading config and enabling all networks 
,09-13 13:50:47.472  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:47.472  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:47.472  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:47.473  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:47.475  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:47.475  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:47.476  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:50:47.476  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:50:47.478  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:47.478  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:50:47.478  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:47.478  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:47.507   874  1313 D WifiConfigStore: loaded 0 passpoint configs
,09-13 13:50:47.508   874  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 13:50:47.510   874  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 13:50:47.511   874  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 13:50:47.511   874  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 13:50:47.511   874  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 13:50:47.512   874  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 13:50:47.523   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 13:50:47.524   874  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:50:47.525   374   873 D CommandListener: Setting iface cfg
,09-13 13:50:47.526   874  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-13 13:50:47.526   874  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 13:50:47.538   874  1313 E native  : do suspend true
09-13 13:50:47.538   874  1312 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 13:50:47.544   874  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 13:50:47.559   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:50:48.155   874  1959 I ActivityManager: Killing 3702:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 13:50:48.745   874  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:50:48.824   874  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.38 rxSuccessRate=6.56 delta 1000 -> 1000
,09-13 13:50:48.826   874  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 13:50:48.826   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:50:48.850   874  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 13:50:48.895   874  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 13:50:48.899  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 13:50:49.332  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 13:50:49.383  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:50:49.384  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-13 13:50:49.388   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:50:49.411   874  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:50:49.412   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:50:49.412   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 13:50:49.459   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:50:49.480   374   873 D CommandListener: Setting iface cfg
,09-13 13:50:49.482   874  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 13:50:49.488   874  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 13:50:49.501  4052  4059 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@f4b5848)
,09-13 13:50:49.527   874  4088 D DhcpClient: Receive thread started
,09-13 13:50:49.606   874  1313 E native  : do suspend false
,09-13 13:50:49.612  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:49.615   874  1879 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 13:50:49.627  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:49.630   874  4088 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172662, domain null
09-13 13:50:49.631   874  1879 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172662 seconds
09-13 13:50:49.631  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:50:49.632   874  1879 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 13:50:49.660   874  4088 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 13:50:49.660   874  1879 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 13:50:49.662   374   873 D CommandListener: Setting iface cfg
09-13 13:50:49.667   874  1879 D DhcpClient: Scheduling renewal in 86399s
,09-13 13:50:49.671   874  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 13:50:49.674   874  1313 E native  : do suspend true
,09-13 13:50:49.687  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 13:50:49.687  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 13:50:49.687  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:50:49.688  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:50:49.691   874  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 13:50:49.692   874  1313 D WifiConfigStore: No blacklist allowed without epno enabled
09-13 13:50:49.693   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 13:50:49.694   874  1315 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 13:50:49.705   874  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 13:50:49.722  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:50:49.722  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 13:50:49.723  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 13:50:49.738   874  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 13:50:49.738   874  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 13:50:49.739   874  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 13:50:49.740   874  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 13:50:49.742   874  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 13:50:49.748   874  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 13:50:49.752   874  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 13:50:49.752   874  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-13 13:50:49.752   874  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 13:50:49.752   874  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 13:50:49.753   874  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-13 13:50:49.753   874  1315 D ConnectivityService:    accepting network in place of null
,09-13 13:50:49.754   874  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:50:49.769   874  4085 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159685, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:50:49.774   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:50:49.804   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:50:49.807   874  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 13:50:49.808   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:50:49.811   874  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 13:50:49.816  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:49.816  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:50:49.817  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:49.817  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:49.817   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 13:50:49.819  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:49.819  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:50:49.819  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:49.819  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:49.820  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:49.820  3797  3797 V io.jxcore,.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:50:49.820  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:50:49.820  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:49.820  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:50:49.833  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:50:49.842  1722  1722 D SystemUpdateService: onCreate
,09-13 13:50:49.845  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:50:49.849   874  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 13:50:49.869  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 13:50:49.870  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:50:49.876  1722  4099 I SystemUpdateService: active receiver: enabled
,09-13 13:50:49.877  1722  2465 I iu.UploadsManager: num queued entries: 0
,09-13 13:50:49.878  1722  2465 I iu.UploadsManager: num updated entries: 0
09-13 13:50:49.878  1722  2465 I iu.SyncManager: NEXT; no task
,09-13 13:50:49.886  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:50:49.889  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:50:49.895  1722  4102 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 13:50:49.895  1722  4102 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 13:50:49.898  1722  4102 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 13:50:49.904  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:50:49.909  3937  3937 D SprintDMHelper: simOperator: 
,09-13 13:50:49.909  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:50:49.916  1722  4099 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:50:49.923   874  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 11:50:49 GMT], X-Android-Received-Millis=[1473767449920], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473767449889]}
,09-13 13:50:49.925   874  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 13:50:49.925   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-13 13:50:49.926   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 13:50:49.931   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 13:50:49.944  1722  4099 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 13:50:49.944  1722  4099 I SystemUpdateService: now status is 0 (complete)
09-13 13:50:49.944  1722  4099 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:50:49.944  1722  4099 I SystemUpdateService: file has been verified
09-13 13:50:49.944  1722  4099 I SystemUpdateService: OTA package size = 12249756
,09-13 13:50:49.948  1722  4099 I SystemUpdateService: showing system update notification
,09-13 13:50:49.965  1722  1722 D SystemUpdateService: onDestroy
,09-13 13:50:50.000  1513  4109 I VacuumService: Vacuum at: now=1473767450000 tag=VacuumService
,09-13 13:50:50.021  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 13:50:50.021  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 13:50:50.021  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:50:50.022  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-13 13:50:50.046  1722  4102 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-13 13:50:50.064  2281  4105 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 13:50:50.131  1513  4110 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 13:50:50.133  1513  4110 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 13:50:50.159  1513  4110 W Uploader:  no longer exists, so no auth token.
,09-13 13:50:50.808   874  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 13:50:51.779  1513  4110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 13:50:51.779  1513  4110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-13 13:50:51.780  1513  4110 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:50:51.780  1513  4110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:50:51.812  1513  4110 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 13:50:51.812  1513  4110 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 13:50:51.812  1513  4110 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 13:50:52.455   874  2215 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,09-13 13:50:52.455   874  2215 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:50:52.476  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 13:50:52.480   874  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 13:50:52.480  1513  4110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 13:50:52.480   874  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 13:50:52.481  1513  4110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 13:50:52.481   874  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 13:50:52.481  1513  4110 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:50:52.481  1513  4110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 13:50:52.481   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:50:52.500   874  1313 E native  : do suspend true
,09-13 13:50:52.503  1513  4110 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 13:50:52.503  1513  4110 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 13:50:52.503  1513  4110 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 13:50:52.509   874  1879 D DhcpClient: Clearing IP address
,09-13 13:50:52.510   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-13 13:50:52.513   374   873 D CommandListener: Setting iface cfg
,09-13 13:50:52.514  1513  4108 V NativeCrypto: Read error: ssl=0x9b1e8200: I/O error during system call, Connection timed out
09-13 13:50:52.518  1513  4108 V NativeCrypto: SSL shutdown failed: ssl=0x9b1e8200: I/O error during system call, Broken pipe
,09-13 13:50:52.521   874  2127 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-13 13:50:52.521   874  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-13 13:50:52.528   874  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-13 13:50:52.532   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-13 13:50:52.533   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 13:50:52.541   460   460 E Parcel  : Reading a NULL string not supported here.
,09-13 13:50:52.545   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 13:50:52.547   874  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
09-13 13:50:52.547   874  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 13:50:52.548   874  1313 E native  : do suspend true
09-13 13:50:52.548   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 13:50:52.548   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 13:50:52.550   874  4088 D DhcpClient: Receive thread stopped
,09-13 13:50:52.555   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-13 13:50:52.556   874  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 13:50:52.557   874  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:50:52.562  1513  4110 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,09-13 13:50:52.576  2043  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:50:52.577   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 13:50:52.578  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:52.578  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:52.578  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:52.578  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:50:52.579  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:52.579  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:52.579  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:52.579  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:52.580  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:52.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:52.580  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:50:52.580  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:52.588   874  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 13:50:52.589   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:50:52.612   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:50:52.613   874  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 13:50:52.613   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:50:52.615   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 13:50:52.618  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:52.619  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:52.619  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:52.623  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-13 13:50:52.626  1722  1722 D SystemUpdateService: onCreate
09-13 13:50:52.628  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:50:52.637  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 13:50:52.639  1722  2465 I iu.UploadsManager: num queued entries: 0
,09-13 13:50:52.639  1722  2465 I iu.UploadsManager: num updated entries: 0
,09-13 13:50:52.643  1722  4136 I SystemUpdateService: active receiver: enabled
,09-13 13:50:52.645  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:50:52.646  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:50:52.648  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:50:52.652  3937  3937 D SprintDMHelper: simOperator: 
,09-13 13:50:52.652  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:50:52.659  1722  4136 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:50:52.662  1722  2465 I iu.SyncManager: NEXT; no task
,09-13 13:50:52.667  2281  4140 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 13:50:52.683   374   873 E Netd    : netlink response contains error (No such file or directory)
,09-13 13:50:52.684   874  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 13:50:52.688  1722  4136 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 13:50:52.688  1722  4136 I SystemUpdateService: now status is 0 (complete)
09-13 13:50:52.688  1722  4136 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:50:52.688  1722  4136 I SystemUpdateService: file has been verified
,09-13 13:50:52.688  1722  4136 I SystemUpdateService: OTA package size = 12249756
,09-13 13:50:52.700  1722  4136 I SystemUpdateService: showing system update notification
,09-13 13:50:52.712  1722  1722 D SystemUpdateService: onDestroy
,09-13 13:50:57.509   874   891 I ActivityManager: Start proc 4144:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 13:50:57.637  4144  4144 D AdapterServiceConfig: Adding HeadsetService
09-13 13:50:57.638  4144  4144 D AdapterServiceConfig: Adding A2dpService
,09-13 13:50:57.639  4144  4144 D AdapterServiceConfig: Adding HidService
09-13 13:50:57.639  4144  4144 D AdapterServiceConfig: Adding HealthService
09-13 13:50:57.641  4144  4144 D AdapterServiceConfig: Adding PanService
09-13 13:50:57.641  4144  4144 D AdapterServiceConfig: Adding GattService
09-13 13:50:57.642  4144  4144 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 13:50:57.670   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a0b07:true
,09-13 13:50:57.671  4144  4144 D BluetoothAdapterState: make() - Creating AdapterState,
,09-13 13:50:57.676  4144  4144 I bt_bluedroid: init
,09-13 13:50:57.677  4144  4156 I BluetoothAdapterState: Entering OffState
,09-13 13:50:57.683  4144  4157 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 13:50:57.683  4144  4157 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 13:50:57.683  4144  4157 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 13:50:57.684  4144  4157 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 13:50:57.686  4144  4144 I bt_bluedroid: get_profile_interface socket
,09-13 13:50:57.688  4144  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:50:57.690  4144  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:50:57.690  4144  4144 I bt_bluedroid: get_profile_interface sdp
,09-13 13:50:57.696  4144  4155 I bt_bluedroid: config_hci_snoop_log
,09-13 13:50:57.699   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 13:50:57.708  4144  4156 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 13:50:57.709  4144  4156 D BluetoothAdapterProperties: Setting state to 14
09-13 13:50:57.709  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 13:50:57.712  4144  4156 D BluetoothBondStateMachine: make
,09-13 13:50:57.716  4144  4161 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 13:50:57.719  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:50:57.723  4144  4144 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 13:50:57.731  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:57.733  4144  4144 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:50:57.734  4144  4144 D BtGatt.GattService: Received start request. Starting profile...
,09-13 13:50:57.735  4144  4144 D BtGatt.GattService: start()
09-13 13:50:57.735  4144  4144 I bt_bluedroid: get_profile_interface gatt
,09-13 13:50:57.737  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:57.737  4144  4144 D BtGatt.AdvertiseManager: advertise manager created
,09-13 13:50:57.748  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:50:57.749  4144  4144 V BluetoothAdapterState: isTurningOn()=false
09-13 13:50:57.749  4144  4144 V BluetoothAdapterState: isBleTurningOn()=true
09-13 13:50:57.749  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:50:57.749  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 13:50:57.750  4144  4156 I bt_bluedroid: enable
09-13 13:50:57.750  4144  4157 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 13:50:57.751  4144  4157 I bt_hci  : start_up
,09-13 13:50:57.757   874  1315 D ConnectivityService: handlePromptUnvalidated 101
,09-13 13:50:57.770  4144  4157 I bt_vendor: alloc value 0xb3a3e189
,09-13 13:50:57.770  4144  4157 I bt_vendor: init
09-13 13:50:57.770  4144  4157 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 13:50:57.770  4144  4157 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 13:50:57.878  4144  4157 D bt_hci  : start_up starting async portion
,09-13 13:50:57.879  4144  4164 I bt_hci  : event_finish_startup
,09-13 13:50:57.879  4144  4164 I bt_hci_h4: hal_open
09-13 13:50:57.880  4144  4164 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 13:50:57.891  4144  4164 I bt_userial_vendor: device fd = 51 open
,09-13 13:50:57.920  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:50:57.952  4144  4164 D bt_hwcfg: Chipset BCM4354A2
09-13 13:50:57.952  4144  4164 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 13:50:57.953  4144  4164 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 13:50:58.614  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 13:50:58.615  4144  4164 D bt_hwcfg: Settlement delay -- 100 ms
09-13 13:50:58.616  4144  4164 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 13:50:58.732  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:50:58.734  4144  4164 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 13:50:58.762  4144  4164 I bt_hwcfg: vendor lib fwcfg completed
,09-13 13:50:58.762  4144  4164 I bt_vendor: firmware callback
09-13 13:50:58.763  4144  4164 I bt_hci  : firmware_config_callback
,09-13 13:50:58.774  4144  4166 I bt_btu  : btu_task pending for preload complete event
,09-13 13:50:58.774  4144  4166 I bt_btu_task: Bluetooth chip preload is complete
,09-13 13:50:58.774  4144  4166 I bt_btu  : btu_task received preload complete event
,09-13 13:50:58.784  4144  4166 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 13:50:58.784  4144  4166 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 13:50:58.784  4144  4166 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 13:50:58.784  4144  4166 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 13:50:58.785  4144  4166 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 13:50:58.785  4144  4166 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 13:50:58.785  4144  4166 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 13:50:58.785  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 13:50:58.785  4144  4166 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 13:50:58.786  4144  4166 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 13:50:58.786  4144  4166 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 13:50:58.786  4144  4166 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 13:50:58.786  4144  4166 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 13:50:58.786  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 13:50:58.787  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 13:50:58.923  4144  4166 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bbd9d
,09-13 13:50:58.923  4144  4166 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bbd9d 
,09-13 13:50:58.948  4144  4160 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 13:50:58.949  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 13:50:58.950  4144  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:50:58.953  4144  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:50:58.955  4144  4160 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:50:58.956  4144  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 13:50:58.956  4144  4160 D bt_hci  : do_postload posting postload work item
,09-13 13:50:58.957  4144  4164 I bt_hci  : event_postload
09-13 13:50:58.957  4144  4164 I bt_vendor: sco_config_cb
09-13 13:50:58.957  4144  4164 I bt_hci  : sco_config_callback postload finished.
,09-13 13:50:58.959  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:58.961  4144  4160 D bt_bte_conf: Device ID record 1 : primary
09-13 13:50:58.961  4144  4160 D bt_bte_conf:   vendorId            = 000f
09-13 13:50:58.961  4144  4160 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 13:50:58.961  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:58.961  4144  4160 D bt_bte_conf:   product             = 1200
09-13 13:50:58.962  4144  4160 D bt_bte_conf:   version             = 1436
09-13 13:50:58.962  4144  4160 D bt_bte_conf:   clientExecutableURL = 
,09-13 13:50:58.962  4144  4160 D bt_bte_conf:   serviceDescription  = 
,09-13 13:50:58.962  4144  4160 D bt_bte_conf:   documentationURL    = 
,09-13 13:50:58.963  4144  4160 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 13:50:58.964  4144  4157 D bt_stack_manager: event_start_up_stack finished
09-13 13:50:58.964  4144  4164 I bt_vendor: low_power_mode_cb
,09-13 13:50:58.965  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:58.965  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 13:50:58.966  4144  4156 D BluetoothAdapterProperties: Setting state to 15
,09-13 13:50:58.966  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 13:50:58.968  4144  4156 I BluetoothAdapterState: Entering BleOnState
,09-13 13:50:58.972  4144  4156 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 13:50:58.973  4144  4156 D BluetoothAdapterProperties: Setting state to 11
,09-13 13:50:58.973  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 13:50:58.986  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:58.989  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:58.991  4144  4144 D HeadsetService: Received start request. Starting profile...
09-13 13:50:58.994  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:58.997  4144  4144 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:50:58.997  4144  4144 D HeadsetStateMachine: make
09-13 13:50:58.997  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:58.999  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:50:59.006  4144  4144 D HeadsetStateMachine: max_hf_connections = 1
,09-13 13:50:59.006  4144  4144 I bt_bluedroid: get_profile_interface handsfree
,09-13 13:50:59.007  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-13 13:50:59.007  4144  4160 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-13 13:50:59.011  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:59.012  4144  4144 D A2dpService: Received start request. Starting profile...
,09-13 13:50:59.013  4144  4144 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 13:50:59.013  4144  4144 I bt_bluedroid: get_profile_interface avrcp
,09-13 13:50:59.019  4144  4144 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 13:50:59.020  4144  4144 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:50:59.020  4144  4144 D A2dpStateMachine: make
,09-13 13:50:59.021  4144  4144 I bt_bluedroid: get_profile_interface a2dp
,09-13 13:50:59.022  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 13:50:59.024  4144  4176 D A2dpStateMachine: Enter Disconnected: -2
,09-13 13:50:59.024  4144  4144 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 13:50:59.025  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:59.027  4144  4144 D HidService: Received start request. Starting profile...
,09-13 13:50:59.027  3881  3881 D BluetoothInputDevice: Proxy object connected
09-13 13:50:59.027  4144  4144 I bt_bluedroid: get_profile_interface hidhost
,09-13 13:50:59.027  4144  4160 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399d3e5
09-13 13:50:59.027  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 13:50:59.027  4144  4144 D HidService: setHidService(): set to: null
,09-13 13:50:59.028  3881  3881 D HidProfile: Bluetooth service connected
09-13 13:50:59.029  4144  4144 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:50:59.030  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:59.031  4144  4144 D HealthService: Received start request. Starting profile...
,09-13 13:50:59.031  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:50:59.033  4144  4144 I bt_bluedroid: get_profile_interface health
,09-13 13:50:59.034  4144  4144 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 13:50:59.036  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:59.037  4144  4144 D PanService: Received start request. Starting profile...
,09-13 13:50:59.038  3881  3881 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 13:50:59.038  4144  4144 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 13:50:59.038  4144  4144 I bt_bluedroid: get_profile_interface pan
,09-13 13:50:59.038  3881  3881 D PanProfile: Bluetooth service connected
,09-13 13:50:59.039  4144  4160 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 13:50:59.043  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:50:59.045  3881  3881 D BluetoothMap: Proxy object connected
,09-13 13:50:59.045  4144  4144 D BluetoothMapService: Received start request. Starting profile...
,09-13 13:50:59.045  4144  4144 D BluetoothMapService: start()
09-13 13:50:59.046  3881  3881 D MapProfile: Bluetooth service connected
09-13 13:50:59.046  3881  3881 D BluetoothMap: getConnectedDevices()
09-13 13:50:59.047  3881  3881 D BluetoothMap: Bluetooth is Not enabled
,09-13 13:50:59.048  4144  4144 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-13 13:50:59.050  4144  4144 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 13:50:59.050  4144  4144 D BluetoothMapAppObserver: createReceiver()
,09-13 13:50:59.051  4144  4144 D BluetoothMapAppObserver: initObservers()
,09-13 13:50:59.051  4144  4144 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 13:50:59.064  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:50:59.064  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 13:50:59.064  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:59.064  4144  4174 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 13:50:59.064  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:59.067  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-13 13:50:59.067  4144  4144 V BluetoothAdapterState: isTurningOn()=true,
09-13 13:50:59.067  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:59.067  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:50:59.067  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:50:59.067  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 13:50:59.068  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:59.068  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:59.068  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isTurningOn()=true
,09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:59.069  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:50:59.070  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-13 13:50:59.070  4144  4144 V BluetoothAdapterState: isTurningOn()=true
,09-13 13:50:59.070  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:50:59.070  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:50:59.070  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 13:50:59.071  4144  4156 D BluetoothAdapterProperties: ScanMode =  20
09-13 13:50:59.071  4144  4156 D BluetoothAdapterProperties: State =  11
09-13 13:50:59.073  4144  4160 D BluetoothAdapterProperties: Scan Mode:21
,09-13 13:50:59.073  4144  4156 D BluetoothAdapterProperties: Setting state to 12
09-13 13:50:59.073  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 13:50:59.073  4144  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:50:59.074  4144  4156 I BluetoothAdapterState: Entering OnState
09-13 13:50:59.075  1371  1384 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:59.078  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:59.080  1371  2198 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 13:50:59.080  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:59.084  1371  1371 D BluetoothMap: Proxy object connected
,09-13 13:50:59.084  1371  1371 D MapProfile: Bluetooth service connected
09-13 13:50:59.084  1371  1371 D BluetoothMap: getConnectedDevices()
09-13 13:50:59.084  4144  4144 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 13:50:59.084   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:50:59.085  1945  2092 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:59.085  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:50:59.085  3881  3892 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 13:50:59.085  4144  4144 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 13:50:59.087  1371  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:50:59.087  4144  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:50:59.088  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:50:59.089  1371  1371 D BluetoothInputDevice: Proxy object connected
09-13 13:50:59.090  1371  1371 D HidProfile: Bluetooth service connected
,09-13 13:50:59.090  3881  3893 D BluetoothMap: onBluetoothStateChange: up=true
09-13 13:50:59.091  3881  3892 D BluetoothPan: onBluetoothStateChange on: true
09-13 13:50:59.091  4144  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:50:59.091   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:50:59.092  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:50:59.093  1371  2198 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:50:59.094  4144  4144 D ObexServerSockets: Succeed to create listening sockets 
09-13 13:50:59.094  4144  4144 D ObexServerSockets0: startAccept()
09-13 13:50:59.094  4144  4144 D ObexServerSockets0: prepareForNewConnect()
09-13 13:50:59.094  3881  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 13:50:59.094  1371  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:50:59.096  4144  4144 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-13 13:50:59.096  4144  4144 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 13:50:59.097  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:50:59.098   874   874 D BluetoothA2dp: Proxy object connected
,09-13 13:50:59.099  1371  2198 D BluetoothPan: onBluetoothStateChange on: true
09-13 13:50:59.098  1371  1371 D BluetoothA2dp: Proxy object connected
09-13 13:50:59.099  4144  4182 D ObexServerSockets0: Accepting socket connection...
,09-13 13:50:59.101   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:50:59.102  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 13:50:59.102   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:50:59.102  1371  1371 D PanProfile: Bluetooth service connected
09-13 13:50:59.102  4144  4183 D ObexServerSockets0: Accepting socket connection...
09-13 13:50:59.105   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 13:50:59.106  4144  4144 D BluetoothMapService: onReceive
,09-13 13:50:59.107  4144  4144 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:50:59.107  4144  4144 D BluetoothMapService: STATE_ON
09-13 13:50:59.109  3881  3881 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 13:50:59.110  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:50:59.111  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 13:50:59.112  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:50:59.113  3881  3881 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 13:50:59.123  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:50:59.126  3881  3881 D BluetoothA2dp: Proxy object connected
,09-13 13:50:59.128  4144  4144 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 13:50:59.128  4144  4144 D ObexServerSockets0: prepareForNewConnect()
09-13 13:50:59.130  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:50:59.136  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:50:59.142  3881  3881 D BluetoothPbap: Proxy object connected
,09-13 13:50:59.142  1371  1371 D BluetoothPbap: Proxy object connected
09-13 13:50:59.142  1371  1371 D PbapServerProfile: Bluetooth service connected
09-13 13:50:59.142  3881  3881 D PbapServerProfile: Bluetooth service connected
,09-13 13:50:59.155  4144  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:50:59.180  4144  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:50:59.184  4144  4192 I BtOppRfcommListener: Accept thread started.
,09-13 13:50:59.186   874   874 D BluetoothHeadset: Proxy object connected
09-13 13:50:59.186   874   874 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.187  1371  1385 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.187  1371  1371 D HeadsetProfile: Bluetooth service connected
,09-13 13:50:59.187  1945  1956 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.188   874   874 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.194  1371  1384 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.194  1371  1371 D HeadsetProfile: Bluetooth service connected
,09-13 13:50:59.202   874   891 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.202   874   891 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.216  3881  3892 D BluetoothHeadset: Proxy object connected
,09-13 13:50:59.217  3881  3881 D HeadsetProfile: Bluetooth service connected
,09-13 13:51:02.471  4144  4156 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 13:51:02.472  4144  4156 D BluetoothAdapterProperties: Setting state to 13
09-13 13:51:02.472  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 13:51:02.474  4144  4156 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 13:51:02.476  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:51:02.479  4144  4160 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:51:02.480  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 13:51:02.488  4144  4144 D BluetoothMapService: onReceive
,09-13 13:51:02.488  4144  4144 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 13:51:02.488  4144  4144 D BluetoothMapService: STATE_TURNING_OFF
09-13 13:51:02.488  4144  4144 D BluetoothMapService: MAP Service closeService in
,09-13 13:51:02.488  4144  4144 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 13:51:02.488  4144  4144 D ObexServerSockets0: shutdown(block = true)
09-13 13:51:02.489  4144  4144 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 13:51:02.490  4144  4144 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 13:51:02.490  4144  4182 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 13:51:02.490  4144  4183 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 13:51:02.490  4144  4168 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-13 13:51:02.494  4144  4144 I BtOppRfcommListener: stopping Accept Thread
,09-13 13:51:02.494  4144  4192 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:51:02.496  4144  4192 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 13:51:02.498  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:02.498  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:51:02.500  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:51:02.500  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:51:02.504  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:02.504  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:51:02.505  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:51:02.505  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:51:02.506  4144  4144 D HeadsetService: Received stop request...Stopping profile...
09-13 13:51:02.509  3881  3893 D BluetoothHeadset: Proxy object disconnected
09-13 13:51:02.509   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 13:51:02.509   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 13:51:02.510  1371  2198 D BluetoothHeadset: Proxy object disconnected
09-13 13:51:02.510  1945  1958 D BluetoothHeadset: Proxy object disconnected
,09-13 13:51:02.510   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 13:51:02.511  4144  4144 D A2dpService: Received stop request...Stopping profile...
09-13 13:51:02.511  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:02.511  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:51:02.511  4144  4176 D A2dpStateMachine: Exit Disconnected: -1
,09-13 13:51:02.512  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:51:02.512  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:51:02.512   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 13:51:02.513  4144  4144 D HidService: Received stop request...Stopping profile...
09-13 13:51:02.513  4144  4144 D HidService: Stopping Bluetooth HidService
09-13 13:51:02.514  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:02.515  4144  4144 D HealthService: Received stop request...Stopping profile...
09-13 13:51:02.516  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:02.516  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 13:51:02.518  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:02.520  4144  4144 V BluetoothAdapterState: isTurningOff()=true
09-13 13:51:02.520  4144  4144 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:51:02.520  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.520  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:02.521  1371  1371 D HeadsetProfile: Bluetooth service disconnected
09-13 13:51:02.521  1371  1371 D BluetoothA2dp: Proxy object disconnected
09-13 13:51:02.522  1371  1371 D BluetoothInputDevice: Proxy object disconnected
09-13 13:51:02.522  1371  1371 D HidProfile: Bluetooth service disconnected
,09-13 13:51:02.522  3881  3881 D HeadsetProfile: Bluetooth service disconnected
,09-13 13:51:02.522  3881  3881 D BluetoothA2dp: Proxy object disconnected
09-13 13:51:02.523  3881  3881 D BluetoothInputDevice: Proxy object disconnected
,09-13 13:51:02.523  3881  3881 D HidProfile: Bluetooth service disconnected
09-13 13:51:02.524  4144  4144 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 13:51:02.525  4144  4144 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 13:51:02.525  4144  4166 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:51:02.525  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 13:51:02.525  4144  4166 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 13:51:02.525  4144  4166 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:51:02.525  4144  4160 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 13:51:02.527  4144  4144 D PanService: Received stop request...Stopping profile...
09-13 13:51:02.527  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:51:02.527  1371  1371 D PanProfile: Bluetooth service disconnected
,09-13 13:51:02.528  4144  4144 V BluetoothAdapterState: isTurningOff()=true
09-13 13:51:02.528  4144  4144 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:51:02.528  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.528  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:02.529  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 13:51:02.529  4144  4166 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:51:02.529  4144  4166 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:51:02.529  4144  4166 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:51:02.529  4144  4166 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:51:02.530  4144  4166 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:51:02.530  4144  4166 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:51:02.530  4144  4144 D BluetoothMapService: Received stop request...Stopping profile...
09-13 13:51:02.530  4144  4144 D BluetoothMapService: stop()
09-13 13:51:02.531  4144  4144 D BluetoothMapAppObserver: deinitObservers()
09-13 13:51:02.531  4144  4144 D BluetoothMapAppObserver: removeReceiver()
,09-13 13:51:02.532  1371  1371 D BluetoothMap: Proxy object disconnected
09-13 13:51:02.532  1371  1371 D MapProfile: Bluetooth service disconnected
09-13 13:51:02.532  4144  4144 V BluetoothAdapterState: isTurningOff()=true
09-13 13:51:02.532  4144  4144 V BluetoothAdapterState: isTurningOn()=false
09-13 13:51:02.532  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.532  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:02.533  3881  3881 D DockEventReceiver: finishStartingService: stopping service
09-13 13:51:02.533  4144  4144 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 13:51:02.533  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 13:51:02.533  4144  4144 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 13:51:02.533  4144  4144 V BluetoothAdapterState: isTurningOff()=true
09-13 13:51:02.533  4144  4144 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:51:02.533  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.534  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:02.534  4144  4144 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 13:51:02.534  4144  4160 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 13:51:02.534  3881  3881 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:51:02.534  3881  3881 D PanProfile: Bluetooth service disconnected
,09-13 13:51:02.534  4144  4144 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:51:02.534  3881  3881 D BluetoothMap: Proxy object disconnected
09-13 13:51:02.534  3881  3881 D MapProfile: Bluetooth service disconnected
09-13 13:51:02.537  4144  4144 V BluetoothAdapterState: isTurningOff()=true
09-13 13:51:02.537  4144  4144 V BluetoothAdapterState: isTurningOn()=false
09-13 13:51:02.537  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.537  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:02.538  4144  4144 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 13:51:02.538  4144  4144 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 13:51:02.539  4144  4144 D BluetoothMapService: MAP Service closeService in
09-13 13:51:02.539  4144  4144 V BluetoothAdapterState: isTurningOff()=true
,09-13 13:51:02.539  4144  4144 V BluetoothAdapterState: isTurningOn()=false
09-13 13:51:02.539  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.539  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:02.539  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 13:51:02.540  4144  4156 D BluetoothAdapterProperties: Setting state to 15
09-13 13:51:02.540  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 13:51:02.540  4144  4144 D BluetoothMapService: cleanup()
09-13 13:51:02.540  4144  4144 D BluetoothMapService: MAP Service closeService in
09-13 13:51:02.541  1371  2198 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 13:51:02.541  4144  4156 I BluetoothAdapterState: Entering BleOnState
09-13 13:51:02.541  3881  3893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:51:02.542  1371  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:51:02.542   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:51:02.542  1945  2199 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 13:51:02.542  3881  3893 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 13:51:02.542  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:51:02.543  1371  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:51:02.547  3881  3892 D BluetoothMap: onBluetoothStateChange: up=false
,09-13 13:51:02.548  3881  3893 D BluetoothPan: onBluetoothStateChange on: false
,09-13 13:51:02.548   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:51:02.548  1371  2198 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:51:02.548  3881  3892 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:51:02.549  1371  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:51:02.550  1371  1385 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:51:02.550   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:51:02.550   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:51:02.550  3881  3893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:51:02.551  4144  4156 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 13:51:02.551  4144  4156 D BluetoothAdapterProperties: Setting state to 16
09-13 13:51:02.551  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 13:51:02.552  4144  4156 D BluetoothAdapterProperties: onBleDisable
09-13 13:51:02.552  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:51:02.552  4144  4157 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 13:51:02.553  4144  4160 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:51:02.553  4144  4166 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 13:51:02.553  4144  4166 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 13:51:02.556  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:02.557  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:02.558  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:02.559  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:02.560  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:02.561  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:02.563  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:51:02.568  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:51:02.569  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:51:02.755  4144  4160 I bt_hci  : shut_down
,09-13 13:51:02.765  4144  4164 I bt_vendor: low_power_mode_cb
09-13 13:51:02.765  4144  4164 D bt_hwcfg: hw_epilog_process
,09-13 13:51:02.781  4144  4164 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-13 13:51:02.781  4144  4164 I bt_vendor: epilog_cb
,09-13 13:51:02.781  4144  4164 I bt_hci  : epilog_finished_callback
,09-13 13:51:02.787  4144  4160 I bt_hci_h4: hal_close
,09-13 13:51:02.789  4144  4160 I bt_userial_vendor: device fd = 51 close
,09-13 13:51:02.923  4144  4157 D bt_stack_manager: event_shut_down_stack finished.
,09-13 13:51:02.924  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 13:51:02.930  4144  4144 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:51:02.930  4144  4156 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 13:51:02.932  4144  4144 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 13:51:02.932  4144  4144 D BtGatt.GattService: stop()
09-13 13:51:02.933  4144  4144 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 13:51:02.940  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:51:02.940  4144  4144 V BluetoothAdapterState: isTurningOn()=false
09-13 13:51:02.940  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:02.941  4144  4144 V BluetoothAdapterState: isBleTurningOff()=true
09-13 13:51:02.941  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 13:51:02.942  4144  4156 D BluetoothAdapterProperties: Setting state to 10
09-13 13:51:02.942  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 13:51:02.944  4144  4156 I BluetoothAdapterState: Entering OffState
,09-13 13:51:02.946   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 13:51:02.969  4144  4144 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 13:51:02.970  4144  4144 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 13:51:02.970  4144  4157 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 13:51:02.982  4144  4157 D bt_stack_manager: event_clean_up_stack finished.
,09-13 13:51:02.984  4144  4144 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 13:51:02.988  4144  4144 I art     : System.exit called, status: 0
,09-13 13:51:02.988  4144  4144 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 13:51:03.048   874   884 I ActivityManager: Process com.android.bluetooth (pid 4144) has died
,09-13 13:51:07.468  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:51:07.469  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:07.474  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:51:07.474  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb69804 removed from the list
09-13 13:51:07.474  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:51:07.475  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:07.475  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:07.478  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:51:07.478  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bad822 added. We now have 4 listener(s)
,09-13 13:51:07.479  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:51:07.481  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:07.481  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bad822 removed from the list
,09-13 13:51:07.481  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:51:07.482  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:07.483  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:07.485  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:51:07.485  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b492b3 added. We now have 4 listener(s)
09-13 13:51:07.486  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:51:12.498  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:12.550   874   891 I ActivityManager: Start proc 4202:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 13:51:12.678  4202  4202 D AdapterServiceConfig: Adding HeadsetService
09-13 13:51:12.678  4202  4202 D AdapterServiceConfig: Adding A2dpService
09-13 13:51:12.678  4202  4202 D AdapterServiceConfig: Adding HidService
09-13 13:51:12.678  4202  4202 D AdapterServiceConfig: Adding HealthService
09-13 13:51:12.679  4202  4202 D AdapterServiceConfig: Adding PanService
09-13 13:51:12.679  4202  4202 D AdapterServiceConfig: Adding GattService
09-13 13:51:12.679  4202  4202 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 13:51:12.693  4202  4202 D BluetoothAdapterState: make() - Creating AdapterState
09-13 13:51:12.693   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f86c48:true
,09-13 13:51:12.698  4202  4202 I bt_bluedroid: init
,09-13 13:51:12.699  4202  4214 I BluetoothAdapterState: Entering OffState
,09-13 13:51:12.705  4202  4215 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 13:51:12.706  4202  4215 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 13:51:12.706  4202  4215 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 13:51:12.707  4202  4215 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 13:51:12.709  4202  4202 I bt_bluedroid: get_profile_interface socket
,09-13 13:51:12.710  4202  4202 I bt_bluedroid: get_profile_interface sdp
,09-13 13:51:12.714  4202  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:51:12.716  4202  4213 I bt_bluedroid: config_hci_snoop_log
09-13 13:51:12.716  4202  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:51:12.719   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 13:51:12.732  4202  4214 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 13:51:12.733  4202  4214 D BluetoothAdapterProperties: Setting state to 14
09-13 13:51:12.733  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 13:51:12.738  4202  4214 D BluetoothBondStateMachine: make
,09-13 13:51:12.742  4202  4219 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 13:51:12.751  4202  4214 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:51:12.754  4202  4202 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 13:51:12.764  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:12.766  4202  4202 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:51:12.768  4202  4202 D BtGatt.GattService: Received start request. Starting profile...
09-13 13:51:12.769  4202  4202 D BtGatt.GattService: start()
09-13 13:51:12.769  4202  4202 I bt_bluedroid: get_profile_interface gatt
,09-13 13:51:12.772  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:12.772  4202  4202 D BtGatt.AdvertiseManager: advertise manager created
,09-13 13:51:12.788  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-13 13:51:12.788  4202  4202 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:51:12.788  4202  4202 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 13:51:12.788  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:51:12.789  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 13:51:12.789  4202  4214 I bt_bluedroid: enable
09-13 13:51:12.790  4202  4215 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 13:51:12.791  4202  4215 I bt_hci  : start_up
,09-13 13:51:12.801  4202  4215 I bt_vendor: alloc value 0xb3a3e189
09-13 13:51:12.801  4202  4215 I bt_vendor: init
,09-13 13:51:12.801  4202  4215 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 13:51:12.801  4202  4215 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 13:51:12.909  4202  4215 D bt_hci  : start_up starting async portion
,09-13 13:51:12.910  4202  4222 I bt_hci  : event_finish_startup
09-13 13:51:12.910  4202  4222 I bt_hci_h4: hal_open
09-13 13:51:12.910  4202  4222 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 13:51:12.922  4202  4222 I bt_userial_vendor: device fd = 51 open
,09-13 13:51:12.952  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:51:12.983  4202  4222 D bt_hwcfg: Chipset BCM4354A2
,09-13 13:51:12.984  4202  4222 D bt_hwcfg: Target name = [BCM4354A2]
09-13 13:51:12.984  4202  4222 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 13:51:13.663  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:13.671  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:13.676  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:13.705  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 13:51:13.706  4202  4222 D bt_hwcfg: Settlement delay -- 100 ms
09-13 13:51:13.706  4202  4222 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 13:51:13.715  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:51:13.716  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 13:51:13.716  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:13.716  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:13.747  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:51:13.748  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 13:51:13.748  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 13:51:13.821  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:51:13.821  4202  4222 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 13:51:13.855  4202  4222 I bt_hwcfg: vendor lib fwcfg completed
,09-13 13:51:13.855  4202  4222 I bt_vendor: firmware callback
09-13 13:51:13.855  4202  4222 I bt_hci  : firmware_config_callback
,09-13 13:51:13.859  4202  4226 I bt_btu  : btu_task pending for preload complete event
,09-13 13:51:13.860  4202  4226 I bt_btu_task: Bluetooth chip preload is complete
09-13 13:51:13.860  4202  4226 I bt_btu  : btu_task received preload complete event
,09-13 13:51:13.868  4202  4226 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 13:51:13.868  4202  4226 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 13:51:13.869  4202  4226 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 13:51:13.869  4202  4226 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 13:51:13.869  4202  4226 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 13:51:13.869  4202  4226 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 13:51:13.870  4202  4226 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 13:51:13.870  4202  4226 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 13:51:13.870  4202  4226 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 13:51:13.870  4202  4226 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 13:51:13.870  4202  4226 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 13:51:13.871  4202  4226 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 13:51:13.871  4202  4226 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 13:51:13.871  4202  4226 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-13 13:51:13.871  4202  4226 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 13:51:14.004  4202  4226 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bbd9d
,09-13 13:51:14.004  4202  4226 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bbd9d 
,09-13 13:51:14.017  4202  4218 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 13:51:14.019  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 13:51:14.020  4202  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:51:14.023  4202  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:51:14.026  4202  4218 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:51:14.027  4202  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:51:14.027  4202  4218 D bt_hci  : do_postload posting postload work item
09-13 13:51:14.028  4202  4222 I bt_hci  : event_postload
,09-13 13:51:14.028  4202  4222 I bt_vendor: sco_config_cb
09-13 13:51:14.029  4202  4222 I bt_hci  : sco_config_callback postload finished.
09-13 13:51:14.030  4202  4218 D bt_bte_conf: Device ID record 1 : primary
09-13 13:51:14.030  4202  4218 D bt_bte_conf:   vendorId            = 000f
09-13 13:51:14.031  4202  4218 D bt_bte_conf:   vendorIdSource      = 0001
09-13 13:51:14.031  4202  4218 D bt_bte_conf:   product             = 1200
09-13 13:51:14.031  4202  4218 D bt_bte_conf:   version             = 1436
,09-13 13:51:14.031  4202  4218 D bt_bte_conf:   clientExecutableURL = 
09-13 13:51:14.031  4202  4218 D bt_bte_conf:   serviceDescription  = 
09-13 13:51:14.031  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:14.032  4202  4218 D bt_bte_conf:   documentationURL    = 
09-13 13:51:14.032  4202  4218 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 13:51:14.033  4202  4215 D bt_stack_manager: event_start_up_stack finished
,09-13 13:51:14.035  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:14.035  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 13:51:14.036  4202  4214 D BluetoothAdapterProperties: Setting state to 15
,09-13 13:51:14.036  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 13:51:14.038  4202  4214 I BluetoothAdapterState: Entering BleOnState
09-13 13:51:14.045  4202  4214 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 13:51:14.045  4202  4214 D BluetoothAdapterProperties: Setting state to 11
09-13 13:51:14.045  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 13:51:14.048  4202  4222 I bt_vendor: low_power_mode_cb
,09-13 13:51:14.055  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:14.056  4202  4202 D HeadsetService: Received start request. Starting profile...
,09-13 13:51:14.059  4202  4202 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:51:14.059  4202  4202 D HeadsetStateMachine: make
09-13 13:51:14.070  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:14.075  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:14.076  4202  4202 D HeadsetStateMachine: max_hf_connections = 1
09-13 13:51:14.076  4202  4202 I bt_bluedroid: get_profile_interface handsfree
09-13 13:51:14.077  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 13:51:14.077  4202  4218 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 13:51:14.083  4202  4214 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:51:14.086  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:14.087  4202  4202 D A2dpService: Received start request. Starting profile...
09-13 13:51:14.088  4202  4202 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 13:51:14.088  4202  4202 I bt_bluedroid: get_profile_interface avrcp
,09-13 13:51:14.094  4202  4202 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 13:51:14.094  4202  4202 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:51:14.094  4202  4202 D A2dpStateMachine: make
,09-13 13:51:14.097  4202  4202 I bt_bluedroid: get_profile_interface a2dp
,09-13 13:51:14.098  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-13 13:51:14.100  4202  4235 D A2dpStateMachine: Enter Disconnected: -2
,09-13 13:51:14.102  4202  4202 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 13:51:14.103  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:14.107  4202  4202 D HidService: Received start request. Starting profile...
09-13 13:51:14.107  4202  4202 I bt_bluedroid: get_profile_interface hidhost
09-13 13:51:14.107  4202  4202 D HidService: setHidService(): set to: null
09-13 13:51:14.107  4202  4218 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399d3e5
09-13 13:51:14.108  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 13:51:14.108  4202  4202 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:51:14.109  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
09-13 13:51:14.109  4202  4202 D HealthService: Received start request. Starting profile...
,09-13 13:51:14.111  4202  4202 I bt_bluedroid: get_profile_interface health
09-13 13:51:14.112  4202  4202 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 13:51:14.112  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:14.113  4202  4202 D PanService: Received start request. Starting profile...
,09-13 13:51:14.113  4202  4202 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 13:51:14.113  4202  4202 I bt_bluedroid: get_profile_interface pan
09-13 13:51:14.114  4202  4218 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 13:51:14.115  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
09-13 13:51:14.116  4202  4202 D BluetoothMapService: Received start request. Starting profile...
09-13 13:51:14.116  4202  4202 D BluetoothMapService: start()
,09-13 13:51:14.121  4202  4202 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 13:51:14.124  4202  4202 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 13:51:14.124  4202  4202 D BluetoothMapAppObserver: createReceiver()
,09-13 13:51:14.127  4202  4202 D BluetoothMapAppObserver: initObservers()
,09-13 13:51:14.128  4202  4202 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 13:51:14.146  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:51:14.146  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-13 13:51:14.147  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:14.147  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:14.148  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:51:14.152  4202  4232 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-13 13:51:14.153  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isTurningOn()=true
,09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:51:14.154  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:51:14.154  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 13:51:14.155  4202  4214 D BluetoothAdapterProperties: ScanMode =  20
09-13 13:51:14.155  4202  4214 D BluetoothAdapterProperties: State =  11
,09-13 13:51:14.156  4202  4214 D BluetoothAdapterProperties: Setting state to 12
09-13 13:51:14.156  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 13:51:14.157  4202  4218 D BluetoothAdapterProperties: Scan Mode:21
09-13 13:51:14.157  4202  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:51:14.157  1371  1385 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 13:51:14.157  4202  4214 I BluetoothAdapterState: Entering OnState
09-13 13:51:14.164  3881  3892 D BluetoothHeadset: onBluetoothStateChange: up=true,
09-13 13:51:14.165  4202  4202 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 13:51:14.166  4202  4202 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 13:51:14.168  4202  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:51:14.168  1371  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:14.176  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:51:14.179  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:51:14.180  4202  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:51:14.182   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:51:14.182  1945  1958 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:14.184  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:51:14.184  3881  3893 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 13:51:14.185  4202  4202 D ObexServerSockets: Succeed to create listening sockets 
09-13 13:51:14.185  4202  4202 D ObexServerSockets0: startAccept()
09-13 13:51:14.186  4202  4202 D ObexServerSockets0: prepareForNewConnect()
,09-13 13:51:14.187  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:51:14.187  1371  2198 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:51:14.191  3881  3892 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 13:51:14.191  4202  4202 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 13:51:14.191  4202  4202 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 13:51:14.195  4202  4241 D ObexServerSockets0: Accepting socket connection...
,09-13 13:51:14.195  3881  3881 D BluetoothMap: Proxy object connected
09-13 13:51:14.195  4202  4242 D ObexServerSockets0: Accepting socket connection...
09-13 13:51:14.195  1371  1371 D BluetoothMap: Proxy object connected
09-13 13:51:14.195  3881  3881 D MapProfile: Bluetooth service connected
09-13 13:51:14.196  1371  1371 D MapProfile: Bluetooth service connected
,09-13 13:51:14.196  1371  1371 D BluetoothMap: getConnectedDevices()
09-13 13:51:14.196  3881  3881 D BluetoothMap: getConnectedDevices()
09-13 13:51:14.196  3881  3892 D BluetoothPan: onBluetoothStateChange on: true
09-13 13:51:14.198  1371  1371 D BluetoothInputDevice: Proxy object connected
09-13 13:51:14.198  1371  1371 D HidProfile: Bluetooth service connected
,09-13 13:51:14.200   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 13:51:14.201  3881  3881 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:51:14.201  3881  3881 D PanProfile: Bluetooth service connected
09-13 13:51:14.201  1371  2198 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:51:14.202   874   874 D BluetoothA2dp: Proxy object connected
09-13 13:51:14.202  3881  3892 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:51:14.206  3881  3881 D BluetoothInputDevice: Proxy object connected
,09-13 13:51:14.207  3881  3881 D HidProfile: Bluetooth service connected
09-13 13:51:14.207  1371  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 13:51:14.210  1371  1371 D BluetoothA2dp: Proxy object connected
09-13 13:51:14.210  1371  2198 D BluetoothPan: onBluetoothStateChange on: true
,09-13 13:51:14.214  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:51:14.214  1371  1371 D PanProfile: Bluetooth service connected
,09-13 13:51:14.214   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:51:14.214   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:51:14.214  3881  3893 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 13:51:14.218  3881  3881 D BluetoothA2dp: Proxy object connected
,09-13 13:51:14.219   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 13:51:14.220  4202  4202 D BluetoothMapService: onReceive
,09-13 13:51:14.220  4202  4202 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:51:14.220  4202  4202 D BluetoothMapService: STATE_ON
09-13 13:51:14.221  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:14.222  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:14.228  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:51:14.240  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:51:14.241  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:51:14.247  3881  3881 D BluetoothPbap: Proxy object connected
,09-13 13:51:14.247  3881  3881 D PbapServerProfile: Bluetooth service connected
09-13 13:51:14.247  4202  4202 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 13:51:14.247  4202  4202 D ObexServerSockets0: prepareForNewConnect()
09-13 13:51:14.247  1371  1371 D BluetoothPbap: Proxy object connected
09-13 13:51:14.247  1371  1371 D PbapServerProfile: Bluetooth service connected
,09-13 13:51:14.250  4202  4245 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:51:14.272  3881  3892 D BluetoothHeadset: Proxy object connected
,09-13 13:51:14.273   874   874 D BluetoothHeadset: Proxy object connected
,09-13 13:51:14.273   874   874 D BluetoothHeadset: Proxy object connected
09-13 13:51:14.273  3881  3881 D HeadsetProfile: Bluetooth service connected
,09-13 13:51:14.273  1371  2198 D BluetoothHeadset: Proxy object connected
,09-13 13:51:14.274  1945  2199 D BluetoothHeadset: Proxy object connected
09-13 13:51:14.274   874   874 D BluetoothHeadset: Proxy object connected
09-13 13:51:14.274  1371  1371 D HeadsetProfile: Bluetooth service connected
09-13 13:51:14.276  4202  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:51:14.278  4202  4251 I BtOppRfcommListener: Accept thread started.
,09-13 13:51:14.282   874   891 D BluetoothHeadset: Proxy object connected
09-13 13:51:14.282  1945  2092 D BluetoothHeadset: Proxy object connected
,09-13 13:51:14.303  1371  1384 D BluetoothHeadset: Proxy object connected
,09-13 13:51:14.303  1371  1371 D HeadsetProfile: Bluetooth service connected
,09-13 13:51:14.320   874   891 D BluetoothHeadset: Proxy object connected
09-13 13:51:14.320   874   891 D BluetoothHeadset: Proxy object connected
,09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:17.519  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:51:17.525  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:51:17.527  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:51:17.527  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b492b3 removed from the list
,09-13 13:51:17.528  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:51:17.528  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:17.528  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:17.531  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:51:17.531  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b073070 added. We now have 4 listener(s)
09-13 13:51:17.532  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:51:17.535   874  1962 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,09-13 13:51:17.536   874  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:51:22.550  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:22.551   874   885 D WifiService: setWifiEnabled: true pid=3797, uid=10000
09-13 13:51:22.551   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:51:22.567   874  1313 D WifiConfigStore: Loading config and enabling all networks 
,09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:22.589  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:51:22.595  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:51:22.609  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:51:22.611   874  1313 D WifiConfigStore: loaded 0 passpoint configs
,09-13 13:51:22.613   874  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 13:51:22.613   874  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 13:51:22.614   874  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 13:51:22.614   874  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 13:51:22.614   874  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 13:51:22.615   874  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-13 13:51:22.616  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:51:22.630   874  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:51:22.631   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 13:51:22.634   374   873 D CommandListener: Setting iface cfg
,09-13 13:51:22.684   874  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-13 13:51:22.684   874  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 13:51:22.687   874  1313 E native  : do suspend true
,09-13 13:51:22.708   874  1312 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 13:51:22.721   874  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 13:51:22.721   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:51:23.918   874  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:51:24.062   874  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.66 rxSuccessRate=2.28 delta 1000 -> 1000
,09-13 13:51:24.064   874  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 13:51:24.064   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:51:24.083   874  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 13:51:24.120   874  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 13:51:24.121  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 13:51:24.558  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 13:51:24.605  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 13:51:24.606  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 13:51:24.612   874  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:51:24.632   874  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 13:51:24.633   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:51:24.633   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 13:51:24.662   874  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:51:24.687   374   873 D CommandListener: Setting iface cfg
,09-13 13:51:24.689   874  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 13:51:24.705   874  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 13:51:24.726   874  4261 D DhcpClient: Receive thread started
,09-13 13:51:24.825   874  1313 E native  : do suspend false
,09-13 13:51:24.851   874  1879 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 13:51:24.870   874  4261 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-13 13:51:24.871   874  1879 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-13 13:51:24.877   874  1879 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 13:51:24.899   874  4261 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 13:51:24.900   874  1879 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 13:51:24.907   374   873 D CommandListener: Setting iface cfg
,09-13 13:51:24.919   874  1879 D DhcpClient: Scheduling renewal in 86399s
,09-13 13:51:24.920   874  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 13:51:24.923   874  1313 E native  : do suspend true
,09-13 13:51:24.950   874  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 13:51:24.953   874  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 13:51:24.954   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 13:51:24.958   874  1315 D ConnectivityService: Adding iface wlan0 to network 102
09-13 13:51:24.960   874  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 13:51:25.028   874  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 13:51:25.028   874  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 13:51:25.031   874  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 13:51:25.035   874  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 13:51:25.038   874  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 13:51:25.052   874  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 13:51:25.057   874  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-13 13:51:25.058   874  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-13 13:51:25.058   874  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 13:51:25.058   874  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 13:51:25.059   874  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 13:51:25.059   874  1315 D ConnectivityService:    accepting network in place of null
,09-13 13:51:25.060   874  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:51:25.084   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195000, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:51:25.106   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:51:25.153   874  4259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 13:51:25.169   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:51:25.179   874  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 13:51:25.180   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:51:25.189   874  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-13 13:51:25.191   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:25.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:25.215   874  4259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 11:51:25 GMT], X-Android-Received-Millis=[1473767485215], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473767485190]}
,09-13 13:51:25.217   874  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 13:51:25.218   874  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-13 13:51:25.218   874  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102],
,09-13 13:51:25.219   874  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 13:51:25.222  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:25.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:51:25.228  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:25.229  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:51:25.236  1722  1722 D SystemUpdateService: onCreate
,09-13 13:51:25.239  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:51:25.259  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 13:51:25.265  1722  4271 I SystemUpdateService: active receiver: enabled
,09-13 13:51:25.268  1722  2465 I iu.UploadsManager: num queued entries: 0
,09-13 13:51:25.268  1722  2465 I iu.UploadsManager: num updated entries: 0
,09-13 13:51:25.273  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:51:25.274  1722  4271 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:51:25.275  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:51:25.276  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:51:25.281  1722  4273 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 13:51:25.281  1722  4273 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 13:51:25.282  1722  4273 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 13:51:25.287  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:51:25.290  3937  3937 D SprintDMHelper: simOperator: 
09-13 13:51:25.291  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-13 13:51:25.291  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:25.302  1722  2465 I iu.SyncManager: NEXT; no task
,09-13 13:51:25.317  1722  4271 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 13:51:25.317  1722  4271 I SystemUpdateService: now status is 0 (complete)
09-13 13:51:25.317  1722  4271 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:51:25.317  1722  4271 I SystemUpdateService: file has been verified
09-13 13:51:25.317  1722  4271 I SystemUpdateService: OTA package size = 12249756
,09-13 13:51:25.323   874   886 I ActivityManager: Start proc 4277:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-13 13:51:25.362  1722  4271 I SystemUpdateService: showing system update notification
,09-13 13:51:25.383  4277  4277 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-13 13:51:25.390  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-13 13:51:25.390  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-13 13:51:25.390  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:51:25.397  1722  1722 D SystemUpdateService: onDestroy
,09-13 13:51:25.390  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:25.419  1722  4273 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-13 13:51:25.430  4052  4292 V KeepSync: Connecting to GoogleApiClient
,09-13 13:51:25.430   874  1701 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:51:25.447  4277  4277 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-13 13:51:25.459  4277  4277 I BooksApp: Created application version: 3.6.9 (30609)
,09-13 13:51:25.495  2281  4276 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 13:51:25.495  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:51:25.496  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:51:25.496  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:51:25.496  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:25.528  1722  4299 V BaseAuthAsyncOperation: access token request failed
,09-13 13:51:25.529  4052  4292 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:51:25.588  4277  4300 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:51:25.761  4277  4307 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:51:25.800  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:51:25.801  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:51:25.801  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:25.801  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:25.812  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:51:25.813  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 13:51:25.821  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:25.822  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:25.831  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:51:25.832  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:51:25.832  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:25.832  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:25.843  4277  4307 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:51:25.845  4277  4300 E BooksSync: Soft error
09-13 13:51:25.845  4277  4300 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:51:25.845  4277  4300 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:51:25.848  4277  4300 E BooksSync: Sync error
09-13 13:51:25.848  4277  4300 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:51:25.848  4277  4300 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:51:25.848  4277  4300 I BooksSync: Finished books sync
,09-13 13:51:25.859   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161936, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:51:25.865  4052  4292 E KeepSync: IOException
09-13 13:51:25.865  4052  4292 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:51:25.865  4052  4292 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:51:25.865  4052  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:51:25.865  4052  4292 E KeepSync: 	... 10 more
,09-13 13:51:25.865  4052  4292 W KeepSync: Sync result 2
,09-13 13:51:25.891   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 162015, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:51:26.074   874  1701 I ActivityManager: Killing 2219:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 13:51:26.178   874  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:27.580  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:27.587  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:27.588  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:27.589  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b073070 removed from the list
,09-13 13:51:27.589  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:51:27.589  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:27.589  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:27.603  3797  4309 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 13:51:27.604  3797  4309 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 13:51:30.442  4277  4297 I art     : Waiting for a blocking GC DisableMovingGc
,09-13 13:51:30.446  4277  4297 I art     : Starting a blocking GC DisableMovingGc
,09-13 13:51:30.462  4277  4297 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 13:51:30.609  3797  4309 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 13:51:30.609  3797  4312 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 13:51:30.610  3797  4309 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:51:30.610  3797  4312 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:51:30.610  3797  4309 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:51:30.610  3797  4312 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:51:30.610  3797  4309 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:51:30.611  3797  4309 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 13:51:30.611  3797  4312 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 13:51:30.615  3797  4314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
,09-13 13:51:30.616  3797  4312 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 13:51:30.619  3797  4315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
,09-13 13:51:30.620  3797  4315 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
09-13 13:51:30.621  3797  4316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
09-13 13:51:30.621  3797  4315 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 13:51:30.621  3797  4315 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 13:51:30.622  3797  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
09-13 13:51:30.623  3797  4317 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
09-13 13:51:30.624  3797  4317 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 13:51:30.624  3797  4317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 13:51:33.065   874  1315 D ConnectivityService: handlePromptUnvalidated 102
,09-13 13:51:33.609  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 13:51:33.611  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 13:51:33.618  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bbd1cc Bundle[{}]
,09-13 13:51:33.619  3797  3849 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 13:51:33.619  3797  3849 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 13:51:33.619  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 13:51:33.620  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 13:51:33.621  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 13:51:33.621  3797  3849 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 13:51:33.625  3797  3849 I System.out: Running OutgoingSocketThread
,09-13 13:51:33.629  3797  4318 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 13:51:33.629  3797  4318 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 13:51:33.953  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:33.964  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:33.968  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:34.008  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:51:34.008  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 13:51:34.008  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:34.009  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:34.040  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:51:34.040  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 13:51:34.041  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 13:51:35.543  3516  3527 D Finsky  : [269] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-13 13:51:35.560  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:35.600  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 13:51:35.600  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 13:51:35.600  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:35.600  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:35.641  3516  3527 D Finsky  : [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-13 13:51:36.639  3797  4320 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 13:51:36.639  3797  4320 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:51:36.640  3797  4318 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 13:51:36.640  3797  4320 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:51:36.640  3797  4318 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 13:51:36.640  3797  4318 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:51:36.641  3797  4320 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
09-13 13:51:36.643  3797  4320 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 13:51:36.646  3797  4318 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 13:51:36.648  3797  4318 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 13:51:36.649  3797  4322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Sender)
,09-13 13:51:36.657  3797  4324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
,09-13 13:51:36.660  3797  4323 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Receiver)
,09-13 13:51:36.661  3797  4325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Receiver)
09-13 13:51:36.662  3797  4323 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: IncomingSocketThread/Receiver)
09-13 13:51:36.662  3797  4323 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 13:51:36.662  3797  4323 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 13:51:36.662  3797  4325 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: OutgoingSocketThread/Receiver)
09-13 13:51:36.663  3797  4325 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 13:51:36.663  3797  4325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 13:51:39.641  3797  3849 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-13 13:51:39.644  3797  3849 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 13:51:39.644  3797  3849 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,09-13 13:51:39.650  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:51:39.650  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@971efe9 added. We now have 3 listener(s)
09-13 13:51:39.652  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:51:39.652  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:51:39.652  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:51:39.652  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:51:39.652  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2546e added. We now have 4 listener(s)
09-13 13:51:39.652  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:51:39.654  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:51:39.661  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:39.676  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:39.682  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:39.683  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:51:39.684  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:51:39.685  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:51:39.685  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:51:39.686  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:51:39.686  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:39.688  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:51:39.688  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:51:39.690  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@971efe9 removed from the list
09-13 13:51:39.691  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:39.691  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:39.691  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2546e removed from the list
,09-13 13:51:39.699  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:39.700  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:51:39.700  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:39.702  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:39.702  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:39.706  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:39.707  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:39.707  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:39.707  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2546e not in the list
09-13 13:51:39.708  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:39.708  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:39.712  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:39.712  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:51:39.712  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:51:39.713  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2546e not in the list
09-13 13:51:39.713  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:39.713  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:39.714  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:39.714  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@971efe9 not in the list
09-13 13:51:39.716  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:51:39.717  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@586e39c added. We now have 3 listener(s)
,09-13 13:51:39.724  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:51:39.724  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:51:39.725  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 13:51:39.725  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:51:39.726  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a70a1a5 added. We now have 4 listener(s)
09-13 13:51:39.726  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:51:39.728  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:51:39.735  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:39.750  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:39.756  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:39.757  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:51:39.757  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:51:39.758  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:51:39.758  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:51:39.758  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:51:39.758  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 13:51:39.763  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:39.766  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:51:39.767  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:51:39.768  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:39.779  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:51:39.780  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:51:39.780  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:51:39.793  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 13:51:39.793  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:51:39.794  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 13:51:39.796  3797  3849 D BluetoothAdapter: STATE_ON
,09-13 13:51:39.807  4202  4233 D BtGatt.GattService: registerClient() - UUID=25ae62e7-54a9-4c31-838b-43d41e139401
,09-13 13:51:39.811  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=25ae62e7-54a9-4c31-838b-43d41e139401, clientIf=5
,09-13 13:51:39.813  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 13:51:39.817  4202  4252 D BtGatt.GattService: start scan with filters
,09-13 13:51:39.831  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:51:39.831  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:51:39.832  4202  4221 D BtGatt.ScanManager: handling starting scan
09-13 13:51:39.832  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:51:39.832  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:51:39.839  4202  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d89ba0
,09-13 13:51:39.844  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-13 13:51:39.845  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:51:39.845  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:51:39.852  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:51:39.856  3797  3849 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 13:51:39.857  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:51:39.857  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:51:39.857  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:39.857  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:51:39.857  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:51:39.857  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 13:51:39.857  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:51:39.857  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 13:51:39.857  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:51:39.857  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 13:51:39.858  3797  3849 D BluetoothAdapter: STATE_ON
09-13 13:51:39.859  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 13:51:39.859  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:51:39.859  4202  4233 D BtGatt.GattService: stopScan() - queue size =1
09-13 13:51:39.861  4202  4252 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 13:51:39.861  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:51:39.861  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:51:39.861  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 13:51:39.861  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:51:39.861  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 13:51:39.862  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 13:51:39.862  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:51:39.862  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:51:39.863  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:51:39.863  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:51:39.863  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:51:39.865  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:51:39.865  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:51:39.865  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:51:39.877  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 13:51:39.878  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:39.879  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:51:39.879  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:51:39.914  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:51:39.915  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:39.938  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 13:51:39.938  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:39.967  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:51:39.967  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:39.968  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
,09-13 13:51:39.983  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 13:51:39.983  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:39.984  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:51:39.993  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:51:39.993  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:40.083  1882  2002 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-13 13:51:40.084  1882  2002 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-13 13:51:40.136  1513  1513 I ConfigService: onCreate
,09-13 13:51:40.366  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-13 13:51:40.367  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:51:40.367  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:51:42.866  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:51:42.867  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:51:42.867  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:51:42.868  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:42.868  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:42.869  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:51:42.869  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:51:42.870  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@586e39c removed from the list
,09-13 13:51:42.870  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:42.870  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a70a1a5 removed from the list
09-13 13:51:42.871  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:51:42.871  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:42.873  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:42.873  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:42.879  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:51:42.879  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:42.879  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:42.880  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a70a1a5 not in the list
,09-13 13:51:42.880  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:42.880  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:42.884  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:42.884  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:42.884  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:51:42.885  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a70a1a5 not in the list
09-13 13:51:42.885  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:42.885  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:42.885  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:42.886  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@586e39c not in the list
09-13 13:51:42.888  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:51:42.889  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bc8346 added. We now have 3 listener(s)
,09-13 13:51:42.895  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:51:42.896  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:51:42.896  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:51:42.897  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:51:42.897  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9676907 added. We now have 4 listener(s)
,09-13 13:51:42.898  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:51:42.899  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:51:42.907  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:42.922  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:42.929  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:42.929  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:51:42.930  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 13:51:42.935  3797  3849 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-13 13:51:42.935  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 13:51:42.937  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:42.944  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 13:51:42.944  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 13:51:42.945  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 13:51:42.946  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:51:42.947  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:42.949  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 13:51:42.950  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 13:51:42.950  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 13:51:42.951  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 13:51:42.952  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 13:51:42.952  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 13:51:42.952  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:51:42.952  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 13:51:42.958  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 13:51:42.958  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:51:42.960  3797  4329 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:51:42.966  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:51:42.967  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:51:42.967  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:51:42.968  3797  4329 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 13:51:42.970  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 13:51:42.970  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:51:42.971  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-13 13:51:42.972  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 13:51:42.972  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 13:51:42.972  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 13:51:42.973  3797  3849 D BluetoothAdapter: STATE_ON
,09-13 13:51:42.977  4202  4233 D BtGatt.GattService: registerClient() - UUID=78447e20-0ee9-400d-9a5a-c18da10f6551
09-13 13:51:42.978  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=78447e20-0ee9-400d-9a5a-c18da10f6551, clientIf=5
,09-13 13:51:42.978  3797  3810 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 13:51:42.983  4202  4220 D BtGatt.AdvertiseManager: message : 0
,09-13 13:51:42.986  4202  4220 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 13:51:43.003  4202  4218 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 13:51:43.012  4202  4218 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 13:51:43.015  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 13:51:43.015  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:51:43.017  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:51:43.019  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 13:51:43.019  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 13:51:43.019  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 13:51:43.019  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 13:51:43.019  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 13:51:43.019  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 13:51:43.023  3797  3797 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 13:51:43.023  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 13:51:43.026  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 13:51:43.026  3797  3849 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:51:43.524  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 13:51:45.224  1513  1513 I ConfigService: onDestroy
,09-13 13:51:46.028  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:51:46.029  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 13:51:46.029  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
09-13 13:51:46.029  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 13:51:46.030  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 13:51:46.030  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 13:51:46.032  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:51:46.032  3797  4329 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 13:51:46.032  3797  4329 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 13:51:46.032  3797  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 13:51:46.032  3797  4329 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 13:51:46.032  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:51:46.033  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 13:51:46.033  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:51:46.033  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:51:46.033  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 13:51:46.034  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:51:46.036  3797  3849 D BluetoothAdapter: STATE_ON
09-13 13:51:46.037  3797  3849 D BluetoothLeScanner: could not find callback wrapper
09-13 13:51:46.038  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:51:46.038  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 13:51:46.041  4202  4220 D BtGatt.AdvertiseManager: message : 1
,09-13 13:51:46.042  4202  4220 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 13:51:46.053  4202  4218 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 13:51:46.053  4202  4218 D BtGatt.GattService: Client app is not null!
,09-13 13:51:46.056  4202  4252 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:51:46.058  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:51:46.058  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 13:51:46.058  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 13:51:46.059  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 13:51:46.059  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 13:51:46.062  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:51:46.063  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:51:46.063  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:51:46.065  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:51:46.069  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:51:46.069  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:51:46.070  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 13:51:46.070  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:51:46.070  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:51:46.071  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:51:46.071  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:46.071  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:46.071  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:51:46.071  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:51:46.071  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bc8346 removed from the list
09-13 13:51:46.071  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:46.072  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9676907 removed from the list
09-13 13:51:46.072  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:51:46.072  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:46.072  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:46.073  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:46.074  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:46.074  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:46.074  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:46.074  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9676907 not in the list
09-13 13:51:46.074  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:46.074  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:46.077  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:46.077  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:46.077  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:46.077  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9676907 not in the list
09-13 13:51:46.078  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:46.078  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:46.078  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:46.079  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bc8346 not in the list
,09-13 13:51:46.080  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:51:46.081  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3f95a0 added. We now have 3 listener(s)
,09-13 13:51:46.087  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:51:46.087  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:51:46.088  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 13:51:46.088  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:51:46.089  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369a559 added. We now have 4 listener(s)
09-13 13:51:46.089  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:51:46.091  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:51:46.094  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:46.102  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:46.106  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:46.107  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:51:46.107  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:51:46.107  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 13:51:46.108  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:51:46.108  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:51:46.108  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:51:46.110  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:46.115  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:46.116  3797  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:51:46.116  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:51:46.122  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:51:46.124  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 13:51:46.124  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:51:46.131  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 13:51:46.132  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:51:46.132  3797  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 13:51:46.134  3797  3849 D BluetoothAdapter: STATE_ON
,09-13 13:51:46.140  4202  4213 D BtGatt.GattService: registerClient() - UUID=cc242b96-8a4b-436f-8de8-d6c2d3027f19
,09-13 13:51:46.141  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=cc242b96-8a4b-436f-8de8-d6c2d3027f19, clientIf=5
,09-13 13:51:46.141  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 13:51:46.142  4202  4252 D BtGatt.GattService: start scan with filters
,09-13 13:51:46.150  4202  4221 D BtGatt.ScanManager: handling starting scan
,09-13 13:51:46.150  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 13:51:46.150  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:51:46.151  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 13:51:46.151  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:51:46.160  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:51:46.161  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:51:46.162  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:51:46.168  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:51:46.170  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 13:51:46.170  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:51:46.170  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 13:51:46.177  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 13:51:46.177  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:51:46.177  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:51:46.177  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:51:46.190  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:51:46.190  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:46.197  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 13:51:46.197  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:46.572  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:51:46.662  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 13:51:46.662  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:51:46.662  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:51:47.704  4202  4202 D BtGatt.ScanManager: awakened up at time 217621
,09-13 13:51:47.707  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:51:47.753  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-13 13:51:47.753  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:51:47.754  4202  4218 D BtGatt.GattService: current time is 217670993424
,09-13 13:51:47.755  4202  4218 D BtGatt.GattService: Batch record : [-126, -22, -96, 83, -39, -56, 1, -128, -74, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 87, 45, 110, 28, -13, -4, 1, -128, -61, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -102, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -101, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 13:51:47.759  4202  4218 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
,09-13 13:51:47.761  4202  4218 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,09-13 13:51:47.762  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 13:51:47.763  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 13:51:47.764  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:51:47.764  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:51:47.765  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 13:51:47.772  3797  3797 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 1
,09-13 13:51:47.774  3797  3797 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 2
,09-13 13:51:47.775  3797  3797 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-13 13:51:47.776  3797  3797 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-13 13:51:49.183  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:51:49.183  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:51:49.184  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:51:49.184  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:49.185  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 13:51:49.188  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:51:49.190  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:51:49.190  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:51:49.190  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:51:49.191  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:51:49.191  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 13:51:49.193  3797  3849 D BluetoothAdapter: STATE_ON
09-13 13:51:49.196  4202  4252 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:51:49.199  4202  4212 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:51:49.200  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 13:51:49.201  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 13:51:49.203  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 13:51:49.204  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:51:49.205  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 13:51:49.208  4202  4202 D BtGatt.ScanManager: awakened up at time 219125
,09-13 13:51:49.209  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:51:49.210  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:51:49.211  3797  3849 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:51:49.212  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:51:49.215  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:51:49.215  3797  3849 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-13 13:51:49.218  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:51:49.218  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:49.218  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:51:49.218  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:51:49.219  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:51:49.219  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:51:49.219  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 13:51:49.219  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3f95a0 removed from the list
09-13 13:51:49.219  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:49.220  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369a559 removed from the list
,09-13 13:51:49.220  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:51:49.220  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:49.221  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:49.221  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:51:49.221  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:49.221  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:51:49.221  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
09-13 13:51:49.222  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:49.222  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:49.222  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:49.222  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369a559 not in the list
09-13 13:51:49.222  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:49.222  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:49.224  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:49.224  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:49.224  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:49.225  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369a559 not in the list
09-13 13:51:49.225  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:49.225  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:51:49.226  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:49.226  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3f95a0 not in the list
,09-13 13:51:49.228  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:51:49.228  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec678b8 added. We now have 3 listener(s)
,09-13 13:51:49.234  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:51:49.234  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:51:49.234  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:51:49.234  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:51:49.234  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@999a691 added. We now have 4 listener(s)
09-13 13:51:49.234  3797  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:51:49.235  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:51:49.235  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 13:51:49.235  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:51:49.236  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:51:49.238  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:51:49.243  3797  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:51:49.246  3797  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:51:49.247  3797  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:51:49.247  3797  3849 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:51:49.247  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:51:49.247  3797  3849 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:51:49.247  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:49.248  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:49.248  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:51:49.248  3797  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:51:49.248  3797  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec678b8 removed from the list
09-13 13:51:49.248  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:49.248  3797  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@999a691 removed from the list
,09-13 13:51:49.251  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:51:49.253  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:51:49.254  3797  3849 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:51:49.254  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:49.254  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:49.254  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:49.256  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:51:49.256  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:49.256  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:49.256  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@999a691 not in the list
09-13 13:51:49.256  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:49.256  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:51:49.257  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:51:49.257  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:51:49.257  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-13 13:51:49.257  3797  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:51:49.257  3797  3849 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@999a691 not in the list
,09-13 13:51:49.257  3797  3849 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:51:49.258  3797  3849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:51:49.257  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:51:49.258  3797  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:51:49.258  3797  3849 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec678b8 not in the list
,09-13 13:51:49.258  4202  4218 D BtGatt.GattService: current time is 219175111529
09-13 13:51:49.258  4202  4218 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:51:49.259  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 13:51:49.259  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 13:51:49.259  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:51:49.259  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 13:51:49.259  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:51:49.259  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 13:51:49.260  3797  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:51:49.720  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:51:51.275  3797  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-13 13:51:53.272  3797  3849 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 460
,09-13 13:51:53.273  3797  3849 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 460, name: My test thread name)
,09-13 13:51:53.279  3797  4333 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,09-13 13:51:53.280  3797  4333 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
,09-13 13:51:53.281  3797  4333 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 13:51:53.285  3797  3849 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 13:51:53.293  3797  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,09-13 13:51:53.295  3797  4332 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-13 13:51:53.297  3797  4334 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 465, thread name: My test thread name): Test exception.
,09-13 13:51:53.297  3797  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 13:51:53.305  3797  3849 I jxcore-log: Total number of executed tests:  82
09-13 13:51:53.305  3797  3849 I jxcore-log: 
,09-13 13:51:53.306  3797  3849 I jxcore-log: Number of passed tests:  82
09-13 13:51:53.306  3797  3849 I jxcore-log: 
,09-13 13:51:53.307  3797  3849 I jxcore-log: Number of failed tests:  0
09-13 13:51:53.307  3797  3849 I jxcore-log: 
,09-13 13:51:53.308  3797  3849 I jxcore-log: Number of ignored tests:  0
09-13 13:51:53.308  3797  3849 I jxcore-log: 
09-13 13:51:53.308  3797  3849 I jxcore-log: Total duration:  101531
09-13 13:51:53.308  3797  3849 I jxcore-log: 
,09-13 13:51:53.318  3797  3849 I jxcore-log: Unit Test app is loaded
09-13 13:51:53.318  3797  3849 I jxcore-log: 
,09-13 13:51:53.333  3797  3797 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 13:51:53.333  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.333  3797  3849 I jxcore-log: 
,09-13 13:51:53.337  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.337  3797  3849 I jxcore-log: 
,09-13 13:51:53.338  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.338  3797  3849 I jxcore-log: 
,09-13 13:51:53.339  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.339  3797  3849 I jxcore-log: 
09-13 13:51:53.341  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 13:51:53.341  3797  3849 I jxcore-log: 
,09-13 13:51:53.342  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:51:53.342  3797  3849 I jxcore-log: 
,09-13 13:51:53.345  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.345  3797  3849 I jxcore-log: 
,09-13 13:51:53.347  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.347  3797  3849 I jxcore-log: 
09-13 13:51:53.348  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 13:51:53.348  3797  3849 I jxcore-log: 
,09-13 13:51:53.348  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:51:53.348  3797  3849 I jxcore-log: 
09-13 13:51:53.349  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:51:53.349  3797  3849 I jxcore-log: 
09-13 13:51:53.351  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.351  3797  3849 I jxcore-log: 
,09-13 13:51:53.352  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.352  3797  3849 I jxcore-log: 
,09-13 13:51:53.353  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.353  3797  3849 I jxcore-log: 
,09-13 13:51:53.354  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.354  3797  3849 I jxcore-log: 
,09-13 13:51:53.355  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.355  3797  3849 I jxcore-log: 
09-13 13:51:53.356  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.356  3797  3849 I jxcore-log: 
09-13 13:51:53.357  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.357  3797  3849 I jxcore-log: 
,09-13 13:51:53.358  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.358  3797  3849 I jxcore-log: 
,09-13 13:51:53.358  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.358  3797  3849 I jxcore-log: 
09-13 13:51:53.360  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.360  3797  3849 I jxcore-log: 
09-13 13:51:53.360  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.360  3797  3849 I jxcore-log: 
09-13 13:51:53.361  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.361  3797  3849 I jxcore-log: 
09-13 13:51:53.362  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.362  3797  3849 I jxcore-log: 
,09-13 13:51:53.363  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.363  3797  3849 I jxcore-log: 
09-13 13:51:53.364  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.364  3797  3849 I jxcore-log: 
09-13 13:51:53.365  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.365  3797  3849 I jxcore-log: 
,09-13 13:51:53.365  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.365  3797  3849 I jxcore-log: 
09-13 13:51:53.366  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.366  3797  3849 I jxcore-log: 
09-13 13:51:53.367  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.367  3797  3849 I jxcore-log: 
,09-13 13:51:53.368  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.368  3797  3849 I jxcore-log: 
09-13 13:51:53.369  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.369  3797  3849 I jxcore-log: 
,09-13 13:51:53.370  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.370  3797  3849 I jxcore-log: 
,09-13 13:51:53.371  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.371  3797  3849 I jxcore-log: 
09-13 13:51:53.371  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.371  3797  3849 I jxcore-log: 
,09-13 13:51:53.372  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.372  3797  3849 I jxcore-log: 
09-13 13:51:53.372  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.372  3797  3849 I jxcore-log: 
09-13 13:51:53.373  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:51:53.373  3797  3849 I jxcore-log: 
09-13 13:51:53.373  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.373  3797  3849 I jxcore-log: 
09-13 13:51:53.374  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 13:51:53.374  3797  3849 I jxcore-log: 
,09-13 13:51:53.374  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.374  3797  3849 I jxcore-log: 
09-13 13:51:53.375  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.375  3797  3849 I jxcore-log: 
09-13 13:51:53.375  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.375  3797  3849 I jxcore-log: 
09-13 13:51:53.376  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.376  3797  3849 I jxcore-log: 
09-13 13:51:53.376  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.376  3797  3849 I jxcore-log: 
,09-13 13:51:53.377  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:51:53.377  3797  3849 I jxcore-log: 
09-13 13:51:53.377  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.377  3797  3849 I jxcore-log: 
09-13 13:51:53.378  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 13:51:53.378  3797  3849 I jxcore-log: 
09-13 13:51:53.378  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.378  3797  3849 I jxcore-log: 
,09-13 13:51:53.379  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:51:53.379  3797  3849 I jxcore-log: 
09-13 13:51:53.380  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 13:51:53.380  3797  3849 I jxcore-log: 
09-13 13:51:53.380  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 13:51:53.380  3797  3849 I jxcore-log: 
09-13 13:51:53.381  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 13:51:53.381  3797  3849 I jxcore-log: 
,09-13 13:51:53.381  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:51:53.381  3797  3849 I jxcore-log: 
09-13 13:51:53.382  3797  3849 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:51:53.382  3797  3849 I jxcore-log: 
,09-13 13:51:53.386  3797  3849 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-13 13:51:53.386  3797  3849 I jxcore-log:   bluetooth: 'on',
09-13 13:51:53.386  3797  3849 I jxcore-log:   wifi: 'on',
09-13 13:51:53.386  3797  3849 I jxcore-log:   cellular: 'doNotCare',
09-13 13:51:53.386  3797  3849 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 13:51:53.386  3797  3849 I jxcore-log: 
,09-13 13:51:53.399  3797  3849 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-13 13:51:53.399  3797  3849 I jxcore-log:   bluetooth: 'on',
09-13 13:51:53.399  3797  3849 I jxcore-log:   wifi: 'on',
09-13 13:51:53.399  3797  3849 I jxcore-log:   cellular: 'doNotCare',
09-13 13:51:53.399  3797  3849 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 13:51:53.399  3797  3849 I jxcore-log: 
,09-13 13:51:53.402  3797  3849 I jxcore-log: My device name is: motorola-Nexus 6
09-13 13:51:53.402  3797  3849 I jxcore-log: 
,09-13 13:51:53.405  3797  3849 I jxcore-log: Running for WIFI network type
09-13 13:51:53.405  3797  3849 I jxcore-log: 
,09-13 13:51:54.438  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:54.446  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:51:54.448  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:51:54.483  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 13:51:54.483  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 13:51:54.484  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:51:54.484  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:54.512  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:51:54.512  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 13:51:54.512  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 13:51:55.958  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 13:51:55.958  3797  3849 I jxcore-log: 
,09-13 13:51:56.412  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 13:51:56.412  3797  3849 I jxcore-log: 
,09-13 13:51:56.437  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 13:51:56.437  3797  3849 I jxcore-log: 
,09-13 13:51:57.058  4277  4335 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:51:57.099  4277  4336 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:51:57.139  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:51:57.139  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:51:57.140  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:51:57.140  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:57.195  1513  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:51:57.195  1513  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:51:57.196  1513  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:51:57.196  1513  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:51:57.217  4277  4336 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:51:57.218  4277  4335 E BooksSync: Soft error
09-13 13:51:57.218  4277  4335 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:51:57.218  4277  4335 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:51:57.218  4277  4335 E BooksSync: Sync error
09-13 13:51:57.218  4277  4335 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:51:57.218  4277  4335 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:51:57.218  4277  4335 I BooksSync: Finished books sync
,09-13 13:51:57.238   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 226828, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:51:57.845  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 13:51:57.845  3797  3849 I jxcore-log: 
,09-13 13:51:58.081  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 13:51:58.081  3797  3849 I jxcore-log: 
,09-13 13:51:58.087  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 13:51:58.087  3797  3849 I jxcore-log: 
,09-13 13:51:58.094  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 13:51:58.094  3797  3849 I jxcore-log: 
,09-13 13:51:58.170  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 13:51:58.170  3797  3849 I jxcore-log: 
,09-13 13:51:58.190  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 13:51:58.190  3797  3849 I jxcore-log: 
,09-13 13:51:58.196  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 13:51:58.196  3797  3849 I jxcore-log: 
,09-13 13:51:59.119  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 13:51:59.119  3797  3849 I jxcore-log: 
,09-13 13:51:59.287  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 13:51:59.287  3797  3849 I jxcore-log: 
,09-13 13:51:59.650  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 13:51:59.650  3797  3849 I jxcore-log: 
,09-13 13:51:59.660  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 13:51:59.660  3797  3849 I jxcore-log: 
,09-13 13:51:59.666  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 13:51:59.666  3797  3849 I jxcore-log: 
,09-13 13:51:59.672  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 13:51:59.672  3797  3849 I jxcore-log: 
,09-13 13:51:59.709  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 13:51:59.709  3797  3849 I jxcore-log: 
,09-13 13:51:59.755  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 13:51:59.755  3797  3849 I jxcore-log: 
,09-13 13:51:59.762  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 13:51:59.762  3797  3849 I jxcore-log: 
,09-13 13:51:59.770  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 13:51:59.770  3797  3849 I jxcore-log: 
,09-13 13:51:59.789  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 13:51:59.789  3797  3849 I jxcore-log: 
,09-13 13:51:59.794  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 13:51:59.794  3797  3849 I jxcore-log: 
,09-13 13:51:59.800  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 13:51:59.800  3797  3849 I jxcore-log: 
,09-13 13:51:59.817  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 13:51:59.817  3797  3849 I jxcore-log: 
,09-13 13:51:59.844  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 13:51:59.844  3797  3849 I jxcore-log: 
,09-13 13:51:59.858  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 13:51:59.858  3797  3849 I jxcore-log: 
,09-13 13:51:59.873  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 13:51:59.873  3797  3849 I jxcore-log: 
,09-13 13:51:59.886  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 13:51:59.886  3797  3849 I jxcore-log: 
,09-13 13:51:59.904  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 13:51:59.904  3797  3849 I jxcore-log: 
,09-13 13:51:59.915  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 13:51:59.915  3797  3849 I jxcore-log: 
,09-13 13:51:59.921  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 13:51:59.921  3797  3849 I jxcore-log: 
,09-13 13:51:59.952  3797  3849 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 13:51:59.952  3797  3849 I jxcore-log: 
,09-13 13:51:59.964  3797  3849 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 13:51:59.965  3797  3849 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 13:51:59.965  3797  3849 I jxcore-log: 
,09-13 13:51:59.968  3797  3849 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 13:51:59.968  3797  3849 I jxcore-log: 
,09-13 13:51:59.968  3797  3849 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 13:51:59.968  3797  3849 I jxcore-log: 
,09-13 13:51:59.974  3797  3849 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 13:51:59.974  3797  3849 I jxcore-log: 
,09-13 13:52:00.046  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:00.046  3797  3849 I jxcore-log: 
,09-13 13:52:00.046  3797  3849 I jxcore-log: websocket error
09-13 13:52:00.046  3797  3849 I jxcore-log: 
09-13 13:52:00.046  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:00.046  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:00.046  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:00.046  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:00.046  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:00.046  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:00.046  3797  3849 I jxcore-log: 
,09-13 13:52:01.277  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:01.277  3797  3849 I jxcore-log: 
,09-13 13:52:01.278  3797  3849 I jxcore-log: websocket error
09-13 13:52:01.278  3797  3849 I jxcore-log: 
,09-13 13:52:01.278  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:01.278  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:01.278  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:01.278  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:01.278  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:01.278  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:01.278  3797  3849 I jxcore-log: 
,09-13 13:52:02.527   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=232443, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:52:03.100  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:03.100  3797  3849 I jxcore-log: 
,09-13 13:52:03.101  3797  3849 I jxcore-log: websocket error
09-13 13:52:03.101  3797  3849 I jxcore-log: 
09-13 13:52:03.101  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:03.101  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:03.101  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:03.101  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:03.101  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:03.101  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:03.101  3797  3849 I jxcore-log: 
,09-13 13:52:07.708   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=237624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 13:52:07.827  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:07.827  3797  3849 I jxcore-log: 
,09-13 13:52:07.828  3797  3849 I jxcore-log: websocket error
09-13 13:52:07.828  3797  3849 I jxcore-log: 
09-13 13:52:07.828  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:07.828  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:07.828  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:07.828  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:07.828  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:07.828  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:07.828  3797  3849 I jxcore-log: 
,09-13 13:52:12.316  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:12.316  3797  3849 I jxcore-log: 
,09-13 13:52:12.317  3797  3849 I jxcore-log: websocket error
09-13 13:52:12.317  3797  3849 I jxcore-log: 
,09-13 13:52:12.317  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:12.317  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:12.317  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:12.317  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:12.317  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:12.317  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:12.317  3797  3849 I jxcore-log: 
,09-13 13:52:17.388  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:17.388  3797  3849 I jxcore-log: 
09-13 13:52:17.388  3797  3849 I jxcore-log: websocket error
09-13 13:52:17.388  3797  3849 I jxcore-log: 
,09-13 13:52:17.389  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:17.389  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:17.389  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:17.389  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:17.389  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:17.389  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:17.389  3797  3849 I jxcore-log: 
,09-13 13:52:22.450  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:22.450  3797  3849 I jxcore-log: 
,09-13 13:52:22.451  3797  3849 I jxcore-log: websocket error
09-13 13:52:22.451  3797  3849 I jxcore-log: 
,09-13 13:52:22.452  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:22.452  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:22.452  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:22.452  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:22.452  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:22.452  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:22.452  3797  3849 I jxcore-log: 
,09-13 13:52:27.509  4052  4338 V KeepSync: Connecting to GoogleApiClient
,09-13 13:52:27.509   874  2214 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:52:27.512  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:27.512  3797  3849 I jxcore-log: 
,09-13 13:52:27.513  3797  3849 I jxcore-log: websocket error
09-13 13:52:27.513  3797  3849 I jxcore-log: 
09-13 13:52:27.513  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:27.513  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:27.513  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:27.513  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:27.513  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:27.513  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:27.513  3797  3849 I jxcore-log: 
,09-13 13:52:27.583  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:52:27.590  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:52:27.620  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:52:27.620  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:52:27.620  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:52:27.620  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:52:27.639  1722  4339 V BaseAuthAsyncOperation: access token request failed
,09-13 13:52:27.640  4052  4338 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:52:27.694  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:52:27.694  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:52:27.694  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:52:27.694  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:52:27.713  4052  4338 E KeepSync: IOException
09-13 13:52:27.713  4052  4338 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:52:27.713  4052  4338 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:52:27.713  4052  4338 E KeepSync: 	,at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:52:27.713  4052  4338 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:52:27.713  4052  4338 E KeepSync: 	... 10 more
09-13 13:52:27.713  4052  4338 W KeepSync: Sync result 2
,09-13 13:52:27.724   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 227251, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:52:32.576  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:32.576  3797  3849 I jxcore-log: 
,09-13 13:52:32.577  3797  3849 I jxcore-log: websocket error
09-13 13:52:32.577  3797  3849 I jxcore-log: 
09-13 13:52:32.577  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:32.577  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:32.577  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:32.577  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:32.577  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:32.577  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:32.577  3797  3849 I jxcore-log: 
,09-13 13:52:38.642  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:38.642  3797  3849 I jxcore-log: 
09-13 13:52:38.642  3797  3849 I jxcore-log: websocket error
09-13 13:52:38.642  3797  3849 I jxcore-log: 
,09-13 13:52:38.643  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:38.643  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:38.643  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:38.643  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:38.643  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:38.643  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:38.643  3797  3849 I jxcore-log: 
,09-13 13:52:43.755  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:43.755  3797  3849 I jxcore-log: 
,09-13 13:52:43.756  3797  3849 I jxcore-log: websocket error
09-13 13:52:43.756  3797  3849 I jxcore-log: 
09-13 13:52:43.757  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:43.757  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:43.757  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:43.757  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:43.757  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:43.757  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:43.757  3797  3849 I jxcore-log: 
,09-13 13:52:44.694   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=274611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:52:48.828  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:48.828  3797  3849 I jxcore-log: 
09-13 13:52:48.828  3797  3849 I jxcore-log: websocket error
09-13 13:52:48.828  3797  3849 I jxcore-log: 
09-13 13:52:48.828  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:48.828  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:48.828  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:48.828  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:48.828  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:48.828  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:48.828  3797  3849 I jxcore-log: 
,09-13 13:52:53.814   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=283731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 13:52:53.902  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:53.902  3797  3849 I jxcore-log: 
,09-13 13:52:53.903  3797  3849 I jxcore-log: websocket error
09-13 13:52:53.903  3797  3849 I jxcore-log: 
09-13 13:52:53.904  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:53.904  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:53.904  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:53.904  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:53.904  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:53.904  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:53.904  3797  3849 I jxcore-log: 
,09-13 13:52:58.087  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:52:58.090  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:52:58.125  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 13:52:58.125  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:52:58.125  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:52:58.125  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:52:58.152  3553  4350 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:52:58.152  3553  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:52:58.152  3553  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	... 12 more
09-13 13:52:58.152  3553  4350 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at fal.a(PG:38)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:52:58.152  3553  4350 E HttpOperation: 	... 14 more
,09-13 13:52:58.230  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 13:52:58.230  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 13:52:58.230  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:52:58.230  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:52:58.264  3553  4350 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:52:58.264  3553  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at hec.a(PG:42)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at hee.a(PG:102)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at czr.a(PG:65)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at kka.a(PG:108)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:52:58.264  3553  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	... 15 more
09-13 13:52:58.264  3553  4350 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at fal.a(PG:38)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:52:58.264  3553  4350 E HttpOperation: 	... 17 more
,09-13 13:52:58.265  3553  4350 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:52:58.265  3553  4350 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	... 15 more
09-13 13:52:58.265  3553  4350 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:52:58.265  3553  4350 E ExperimentLoader: 	... 17 more
,09-13 13:52:58.412   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 260452, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:52:58.977  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:52:58.977  3797  3849 I jxcore-log: 
,09-13 13:52:58.978  3797  3849 I jxcore-log: websocket error
09-13 13:52:58.978  3797  3849 I jxcore-log: 
09-13 13:52:58.978  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:52:58.978  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:52:58.978  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:52:58.978  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:58.978  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:52:58.978  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:52:58.978  3797  3849 I jxcore-log: 
,09-13 13:53:04.058  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:53:04.058  3797  3849 I jxcore-log: 
09-13 13:53:04.059  3797  3849 I jxcore-log: websocket error
09-13 13:53:04.059  3797  3849 I jxcore-log: 
,09-13 13:53:04.060  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:53:04.060  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:53:04.060  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:53:04.060  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:04.060  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:53:04.060  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:04.060  3797  3849 I jxcore-log: 
,09-13 13:53:09.116  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:53:09.116  3797  3849 I jxcore-log: 
,09-13 13:53:09.116  3797  3849 I jxcore-log: websocket error
09-13 13:53:09.116  3797  3849 I jxcore-log: 
09-13 13:53:09.116  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:53:09.116  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:53:09.116  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:53:09.116  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:09.116  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:53:09.116  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:09.116  3797  3849 I jxcore-log: 
,09-13 13:53:14.174  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:53:14.174  3797  3849 I jxcore-log: 
,09-13 13:53:14.174  3797  3849 I jxcore-log: websocket error
09-13 13:53:14.174  3797  3849 I jxcore-log: 
09-13 13:53:14.175  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:53:14.175  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:53:14.175  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:53:14.175  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:14.175  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:53:14.175  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:14.175  3797  3849 I jxcore-log: 
,09-13 13:53:19.260  3797  3849 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:53:19.260  3797  3849 I jxcore-log: 
,09-13 13:53:19.261  3797  3849 I jxcore-log: websocket error
09-13 13:53:19.261  3797  3849 I jxcore-log: 
09-13 13:53:19.262  3797  3849 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:53:19.262  3797  3849 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:53:19.262  3797  3849 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:53:19.262  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:19.262  3797  3849 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:53:19.262  3797  3849 I jxcore-log: emit@events.js:82:1
09-13 13:53:19.262  3797  3849 I jxcore-log: 
,09-13 13:53:24.388  3797  3849 I jxcore-log: ThaliTape :: Reconnected to the test server
09-13 13:53:24.388  3797  3849 I jxcore-log: 
,09-13 13:53:24.404  3797  3849 I jxcore-log: ThaliTape :: Connected to the test server
09-13 13:53:24.404  3797  3849 I jxcore-log: 
,09-13 13:53:28.700  4277  4361 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:53:28.722  4277  4362 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:53:28.750  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:28.753  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:28.806  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:53:28.807  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:53:28.807  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:53:28.807  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:28.860  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:28.863  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:28.892  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:53:28.893  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:53:28.893  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:53:28.893  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:28.912  4277  4362 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:53:28.913  4277  4361 E BooksSync: Soft error
09-13 13:53:28.913  4277  4361 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:53:28.913  4277  4361 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:53:28.913  4277  4361 E BooksSync: Sync error
09-13 13:53:28.913  4277  4361 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:53:28.913  4277  4361 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:53:28.913  4277  4361 I BooksSync: Finished books sync
,09-13 13:53:28.928   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289257, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:53:52.468  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:52.478  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:52.484  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:52.538  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 13:53:52.538  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 13:53:52.538  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:53:52.538  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:52.566  1513  2068 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 13:53:52.566  1513  2068 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 13:53:52.566  1513  2068 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 13:53:52.566  1513  2068 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 13:53:52.566  1513  2068 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 13:53:52.566  1513  2068 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 13:53:52.566  1513  2068 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 13:53:52.573  3516  3545 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 13:53:52.573  3516  3545 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 13:53:52.573  3516  3545 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 13:53:52.573  3516  3545 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 13:53:52.573  3516  3545 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 13:53:52.573  3516  3545 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 13:53:52.573  3516  3545 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 13:53:59.174  4052  4367 V KeepSync: Connecting to GoogleApiClient
,09-13 13:53:59.175   874  1701 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:53:59.197  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:59.204  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:53:59.262  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:53:59.262  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:53:59.262  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:53:59.262  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:59.321  3553  4369 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:53:59.321  3553  4369 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:53:59.321  3553  4369 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	... 12 more
09-13 13:53:59.321  3553  4369 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at fal.a(PG:38)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:53:59.321  3553  4369 E HttpOperation: 	... 14 more
,09-13 13:53:59.327  1513  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:53:59.327  1513  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:53:59.327  1513  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:53:59.327  1513  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:59.372  1722  4370 V BaseAuthAsyncOperation: access token request failed
,09-13 13:53:59.375  4052  4367 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:53:59.387  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:53:59.387  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:53:59.388  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:53:59.388  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:59.412  3553  4369 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:53:59.412  3553  4369 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at hec.a(PG:42)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at hee.a(PG:102)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at czr.a(PG:65)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at kka.a(PG:108)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:53:59.412  3553  4369 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	... 15 more
09-13 13:53:59.412  3553  4369 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at fal.a(PG:38)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:53:59.412  3553  4369 E HttpOperation: 	... 17 more
,09-13 13:53:59.413  3553  4369 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:53:59.413  3553  4369 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	... 15 more
09-13 13:53:59.413  3553  4369 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:53:59.413  3553  4369 E ExperimentLoader: 	... 17 more
,09-13 13:53:59.508   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 320728, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:53:59.538  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:53:59.538  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:53:59.538  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:53:59.538  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:53:59.555  4052  4367 E KeepSync: IOException
09-13 13:53:59.555  4052  4367 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:53:59.555  4052  4367 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:53:59.555  4052  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:53:59.555  4052  4367 E KeepSync: 	... 10 more
,09-13 13:53:59.556  4052  4367 W KeepSync: Sync result 2
,09-13 13:53:59.567   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 320527, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:54:58.190  1513  2119 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 13:55:04.571  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:55:04.573  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:55:04.600  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:55:04.600  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:55:04.601  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:55:04.601  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:55:04.620  3553  4376 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:55:04.620  3553  4376 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:55:04.620  3553  4376 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	... 12 more
09-13 13:55:04.620  3553  4376 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at fal.a(PG:38)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:55:04.620  3553  4376 E HttpOperation: 	... 14 more
,09-13 13:55:04.680  1513  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:55:04.680  1513  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:55:04.680  1513  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:55:04.680  1513  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:55:04.697  3553  4376 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:55:04.697  3553  4376 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at hec.a(PG:42)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at hee.a(PG:102)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at czr.a(PG:65)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at kka.a(PG:108)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:55:04.697  3553  4376 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	... 15 more
09-13 13:55:04.697  3553  4376 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at fal.a(PG:38)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:55:04.697  3553  4376 E HttpOperation: 	... 17 more
,09-13 13:55:04.697  3553  4376 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:55:04.697  3553  4376 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	... 15 more
09-13 13:55:04.697  3553  4376 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:55:04.697  3553  4376 E ExperimentLoader: 	... 17 more
,09-13 13:55:04.811   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 414223, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:55:35.039  4277  4381 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:55:35.085  4277  4384 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:55:35.100  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:55:35.103  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:55:35.136  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:55:35.136  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:55:35.136  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:55:35.136  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:55:35.173  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:55:35.176  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:55:35.200  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:55:35.200  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:55:35.200  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:55:35.200  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:55:35.215  4277  4384 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:55:35.216  4277  4381 E BooksSync: Soft error
09-13 13:55:35.216  4277  4381 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:55:35.216  4277  4381 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:55:35.216  4277  4381 E BooksSync: Sync error
09-13 13:55:35.216  4277  4381 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:55:35.216  4277  4381 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:55:35.216  4277  4381 I BooksSync: Finished books sync
,09-13 13:55:35.231   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 443049, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:55:37.037  3797  3849 I jxcore-log: TAP version 13
09-13 13:55:37.037  3797  3849 I jxcore-log: 
,09-13 13:55:37.041  3797  3849 I jxcore-log: # setup
09-13 13:55:37.041  3797  3849 I jxcore-log: 
,09-13 13:55:37.891  3797  3849 I jxcore-log: # 1. calling createNativeListener directly rejects
09-13 13:55:37.891  3797  3849 I jxcore-log: 
,09-13 13:55:38.692  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:38.692  3797  3849 I jxcore-log: 
,09-13 13:55:38.702  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 39781
09-13 13:55:38.702  3797  3849 I jxcore-log: 
,09-13 13:55:38.708  3797  3849 I jxcore-log: ok 1 Should throw
09-13 13:55:38.708  3797  3849 I jxcore-log: 
,09-13 13:55:38.710  3797  3849 I jxcore-log: # teardown
09-13 13:55:38.710  3797  3849 I jxcore-log: 
,09-13 13:55:38.940  3797  3849 I jxcore-log: # setup
09-13 13:55:38.940  3797  3849 I jxcore-log: 
,09-13 13:55:39.707  3797  3849 I jxcore-log: # 2. emits incomingConnectionState
09-13 13:55:39.707  3797  3849 I jxcore-log: 
,09-13 13:55:40.318  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:40.318  3797  3849 I jxcore-log: 
,09-13 13:55:40.327  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 48324
09-13 13:55:40.327  3797  3849 I jxcore-log: 
,09-13 13:55:40.344  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:40.344  3797  3849 I jxcore-log: 
,09-13 13:55:40.346  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:40.346  3797  3849 I jxcore-log: 
,09-13 13:55:40.356  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:40.356  3797  3849 I jxcore-log: 
,09-13 13:55:40.362  3797  3849 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-13 13:55:40.362  3797  3849 I jxcore-log: 
,09-13 13:55:40.385  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:40.385  3797  3849 I jxcore-log: 
,09-13 13:55:40.386  3797  3849 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-13 13:55:40.386  3797  3849 I jxcore-log: 
,09-13 13:55:40.393  3797  3849 I jxcore-log: # teardown
09-13 13:55:40.393  3797  3849 I jxcore-log: 
,09-13 13:55:40.844  3797  3849 I jxcore-log: # setup
09-13 13:55:40.844  3797  3849 I jxcore-log: 
,09-13 13:55:41.662  3797  3849 I jxcore-log: # 3. emits routerPortConnectionFailed
09-13 13:55:41.662  3797  3849 I jxcore-log: 
,09-13 13:55:42.061  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:42.061  3797  3849 I jxcore-log: 
,09-13 13:55:42.068  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 44275
09-13 13:55:42.068  3797  3849 I jxcore-log: 
,09-13 13:55:42.084  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:42.084  3797  3849 I jxcore-log: 
,09-13 13:55:42.087  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:42.087  3797  3849 I jxcore-log: 
,09-13 13:55:42.091  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:42.091  3797  3849 I jxcore-log: 
,09-13 13:55:42.128  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:42.128  3797  3849 I jxcore-log: 
,09-13 13:55:42.133  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:42.133  3797  3849 I jxcore-log: 
,09-13 13:55:42.144  3797  3849 I jxcore-log: DEBUG createNativeListener: 
09-13 13:55:42.144  3797  3849 I jxcore-log: 
,09-13 13:55:42.148  3797  3849 I jxcore-log: ok 4 tried to connect to right port
09-13 13:55:42.148  3797  3849 I jxcore-log: 
,09-13 13:55:42.151  3797  3849 I jxcore-log: ok 5 failed due to refused connection
09-13 13:55:42.151  3797  3849 I jxcore-log: 
,09-13 13:55:42.154  3797  3849 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-13 13:55:42.154  3797  3849 I jxcore-log: 
,09-13 13:55:42.164  3797  3849 I jxcore-log: # teardown
09-13 13:55:42.164  3797  3849 I jxcore-log: 
,09-13 13:55:42.166  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:42.166  3797  3849 I jxcore-log: 
,09-13 13:55:44.072  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:44.072  3797  3849 I jxcore-log: 
,09-13 13:55:44.077  3797  3849 I jxcore-log: # setup
09-13 13:55:44.077  3797  3849 I jxcore-log: 
,09-13 13:55:44.078  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:44.078  3797  3849 I jxcore-log: 
,09-13 13:55:46.067  3797  3849 I jxcore-log: # 4. native server connections all up
09-13 13:55:46.067  3797  3849 I jxcore-log: 
,09-13 13:55:47.194  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:47.194  3797  3849 I jxcore-log: 
,09-13 13:55:47.201  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 41905
09-13 13:55:47.201  3797  3849 I jxcore-log: 
,09-13 13:55:47.215  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:47.215  3797  3849 I jxcore-log: 
,09-13 13:55:47.216  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:47.216  3797  3849 I jxcore-log: 
,09-13 13:55:47.218  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:47.218  3797  3849 I jxcore-log: 
,09-13 13:55:47.249  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:47.249  3797  3849 I jxcore-log: 
,09-13 13:55:47.252  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:47.252  3797  3849 I jxcore-log: 
,09-13 13:55:47.256  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:47.256  3797  3849 I jxcore-log: 
,09-13 13:55:47.258  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:47.258  3797  3849 I jxcore-log: 
,09-13 13:55:47.280  3797  3849 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-13 13:55:47.280  3797  3849 I jxcore-log: 
,09-13 13:55:47.280  3797  3849 I jxcore-log: ok 8 Send/recvd #1 should be same
09-13 13:55:47.280  3797  3849 I jxcore-log: 
,09-13 13:55:47.283  3797  3849 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-13 13:55:47.283  3797  3849 I jxcore-log: 
09-13 13:55:47.283  3797  3849 I jxcore-log: ok 10 Send/recvd #2 should be same
09-13 13:55:47.283  3797  3849 I jxcore-log: 
,09-13 13:55:47.286  3797  3849 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-13 13:55:47.286  3797  3849 I jxcore-log: 
,09-13 13:55:47.292  3797  3849 I jxcore-log: # teardown
09-13 13:55:47.292  3797  3849 I jxcore-log: 
,09-13 13:55:48.218  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:48.218  3797  3849 I jxcore-log: 
,09-13 13:55:48.221  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:48.221  3797  3849 I jxcore-log: 
,09-13 13:55:48.223  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:48.223  3797  3849 I jxcore-log: 
,09-13 13:55:48.227  3797  3849 I jxcore-log: # setup
09-13 13:55:48.227  3797  3849 I jxcore-log: 
,09-13 13:55:48.228  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:48.228  3797  3849 I jxcore-log: 
,09-13 13:55:51.078  3797  3849 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-13 13:55:51.078  3797  3849 I jxcore-log: 
,09-13 13:55:53.125  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:53.125  3797  3849 I jxcore-log: 
,09-13 13:55:53.136  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 46868
09-13 13:55:53.136  3797  3849 I jxcore-log: 
,09-13 13:55:53.142  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:53.142  3797  3849 I jxcore-log: 
,09-13 13:55:53.144  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:53.144  3797  3849 I jxcore-log: 
,09-13 13:55:53.145  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:53.145  3797  3849 I jxcore-log: 
,09-13 13:55:53.161  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:53.161  3797  3849 I jxcore-log: 
,09-13 13:55:53.164  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:53.164  3797  3849 I jxcore-log: 
,09-13 13:55:53.178  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:53.178  3797  3849 I jxcore-log: 
,09-13 13:55:53.192  3797  3849 I jxcore-log: ok 12 socket shouldn't close until after stream
09-13 13:55:53.192  3797  3849 I jxcore-log: 
09-13 13:55:53.193  3797  3849 I jxcore-log: ok 13 incoming remains open
09-13 13:55:53.193  3797  3849 I jxcore-log: 
,09-13 13:55:53.197  3797  3849 I jxcore-log: # teardown
09-13 13:55:53.197  3797  3849 I jxcore-log: 
,09-13 13:55:54.046  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:54.046  3797  3849 I jxcore-log: 
,09-13 13:55:54.058  3797  3849 I jxcore-log: # setup
09-13 13:55:54.058  3797  3849 I jxcore-log: 
,09-13 13:55:54.059  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:54.059  3797  3849 I jxcore-log: 
,09-13 13:55:54.459  3797  3849 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-13 13:55:54.459  3797  3849 I jxcore-log: 
,09-13 13:55:54.921  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:54.921  3797  3849 I jxcore-log: 
,09-13 13:55:54.931  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 38086
09-13 13:55:54.931  3797  3849 I jxcore-log: 
,09-13 13:55:54.941  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:54.941  3797  3849 I jxcore-log: 
,09-13 13:55:54.942  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:54.942  3797  3849 I jxcore-log: 
,09-13 13:55:54.944  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:54.944  3797  3849 I jxcore-log: 
,09-13 13:55:54.954  3797  3849 I jxcore-log: ok 14 we should not have gotten an error
09-13 13:55:54.954  3797  3849 I jxcore-log: 
,09-13 13:55:54.962  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:54.962  3797  3849 I jxcore-log: 
,09-13 13:55:54.965  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:54.965  3797  3849 I jxcore-log: 
,09-13 13:55:54.976  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:54.976  3797  3849 I jxcore-log: 
,09-13 13:55:54.978  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:54.978  3797  3849 I jxcore-log: 
,09-13 13:55:54.986  3797  3849 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-13 13:55:54.986  3797  3849 I jxcore-log: 
,09-13 13:55:54.987  3797  3849 I jxcore-log: ok 16 incoming is cleaned up
09-13 13:55:54.987  3797  3849 I jxcore-log: 
,09-13 13:55:54.994  3797  3849 I jxcore-log: # teardown
09-13 13:55:54.994  3797  3849 I jxcore-log: 
,09-13 13:55:55.796  3797  3849 I jxcore-log: # setup
09-13 13:55:55.796  3797  3849 I jxcore-log: 
,09-13 13:55:56.197  3797  3849 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-13 13:55:56.197  3797  3849 I jxcore-log: 
,09-13 13:55:56.333  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:56.333  3797  3849 I jxcore-log: 
,09-13 13:55:56.337  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 41802
09-13 13:55:56.337  3797  3849 I jxcore-log: 
,09-13 13:55:56.343  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:56.343  3797  3849 I jxcore-log: 
,09-13 13:55:56.345  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:56.345  3797  3849 I jxcore-log: 
,09-13 13:55:56.347  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:56.347  3797  3849 I jxcore-log: 
,09-13 13:55:56.363  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:56.363  3797  3849 I jxcore-log: 
,09-13 13:55:56.365  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:56.365  3797  3849 I jxcore-log: 
,09-13 13:55:56.382  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:56.382  3797  3849 I jxcore-log: 
,09-13 13:55:56.391  3797  3849 I jxcore-log: ok 17 stream was closed
09-13 13:55:56.391  3797  3849 I jxcore-log: 
,09-13 13:55:56.391  3797  3849 I jxcore-log: ok 18 incoming should survive
09-13 13:55:56.391  3797  3849 I jxcore-log: 
09-13 13:55:56.392  3797  3849 I jxcore-log: ok 19 mux should have no streams
09-13 13:55:56.392  3797  3849 I jxcore-log: 
,09-13 13:55:56.397  3797  3849 I jxcore-log: # teardown
09-13 13:55:56.397  3797  3849 I jxcore-log: 
,09-13 13:55:56.521  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:56.521  3797  3849 I jxcore-log: 
,09-13 13:55:56.536  3797  3849 I jxcore-log: # setup
09-13 13:55:56.536  3797  3849 I jxcore-log: 
,09-13 13:55:56.537  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:56.537  3797  3849 I jxcore-log: 
,09-13 13:55:56.619  3797  3849 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-13 13:55:56.619  3797  3849 I jxcore-log: 
,09-13 13:55:56.699  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:56.699  3797  3849 I jxcore-log: 
,09-13 13:55:56.707  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 41987
09-13 13:55:56.707  3797  3849 I jxcore-log: 
,09-13 13:55:56.720  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:56.720  3797  3849 I jxcore-log: 
,09-13 13:55:56.722  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:56.722  3797  3849 I jxcore-log: 
,09-13 13:55:56.723  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:56.723  3797  3849 I jxcore-log: 
,09-13 13:55:56.733  3797  3849 I jxcore-log: ok 20 we should not have gotten an error
09-13 13:55:56.733  3797  3849 I jxcore-log: 
,09-13 13:55:56.742  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:56.742  3797  3849 I jxcore-log: 
,09-13 13:55:56.745  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:56.745  3797  3849 I jxcore-log: 
,09-13 13:55:56.756  3797  3849 I jxcore-log: ok 21 Buffers are identical
09-13 13:55:56.756  3797  3849 I jxcore-log: 
,09-13 13:55:56.759  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:56.759  3797  3849 I jxcore-log: 
,09-13 13:55:56.762  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:56.762  3797  3849 I jxcore-log: 
,09-13 13:55:56.765  3797  3849 I jxcore-log: ok 22 native server is nulled out
09-13 13:55:56.765  3797  3849 I jxcore-log: 
09-13 13:55:56.765  3797  3849 I jxcore-log: ok 23 native server should be closed
09-13 13:55:56.765  3797  3849 I jxcore-log: 
,09-13 13:55:56.766  3797  3849 I jxcore-log: ok 24 incoming has been removed
09-13 13:55:56.766  3797  3849 I jxcore-log: 
09-13 13:55:56.766  3797  3849 I jxcore-log: ok 25 Incoming should be done
09-13 13:55:56.766  3797  3849 I jxcore-log: 
09-13 13:55:56.766  3797  3849 I jxcore-log: ok 26 The mux object should be closed
09-13 13:55:56.766  3797  3849 I jxcore-log: 
09-13 13:55:56.767  3797  3849 I jxcore-log: ok 27 The mux stream should be closed
09-13 13:55:56.767  3797  3849 I jxcore-log: 
09-13 13:55:56.768  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:56.768  3797  3849 I jxcore-log: 
,09-13 13:55:56.783  3797  3849 I jxcore-log: # teardown
09-13 13:55:56.783  3797  3849 I jxcore-log: 
,09-13 13:55:56.889  3797  3849 I jxcore-log: # setup
09-13 13:55:56.889  3797  3849 I jxcore-log: 
,09-13 13:55:56.976  3797  3849 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-13 13:55:56.976  3797  3849 I jxcore-log: 
,09-13 13:55:57.078  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:57.078  3797  3849 I jxcore-log: 
,09-13 13:55:57.089  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 39128
09-13 13:55:57.089  3797  3849 I jxcore-log: 
,09-13 13:55:57.115  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.115  3797  3849 I jxcore-log: 
,09-13 13:55:57.116  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.116  3797  3849 I jxcore-log: 
09-13 13:55:57.117  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.117  3797  3849 I jxcore-log: 
,09-13 13:55:57.121  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.121  3797  3849 I jxcore-log: 
,09-13 13:55:57.122  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.122  3797  3849 I jxcore-log: 
09-13 13:55:57.123  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.123  3797  3849 I jxcore-log: 
,09-13 13:55:57.126  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.126  3797  3849 I jxcore-log: 
,09-13 13:55:57.127  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.127  3797  3849 I jxcore-log: 
09-13 13:55:57.128  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.128  3797  3849 I jxcore-log: 
,09-13 13:55:57.131  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.131  3797  3849 I jxcore-log: 
09-13 13:55:57.132  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.132  3797  3849 I jxcore-log: 
,09-13 13:55:57.135  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.135  3797  3849 I jxcore-log: 
,09-13 13:55:57.137  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.137  3797  3849 I jxcore-log: 
09-13 13:55:57.138  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.138  3797  3849 I jxcore-log: 
,09-13 13:55:57.139  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.139  3797  3849 I jxcore-log: 
09-13 13:55:57.141  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.141  3797  3849 I jxcore-log: 
,09-13 13:55:57.141  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.141  3797  3849 I jxcore-log: 
09-13 13:55:57.142  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.142  3797  3849 I jxcore-log: 
,09-13 13:55:57.150  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.150  3797  3849 I jxcore-log: 
,09-13 13:55:57.151  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.151  3797  3849 I jxcore-log: 
09-13 13:55:57.152  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.152  3797  3849 I jxcore-log: 
,09-13 13:55:57.155  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.155  3797  3849 I jxcore-log: 
09-13 13:55:57.155  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.155  3797  3849 I jxcore-log: 
09-13 13:55:57.156  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.156  3797  3849 I jxcore-log: 
,09-13 13:55:57.158  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.158  3797  3849 I jxcore-log: 
09-13 13:55:57.158  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.158  3797  3849 I jxcore-log: 
,09-13 13:55:57.159  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.159  3797  3849 I jxcore-log: 
09-13 13:55:57.160  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:57.160  3797  3849 I jxcore-log: 
09-13 13:55:57.161  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:57.161  3797  3849 I jxcore-log: 
,09-13 13:55:57.162  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:57.162  3797  3849 I jxcore-log: 
,09-13 13:55:57.240  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.240  3797  3849 I jxcore-log: 
,09-13 13:55:57.242  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.242  3797  3849 I jxcore-log: 
,09-13 13:55:57.244  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.244  3797  3849 I jxcore-log: 
,09-13 13:55:57.247  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.247  3797  3849 I jxcore-log: 
,09-13 13:55:57.249  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.249  3797  3849 I jxcore-log: 
,09-13 13:55:57.251  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.251  3797  3849 I jxcore-log: 
,09-13 13:55:57.253  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.253  3797  3849 I jxcore-log: 
09-13 13:55:57.255  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.255  3797  3849 I jxcore-log: 
,09-13 13:55:57.257  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.257  3797  3849 I jxcore-log: 
,09-13 13:55:57.259  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.259  3797  3849 I jxcore-log: 
09-13 13:55:57.260  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.260  3797  3849 I jxcore-log: 
,09-13 13:55:57.262  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.262  3797  3849 I jxcore-log: 
,09-13 13:55:57.263  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.263  3797  3849 I jxcore-log: 
09-13 13:55:57.265  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.265  3797  3849 I jxcore-log: 
,09-13 13:55:57.266  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.266  3797  3849 I jxcore-log: 
09-13 13:55:57.268  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.268  3797  3849 I jxcore-log: 
,09-13 13:55:57.270  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.270  3797  3849 I jxcore-log: 
,09-13 13:55:57.271  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.271  3797  3849 I jxcore-log: 
09-13 13:55:57.272  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.272  3797  3849 I jxcore-log: 
,09-13 13:55:57.274  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.274  3797  3849 I jxcore-log: 
09-13 13:55:57.275  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.275  3797  3849 I jxcore-log: 
,09-13 13:55:57.276  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.276  3797  3849 I jxcore-log: 
09-13 13:55:57.277  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.277  3797  3849 I jxcore-log: 
,09-13 13:55:57.279  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.279  3797  3849 I jxcore-log: 
,09-13 13:55:57.281  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.281  3797  3849 I jxcore-log: 
09-13 13:55:57.282  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.282  3797  3849 I jxcore-log: 
,09-13 13:55:57.283  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.283  3797  3849 I jxcore-log: 
09-13 13:55:57.285  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.285  3797  3849 I jxcore-log: 
,09-13 13:55:57.286  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.286  3797  3849 I jxcore-log: 
09-13 13:55:57.287  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.287  3797  3849 I jxcore-log: 
,09-13 13:55:57.288  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.288  3797  3849 I jxcore-log: 
09-13 13:55:57.290  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.290  3797  3849 I jxcore-log: 
,09-13 13:55:57.295  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.295  3797  3849 I jxcore-log: 
,09-13 13:55:57.296  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.296  3797  3849 I jxcore-log: 
09-13 13:55:57.298  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.298  3797  3849 I jxcore-log: 
,09-13 13:55:57.299  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.299  3797  3849 I jxcore-log: 
,09-13 13:55:57.300  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.300  3797  3849 I jxcore-log: 
,09-13 13:55:57.307  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.307  3797  3849 I jxcore-log: 
,09-13 13:55:57.309  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.309  3797  3849 I jxcore-log: 
09-13 13:55:57.310  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.310  3797  3849 I jxcore-log: 
,09-13 13:55:57.313  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.313  3797  3849 I jxcore-log: 
,09-13 13:55:57.314  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.314  3797  3849 I jxcore-log: 
,09-13 13:55:57.315  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.315  3797  3849 I jxcore-log: 
,09-13 13:55:57.317  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.317  3797  3849 I jxcore-log: 
09-13 13:55:57.318  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.318  3797  3849 I jxcore-log: 
,09-13 13:55:57.319  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.319  3797  3849 I jxcore-log: 
09-13 13:55:57.320  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.320  3797  3849 I jxcore-log: 
,09-13 13:55:57.321  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.321  3797  3849 I jxcore-log: 
,09-13 13:55:57.323  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.323  3797  3849 I jxcore-log: 
,09-13 13:55:57.325  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.325  3797  3849 I jxcore-log: 
09-13 13:55:57.326  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.326  3797  3849 I jxcore-log: 
,09-13 13:55:57.327  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.327  3797  3849 I jxcore-log: 
,09-13 13:55:57.328  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.328  3797  3849 I jxcore-log: 
,09-13 13:55:57.329  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.329  3797  3849 I jxcore-log: 
09-13 13:55:57.330  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.330  3797  3849 I jxcore-log: 
09-13 13:55:57.332  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.332  3797  3849 I jxcore-log: 
,09-13 13:55:57.334  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.334  3797  3849 I jxcore-log: 
09-13 13:55:57.335  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.335  3797  3849 I jxcore-log: 
,09-13 13:55:57.336  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.336  3797  3849 I jxcore-log: 
09-13 13:55:57.337  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.337  3797  3849 I jxcore-log: 
,09-13 13:55:57.339  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.339  3797  3849 I jxcore-log: 
09-13 13:55:57.340  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.340  3797  3849 I jxcore-log: 
,09-13 13:55:57.341  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.341  3797  3849 I jxcore-log: 
,09-13 13:55:57.342  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.342  3797  3849 I jxcore-log: 
09-13 13:55:57.344  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.344  3797  3849 I jxcore-log: 
,09-13 13:55:57.345  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.345  3797  3849 I jxcore-log: 
09-13 13:55:57.347  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.347  3797  3849 I jxcore-log: 
,09-13 13:55:57.348  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.348  3797  3849 I jxcore-log: 
09-13 13:55:57.349  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.349  3797  3849 I jxcore-log: 
,09-13 13:55:57.350  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.350  3797  3849 I jxcore-log: 
09-13 13:55:57.351  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.351  3797  3849 I jxcore-log: 
,09-13 13:55:57.353  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.353  3797  3849 I jxcore-log: 
09-13 13:55:57.355  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.355  3797  3849 I jxcore-log: 
,09-13 13:55:57.356  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.356  3797  3849 I jxcore-log: 
,09-13 13:55:57.357  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.357  3797  3849 I jxcore-log: 
,09-13 13:55:57.359  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.359  3797  3849 I jxcore-log: 
09-13 13:55:57.360  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.360  3797  3849 I jxcore-log: 
,09-13 13:55:57.361  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.361  3797  3849 I jxcore-log: 
,09-13 13:55:57.362  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:57.362  3797  3849 I jxcore-log: 
,09-13 13:55:57.363  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:57.363  3797  3849 I jxcore-log: 
,09-13 13:55:57.448  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.448  3797  3849 I jxcore-log: 
,09-13 13:55:57.450  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.450  3797  3849 I jxcore-log: 
,09-13 13:55:57.451  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.451  3797  3849 I jxcore-log: 
,09-13 13:55:57.453  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.453  3797  3849 I jxcore-log: 
,09-13 13:55:57.454  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.454  3797  3849 I jxcore-log: 
,09-13 13:55:57.456  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.456  3797  3849 I jxcore-log: 
09-13 13:55:57.457  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.457  3797  3849 I jxcore-log: 
,09-13 13:55:57.458  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.458  3797  3849 I jxcore-log: 
,09-13 13:55:57.459  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.459  3797  3849 I jxcore-log: 
,09-13 13:55:57.460  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.460  3797  3849 I jxcore-log: 
09-13 13:55:57.461  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.461  3797  3849 I jxcore-log: 
,09-13 13:55:57.464  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.464  3797  3849 I jxcore-log: 
,09-13 13:55:57.465  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.465  3797  3849 I jxcore-log: 
,09-13 13:55:57.466  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.466  3797  3849 I jxcore-log: 
,09-13 13:55:57.468  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.468  3797  3849 I jxcore-log: 
,09-13 13:55:57.472  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.472  3797  3849 I jxcore-log: 
,09-13 13:55:57.474  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.474  3797  3849 I jxcore-log: 
,09-13 13:55:57.475  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.475  3797  3849 I jxcore-log: 
,09-13 13:55:57.476  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.476  3797  3849 I jxcore-log: 
,09-13 13:55:57.477  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.477  3797  3849 I jxcore-log: 
,09-13 13:55:57.478  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.478  3797  3849 I jxcore-log: 
09-13 13:55:57.479  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.479  3797  3849 I jxcore-log: 
,09-13 13:55:57.480  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.480  3797  3849 I jxcore-log: 
,09-13 13:55:57.481  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.481  3797  3849 I jxcore-log: 
,09-13 13:55:57.483  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.483  3797  3849 I jxcore-log: 
,09-13 13:55:57.484  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.484  3797  3849 I jxcore-log: 
,09-13 13:55:57.485  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.485  3797  3849 I jxcore-log: 
09-13 13:55:57.486  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.486  3797  3849 I jxcore-log: 
,09-13 13:55:57.487  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.487  3797  3849 I jxcore-log: 
,09-13 13:55:57.488  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.488  3797  3849 I jxcore-log: 
,09-13 13:55:57.489  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.489  3797  3849 I jxcore-log: 
,09-13 13:55:57.490  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.490  3797  3849 I jxcore-log: 
,09-13 13:55:57.491  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.491  3797  3849 I jxcore-log: 
09-13 13:55:57.492  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.492  3797  3849 I jxcore-log: 
,09-13 13:55:57.493  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.493  3797  3849 I jxcore-log: 
,09-13 13:55:57.495  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.495  3797  3849 I jxcore-log: 
,09-13 13:55:57.496  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.496  3797  3849 I jxcore-log: 
09-13 13:55:57.497  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.497  3797  3849 I jxcore-log: 
,09-13 13:55:57.501  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.501  3797  3849 I jxcore-log: 
,09-13 13:55:57.502  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.502  3797  3849 I jxcore-log: 
,09-13 13:55:57.503  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.503  3797  3849 I jxcore-log: 
,09-13 13:55:57.505  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.505  3797  3849 I jxcore-log: 
,09-13 13:55:57.506  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.506  3797  3849 I jxcore-log: 
09-13 13:55:57.507  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.507  3797  3849 I jxcore-log: 
,09-13 13:55:57.508  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.508  3797  3849 I jxcore-log: 
,09-13 13:55:57.509  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.509  3797  3849 I jxcore-log: 
,09-13 13:55:57.510  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.510  3797  3849 I jxcore-log: 
,09-13 13:55:57.511  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.511  3797  3849 I jxcore-log: 
09-13 13:55:57.512  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:57.512  3797  3849 I jxcore-log: 
,09-13 13:55:57.513  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:57.513  3797  3849 I jxcore-log: 
,09-13 13:55:57.516  3797  3849 I jxcore-log: ok 28 native server is nulled out
09-13 13:55:57.516  3797  3849 I jxcore-log: 
,09-13 13:55:57.517  3797  3849 I jxcore-log: ok 29 native server should be closed
09-13 13:55:57.517  3797  3849 I jxcore-log: 
09-13 13:55:57.517  3797  3849 I jxcore-log: ok 30 incoming has been removed
09-13 13:55:57.517  3797  3849 I jxcore-log: 
,09-13 13:55:57.518  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.518  3797  3849 I jxcore-log: 
09-13 13:55:57.519  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.519  3797  3849 I jxcore-log: 
,09-13 13:55:57.520  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.520  3797  3849 I jxcore-log: 
09-13 13:55:57.520  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.520  3797  3849 I jxcore-log: 
,09-13 13:55:57.521  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.521  3797  3849 I jxcore-log: 
09-13 13:55:57.521  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.521  3797  3849 I jxcore-log: 
,09-13 13:55:57.521  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.521  3797  3849 I jxcore-log: 
09-13 13:55:57.522  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.522  3797  3849 I jxcore-log: 
09-13 13:55:57.522  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.522  3797  3849 I jxcore-log: 
,09-13 13:55:57.522  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:57.522  3797  3849 I jxcore-log: 
,09-13 13:55:57.631  3797  3849 I jxcore-log: # teardown
09-13 13:55:57.631  3797  3849 I jxcore-log: 
,09-13 13:55:57.835  3797  3849 I jxcore-log: # setup
09-13 13:55:57.835  3797  3849 I jxcore-log: 
,09-13 13:55:58.648  3797  3849 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-13 13:55:58.648  3797  3849 I jxcore-log: 
,09-13 13:55:59.260  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:55:59.260  3797  3849 I jxcore-log: 
,09-13 13:55:59.268  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 44734
09-13 13:55:59.268  3797  3849 I jxcore-log: 
,09-13 13:55:59.279  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:55:59.279  3797  3849 I jxcore-log: 
,09-13 13:55:59.281  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:55:59.281  3797  3849 I jxcore-log: 
,09-13 13:55:59.282  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:55:59.282  3797  3849 I jxcore-log: 
,09-13 13:55:59.289  3797  3849 I jxcore-log: ok 31 we should not have gotten an error
09-13 13:55:59.289  3797  3849 I jxcore-log: 
,09-13 13:55:59.296  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:55:59.296  3797  3849 I jxcore-log: 
,09-13 13:55:59.298  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:55:59.298  3797  3849 I jxcore-log: 
,09-13 13:55:59.305  3797  3849 I jxcore-log: ok 32 Buffers are identical
09-13 13:55:59.305  3797  3849 I jxcore-log: 
,09-13 13:55:59.306  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:55:59.306  3797  3849 I jxcore-log: 
,09-13 13:55:59.308  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:55:59.308  3797  3849 I jxcore-log: 
,09-13 13:55:59.326  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:55:59.326  3797  3849 I jxcore-log: 
,09-13 13:55:59.327  3797  3849 I jxcore-log: ok 33 server should be fine
09-13 13:55:59.327  3797  3849 I jxcore-log: 
09-13 13:55:59.327  3797  3849 I jxcore-log: ok 34 server should be open
09-13 13:55:59.327  3797  3849 I jxcore-log: 
,09-13 13:55:59.328  3797  3849 I jxcore-log: ok 35 incoming has been removed
09-13 13:55:59.328  3797  3849 I jxcore-log: 
09-13 13:55:59.328  3797  3849 I jxcore-log: ok 36 The mux object should be closed
09-13 13:55:59.328  3797  3849 I jxcore-log: 
,09-13 13:55:59.328  3797  3849 I jxcore-log: ok 37 The mux stream should be closed
09-13 13:55:59.328  3797  3849 I jxcore-log: 
,09-13 13:55:59.333  3797  3849 I jxcore-log: # teardown
09-13 13:55:59.333  3797  3849 I jxcore-log: 
,09-13 13:55:59.776  3797  3849 I jxcore-log: # setup
09-13 13:55:59.776  3797  3849 I jxcore-log: 
,09-13 13:56:00.596  3797  3849 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-13 13:56:00.596  3797  3849 I jxcore-log: 
,09-13 13:56:01.207  3797  3849 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:56:01.207  3797  3849 I jxcore-log: 
,09-13 13:56:01.215  3797  3849 I jxcore-log: DEBUG createNativeListener: listening 42876
09-13 13:56:01.215  3797  3849 I jxcore-log: 
,09-13 13:56:01.222  3797  3849 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:56:01.222  3797  3849 I jxcore-log: 
,09-13 13:56:01.223  3797  3849 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:56:01.223  3797  3849 I jxcore-log: 
,09-13 13:56:01.224  3797  3849 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:56:01.224  3797  3849 I jxcore-log: 
,09-13 13:56:01.231  3797  3849 I jxcore-log: ok 38 we should not have gotten an error
09-13 13:56:01.231  3797  3849 I jxcore-log: 
,09-13 13:56:01.237  3797  3849 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:56:01.237  3797  3849 I jxcore-log: 
,09-13 13:56:01.240  3797  3849 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:56:01.240  3797  3849 I jxcore-log: 
,09-13 13:56:01.247  3797  3849 I jxcore-log: ok 39 Buffers are identical
09-13 13:56:01.247  3797  3849 I jxcore-log: 
,09-13 13:56:01.251  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-13 13:56:01.251  3797  3849 I jxcore-log: 
,09-13 13:56:01.252  3797  3849 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:56:01.252  3797  3849 I jxcore-log: 
,09-13 13:56:01.255  3797  3849 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:56:01.255  3797  3849 I jxcore-log: 
,09-13 13:56:01.260  3797  3849 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:56:01.260  3797  3849 I jxcore-log: 
,09-13 13:56:01.261  3797  3849 I jxcore-log: ok 40 server should be fine
09-13 13:56:01.261  3797  3849 I jxcore-log: 
09-13 13:56:01.261  3797  3849 I jxcore-log: ok 41 server should be open
09-13 13:56:01.261  3797  3849 I jxcore-log: 
,09-13 13:56:01.262  3797  3849 I jxcore-log: ok 42 incoming has been removed
09-13 13:56:01.262  3797  3849 I jxcore-log: 
09-13 13:56:01.262  3797  3849 I jxcore-log: ok 43 The mux object should be closed
09-13 13:56:01.262  3797  3849 I jxcore-log: 
09-13 13:56:01.262  3797  3849 I jxcore-log: ok 44 The mux stream should be closed
09-13 13:56:01.262  3797  3849 I jxcore-log: 
,09-13 13:56:01.269  3797  3849 I jxcore-log: # teardown
09-13 13:56:01.269  3797  3849 I jxcore-log: 
,09-13 13:56:01.934  3797  3849 I jxcore-log: # setup
09-13 13:56:01.934  3797  3849 I jxcore-log: 
,09-13 13:56:02.432  3797  3849 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
09-13 13:56:02.432  3797  3849 I jxcore-log: 
,09-13 13:56:03.265  3797  3849 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
09-13 13:56:03.265  3797  3849 I jxcore-log: 
,09-13 13:56:03.266  3797  3849 I jxcore-log: ok 45 Got right error
09-13 13:56:03.266  3797  3849 I jxcore-log: 
,09-13 13:56:03.271  3797  3849 I jxcore-log: # teardown
09-13 13:56:03.271  3797  3849 I jxcore-log: 
,09-13 13:56:04.085  3797  3849 I jxcore-log: # setup
09-13 13:56:04.085  3797  3849 I jxcore-log: 
,09-13 13:56:04.482  3797  3849 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
09-13 13:56:04.482  3797  3849 I jxcore-log: 
,09-13 13:56:05.162  3797  3849 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
09-13 13:56:05.162  3797  3849 I jxcore-log: 
,09-13 13:56:05.163  3797  3849 I jxcore-log: ok 46 Got socket hang up
09-13 13:56:05.163  3797  3849 I jxcore-log: 
,09-13 13:56:05.167  3797  3849 I jxcore-log: # teardown
09-13 13:56:05.167  3797  3849 I jxcore-log: 
,09-13 13:56:05.523  4052  4386 V KeepSync: Connecting to GoogleApiClient
,09-13 13:56:05.524   874  2214 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:56:05.594  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:56:05.599  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:56:05.652  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:56:05.653  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:56:05.653  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:56:05.653  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:56:05.692  1722  4387 V BaseAuthAsyncOperation: access token request failed
,09-13 13:56:05.695  4052  4386 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:56:05.771  1513  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:56:05.771  1513  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:56:05.771  1513  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:56:05.771  1513  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:56:05.797  4052  4386 E KeepSync: IOException
09-13 13:56:05.797  4052  4386 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:56:05.797  4052  4386 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:56:05.797  4052  4386 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:56:05.797  4052  4386 E KeepSync: 	... 10 more
,09-13 13:56:05.797  4052  4386 W KeepSync: Sync result 2
,09-13 13:56:05.809   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 475257, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:56:06.027  3797  3849 I jxcore-log: # setup
09-13 13:56:06.027  3797  3849 I jxcore-log: 
,09-13 13:56:06.254  3797  3849 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
09-13 13:56:06.254  3797  3849 I jxcore-log: 
,09-13 13:56:07.167  3797  3849 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
09-13 13:56:07.167  3797  3849 I jxcore-log: 
,09-13 13:56:07.168  3797  3849 I jxcore-log: ok 47 Got 500 as expected
09-13 13:56:07.168  3797  3849 I jxcore-log: 
,09-13 13:56:07.171  3797  3849 I jxcore-log: # teardown
09-13 13:56:07.171  3797  3849 I jxcore-log: 
,09-13 13:56:07.769  3797  3849 I jxcore-log: # setup
09-13 13:56:07.769  3797  3849 I jxcore-log: 
,09-13 13:56:08.988  3797  3849 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
09-13 13:56:08.988  3797  3849 I jxcore-log: 
,09-13 13:56:12.032  3797  3849 I jxcore-log: ok 48 should be equal
09-13 13:56:12.032  3797  3849 I jxcore-log: 
,09-13 13:56:12.032  3797  3849 I jxcore-log: ok 49 revs are equal
09-13 13:56:12.032  3797  3849 I jxcore-log: 
,09-13 13:56:12.039  3797  3849 I jxcore-log: # teardown
09-13 13:56:12.039  3797  3849 I jxcore-log: 
,09-13 13:57:14.649  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:57:14.651  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:57:14.695  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:57:14.695  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:57:14.695  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:57:14.695  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:57:14.723  3553  4392 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:57:14.723  3553  4392 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at czp.a(PG:9087)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:14.723  3553  4392 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	... 12 more
09-13 13:57:14.723  3553  4392 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at fal.a(PG:38)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:57:14.723  3553  4392 E HttpOperation: 	... 14 more
,09-13 13:57:15.009  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:57:15.009  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:57:15.009  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:57:15.009  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:57:15.032  3553  4395 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:57:15.032  3553  4395 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:15.032  3553  4395 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	... 12 more
09-13 13:57:15.032  3553  4395 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at fal.a(PG:38)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:57:15.032  3553  4395 E HttpOperation: 	... 14 more
,09-13 13:57:15.074  1513  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:57:15.074  1513  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:57:15.074  1513  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:57:15.075  1513  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:57:15.089  3553  4395 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:57:15.089  3553  4395 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at hec.a(PG:42)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at hee.a(PG:102)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at czr.a(PG:65)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at kka.a(PG:108)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:15.089  3553  4395 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	... 15 more
09-13 13:57:15.089  3553  4395 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at fal.a(PG:38)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:57:15.089  3553  4395 E HttpOperation: 	... 17 more
,09-13 13:57:15.089  3553  4395 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:57:15.089  3553  4395 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	... 15 more
09-13 13:57:15.089  3553  4395 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:57:15.089  3553  4395 E ExperimentLoader: 	... 17 more
,09-13 13:57:15.212   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 414728, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:57:47.556  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:57:47.557  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:57:47.586  1513  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:57:47.586  1513  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:57:47.586  1513  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:57:47.586  1513  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:57:47.600  3553  4399 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:57:47.600  3553  4399 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:47.600  3553  4399 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	... 12 more
09-13 13:57:47.600  3553  4399 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at fal.a(PG:38)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:57:47.600  3553  4399 E HttpOperation: 	... 14 more
,09-13 13:57:47.707  1513  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:57:47.707  1513  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:57:47.707  1513  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:57:47.707  1513  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:57:47.736  3553  4399 E HttpOperation: [getmobileexperiments] Unexpected exception
,09-13 13:57:47.736  3553  4399 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at hec.a(PG:42)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at hee.a(PG:102)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at czr.a(PG:65)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at kka.a(PG:108)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:47.736  3553  4399 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	... 15 more
09-13 13:57:47.736  3553  4399 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at fal.a(PG:38)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:57:47.736  3553  4399 E HttpOperation: 	... 17 more
,09-13 13:57:47.736  3553  4399 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:57:47.736  3553  4399 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	... 15 more
09-13 13:57:47.736  3553  4399 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:57:47.736  3553  4399 E ExperimentLoader: 	... 17 more
,09-13 13:57:47.892   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 577224, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 14:02:48.761   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=878677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:03:05.894   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=895810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:03:13.360   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=903277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:03:30.987   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=920904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:03:38.427   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=928343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:03:56.040   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=945957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:04:03.467   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=953383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:04:21.094   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=971010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:04:28.534   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=978450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:04:46.161   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:04:53.787   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1003703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:05:11.414   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1021330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:05:18.854   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1028771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:05:36.481   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:05:43.920   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1053837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:06:01.560   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071476, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:06:08.987   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1078903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:06:26.614   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1096530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:06:34.054   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1103970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:06:51.680   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:06:59.120   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1129037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:07:16.748   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1146664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:07:24.188   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1154104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:07:41.814   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1171731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:07:49.254   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1179170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:08:06.880   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:08:12.800   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1202717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:08:28.620   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 14:08:31.934   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:08:37.867   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1227783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:08:57.014   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1246930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:09:02.947   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1252863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:09:22.107   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1272023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:09:28.054   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1277970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:09:47.201   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1297117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:09:53.147   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1303063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:10:12.267   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1322184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:10:18.200   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1328117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:10:37.320   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1347237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:10:43.253   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1353170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:11:02.401   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1372317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:11:08.347   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1378263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:11:27.468   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:11:33.413   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1403330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:11:52.534   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:11:58.480   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1428397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:12:17.601   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:12:23.547   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1453463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:12:42.667   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1472584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:13:00.028   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1489944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:13:07.774   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1497690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 14:13:25.120   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms)
```
