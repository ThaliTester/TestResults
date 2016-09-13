#### Test 836273372e7ca3d_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-13 09:17:14.724   979   979 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
09-13 09:17:14.725   979   979 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,09-13 09:17:14.754   979   979 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
09-13 09:17:14.754   979   979 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
09-13 09:17:15.406  3787  3787 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 09:17:15.412  3787  3787 D AndroidRuntime: CheckJNI is OFF
09-13 09:17:15.457  3787  3787 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 09:17:15.509  3787  3787 I Radio-JNI: register_android_hardware_Radio DONE
09-13 09:17:15.531  3787  3787 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 09:17:15.536   874  1991 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 09:17:15.563  3787  3787 D AndroidRuntime: Shutting down VM
09-13 09:17:15.569  2025  2404 W SearchService: Abort, client detached.
09-13 09:17:15.585  2025  2349 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a249115
09-13 09:17:15.585  2025  2361 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 09:17:15.585  2025  2025 I HotwordDetector: Closing mic
09-13 09:17:15.590   874  2100 I ActivityManager: Start proc 3796:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 09:17:15.632   378  2363 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 09:17:15.634   378  2363 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 09:17:15.641   378  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 09:17:15.643  2025  2358 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 09:17:15.643  2025  2359 I MicroRecognitionRnrImpl: Detection finished
09-13 09:17:15.663  3796  3796 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 09:17:15.687  3796  3796 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 09:17:15.693  3796  3796 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2007-2010)
09-13 09:17:15.694  3796  3796 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 09:17:15.706  3796  3796 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2758285}
09-13 09:17:15.706  3796  3796 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 09:17:15.706  3796  3796 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 09:17:15.713  3796  3796 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 09:17:15.714  3796  3796 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 09:17:15.727  3796  3796 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 09:17:15.738  3796  3796 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 09:17:15.738  3796  3796 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 09:17:15.738  3796  3796 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 09:17:15.738  3796  3796 I Adreno  : Build Date                       : 10/20/15
09-13 09:17:15.738  3796  3796 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 09:17:15.738  3796  3796 I Adreno  : Local Branch                     : M14
09-13 09:17:15.738  3796  3796 I Adreno  : Remote Branch                    : 
09-13 09:17:15.738  3796  3796 I Adreno  : Remote Branch                    : 
09-13 09:17:15.738  3796  3796 I Adreno  : Reconstruct Branch               : 
09-13 09:17:15.745   979   979 I kickstart: STATUS: Received file 'm9kefs2'
09-13 09:17:15.745   979   979 I kickstart: STATUS: 950272 bytes transferred in 0.990356 seconds
09-13 09:17:15.745   979   979 I kickstart: STATUS: Successfully downloaded files from target 
09-13 09:17:15.745   979   979 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
09-13 09:17:15.749   979   979 I kickstart: STATUS: Sahara protocol completed
09-13 09:17:15.800   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bc6eca:true
,09-13 09:17:15.835  3796  3796 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 09:17:15.847  3796  3796 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 09:17:15.927  3796  3834 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 09:17:15.936  3796  3821 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 09:17:15.976  3796  3834 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 09:17:16.025   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms
,09-13 09:17:16.032  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-13 09:17:16.081  3796  3796 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3796
,09-13 09:17:16.175  3796  3796 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 09:17:16.342  3796  3837 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1697908432
,09-13 09:17:16.354  3796  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 09:17:16.354  3796  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 09:17:16.354  3796  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 09:17:16.354  3796  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 09:17:16.354  3796  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 09:17:16.355  3796  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d22cc0 added. We now have 1 listener(s)
,09-13 09:17:16.363  3796  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-13 09:17:16.364  3796  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:16.365  3796  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:17:16.365  3796  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 09:17:16.368  3796  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33acb9f added. We now have 1 listener(s)
,09-13 09:17:16.369  3796  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 09:17:16.373   874  1311 D WifiService: New client listening to asynchronous messages
,09-13 09:17:16.374  3796  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:17:16.374  3796  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 09:17:16.374  3796  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 09:17:16.374  3796  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 09:17:16.374  3796  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 09:17:16.378  3796  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:16.378  3796  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 09:17:16.383  3796  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:16.384  3796  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:16.384  3796  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 09:17:16.384  3796  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:16.384  3796  3837 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 09:17:16.387  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:16.388  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:16.415   874  1954 I ActivityManager: Killing 3238:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 09:17:16.423  3796  3796 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 09:17:16.463   874  1954 I ActivityManager: Killing 3147:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-13 09:17:17.087   874  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 09:17:17.287  3796  3847 W jxcore-log: Initializing JXcore engine
,09-13 09:17:17.287  3796  3847 W jxcore-log: JXcore engine is ready
,09-13 09:17:17.326  3847  3847 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-13 09:17:17.326  3847  3847 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10717]" dev="sockfs" ino=10717 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 09:17:17.326  3847  3847 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 09:17:17.326  3847  3847 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25239]" dev="sockfs" ino=25239 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 09:17:17.340  3796  3847 W jxcore-log: Starting JXcore engine
,09-13 09:17:17.418  3796  3847 W jxcore-log: Platform android
09-13 09:17:17.418  3796  3847 W jxcore-log: 
,09-13 09:17:17.418  3796  3847 W jxcore-log: Process ARCH arm
09-13 09:17:17.418  3796  3847 W jxcore-log: 
,09-13 09:17:17.620  3796  3847 I jxcore-log: JXcore Cordova bridge is ready!
09-13 09:17:17.620  3796  3847 I jxcore-log: 
,09-13 09:17:17.621  3796  3847 W jxcore-log: JXcore engine is started
,09-13 09:17:17.630  3796  3837 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 09:17:17.635  3796  3796 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 09:17:18.000   874  1886 D NetlinkSocketObserver: NeighborEvent{elapsedMs=104317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-13 09:17:18.352  1523  1523 I ConfigService: onDestroy
09-13 09:17:18.998  3758  3773 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 09:17:24.079  3541  3552 D Finsky  : [273] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-13 09:17:24.089  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:17:24.100  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:17:24.105  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:17:24.152  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 09:17:24.152  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 09:17:24.153  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:17:24.153  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:24.188  3541  3552 D Finsky  : [273] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-13 09:17:27.256   874   887 I ActivityManager: Waited long enough for: ServiceRecord{186c74c u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-13 09:17:27.589  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:17:27.605  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 09:17:27.605  3796  3847 I jxcore-log: 
,09-13 09:17:27.608  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 09:17:27.608  3796  3847 I jxcore-log: 
,09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:27.635  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:27.647  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:27.650  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 09:17:27.650  3796  3847 I jxcore-log: 
,09-13 09:17:27.652  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 09:17:27.652  3796  3847 I jxcore-log: 
,09-13 09:17:27.660  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:17:27.662  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 09:17:27.662  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:27.662  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:27.703  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 09:17:27.704  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:17:27.706  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-13 09:17:28.151  3796  3847 I jxcore-log: Unit Test app is loaded
09-13 09:17:28.151  3796  3847 I jxcore-log: 
,09-13 09:17:28.160  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:17:28.160  3796  3847 I jxcore-log: 
,09-13 09:17:28.165  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 09:17:28.167  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f00dfde added. We now have 2 listener(s)
,09-13 09:17:28.167  3796  3796 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 09:17:28.168  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 09:17:28.168  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:17:28.168  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:17:28.168  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:17:28.168  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4925bf added. We now have 2 listener(s)
09-13 09:17:28.168  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:17:28.169  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:17:28.172  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:28.182  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:28.188  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:28.188  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:28.188  3796  3847 D ExecuteNativeTests: Running unit tests
,09-13 09:17:28.188  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 09:17:28.188  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66f77d5 added. We now have 3 listener(s)
,09-13 09:17:28.194  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:28.194  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:17:28.194  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 09:17:28.194  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:17:28.194  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b71bea added. We now have 3 listener(s)
09-13 09:17:28.194  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:17:28.200  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:17:28.207  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:28.214  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:28.218  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:28.225  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:28.230  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:28.230  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:28.232  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:28.235  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:36.081   874  1886 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:17:36.605   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 09:17:37.091   874  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 09:17:38.325  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 09:17:38.325  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 added. We now have 4 listener(s)
,09-13 09:17:38.326  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 09:17:38.326  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:17:38.326  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:17:38.326  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:17:38.326  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 added. We now have 4 listener(s)
09-13 09:17:38.326  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:17:38.327  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 09:17:38.330  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:38.340  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:38.345  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:38.345  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:38.368  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:38.369  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 09:17:38.370  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:38.370  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:38.370  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 09:17:38.370  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 09:17:38.371  3796  3847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 09:17:38.372  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 09:17:38.372  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 09:17:38.372  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:38.372  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:38.372  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 09:17:38.372  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:38.373  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:38.373  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:38.373  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:17:38.373  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 09:17:38.373  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 removed from the list
09-13 09:17:38.373  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:38.373  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 removed from the list
,09-13 09:17:38.374  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:38.375  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:38.375  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:38.377  3796  3847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 09:17:38.377  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:38.377  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:38.378  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:38.378  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:38.378  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:38.378  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
,09-13 09:17:38.378  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:38.378  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:38.378  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-13 09:17:38.383  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 09:17:38.384  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 09:17:38.385  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:38.385  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:38.385  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:38.385  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:38.385  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:38.385  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:38.385  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:38.385  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:38.385  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:38.386  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 09:17:38.387  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:38.394  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:38.399  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:38.399  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:17:38.400  3796  3847 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 09:17:38.400  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 09:17:38.400  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:38.400  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 09:17:38.400  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 09:17:38.401  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:38.402  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 09:17:38.404  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 09:17:38.404  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 09:17:38.404  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 09:17:38.404  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 09:17:38.404  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:38.404  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 09:17:38.407  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:38.410  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 09:17:38.410  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 09:17:38.411  3796  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:38.413  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:38.413  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:17:38.414  3796  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 09:17:38.417  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 09:17:38.419  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:38.419  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 09:17:38.423  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 09:17:38.424  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:38.424  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-13 09:17:38.425  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 09:17:38.425  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:38.425  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 09:17:38.426  3796  3847 D BluetoothAdapter: STATE_ON,
,09-13 09:17:38.433  2719  2733 D BtGatt.GattService: registerClient() - UUID=3b78f037-2e6f-4358-8a5e-bbee39073b53
,09-13 09:17:38.434  2719  2769 D BtGatt.GattService: onClientRegistered() - UUID=3b78f037-2e6f-4358-8a5e-bbee39073b53, clientIf=5
,09-13 09:17:38.434  3796  3808 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 09:17:38.438  2719  2772 D BtGatt.AdvertiseManager: message : 0
,09-13 09:17:38.442  2719  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 09:17:38.456  2719  2769 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 09:17:38.465  2719  2769 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 09:17:38.466  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 09:17:38.467  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 09:17:38.468  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:38.471  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:38.471  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 09:17:38.471  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 09:17:38.472  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 09:17:38.472  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 09:17:38.472  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 09:17:38.475  3796  3796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
09-13 09:17:38.475  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:38.476  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 09:17:38.478  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 09:17:38.478  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 09:17:38.478  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 09:17:38.478  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 09:17:38.478  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 09:17:38.478  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 09:17:38.478  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 09:17:38.479  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-13 09:17:38.479  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:17:38.479  3796  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 09:17:38.479  3796  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:17:38.479  3796  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 09:17:38.480  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 09:17:38.480  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 09:17:38.480  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:17:38.480  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 09:17:38.480  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:38.481  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 09:17:38.482  3796  3847 D BluetoothAdapter: STATE_ON,
09-13 09:17:38.483  3796  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 09:17:38.483  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 09:17:38.483  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 09:17:38.485  2719  2772 D BtGatt.AdvertiseManager: message : 1
09-13 09:17:38.485  2719  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 09:17:38.494  2719  2769 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 09:17:38.494  2719  2769 D BtGatt.GattService: Client app is not null!
09-13 09:17:38.495  2719  2902 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 09:17:38.496  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 09:17:38.496  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 09:17:38.496  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 09:17:38.496  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 09:17:38.496  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 09:17:38.497  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:38.498  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:17:38.498  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-13 09:17:38.499  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:17:38.501  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 09:17:38.501  3796  3796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 09:17:38.501  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 09:17:38.502  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 09:17:38.502  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:17:38.502  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:38.506  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 09:17:38.506  3796  3847 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-13 09:17:38.506  3796  3847 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-13 09:17:38.507  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-13 09:17:38.507  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 09:17:38.507  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 09:17:38.507  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 09:17:38.507  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:38.510  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:17:38.510  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 09:17:38.510  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 09:17:38.511  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:17:38.511  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 09:17:38.511  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 09:17:38.511  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:38.512  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:17:38.514  3796  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:38.517  3796  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 09:17:38.520  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 09:17:38.520  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 09:17:38.526  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 09:17:38.527  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:38.527  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 09:17:38.531  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 09:17:38.532  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 09:17:38.532  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,09-13 09:17:38.532  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:38.532  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 09:17:38.532  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 09:17:38.533  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:38.538  2719  2923 D BtGatt.GattService: registerClient() - UUID=64beb633-f6e6-4f5e-bf9e-b1659d1fe4ab
,09-13 09:17:38.539  2719  2769 D BtGatt.GattService: onClientRegistered() - UUID=64beb633-f6e6-4f5e-bf9e-b1659d1fe4ab, clientIf=5
,09-13 09:17:38.539  3796  3807 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 09:17:38.541  2719  2772 D BtGatt.AdvertiseManager: message : 0
,09-13 09:17:38.546  2719  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 09:17:38.560  2719  2769 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 09:17:38.572  2719  2769 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 09:17:38.574  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 09:17:38.574  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,09-13 09:17:38.577  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:38.580  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 09:17:38.581  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:38.582  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 09:17:38.582  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 09:17:38.582  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 09:17:38.583  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 09:17:38.583  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 09:17:38.591  3796  3796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 09:17:38.592  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:39.089  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:39.089  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 09:17:39.091  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:17:39.091  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 09:17:39.091  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-13 09:17:39.092  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:17:39.092  3796  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 09:17:39.093  3796  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 09:17:39.093  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:39.093  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.093  3796  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 09:17:39.093  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 09:17:39.094  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:17:39.094  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 09:17:39.095  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:39.095  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:17:39.095  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 09:17:39.095  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 09:17:39.099  3796  3847 D BluetoothAdapter: STATE_ON
09-13 09:17:39.099  3796  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 09:17:39.100  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:17:39.100  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 09:17:39.103  2719  2772 D BtGatt.AdvertiseManager: message : 1
09-13 09:17:39.104  2719  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 09:17:39.126  2719  2769 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 09:17:39.127  2719  2769 D BtGatt.GattService: Client app is not null!
,09-13 09:17:39.131  2719  2733 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 09:17:39.132  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 09:17:39.132  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 09:17:39.132  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 09:17:39.133  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 09:17:39.133  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 09:17:39.137  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:39.138  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:17:39.138  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:17:39.139  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 09:17:39.142  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:17:39.142  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:39.142  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:17:39.143  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.143  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.144  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.146  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 09:17:39.152  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:39.166  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:39.173  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:39.173  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:17:39.174  3796  3847 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 09:17:39.174  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 09:17:39.175  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:39.175  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 09:17:39.175  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 09:17:39.176  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:39.178  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:17:39.179  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 09:17:39.179  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 09:17:39.179  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 09:17:39.180  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 09:17:39.180  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:39.180  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:17:39.183  3796  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:39.184  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:39.194  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 09:17:39.195  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:39.195  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:17:39.196  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 09:17:39.197  3796  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 09:17:39.208  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 09:17:39.210  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:39.210  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 09:17:39.215  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 09:17:39.215  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 09:17:39.215  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-13 09:17:39.216  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:39.216  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:39.216  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 09:17:39.218  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:39.225  2719  2922 D BtGatt.GattService: registerClient() - UUID=65910e80-e124-4194-88b6-92ef7e221f51
09-13 09:17:39.226  2719  2769 D BtGatt.GattService: onClientRegistered() - UUID=65910e80-e124-4194-88b6-92ef7e221f51, clientIf=5
,09-13 09:17:39.227  3796  3807 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 09:17:39.230  2719  2772 D BtGatt.AdvertiseManager: message : 0
,09-13 09:17:39.235  2719  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 09:17:39.261  2719  2769 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 09:17:39.272  2719  2769 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 09:17:39.273  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 09:17:39.273  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 09:17:39.275  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:39.279  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 09:17:39.279  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 09:17:39.280  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 09:17:39.280  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 09:17:39.281  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 09:17:39.281  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 09:17:39.281  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 09:17:39.290  3796  3796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:39.291  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:39.641   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 09:17:39.782  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 09:17:39.782  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 09:17:39.783  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 09:17:39.783  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 09:17:39.784  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 09:17:39.784  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:17:39.785  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 09:17:39.787  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 09:17:39.787  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:17:39.787  3796  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 09:17:39.788  3796  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:17:39.789  3796  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 09:17:39.789  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 09:17:39.789  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:17:39.790  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:17:39.790  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 09:17:39.790  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:39.790  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 09:17:39.793  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:39.793  3796  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 09:17:39.794  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:17:39.794  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 09:17:39.796  2719  2772 D BtGatt.AdvertiseManager: message : 1
09-13 09:17:39.798  2719  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 09:17:39.818  2719  2769 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 09:17:39.819  2719  2769 D BtGatt.GattService: Client app is not null!
09-13 09:17:39.821  2719  2730 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 09:17:39.823  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 09:17:39.823  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 09:17:39.823  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 09:17:39.824  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 09:17:39.824  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 09:17:39.829  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:39.829  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:17:39.830  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:17:39.831  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 09:17:39.835  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 09:17:39.835  3796  3796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 09:17:39.835  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 09:17:39.835  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:39.836  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:39.836  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 09:17:39.837  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:17:39.842  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.842  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.842  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:17:39.842  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.843  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:39.843  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.843  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.843  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:39.845  3796  3847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 09:17:39.847  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.847  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.848  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.848  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.848  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:39.848  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.849  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.849  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.849  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.851  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 09:17:39.851  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.851  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.852  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.852  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:39.852  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.852  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.852  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:17:39.853  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.853  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.854  3796  3847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 09:17:39.855  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.855  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.855  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:39.855  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.855  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.856  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.856  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.856  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.856  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:39.857  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 09:17:39.858  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.858  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.858  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.858  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:39.859  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.859  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.859  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.859  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.859  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:39.861  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 09:17:39.861  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:39.861  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:39.861  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:39.862  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 09:17:39.862  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:39.862  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:39.862  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:39.863  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 09:17:39.864  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 09:17:39.864  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:39.864  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:17:39.865  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.865  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.865  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.865  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.866  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:39.866  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.866  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.866  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.867  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:39.870  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 09:17:39.870  3796  3847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 09:17:39.871  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 09:17:39.874  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 09:17:39.875  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 09:17:39.875  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 09:17:39.876  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 09:17:39.877  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 09:17:39.877  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-13 09:17:39.878  3796  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 09:17:39.878  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 09:17:39.879  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 09:17:39.879  3796  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 09:17:39.879  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 09:17:39.879  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 09:17:39.879  3796  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 09:17:39.879  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 09:17:39.888  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-13 09:17:39.889  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-13 09:17:39.889  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-13 09:17:39.890  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 09:17:39.890  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 09:17:39.890  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-13 09:17:39.891  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 09:17:39.891  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 09:17:39.892  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:39.892  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.892  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.892  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 09:17:39.892  3796  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426),
09-13 09:17:39.893  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.893  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.893  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
,09-13 09:17:39.893  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.893  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.893  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.894  3796  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
09-13 09:17:39.894  3796  3847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 09:17:39.895  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:39.895  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.895  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.895  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.895  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.895  3796  3870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:39.895  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.895  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:17:39.895  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.895  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.896  3796  3847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 09:17:39.896  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:39.896  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.896  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.897  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.897  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.897  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
,09-13 09:17:39.897  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.897  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.897  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.898  3796  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-13 09:17:39.898  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 09:17:39.898  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 09:17:39.898  3796  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-13 09:17:39.898  3796  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 09:17:39.898  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 09:17:39.898  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 09:17:39.898  3796  3847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-13 09:17:39.898  3796  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 09:17:39.898  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 09:17:39.899  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 09:17:39.899  3796  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 09:17:39.899  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:39.899  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:39.899  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:39.899  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:39.899  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:39.899  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:39.899  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:39.899  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:39.900  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:39.901  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 09:17:39.903  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:39.909  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:39.911  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:39.911  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:39.911  3796  3847 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 09:17:39.911  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-13 09:17:39.913  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:39.913  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 09:17:39.913  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 09:17:39.913  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:39.914  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:39.914  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:17:39.915  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-13 09:17:39.915  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 09:17:39.915  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 09:17:39.915  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 09:17:39.916  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:39.916  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 09:17:39.916  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:39.916  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:17:39.917  3796  3872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
09-13 09:17:39.919  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 09:17:39.919  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 09:17:39.919  3796  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 09:17:39.922  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 09:17:39.922  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:39.922  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 09:17:39.924  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 09:17:39.924  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 09:17:39.924  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-13 09:17:39.924  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 09:17:39.925  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:39.925  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 09:17:39.925  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:39.927  2719  2922 D BtGatt.GattService: registerClient() - UUID=d69e1396-0e9a-4d2c-9ef3-1bad2a59691c
,09-13 09:17:39.928  2719  2769 D BtGatt.GattService: onClientRegistered() - UUID=d69e1396-0e9a-4d2c-9ef3-1bad2a59691c, clientIf=5
09-13 09:17:39.928  3796  3807 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 09:17:39.929  2719  2772 D BtGatt.AdvertiseManager: message : 0
,09-13 09:17:39.931  2719  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 09:17:39.941  2719  2769 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 09:17:39.947  2719  2769 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 09:17:39.947  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 09:17:39.947  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 09:17:39.949  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:39.950  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 09:17:39.950  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 09:17:39.951  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 09:17:39.951  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 09:17:39.951  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 09:17:39.951  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 09:17:39.951  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 09:17:39.955  3796  3796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:39.956  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:40.455  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:40.456  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 09:17:40.456  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:17:40.456  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 09:17:40.457  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 09:17:40.457  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 09:17:40.458  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:17:40.458  3796  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 09:17:40.458  3796  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:17:40.459  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:17:40.459  3796  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 09:17:40.459  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 09:17:40.460  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:40.460  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:40.460  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:17:40.461  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 09:17:40.461  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:40.462  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 09:17:40.467  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:40.468  3796  3847 D BluetoothLeScanner: could not find callback wrapper
,09-13 09:17:40.468  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:17:40.469  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 09:17:40.472  2719  2772 D BtGatt.AdvertiseManager: message : 1
,09-13 09:17:40.473  2719  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 09:17:40.484  2719  2769 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 09:17:40.485  2719  2769 D BtGatt.GattService: Client app is not null!
09-13 09:17:40.487  2719  2730 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 09:17:40.488  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 09:17:40.488  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 09:17:40.488  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 09:17:40.488  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 09:17:40.488  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 09:17:40.492  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:40.493  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 09:17:40.494  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 09:17:40.496  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 09:17:40.500  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:17:40.500  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:40.501  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:17:40.501  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
,09-13 09:17:40.502  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:40.502  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:40.506  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:40.506  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.507  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:40.507  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:40.507  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:40.508  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:40.508  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:40.508  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.509  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:40.513  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 09:17:40.513  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:40.515  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 09:17:40.516  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 09:17:40.517  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 09:17:40.517  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:17:40.517  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 09:17:40.518  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 09:17:40.519  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:40.519  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 09:17:40.520  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:17:40.520  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 09:17:40.520  3796  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:40.520  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:40.520  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 09:17:40.521  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
09-13 09:17:40.521  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:17:40.521  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:40.521  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:17:40.522  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 09:17:40.522  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:40.522  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:40.522  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:40.525  3796  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 09:17:40.525  3796  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:17:40.525  3796  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 09:17:40.525  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:17:40.526  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:17:40.526  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:40.526  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:40.526  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:40.526  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 09:17:40.526  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.527  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:17:40.527  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:40.530  3796  3847 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 09:17:40.530  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 09:17:40.531  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 09:17:40.531  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:40.531  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 09:17:40.532  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:17:40.532  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:40.532  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.532  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:40.533  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:40.533  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:40.534  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:40.534  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:40.534  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.534  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:40.540  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:40.540  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.541  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:40.541  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:40.541  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:40.541  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:40.541  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:40.541  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:40.541  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:40.543  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:17:40.543  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:40.543  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:40.543  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f304a8 not in the list
,09-13 09:17:40.543  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:40.543  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d45bc1 not in the list
09-13 09:17:40.543  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:17:40.543  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:40.543  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:40.544  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 09:17:40.545  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 09:17:40.545  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 09:17:40.545  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 09:17:40.545  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-13 09:17:40.545  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 09:17:40.548  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 09:17:40.548  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 09:17:40.549  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 09:17:40.549  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 09:17:40.549  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 09:17:40.549  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 09:17:40.549  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 09:17:40.549  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 09:17:40.550  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-13 09:17:40.550  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 09:17:40.551  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 09:17:40.551  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-13 09:17:40.551  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 09:17:40.551  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 09:17:40.552  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 09:17:40.552  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1471e16 added. We now have 4 listener(s)
,09-13 09:17:40.554  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:40.554  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:17:40.554  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 09:17:40.554  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:17:40.555  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@176b397 added. We now have 4 listener(s)
09-13 09:17:40.555  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 09:17:40.555  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 09:17:40.558  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:40.564  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:40.566  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:40.566  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:40.568  3796  3847 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 09:17:40.568   874  2100 D WifiService: setWifiEnabled: true pid=3796, uid=10000
,09-13 09:17:40.568   874  2100 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:17:40.571  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:40.574  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:40.578   874  2100 D WifiService: setWifiEnabled: false pid=3796, uid=10000
,09-13 09:17:40.578   874  2100 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:17:40.596  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 09:17:40.599   874  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 09:17:40.600   874  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 09:17:40.600   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 09:17:40.600   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:40.613   874  1887 D DhcpClient: Clearing IP address
,09-13 09:17:40.614   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 09:17:40.618   374   872 D CommandListener: Setting iface cfg
,09-13 09:17:40.625  1523  2494 V NativeCrypto: Read error: ssl=0x9afc7000: I/O error during system call, Connection timed out
,09-13 09:17:40.628   874  1888 D DhcpClient: Receive thread stopped
,09-13 09:17:40.629  1523  2494 V NativeCrypto: SSL shutdown failed: ssl=0x9afc7000: I/O error during system call, Broken pipe
,09-13 09:17:40.631   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 09:17:40.631   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-13 09:17:40.637   402   402 E Parcel  : Reading a NULL string not supported here.
09-13 09:17:40.639   874  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
09-13 09:17:40.641   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 09:17:40.645   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 09:17:40.678   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:40.731   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:40.731   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 09:17:40.732   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 09:17:40.732   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:17:40.739   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 09:17:40.745   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:40.757  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:40.757  3428  3428 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fb8aea7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) },
09-13 09:17:40.761  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:40.759  2076  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 09:17:40.762  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 09:17:40.763   874  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:40.765  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:40.768  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:40.768  1744  1744 D SystemUpdateService: onCreate
,09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:40.772  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:40.773  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 09:17:40.774  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:40.779  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:40.781  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:40.784  1744  3884 I SystemUpdateService: active receiver: enabled
,09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:40.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:40.787  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:40.788  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:40.790  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:40.791  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:40.792  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 09:17:40.795  1744  2462 I iu.UploadsManager: num queued entries: 0
,09-13 09:17:40.796  1744  3884 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-13 09:17:40.797  1744  2462 I iu.UploadsManager: num updated entries: 0,
09-13 09:17:40.797  1744  2462 I iu.SyncManager: NEXT; no task
,09-13 09:17:40.799  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 09:17:40.801  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 09:17:40.800  1744  3884 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 09:17:40.804  1744  3884 I SystemUpdateService: now status is 0 (complete)
09-13 09:17:40.804  1744  3884 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 09:17:40.804  1744  3884 I SystemUpdateService: file has been verified
09-13 09:17:40.804  1744  3884 I SystemUpdateService: OTA package size = 12249756
,09-13 09:17:40.807   374   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 09:17:40.808   874  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 09:17:40.810  1744  3884 I SystemUpdateService: showing system update notification
,09-13 09:17:40.813   874   884 I ActivityManager: Start proc 3888:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 09:17:40.823  1744  1744 D SystemUpdateService: onDestroy
,09-13 09:17:40.838  3888  3888 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 09:17:40.841  3888  3888 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:17:40.845  3888  3888 D SprintDMHelper: simOperator: 
,09-13 09:17:40.845  3888  3888 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 09:17:40.857   874   885 I ActivityManager: Start proc 3900:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 09:17:40.858   874   885 I ActivityManager: Killing 2989:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 09:17:41.008   874  1954 I ActivityManager: Start proc 3915:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 09:17:41.011  3089  3914 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 09:17:41.022   874  1955 I ActivityManager: Killing 3428:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 09:17:41.028  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 09:17:41.083  3796  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:41.089   874  1972 D WifiService: setWifiEnabled: true pid=3796, uid=10000
,09-13 09:17:41.089   874  1972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:17:41.100   874  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.123  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:41.126  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:41.133   874  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-13 09:17:41.133  3915  3915 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 09:17:41.134   874  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 09:17:41.134   874  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.135  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:41.135   874  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 09:17:41.135   874  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 09:17:41.135   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 09:17:41.135   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-13 09:17:41.138  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.141  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:41.143  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.147  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:41.148   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-13 09:17:41.149  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:41.149   874  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.75 rxSuccessRate=23.75 delta 1000 -> 994
09-13 09:17:41.149   374   872 D CommandListener: Setting iface cfg
09-13 09:17:41.150   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-13 09:17:41.150   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 09:17:41.151   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 09:17:41.151   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 09:17:41.157   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 09:17:41.157   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:41.170   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 09:17:41.205  3915  3915 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 09:17:41.205  3915  3915 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 09:17:41.205  3915  3915 I GAv4    :   adb logcat -s GAv4
,09-13 09:17:41.226  3915  3915 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 09:17:41.228   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 09:17:41.231  3915  3915 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 09:17:41.256  3915  3934 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 09:17:41.368  3915  3915 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 09:17:41.402  3915  3915 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 09:17:41.423  3915  3915 I LibraryLoader: Time to load native libraries: 16 ms (timestamps 7724-7740)
,09-13 09:17:41.423  3915  3915 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 09:17:41.433  3915  3915 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ef1769}
,09-13 09:17:41.433  3915  3915 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 09:17:41.433  3915  3915 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 09:17:41.443  3915  3915 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 09:17:41.445  3915  3915 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 09:17:41.463  3915  3915 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 09:17:41.476  3915  3915 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 09:17:41.476  3915  3915 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 09:17:41.477  3915  3915 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 09:17:41.477  3915  3915 I Adreno  : Build Date                       : 10/20/15
09-13 09:17:41.477  3915  3915 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 09:17:41.477  3915  3915 I Adreno  : Local Branch                     : M14
09-13 09:17:41.477  3915  3915 I Adreno  : Remote Branch                    : 
09-13 09:17:41.477  3915  3915 I Adreno  : Remote Branch                    : 
09-13 09:17:41.477  3915  3915 I Adreno  : Reconstruct Branch               : 
,09-13 09:17:41.543  3915  3915 I NSApplication: Starting up...
,09-13 09:17:41.556  3915  3963 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 09:17:41.592  3796  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:41.593   874  1992 I ActivityManager: Start proc 3968:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 09:17:41.595   874  1992 I ActivityManager: Killing 3497:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 09:17:41.629  2719  2765 D BluetoothAdapterState: Current state: ON, message: 23
09-13 09:17:41.630  2719  2765 D BluetoothAdapterProperties: Setting state to 13
,09-13 09:17:41.630  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 09:17:41.631  2719  2765 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 09:17:41.633  2719  2765 I BluetoothAdapterState: Entering PendingCommandState
,09-13 09:17:41.639  2719  2769 D BluetoothAdapterProperties: Scan Mode:20
,09-13 09:17:41.640  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 09:17:41.640  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.641  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:41.641  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:41.641  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:41.643  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.643  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:41.644  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:41.644  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:41.644  2719  2719 D HeadsetService: Received stop request...Stopping profile...
,09-13 09:17:41.646  1353  2064 D BluetoothHeadset: Proxy object disconnected
09-13 09:17:41.646  1353  1353 D HeadsetProfile: Bluetooth service disconnected
09-13 09:17:41.646  2719  2719 V BluetoothAdapterState: isTurningOff()=true
,09-13 09:17:41.646  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:41.647  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false,
09-13 09:17:41.647  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 09:17:41.648  1932  2112 D BluetoothHeadset: Proxy object disconnected
,09-13 09:17:41.653   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 09:17:41.653   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 09:17:41.648  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.654  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:41.654   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 09:17:41.656  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:41.656  2719  2719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 09:17:41.658  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:41.658  2719  2719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 09:17:41.658  2719  2769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 09:17:41.658  2719  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:41.658  2719  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:41.658  2719  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:41.659  2719  2769 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 09:17:41.660  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:41.660  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:41.660  2719  2719 D A2dpService: Received stop request...Stopping profile...
09-13 09:17:41.661  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:41.661  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:41.661  2719  2916 D A2dpStateMachine: Exit Disconnected: -1
09-13 09:17:41.663  1353  1353 D BluetoothA2dp: Proxy object disconnected
09-13 09:17:41.663   874   874 D BluetoothA2dp: Proxy object disconnected
,09-13 09:17:41.664  2719  2719 D HidService: Received stop request...Stopping profile...
09-13 09:17:41.664  2719  2719 D HidService: Stopping Bluetooth HidService
09-13 09:17:41.665  1353  1353 D BluetoothInputDevice: Proxy object disconnected
09-13 09:17:41.665  1353  1353 D HidProfile: Bluetooth service disconnected
09-13 09:17:41.665  2719  2719 D HealthService: Received stop request...Stopping profile...
,09-13 09:17:41.672  2719  2719 D PanService: Received stop request...Stopping profile...
,09-13 09:17:41.673  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 09:17:41.673  1353  1353 D PanProfile: Bluetooth service disconnected
,09-13 09:17:41.673  2719  2719 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 09:17:41.673  2719  2719 D BluetoothMapService: stop()
,09-13 09:17:41.674  2719  2719 D BluetoothMapAppObserver: deinitObservers()
,09-13 09:17:41.674  2719  2719 D BluetoothMapAppObserver: removeReceiver()
,09-13 09:17:41.675  1353  1353 D BluetoothMap: Proxy object disconnected
,09-13 09:17:41.675  1353  1353 D MapProfile: Bluetooth service disconnected
,09-13 09:17:41.675  2719  2719 V BluetoothAdapterState: isTurningOff()=true
,09-13 09:17:41.675  2719  2719 V BluetoothAdapterState: isTurningOn()=false
,09-13 09:17:41.675  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 09:17:41.675  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 09:17:41.676  2719  2769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-13 09:17:41.676  2719  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:41.676  2719  2719 V BluetoothAdapterState: isTurningOff()=true
,09-13 09:17:41.676  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:41.676  2719  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 09:17:41.676  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false,
09-13 09:17:41.676  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false,
,09-13 09:17:41.676  2719  2895 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 09:17:41.676  2719  2895 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:17:41.676  2719  2895 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:17:41.676  2719  2895 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:17:41.676  2719  2719 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 09:17:41.676  2719  2719 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 09:17:41.676  2719  2769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 09:17:41.676  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:41.676  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:41.677  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:41.677  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:41.677  2719  2719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 09:17:41.677  2719  2769 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 09:17:41.677  2719  2719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 09:17:41.677  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:41.677  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:41.677  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:41.677  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:41.677  2719  2719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 09:17:41.678  2719  2719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 09:17:41.678  2719  2719 D BluetoothMapService: MAP Service closeService in
09-13 09:17:41.678  2719  2719 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 09:17:41.678  2719  2719 D ObexServerSockets0: shutdown(block = true)
09-13 09:17:41.679  2719  2924 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 09:17:41.680  2719  2719 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 09:17:41.680  2719  2925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 09:17:41.680  2719  2899 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 09:17:41.680  2719  2719 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 09:17:41.681  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:41.681  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:41.681  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:41.681  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:41.681  2719  2719 D BluetoothMapService: cleanup()
09-13 09:17:41.681  2719  2719 D BluetoothMapService: MAP Service closeService in
09-13 09:17:41.682  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 09:17:41.682  2719  2765 D BluetoothAdapterProperties: Setting state to 15
09-13 09:17:41.682  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 09:17:41.682  2719  2719 I BtOppRfcommListener: stopping Accept Thread
09-13 09:17:41.683  2719  3460 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:17:41.683  2719  3460 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 09:17:41.683  1353  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 09:17:41.683  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.684   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 09:17:41.684  2719  2765 I BluetoothAdapterState: Entering BleOnState
09-13 09:17:41.684  1353  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 09:17:41.685  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateCo,nnectivityInfo: No relevant state changes
09-13 09:17:41.686  1353  1377 D BluetoothPan: onBluetoothStateChange on: false
09-13 09:17:41.687  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.688  1932  1948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:41.688  1353  2064 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:41.688  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.688   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:41.688   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:41.688  1353  3982 D BluetoothMap: onBluetoothStateChange: up=false
09-13 09:17:41.689  1353  1367 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 09:17:41.690   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:41.690  2719  2765 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 09:17:41.690  2719  2765 D BluetoothAdapterProperties: Setting state to 16
09-13 09:17:41.690  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 09:17:41.692  2719  2765 D BluetoothAdapterProperties: onBleDisable
09-13 09:17:41.692  2719  2765 I BluetoothAdapterState: Entering PendingCommandState
09-13 09:17:41.693  2719  2766 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 09:17:41.693  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.693  2719  2769 D BluetoothAdapterProperties: Scan Mode:20
09-13 09:17:41.693  2719  2895 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 09:17:41.693  2719  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:41.694  3796  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
09-13 09:17:41.695  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.695  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.699  3968  3968 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
09-13 09:17:41.700  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.701  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.702  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.703  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:41.703  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:41.898  2719  2769 I bt_hci  : shut_down
,09-13 09:17:41.900  2719  2775 D bt_hwcfg: hw_epilog_process
,09-13 09:17:41.901  2719  2775 I bt_vendor: low_power_mode_cb
,09-13 09:17:41.902   874  1942 I ActivityManager: Killing 3047:com.google.android.keep/u0a79 (adj 15): empty #17
,09-13 09:17:41.920  2719  2775 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-13 09:17:41.920  2719  2775 I bt_vendor: epilog_cb
,09-13 09:17:41.920  2719  2775 I bt_hci  : epilog_finished_callback
,09-13 09:17:41.965  2719  2769 I bt_hci_h4: hal_close,
,09-13 09:17:41.966  2719  2769 I bt_userial_vendor: device fd = 51 close
,09-13 09:17:41.988   874  1384 I ActivityManager: Start proc 3985:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 09:17:42.075  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 09:17:42.080  3985  3985 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 09:17:42.085  2719  2766 D bt_stack_manager: event_shut_down_stack finished.
,09-13 09:17:42.086  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 09:17:42.091  2719  2765 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 09:17:42.091  2719  2719 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 09:17:42.092  2719  2719 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 09:17:42.092  2719  2719 D BtGatt.GattService: stop()
09-13 09:17:42.093  2719  2719 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 09:17:42.097  2719  2719 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:42.097  2719  2719 V BluetoothAdapterState: isTurningOn()=false
,09-13 09:17:42.097  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:42.097  2719  2719 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 09:17:42.098  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 09:17:42.099  2719  2765 D BluetoothAdapterProperties: Setting state to 10
09-13 09:17:42.099  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 09:17:42.100  2719  2765 I BluetoothAdapterState: Entering OffState
09-13 09:17:42.101   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-13 09:17:42.121  2719  2719 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 09:17:42.121  2719  2719 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 09:17:42.121  2719  2766 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 09:17:42.123  2719  2766 D bt_stack_manager: event_clean_up_stack finished.
09-13 09:17:42.123  2719  2719 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 09:17:42.125  2719  2719 I art     : System.exit called, status: 0
09-13 09:17:42.126  2719  2719 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 09:17:42.129  3796  3973 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:42.142   280   280 E lowmemorykiller: Error writing /proc/2719/oom_score_adj; errno=22
,09-13 09:17:42.149  3985  3985 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 09:17:42.172   874  1963 I ActivityManager: Start proc 4010:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-13 09:17:42.173   874  1963 I ActivityManager: Killing 1680:android.process.acore/u0a5 (adj 15): empty #17
,09-13 09:17:42.213   874   885 I ActivityManager: Process com.android.bluetooth (pid 2719) has died
,09-13 09:17:42.216   874   885 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
09-13 09:17:42.217   874   885 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 09:17:42.244  4010  4010 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-13 09:17:42.388   874  1382 I ActivityManager: Start proc 4030:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-13 09:17:42.457  4030  4030 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 09:17:42.467  4030  4030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 09:17:42.476   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@799a7aa:true
,09-13 09:17:42.509   874  1972 I ActivityManager: Start proc 4045:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-13 09:17:42.520  4030  4030 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 09:17:42.522  4030  4030 D BluetoothMap: Create BluetoothMap proxy object
,09-13 09:17:42.527  4030  4030 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 09:17:42.533  4030  4030 D DockEventReceiver: finishStartingService: stopping service
,09-13 09:17:42.537   874  2100 I ActivityManager: Killing 3662:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 09:17:42.617  4045  4045 D AdapterServiceConfig: Adding HeadsetService
09-13 09:17:42.617  4045  4045 D AdapterServiceConfig: Adding A2dpService
,09-13 09:17:42.618  4045  4045 D AdapterServiceConfig: Adding HidService
09-13 09:17:42.618  4045  4045 D AdapterServiceConfig: Adding HealthService
09-13 09:17:42.618  4045  4045 D AdapterServiceConfig: Adding PanService
,09-13 09:17:42.618  4045  4045 D AdapterServiceConfig: Adding GattService
09-13 09:17:42.618  4045  4045 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 09:17:42.622  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:17:42.635  4045  4045 D BluetoothAdapterState: make() - Creating AdapterState
09-13 09:17:42.635   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d35a81:true
,09-13 09:17:42.637  4045  4045 I bt_bluedroid: init
,09-13 09:17:42.637  4045  4060 I BluetoothAdapterState: Entering OffState
,09-13 09:17:42.640  4045  4061 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 09:17:42.640  4045  4061 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 09:17:42.640  4045  4061 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 09:17:42.640  4045  4061 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 09:17:42.642  4045  4045 I bt_bluedroid: get_profile_interface socket
,09-13 09:17:42.644  4045  4045 I bt_bluedroid: get_profile_interface sdp
,09-13 09:17:42.647  4045  4064 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 09:17:42.649  4045  4058 I bt_bluedroid: config_hci_snoop_log
,09-13 09:17:42.650   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-13 09:17:42.651  4045  4064 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 09:17:42.656  4045  4060 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 09:17:42.656  4045  4060 D BluetoothAdapterProperties: Setting state to 14
,09-13 09:17:42.656  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 09:17:42.657  4045  4060 D BluetoothBondStateMachine: make
,09-13 09:17:42.658  4030  4030 D BluetoothPbap: Proxy object connected
,09-13 09:17:42.661  4045  4065 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 09:17:42.663  4030  4030 D PbapServerProfile: Bluetooth service connected
,09-13 09:17:42.664  4030  4030 D BluetoothPbap: Proxy object disconnected
09-13 09:17:42.664  4030  4030 D PbapServerProfile: Bluetooth service disconnected
,09-13 09:17:42.675   874  1963 I ActivityManager: Start proc 4066:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-13 09:17:42.678  4045  4060 I BluetoothAdapterState: Entering PendingCommandState
09-13 09:17:42.678  4045  4045 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 09:17:42.681  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:42.681  4045  4045 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 09:17:42.681  4045  4045 D BtGatt.GattService: Received start request. Starting profile...
09-13 09:17:42.682  4045  4045 D BtGatt.GattService: start()
09-13 09:17:42.682  4045  4045 I bt_bluedroid: get_profile_interface gatt
09-13 09:17:42.682  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:42.682  4045  4045 D BtGatt.AdvertiseManager: advertise manager created
,09-13 09:17:42.688  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:42.689  4045  4045 V BluetoothAdapterState: isTurningOn()=false
,09-13 09:17:42.689  4045  4045 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 09:17:42.689  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:42.689  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 09:17:42.689  4045  4060 I bt_bluedroid: enable
,09-13 09:17:42.690  4045  4061 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 09:17:42.690  4045  4061 I bt_hci  : start_up
,09-13 09:17:42.696  4045  4061 I bt_vendor: alloc value 0xb3a4a189
,09-13 09:17:42.696  4045  4061 I bt_vendor: init
09-13 09:17:42.696  4045  4061 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 09:17:42.696  4045  4061 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 09:17:42.755  4066  4066 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 09:17:42.803  4045  4061 D bt_hci  : start_up starting async portion
09-13 09:17:42.804  4045  4074 I bt_hci  : event_finish_startup
09-13 09:17:42.805  4045  4074 I bt_hci_h4: hal_open
09-13 09:17:42.805  4045  4074 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 09:17:42.811  4045  4074 I bt_userial_vendor: device fd = 51 open
,09-13 09:17:42.847  4045  4074 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 09:17:42.879  4045  4074 D bt_hwcfg: Chipset BCM4354A2
,09-13 09:17:42.879  4045  4074 D bt_hwcfg: Target name = [BCM4354A2]
09-13 09:17:42.880  4045  4074 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 09:17:42.913  4066  4066 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 09:17:42.913  4066  4066 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 09:17:42.913  4066  4066 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 09:17:42.913  4066  4066 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.913  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 09:17:42.914  4066  4066 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 09:17:42.914  4066  4066 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 09:17:42.914  4066  4066 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:17:42.914  4066  4066 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:17:42.914  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:17:42.918  4030  4030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 09:17:42.925  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:17:42.937  4030  4030 D DockEventReceiver: finishStartingService: stopping service
,09-13 09:17:42.976   874  2100 I ActivityManager: Killing 3675:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 09:17:43.035   874  1972 I ActivityManager: Killing 3478:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 09:17:43.149  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 09:17:43.212  4066  4084 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 09:17:43.227   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f2c2962:true
,09-13 09:17:43.376  4045  4074 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 09:17:43.377  4045  4074 D bt_hwcfg: Settlement delay -- 100 ms
09-13 09:17:43.377  4045  4074 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 09:17:43.492  4045  4074 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 09:17:43.493  4045  4074 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 09:17:43.512  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 09:17:43.528  4045  4074 I bt_hwcfg: vendor lib fwcfg completed
,09-13 09:17:43.528  4045  4074 I bt_vendor: firmware callback
,09-13 09:17:43.528  4045  4074 I bt_hci  : firmware_config_callback
,09-13 09:17:43.538  4045  4106 I bt_btu  : btu_task pending for preload complete event
,09-13 09:17:43.539  4045  4106 I bt_btu_task: Bluetooth chip preload is complete
09-13 09:17:43.539  4045  4106 I bt_btu  : btu_task received preload complete event,
,09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_A2D,
09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 09:17:43.546  4045  4106 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 09:17:43.547  4045  4106 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 09:17:43.547  4045  4106 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-13 09:17:43.547  4045  4106 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 09:17:43.564  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 09:17:43.564  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 09:17:43.567   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 09:17:43.575   874  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 09:17:43.575   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 09:17:43.575   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:43.589   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:43.599   374   872 D CommandListener: Setting iface cfg
,09-13 09:17:43.600   874  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 09:17:43.613   874  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-13 09:17:43.616   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 09:17:43.654  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 09:17:43.674  4045  4106 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d
,09-13 09:17:43.675  4045  4106 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,09-13 09:17:43.682   874  4110 D DhcpClient: Receive thread started
,09-13 09:17:43.687  4045  4064 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 09:17:43.690  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 09:17:43.691  4045  4064 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 09:17:43.694  4045  4064 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 09:17:43.698  4045  4064 D BluetoothAdapterProperties: Scan Mode:20
,09-13 09:17:43.701  4045  4064 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:17:43.702  4045  4064 D bt_hci  : do_postload posting postload work item
09-13 09:17:43.702  4045  4074 I bt_hci  : event_postload
,09-13 09:17:43.702  4045  4074 I bt_vendor: sco_config_cb
,09-13 09:17:43.702  4045  4074 I bt_hci  : sco_config_callback postload finished.
,09-13 09:17:43.704  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:43.708  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.710  4045  4064 D bt_bte_conf: Device ID record 1 : primary
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   vendorId            = 000f
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   vendorIdSource      = 0001
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   product             = 1200
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   version             = 1436
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   clientExecutableURL = 
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   serviceDescription  = 
09-13 09:17:43.710  4045  4064 D bt_bte_conf:   documentationURL    = 
,09-13 09:17:43.710  4045  4064 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 09:17:43.711  4045  4061 D bt_stack_manager: event_start_up_stack finished
09-13 09:17:43.711  4045  4074 I bt_vendor: low_power_mode_cb
09-13 09:17:43.711  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 09:17:43.711  4045  4060 D BluetoothAdapterProperties: Setting state to 15
09-13 09:17:43.711  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 09:17:43.712  4045  4060 I BluetoothAdapterState: Entering BleOnState
09-13 09:17:43.712  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.715  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.716  4045  4060 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 09:17:43.716  4045  4060 D BluetoothAdapterProperties: Setting state to 11
09-13 09:17:43.716  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 09:17:43.724  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:43.724  4045  4045 D HeadsetService: Received start request. Starting profile...
,09-13 09:17:43.728  4045  4045 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 09:17:43.728  4045  4045 D HeadsetStateMachine: make
09-13 09:17:43.730  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.731  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.732  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.734  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:43.744  4045  4045 D HeadsetStateMachine: max_hf_connections = 1
,09-13 09:17:43.744  4045  4045 I bt_bluedroid: get_profile_interface handsfree
09-13 09:17:43.744  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 09:17:43.744  4045  4064 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-13 09:17:43.745  4045  4060 I BluetoothAdapterState: Entering PendingCommandState
,09-13 09:17:43.750  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:43.751  4045  4045 D A2dpService: Received start request. Starting profile...
09-13 09:17:43.752  4045  4045 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 09:17:43.752  4045  4045 I bt_bluedroid: get_profile_interface avrcp
,09-13 09:17:43.759  4045  4045 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 09:17:43.759  4045  4045 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 09:17:43.760  4045  4045 D A2dpStateMachine: make
,09-13 09:17:43.761  4045  4045 I bt_bluedroid: get_profile_interface a2dp
,09-13 09:17:43.761  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 09:17:43.765  4045  4118 D A2dpStateMachine: Enter Disconnected: -2
,09-13 09:17:43.768  4045  4045 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 09:17:43.768  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:43.770   874  1310 E native  : do suspend false
,09-13 09:17:43.770  4045  4045 D HidService: Received start request. Starting profile...
09-13 09:17:43.770  4030  4030 D BluetoothInputDevice: Proxy object connected
,09-13 09:17:43.770  4045  4045 I bt_bluedroid: get_profile_interface hidhost
,09-13 09:17:43.770  4030  4030 D HidProfile: Bluetooth service connected
09-13 09:17:43.771  4045  4045 D HidService: setHidService(): set to: null
09-13 09:17:43.771  4045  4045 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 09:17:43.772  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:43.772  4045  4064 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
09-13 09:17:43.772  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 09:17:43.772  4045  4045 D HealthService: Received start request. Starting profile...
,09-13 09:17:43.774  4045  4045 I bt_bluedroid: get_profile_interface health
,09-13 09:17:43.776  4045  4045 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 09:17:43.777  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:43.778  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:17:43.779  4030  4030 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 09:17:43.779  4045  4045 D PanService: Received start request. Starting profile...
09-13 09:17:43.780  4045  4045 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 09:17:43.780  4045  4045 I bt_bluedroid: get_profile_interface pan
09-13 09:17:43.780  4030  4030 D PanProfile: Bluetooth service connected
09-13 09:17:43.782   874  1887 D DhcpClient: Broadcasting DHCPDISCOVER
09-13 09:17:43.782  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:43.782  4045  4064 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 09:17:43.783  4045  4045 D BluetoothMapService: Received start request. Starting profile...
09-13 09:17:43.783  4045  4045 D BluetoothMapService: start()
09-13 09:17:43.784  4030  4030 D BluetoothMap: Proxy object connected
,09-13 09:17:43.785  4030  4030 D MapProfile: Bluetooth service connected
,09-13 09:17:43.785  4030  4030 D BluetoothMap: getConnectedDevices()
,09-13 09:17:43.785  4045  4045 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-13 09:17:43.786  4045  4045 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 09:17:43.786  4045  4045 D BluetoothMapAppObserver: createReceiver()
09-13 09:17:43.786  4030  4030 D BluetoothMap: Bluetooth is Not enabled
09-13 09:17:43.787  4045  4045 D BluetoothMapAppObserver: initObservers()
09-13 09:17:43.787  4045  4045 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 09:17:43.791  4045  4045 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:43.791  4045  4045 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:43.791  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 09:17:43.791  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 09:17:43.792  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:43.792  4045  4045 V BluetoothAdapterState: isTurningOn()=true
,09-13 09:17:43.792  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 09:17:43.792  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:43.793  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:43.793  4045  4116 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:43.797  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:43.798  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 09:17:43.798  4045  4060 D BluetoothAdapterProperties: ScanMode =  20
09-13 09:17:43.798  4045  4060 D BluetoothAdapterProperties: State =  11
09-13 09:17:43.799  4045  4064 D BluetoothAdapterProperties: Scan Mode:21
09-13 09:17:43.799  4045  4060 D BluetoothAdapterProperties: Setting state to 12
09-13 09:17:43.799  4045  4064 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:17:43.799  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 09:17:43.799  4045  4060 I BluetoothAdapterState: Entering OnState
09-13 09:17:43.800  1353  2064 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 09:17:43.801  3796  3796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 09:17:43.802  1353  1353 D BluetoothInputDevice: Proxy object connected
09-13 09:17:43.802  1353  1353 D HidProfile: Bluetooth service connected
09-13 09:17:43.802   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 09:17:43.803  1353  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 09:17:43.804   874   874 D BluetoothA2dp: Proxy object connected
09-13 09:17:43.804  3796  3796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-13 09:17:43.807  1353  1353 D BluetoothA2dp: Proxy object connected
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:43.807  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:43.807  4030  4044 D BluetoothPan: onBluetoothStateChange on: true
09-13 09:17:43.807  4030  4042 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 09:17:43.808  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:43.809  1353  3982 D BluetoothPan: onBluetoothStateChange on: true
09-13 09:17:43.811  4045  4045 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 09:17:43.811  4045  4045 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 09:17,:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:43.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:43.812  1932  1944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:43.812  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 09:17:43.812  1353  1353 D PanProfile: Bluetooth service connected
09-13 09:17:43.813  4045  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:43.813  1353  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:43.813  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:43.813   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:43.814   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:43.814  4030  4044 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 09:17:43.814  1353  1377 D BluetoothMap: onBluetoothStateChange: up=true
09-13 09:17:43.815  4045  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:43.816  4045  4045 D ObexServerSockets: Succeed to create listening sockets 
09-13 09:17:43.816  4045  4045 D ObexServerSockets0: startAccept()
09-13 09:17:43.816  4045  4045 D ObexServerSockets0: prepareForNewConnect()
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:43.817  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:43.817  1353  1353 D BluetoothMap: Proxy object connected
09-13 09:17:43.817  1353  1353 D MapProfile: Bluetooth service connected
09-13 09:17:43.817  1353  1353 D BluetoothMap: getConnectedDevices()
09-13 09:17:43.818  4045  4045 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 09:17:43.818  4045  4045 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 09:17:43.818  4045  4125 D ObexServerSockets0: Accepting socket connection...
09-13 09:17:43.818  4030  4042 D BluetoothMap: onBluetoothStateChange: up=true
09-13 09:17:43.819  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:43.819  1353  3982 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 09:17:43.819  4045  4124 D ObexServerSockets0: Accepting socket connection...
09-13 09:17:43.820   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:43.821   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:43.822  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:43.822  4045  4045 D BluetoothMapService: onReceive
09-13 09:17:43.822  4045  4045 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:17:43.822  4045  4045 D BluetoothMapService: STATE_ON
09-13 09:17:43.824  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:43.825  4030  4030 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 09:17:43.826  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.827  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.828  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.829  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:43.835  4030  4030 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 09:17:43.840  4030  4030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 09:17:43.842  4030  4030 D BluetoothA2dp: Proxy object connected
09-13 09:17:43.843  4045  4045 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 09:17:43.844  4045  4045 D ObexServerSockets0: prepareForNewConnect()
09-13 09:17:43.846  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:17:43.847  4030  4030 D DockEventReceiver: finishStartingService: stopping service
09-13 09:17:43.848  4045  4129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:43.848  4030  4030 D BluetoothPbap: Proxy object connected
09-13 09:17:43.848  4030  4030 D PbapServerProfile: Bluetooth service connected
09-13 09:17:43.854  1353  1353 D BluetoothPbap: Proxy object connected
09-13 09:17:43.854  1353  1353 D PbapServerProfile: Bluetooth service connected
,09-13 09:17:43.872  4045  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:43.873  4045  4135 I BtOppRfcommListener: Accept thread started.
09-13 09:17:43.881   874  4110 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172693, domain null
09-13 09:17:43.882   874  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172693 seconds
09-13 09:17:43.883   874  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 09:17:43.915  1353  1367 D BluetoothHeadset: Proxy object connected
,09-13 09:17:43.915  1353  1353 D HeadsetProfile: Bluetooth service connected
,09-13 09:17:43.915  1932  2347 D BluetoothHeadset: Proxy object connected
,09-13 09:17:43.916   874   874 D BluetoothHeadset: Proxy object connected
,09-13 09:17:43.916   874   874 D BluetoothHeadset: Proxy object connected
09-13 09:17:43.917   874   874 D BluetoothHeadset: Proxy object connected
,09-13 09:17:43.920   874   891 D BluetoothHeadset: Proxy object connected
,09-13 09:17:43.937  4030  4044 D BluetoothHeadset: Proxy object connected
09-13 09:17:43.938  4030  4030 D HeadsetProfile: Bluetooth service connected
,09-13 09:17:43.967   874  4110 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 09:17:43.968   874  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 09:17:43.972   374   872 D CommandListener: Setting iface cfg
,09-13 09:17:43.975   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 09:17:43.982   874  1887 D DhcpClient: Scheduling renewal in 86399s
,09-13 09:17:43.989   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 09:17:43.990   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 09:17:43.991   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 09:17:43.991   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 09:17:43.994   874  1312 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 09:17:43.998   874  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 09:17:44.050   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 09:17:44.050   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 09:17:44.052   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 09:17:44.053   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 09:17:44.054   874  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 09:17:44.065   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 09:17:44.072   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-13 09:17:44.072   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-13 09:17:44.073   874  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 09:17:44.074   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 09:17:44.074   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-13 09:17:44.074   874  1312 D ConnectivityService:    accepting network in place of null
,09-13 09:17:44.077   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 09:17:44.091   874  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130407, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:17:44.117   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.166  3796  4006 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:44.172  3796  4006 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:44.173   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:44.179  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:17:44.179  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:44.179   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 09:17:44.180   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:17:44.185   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 09:17:44.189   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 09:17:44.194   874  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:816::200e
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.209  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:44.211  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.216  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:44.217  4045  4060 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 09:17:44.217  4045  4060 D BluetoothAdapterProperties: Setting state to 13
,09-13 09:17:44.217  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 09:17:44.218  4045  4060 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 09:17:44.219  4045  4060 I BluetoothAdapterState: Entering PendingCommandState
,09-13 09:17:44.220  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:44.220  4045  4064 D BluetoothAdapterProperties: Scan Mode:20
,09-13 09:17:44.221  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 09:17:44.222  4045  4045 D BluetoothMapService: onReceive
09-13 09:17:44.222  4045  4045 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:17:44.222  4045  4045 D BluetoothMapService: STATE_TURNING_OFF
09-13 09:17:44.223  4045  4045 D BluetoothMapService: MAP Service closeService in
09-13 09:17:44.223  4045  4045 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 09:17:44.223  4045  4045 D ObexServerSockets0: shutdown(block = true)
09-13 09:17:44.224  4045  4045 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 09:17:44.224  4045  4124 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 09:17:44.224  4045  4045 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 09:17:44.224  4045  4112 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 09:17:44.225  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-13 09:17:44.225  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.225  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:44.225  4045  4125 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 09:17:44.226  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:44.226  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:44.226  4045  4045 I BtOppRfcommListener: stopping Accept Thread
09-13 09:17:44.226  4045  4135 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:17:44.227  4045  4135 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 09:17:44.229  1744  1744 D SystemUpdateService: onCreate
09-13 09:17:44.229  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.230  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:44.230  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:44.231  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.234  4045  4045 D HeadsetService: Received stop request...Stopping profile...
09-13 09:17:44.235  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.235  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:44.236  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-13 09:17:44.236  4045  4045 D A2dpService: Received stop request...Stopping profile...
09-13 09:17:44.237  1353  1377 D BluetoothHeadset: Proxy object disconnected
09-13 09:17:44.237  4045  4118 D A2dpStateMachine: Exit Disconnected: -1
09-13 09:17:44.238  4030  4042 D BluetoothHeadset: Proxy object disconnected
09-13 09:17:44.239  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:17:44.239  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:44.239  4045  4045 D HidService: Received stop request...Stopping profile...
09-13 09:17:44.239  4045  4045 D HidService: Stopping Bluetooth HidService
09-13 09:17:44.241  1932  1944 D BluetoothHeadset: Proxy object disconnected
09-13 09:17:44.241   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 09:17:44.241   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 09:17:44.241   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 09:17:44.241   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 09:17:44.242  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:44.242  4030  4030 D BluetoothA2dp: Proxy object disconnected
09-13 09:17:44.242  4030  4030 D HeadsetProfile: Bluetooth service disconnected
09-13 09:17:44.243  4030  4030 D BluetoothInputDevice: Proxy object disconnected
,09-13 09:17:44.243  4030  4030 D HidProfile: Bluetooth service disconnected
09-13 09:17:44.244  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:44.247  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:44.247  4045  4045 D HealthService: Received stop request...Stopping profile...
09-13 09:17:44.250  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:44.250  1353  1353 D HeadsetProfile: Bluetooth service disconnected
,09-13 09:17:44.250  1353  1353 D BluetoothA2dp: Proxy object disconnected
09-13 09:17:44.250  1353  1353 D BluetoothInputDevice: Proxy object disconnected
09-13 09:17:44.250  1353  1353 D HidProfile: Bluetooth service disconnected
09-13 09:17:44.251  1744  4147 I SystemUpdateService: active receiver: enabled
09-13 09:17:44.251  4045  4045 D PanService: Received stop request...Stopping profile...
09-13 09:17:44.252  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 09:17:44.252  1353  1353 D PanProfile: Bluetooth service disconnected
09-13 09:17:44.252  4030  4030 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 09:17:44.252  4030  4030 D PanProfile: Bluetooth service disconnected
,09-13 09:17:44.252  4045  4045 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:44.252  4045  4045 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:44.252  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:44.252  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:44.253  4045  4045 D BluetoothMapService: Received stop request...Stopping profile...
09-13 09:17:44.253  4045  4045 D BluetoothMapService: stop()
,09-13 09:17:44.254  4045  4045 D BluetoothMapAppObserver: deinitObservers()
09-13 09:17:44.254  4045  4045 D BluetoothMapAppObserver: removeReceiver()
09-13 09:17:44.256  1353  1353 D BluetoothMap: Proxy object disconnected
09-13 09:17:44.256  1353  1353 D MapProfile: Bluetooth service disconnected
09-13 09:17:44.256  4030  4030 D BluetoothMap: Proxy object disconnected
09-13 09:17:44.257  4030  4030 D MapProfile: Bluetooth service disconnected
,09-13 09:17:44.258  4045  4045 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 09:17:44.258  4045  4106 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:44.258  4045  4106 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:44.258  4045  4106 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:44.259  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 09:17:44.258  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 09:17:44.260  4045  4064 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 09:17:44.261  4045  4045 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:17:44.261  4045  4045 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:44.262  4045  4045 V BluetoothAdapterState: isTurningOn()=false
,09-13 09:17:44.262  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:44.262  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:44.263  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 09:17:44.263  4045  4106 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:44.264  4045  4106 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 09:17:44.264  4045  4106 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:17:44.264  4045  4106 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 09:17:44.264  4045  4106 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:17:44.264  4045  4106 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:17:44.264  4045  4045 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 09:17:44.265  4045  4045 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 09:17:44.265  4045  4045 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 09:17:44.265  4045  4064 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 09:17:44.265  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:44.266  4045  4045 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 09:17:44.266  4045  4064 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 09:17:44.266  4045  4045 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 09:17:44.266  4045  4045 V BluetoothAdapterState: isTurningOff()=true
09-13 09:17:44.266  4045  4045 V BluetoothAdapterState: isTurningOn()=false
,09-13 09:17:44.266  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:44.266  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:44.266  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 09:17:44.268  4045  4045 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 09:17:44.268  4045  4045 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 09:17:44.270  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 09:17:44.271  4045  4045 D BluetoothMapService: MAP Service closeService in
09-13 09:17:44.271  4045  4045 V BluetoothAdapterState: isTurningOff()=true
,09-13 09:17:44.271  4045  4045 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:44.271  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:44.271  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:44.271  4045  4045 D BluetoothMapService: cleanup()
,09-13 09:17:44.271  4045  4045 D BluetoothMapService: MAP Service closeService in
09-13 09:17:44.271  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 09:17:44.272  4045  4060 D BluetoothAdapterProperties: Setting state to 15
,09-13 09:17:44.272  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 09:17:44.272  4045  4060 I BluetoothAdapterState: Entering BleOnState
09-13 09:17:44.272  1744  2462 I iu.UploadsManager: num queued entries: 0
09-13 09:17:44.274   874  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:17:44 GMT], X-Android-Received-Millis=[1473751064274], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473751064245]}
09-13 09:17:44.275  1353  2064 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 09:17:44.276   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 09:17:44.276   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 09:17:44.276   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 09:17:44.276   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 09:17:44.276  1353  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 09:17:44.277  1744  2462 I iu.UploadsManager: num updated entries: 0
09-13 09:17:44.277  4030  4044 D BluetoothPan: onBluetoothStateChange on: false
09-13 09:17:44.278   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 09:17:44.278  1744  4147 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-13 09:17:44.280  4030  4148 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 09:17:44.279  1744  2462 I iu.SyncManager: NEXT; no task
09-13 09:17:44.280  3888  3888 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:17:44.280  4030  4042 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 09:17:44.281  1744  4147 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 09:17:44.281  1744  4147 I SystemUpdateService: now status is 0 (complete)
09-13 09:17:44.281  4030  4044 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:44.281  1744  4147 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 09:17:44.281  1744  4147 I SystemUpdateService: file has been verified
09-13 09:17:44.281  1353  2064 D BluetoothPan: onBluetoothStateChange on: false
09-13 09:17:44.281  1744  4151 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 09:17:44.281  1744  4151 W BaseAppContext: Using Auth Proxy for data requests.
09-13 09:17:44.281  1932  1948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:44.282  1353  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:44.282   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 09:17:44.282   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:44.282  1744  4147 I SystemUpdateService: OTA package size = 12249756
09-13 09:17:44.282  4030  4148 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 09:17:44.282  1744  4151 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 09:17:44.284  1353  1377 D BluetoothMap: onBluetoothStateChange: up=false
09-13 09:17:44.284  4030  4042 D BluetoothMap: onBluetoothStateChange: up=false
09-13 09:17:44.286  1353  2064 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 09:17:44.289  1744  4147 I SystemUpdateService: showing system update notification
,09-13 09:17:44.289   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:17:44.290  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 09:17:44.290  4045  4060 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 09:17:44.290  4045  4060 D BluetoothAdapterProperties: Setting state to 16
09-13 09:17:44.290  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 09:17:44.290  4045  4060 D BluetoothAdapterProperties: onBleDisable
,09-13 09:17:44.291  4045  4060 I BluetoothAdapterState: Entering PendingCommandState
09-13 09:17:44.291  4045  4061 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 09:17:44.291  4045  4106 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-13 09:17:44.291  4045  4106 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 09:17:44.293  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 09:17:44.294  4045  4064 D BluetoothAdapterProperties: Scan Mode:20
,09-13 09:17:44.296  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:44.295  3888  3888 D SprintDMHelper: simOperator: 
09-13 09:17:44.296  3888  3888 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 09:17:44.298  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:44.300  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:44.302  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:44.304  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:44.307  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:44.312  1744  1744 D SystemUpdateService: onDestroy
,09-13 09:17:44.327  4030  4030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 09:17:44.332  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 09:17:44.332  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-13 09:17:44.332  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:44.333  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:44.334  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:17:44.336  4030  4030 D DockEventReceiver: finishStartingService: stopping service
,09-13 09:17:44.350  1744  4151 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-13 09:17:44.350  4030  4030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 09:17:44.367  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:17:44.373  4030  4030 D DockEventReceiver: finishStartingService: stopping service
,09-13 09:17:44.461  3089  4154 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 09:17:44.491  4045  4064 I bt_hci  : shut_down
,09-13 09:17:44.492  4045  4074 D bt_hwcfg: hw_epilog_process
,09-13 09:17:44.493  4045  4074 I bt_vendor: low_power_mode_cb
,09-13 09:17:44.519  4045  4074 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 09:17:44.520  4045  4074 I bt_vendor: epilog_cb
09-13 09:17:44.520  4045  4074 I bt_hci  : epilog_finished_callback
09-13 09:17:44.521  4045  4064 I bt_hci_h4: hal_close
,09-13 09:17:44.524  4045  4064 I bt_userial_vendor: device fd = 51 close
,09-13 09:17:44.646  4045  4061 D bt_stack_manager: event_shut_down_stack finished.
,09-13 09:17:44.648  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 09:17:44.652  4045  4060 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 09:17:44.652  4045  4045 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 09:17:44.653  4045  4045 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 09:17:44.653  4045  4045 D BtGatt.GattService: stop()
,09-13 09:17:44.653  4045  4045 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 09:17:44.657  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:44.657  4045  4045 V BluetoothAdapterState: isTurningOn()=false
,09-13 09:17:44.657  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 09:17:44.657  4045  4045 V BluetoothAdapterState: isBleTurningOff()=true
09-13 09:17:44.658  4045  4060 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25,
09-13 09:17:44.658  4045  4060 D BluetoothAdapterProperties: Setting state to 10,
09-13 09:17:44.658  4045  4060 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 09:17:44.659  4045  4060 I BluetoothAdapterState: Entering OffState
09-13 09:17:44.660   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 09:17:44.678  4045  4045 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-13 09:17:44.678  4045  4045 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 09:17:44.678  4045  4045 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 09:17:44.680  4045  4061 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 09:17:44.685  4045  4061 D bt_stack_manager: event_clean_up_stack finished.
,09-13 09:17:44.687  4045  4045 I art     : System.exit called, status: 0
,09-13 09:17:44.687  4045  4045 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 09:17:44.719  3796  4143 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:44.719  3796  4143 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:44.719  3796  4143 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:17:44.720  3796  4143 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:44.724  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:44.730   280   280 E lowmemorykiller: Error writing /proc/4045/oom_score_adj; errno=22
,09-13 09:17:44.731   874   891 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,09-13 09:17:44.734   874   891 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1300)
,09-13 09:17:44.735   874   891 W ActivityManager: Application dead when creating service ServiceRecord{cec28b8 u0 com.android.bluetooth/.btservice.AdapterService}
,09-13 09:17:44.736   874   891 I ActivityManager: Process com.android.bluetooth (pid 4045) has died
,09-13 09:17:44.737   874   891 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 09:17:44.741   874   891 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,09-13 09:17:44.743   874   891 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
09-13 09:17:44.743   874   891 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:15988)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1587)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1543)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1214)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:17:44.743   874   891 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:17:44.743   874   891 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 09:17:44.744   874  1972 W ActivityManager: Spurious death for ProcessRecord{4845e3f 0:com.android.bluetooth/1002}, curProc for 4045: null
,09-13 09:17:45.181   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 09:17:46.641   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 09:17:47.334  4010  4017 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@9bc58af)
,09-13 09:17:47.729   874   891 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,09-13 09:17:47.793   874   891 I ActivityManager: Start proc 4167:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 09:17:47.890  4167  4167 D AdapterServiceConfig: Adding HeadsetService
,09-13 09:17:47.890  4167  4167 D AdapterServiceConfig: Adding A2dpService
,09-13 09:17:47.891  4167  4167 D AdapterServiceConfig: Adding HidService
,09-13 09:17:47.891  4167  4167 D AdapterServiceConfig: Adding HealthService
,09-13 09:17:47.891  4167  4167 D AdapterServiceConfig: Adding PanService
,09-13 09:17:47.891  4167  4167 D AdapterServiceConfig: Adding GattService
,09-13 09:17:47.891  4167  4167 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 09:17:47.902  4167  4167 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 09:17:47.902   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e971864:true
,09-13 09:17:47.905  4167  4167 I bt_bluedroid: init
,09-13 09:17:47.905  4167  4179 I BluetoothAdapterState: Entering OffState
,09-13 09:17:47.910  4167  4180 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 09:17:47.910  4167  4180 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 09:17:47.910  4167  4180 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 09:17:47.911  4167  4180 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 09:17:47.912  4167  4167 I bt_bluedroid: get_profile_interface socket
,09-13 09:17:47.913  4167  4167 I bt_bluedroid: get_profile_interface sdp
,09-13 09:17:47.917  4167  4177 I bt_bluedroid: config_hci_snoop_log
09-13 09:17:47.918  4167  4183 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 09:17:47.924   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-13 09:17:47.924  4167  4183 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 09:17:47.929  4167  4179 D BluetoothAdapterState: Current state: OFF, message: 0
09-13 09:17:47.929  4167  4179 D BluetoothAdapterProperties: Setting state to 14
,09-13 09:17:47.929  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-13 09:17:47.930  4167  4179 D BluetoothBondStateMachine: make
,09-13 09:17:47.933  4167  4184 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 09:17:47.935  4167  4179 I BluetoothAdapterState: Entering PendingCommandState
09-13 09:17:47.936  4167  4167 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 09:17:47.938  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:47.938  4167  4167 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 09:17:47.939  4167  4167 D BtGatt.GattService: Received start request. Starting profile...
09-13 09:17:47.939  4167  4167 D BtGatt.GattService: start()
09-13 09:17:47.939  4167  4167 I bt_bluedroid: get_profile_interface gatt
09-13 09:17:47.940  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:47.940  4167  4167 D BtGatt.AdvertiseManager: advertise manager created
,09-13 09:17:47.947  4167  4167 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:47.947  4167  4167 V BluetoothAdapterState: isTurningOn()=false
09-13 09:17:47.947  4167  4167 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 09:17:47.947  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:47.947  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 09:17:47.948  4167  4179 I bt_bluedroid: enable
09-13 09:17:47.948  4167  4180 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 09:17:47.949  4167  4180 I bt_hci  : start_up
,09-13 09:17:47.966  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:17:47.968  4167  4180 I bt_vendor: alloc value 0xb3a4a189
,09-13 09:17:47.968  4167  4180 I bt_vendor: init
,09-13 09:17:47.969  4167  4180 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-13 09:17:47.969  4167  4180 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 09:17:47.991  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:17:47.991  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 09:17:47.991  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:47.991  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:48.009  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 09:17:48.009  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:17:48.009  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-13 09:17:48.078  4167  4180 D bt_hci  : start_up starting async portion
,09-13 09:17:48.079  4167  4187 I bt_hci  : event_finish_startup
09-13 09:17:48.080  4167  4187 I bt_hci_h4: hal_open
09-13 09:17:48.080  4167  4187 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 09:17:48.087  4167  4187 I bt_userial_vendor: device fd = 51 open
,09-13 09:17:48.121  4167  4187 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 09:17:48.152  4167  4187 D bt_hwcfg: Chipset BCM4354A2
09-13 09:17:48.153  4167  4187 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 09:17:48.153  4167  4187 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 09:17:48.264  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 09:17:48.771  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 09:17:48.832  4167  4187 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 09:17:48.834  4167  4187 D bt_hwcfg: Settlement delay -- 100 ms
09-13 09:17:48.834  4167  4187 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 09:17:48.951  4167  4187 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 09:17:48.952  4167  4187 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 09:17:48.982  4167  4187 I bt_hwcfg: vendor lib fwcfg completed
,09-13 09:17:48.982  4167  4187 I bt_vendor: firmware callback
,09-13 09:17:48.982  4167  4187 I bt_hci  : firmware_config_callback
,09-13 09:17:48.988  4167  4189 I bt_btu  : btu_task pending for preload complete event
,09-13 09:17:48.988  4167  4189 I bt_btu_task: Bluetooth chip preload is complete
,09-13 09:17:48.988  4167  4189 I bt_btu  : btu_task received preload complete event
,09-13 09:17:48.996  4167  4189 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 09:17:48.996  4167  4189 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 09:17:48.997  4167  4189 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 09:17:48.997  4167  4189 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 09:17:48.997  4167  4189 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 09:17:48.997  4167  4189 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 09:17:48.998  4167  4189 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 09:17:48.998  4167  4189 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 09:17:48.998  4167  4189 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 09:17:48.998  4167  4189 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 09:17:48.999  4167  4189 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 09:17:48.999  4167  4189 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 09:17:48.999  4167  4189 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 09:17:48.999  4167  4189 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 09:17:49.000  4167  4189 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 09:17:49.130  4167  4189 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d
,09-13 09:17:49.130  4167  4189 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,09-13 09:17:49.155  4167  4183 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 09:17:49.156  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 09:17:49.157  4167  4183 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 09:17:49.159  4167  4183 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 09:17:49.162  4167  4183 D BluetoothAdapterProperties: Scan Mode:20
09-13 09:17:49.162  4167  4183 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 09:17:49.162  4167  4183 D bt_hci  : do_postload posting postload work item
09-13 09:17:49.163  4167  4187 I bt_hci  : event_postload
,09-13 09:17:49.164  4167  4187 I bt_vendor: sco_config_cb
,09-13 09:17:49.164  4167  4187 I bt_hci  : sco_config_callback postload finished.
09-13 09:17:49.165  4167  4183 D bt_bte_conf: Device ID record 1 : primary
09-13 09:17:49.165  4167  4183 D bt_bte_conf:   vendorId            = 000f
09-13 09:17:49.165  4167  4183 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 09:17:49.165  4167  4183 D bt_bte_conf:   product             = 1200
09-13 09:17:49.165  4167  4183 D bt_bte_conf:   version             = 1436
09-13 09:17:49.165  4167  4183 D bt_bte_conf:   clientExecutableURL = 
,09-13 09:17:49.165  4167  4183 D bt_bte_conf:   serviceDescription  = 
,09-13 09:17:49.165  4167  4183 D bt_bte_conf:   documentationURL    = 
09-13 09:17:49.165  4167  4183 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 09:17:49.165  4167  4180 D bt_stack_manager: event_start_up_stack finished
09-13 09:17:49.167  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 09:17:49.167  4167  4179 D BluetoothAdapterProperties: Setting state to 15
,09-13 09:17:49.167  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 09:17:49.168  4167  4179 I BluetoothAdapterState: Entering BleOnState
,09-13 09:17:49.172  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.175  4167  4187 I bt_vendor: low_power_mode_cb
,09-13 09:17:49.174  4167  4179 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 09:17:49.175  4167  4179 D BluetoothAdapterProperties: Setting state to 11
,09-13 09:17:49.175  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 09:17:49.178  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.183  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:49.186  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.187  4167  4167 D HeadsetService: Received start request. Starting profile...
09-13 09:17:49.195  4167  4179 I BluetoothAdapterState: Entering PendingCommandState
,09-13 09:17:49.196  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:49.199  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.201  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:49.202  4167  4167 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 09:17:49.203  4167  4167 D HeadsetStateMachine: make
,09-13 09:17:49.212  4167  4167 D HeadsetStateMachine: max_hf_connections = 1
,09-13 09:17:49.212  4167  4167 I bt_bluedroid: get_profile_interface handsfree
09-13 09:17:49.212  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 09:17:49.212  4167  4183 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 09:17:49.217  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:49.217  4167  4167 D A2dpService: Received start request. Starting profile...
09-13 09:17:49.218  4167  4167 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 09:17:49.218  4167  4167 I bt_bluedroid: get_profile_interface avrcp
,09-13 09:17:49.225  4167  4167 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 09:17:49.225  4167  4167 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 09:17:49.225  4167  4167 D A2dpStateMachine: make
09-13 09:17:49.227  4167  4167 I bt_bluedroid: get_profile_interface a2dp
,09-13 09:17:49.227  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 09:17:49.229  4167  4167 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 09:17:49.230  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:49.230  4167  4198 D A2dpStateMachine: Enter Disconnected: -2
09-13 09:17:49.230  4167  4167 D HidService: Received start request. Starting profile...
,09-13 09:17:49.232  4167  4167 I bt_bluedroid: get_profile_interface hidhost
,09-13 09:17:49.232  4167  4167 D HidService: setHidService(): set to: null
09-13 09:17:49.232  4167  4183 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
,09-13 09:17:49.232  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 09:17:49.233  4167  4167 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 09:17:49.234  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
09-13 09:17:49.234  4167  4167 D HealthService: Received start request. Starting profile...
09-13 09:17:49.236  4167  4167 I bt_bluedroid: get_profile_interface health
,09-13 09:17:49.237  4167  4167 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 09:17:49.238  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:49.239  4167  4167 D PanService: Received start request. Starting profile...
09-13 09:17:49.239  4167  4167 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 09:17:49.239  4167  4167 I bt_bluedroid: get_profile_interface pan
,09-13 09:17:49.240  4167  4183 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 09:17:49.242  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:49.243  4167  4167 D BluetoothMapService: Received start request. Starting profile...
09-13 09:17:49.243  4167  4167 D BluetoothMapService: start()
,09-13 09:17:49.245  4167  4167 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 09:17:49.246  4167  4167 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 09:17:49.246  4167  4167 D BluetoothMapAppObserver: createReceiver()
,09-13 09:17:49.247  4167  4167 D BluetoothMapAppObserver: initObservers()
09-13 09:17:49.247  4167  4167 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 09:17:49.255  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:17:49.257  4167  4196 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 09:17:49.257  4167  4167 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:49.257  4167  4167 V BluetoothAdapterState: isTurningOn()=true
,09-13 09:17:49.257  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:49.258  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:49.259  4167  4167 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:49.259  4167  4167 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:49.259  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:49.259  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isTurningOff()=false
,09-13 09:17:49.260  4167  4167 V BluetoothAdapterState: isTurningOn()=true
,09-13 09:17:49.261  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
09-13 09:17:49.261  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:49.261  4167  4167 V BluetoothAdapterState: isTurningOff()=false
09-13 09:17:49.261  4167  4167 V BluetoothAdapterState: isTurningOn()=true
09-13 09:17:49.261  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 09:17:49.261  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
09-13 09:17:49.261  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 09:17:49.261  4167  4179 D BluetoothAdapterProperties: ScanMode =  20
09-13 09:17:49.262  4167  4179 D BluetoothAdapterProperties: State =  11
09-13 09:17:49.264  4167  4183 D BluetoothAdapterProperties: Scan Mode:21
09-13 09:17:49.264  4167  4179 D BluetoothAdapterProperties: Setting state to 12
,09-13 09:17:49.264  4167  4183 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:17:49.264  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 09:17:49.265  1353  2064 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 09:17:49.265  4167  4179 I BluetoothAdapterState: Entering OnState
09-13 09:17:49.268   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:49.270  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:49.271  1353  1353 D BluetoothInputDevice: Proxy object connected
,09-13 09:17:49.271  1353  1353 D HidProfile: Bluetooth service connected
,09-13 09:17:49.272  1353  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 09:17:49.272  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.273  4167  4167 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 09:17:49.274  4167  4167 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 09:17:49.275  4167  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:49.276  4030  4042 D BluetoothPan: onBluetoothStateChange on: true
,09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:49.279  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:49.280  4167  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:49.280  3796  4166 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:49.281  4030  4044 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 09:17:49.281  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.281  4167  4167 D ObexServerSockets: Succeed to create listening sockets 
09-13 09:17:49.282  4167  4167 D ObexServerSockets0: startAccept()
09-13 09:17:49.282  4167  4167 D ObexServerSockets0: prepareForNewConnect()
09-13 09:17:49.284  4030  4148 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 09:17:49.285  3796  4166 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.286  4030  4042 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:49.286  4167  4167 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 09:17:49.286  4167  4167 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:49.286  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:17:49.286  1353  1377 D BluetoothPan: onBluetoothStateChange on: true
,09-13 09:17:49.288   874   874 D BluetoothA2dp: Proxy object connected
09-13 09:17:49.288  1353  1353 D BluetoothA2dp: Proxy object connected
09-13 09:17:49.288  1932  1948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:49.289  1353  3982 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:49.290  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:49.290   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:49.290  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:49.290   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:49.290  4030  4042 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 09:17:49.290   874  1974 D WifiService: setWifiEnabled: false pid=3796, uid=10000
09-13 09:17:49.291   874  1974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:17:49.291  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 09:17:49.291  1353  1353 D PanProfile: Bluetooth service connected
09-13 09:17:49.292  4167  4205 D ObexServerSockets0: Accepting socket connection...
,09-13 09:17:49.293  4167  4204 D ObexServerSockets0: Accepting socket connection...
09-13 09:17:49.293   874  2100 D WifiService: setWifiEnabled: false pid=3796, uid=10000
09-13 09:17:49.294   874  2100 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:17:49.300  4030  4030 D BluetoothA2dp: Proxy object connected
09-13 09:17:49.301  1353  2064 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 09:17:49.302  4030  4030 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 09:17:49.302  4030  4030 D PanProfile: Bluetooth service connected
09-13 09:17:49.303  4030  4030 D BluetoothInputDevice: Proxy object connected
09-13 09:17:49.304  4030  4030 D HidProfile: Bluetooth service connected
,09-13 09:17:49.305  1353  1353 D BluetoothMap: Proxy object connected
09-13 09:17:49.305  1353  1353 D MapProfile: Bluetooth service connected
09-13 09:17:49.306  1353  1353 D BluetoothMap: getConnectedDevices()
,09-13 09:17:49.307  4030  4148 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 09:17:49.309  4030  4030 D BluetoothMap: Proxy object connected
,09-13 09:17:49.309  4030  4030 D MapProfile: Bluetooth service connected
09-13 09:17:49.309  1353  1367 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 09:17:49.310  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 09:17:49.312   874  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 09:17:49.312   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:17:49.312   874  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 09:17:49.312   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 09:17:49.312   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:49.314  4167  4167 D BluetoothMapService: onReceive
,09-13 09:17:49.314  4167  4167 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:17:49.314  4167  4167 D BluetoothMapService: STATE_ON
09-13 09:17:49.315   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 09:17:49.309  4030  4030 D BluetoothMap: getConnectedDevices()
,09-13 09:17:49.316  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.319  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.321  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.323  4030  4030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 09:17:49.330   874  1887 D DhcpClient: Clearing IP address
,09-13 09:17:49.330   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 09:17:49.331  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:17:49.332  4030  4030 D DockEventReceiver: finishStartingService: stopping service
,09-13 09:17:49.334   374   872 D CommandListener: Setting iface cfg
09-13 09:17:49.336  1523  4162 V NativeCrypto: Read error: ssl=0x9b0c3000: I/O error during system call, Connection timed out
,09-13 09:17:49.337  1523  4162 V NativeCrypto: SSL shutdown failed: ssl=0x9b0c3000: I/O error during system call, Broken pipe
,09-13 09:17:49.338   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 09:17:49.338   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 09:17:49.340   402   402 E Parcel  : Reading a NULL string not supported here.
09-13 09:17:49.343   874  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
09-13 09:17:49.344   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 09:17:49.346   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 09:17:49.347   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 09:17:49.353  4030  4030 D BluetoothPbap: Proxy object connected
09-13 09:17:49.353  4030  4030 D PbapServerProfile: Bluetooth service connected
09-13 09:17:49.353   874  4110 D DhcpClient: Receive thread stopped
09-13 09:17:49.354  4167  4167 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 09:17:49.354  4167  4167 D ObexServerSockets0: prepareForNewConnect()
,09-13 09:17:49.358  1353  1353 D BluetoothPbap: Proxy object connected
09-13 09:17:49.358  1353  1353 D PbapServerProfile: Bluetooth service connected
,09-13 09:17:49.360   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.364  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:49.366  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:17:49.366   874  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 09:17:49.372  4167  4213 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.372  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:49.374  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:49.376  2076  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.376  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:17:49.378  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:49.391  4167  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:49.391   874   891 D BluetoothHeadset: Proxy object connected
09-13 09:17:49.391   874   891 D BluetoothHeadset: Proxy object connected
09-13 09:17:49.391  1353  1377 D BluetoothHeadset: Proxy object connected
,09-13 09:17:49.391  1353  1353 D HeadsetProfile: Bluetooth service connected
,09-13 09:17:49.392  4030  4044 D BluetoothHeadset: Proxy object connected
09-13 09:17:49.393  4167  4218 I BtOppRfcommListener: Accept thread started.
09-13 09:17:49.393  1932  2154 D BluetoothHeadset: Proxy object connected
,09-13 09:17:49.393   874   874 D BluetoothHeadset: Proxy object connected
09-13 09:17:49.393   874   874 D BluetoothHeadset: Proxy object connected
09-13 09:17:49.393   874   874 D BluetoothHeadset: Proxy object connected
09-13 09:17:49.394  4030  4030 D HeadsetProfile: Bluetooth service connected
09-13 09:17:49.394   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:49.413   874   891 D BluetoothHeadset: Proxy object connected
,09-13 09:17:49.414   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:49.415   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 09:17:49.415   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:17:49.416   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 09:17:49.418  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.419  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.420  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.424  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-13 09:17:49.427  1744  1744 D SystemUpdateService: onCreate
09-13 09:17:49.430  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-13 09:17:49.433  1744  4223 I SystemUpdateService: active receiver: enabled
,09-13 09:17:49.437  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 09:17:49.439  1744  2462 I iu.UploadsManager: num queued entries: 0
,09-13 09:17:49.442  1744  4223 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 09:17:49.444  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 09:17:49.446  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 09:17:49.447  3888  3888 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:17:49.440  1744  2462 I iu.UploadsManager: num updated entries: 0
,09-13 09:17:49.449  1744  4223 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 09:17:49.449  1744  4223 I SystemUpdateService: now status is 0 (complete)
,09-13 09:17:49.449  1744  4223 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 09:17:49.449  1744  4223 I SystemUpdateService: file has been verified
,09-13 09:17:49.454  3888  3888 D SprintDMHelper: simOperator: 
,09-13 09:17:49.454  3888  3888 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 09:17:49.463  1744  4223 I SystemUpdateService: OTA package size = 12249756
,09-13 09:17:49.467  3089  4228 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 09:17:49.468   374   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 09:17:49.469   874  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 09:17:49.476  1744  2462 I iu.SyncManager: NEXT; no task
,09-13 09:17:49.487  1744  4223 I SystemUpdateService: showing system update notification
,09-13 09:17:49.494  1744  1744 D SystemUpdateService: onDestroy
,09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.806  3796  4208 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:49.813  3796  4208 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:49.821  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:49.822   874   884 D WifiService: setWifiEnabled: true pid=3796, uid=10000
,09-13 09:17:49.823   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:17:49.832   874  1991 D WifiService: setWifiEnabled: true pid=3796, uid=10000
,09-13 09:17:49.832   874  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:17:49.838   874  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.856  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:49.864  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.877  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:49.881  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:49.881   874  1310 D WifiConfigStore: loaded 0 passpoint configs
09-13 09:17:49.882   874  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 09:17:49.883   874  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 09:17:49.884   874  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 09:17:49.885   874  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 09:17:49.885   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 09:17:49.885   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:49.887  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:49.891  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:49.899   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 09:17:49.900   374   872 D CommandListener: Setting iface cfg
,09-13 09:17:49.901   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-13 09:17:49.901   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 09:17:49.907   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 09:17:49.911   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 09:17:49.915   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 09:17:49.915   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:17:50.345  3796  4230 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:17:50.352  3796  4230 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:17:50.360  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:17:50.363  3796  3847 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 09:17:50.364   874  1991 D WifiService: setWifiEnabled: true pid=3796, uid=10000
09-13 09:17:50.364   874  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:17:50.380  3796  4233 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 09:17:50.381  3796  4233 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 09:17:50.749   874  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.25 rxSuccessRate=7.62 delta 1000 -> 994
,09-13 09:17:50.750   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 09:17:50.751   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:50.783   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 09:17:50.845   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 09:17:50.847  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 09:17:50.894  3796  4236 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 09:17:50.895  3796  4233 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 09:17:50.895  3796  4236 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 09:17:50.895  3796  4233 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 09:17:50.896  3796  4236 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:17:50.896  3796  4233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:17:50.898  3796  4236 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 09:17:50.898  3796  4233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 09:17:50.899  3796  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: OutgoingSocketThread/Sender)
,09-13 09:17:50.901  3796  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: IncomingSocketThread/Sender)
,09-13 09:17:50.902  3796  4233 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 09:17:50.902  3796  4236 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 09:17:50.903  3796  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 490, name: OutgoingSocketThread/Receiver)
09-13 09:17:50.904  3796  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 490, thread name: OutgoingSocketThread/Receiver)
,09-13 09:17:50.904  3796  4241 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 09:17:50.905  3796  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 490, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 09:17:50.908  3796  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 489, name: IncomingSocketThread/Receiver)
,09-13 09:17:50.909  3796  4242 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 489, thread name: IncomingSocketThread/Receiver)
,09-13 09:17:50.909  3796  4242 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 09:17:50.910  3796  4242 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 489, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 09:17:51.278  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 09:17:51.350  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 09:17:51.352  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 09:17:51.359   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 09:17:51.374   874  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 09:17:51.374   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 09:17:51.375   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:51.393   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 09:17:51.399  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 09:17:51.402   374   872 D CommandListener: Setting iface cfg
,09-13 09:17:51.403  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 09:17:51.406   874  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 09:17:51.408  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9362683 Bundle[{}]
,09-13 09:17:51.409  3796  3847 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 09:17:51.409  3796  3847 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 09:17:51.410  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 09:17:51.410  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 09:17:51.411  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 09:17:51.412  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 09:17:51.420   874  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-13 09:17:51.420  3796  4245 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 09:17:51.422   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 09:17:51.423  3796  4245 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 09:17:51.442   874  4247 D DhcpClient: Receive thread started
,09-13 09:17:51.526   874  1310 E native  : do suspend false
,09-13 09:17:51.549   874  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 09:17:51.597   874  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,09-13 09:17:51.600   874  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds,
09-13 09:17:51.604   874  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 09:17:51.637   874  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 09:17:51.638   874  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 09:17:51.644   374   872 D CommandListener: Setting iface cfg
,09-13 09:17:51.656   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 09:17:51.656   874  1887 D DhcpClient: Scheduling renewal in 86399s
,09-13 09:17:51.668   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 09:17:51.670   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 09:17:51.670   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 09:17:51.671   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 09:17:51.672   874  1312 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 09:17:51.677   874  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 09:17:51.747   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 09:17:51.747   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 09:17:51.751   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 09:17:51.754   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 09:17:51.757   874  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 09:17:51.767   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 09:17:51.772   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-13 09:17:51.772   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-13 09:17:51.772   874  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 09:17:51.773   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 09:17:51.773   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 09:17:51.773   874  1312 D ConnectivityService:    accepting network in place of null
,09-13 09:17:51.775   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 09:17:51.791   874  4244 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138107, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:17:51.804   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:51.843   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 09:17:51.848   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 09:17:51.849   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:17:51.855   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 09:17:51.857   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:51.869  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:51.873  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:51.879  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:51.882  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:51.882   874  4243 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:816::200e
,09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:51.888  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:51.891  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:51.905  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 09:17:51.910  1744  1744 D SystemUpdateService: onCreate
,09-13 09:17:51.915  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 09:17:51.924  3796  4258 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 09:17:51.924  3796  4258 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 09:17:51.925  3796  4258 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:17:51.925  3796  4258 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 09:17:51.925  3796  4245 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 09:17:51.925  3796  4258 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 09:17:51.925  3796  4245 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 09:17:51.926  3796  4262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: IncomingSocketThread/Sender),
,09-13 09:17:51.926  3796  4263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 502, name: IncomingSocketThread/Receiver)
,09-13 09:17:51.927  3796  4263 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 502, thread name: IncomingSocketThread/Receiver)
09-13 09:17:51.927  3796  4263 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 09:17:51.927  3796  4263 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 502, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 09:17:51.928  3796  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:17:51.929  3796  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 09:17:51.930  3796  4245 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 09:17:51.930  3796  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 503, name: OutgoingSocketThread/Sender)
09-13 09:17:51.931  3796  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 504, name: OutgoingSocketThread/Receiver)
09-13 09:17:51.931  3796  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 504, thread name: OutgoingSocketThread/Receiver)
09-13 09:17:51.931  3796  4266 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 09:17:51.931  3796  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 504, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 09:17:51.955  1744  4257 I SystemUpdateService: active receiver: enabled
,09-13 09:17:51.958  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 09:17:51.960  1744  2462 I iu.UploadsManager: num queued entries: 0
,09-13 09:17:51.960  1744  2462 I iu.UploadsManager: num updated entries: 0
,09-13 09:17:51.964   874  4243 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:17:51 GMT], X-Android-Received-Millis=[1473751071962], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473751071932]}
,09-13 09:17:51.965   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 09:17:51.965   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-13 09:17:51.965   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 09:17:51.967   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 09:17:51.972  1744  4257 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 09:17:51.976  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 09:17:51.977  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 09:17:51.979  3888  3888 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-13 09:17:51.984  1744  4269 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 09:17:51.984  1744  4269 W BaseAppContext: Using Auth Proxy for data requests.
09-13 09:17:51.987  1744  4269 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 09:17:51.988  3888  3888 D SprintDMHelper: simOperator: 
,09-13 09:17:51.988  3888  3888 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 09:17:52.020  1744  2462 I iu.SyncManager: NEXT; no task
09-13 09:17:52.020  1744  4257 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 09:17:52.020  1744  4257 I SystemUpdateService: now status is 0 (complete)
,09-13 09:17:52.021  1744  4257 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 09:17:52.021  1744  4257 I SystemUpdateService: file has been verified
,09-13 09:17:52.021  1744  4257 I SystemUpdateService: OTA package size = 12249756
,09-13 09:17:52.045  1744  4257 I SystemUpdateService: showing system update notification
,09-13 09:17:52.046  1523  2289 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-13 09:17:52.046  1523  2289 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 09:17:52.046  1523  2289 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:52.047  1523  2289 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:52.058  4010  4267 V KeepSync: Connecting to GoogleApiClient
,09-13 09:17:52.062   874  1954 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 09:17:52.072   874  1312 D ConnectivityService: handlePromptUnvalidated 101
,09-13 09:17:52.077  1744  1744 D SystemUpdateService: onDestroy
,09-13 09:17:52.098  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 09:17:52.098  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 09:17:52.099  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:52.099  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:52.101  1744  4269 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-13 09:17:52.118  3006  4270 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 09:17:52.118  3006  4270 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jdm.a(PG:82)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jcs.o(PG:406)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jcn.a(PG:1379)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jcs.i(PG:143)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at blb.a(PG:3937)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at czp.a(PG:18188)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at czp.a(PG:9081)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at czq.run(PG:1686)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 09:17:52.118  3006  4270 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jdj.a(PG:4091)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jdj.a(PG:1125)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jdm.a(PG:77)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	... 12 more
09-13 09:17:52.118  3006  4270 E HttpOperation: Caused by: faj: BadAuthentication
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at fal.a(PG:38)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	at jdj.a(PG:4089)
09-13 09:17:52.118  3006  4270 E HttpOperation: 	... 14 more
,09-13 09:17:52.155  1523  2999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 09:17:52.155  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 09:17:52.155  1523  2999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 09:17:52.155  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 09:17:52.155  1523  2999 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:52.155  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:17:52.155  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 09:17:52.155  1523  2999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:52.167  3089  4273 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 09:17:52.176  3006  4270 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 09:17:52.176  3006  4270 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jdm.a(PG:82)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jcs.o(PG:406)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jcn.a(PG:1379)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jcs.i(PG:143)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at hec.a(PG:42)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at hee.a(PG:102)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at czr.a(PG:65)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at kka.a(PG:108)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at czp.a(PG:19176)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at czp.a(PG:9081)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at czq.run(PG:1686)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 09:17:52.176  3006  4270 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jdj.a(PG:4091)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jdj.a(PG:1125)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jdm.a(PG:77)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	... 15 more
09-13 09:17:52.176  3006  4270 E HttpOperation: Caused by: faj: BadAuthentication
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at fal.a(PG:38)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	at jdj.a(PG:4089)
09-13 09:17:52.176  3006  4270 E HttpOperation: 	... 17 more
,09-13 09:17:52.176  3006  4270 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 09:17:52.176  3006  4270 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at hec.a(PG:42)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at hee.a(PG:102)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at czr.a(PG:65)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at kka.a(PG:108)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	... 15 more
09-13 09:17:52.176  3006  4270 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at fal.a(PG:38)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 09:17:52.176  3006  4270 E ExperimentLoader: 	... 17 more
,09-13 09:17:52.178  1744  4278 V BaseAuthAsyncOperation: access token request failed
,09-13 09:17:52.182  4010  4267 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 09:17:52.278   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 132415, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 09:17:52.334  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 09:17:52.335  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 09:17:52.335  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:17:52.335  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:17:52.366  4010  4267 E KeepSync: IOException
09-13 09:17:52.366  4010  4267 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 09:17:52.366  4010  4267 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 09:17:52.366  4010  4267 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 09:17:52.366  4010  4267 E KeepSync: 	... 10 more
09-13 09:17:52.366  4010  4267 W KeepSync: Sync result 2
,09-13 09:17:52.369   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132058, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 09:17:52.427  3796  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 513)
,09-13 09:17:52.428  3796  3847 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 09:17:52.428  3796  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 514)
,09-13 09:17:52.430  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 09:17:52.431  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@922956d added. We now have 5 listener(s)
,09-13 09:17:52.434  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:52.434  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 09:17:52.434  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:17:52.434  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 09:17:52.434  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f05a2 added. We now have 5 listener(s)
09-13 09:17:52.435  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 09:17:52.435  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 09:17:52.437  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:17:52.441  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:17:52.443  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:17:52.443  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:17:52.445  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:52.445  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:52.445  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:17:52.445  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 09:17:52.446  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@922956d removed from the list
,09-13 09:17:52.446  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:52.446  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f05a2 removed from the list
09-13 09:17:52.446  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:52.447  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:52.447  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:17:52.447  3796  3847 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-13 09:17:52.447  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 09:17:52.448  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:52.448  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 09:17:52.448  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 09:17:52.448  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:52.448  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:17:52.449  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 09:17:52.449  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 09:17:52.449  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 09:17:52.449  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 09:17:52.449  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:52.449  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:17:52.458  3796  4282 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:52.460  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 09:17:52.460  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 09:17:52.462  3796  4282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 09:17:52.460  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:17:52.464  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 09:17:52.464  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:17:52.464  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:52.464  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 09:17:52.466  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 09:17:52.466  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:52.466  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-13 09:17:52.466  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:52.466  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:52.466  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 09:17:52.467  3796  3847 D BluetoothAdapter: STATE_ON
09-13 09:17:52.470  4167  4203 D BtGatt.GattService: registerClient() - UUID=30f9d6b7-5c32-4132-b726-1e5f6c89a09c
,09-13 09:17:52.471  4167  4183 D BtGatt.GattService: onClientRegistered() - UUID=30f9d6b7-5c32-4132-b726-1e5f6c89a09c, clientIf=5
,09-13 09:17:52.472  3796  3807 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 09:17:52.473  4167  4185 D BtGatt.AdvertiseManager: message : 0
09-13 09:17:52.476  4167  4185 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 09:17:52.484  4167  4183 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 09:17:52.490  4167  4183 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 09:17:52.490  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 09:17:52.491  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 09:17:52.492  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:52.493  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:52.493  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 09:17:52.493  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 09:17:52.493  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 09:17:52.493  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 09:17:52.494  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 09:17:52.496  3796  3796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:52.496  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:52.849   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 09:17:52.997  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 09:17:52.997  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 09:17:52.998  3796  3796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 09:17:54.443   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 09:17:55.997  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 09:17:55.997  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 09:17:55.997  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 09:17:55.998  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:17:55.998  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 09:17:56.000  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:17:56.001  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:17:56.001  3796  4282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 09:17:56.001  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:17:56.001  3796  4282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 09:17:56.002  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 09:17:56.002  3796  4282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 09:17:56.002  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 09:17:56.002  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 09:17:56.003  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:56.003  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 09:17:56.006  3796  3847 D BluetoothAdapter: STATE_ON
09-13 09:17:56.006  3796  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 09:17:56.007  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:17:56.007  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 09:17:56.009  4167  4185 D BtGatt.AdvertiseManager: message : 1
09-13 09:17:56.011  4167  4185 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 09:17:56.020  4167  4183 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 09:17:56.021  4167  4183 D BtGatt.GattService: Client app is not null!
,09-13 09:17:56.022  4167  4206 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 09:17:56.023  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 09:17:56.023  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 09:17:56.023  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 09:17:56.023  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 09:17:56.024  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 09:17:56.025  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:17:56.025  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:17:56.026  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 09:17:56.027  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:56.030  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 09:17:56.030  3796  3796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 09:17:56.030  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 09:17:56.031  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:17:56.031  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:56.031  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:56.036  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:56.036  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:56.036  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:56.037  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@922956d not in the list
09-13 09:17:56.037  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:17:56.037  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f05a2 not in the list
09-13 09:17:56.037  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:17:56.038  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:56.038  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:56.040  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 09:17:56.041  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 09:17:56.041  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 09:17:56.041  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 09:17:56.041  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:56.041  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 09:17:56.045  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 09:17:56.045  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 09:17:56.050  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 09:17:56.052  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:56.052  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 09:17:56.059  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 09:17:56.060  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 09:17:56.061  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 09:17:56.063  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:56.067  4167  4178 D BtGatt.GattService: registerClient() - UUID=226f2ff7-bd0b-4ec1-a421-f4addccfe071
,09-13 09:17:56.068  4167  4183 D BtGatt.GattService: onClientRegistered() - UUID=226f2ff7-bd0b-4ec1-a421-f4addccfe071, clientIf=5
,09-13 09:17:56.069  3796  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 09:17:56.071  4167  4177 D BtGatt.GattService: start scan with filters
,09-13 09:17:56.075  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 09:17:56.076  4167  4186 D BtGatt.ScanManager: handling starting scan
,09-13 09:17:56.076  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 09:17:56.077  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 09:17:56.077  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 09:17:56.079  4167  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1242e7
,09-13 09:17:56.089  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 09:17:56.090  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 09:17:56.090  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 09:17:56.091  4167  4183 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 09:17:56.091  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 09:17:56.092  4167  4186 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 09:17:56.097  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:56.105  4167  4183 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 09:17:56.105  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 09:17:56.106  4167  4186 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 09:17:56.107  4167  4186 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 09:17:56.137  4167  4183 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 09:17:56.137  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 09:17:56.155  4167  4183 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
09-13 09:17:56.155  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 09:17:56.241   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-13 09:17:56.591  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 09:17:56.592  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 09:17:56.592  3796  3796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 09:17:57.094   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 13 -> obsolete
,09-13 09:17:57.659  4167  4167 D BtGatt.ScanManager: awakened up at time 143975
,09-13 09:17:57.662  4167  4186 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 09:17:57.686  4167  4183 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-13 09:17:57.686  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 09:17:57.686  4167  4183 D BtGatt.GattService: current time is 144003714722
09-13 09:17:57.687  4167  4183 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -96, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -93, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 09:17:57.688  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 09:17:57.689  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 09:17:57.690  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 09:17:57.690  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 09:17:57.690  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 09:17:59.103  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:17:59.103  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:17:59.104  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 09:17:59.104  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@922956d not in the list
09-13 09:17:59.104  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:17:59.105  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 09:17:59.105  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 09:17:59.105  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:17:59.106  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 09:17:59.106  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 09:17:59.109  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:59.111  4167  4177 D BtGatt.GattService: stopScan() - queue size =1
09-13 09:17:59.113  4167  4203 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 09:17:59.115  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:17:59.115  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 09:17:59.115  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 09:17:59.117  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 09:17:59.117  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 09:17:59.121  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:59.122  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 09:17:59.122  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:17:59.123  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:17:59.125  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:59.127  4167  4167 D BtGatt.ScanManager: awakened up at time 145443
09-13 09:17:59.129  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:17:59.130  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:17:59.130  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:17:59.129  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f05a2 not in the list
,09-13 09:17:59.132  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:17:59.132  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:17:59.134  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:17:59.136  4167  4183 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 09:17:59.136  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 09:17:59.137  4167  4186 D BtGatt.ScanManager: stopping BLe Batch
,09-13 09:17:59.140  3796  3847 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 09:17:59.140  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 09:17:59.142  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:59.144  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 09:17:59.144  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 09:17:59.144  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:17:59.146  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:17:59.146  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 09:17:59.146  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 09:17:59.146  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 09:17:59.146  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 09:17:59.146  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:17:59.147  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:17:59.148  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 09:17:59.153  3796  4286 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 09:17:59.155  4167  4183 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 09:17:59.155  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 09:17:59.156  4167  4186 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 09:17:59.157  3796  4286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 09:17:59.157  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 09:17:59.157  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 09:17:59.162  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 09:17:59.163  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 09:17:59.163  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 09:17:59.166  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 09:17:59.167  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 09:17:59.168  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
,09-13 09:17:59.168  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:59.168  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 09:17:59.168  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 09:17:59.170  3796  3847 D BluetoothAdapter: STATE_ON
,09-13 09:17:59.174  4167  4177 D BtGatt.GattService: registerClient() - UUID=8ea86cd4-21a0-4d33-9f05-e344f7909a41
,09-13 09:17:59.174  4167  4183 D BtGatt.GattService: onClientRegistered() - UUID=8ea86cd4-21a0-4d33-9f05-e344f7909a41, clientIf=5
,09-13 09:17:59.175  3796  3843 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 09:17:59.177  4167  4185 D BtGatt.AdvertiseManager: message : 0
,09-13 09:17:59.179  4167  4183 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-13 09:17:59.179  4167  4183 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 09:17:59.179  4167  4183 D BtGatt.GattService: current time is 145496584729
09-13 09:17:59.180  4167  4183 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -87, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112],
09-13 09:17:59.180  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 09:17:59.180  4167  4183 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 09:17:59.181  4167  4185 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 09:17:59.198  4167  4183 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 09:17:59.208  4167  4183 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 09:17:59.209  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 09:17:59.209  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 09:17:59.210  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 09:17:59.212  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 09:17:59.213  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
09-13 09:17:59.213  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 09:17:59.213  3796  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 09:17:59.214  3796  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 09:17:59.214  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 09:17:59.221  3796  3796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:59.221  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 09:17:59.722  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 09:17:59.723  3796  3796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 09:17:59.723  3796  3796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 09:17:59.777   874  1312 D ConnectivityService: handlePromptUnvalidated 102
,09-13 09:18:02.716  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:18:02.717  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 09:18:02.717  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 09:18:02.717  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 09:18:02.718  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 09:18:02.718  3796  4286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 09:18:02.718  3796  4286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:18:02.718  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:18:02.719  3796  4286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 09:18:02.719  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@922956d not in the list
,09-13 09:18:02.719  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:18:02.719  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 09:18:02.720  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 09:18:02.720  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:18:02.720  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 09:18:02.720  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:18:02.721  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 09:18:02.723  3796  3847 D BluetoothAdapter: STATE_ON
09-13 09:18:02.723  3796  3847 D BluetoothLeScanner: could not find callback wrapper
,09-13 09:18:02.724  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:18:02.724  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 09:18:02.726  4167  4185 D BtGatt.AdvertiseManager: message : 1
09-13 09:18:02.727  4167  4185 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 09:18:02.737  4167  4183 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 09:18:02.737  4167  4183 D BtGatt.GattService: Client app is not null!
,09-13 09:18:02.738  4167  4194 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 09:18:02.739  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 09:18:02.739  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 09:18:02.740  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 09:18:02.740  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 09:18:02.740  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 09:18:02.742  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:18:02.743  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:18:02.743  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 09:18:02.744  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:02.747  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 09:18:02.747  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:18:02.747  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 09:18:02.748  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f05a2 not in the list
09-13 09:18:02.748  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:02.748  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 09:18:02.749  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:02.751  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:18:02.751  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:02.751  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:02.752  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@922956d not in the list
,09-13 09:18:02.752  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:02.752  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f05a2 not in the list
09-13 09:18:02.752  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:18:02.753  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:02.753  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:02.755  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 09:18:02.755  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 09:18:02.756  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 09:18:02.757  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:02.757  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 09:18:02.757  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 09:18:02.764  3796  4288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 534, name: My test thread name)
,09-13 09:18:03.248  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 09:18:04.053   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,09-13 09:18:04.764  3796  3847 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 534
,09-13 09:18:04.764  3796  3847 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 534, name: My test thread name)
,09-13 09:18:04.771  3796  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 535, name: My test thread name)
,09-13 09:18:04.771  3796  4290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 535, thread name: My test thread name)
09-13 09:18:04.772  3796  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 535, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 09:18:04.776  3796  3847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 09:18:04.785  3796  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 539, name: My test thread name)
,09-13 09:18:04.786  3796  4291 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 539, thread name: My test thread name): Test exception.
09-13 09:18:04.786  3796  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 539, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 09:18:04.793  3796  3847 I jxcore-log: Total number of executed tests:  82
09-13 09:18:04.793  3796  3847 I jxcore-log: 
,09-13 09:18:04.795  3796  3847 I jxcore-log: Number of passed tests:  82
09-13 09:18:04.795  3796  3847 I jxcore-log: 
,09-13 09:18:04.795  3796  3847 I jxcore-log: Number of failed tests:  0
09-13 09:18:04.795  3796  3847 I jxcore-log: 
,09-13 09:18:04.798  3796  3847 I jxcore-log: Number of ignored tests:  0
09-13 09:18:04.798  3796  3847 I jxcore-log: 
09-13 09:18:04.798  3796  3847 I jxcore-log: Total duration:  26465
09-13 09:18:04.798  3796  3847 I jxcore-log: 
,09-13 09:18:04.805  3796  3847 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 09:18:04.805  3796  3847 I jxcore-log: 
,09-13 09:18:04.809  3796  3847 I jxcore-log: My device name is: motorola-Nexus 6
09-13 09:18:04.809  3796  3847 I jxcore-log: 
09-13 09:18:04.818  3796  3847 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 09:18:04.818  3796  3847 I jxcore-log: 
,09-13 09:18:04.829  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.829  3796  3847 I jxcore-log: 
,09-13 09:18:04.833  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.833  3796  3847 I jxcore-log: 
,09-13 09:18:04.838  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.838  3796  3847 I jxcore-log: 
,09-13 09:18:04.845  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.845  3796  3847 I jxcore-log: 
,09-13 09:18:04.851  3796  4288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 534, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-13 09:18:04.856  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 09:18:04.856  3796  3847 I jxcore-log: 
,09-13 09:18:04.860  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.860  3796  3847 I jxcore-log: 
,09-13 09:18:04.861  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 09:18:04.861  3796  3847 I jxcore-log: 
,09-13 09:18:04.863  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.863  3796  3847 I jxcore-log: 
,09-13 09:18:04.865  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 09:18:04.865  3796  3847 I jxcore-log: 
,09-13 09:18:04.867  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.867  3796  3847 I jxcore-log: 
,09-13 09:18:04.868  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.868  3796  3847 I jxcore-log: 
,09-13 09:18:04.869  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.869  3796  3847 I jxcore-log: 
,09-13 09:18:04.871  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.871  3796  3847 I jxcore-log: 
,09-13 09:18:04.873  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.873  3796  3847 I jxcore-log: 
,09-13 09:18:04.874  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.874  3796  3847 I jxcore-log: 
,09-13 09:18:04.876  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 09:18:04.876  3796  3847 I jxcore-log: 
,09-13 09:18:04.878  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.878  3796  3847 I jxcore-log: 
,09-13 09:18:04.880  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.880  3796  3847 I jxcore-log: 
,09-13 09:18:04.883  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.883  3796  3847 I jxcore-log: 
,09-13 09:18:04.885  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.885  3796  3847 I jxcore-log: 
,09-13 09:18:04.887  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.887  3796  3847 I jxcore-log: 
,09-13 09:18:04.890  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.890  3796  3847 I jxcore-log: 
,09-13 09:18:04.891  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.891  3796  3847 I jxcore-log: 
,09-13 09:18:04.893  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.893  3796  3847 I jxcore-log: 
,09-13 09:18:04.894  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.894  3796  3847 I jxcore-log: 
,09-13 09:18:04.895  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.895  3796  3847 I jxcore-log: 
,09-13 09:18:04.897  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.897  3796  3847 I jxcore-log: 
,09-13 09:18:04.898  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.898  3796  3847 I jxcore-log: 
,09-13 09:18:04.902  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.902  3796  3847 I jxcore-log: 
,09-13 09:18:04.907  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.907  3796  3847 I jxcore-log: 
,09-13 09:18:04.908  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.908  3796  3847 I jxcore-log: 
09-13 09:18:04.909  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.909  3796  3847 I jxcore-log: 
,09-13 09:18:04.909  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.909  3796  3847 I jxcore-log: 
09-13 09:18:04.910  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.910  3796  3847 I jxcore-log: 
,09-13 09:18:04.911  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.911  3796  3847 I jxcore-log: 
,09-13 09:18:04.913  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.913  3796  3847 I jxcore-log: 
,09-13 09:18:04.914  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.914  3796  3847 I jxcore-log: 
09-13 09:18:04.914  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.914  3796  3847 I jxcore-log: 
,09-13 09:18:04.915  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.915  3796  3847 I jxcore-log: 
,09-13 09:18:04.918   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 09:18:04.920  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.920  3796  3847 I jxcore-log: 
,09-13 09:18:04.922  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.922  3796  3847 I jxcore-log: 
,09-13 09:18:04.922  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.922  3796  3847 I jxcore-log: 
,09-13 09:18:04.924  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:18:04.924  3796  3847 I jxcore-log: 
,09-13 09:18:04.924  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.924  3796  3847 I jxcore-log: 
,09-13 09:18:04.926  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.926  3796  3847 I jxcore-log: 
,09-13 09:18:04.927  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.927  3796  3847 I jxcore-log: 
,09-13 09:18:04.928  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:18:04.928  3796  3847 I jxcore-log: 
,09-13 09:18:04.928  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.928  3796  3847 I jxcore-log: 
09-13 09:18:04.929  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.929  3796  3847 I jxcore-log: 
,09-13 09:18:04.929  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.929  3796  3847 I jxcore-log: 
09-13 09:18:04.930  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:04.930  3796  3847 I jxcore-log: 
,09-13 09:18:04.931  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 09:18:04.931  3796  3847 I jxcore-log: 
,09-13 09:18:04.932  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 09:18:04.932  3796  3847 I jxcore-log: 
09-13 09:18:04.932  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 09:18:04.932  3796  3847 I jxcore-log: 
,09-13 09:18:04.934  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 09:18:04.934  3796  3847 I jxcore-log: 
,09-13 09:18:05.434  4292  4292 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 09:18:05.438  4292  4292 D AndroidRuntime: CheckJNI is OFF
,09-13 09:18:05.481  4292  4292 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 09:18:05.527  4292  4292 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 09:18:05.548  4292  4292 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 09:18:05.557   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 09:18:05.558   874   887 I ActivityManager: Killing 3796:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 09:18:05.667   874   899 W PackageSettings: Skipping PackageSetting{26b1538 com.example.hello/10273} due to missing metadata
,09-13 09:18:05.693   874  1981 I WindowState: WIN DEATH: Window{fb61e7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 09:18:05.694   874  1311 D WifiService: Client connection lost with reason: 4
,09-13 09:18:05.694   874  1942 D GraphicsStats: Buffer count: 2
,09-13 09:18:05.725   874   899 I art     : Starting a blocking GC Explicit
,09-13 09:18:05.741   874   887 W ActivityManager: Force removing ActivityRecord{77c3fd3 u0 com.test.thalitest/.MainActivity t4}: app died, no saved state
,09-13 09:18:05.748   874  1974 W ActivityManager: Spurious death for ProcessRecord{336446b 0:com.test.thalitest/u0a0}, curProc for 3796: null
,09-13 09:18:05.783   874   899 I art     : Explicit concurrent mark sweep GC freed 32055(1983KB) AllocSpace objects, 9(220KB) LOS objects, 33% free, 29MB/43MB, paused 783us total 57.555ms
,09-13 09:18:05.789   874  1384 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3796 uid 10000
,09-13 09:18:05.791  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-13 09:18:05.847  2025  4305 I MicroRecognitionRnrImpl: Starting detection.
,09-13 09:18:05.848  2025  4306 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@6825bed
,09-13 09:18:05.851   378  4308 I AudioFlinger: AudioFlinger's thread 0xb3380000 ready to run
,09-13 09:18:05.853   378  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 09:18:05.853   874   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-13 09:18:05.854  2025  4306 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@6825bed
09-13 09:18:05.857  4292  4292 I art     : System.exit called, status: 0
09-13 09:18:05.857  4292  4292 I AndroidRuntime: VM exiting with result code 0.
09-13 09:18:05.864   378  4308 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,09-13 09:18:05.864   378  4308 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
09-13 09:18:05.864   378  4308 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,09-13 09:18:05.871   378  4308 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-13 09:18:05.872   874   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 09:18:05.889  4167  4167 D BluetoothMapAppObserver: onReceive
,09-13 09:18:05.889  4167  4167 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-13 09:18:05.891   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 09:18:05.893  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 09:18:05.893  2076  2297 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 09:18:05.897  1871  4311 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 09:18:05.900  3648  3648 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 09:18:05.904  1871  4311 I Decoder : createOrResetDecoder
,09-13 09:18:05.917  1932  1932 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 09:18:05.923   874   885 I ActivityManager: Start proc 4315:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 09:18:05.956  2025  2025 I HotwordWorkerImpl: onReady
,09-13 09:18:05.969  1523  1523 I ConfigService: onCreate
,09-13 09:18:05.976  4315  4315 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 09:18:05.984   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 09:18:05.987  1871  4311 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 09:18:06.012  1871  4311 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 09:18:06.015  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-13 09:18:06.015  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 09:18:06.017  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 09:18:06.017  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-13 09:18:06.018  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-13 09:18:06.019  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-13 09:18:06.019  1947  2066 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-13 09:18:06.020   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 09:18:06.020  1871  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 09:18:06.020  1871  4311 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 09:18:06.020  1871  4311 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 09:18:06.020   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 09:18:06.020   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 09:18:06.020   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 09:18:06.020   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 09:18:06.020   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 09:18:06.020   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 09:18:06.020   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:06.020   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.020   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:18:06.020  1871  4311 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 09:18:06.020  1871  4311 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-13 09:18:06.020  1871  4311 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 09:18:06.026   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 09:18:06.026   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	,at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 09:18:06.026   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:18:06.026   874   887 E DropBoxManagerService: 	... 13 more
,09-13 09:18:06.031   874  1955 I ActivityManager: Start proc 4331:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-13 09:18:06.032  1947  2066 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 09:18:06.032  1947  2066 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1947
09-13 09:18:06.032  1947  2066 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.032  1947  2066 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 09:18:06.034   874   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 09:18:06.034   874  4338 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:18:06.034   874  4338 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:18:06.034   874  4338 E DropBoxManagerService: 	... 5 more
,09-13 09:18:06.037  2025  2404 W SearchService: Abort, client detached.
,09-13 09:18:06.039  2025  2025 I HotwordDetector: Closing mic
,09-13 09:18:06.039  2025  2349 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6825bed
09-13 09:18:06.040  2025  4306 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-13 09:18:06.048   874  4345 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 09:18:06.071  4315  4315 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 09:18:06.081   874  4345 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 09:18:06.081   874  4345 I Adreno  : Build Date                       : 10/20/15
09-13 09:18:06.081   874  4345 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 09:18:06.081   874  4345 I Adreno  : Local Branch                     : M14
09-13 09:18:06.081   874  4345 I Adreno  : Remote Branch                    : 
09-13 09:18:06.081   874  4345 I Adreno  : Remote Branch                    : 
09-13 09:18:06.081   874  4345 I Adreno  : Reconstruct Branch               : 
,09-13 09:18:06.074  4315  4330 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.074  4315  4330 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.084  4315  4330 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 09:18:06.086   874  4345 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 09:18:06.086  4315  4346 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 09:18:06.092   874  1972 I ActivityManager: Start proc 4347:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 09:18:06.099   378  4308 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-13 09:18:06.103   378  4308 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,09-13 09:18:06.107   378  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-13 09:18:06.108  2025  4305 I MicroRecognitionRnrImpl: Detection finished
09-13 09:18:06.109  2025  2358 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-13 09:18:06.137  4347  4347 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 09:18:06.152  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-13 09:18:06.152  1523  1523 D AndroidRuntime: Shutting down VM
09-13 09:18:06.153  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
09-13 09:18:06.153  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
09-13 09:18:06.153  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 09:18:06.153  1523  1523 E AndroidRuntime: 	... 8 more
,09-13 09:18:06.157   874  4366 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:18:06.157   874  4366 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:18:06.157   874  4366 E DropBoxManagerService: 	... 5 more
,09-13 09:18:06.181  1744  4367 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-13 09:18:06.181  1744  4367 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-13 09:18:06.200  4315  4330 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-13 09:18:06.205  4315  4346 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.205  4315  4346 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 09:18:06.206  4315  4346 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 09:18:06.206  4315  4346 E AndroidRuntime: Process: android.process.acore, PID: 4315
09-13 09:18:06.206  4315  4346 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:18:06.206  4315  4346 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 09:18:06.207  4315  4330 I Process : Sending signal. PID: 4315 SIG: 9
,09-13 09:18:06.215   874  4369 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:18:06.215   874  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:18:06.215   874  4369 E DropBoxManagerService: 	... 5 more
,09-13 09:18:06.245   874  1384 I ActivityManager: Process android.process.acore (pid 4315) has died
,09-13 09:18:06.246   874  1384 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-13 09:18:06.422   282   282 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
09-13 09:18:06.423   282   282 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,09-13 09:18:06.423   282   282 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
09-13 09:18:06.423   282   282 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
09-13 09:18:06.423   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
09-13 09:18:06.423   282   282 E qdoverlay: MdpCtrl close error in unset
,09-13 09:18:06.701   282   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 09:18:06.702   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,09-13 09:18:06.702   282   282 E qdoverlay: MdpCtrl close error in unset

```
